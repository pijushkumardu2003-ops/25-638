<style>
    :root {
        --primary-color: #1e3a8a;
        --secondary-color: #3b82f6;
        --text-color: #1f2937;
        --bg-color: #f8fafc;
        --card-bg: #ffffff;
        --border-color: #e2e8f0;
    }

    * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
    }

    body {
        font-family: 'Inter', sans-serif;
        background-color: var(--bg-color);
        color: var(--text-color);
        line-height: 1.6;
        padding: 20px;
    }

    .container {
        max-width: 900px;
        margin: 20px auto;
        background: var(--card-bg);
        padding: 40px;
        border-radius: 12px;
        box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
    }

    header {
        border-bottom: 2px solid var(--border-color);
        padding-bottom: 25px;
        margin-bottom: 30px;
    }

    header h1 {
        font-size: 2.2rem;
        color: var(--primary-color);
        letter-spacing: 1px;
        margin-bottom: 5px;
    }

    header h2 {
        font-size: 1.1rem;
        font-weight: 600;
        color: var(--secondary-color);
        text-transform: uppercase;
        margin-bottom: 15px;
    }

    .contact-info {
        display: flex;
        flex-wrap: wrap;
        gap: 15px 25px;
        font-size: 0.95rem;
    }

    .contact-info div {
        display: flex;
        align-items: center;
        gap: 8px;
    }

    .contact-info i {
        color: var(--secondary-color);
    }

    .contact-info a {
        color: var(--text-color);
        text-decoration: none;
        transition: color 0.2s;
    }

    .contact-info a:hover {
        color: var(--secondary-color);
    }

    section {
        margin-bottom: 30px;
    }

    .section-title {
        font-size: 1.25rem;
        color: var(--primary-color);
        text-transform: uppercase;
        border-bottom: 2px solid var(--primary-color);
        padding-bottom: 5px;
        margin-bottom: 15px;
        display: flex;
        align-items: center;
        gap: 10px;
    }

    p {
        font-size: 0.98rem;
        color: #374151;
    }

    /* Skills Grid */
    .skills-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
        gap: 20px;
    }

    .skill-card {
        background: #f1f5f9;
        padding: 15px;
        border-radius: 8px;
        border-left: 4px solid var(--secondary-color);
    }

    .skill-card h4 {
        color: var(--primary-color);
        margin-bottom: 8px;
    }

    /* Experience & Projects */
    .item {
        margin-bottom: 20px;
    }

    .item-header {
        display: flex;
        justify-content: space-between;
        align-items: flex-start;
        margin-bottom: 5px;
    }

    .item-title {
        font-size: 1.05rem;
        font-weight: 700;
        color: var(--primary-color);
    }

    .item-sub {
        font-weight: 600;
        color: var(--secondary-color);
    }

    .item-date {
        font-size: 0.85rem;
        background: #e0f2fe;
        color: #0369a1;
        padding: 3px 8px;
        border-radius: 4px;
        font-weight: 600;
    }

    ul {
        list-style-type: disc;
        margin-left: 20px;
        margin-top: 8px;
    }

    li {
        margin-bottom: 6px;
        font-size: 0.95rem;
    }

    /* Strengths Grid */
    .strengths-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
        gap: 15px;
    }

    .strength-item {
        background: #fff;
        border: 1px solid var(--border-color);
        padding: 12px;
        border-radius: 6px;
    }

    .strength-item h5 {
        color: var(--primary-color);
        margin-bottom: 5px;
    }

    .strength-item p {
        font-size: 0.88rem;
    }

    @media (max-width: 600px) {
        .container {
            padding: 20px;
        }
        .item-header {
            flex-direction: column;
            gap: 5px;
        }
    }
</style>

