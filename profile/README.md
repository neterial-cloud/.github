### [Neterial - Your app. Your cloud. Vibe deploy in minutes](https://neterial.io/)

**[Documentation](https://docs.neterial.io)**

#### Projects

- **[Neterial CLI](https://github.com/neterialio/cli)** — create and manage k3s clusters from the command-line

#### About

Neterial is a deployment automation layer that provides a PaaS-like workflow on your own cloud infrastructure. It connects directly to your GitHub account and your chosen cloud provider (AWS or Hetzner), acting as a control plane to automate the entire deployment process. The core function is to bridge the gap between a git push and a running application, giving developers the convenience of a managed platform without surrendering ownership of their hardware.

The project was created to solve the fundamental trade-offs of modern deployment solutions. All-in-one PaaS platforms (e.g., Vercel, Heroku) offer a great developer experience but result in opaque, unpredictable pricing, high vendor lock-in, and a complete lack of infrastructure control. The alternative, a fully DIY approach on a cloud provider, offers total control but introduces significant DevOps complexity and maintenance overhead. Neterial is designed to offer the best of both worlds: a streamlined, automated workflow on infrastructure you fully own and control.

Under the hood, Neterial automates the provisioning of a VM in the user's cloud account and configures a lightweight, production-ready K3s cluster inside it. A GitHub integration monitors your repository for new commits, triggering automated builds and deployments. The platform includes zero-config templates for popular frameworks (Next.js, etc.), a full-featured CLI for terminal-based management, and a web console for observing deployment history, and managing infrastructure.
