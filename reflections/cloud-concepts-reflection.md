# Cloud Concepts & Version Control Reflection

## 1. Cloud Services I Use Daily
In my daily life, I interact with several cloud applications across different service and deployment models:

1. **Google Drive / Google Docs**
   - **Service Model:** Software as a Service (SaaS). It provides a complete, ready-to-use software application through a web browser without requiring infrastructure setup.
   - **Deployment Model:** Public Cloud. It is hosted on Google’s infrastructure and accessible over the public internet to subscribers worldwide.

2. **Canva**
   - **Service Model:** Software as a Service (SaaS). It offers web-based graphic design tools and templates directly to end-users over the internet.
   - **Deployment Model:** Public Cloud. Accessible globally via web browsers and mobile applications.

3. **Unity / Vercel (or GCash / Netflix)**
   - **Service Model:** Platform as a Service (PaaS) / SaaS. Tools like Vercel or cloud deployment platforms allow developers to deploy applications without managing underlying operating systems or servers.
   - **Deployment Model:** Public Cloud. The services run on shared cloud infrastructure available over the internet.

---

## 2. Importance of Git & GitHub in Cloud Projects
Version control systems like Git, combined with platforms like GitHub, are critical in modern cloud infrastructure management. Cloud resources are increasingly defined using code (Infrastructure as Code - IaC). Managing cloud configurations through repository tools ensures several key benefits:

- **Tracking Changes & History:** GitHub keeps an exact audit log of who changed infrastructure settings, when, and why. If a misconfiguration causes downtime, teams can quickly inspect commits and rollback to a previous working state.
- **Team Collaboration:** Multiple developers or system administrators can work on the same project using branches and pull requests without overwriting each other's work. Code reviews ensure changes are validated before deployment.
- **Automated Workflows (CI/CD):** Integration between GitHub and cloud platforms enables continuous deployment. When code is pushed to a repository, automated scripts can test, build, and deploy cloud resources reliably, minimizing human error.
