
## About

Backend Software Engineer specializing in Java Spring Boot, Cloud Solutions, and Docker. Passionate about building scalable, high-performance backend systems, optimizing databases, and leveraging cloud technologies for reliability and efficiency.

<p align="flex-start">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=java,spring,mongodb,postgresql,redis,rabbitmq,grafana,docker&perline=10" style="margin-right: 120px; "/>
  </a>
 </p>


 <!DOCTYPE html>
<html>
<head>
    <title>Click Game</title>
</head>
<body style="text-align: center; font-family: Arial, sans-serif; margin-top: 50px;">

    <h1>Click the Box!</h1>
    <h2 id="score">Score: 0</h2>

    <div id="box" 
         style="width: 100px; height: 100px; background-color: red; margin: 50px auto; cursor: pointer; position: relative;">
    </div>

    <script>
        let score = 0;
        let box = document.getElementById('box');
        let scoreText = document.getElementById('score');

        box.onclick = function() {
            score += 1;
            scoreText.innerText = 'Score: ' + score;

            let x = Math.random() * (window.innerWidth - 100);
            let y = Math.random() * (window.innerHeight - 100);

            box.style.position = 'absolute';
            box.style.left = x + 'px';
            box.style.top = y + 'px';
        };
    </script>

</body>
</html>



### Professional Focus
- **Backend Development**: Skilled in building scalable and efficient backend systems using Java Spring Boot.
- **Cloud Solutions**: Proficient in leveraging cloud technologies to enhance application performance and reliability.
- **Containerization**: Experienced in containerization and orchestration with Docker to streamline development workflows.


### Interests
- **Artificial Intelligence**: Curious about exploring advanced AI technologies and their applications in solving real world problems.
- **Low-Level Programming**: Fascinated by the intricacies of low level programming and its impact on system efficiency and performance.

### Contact
**Email:** mohamad.h.zbib@gmail.com

**Phone:** 961 76 782 106


