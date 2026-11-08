<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:00BFFF&height=200&section=header&text=Yehia%20Gewily&fontSize=56&fontColor=ffffff&fontAlignY=36&desc=Backend%20and%20AI%20Infrastructure%20Engineer&descSize=18&descAlignY=56&animation=fadeIn" width="100%" alt="Yehia Gewily, Backend & AI Infrastructure Engineer"/>

<div align="center">

  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=2500&pause=800&color=00BFFF&multiline=true&repeat=false&width=520&height=140&lines=%24+whoami;Yehia+Gewily%2C+founding+engineer+at+Nover;%24+cat+focus.txt;Backend+%C2%B7+GPU+inference+%C2%B7+LLM+agents+%C2%B7+streaming;%24+echo+%24MOTTO;I+build+the+parts+of+a+product+nobody+sees." alt="$ whoami: Yehia Gewily, founding engineer at Nover. Focus: backend, GPU inference, LLM agents, streaming."/>

  <p>
    <a href="mailto:yehiasaidgewily@gmail.com"><img src="https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=EA4335&labelColor=0d1117" alt="Email"/></a>
    <a href="https://www.linkedin.com/in/yehia-gewily-7545231a6/"><img src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=0A66C2&labelColor=0d1117" alt="LinkedIn"/></a>
    <a href="https://yehia-gewily.me"><img src="https://img.shields.io/badge/Website-0d1117?style=for-the-badge&logo=googlechrome&logoColor=00BFFF&labelColor=0d1117" alt="Website"/></a>
  </p>

</div>

---

## About

I build the parts of a product nobody sees: the APIs, the queues, the GPU pipelines, and the infrastructure that keeps them running.

These days that mostly means AI systems: fine-tuning models, serving them on GPUs at scale, and connecting LLM agents to real products.

I can work across the stack when needed, but backend and AI infrastructure are where I go deep.

## Experience

