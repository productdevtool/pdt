<p align="center">
    <img align="center" width="480" height="270" alt="PDT" src="https://github.com/user-attachments/assets/b1b05e40-d398-47cc-82a0-a1f1dd4946e5" />
</p>

<div align="center">
    <h1>Product Dev Tool</h3>
    <h4><em>pdt is an opinionated, AI-native toolkit for founders to get from idea to first paying customer, faster.</em></h4>
    <h4><em>It's not just about generating code; it's about building a business.</em></h4>
</div>

Building a new venture is a battle against time and complexity. Founders have great ideas, but the friction between that idea and a market-ready product—complete with a marketing site, user authentication, payments, and documentation—is immense.

PDT is designed to eliminate that friction. It's an all-in-one, open-source system that turns a generic AI assistant into a specialized, highly effective system builder, allowing you to act as a strategic director, not a tactical programmer.

## Our Philosophy

Our approach is guided by four core beliefs about what it takes to build a successful product in the age of AI.

> ### 1\. Build Products, Not Projects.
>
> A project can be a hobby. A product is built to be sold. This philosophy is at the core of PDT. Every feature, from the pre-configured payments in the starter kit to the `pdt write` command for generating marketing content, is designed to move you closer to a commercially viable business that solves a real-world problem.

> ### 2\. The Fastest Path from Idea to Revenue.
>
> Your primary bottleneck isn't writing code—it's the entire lifecycle of shipping a feature. Generating code is only one piece of the puzzle. PDT is designed to expedite the *entire path* from `idea -> spec -> code -> tests -> docs -> marketing`. It's a holistic system for building and selling, not just an AI wrapper.

> ### 3\. An Opinionated Workflow, Not Vibe Coding.
>
> Your tools should make you better at your job. Simply prompting a generic AI is inconsistent and unpredictable. PDT introduces a structured, repeatable workflow. Through clear commands (`pdt spec`, `pdt code`), architectural guardrails, and high-quality templates, we ensure the AI's output is always consistent, high-quality, and aligned with your project's architecture.

> ### 4\. Expert Tooling, No Pro Toolchain Required.
>
> Building a modern product is hard enough without having to become an expert in a professional developer's toolchain (CI/CD, webpack, testing frameworks, etc.). PDT provides this expert context *for* you, abstracting away the complexity so you can focus on your vision and your customers. It's built for the long tail of founders and builders who are experts in their domain, not necessarily in software engineering.


## The Workflow

The PDT workflow elevates you from programmer to director. You define the "what," and PDT orchestrates the "how."

1.  **Plan a Feature:** Use an interactive prompt to create a detailed feature plan.
    ```bash
    pdt spec "Allow users to upload a profile picture"
    ```
2.  **Build the Feature:** Instruct the AI to build the feature according to the plan and your architectural rules.
    ```bash
    pdt code specs/004-profile-picture.md
    ```
3.  **Test the Feature:** Instruct the AI to write unit and integration tests.
    ```bash
    pdt test specs/004-profile-picture.md
    ```
4.  **Market the Feature:** Instruct the AI to write marketing content to announce your new feature.
    ```bash
    pdt write blog "New! Personalize Your Profile with Avatars"
    ```

## Quick Start

Get your new venture running in under 5 minutes.

1.  **Clone the Starter Kit:** This repo contains a production-ready Next.js & Convex application.
    ```bash
    git clone https://github.com/productdevtool/pdt-starter.git my-awesome-product
    cd my-awesome-product
    ```
2.  **Install the CLI:** Get the PDT command center.
    ```bash
    # Installation instructions will go here (e.g., go install, brew, etc.)
    ```
3.  **Start Building:** Define your first feature and let PDT build it.
    ```bash
    pdt spec "User login with Google"
    ```

## Our Repositories

The PDT ecosystem is composed of a few key repositories:

  * **`pdt` (You are here):** The main hub containing our website, documentation, and community information.
  * **`pdt-cli`:** The Go-based command-line tool that orchestrates the development process.
  * **`pdt-starter`:** The core boilerplate application that you clone to start your own business.

## Community & Contributing

PDT is an open-source project, and we welcome contributions of all kinds.

  * _Join our community. (coming soon)_
  * _Read our Contributing Guidelines to get started. (coming soon)_
