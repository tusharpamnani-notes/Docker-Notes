# Microservices Architecture

- **Definition:** A variant of the service-oriented architecture (SOA) structural style that organizes an application as a collection of loosely coupled services.

- **Characteristics:**
  - Fine-grained services with specific responsibilities.
  - Lightweight protocols.
  
## Monolithic Architecture

- **Characteristics:**
  - Built, deployed, and duplicated as a single unit.

## Microservices

- **Characteristics:**
  - Segregates functionality into small, separate services.
  - Each service has a single responsibility.
  - Independently deployable and scalable.
  - Loosely coupled.
  - Supports autonomous development by different teams, languages, and platforms.
  - Enables smaller team ownership of microservices and their data.

## Transition from Monolith to Microservices

- **Approach:**
  - Break the application/system into smaller units.
  - Use the strangler pattern for gradual migration.

  ![Strangler Approach](https://github.com/tusharpamnani-notes/Docker-Notes/blob/main/assets/strangler.png)

## Microservices - Benefits

- Improved fault isolation.
- Elimination of vendor or technology lock-in.
- Ease of understanding.
- Smaller and faster deployments.
- Scalability.

## Microservices - Drawbacks

- Added complexity to resolve existing complexity issues.
- Testing and deployment challenges.
- Impact on multiple microservices during updates.
- Management of multiple databases.
- Potential for latency issues, transient errors, and multiple points of failure.
- Security concerns.

## Recommendations

- **Training and Proof of Concepts:** Ensure teams are trained and have practical experience.
- **Start Simple:** Avoid complex infrastructures initially.
- **Testing and Deployment Considerations:** Carefully assess the simplicity of testing and deployment.
- **Coordination Challenges:** Address challenges with coordination among multiple teams.
- **Data Management:** Consider the implications of multiple databases and data ownership.
- **Addressing Latency and Failures:** Be prepared to handle latency, transient errors, and multiple points of failure.
- **Security Measures:** Prioritize security considerations in a microservices environment.
