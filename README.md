# Nick's system design library
For excalidraw.com drawing tool. I wanted to provide extensive, stylish, one-and-only system design components library to build beautiful and precise diagrams.

Usage: download .excalidrawlib file, drag and drop it onto browser tab with excalidraw open.

Here is a showcase with a 3 minute draft of some yet another AI service:
<img width="1714" height="1027" alt="image" src="https://github.com/user-attachments/assets/f96bb6c5-1a61-48b6-8285-0877e0ef64de" />

## Components
### Service architecture
<img width="386" height="387" alt="image" src="https://github.com/user-attachments/assets/3c231f09-b87e-4773-bca8-d62b3f4db8a0" />

Services — base building blocks of complex systems.
- **Service instance**
- **Service layer**
- **Scaled service**
- **Auth service**
- **Payment service**
- **Inference (AI) service**
- **Edge node/service**
- **CRON job**
- **Serverless function**

Appendices — add them to any block to highlight advanced behavior.
- **Retry policy appendix**
- **Outbox messaging appendix**
- **Rate limiter appendix**
- **Circuit breaker appendix**

### Databases
<img width="378" height="400" alt="image" src="https://github.com/user-attachments/assets/2ddb133e-1890-42bd-be3c-4b9de28242d7" />

Database selection of many flavors. Queues and patterns included!
- **Generic Database**
- **Relational Database**
- **Cache (appendix)**
- **Document storage**
- **Message Queue**
- **CQRS database pattern**
- **Hyper scale database (consistent hashing)**
- **Object storage**
- **Key-Value storage**
- **Text index (search)**
- **Columnar database**
- **Cold storage**
- **Graph database**
- **Timeseries database**
- **Vector database**

### Cloud
<img width="389" height="116" alt="image" src="https://github.com/user-attachments/assets/3ecfad6a-c8df-49ca-9d58-2930a6c52174" />

- **Generic cloud**
- **CDN**
- **Cloud payment**
- **Cloud inference (AI)**

### Users
<img width="386" height="216" alt="image" src="https://github.com/user-attachments/assets/78a9edec-deb1-4bff-8d5f-ccd0c4d61888" />

- **Generic user**
- **User group**
- **Web browser**
- **A laptop**
- **A smartphone**

### Infra and Misc
<img width="392" height="313" alt="image" src="https://github.com/user-attachments/assets/26cd2138-8963-4d36-bdd1-e3b6f0fed53d" />

Crucial components that don't really fit into other groups.
- **Load balancer**
- **Observability stack** - Logs, metrics, traces, alerts
- **Process chain**
- **DNS**
- **Proxy**
- **Hardware server**
- **Business Process Modeling** - e.g. Camunda
- **Map-Reduce pattern**

Badges to highlight flows and statuses.
- **Ok badge**
- **Warning badge**
- **Error badge**
