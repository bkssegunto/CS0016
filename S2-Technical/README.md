# IT0123 DevNet Resource Validation Plan

## Student and Project

- Name: Bienn Kyla Segunto
- Section: TN35
- Repository name: `it0123-devnet-resource-plan`

## Purpose

Selecting the correct Cisco DevNet resource ensures that the available access, permissions, setup process, and learning format match the requirements of a network-automation task. Verifying an AI recommendation by using the official Cisco documentations also prevents inaccurate information from being included in the development plan.

## Validated Resource Decisions

For UC1, I selected always-on-sandbox because the team needs immediate access to a shared environment for non-administrative API practice. According to Cisco, Always-On Sandboxes do not require reservations, are shared among users, and restrict administrative access.

For UC2, I selected reservation-sandbox because the team needs a private environment with administrative access for testing configuration changes. As stated in Cisco's documentation, Reservation Sandboxes provide private access and administrative privileges but require a reservation, setup time, and usually a VPN connection.

For UC3, I selected learning-lab because the beginner needs structured, step-by-step instruction before performing an independent API activity. DevNet Learning Labs provide guided content for learning Cisco technologies and development concepts.

Lastly, for UC4, I selected code-exchange because the developer wants to examine existing network-automation projects before creating a new solution. Cisco Code Exchange provides a curated collection of code examples and repositories contributed by Cisco teams and the developer community.

## AI Evaluation

I accepted all four recommendations of OpenAI for the corresponding resource types for each use case. I came to that decision because upon inspecting the official documentation/s from the Cisco website, I was able to verify that the resource types fit the requirements of each case.

## Validation Evidence

- Validator result: 9/9 checks passed
- Command used: python validate_plan.py | Tee-Object validator_output.txt
- Official Cisco pages reviewed: https://developer.cisco.com/docs/sandbox/getting-started/#what-is-devnet-sandbox, https://developer.cisco.com/learning/, https://developer.cisco.com/site/codeexchange-about-page/

## Git Evidence

- Initial commit message: Initialize DevNet resource validation activity
- Validation commit message: Complete and validate DevNet resource plan
- Output of `git log --oneline`:

## AI-Use Disclosure

I used OpenAI ChatGPT/Codex to enter the suggested prompt from the worksheet to recommend which resource type from DevNet was the best for each use case. I reviewed the AI's recommendations and explanations, and compared them to the official Cisco documentations before accepting anything.
