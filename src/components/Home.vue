<template>
  <div class="home">
    <div class="wrapper">
      <code>Hello! My name is</code>
      <div class="hero">Keloysius Mak</div>
      <div class="headline">I am a Computer Science student at<br/>the National University of Singapore with a<br/>passion for <strong>solving real-world problems</strong> with technology.</div>
      <div class="json-wrapper">
        <code>
          $ cat profile.json</br></br>
          {
          <ul>
            <li>"github": <a href="https://github.com/keloysiusmak" target="_blank">https://github.com/keloysiusmak</a>,</li>
            <li>"linkedin": <a href="https://linkedin.com/in/keloysiusmak" target="_blank">https://linkedin.com/keloysiusmak</a>,</li>
            <li>"medium": <a href="https://medium.com/@keloysiusmak" target="_blank">https://medium.com/keloysiusmak</a>,</li>
            <li>"twitter": <a href="https://twitter.com/keloysius" target="_blank">https://twitter.com/keloysius</a></li>
          </ul>
          }
        </code>
      </div>
      <div class="alert">Currently looking for <strong>Spring & Summer 2020</strong> Internships!</div>
      <div class="headline">Here's the latest copy of my <a href="https://www.dropbox.com/s/hvj177vi1dodr44/R%C3%A9sum%C3%A9.pdf?dl=0" target="_blank">Résumé</a></div>
      <div class="headline">You can reach me at <a href="mailto:keloysiusmak@gmail.com">keloysiusmak@gmail.com</a></div>
      <div class="feature">
        Work Experience
      </div>
      <div class="listing">
        <div class="img-wrapper">
          <img src="../assets/img/govtech.png" />
        </div>
        <div class="writeup">
          <div class="highlight">Currently here!</div>
          <div class="date"><i>Singapore</i>, Fall 2019</div>
          <div class="title">GovTech</div>
          <div class="position">Software Engineering Intern</div>
          <ul>
            <li>Setup Elasticsearch, Logstash and Kibana (ELK) with Kubernetes on bare-metal</li>
            <li>Optimized binaries for threat hunting platform</li>
            <li>Setup Ubuntu Server and local VCS with Gitlab for threat hunting platform</li>
          </ul>
          <div class="tag-wrapper">
            <div class="tag"><code>Docker</code></div>
            <div class="tag"><code>ELK</code></div>
            <div class="tag"><code>Kubernetes</code></div>
            <div class="tag"><code>Go</code></div>
          </div>
        </div>
      </div>
      <div class="listing">
        <div class="img-wrapper">
          <img src="../assets/img/ninjavan.png" />
        </div>
        <div class="writeup">
          <div class="date"><i>Singapore</i>, Summer 2019</div>
          <div class="title">NinjaVan</div>
          <div class="position">Software Engineering Intern</div>
          <ul>
            <li>Optimized and improved microservices to improve latency</li>
            <li>Created internal tools for endpoint load monitoring with InfluxDb and Chronograf and alert triggering for 40 million daily messages</li>
            <li>Built tools to speed up and assist QA team for publishing and consuming high volumes of Kafka messages</li>
          </ul>
          <div class="article">Medium Stories: <a href="https://medium.com/@keloysiusmak/the-importance-of-people-b914f4289f6a" target="_blank">The Importance of People</a></div>
          <div class="tag-wrapper">
            <div class="tag"><code>ELK</code></div>
            <div class="tag"><code>Go</code></div>
            <div class="tag"><code>Java</code></div>
            <div class="tag"><code>Kafka</code></div>
            <div class="tag"><code>TICK</code></div>
          </div>
        </div>
      </div>
      <div class="listing">
        <div class="img-wrapper">
          <img src="../assets/img/treatsure.png" />
        </div>
        <div class="writeup">
          <div class="date"><i>Singapore</i>, Summer 2018</div>
          <div class="title">Treatsure</div>
          <div class="position">Software Engineering Intern</div>
          <ul>
            <li>Identified security vulnerabilities and implemented token-based security authentication process for production</li>
            <li>Designed and executed the migration from MongoDB to MSSQL in production environments</li>
            <li>Containerized and orchestrated microservices for production to support >1,400 daily active users</li>
          </ul>
          <div class="tag-wrapper">
            <div class="tag"><code>Azure</code></div>
            <div class="tag"><code>Kubernetes</code></div>
            <div class="tag"><code>NodeJS</code></div>
            <div class="tag"><code>OAuth</code></div>
          </div>
        </div>
      </div>
      <div class="listing last">
        <div class="img-wrapper">
          <img src="../assets/img/nuh.jpeg" />
        </div>
        <div class="writeup">
          <div class="date"><i>Singapore</i>, Fall 2017</div>
          <div class="title">National University Hospital</div>
          <div class="position">Software Engineering Intern</div>
          <ul>
            <li>Implemented and deployed a trained deep learning model to assist doctors in predicting the occurrence of Appendicitis</li>
            <li>Deployed a NLP tool in collaboration with PHD researchers to dissect and augment mortality reports with relevant research</li>
            <li>Built an internal repository for PhD Researchers</li>
          </ul>
          <div class="tag-wrapper">
            <div class="tag"><code>Bootstrap</code></div>
            <div class="tag"><code>LAMP</code></div>
            <div class="tag"><code>PHP</code></div>
            <div class="tag"><code>Python</code></div>
          </div>
        </div>
      </div>
      <div class="feature">
        Skills & Coursework
      </div>
      <div class="skills">
        <div class="skill-column">
          <div class="skill-category">
            <div class="title">Programming</div>
            <div class="writeup"><i>(Experienced)</i> Python, Javascript, Java</div>
            <div class="writeup"><i>(Familiar)</i> Swift, PHP, C/C++, Go</div>
          </div>
          <div class="skill-category">
            <div class="title">Platforms</div>
            <div class="writeup"><i>(Experienced)</i> AWS</div>
            <div class="writeup"><i>(Familiar)</i> Azure, GCP</div>
          </div>
          <div class="skill-category">
            <div class="title">Databases</div>
            <div class="writeup">MySQL, MSSQL, InfluxDB, MongoDB, DynamoDB</div>
          </div>
        </div>
        <div class="skill-column">
          <div class="skill-category">
            <div class="title">Frameworks / Stacks</div>
            <div class="writeup">ELK, LAMP, ME(A/R/V)N, TICK</div>
          </div>
          <div class="skill-category">
            <div class="title">DevOps</div>
            <div class="writeup">Chef, Docker, Elasticsearch, Kubernetes, Logstash, Kibana, Travis</div>
          </div>
          <div class="skill-category">
            <div class="title">Tools</div>
            <div class="writeup">Jest, Kafka, Mocha, Serverless</div>
          </div>
        </div>
        <div class="skill-column">
          <div class="skill-category">
            <div class="title">Coursework</div>
            <div class="writeup">Algorithm Design, Artificial Intelligence, Computer Security, Cryptography Theory, Data Structures, Network Architecture, Software Engineering</div>
          </div>
        </div>
      </div>
      <div class="feature">
        Certifications
      </div>
      <div class="certification">AWS Certified Cloud Practitioner</div>
      <div class="certification">Elasticsearch Engineer I / Elasticsearch Engineer II</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
