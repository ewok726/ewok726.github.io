<!DOCTYPE html>
<html>
<head>
    <meta charset= "utf-8">
    <title>Nightmare | Homepage</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=IM+Fell+Double+Pica+SC&display=swap');
        body {
            min-height: 100vh;
            color: lightyellow;
            font-family: georgia;
            background-image: linear-gradient(rgba(43, 56, 94, 0.3), rgba(63, 82, 137, 0.5), rgba(86, 149, 152, 0.7), rgba(200, 225, 223, 0.9), #FFF), url("https://t4.ftcdn.net/jpg/01/89/61/09/240_F_189610906_zwAmM9375UK5kZQUqmhGVcWAGtZAooNe.jpg");
            overflow-x: hidden;
        }
        h1 {
            font-family: "IM Fell Double Pica SC";
            font-size: 60px;
            text-align: center;
            height: 35px;
        }
        h2 {
            font-family: "IM Fell Double Pica SC";
            font-size: 30px;
            color: #ffc;
        }
        #page-img,
        #page-img2 {
            object-fit: cover;
            max-height: 250px;
        }
        #reddit-link {
            width: 100px;
            opacity: 80%;
        }
        #reddit-link:hover{
            width: 115px;
            transition: 0.2s;
            opacity: 100%;
        }
        #discord-link {
            width: 90px;
            opacity: 80%;
        }
        #discord-link:hover {
            width: 105px;
            transition: 0.2s;
            opacity: 100%;
        }
        td {
            padding: 10px;
            text-align: center;
        }
        #title {
            margin: 55px 0 40px;
        }
        #navigation {
            height: 55px;
            max-width: 550px;
            margin: 0 auto 20px;
            font-size: 20px;
            background: rgba(110,110,100,0.5);
            color: #ffc;
            border-bottom: solid rgb(110,110,100);
        }
        #homecontent {
            display: flex;
            margin: 0 auto;
            max-width: 1000px;
        }
        #news {
            max-height: 750px;
            width: 50%;
            max-width: 500px;
            margin-bottom: 20px;
            background: rgba(110,110,100,0.5);
            border-top: solid rgba(110,110,100);
            font-family: courier;
            direction: rtl;
            overflow-y: auto;
        }
        #news header {
            text-align: center;
            margin-top: 20px;
            background: rgba(165,165,150,0.5);
            padding: 1px;
            direction: ltr;
        }
        .date {
            text-align: center;
            margin-top: 0px;
            background: rgba(165,165,150,0.8);
            padding: 5px;
            direction: ltr;
        }
        .article {
            margin: 0 10px;
            background: rgba(165,165,150,0.8);
            padding: 20px;
            direction: ltr;
        }
        ::-webkit-scrollbar {
            width: 7.5px;
        }
        ::-webkit-scrollbar-track,
        ::-webkit-scrollbar-thumb:hover {
            background: rgba(165,165,150,0.5);
        }
        ::-webkit-scrollbar-thumb {
            background: rgba(165,165,150,0.8);
        }
        #page-links {
            display: block;
            height: 750px;
        }
        .page-link-box {
            max-height: 350px;
            width: 40vw;
            margin: 0 10px 10px;
            background: rgba(110,110,100,0.5);
            border-top: solid rgba(110,110,100);
            text-align: center;
            padding: 10px;
        }
        #other-links {
            display: table;
            width: 100%;
            max-width: 800px;
            margin: 40px auto;
            table-layout: fixed;
        }
        #other-links td{
            display: table-cell;
            height: 250px;
            margin: 0 auto;
            background: rgba(110,110,100,0.5);
            border-top: solid rgba(110,110,100);
            font-size: 21px;
        }
        a:hover {
            color: yellow;
            font-size: 115%;
            transition: 0.15s ease;
        }
        footer {
            width: 50%;
            text-align: center;
            color: rgb(89, 110, 100);
            margin: auto;
            background: rgba(1100, 1100, 1000, 0.33);
            padding: 2px;
        }
    </style>
</head>
<body>
    <h1 id="title">NightmarE</h1>
    <table id="navigation">
        <tr>
            <td><a>Home</a>
            <td><a>Comic</a>
            <td><a>Prison Files</a>
            <td><a>Gallery</a>
            <td><a>News</a>
            <td><a>Other</a>
        </tr>
        </table>
<div id="homecontent">
    <div id="page-links">
        <div class="page-link-box"><header><h2>Start Reading</h2></header>
        <p>
            <a> <img style="width: 95%;" src="https://drive.google.com/thumbnail?id=14C9P8haLvDfd5VxSRNn8ms6f6APlwqLX" alt="Link to page 1" id="page-img"> </a>
        </p></div>
        <div class="page-link-box"><header><h2>Catch Up</h2></header>
        <p>
            <a> <img style="width: 95%;" src="https://drive.google.com/thumbnail?id=14C9P8haLvDfd5VxSRNn8ms6f6APlwqLX" alt="Link to most recent page" id="page-img2"> </a>
        </p></div>
    </div>
</div>
    <table id="other-links">
        <td><header><h2>Learn More</h2></header>
            <p>
            <a><strong>FAQ</strong></a><br><br>
            <a><strong>About</strong></a>
            </p>
        </td>
        <td><header><h2>Join the<br>Community</h2></header>
            <p>
            <a><img src="https://www.iconpacks.net/icons/2/free-reddit-logo-icon-2436-thumb.png" alt="Link to community subreddit" id="reddit-link"></a>
            <a><img src="https://seeklogo.com/images/D/discord-logo-7A1EC3216C-seeklogo.com.png" id="discord-link"></a>
            </p>
        </td>
        <td><header><h2>Contact Me</h2></header>
            <p>elijahwalkerNM<br>@gmail.com</p>
        </td>
    </table>
    <footer>
        Nightmare &copy; 2024 Elijah Walker.
    </footer>
</body>
</html>
