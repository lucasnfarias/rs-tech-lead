# rs-tech-lead
Eduacational repository related to Rocketseat Tech Lead Course

## Tech Lead Cornerstones
<img width="532" height="463" alt="image" src="https://github.com/user-attachments/assets/685ab74f-f87a-45cc-a0c9-5cd746d77c04" />

- **Technical mastery:** Informed decisions, architecture, guide team to use the best quality patterns
  - e.g. Imagine starting and leading a new project development without a solid knowledge about the language or framework. It'll result in wrong decisions, a bunch of errors/bugs and team demotivation. 
- **Communication & Collaboration:** Goal alignments, conflicts resolution and team work/engagement. Encourage a collaborative culture.
  - e.g. When implement a new technology, it is crucial to communicate the benefits, align expectations and incorporate team feedback to transition smoothly 
- **Strategic View & Innovation:** Competive market, business alignment and encourage team innovation.
  - e.g. Migrate to cloud or adopt AI rquires to evaluate how these technologies will benefit the company in the long run, as well as planning its implementation strategically
 
## System Architecture
- Tools:
  - Mermaid: diagrams
  - Confluence, Notion and README: documentation
  - Grafana: Monitoring & Observability
 
- E.g. A new ecommerce application that will go on Black friday
  - https://github.com/rocketseat-education/tech-lead/blob/main/gestao_tecnica_e_arquitetura/arquitetura_de_sistemas/README.md
  - Improvements:
    -  Performance bottlenecks: API gateway, separate checkout and payment service (assynchronous)
    -  Maintance issues: separate modules
    -  Issues integrating new modules: separate modules by domain/business rules
   
## Technical Scope
<img width="855" height="734" alt="image" src="https://github.com/user-attachments/assets/455c545f-a872-454e-96c3-6f64914b6704" />

## Code Review
- Tech Lead has a bigger responsability than regular devs when reviewing code
- Scalability, Maintainability and Continuous quality
- Effective to block introduction of technical debts that can grow exponentially
- Identify possible security risks and vulnerabilites
- Promote a culture to identify security flaws like authentication, data validation and API security
- Excellent opportunity to professional growth and mentorship. Take advantage to share the knowledge inside the team. Verify errors, but also orient, teach and give examples.
- Define quality and technical patterns (e.g. variable naming, big-o, tests, ...)
- Positive culture: see code review as an opportunity to learn and collaborate and not to criticize. It's ok to make mistake and learn from them
- Code review is present on all layers: planning, testing, refinement, implementation and maintanance

- **How to make it efficient:**
  - Set the quality standard, scalability and security
  - Keys Points:
    - Readability and maintainability
      - e.g.separate responsabilities (checkout, payment, stock, ...) 
    - Performance
      - e.g. async loops forEach to Promise.all, db transactions
    - Security
      - e.g. input data validation, db transactions
    - Scalability
      - e.g. loops, big-o, parallelism, ... 
    - Testability
      - e.g. automated tests
  - Positive feedback culture
    - Encourage feedback
    - Focus on continuous learning
    - Safe environment

### Conventional Commits
- https://www.conventionalcommits.org/en/v1.0.0/
- How to structure a commit message
- Why use it?
  - Automatically generating CHANGELOGs.
  - Automatically determining a semantic version bump (based on the types of commits landed).
  - Communicating the nature of changes to teammates, the public, and other stakeholders.
  - Triggering build and publish processes.
  - Making it easier for people to contribute to your projects, by allowing them to explore a more structured commit history.
- Enforce and verify on your project with https://commitlint.js.org/   
