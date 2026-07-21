---
layout: page
title: Can We Trust AI Evaluation?
subtitle: "Robustness, Causality, and Risk in Modern AI Assessment"
use-site-title: true
---
<div class="venue" style="font-size: 27px; display: block; font-family: 'Open Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif; font-weight: 300; color: #404040; text-align: center;">
  NeurIPS 2026, Sydney, Australia, December 11 or 12, 2026
</div>



# News
* The call for papers draft is available.
* OpenReview submission site: TBA.
* Workshop date, room, and final program: TBA.



# Overview

Modern AI systems are judged through benchmarks, aggregate scores, and public leaderboards, but these signals can be fragile under newly collected test sets, repeated benchmark use, small perturbations, underreported variance, leakage, and contamination. This workshop asks when AI evaluation evidence is strong enough to guide deployment decisions, bringing together researchers and practitioners working on uncertainty and robustness, benchmark and leaderboard auditing, measurement and causal validity, judge reliability, application-domain evaluation, and deployment risk and governance.

We invite submissions on topics including, but not limited to:

- **Uncertainty and robustness:** How stable are evaluation conclusions under sampling variation, calibration error, random seeds, data splits, prompts, metrics, evaluator choices, noisy or delayed feedback, tail risk, and worst-case behavior?
- **Benchmark and leaderboard auditing:** How do benchmark reuse, contamination, leakage, documentation gaps, lifecycle practice, public incentives, and benchmark-specific optimization affect the trustworthiness of evaluation claims?
- **Measurement and causal validity:** What construct is an evaluation protocol intended to measure, what ground truth does it rely on, and what causal, structural, or statistical assumptions connect the protocol to the claim?
- **Stress tests and judge reliability:** How should evaluations assess protocol robustness, ambiguous labels, human-, crowd-, and model-judge reliability, and failure modes in evaluation pipelines?
- **Application-domain evaluation:** How should evaluation protocols be designed and audited for domain-specific settings such as medicine and healthcare, finance, science, robotics, cybersecurity, education, public-sector decision-making, and other high-stakes applications?
- **Deployment risk and governance:** When do offline metrics support real-world model selection, safety claims, monitoring, and deployment decisions, and what decision-aware metrics, fairness--accuracy--risk trade-offs, reporting checklists, auditing guidelines, and deployment criteria are needed?

See the [Call for Papers]({{ site.baseurl }}/cfp/) for details.

### Important Dates (Indicative)

**Paper submission opens:** TBA <br>
**Paper submission deadline:** August 29, 2026 (AoE) <br>
**Review deadline:** September 14, 2026 (AoE) <br>
**Author notification:** September 22, 2026 (AoE) <br>
**Final program posted:** September 27, 2026 <br>
**Workshop:** December 11 or 12, 2026


<hr>

# Speakers & Panelists
<div class="container" style="margin-top: 20px;margin-bottom: 0px;">
  <div class="row">
    {% for p in site.data.speakers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    {% endfor %}
  </div>
</div>

Talk titles and panel details will be announced after the final program is confirmed.

<hr>

# Organizers

<div class="container" style="margin-top: 25px;margin-bottom: 40px;">
  <div class="row">
    {% for p in site.data.organizers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    {% endfor %}
  </div>
</div>
<hr>


# Sponsors

<div class="sponsor-logos">
  <a href="https://www.melbconnect.com.au/" target="_blank"><img alt="Melbourne Connect" src="img/melbourne-connect-only-logo.png" /></a>
  <a href="https://www.unimelb.edu.au/" target="_blank"><img alt="The University of Melbourne" src="img/unimelb-logo.svg" /></a>
</div>

<hr>
