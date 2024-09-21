<script>
    import Photo from "../lib/components/Photo.svelte";
</script>

<main>
    <Photo />
    <h1>
        About Me
    </h1>
    <p>
        I am a dedicated U.S. Signals Intelligence Soldier and student with a strong technical background in software development and project management. I have experiecne in the development of web applications and managing IT initiatives that support critical operations, including projects for an EMS company and veteran housing programs. My role in the military continues to hone my leadership skills, analytical thinking, and ability to work under pressure, all while maintaining an active TS/SCI clearance. I am committed to leveraging my diverse skill set and experience to contribute to impactful projects and drive innovation within the engineering and technical sector.
    </p>
</main>

<style>
    main {
        display: flex;
        flex-direction: column;
        margin: auto;
        align-items: center;
        width: fit-content;
        margin: 20px;
        margin-top: 25px;
        margin-bottom: 10px;
    }
    h1,p {
        margin: 0;
    }
    h1 {
        margin: 10px;
        margin-bottom: 0;
        color: rgb(0, 0, 0);

    }
    p {
        text-align: center;
        margin: 5px;
        font-size: 20px;
        text-shadow: 0px 0px 5px rgb(0, 0, 0);
        /* color: rgb(247, 221, 161); */

    }
</style>