<script>
    let projects = [
        {name: "All of my itch.io games", description: "There's so much I can't list them here", link: "https://twingamerdudes.itch.io/"},
        {name: "Stickman Sandbox", description: "Apart of a defunct game studio, not on my itch.io page", link: "https://ohm-interactive.itch.io/stickman-sandbox"},
        {name: "ai_director", description: "The first ever ai_show engine to support stage directions", link: "https://github.com/Twingamerdudes/ai_director"},
        {name: "ai_engine", description: "Open source ai_sponge", link: "https://github.com/Twingamerdudes/ai_engine"},
        {name: "ai_rick", description: "AI Rick and Morty. What's better than infinite content!", link: "https://www.youtube.com/watch?v=q9Sxrkk7Sm8"},
        {name: "Lua for NEM", description: "A mod to NEM (which is a mod of M:PN), which adds Lua to it", link: "https://github.com/Twingamerdudes/Lua-For-NEM"},
        {name: "Chaos Mod", description: "A mod for Five Nights at Freddy's Security Breach which makes everything chaotic", link: "https://github.com/Twingamerdudes/Chaos-Mod"},
        {name: "Tire", description: "A programming language made in python", link: "https://github.com/Twingamerdudes/Tire"},
        {name: "EngScript", description: "English, as a programming language", link: "https://github.com/Twingamerdudes/EngScript"},
        {name: "Neural Symphony", description: "Fully AI Generated music, one of the few left on spotify", link: "https://www.neuralsymphony.tech/"},
        {name: "Tribe", description: "A tool for simulating lifeforms", link: "https://github.com/Twingamerdudes/Tribe"},
        {name: "Copilot Language", description: "A programming language made using only AI", link: "https://github.com/Twingamerdudes/Copilot-Language"},
        {name: "XGen", description: "A FNF No-Code Engine", link: "https://github.com/Twingamerdudes/XGen"}
        ]
</script>

<h1>Projects</h1>
<p>A collection of some of my most impressive projects over the years</p>
{#each projects as project}
    <div class="project">
        <h2>{project.name}</h2>
        <p>{project.description}</p>
        <a href={project.link} target="_blank">View page</a>
    </div>
{/each}
<style>
    .project {
        border: 1px solid #333333;
        padding: 10px;
        margin-bottom: 20px;
        background-color: #444444;
        width: 50%;
        text-align: center;
        /* center it */
        margin-left: auto;
        margin-right: auto;
        border-radius: 10px;
    }

    .project h2 {
        font-size: 24px;
        margin-bottom: 10px;
    }

    .project p {
        font-size: 16px;
        margin-bottom: 10px;
    }

    .project a {
        display: inline-block;
        padding: 5px 10px;
        background-color: #646464;
        color: #fff;
        text-decoration: none;
        border-radius: 5px;
    }

    .project a:hover {
        background-color: #5c5c5c;
    }

</style>