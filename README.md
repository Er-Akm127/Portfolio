 
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>${name}'s Portfolio</title>
    <style>
        main {
            width: 100vw;
            height: 100vh;
            display: flex;
            flex-direction: column;
            
            margin-left: 5vw;

        }

        body {
            background: linear-gradient(132deg, rgb(115, 93, 142) 0.00%, rgb(58, 33, 86) 100.00%);
            display: flex;
           
            justify-content: center;
            align-items: center;
        }

        h1:hover {
            transform: rotate(360deg);
            transition: transform 3s;
        }

        #welcome {
            width: 40vw;
            height: auto;
            padding: 3vw;
            background-color: aliceblue;
            color: black;
            font-weight: bolder;
            border: 2px solid grey;
            border-radius: 25px;
            font-size: larger;
        }

        #intro {
            width: 40vw;
            padding: 3vw;
            font-weight: bolder;
            background-color: yellow;
            opacity: 80%;
            border-radius: 25px;
            margin-top: 2vh;

        }

        #skill {
            border-radius: 25px;
            border: 2px solid darkred;
            margin-top: 2vh;
            width: 40vw;
            font-size: larger;
            height: auto;
            padding: 5vw;
            background-color: white;
        }

        #others {
            width: 40vw;
            padding: 4vw;
            border: 2px solid darkgreen;
            height: auto;
            border-radius: 25px;
            margin-top: 2vh;
            background-color: aliceblue;
        }

        .skills {

            color: black;
            text-transform: capitalize;
        }

        .skills:hover {
            font-size: larger;

            color: darkblue;
        }

        .blogs,
        .projects {
            overflow: scroll;
            width: 50vw;
            height: 20vh;
            border: 2px solid purple;
            border-radius: 24px;
            background-color: aliceblue;
        }

        .a {
            color: white;
            font-weight: bolder;
            text-decoration: underline;
            text-align: center;
        }

        aside {
           
            width: 15vw;
            height: 65vh;
            background-color: darkmagenta;
            border: 1px solid black;
            color: white;
            text-align: center;
        }

        li {
            list-style-type: none;
        }

        h2 {
            color: white;
        }

        @media screen and (max-width:600px) {
            html,body{
                width: 100vw;
                height: 100vh;
            }
            
            #welcome,#skill,#others,#about,#intro,.blogs,.projects,#project,#blog{
                width: 70vw;
                height: auto;
                margin: 1vw;
                transform: translate(1vw,0vw);
            }
            .projects,.blogs{
                max-width: 74vw;
                width: 70vw;
                height: auto;
            }
            aside{
                display: none;
            }
           
        }
        @media screen and (max-width:850px) {
            
            body,html{
                width: 100vw;
                height: 100vh;
            }
            #welcome,#skill,#others,#about,#intro,.blogs,.projects,#project,#blog{
                width: 70vw;
                height: auto;
                margin: 1vw;
                transform: translate(1vw,0vw);
            }
            aside{
                width: 25vw;
                height: 100vh;
            }
           
        }
    </style>
</head>

<body>
    <aside>
        This webpage contains my following information
        <ul>
            <li class="a">About me</li>
            <li class="a">My Skills</li>
            <li class="a">My Projects</li>
            <li class="a">My Blogs</li>
        </ul>
    </aside>
    <main>
        <div id="welcome">
            Welcome to my portfolio website! I am thrilled to have you here. I have created this website to showcase my
            work and share my journey with you. Please feel free to explore my portfolio and get in touch with me if you
            have any questions or would like to collaborate. Thank you for visiting! 😊
        </div>
        <div id="intro">
            <h4>Hello everyone! I am</h4>
            <h1>${name}</h1>
        </div>
        <div id="skill">
            <p>My skills are in following fields:</p>
            <span class="skills">${skill1}</span> <br><span class="skills">${skill2}</span> <br><span
                class="skills">${skill3}</span>
        </div>
        <div id="others">
            <p>I have completed my 10th from ${school}, and completed next high education degree in ${college}. And
                living at ${address}</p>
        </div>
        <div id="blog">
            <h2>Have a look on my blogs</h2>
            <div class="blogs">
                <h3>${blog1}</h3>
                <p>${blog1_details}</p>
            </div>
            <div class="blogs">
                <h3>${blog2}</h3>
                <p>${blog2_details}</p>
            </div>
            <div class="blogs">
                <h3>${blog3}</h3>
                <p>${blog3_details}</p>
            </div>
            <div class="blogs">
                <h3>${blog4}</h3>
                <p>${blog4_details}</p>
            </div>
            <div class="blogs">
                <h3>${blog5}</h3>
                <p>${blog5_details}</p>
            </div>
        </div>
        <div id="project">
            <h2>Also see some of my projects</h2>
            <div class="projects">
                <h3>${project1}</h3>
                <p>${project1_details}</p>
            </div>
            <div class="projects">
                <h3>${project2}</h3>
                <p>${project2_details}</p>
            </div>
            <div class="projects">
                <h3>${project3}</h3>
                <p>${project3_details}</p>
            </div>
            <div class="projects">
                <h3>${project4}</h3>
                <p>${project4_details}</p>
            </div>
            <div class="projects">
                <h3>${project5}</h3>
                <p>${project5_details}</p>
            </div>
        </div>
    </main>
</body>

</html>
