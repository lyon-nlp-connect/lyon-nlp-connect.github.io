---
author: "Organizers"
title: "About the Community"
date: "2025-01-01T08:52:59+08:00"
tag: "Community"
categories: "Community"
---

The idea behind Lyon NLP Connect is to foster collaborations between PhD students in Lyon and Saint-Étienne working on NLP-related topics.  
Most events will be held in person. 🎤  

{{< rawhtml >}}
<h3>Participants</h3>

<p>
We are a community of 40+ members from universities, research labs, and companies, including Lyon 1, Lyon 2, INSA Lyon, ENS de Lyon, École Centrale de Lyon, LIRIS, ERIC, Hubert Curien, Worldline, and Wikit.
</p>

<h3>About the Meetups</h3>

<p>Each meetup consists of:</p>
<ul>
  <li><strong>Introducing participants</strong> through a brief round-table session</li>
  <!-- <li>A short presentation by one member on a recently published paper</li> -->
  <li><strong>Discussing paper or topics</strong> in a Birds-of-a-Feather (BoF) format</li>
  <li><strong>Exploring collaboration ideas</strong> in pairs in order to propose potential joint projects</li>
</ul>

<section> 
 <h3>What are BoFs?</h3>
<p style="font-size: 1.1em;">
Birds-of-a-Feather (BoF) sessions are informal group discussions focused on a shared topic in ML/NLP.
Instead of formal talks, participants sit together, exchange experiences, raise questions, and explore ideas in an open conversation.
Examples of BoF sessions from conferences:
</p>
<ul>
    <li><a href="https://2023.emnlp.org/program/bof" target="_blank">EMNLP 2023 BoF Sessions</a></li>
    <li><a href="https://coling2025.org/program/bof" target="_blank">COLING 2025 BoF Sessions</a></li>
    <li><a href="https://2023.aclweb.org/calls/bof" target="_blank">ACL 2023 BoF Calls</a></li>
</ul>

<h3>How to propose a topic?</h3>
<p style="font-size: 1.1em;">
    Want to suggest a topic? Fill out the form on the homepage and join the discussion on Discord 🚀
</p>

<h3>How are BoFs organized?</h3>
<p style="font-size: 1em;">
    To foster discussion, we provide topics with guiding questions.  
    Each group member shares their answers, and a representative summarizes the main takeaways for everyone.  
</p>

<p style="font-size: 1.1em;">
    Example topics from our first session:  
</p>
<ul>
    <li>Language generation in research and applications</li>
    <li>Recent papers or articles on language generation</li>
    <li>Limitations of language generation</li>
</ul>

</section>

<style>
    :root {
    --bg-color: #f8f9fb;
    --card-bg: #ffffff;
    --card-border: #e8e8e8;
    --text-color: #222;
    --text-muted: #828282;
    --accent-color: #006ad4;
    --shadow: 0 2px 4px rgba(0,0,0,0.02), 0 1px 6px rgba(0,0,0,0.04);
  }

  .dark {
    --bg-color: #121212;
    --card-bg: #1e1e1e;
    --card-border: #2a2a2a;
    --text-color: #e5e5e5;
    --text-muted: #a0a0a0;
    --accent-color: #519aba;
    --shadow: 0 2px 6px rgba(0,0,0,0.3);
  }

  body {
    background: var(--bg-color);
    color: var(--text-color);
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    margin: 0;
  }

  .organizers {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
    gap: 1.25rem;
    max-width: 550px;
    margin: 0 auto;
    padding: 2.5rem 1.5rem;
  }

  .organizer {
    display: flex;
    align-items: center;
    gap: 1.25rem;
    background: var(--card-bg);
    border: 1px solid var(--card-border);
    padding: 1rem 1.25rem; /* Slightly more compact card size */
    border-radius: 8px;
    box-shadow: var(--shadow);
    transition: transform 0.2s ease, border-color 0.2s ease;
  }

  .organizer:hover {
    transform: translateY(-2px);
    border-color: var(--accent-color);
  }
  .organizer:hover .organizer-name {
    color: var(--accent-color);
  }
  
  .organizer img {
    width: 100px;
    height: 100px;
    border-radius: 6px;
    object-fit: cover;
    flex-shrink: 0;
    background: var(--card-border);
  }

  .organizer-info {
    display: flex;
    flex-direction: column;
    min-width: 0;
  }

  .organizer-name {
    font-size: 1.2rem; /* Larger font size */
    font-weight: 700;
    color: var(--text-color);
    margin: 0 0 0.25rem 0;
  }

  .organizer-affiliation {
    font-size: 0.95rem;
    color: var(--text-muted);
    line-height: 1.4;
    margin: 0 0 0.5rem 0;
  }
  .organizer-affiliation span:not(:last-child)::after {
  content: "•";
  margin: 0 0.3rem;
  font-size: 1.1rem;
  font-weight: 600;
  color: var(--text-muted);
}

  .organizer-email {
    font-size: 0.9rem;
    font-weight: 500;
    color: var(--accent-color);
    text-decoration: none;
  }

  .organizer-email:hover {
    text-decoration: underline;
  }

  @media (max-width: 600px) {
    .organizer {
      flex-direction: column;
      text-align: center;
    }
    .organizer-info {
      align-items: center;
    }
  }
</style>
<h3>Organizers</h3>
<div class="organizers">
  <div class="organizer">
    <img src="/user-solid.png" alt="Thomas CHECCHIN">
    <div class="organizer-info">
      <div class="organizer-name">Thomas CHECCHIN</div>
      <div class="organizer-affiliation">
        <span> ERIC Laboratory </span>
        <span> University of Lyon 2 </span>
      </div>
      <a class="organizer-email" href="mailto:thomas.checchin@univ-lyon2.fr">
        thomas.checchin@univ-lyon2.fr
      </a>
    </div>
  </div>

  <div class="organizer">
    <img src="/erwan.jpg" alt="Erwan VERSMÉE">
    <div class="organizer-info">
      <div class="organizer-name">Erwan VERSMÉE</div>
      <div class="organizer-affiliation">
        <span> ERIC Laboratory </span>
        <span> University of Lyon 2<br>
        Infologic </span>
      </div>
      <a class="organizer-email" href="mailto:eve@infologic.fr">
        eve@infologic.fr
      </a>
    </div>
  </div>
</div>

<h3> Senior organizers</h3>
<div class="organizers">
  <div class="organizer">
    <img src="/irina.webp" alt="Irina PROSKURINA">
    <div class="organizer-info">
      <div class="organizer-name">Irina PROSKURINA</div>
      <div class="organizer-affiliation">
        <span> ERIC Laboratory </span>
        <span> University of Lyon 2<br>
        Hubert Curien Laboratory </span>
        <span> Jean Monnet University </span>
        <!-- ERIC Laboratory · Hubert Curien Laboratory<br> -->
        <!-- University of Lyon 2 · Jean Monnet University -->
      </div>
      <a class="organizer-email" href="mailto:irina.proskurina@univ-lyon2.fr">
        irina.proskurina@univ-lyon2.fr
      </a>
    </div>
  </div>
</div>


{{< /rawhtml >}}