- **[Nover](https://nover.studio)** · Founding Engineer & Tech Lead *(current)*<br>
  Built and run the ML stack for an AI image generation platform: fine-tuning diffusion models on H100s, serving them through ComfyUI on autoscaled AWS GPU instances, and the WebSocket APIs and job orchestration around them. Took the product from early development to public waitlist launch.

- **RankUp** · Backend & Data Automation *(EU, remote)*<br>
  Automated SEO keyword research and clustering with SBERT and DataForSEO, cutting manual strategy work by 40%. Added API cost tracking and structured logging.

- **U LLC** · Software Engineer *(Ohio, remote)*<br>
  Built a real-time EEG digital twin pipeline on streamed OpenBCI data, and wrote a research paper on Kuramoto-based EEG synchronization.

- **Mind Cloud Robotics** · Chairman & Vice Chairman<br>
  Led a team of 70+ engineers to 2nd and 3rd place at UGVC and 9th at ERC, and moved the robot software to a distributed ROS 2 setup.

---

## Stack

**Backend & APIs**<br>
<img src="https://skillicons.dev/icons?i=fastapi,django,flask,spring,nodejs,express,graphql" height="40" alt="FastAPI, Django, Flask, Spring, Node.js, Express, GraphQL"/> &nbsp; + gRPC · WebSockets · REST

**AI & ML**<br>
<img src="https://skillicons.dev/icons?i=pytorch,tensorflow" height="40" alt="PyTorch, TensorFlow"/> &nbsp; + CUDA · Hugging Face · ComfyUI · Modal · LangGraph · LangSmith

**Data & Messaging**<br>
<img src="https://skillicons.dev/icons?i=redis,kafka,postgres,mongodb,cassandra" height="40" alt="Redis, Kafka, PostgreSQL, MongoDB, Cassandra"/> &nbsp; + Flink · Airflow · RabbitMQ

**Infrastructure & DevOps**<br>
<img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,terraform,githubactions,nginx,linux,prometheus,grafana,cloudflare" height="40" alt="AWS, Docker, Kubernetes, Terraform, GitHub Actions, Nginx, Linux, Prometheus, Grafana, Cloudflare"/>

**Languages**<br>
<img src="https://skillicons.dev/icons?i=py,go,rust,ts,js,cpp,c,java,matlab,bash" height="40" alt="Python, Go, Rust, TypeScript, JavaScript, C++, C, Java, MATLAB, Bash"/>

**Also comfortable with**

- **Systems testing:** GoogleTest, libFuzzer, ASan/UBSan, CMake, libpcap, mbedTLS
- **Robotics & embedded:** ROS 2, Arduino, Raspberry Pi, ESP8266, Embedded C
- **Data:** Pandas, NumPy, SciPy
- **Frontend:** React, Next.js, Tailwind (enough to ship a UI over my own APIs)

---

## Projects

### Backend & Infrastructure

- **[Go Distributed Queue](https://github.com/YehiaGewily/Go-distributed-queue)**: Fault-tolerant task queue with crash recovery, priorities, delayed jobs, and dead-letter queues. Chaos-tested.<br>`Go` `Redis` `Prometheus`
- **[Agent Mesh](https://github.com/YehiaGewily/Agent-Mesh)**: Orchestration engine handling 750+ requests/sec under 200 ms, with a live 60 Hz React dashboard.<br>`Go` `Redis` `React` `WebSockets`
- **[EnvGuardian](https://github.com/YehiaGewily/EnvGuardian)**: Keeps `.env` files encrypted in Git using age/SSH keys, with signed changes, safe key rotation, and 80%+ test coverage.<br>`Go` `age` `Cobra`
- **[Real-Time Arbitrage Engine](https://github.com/YehiaGewily/real-time-arbitrage-engine)**: Streams Coinbase and Binance prices through Kafka, spots BTC price gaps with Flink, and sends alerts to Discord and a dashboard.<br>`Python` `Kafka` `Flink` `Docker`

### AI & ML

- **[Nabda](https://github.com/Nabda-Project)** *(capstone)*: Heart-monitoring platform with a custom ESP8266 wearable and real-time alerts, plus an Arabic clinical intake and diagnostic assistant built on a fine-tuned Qwen3-4B.<br>`Qwen3-4B` `Fine-tuning` `Spring Boot` `Flutter` `Next.js`
- **[Agentic LLM Architectures](https://github.com/YehiaGewily/Agentic-LLM-Architectures)**: 12 agent design patterns (reflection, planning, tool use, multi-agent) built as reusable LangGraph workflows, with retrieval, web search, and tracing.<br>`Python` `LangGraph` `Chroma` `LangSmith`
- **[Physics-AI Bridge](https://github.com/YehiaGewily/Physics-AI-Bridge)**: 2D Ising model simulation, extended to Hopfield networks for associative memory.<br>`Python` `NumPy`

### Systems & Simulation

- **[CerebralFlow](https://github.com/YehiaGewily/CerebralFlow)**: Rebuilds brain networks from signals and simulates them as coupled oscillators.<br>`Python` `SciPy`

- **[NetProbe](https://github.com/YehiaGewily/netprobe-cpp)**: Network traffic analyzer with live capture, QUIC SNI decryption, GeoIP lookup, per-process tracking, and a desktop dashboard.<br>`C++20` `Npcap` `Dear ImGui`
- **[THAAD Simulation](https://github.com/YehiaGewily/THAAD-Simulation)**: 3D missile interceptor simulation with Kalman-filtered radar tracking and replayable engagements.<br>`Python` `NumPy`

### Small Tools

- **[Fourier Epicycle Machine](https://github.com/YehiaGewily/The-Fourier-Epicycle-Drawing-Machine)**: Draw any shape and watch rotating circles redraw it in real time.<br>`JavaScript` `p5.js`
- **[dot-spend](https://github.com/YehiaGewily/dot-spend)**: Minimal terminal expense tracker with ASCII charts and CSV export.<br>`Python`

---

## GitHub Stats

<div align="center">
  <img src="https://github-readme-stats-coral-two-59.vercel.app/api?username=YehiaGewily&show_icons=true&theme=shadow_green&hide_border=true&show_rank=true&rank_icon=github&bg_color=0d1117&title_color=00BFFF&icon_color=00BFFF&text_color=c9d1d9" height="165" alt="GitHub stats"/>
  <img src="https://streak-stats.demolab.com/?user=YehiaGewily&theme=shadow_green&hide_border=true&background=0d1117&stroke=00BFFF&ring=00BFFF&fire=00BFFF&currStreakLabel=00BFFF" height="165" alt="GitHub streak"/>
  <br>
  <img src="https://github-readme-stats-coral-two-59.vercel.app/api/top-langs/?username=YehiaGewily&theme=shadow_green&hide_border=true&layout=compact&bg_color=0d1117&title_color=00BFFF&text_color=c9d1d9" alt="Top languages"/>
  <br>
  <img src="./profile-3d-contrib/profile-customize.svg" width="100%" alt="3D contribution graph"/>
</div>

---

<div align="center">
  <em>Building infrastructure that has to actually work? I'd love to hear about it.</em>
  <br><br>
  <a href="mailto:yehiasaidgewily@gmail.com"><strong>yehiasaidgewily@gmail.com</strong></a>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00BFFF,100:0d1117&height=120&section=footer" width="100%" alt=""/>
