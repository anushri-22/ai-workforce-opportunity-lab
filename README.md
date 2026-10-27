# AI Workforce Opportunity Lab

**From AI opportunity discovery to measurable business impact**

[**Explore the interactive dashboard →**](https://anushri-22.github.io/ai-workforce-opportunity-lab/)

## The opportunity

How can a mid-market organisation identify where AI could create value, build a credible business case and decide whether a pilot is ready to scale?

This project explores that question through **Northstar Advisory**, a fictional UK professional-services company with 500 employees and a proposed 100-user AI pilot.

Its teams face a high administrative workload, fragmented internal knowledge and slow customer-response processes. Leaders need a way to assess opportunities, manage risks and measure value before investing in a wider rollout.

## What the lab demonstrates

The interactive application takes the customer through seven stages:

1. **Executive overview** — the customer’s challenges, AI opportunity and recommended starting point.
2. **Opportunity discovery** — an assessment that ranks six use cases using transparent scoring rules.
3. **Simulated knowledge agent** — a rule-based demonstration that uses fictional documents, provides source references and recommends human escalation when it cannot answer.
4. **ROI calculator** — an editable model comparing productivity capacity, illustrative costs and first-year value across three scenarios.
5. **90-day adoption roadmap** — pilot activities, accountable stakeholders, measures and decision gates.
6. **Account strategy** — stakeholder discovery, qualification, objections, product fit, partner involvement and expansion planning.
7. **AI adoption readiness** — an assessment of sponsorship, employee confidence, data, governance, processes and training.

## Microsoft solution strategy

The lab explores where **Microsoft 365 Copilot** could support productivity within Microsoft 365 and where **Copilot Studio** could be considered for a tailored agent and workflow.

It also recognises that a different assistant, improved search or conventional automation may be a better choice depending on the customer’s requirements, environment and economics.

A potential production design could use Copilot Studio with approved knowledge sources, Power Automate for controlled workflows, and human review. It would require customer-specific validation of permissions, governance, licensing and technical fit.

## Business value

The ROI calculator allows users to change assumptions including pilot size, adoption, time saved, licence cost, implementation cost and training investment.

The model compares conservative, base and optimistic scenarios. It expresses benefits as **productivity capacity**, not guaranteed cash savings.

## Technical overview

Built as a static, interactive application using:

- **React and TypeScript** for the interface and application logic.
- **Vite and Tailwind CSS** for the build and styling.
- **Recharts** for scenario visualisation.
- **Lucide** for icons.
- **Local JSON** for fictional customer data and knowledge documents.
- **GitHub Actions and GitHub Pages** for deployment.

The application runs without a backend or paid API key.

## Project limitations

- Northstar Advisory, its documents and all financial assumptions are fictional.
- The knowledge agent is a **rule-based simulation**. It is not connected to Copilot Studio or a live AI model.
- The opportunity and readiness scores are illustrative decision-support tools; they are not academically validated or predictive.
- The ROI model estimates productivity capacity, not guaranteed cash savings.
- The licence cost is an illustrative assumption, not a statement of Microsoft pricing.
- Microsoft product fit, licensing, permissions and governance would need to be validated for a real customer.

This is an independent portfolio project and is not affiliated with Microsoft.
