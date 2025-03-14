# blackdagger-github-infra

<p align="center">
  <img src="https://github.com/ErdemOzgen/blackdagger/blob/main/assets/images/blackdaggerReadme.png" width="500" alt="blackdagger-logo">
</p>

### GitHub Runner-Powered DAST Scanning

Blackdagger-github-infra revolutionizes traditional DAST by leveraging GitHub Actions runners, significantly enhancing operational security (OPSEC). This method allows penetration testers and Red Team operators to perform scans and execute simulated attacks from GitHub's trusted infrastructure, thereby reducing the likelihood of detection by web defenses and IP-based blocking mechanisms. By simply forking the provided default GitHub repository and configuring your GitHub token within the BPTK DAST settings, you ensure stealthy, uninterrupted, and effective security testing with minimized risk of alerting defensive measures or leaving traceable digital footprints.

![](./imgs/arch.png)

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