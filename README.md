# blackdagger-github-infra

<p align="center">
  <img src="https://github.com/ErdemOzgen/blackdagger/blob/main/assets/images/blackdaggerReadme.png" width="500" alt="blackdagger-logo">
</p>

### GitHub Runner-Powered DAST Scanning

Blackdagger-github-infra revolutionizes traditional DAST by leveraging GitHub Actions runners, significantly enhancing operational security (OPSEC). This method allows penetration testers and Red Team operators to perform scans and execute simulated attacks from GitHub's trusted infrastructure, thereby reducing the likelihood of detection by web defenses and IP-based blocking mechanisms. By simply forking the provided default GitHub repository and configuring your GitHub token within the BPTK DAST settings, you ensure stealthy, uninterrupted, and effective security testing with minimized risk of alerting defensive measures or leaving traceable digital footprints.

![](./imgs/arch.png)


# Blackdagger: Cyber Workflow Automation Framework
Blackdagger is a single binary tool that is capable of managing and automating complex workflows for various purposes. To improve the experience of users while using Blackdagger, various repositories that contains tested YAML files for complex workflows, easy-to-setup infrastructure for CART and DevSecOps purposes are suggested by the team. With major additions to these repositories, everything that makes Blackdagger better is collected under a framework called Blackdagger: Cyber Workflow Automation Framework.

The framework consist of 5 components:

- [**Blackdagger:**](https://github.com/ErdemOzgen/blackdagger) Core of the framework for orchestrating the components and workflows
- [**Blackcart:**](https://github.com/ErdemOzgen/blackcart) A specialized Docker container optimized for Continuous Automated Red Teaming (CART) and DevSecOps pipeline tasks.
- **Blackdagger YAMLs:** Pre-tested [example](https://github.com/ErdemOzgen/blackdagger-default) workflows, demonstrating real-world [DevSecOps](https://github.com/ErdemOzgen/blackdagger-devsecops) and [CART](https://github.com/ErdemOzgen/blackdagger-cart) use-cases, facilitating quick adoption and adaptation.
- [**Blackdagger Github Infra (this repository):**](https://github.com/ErdemOzgen/blackdagger-github-infra) A suite of advanced workflows utilizing GitHub Actions infrastructure for enhanced defense evasion techniques, scalability, and performance.
- [**Blackdagger Web Kit :**](https://github.com/ErdemOzgen/blackdagger-web-kit) A browser extension integrating all core functionalities, enabling direct interaction and execution of Blackdagger workflows from within the browser.

<p align="center">
  <img src="https://github.com/ErdemOzgen/blackdagger/blob/main/assets/images/framework_diagram.png" width="500" alt="framework-diagram">
</p>

Each component is compatible with each other to run on **any environment, for any case and as easy, fast and effective as possible.** The framework also enables adding, removing or modifying components to add extra features for new purposes.

Available YAML configurations in `github-yamls` directory:

- [amas.yaml](github-yamls/amas.yaml)
- [assetfinder.yaml](github-yamls/assetfinder.yaml)
- [bbot.yaml](github-yamls/bbot.yaml)
- [certgrabber.yaml](github-yamls/certgrabber.yaml)
- [ffuf.yaml](github-yamls/ffuf.yaml)
- [gau.yaml](github-yamls/gau.yaml)
- [httprequest.yml](github-yamls/httprequest.yml)
- [httpx.yaml](github-yamls/httpx.yaml)
- [iis-scanner.yaml](github-yamls/iis-scanner.yaml)
- [java-iis.yaml](github-yamls/java-iis.yaml)
- [nuclei-scan.yml](github-yamls/nuclei-scan.yml)
- [nuclei-scanV2.yml](github-yamls/nuclei-scan2.yml)
- [subfinder.yaml](github-yamls/subfinder.yaml)
- [zap-api-scanner.yaml](github-yamls/zap-api-scanner.yaml)
- [zap.yaml](github-yamls/zap.yaml)