# Facebook's Vulnerability Disclosure Policy

Facebook may occasionally find critical security bugs or vulnerabilities in third-party code and systems, including open source software. When that happens, our priority is to see these issues promptly fixed, while making sure that people impacted are informed so that they can protect themselves by deploying a patch or updating their systems.

That sounds simple and clear-cut. However, vulnerability disclosure is anything but simple. Here is what motivated our policy:

1. *Not all bugs are equally sensitive.* A high-impact security issue requires much more care before it is publicly disclosed. The policy outlined below explains how we handle vulnerability disclosure.
2. *Fixing an issue requires close collaboration between researchers at Facebook reporting the issue and the third party responsible for fixing it.* With this policy, we want to clearly and unambiguously explain our expectations when we report issues we find in third-party code and systems. We also make clear when Facebook will disclose these issues.

## Vulnerability Disclosure policy

*In a nutshell,* Facebook will contact the appropriate responsible party and inform them as quickly as reasonably possible of a security vulnerability we’ve found. We expect the third party to respond within 21 days to let us know how the issue is being mitigated to protect the impacted people. If we don’t hear back within 21 days after reporting, Facebook reserves the right to disclose the vulnerability. If within 90 days after reporting there is no fix or update indicating the issue is being addressed in a reasonable manner, Facebook will disclose the vulnerability.

That said, we will adhere to the vulnerability disclosure steps and the proposed timelines whenever reasonably possible, but we can envision scenarios where there might be deviations. If Facebook determines that disclosing a security vulnerability in third party code or systems sooner serves to benefit the public or the potentially impacted people, we reserve the right to do so.

Here are some details.

## Reporting

* Facebook will make a reasonable effort to find the right contact for reporting a vulnerability, such as an open source project maintainer. We will take reasonable steps to find the right way to get in touch with them securely. For example, we will use contact methods including but not limited to emailing security reporting emails (security@ or secure@), filing bugs without confidential details in bug trackers, or filing support tickets.
* The contact should acknowledge the report as soon as reasonably possible.
* The contact should confirm whether we've provided sufficient information to understand the reported problem.
* In its report, Facebook will include a description of the issue found, a statement of Facebook's vulnerability disclosure policy, and the expected next steps.
* If needed, Facebook will provide additional information to the contact to aid in reproducing the issue.
* If we do not receive a response within 21 days from a contact acknowledging the report of a vulnerability, we will assume that no action will be taken. We then reserve the right to disclose the issue.
* For purposes of the disclosure timeframe, Facebook's *sending* the report constitutes the start of the process.
* Facebook will generally decline to sign non-disclosure agreements specific to an individual security issue that we have reported.

## Mitigation & Timeline

* Whenever appropriate, Facebook will work with the responsible contact to establish the nature of the issue and potential fixes. We will share relevant technical details to help expedite the fix.
* The contact should be as transparent as possible about the mitigation progress. They are expected to make reasonable effort to fix the reported issue within 90 days.
* Facebook will coordinate the disclosure with the availability or rollout of the fix.
* If no fix is forthcoming at the 90-day mark, we will notify the contact of our intent to disclose the reported issue.
* If there are no mitigating circumstances, we will disclose the issue as soon as we are reasonably able to do so.

## Disclosure

* Depending on the nature of the problem, there may be a number of disclosure paths: 1) we may disclose the vulnerability publicly, 2) we may disclose it directly to the people using the project, or 3) we may issue a limited disclosure first followed by a full public disclosure. Facebook will work with the contact to determine which approach is most appropriate in each case.
* Our intent is to disclose vulnerabilities in a way that is most helpful to the community. For example, we may include guidance on workarounds, methods for validating patches are in place, and other material that helps people contain or remediate the issue.
* We may choose to include a timeline to document communication and remediation actions taken by both Facebook and the third party. Where reasonable, our disclosure will include suggested steps for mitigating actions.
* We will include a CVE when available, and, if necessary, issue an appropriate CVE.

## Additional Disclosure Considerations

* Here are some potential scenarios when Facebook may deviate from our 90-day requirement:
  * **If the bug is actively being exploited,** and disclosing would help people protect themselves more than not disclosing the issue.
  * **If a fix is ready and has been validated, but the project owner unnecessarily delays rolling out the fix,** we might initiate the disclosure prior to the 90-day deadline when the delay might adversely impact the public.
  * **If a project's release cycle dictates a longer window,** we might agree to delay disclosure beyond the initial 90-day window, where reasonable.
* Facebook will evaluate each issue on a case-by-case basis based on our interpretation of the risk to people.
* We will strive to be as consistent as possible in our application of this policy.
* Nothing in this policy is intended to supersede other agreements that may be in place between Facebook and the third party, such as our Facebook Platform policies or contractual obligations.

Finally, this policy refers to what Facebook does when we find an issue in third party code. If you believe you have found a security vulnerability on Facebook (or other member of the Facebook family of apps), we encourage you to report it through our [Bug Bounty Program](https://www.facebook.com/whitehat/info).

(This document was retrieved from https://www.facebook.com/security/advisories/Vulnerability-Disclosure-Policy on September 23 2021)