<div class="container">
    <!-- HEADER -->
    <header>
        <h1>PIYUSH KUMAR SHEEL</h1>
        <h2>Education Specialist & Educational Researcher</h2>
        <div class="contact-info">
            <div><i class="fa-solid fa-location-dot"></i> Dhaka, Bangladesh</div>
            <div><i class="fa-solid fa-phone"></i> +880 1XXXXXXXXX</div>
            <div><i class="fa-solid fa-envelope"></i> <a href="mailto:plyush.sheel@email.com">plyush.sheel@email.com</a></div>
            <div><i class="fa-brands fa-linkedin"></i> <a href="https://linkedin.com/in/piyushkumarsheel" target="_blank">linkedin.com/in/piyushkumarsheel</a></div>
        </div>
    </header>

    <!-- EXECUTIVE SUMMARY -->
    <section>
        <h3 class="section-title"><i class="fa-solid fa-user"></i> Executive Summary</h3>
        <p>
            Dedicated and research-driven Education Specialist with expertise in inclusive education, curriculum analysis, and educational technology integration. Possesses a strong academic background in quantitative and qualitative research methodologies, policy analysis, and special educational needs (SEN) frameworks. Proven ability to evaluate complex educational systems, design inclusive learning models, and formulate evidence-based policy proposals.
        </p>
    </section>

    <!-- CORE COMPETENCIES & SKILLS -->
    <section>
        <h3 class="section-title"><i class="fa-solid fa-list-check"></i> Core Competencies & Skills</h3>
        <div class="skills-grid">
            <div class="skill-card">
                <h4>Educational Research</h4>
                <p>Constructivist & Positivist Paradigms, Mixed-Methods Design, Phenomenology, Grounded Theory, Measurement & Scaling.</p>
            </div>
            <div class="skill-card">
                <h4>Inclusive Education & SEN</h4>
                <p>IEP, Universal Design for Learning (UDL), Disability Inclusion Frameworks, Assistive Technology Evaluation.</p>
            </div>
            <div class="skill-card">
                <h4>Policy & Governance</h4>
                <p>National Education Policy Analysis, EdTech Integration Strategies, Public Sector Governance.</p>
            </div>
            <div class="skill-card">
                <h4>Technical & Professional</h4>
                <p>Statistical Tools & Data Analysis, Academic Writing, Strategic Program Evaluation.</p>
            </div>
        </div>
    </section>

    <!-- EDUCATION -->
    <section>
        <h3 class="section-title"><i class="fa-solid fa-graduation-cap"></i> Education</h3>
        <div class="item">
            <div class="item-header">
                <div>
                    <div class="item-title">Bachelor of Education (B.Ed. Honors)</div>
                    <div class="item-sub">Institute of Education and Research (IER), University of Dhaka, Bangladesh</div>
                </div>
            </div>
            <ul>
                <li><strong>Specialization:</strong> Special Educational Needs (SEN), Curriculum Evaluation, Educational Technology.</li>
                <li><strong>Key Focus:</strong> Advanced Research Methodology, Inclusive Pedagogies, Educational Policy Formulation.</li>
            </ul>
        </div>
    </section>

    <!-- RESEARCH & KEY PROJECTS -->
    <section>
        <h3 class="section-title"><i class="fa-solid fa-flask"></i> Research & Key Projects</h3>
        
        <div class="item">
            <div class="item-header">
                <div>
                    <div class="item-title">Institutional Analysis of Special Educational Needs Units (SENU)</div>
                    <div class="item-sub">Field Evaluation & Observational Research</div>
                </div>
            </div>
            <ul>
                <li>Conducted structured field evaluations and observational research across key rehabilitation and special education institutions in Bangladesh (including CRP Savar and SWID Bangladesh).</li>
                <li>Assessed the practical implementation of UDL principles and assistive technology integration for learners with intellectual disabilities and autism.</li>
            </ul>
        </div>

        <div class="item">
            <div class="item-header">
                <div>
                    <div class="item-title">Research Proposal: EdTech Integration in Bangladesh</div>
                    <div class="item-sub">Impact of Technology on Education in Bangladesh: Opportunities, Challenges & Future Prospects</div>
                </div>
                <span class="item-date">2024 - 2026</span>
            </div>
            <ul>
                <li>Formulated a comprehensive research framework, literature review, and methodology examining digital literacy and EdTech infrastructure in Bangladeshi public schools.</li>
                <li>Analyzed policy constraints and structural opportunities for Smart Bangladesh 2041 educational initiatives.</li>
            </ul>
        </div>
    </section>

    <!-- PROFESSIONAL EXPERIENCE -->
    <section>
        <h3 class="section-title"><i class="fa-solid fa-briefcase"></i> Professional Experience</h3>
        <div class="item">
            <div class="item-header">
                <div>
                    <div class="item-title">Graduate Student Researcher / Field Observer</div>
                    <div class="item-sub">Institute of Education and Research (IER), University of Dhaka</div>
                </div>
                <span class="item-date">2022 - 2026</span>
            </div>
            <ul>
                <li>Executed institutional evaluations, stakeholder interviews, and pedagogical analyses across urban public and specialized school environments.</li>
                <li>Synthesized national education policies and draft legislative acts into structured policy briefs and institutional summaries.</li>
                <li>Collaborated on observational frameworks evaluating disability inclusion metrics in classroom settings.</li>
            </ul>
        </div>
    </section>

    <!-- CERTIFICATIONS -->
    <section>
        <h3 class="section-title"><i class="fa-solid fa-certificate"></i> Certifications</h3>
        <ul>
            <li><strong>2026:</strong> Inclusive Pedagogy & Assistive Technologies Workshop, Dhaka</li>
            <li><strong>2025:</strong> Advanced Research Methodology & Data Analysis</li>
        </ul>
    </section>

    <!-- KEY STRENGTHS -->
    <section>
        <h3 class="section-title"><i class="fa-solid fa-star"></i> Key Strengths</h3>
        <div class="strengths-grid">
            <div class="strength-item">
                <h5>Field-Based Evaluation</h5>
                <p>Direct, structured observation of institutional practice rather than desk-based assessment alone.</p>
            </div>
            <div class="strength-item">
                <h5>Policy Translation</h5>
                <p>Turning dense legislative and policy language into actionable institutional briefs.</p>
            </div>
            <div class="strength-item">
                <h5>Cross-Sector Collaboration</h5>
                <p>Comfortable working across academic, governmental, and NGO/rehabilitation settings.</p>
            </div>
            <div class="strength-item">
                <h5>Evidence-Based Design</h5>
                <p>Anchoring inclusive learning models in measurable, research-backed frameworks.</p>
            </div>
        </div>
    </section>

    <!-- TEACHING & RESEARCH PHILOSOPHY -->
    <section>
        <h3 class="section-title"><i class="fa-solid fa-lightbulb"></i> Teaching & Research Philosophy</h3>
        <p>
            Approaches education as a field where rigorous research and lived institutional experience must inform one another. Committed to designing learning environments where inclusion is a structural principle rather than an accommodation, and to grounding every policy recommendation in direct field observation across public and specialized school settings.
        </p>
    </section>

    <!-- AREAS OF INTEREST -->
    <section>
        <h3 class="section-title"><i class="fa-solid fa-compass"></i> Areas of Interest</h3>
        <p>
            Disability-inclusive curriculum design, national EdTech policy formation, and assistive technology access in under-resourced and rural school systems.
        </p>
    </section>

    <!-- REFERENCES -->
    <section>
        <h3 class="section-title"><i class="fa-solid fa-address-book"></i> References</h3>
        <p>Academic and professional references, along with detailed project reports and publications, available upon request.</p>
    </section>
</div>