code {
  font-size: 24px;
  color: #777;
  display: inline-block;
}
div.home {
  display: flex;
  justify-content: center;
  margin-top: 100px;
}
div.json-wrapper {
  background-color: #2c3e50;
  border-radius: 20px;
  padding: 20px;
  margin: 40px 0;
  overflow-x: scroll;
  white-space: nowrap;
}
div.json-wrapper::-webkit-scrollbar {
  width: 0 !important;
  overflow: -moz-scrollbars-none;
  -ms-overflow-style: none;
}
div.json-wrapper code {
  color: #FFF;
  font-size: 1.2rem;
}
div.json-wrapper code a {
  color: #FFF;
  text-decoration: none;
}
div.json-wrapper ul {
  list-style-type: none;
}
div.wrapper {
  width: calc(100% - 40px);
  max-width: 800px;
  text-align: left;
  margin: 20px;
  padding: 0 20px;
}
div.feature {
  text-align: left;
  margin: 40px 0;
  padding-top: 40px;
  font-size: 1.5rem;
  border-top: 1px solid #ddd;
}
div.hero {
  font-size: 4rem;
  color: #2c3e50;
  line-height: 4.8rem;
  margin: 5px 0;
}
div.headline strong {
  color: #444;
}
div.headline {
  font-size: 1.2rem;
  color: #777;
}
div.headline a {
  color: #71a6ea;
  font-weight: bold;
  text-decoration: none;
}
div.listing {
  padding-bottom: 20px;
  border-bottom: 1px solid #eee;
  margin-bottom: 20px;
  display: flex;
  flex-direction: row;
  width: calc(100% - 0px);
}
div.listing.last {
  border-bottom: 0;
}
@media only screen and (max-width: 600px) {
  div.listing .img-wrapper {
    display: none;
  }
}
div.listing .img-wrapper {
  width: 120px;
  padding-right: 20px;
}
div.listing .img-wrapper img{
  width: 100%;
}
div.listing .writeup {
}
div.listing .writeup ul {
  list-style-type: circle;
}
div.listing .writeup .date {
}
div.listing .writeup .highlight {
  background-color: #71a6ea;
  color: #fff;
  padding: 5px 20px;
  font-size: 0.8rem;
  border-radius: 5px;
  margin: 5px 0;
  display: inline-block;
}
div.listing .writeup .title {
  font-weight: bold;
  font-size: 2rem;
}
div.listing .writeup .position {
}
div.listing .writeup .article {
  font-size: 0.8rem;
  color: #444;
}
div.listing .writeup .article a {
  color: #71a6ea;
  font-weight: bold;
  text-decoration: none;
}
div.listing .writeup .tag-wrapper {
  margin: 30px 0 10px 0;
  overflow-x: scroll;
}
div.listing .writeup .tag-wrapper::-webkit-scrollbar {
  width: 0 !important;
  overflow: -moz-scrollbars-none;
  -ms-overflow-style: none;
}
div.listing .writeup .tag-wrapper .tag {
  border-radius: 5px;
  border: 1px solid #ddd;
  padding: 10px 20px;
  text-align: center;
  display: inline-block;
  margin: 0px 10px 10px 0;
  width: auto;
}
div.listing .writeup .tag-wrapper .tag:first-of-type {
  margin-left: 0;
}
div.listing .writeup .tag-wrapper .tag:last-of-type {
  margin-right: 0;
}
div.listing .writeup .tag-wrapper .tag code{
  color: #000;
  font-size: 1.2rem;
}
div.alert {
  border-radius: 10px;
  padding: 10px 20px;
  font-size: 0.8rem;
  background-color: #f4f4f4;
  display: inline-block;
  margin: 0 0 10px 0;
}
div.skills {
  display: flex;
}
div.skills .skill-column {
  width: 30%;
  margin-right: 5%;
}
@media only screen and (max-width: 800px) {
  div.skills {
    display: block;
  }
  div.skills .skill-column {
    width: 100% !important;
  }
}

div.skill-category {
  margin-bottom: 2rem;
}
div.skill-category .title {
  font-weight: bold;
  font-size: 1.2rem;
}
div.skill-category .writeup {
  font-size: 1rem;
}
div.skill-category .writeup i {
  font-size: 0.8rem;
  color: #777;
}
</style>
