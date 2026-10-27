<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=180&section=header&text=Raul%20Luzetti&fontSize=50&animation=twinkling&fontAlignY=38" alt="Raul Luzetti" width="100%">
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=900&color=58A6FF&center=true&vCenter=true&width=640&lines=Senior+Software+Engineer+%C2%B7+AI%2FML+%26+Full+Stack;LLM+agents+on+MCP+%C2%B7+Claude+Agent+SDK;Sign-language+AI+serving+on+Vertex+AI;Kubernetes+reliability+on+GCP+%26+AWS" alt="Senior Software Engineer, AI/ML and Full Stack. LLM agents on MCP with the Claude Agent SDK. Sign-language AI serving on Vertex AI. Kubernetes reliability on GCP and AWS.">
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,ts,kotlin,rails,react,nextjs,vue,nodejs,fastapi,tensorflow,gcp,aws,kubernetes,docker,terraform,postgres,mongodb,rabbitmq,grafana,githubactions&perline=10" alt="Python, TypeScript, Kotlin, Ruby on Rails, React, Next.js, Vue, Node.js, FastAPI, TensorFlow, Google Cloud, AWS, Kubernetes, Docker, Terraform, PostgreSQL, MongoDB, RabbitMQ, Grafana, GitHub Actions">
</p>

## Some things I've built in the last 5 years

| Project | What it does | Proof | Stack |
|---|---|---|---|
| **CloudCan** | AI support analyst in Slack: reads logs, metrics, databases and code, then posts the diagnosis | **1,900+** investigations in 6 months | <img src="https://skillicons.dev/icons?i=py,aws,kubernetes,docker,terraform" alt="Python, AWS, Kubernetes, Docker, Terraform" height="28"> |
| **Sign-language avatar** | Text in, an avatar signing it out, rendered live on a cloud GPU | **60 fps**, real time | <img src="https://skillicons.dev/icons?i=ts,nodejs,threejs,gcp,docker" alt="TypeScript, Node.js, Three.js, Google Cloud, Docker" height="28"> |
| **NMT pipeline** | Community videos to a deployed translation model, fully automated | **3** sign languages | <img src="https://skillicons.dev/icons?i=py,tensorflow,gcp,githubactions" alt="Python, TensorFlow, Google Cloud, GitHub Actions" height="28"> |
| **GLaDOS** | One API for sign recognition, translation and the avatar video | **348** commits, sole author | <img src="https://skillicons.dev/icons?i=py,fastapi,gcp,docker" alt="Python, FastAPI, Google Cloud, Docker" height="28"> |
| **Mutano** | Marketing banners that build themselves with computer vision | Promo rollouts: **days** to **minutes** | <img src="https://skillicons.dev/icons?i=py,fastapi,opencv,mysql,redis" alt="Python, FastAPI, OpenCV, MySQL, Redis" height="28"> |

<details>
<summary>How the sign-language system fits together</summary>

```mermaid
flowchart LR
  V[Community videos] --> D[Training data<br/>Cloud Functions]
  D --> TR[Training<br/>TensorFlow on GCE VMs]
  TR --> N[NMT serving<br/>Vertex AI, autoscaling]
  U[Apps] --> G[GLaDOS<br/>FastAPI on Cloud Run]
  G --> R[Avatar video<br/>Three.js + FFmpeg<br/>Cloud Run GPU]
  R -->|translate| N
  R -->|gRPC stream| U
  C[Camera<br/>MediaPipe + TF.js] --> G
  G --> I[Sign recognition<br/>Vertex AI]
```

</details>

## Let's talk

<a href="https://www.linkedin.com/in/raulluzetti"><img src="https://img.shields.io/badge/LinkedIn-raulluzetti-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn: raulluzetti"></a>
<a href="mailto:raul.chiodi@gmail.com"><img src="https://img.shields.io/badge/Email-raul.chiodi%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email: raul.chiodi@gmail.com"></a>

<p align="center">
  <img src="https://raw.githubusercontent.com/kylix31/kylix31/output/snake.svg" alt="A snake game eating Raul's contribution graph">
</p>
