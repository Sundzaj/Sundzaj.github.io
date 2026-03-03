<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Dawid Januszko QA Software Tester</title>
    <script src="https://unpkg.com/feather-icons"></script>
    <link rel="stylesheet" href="style.css" />
    <style>
      @import url("https://fonts.googleapis.com/css2?family=Inter:wght@200;300;400;500;600;700&display=swap");

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
:root {
  --primary-color: #1371ff;
  --text-color: #000000;
}
html {
  font-size: 10px;
}
body {
  font-family: Inter, sans-serif;
  background-color: rgb(255, 255, 255);
  color: rgb(0, 0, 0);
}

/* common styles */
img {
  width: 100%;
}
a {
  text-decoration: none;
  color: white;
}
.description {
  margin-top: 1rem;
  font-size: 1.5rem;
  font-weight: 400;
  line-height: 1.3;
  color: var(--text-color);
}
.title {
  color: var(--primary-color);
  font-weight: 700;
  font-size: 2rem;
  text-transform: uppercase;
}
.item_preTitle {
  font-size: 1.4rem;
  color: var(--text-color);
  font-weight: 300;
}
.item_title {
  font-size: 1.6rem;
  color: rgb(0, 0, 0);
  font-weight: 500;
  margin: 0.8rem 0;
}
.item_subtitle {
  font-size: 1.4rem;
  color: var(--text-color);
  font-weight: 400;
}

/* layouts */
.container {
  max-width: 1000px;
  width: 90%;
  margin: 0 auto;
  display: grid;
  padding: 5rem;
  background: #ffffff;
  grid-template-columns: 1fr 1fr;
  gap: 4rem;
}
@media only screen and (max-width: 768px) {
  .container {
    width: 100%;
    grid-template-columns: 1fr;
    padding: 3rem;
    gap: 7rem;
  }
}
.profile {
  grid-column: 1 / -1;
  margin-bottom: 2rem;
}
.group-1,
.group-2 {
  display: flex;
  flex-direction: column;
  gap: 5rem;
}
.group-3 {
  max-width: 700px;
  width: 100%;
  margin: 0 auto;
  grid-column: 1/-1;
  display: flex;
  flex-direction: row;
  gap: 5rem;
}
.group-3 > div {
  flex: 1;
}
@media only screen and (max-width: 768px) {
  .profile {
    margin-bottom: 0;
  }
  .group-3 {
    flex-direction: column;
  }
}

/* profile */
.profile_container {
  display: flex;
  gap: 2rem;
}
.profile_profileImg {
  max-width: 250px;
}
.profile_name_firstName {
  color: rgb(0, 0, 0);
  font-weight: 200;
  font-size: clamp(2rem, 8vw, 4rem);
  text-transform: uppercase;
  display: block;
  margin-bottom: -0.8rem;
}
.profile_name_lastName {
  color: var(--primary-color);
  font-weight: 700;
  font-size: clamp(2rem, 10vw, 6rem);
  text-transform: uppercase;
  display: block;
}
.profile_title {
  font-size: 1.5rem;
  font-weight: 700;
  text-transform: uppercase;
}
.downloadBtn {
  display: block;
  text-decoration: underline;
  font-size: 1.6rem;
  margin-top: 1rem;
}
.downloadBtn:hover {
  color: var(--primary-color);
}
@media only screen and (max-width: 768px) {
  .profile_container {
    flex-direction: column;
  }
}

/* Expertise */
.skills_list {
  margin-top: 2rem;
  margin-left: 2rem;
  line-height: 1.5;
}

/* Ref  */
.ref_item {
  margin-top: 2rem;
}
.ref_name {
  font-size: 1.6rem;
  font-weight: 700;
}

/* eduction */
.edu_item {
  margin-top: 2rem;
}

/* certification */

.certification_item {
  margin-top: 2rem;
}
/* exp */
.exp_item {
  margin-top: 2rem;
}

/* awards */
.awards_item {
  margin-top: 2rem;
}
@media print {
  .awards,
  .awards_item {
    break-inside: avoid;
    page-break-inside: avoid;
    -webkit-column-break-inside: avoid;
    -webkit-region-break-inside: avoid;
  }
}
/* Interests */
.interest_items {
  margin-top: 2rem;
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  gap: 2rem;
  line-height: 1.5px;
}
.interest_item {
  font-size: 1.5rem;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 0.5rem;
  color: var(--text-color);
}
.interest_item svg {
  width: 2rem;
}

/* socials */
.social_items {
  margin-top: 2rem;
}
.social_item {
  margin-top: 1.5rem;
  font-size: 1.5rem;
  display: flex;
  gap: 0.5rem;
  align-items: center;
  justify-content: flex-start;
  color: var(--text-color);
}
.social_item:hover {
  color: var(--primary-color);
}
.social_item svg {
  width: 2rem;
}
@media print {
  .group-3 {
    break-inside: avoid;
    page-break-inside: avoid;
    -webkit-column-break-inside: avoid;
    -webkit-region-break-inside: avoid;
  }
}

