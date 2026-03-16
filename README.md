# Total Comp Visualisation Tool

An interactive total compensation breakdown built with Claude. Designed for comp teams, managers, and anyone who needs to make a total reward package tangible in a conversation.

## What this is

A single-page visualisation tool that lets you input compensation components and see them update in real time. Built for the specific problem of employees hearing one number (base salary increase) and tuning out everything else.

It includes:

- Interactive sliders for base, bonus, employer pension, benefits, and equity
- Four summary cards, including bonus and equity as a percentage of base
- A live chart that updates as you move the numbers

## What this is not

This is a visualisation layer. It does not generate, model, or recommend compensation figures. Every number you see is a number you entered. There is no data engine, no benchmarking, no AI-generated outputs.

The quality of what it shows depends entirely on the quality of what you input.

## Who it's for

- Comp and reward professionals preparing for pay review conversations
- Managers walking employees through their total package in a 1:1
- Heads of people at startups who handle comp without a dedicated team
- Anyone who has tried to explain equity value on a shared screen and watched eyes glaze over

## How to use it

1. Download or clone this repo
2. Open `index.html` in any browser
3. Adjust the sliders to match the employee's package
4. Use it in a conversation, a screen share, or just to sense-check how a package looks visually

No dependencies. No installation. No login. Just open the file.

## How it was built

One prompt in Claude. The entire tool was generated as a single interactive artifact. The source code in this repo is the output, cleaned up for readability.

If you want to adapt it for your own org (different benefit categories, currency formatting, employer contribution structures), you can either edit the code directly or prompt Claude with your own specifications. It is surprisingly good at this.

## Adapting it

Some things you might want to change:

- **Currency and formatting.** Defaults to GBP. Change the currency symbol and formatting in the code, or ask Claude to regenerate with your currency.
- **Compensation components.** Your org might split benefits differently, have sign-on bonuses, or use RSUs instead of options. Adjust the sliders to match your structure.
- **Ranges.** The slider min/max values are set for illustration. Update them to reflect realistic ranges for your levels.
- **Branding.** This is a prototype. If you want to put your company's colours on it, go for it.

## Limitations

- This is a prototype, not a production tool. It runs locally in a browser.
- It does not save data. Refresh the page and you start from scratch.
- It is not connected to any HRIS, payroll system, or compensation platform.
- Equity valuation is whatever you tell it. It does not pull share prices or model vesting schedules.

## Background

Built by [Giac Soliman](https://www.linkedin.com/in/giacsoliman/), a compensation and reward professional exploring what AI tooling can do for practitioners who never had engineering resources to build things like this.

Part of an ongoing series of prototypes showing what comp teams can build themselves with AI, without waiting for vendor roadmaps or IT backlogs.

## Licence

MIT. Use it, adapt it, share it.
