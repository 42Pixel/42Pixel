<html>
<head>
<style>
@import url('https://fonts.googleapis.com/css2?family=Mali:ital@1&display=swap');
*
{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Mali', cursive;
}
body
{
    display: flex;
    justify-content: center;
    min-height: 100px;
    background-color: #fff;
}
h2
{
    display: flex;
    /* color:transparent; */
    font-size: 15vw;
}
h2 span
{
    animation: animate 3s linear infinite;
    animation-delay: calc(0.1s * var(--i));
}
@keyframes animate
{
    0%
    {
        color: #fff;
        filter: blur(2px) hue-rotate(0deg);
        text-shadow: 0 0 10px #00b3ff,
        0 0 20px #00b3ff,
        0 0 40px #00b3ff,
        0 0 80px #00b3ff,
        0 0 120px #00b3ff,
        0 0 200px #00b3ff,
        0 0 300px #00b3ff,
        0 0 400px #00b3ff;
    }
    30%,70%
    {
        color: #fff;
        filter: blur(2px) hue-rotate(360deg);
        text-shadow: 0 0 10px #00b3ff,
        0 0 20px #00b3ff,
        0 0 40px #00b3ff,
        0 0 80px #00b3ff,
        0 0 120px #00b3ff,
        0 0 200px #00b3ff;
    }
    100%
    {
        color: transparent;
        box-shadow: none;
        filter: blur(2px)hue-rotate(0deg);
    }
}
</style>
</head>
<body>
<h2>
    <span style="--i:1;">H</span>
    <span style="--i:2;">e</span>
    <span style="--i:3;">l</span>
    <span style="--i:4;">l</span>
    <span style="--i:5;">o</span>
    <span style="--i:6;margin-left:5vw">W</span>
    <span style="--i:7;">o</span>
    <span style="--i:8;">r</span>
    <span style="--i:9;">l</span>
    <span style="--i:10;">d</span>
    <span style="--i:11;margin-left:5vw">!</span>
</h2>
</body>
</html>