hr {
  grid-column: 1/-1;
  width: 80%;
  margin: 0 auto;
  margin-top: 5rem;
  margin-bottom: 1rem;
  border: none;
  border-top: 2px solid rgba(128, 128, 128, 0.229);
}
@media only screen and (max-width: 768px) {
  hr {
    margin: 0 auto;
  }
}

    </style>
  </head>

  <body>
    <div class="container">
      <div class="profile">
        <div class="profile_container">
          <div>
            <h1 class="profile_name">
              <span class="profile_name_firstName">Dawid</span>
              <span class="profile_name_lastName">Januszko</span>
            </h1>
            <p class="profile_title">QA Software Engineer</p>
            <p class="description profile_description">
              An ambitious software tester with strong understanding of ISTQB,
              experience in manual testing and API fundamentals, ready to
              strengthen the QA team with accuracy, reliability and a
              willingness to learn automation.
            </p>
          </div>
        </div>
      </div>
      <div class="group-1">
        <div class="skills">
          <h3 class="title">Expertise</h3>
          <ul class="skills_list description">
            <li>JavaScript</li>
            <li>TypeScript</li>
            <li>HTML CSS</li>
            <li>REST API</li>
          </ul>
        </div>
        <div class="skills">
          <h3 class="title">Testing and tools</h3>
          <ul class="skills_list description">
            <p>Jira, Trello, Postman,</p>
            <p>Playwright, Dev Tools, SQL</p>
          </ul>
        </div>

        <div class="edu">
          <h3 class="title">Education</h3>
          <div class="edu_item">
            <p class="item_preTitle">2025</p>
            <h4 class="item_title">
              „Becoming a Professional Software Tester”
            </h4>
            <p class="item_subtitle">Udemy</p>
          </div>
          <div class="edu_item">
            <p class="item_preTitle">2025</p>
            <h4 class="item_title">
              „Playwright JS/TS Automation Testing from Scratch & Framework”
            </h4>
            <p class="item_subtitle">Udemy</p>
          </div>
          <div class="edu_item">
            <p class="item_preTitle">2025</p>
            <h4 class="item_title">“SQL basics | MySQL”</h4>
            <p class="item_subtitle">Udemy</p>
          </div>
        </div>

        <div class="certification">
          <h3 class="title">certification</h3>
          <div class="certification_item">
            <p class="item_preTitle">2025</p>
            <h4 class="item_title">
              Certificate ISTQB Certified Tester Foundation Level
            </h4>
            <p class="description">SJSI</p>
          </div>
        </div>
      </div>
      <div class="group-2">
        <div class="exp">
          <h3 class="title">Experience</h3>
          <div class="skills_list description">
            <p class="item_preTitle">01.2025 - present</p>
            <h4 class="item_title">Software tester</h4>
            <p class="item_subtitle">Freelancer</p>
            <p class="description">
              <li>
                Executing manual test (exploratory and practical with test
                cases)
              </li>
              <li>
                Creating test cases based on documentation and user stories
              </li>
              <li>Logging and tracking bugs using Jira and Trello</li>
            </p>
          </div>
          <div class="skills_list description">
            <p class="item_preTitle">02.2020 - 12.2024</p>
            <h4 class="item_title">MJ Builders</h4>
            <p class="item_subtitle">Construction worker</p>
            <p class="description">
              <li>Carrying out renovations and finishing works</li>
              <li>Teamwork and independent decision-making</li>
            </p>
          </div>
        </div>
        <div class="awards">
          <h3 class="title">Skills and qualifications</h3>
          <div class="skills_list description">
            <p class="description">
              <li>
                Very good knowledge of software testing techniques in accordance
                with the ISTQB syllabus
              </li>
              <li>
                Good understanding of agile software development methodologies
                (Scrum, Kanban)
              </li>
              <li>Creating clear and detailed bug reports and test cases</li>
              <li>Familiarity with JavaScript</li>
              <li>Basic knowledge of API testing using Postman</li>
            </p>
          </div>
        </div>
        <div class="awards">
          <h3 class="title">Language skills</h3>
          <div class="skills_list description">
            <p class="description">
              <li>Polish: native</li>
              <li>English: intermediate (B2)</li>
            </p>
          </div>
        </div>

        <div class="interest">
          <h3 class="title">Interest</h3>
          <div class="interest_items">
            <div class="interest_item">
              <i data-feather="music"></i>
              <span>Music</span>
            </div>
            <div class="interest_item">
              <i data-feather="dribbble"></i>
              <span>Basketball</span>
            </div>
            <div class="interest_item">
              <i data-feather="map"></i>
              <span>Travel</span>
            </div>
          </div>
        </div>
      </div>
      <hr />
      <div class="group-3">
        <div class="contact">
          <h3 class="title">Contact</h3>
          <div class="contact_info">
            <p class="description">Cracow, Poland</p>
            <p class="description">+48 535 777 186</p>
            <p class="description">jaanuszkodawid@gmail.com</p>
          </div>
        </div>
        <div class="social">
          <h3 class="title">Socials</h3>
          <div class="social_items">
            <a
              href="https://github.com/Sundzaj/ReadMe"
              target="_blank"
              class="social_item"
            >
              <i data-feather="github"></i>
              <span>/Sundzaj</span>
            </a>
            <a
              href="https://www.linkedin.com/in/dawid-januszko-182a76363/"
              target="_blank"
              class="social_item"
            >
              <i data-feather="linkedin"></i>
              <span>/dawid-januszko-182a76363</span>
            </a>
          </div>
        </div>
      </div>
    </div>
    <p>
      I hereby give my consent for the processing of my personal data for the
      purposes necessary to carry out the recruitment process in accordance with
      the GDPR.
    </p>
    <script>
      feather.replace();
    </script>
  </body>
</html>
