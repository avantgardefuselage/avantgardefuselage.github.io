+++
author = "JB"
framed = true
+++
```yaml
joshua@se-stv-bjo-111:~$ cat about.yml | yq .basics
name: Joshua Björkäng
email: joshua@bjorkang.family
location: Gothenburg, Sweden
linkedin: https://linkedin.com/in/jbjorkang

joshua@se-stv-bjo-111:~$ cat job.yml | yq .blurb
employed: true
job:
  name: Mullvad VPN AB
  title: Senior Integration Engineer
  description: |
    Aiding with the integration and deployment
    of the VPN infrastructure for the most privacy
    respecting VPN service on the planet.

joshua@se-stv-bjo-111:~$ cat hard-skills.json | jq .technical
{
    "iac": [
        "ansible",
        "puppet"
    ],
    "script": [
        "python",
        "bash"
    ],
    "linux": [
        "ubuntu",
        "debian",
        "rhel"
    ],
    "misc": [
        "bare-metal",
        "vm"
    ],
}

joshua@se-stv-bjo-111:~$ cat soft-skills-interests.yml
---
misc-interests:
  - Business strategy
  - UX & UI design
  - Privacy & computer security
soft-skills:
  - Management and leadership
  - Public speaking
  - Technical copywriting
```
---
