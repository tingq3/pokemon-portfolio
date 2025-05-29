<script>
	import Hobby from '$lib/Hobby.svelte';
</script>

<main>
	<section id="hero" class="hero" aria-labelledby="hero-heading">
		<h1 id="hero-heading">Jack’s Pokémon Portfolio</h1>
	</section>

    <section class="card-vs-intro">
        <div class="card-vs-wrapper">
            <img src="/images/Coding.png" alt="Coding Card" class="vs-card" />
            <div class="vs-label">VS</div>
            <img src="/images/Sleep.png" alt="Sleep Card" class="vs-card" />
        </div>
    </section>

    <section id="experience" class="experience-section">
        <h2 id="experience-heading" class="section-heading">Experience</h2>

        <details open>
            <summary>🎓 Year & Degree</summary>
            <p>I am currently a 2nd-year Computer Science student at UNSW.</p>
        </details>

        <details>
            <summary>📚 Courses Taken</summary>
            <ul>
                <li>COMP1511 – Programming Fundamentals</li>
                <li>COMP1531 – Software Engineering</li>
                <li>COMP2511 – OOP & Design Patterns</li>
                <li>COMP2521 – Data Structures & Algorithms</li>
                <li>COMP3311 – Databases</li>
                <li>COMP3411 – AI</li>
            </ul>
        </details>

        <details>
            <summary>🧰 Frameworks & Tools</summary>
            <ul>
                <li>SvelteKit, React, Tailwind CSS</li>
                <li>Node.js, Express, Docker</li>
                <li>MySQL, PostgreSQL</li>
            </ul>
        </details>

        <details>
            <summary>🚀 Skills & Strengths</summary>
            <ul>
                <li>Full-stack development</li>
                <li>Problem solving and design thinking</li>
                <li>Team collaboration with Git</li>
            </ul>
        </details>
    </section>

	<section id="hobbies" class="hobby-section">
        <h2 class="section-heading">Hobbies</h2>
        <Hobby 
            title="Bouldering"
            image="/images/bouldering.jpg"
            description="I’ve only been bouldering for a few months, but it’s already one of my favorite things to do. I’m still a beginner, but trying new routes and falling off the wall has become part of my weekly routine. It’s fun, frustrating, and super satisfying when I finally reach the top — way better than sitting at a desk all day."
            theme="red"
        />

        <Hobby 
            title="Guitar"
            image="/images/guitar.jpg"
            description="I started learning guitar about 2 years ago. I mostly play fingerstyle and simple songs I like. I’m not amazing at it, but it’s a fun way to relax and take a break from coding or studying. Sometimes I just play random stuff and zone out — it’s chill."
            theme="blue"
            flip
        />
    </section>

</main>
