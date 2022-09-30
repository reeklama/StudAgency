<script>

    let surname;
    let name;
    let mail;
    let phone;
    let discipline;
    let task;
    let files;

    const formData = new FormData();

    $: if (files) {
        // Note that `files` is of type `FileList`, not an Array:
        // https://developer.mozilla.org/en-US/docs/Web/API/FileList
        console.log(files);

        // files.forEach((file) => formData.append("files", file));

        for (const file of files) {
            formData.append('files', file);
        }

    }


    const endpoint = "http://localhost:8080/student";
    let data;




    const go = async () => {
        if  (surname !== undefined &&
            name !== undefined &&
            mail !== undefined &&
            phone !== undefined &&
            discipline !== undefined &&
            task !== undefined) {

            formData.append('surname', surname);
            formData.append('name', name);
            formData.append('mail', mail);
            formData.append('phone', phone);
            formData.append('discipline', discipline);
            formData.append('task', task);


            const response = await fetch(endpoint, {
                method: 'POST',
                body: formData,
            })
            data = await response.text();
            alert(data);
            window.location.href = '/';
        }
        else {
            alert('Введите недостающие данные')
        }
    }



</script>

<svelte:head>
    <title>Home</title>
    <meta name="description" content="Svelte demo app" />

</svelte:head>


<main>
    <p class="in shrift">
        Заполните заявку и наш менеджер свяжется с Вами в ближайшее время
    </p>
    <form  on:submit|preventDefault={go}>
    <div class="in1">
        <p class="shrift1">Заявка</p>
        <table>
            <tr>
                <td><p class="shrift2">Фамилия</p></td>
                <td><p class="vvod puput"><input type="text" placeholder="Иванов" bind:value={surname}></p></td>
                <td><p class="shrift2">Имя</p></td>
                <td><p class="vvod"><input type="text" placeholder="Иван" bind:value={name}></p></td>
            </tr>
            <tr>
                <td><p class="shrift2">Почта</p></td>
                <td><p class="vvod"><input type="email" placeholder="name@gmail.com" bind:value={mail}></p></td>
                <td><p class="shrift2">Телефон</p></td>
                <td><p class="vvod"><input type="text"  placeholder="+79612249944" bind:value={phone}></p></td>
            </tr>
        </table>

        <div class="ww">
            <p class="shrift3 unde">Дисциплина</p>
            <p><input type="text" size="40" placeholder="Юриспруденция" id="discipline" bind:value={discipline}></p>
        </div>
        <div class="ww">
            <p class="shrift3 unde">Описание задачи</p>
            <p><textarea cols="76" rows="8" placeholder="Привидите краткое описание задачи (тип работы, сроки, ВУЗ, тема, кол-во страниц и др.)" id="task" bind:value={task}></textarea></p>
        </div>
        <div class="ww">
            <p class="shrift3 unde">Прикрепите файлы</p>
            <p><input type="file" multiple="multiple" bind:files></p>
        </div>
        <div class="shrift3">
            <p><input class="subbut" type="submit"></p>
        </div>
    </div>
    </form>

</main>


<style>
    .unde{
        display: inline-block;
        border-bottom: 3px solid #000;
        margin-bottom: -10px;
    }

    .subbut{
        transition: 0.5s; /* Время эффекта */
        background-color: #A72828;
        border: none;
        border-radius: 10px;
        padding: 6px 18px 6px 18px;
        color: white;
        font-family: Gill Sans, sans-serif;
    }

    .subbut:hover {
        transform: scale(1.1); /* Увеличиваем масштаб */
    }

    .ww{
        margin-top: -15px;
    }

    table{
        margin-top: -30px;
    }

    td{
        padding-left: 10px;
    }

    .puput{
        width:200px;
    }


    .vvod{
        padding-left: 8px;
    }

    html {
        background-repeat: no-repeat;
        background-position: center center;
        background-attachment: fixed;
        -webkit-background-size: cover;
        -moz-background-size: cover;
        -o-background-size: cover;
        background-size: cover;
    }

    .flex{
        display: flex;
        justify-content: space-between;
    }

    section {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        flex: 1;
        background-image: image('../../lib/fon.jpg')
    }

    .in{
        margin-left: auto;
        margin-right: auto;
        background-color: white;
        text-align: center;
        margin-top: 0;
        width: 700px;
        border-radius: 30px;
        box-shadow: 1px 4.62px 18.1px #8b8b8b;
    }


    .shrift{
        font-size: 32px;
        font-family: Gill Sans, sans-serif;
        letter-spacing: -1px;
        font-style: italic;
        text-align: center;
        padding-top: 20px;
        padding-bottom: 20px;
        color: black;
    }

    .in1{
        background: white;
        text-align: center;
        padding: 5px;
        margin: 20px;
        border-radius: 30px;
        box-shadow: 1px 4.62px 18.1px #8b8b8b;
    }

    .shrift3{
        font-size: 24px;
        font-family: Gill Sans, sans-serif;
        letter-spacing: -1px;
        font-style: italic;
        text-align: center;

        color: black;
    }

    .shrift2{
        font-size: 20px;
        font-family: Gill Sans, sans-serif;
        letter-spacing: -1px;
        font-style: italic;
        text-align: center;
        text-decoration: underline;
        color: black;
        padding-left: 100px;
    }

    .shrift1{
        font-size: 30px;
        font-family: Gill Sans, sans-serif;
        letter-spacing: -1px;
        font-style: italic;
        text-align: center;
        color: black;
    }




    h1 {
        width: 100%;
    }

    .welcome {
        display: block;
        position: relative;
        width: 100%;
        height: 0;
        padding: 0 0 calc(100% * 495 / 2048) 0;
    }

    .welcome img {
        position: absolute;
        width: 100%;
        height: 100%;
        top: 0;
        display: block;
    }
</style>
