<script>
    import Bsky from "$lib/components/Bsky.svelte";
    import GitHub from "$lib/components/GitHub.svelte";
    import LinkedIn from "$lib/components/LinkedIn.svelte";
    import Tag from "$lib/components/Tag.svelte";
    import Chris from "../lib/chris.jpg";
</script>

<div
    class="antialiased max-w-5xl px-4 prose-p:mt-0.5 prose backdrop-blur-lg prose-brown dark:prose-invert lg:prose-lg xl:prose-xl pt-4 xl:pt-8 mx-auto"
>
    <h1>Hello! I am Chris</h1>
    <div>
        <div class="flex flex-col md:flex-row items-center gap-2">
            <p class="lead">
                I love technology and have been a sysadmin type person most of
                my life. I am now pivoting to software and web development,
                largely due to discovering fullstack web frameworks like
                SvelteKit. I love how you can you easily you can make something
                nice looking and responsive and also easily deploy it to the
                web.
            </p>
            <div class="picandsocials flex gap-4">
                <img
                    class="aspect-square max-w-[150px] grayscale rounded-xl md:ml-8"
                    src={Chris}
                    alt="Chris"
                />
                <div class="tags flex-col flex gap-4 justify-center">
                    <a href="https://chrisb.se"><GitHub width={"w-8"} /></a>
                    <a href="https://www.linkedin.com/in/christianbaang/"
                        ><LinkedIn width={"w-8"} /></a
                    >
                    <a href="https://bsky.app/profile/chrisbsides.bsky.social"
                        ><Bsky width={"w-8"} /></a
                    >
                </div>
            </div>
        </div>
        <!-- <h3>Current</h3> -->
        <div>
            <p class="lead">
                I am currently studying fullstack .NET development at YH
                Akademin.
            </p>

            <div class="tags flex flex-wrap gap-2">
                <Tag>Fullstack Development</Tag>
                <Tag>.NET Core</Tag>
                <Tag>C#</Tag>
                <Tag>ASP.NET</Tag>
                <Tag>Blazor</Tag>
                <Tag>TypeScript</Tag>
                <Tag>HTML</Tag>
                <Tag>CSS</Tag>
            </div>
        </div>
    </div>

    <h3>Work History / Projects</h3>
    <h4>Internship</h4>
    <div>
        <p>
            Was part of a team of fullstack-developer interns @ Knowit Östersund
            where we built a webapp with ASP.NET backend and React frontend. I
            was primarily focused on backend user and role management plus AWS
            auth, but I also took the opportunity to improve frontend skills and
            learn React with Shadcn components.
        </p>

        <div class="tags flex flex-wrap gap-2">
            <Tag>ASP.NET</Tag>
            <Tag>React</Tag>
            <Tag>Shadcn/ui</Tag>
            <Tag>Tailwindcss</Tag>
            <Tag>TypeScript</Tag>
        </div>
    </div>

    <h4>YT Playlist Player</h4>
    <div>
        <p>
            Webapp I made to play YouTube music playlists and quickly toggle
            on/off, play next when song end, shuffle songs, pick5random etc.
        </p>

        <div class="tags flex flex-wrap gap-2">
            <Tag>Youtube API</Tag>
            <Tag>YouTube Player API</Tag>
            <Tag>SvelteKit</Tag>
            <Tag>TypeScript</Tag>
            <Tag>Tailwindcss</Tag>
        </div>
    </div>

    <h4>Leaf Music Player</h4>
    <div>
        <p>
            C# WPF .NET 9 Application. I wanted to try out making an offline
            .exe file application for playing local mp3s/flacs on the PC and see
            how to make it more modern looking.
        </p>

        <div class="tags flex flex-wrap gap-2">
            <Tag>C#</Tag>
            <Tag>.NET 9</Tag>
            <Tag>WPF</Tag>
        </div>
    </div>

    <h4>LoL Matchhistory</h4>
    <div>
        <p>
            Webapp I made to get an overview of me and my teammates recent
            matchhistory to make informed decision on whether to play the match
            or jump off.
        </p>
        <div class="tags flex flex-wrap gap-2">
            <Tag>Riot Games API</Tag>
            <Tag>SvelteKit</Tag>
            <Tag>TailwindCSS</Tag>
        </div>
    </div>

    <h3>University studies</h3>
    <div>
        <h4>Computer Science</h4>
        <p>
            Studied programming in C, objectoriented programming in Java,
            HTML/CSS and maths and some more theoretical courses.
        </p>
        <h4>Game Design</h4>
        <p>
            Got a Bachelors degree in Game Design at Uppsala University, Campus
            Gotland. The programme was mostly oriented around group projects we
            made in Unity and Unreal but I took also took extra programming
            courses for my minor.
        </p>
    </div>
</div>

<svelte:head>
    <title>Christian Bång portfolio</title>
</svelte:head>
