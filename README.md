# Climate Reporting Support System for Senior Residents in East San Jose

## 1. Problem and Who It Affects

The United Nations 2030 Agenda says the world is still not reducing greenhouse gases fast enough to keep global warming below 1.5 to 2 degrees Celsius. This same problem can also be seen locally in the Bay Area. Some climate-related problems, like illegal dumping, bad air quality, extreme heat, and poor neighborhood conditions, are not always tracked or fixed properly.

This project focuses on senior living centers in East San Jose. Senior residents can be badly affected by extreme heat, wildfire smoke, air pollution, and waste buildup. These problems can make it harder for them to breathe, move around safely, or get emergency help when needed.

Many senior residents may also not have strong digital skills. This means they may find it hard to use apps or websites to report problems. Because of this, their complaints may not be recorded clearly, or they may not be sent to the right department. When that happens, the problem can stay unsolved, and the seniors are the ones who suffer the most.

## 2. AI Capability Used and Why It Fits

This project uses two AI abilities from the labs.

First, Lab 2 uses AI to read written reports. A resident can describe a problem in their own simple words, such as “There is smoke outside and people are coughing.” The AI then pulls out important details like the location, type of problem, urgency level, department, and language used.

Second, Lab 3 uses AI to understand images. A resident can upload a photo of a real environmental issue, such as smoke in the air, trash buildup, or unsafe neighborhood conditions. The AI looks at the photo and tries to describe the problem, decide how serious it is, and suggest what action should be taken.

These AI tools fit the problem because residents may not always know how to fill out long forms. Instead, they can write a short message or upload a photo. The AI can help turn that information into a more organized report that the city can use.

## 3. Workflow

### Step 1: Input

The input can come from a resident in two ways:

- A short written message about the problem
- A photo showing the problem

For example, a senior resident may write that there is a lot of smoke outside, the air smells bad, and people nearby are coughing. Another resident may upload a photo showing smoky air near a senior living center.

### Step 2: What the AI Does

The AI reads the text or looks at the image. Then it tries to understand the main problem.

For written reports, the AI identifies details such as:

- Location
- Type of issue
- Urgency level
- Correct department
- Language used

For image reports, the AI identifies details such as:

- What is shown in the image
- Whether the situation looks dangerous
- Who may be affected
- What action may be needed

### Step 3: Output

The AI gives an organized report. For example, it may say:

- Location: East San Jose
- Problem: wildfire smoke or bad air quality
- Urgency: high
- Department: public health or air quality department
- Suggested action: send help or warn residents

This output can then be used to create a city report or work order.

### Step 4: Who Acts on It

After the AI creates the report, a city worker or department should review it. The report may go to public health, environmental services, public works, or another city department depending on the problem.

Human review is important because the AI may make mistakes. A person should check if the issue was understood correctly before the city takes action.

### Screenshots

Screenshots from the lab outputs should be added here.

Suggested screenshots to include:

- Screenshot of the Lab 2 structured AI output
- Screenshot of the Lab 3 image analysis output
- Screenshot showing the AI’s urgency and department decision
- Screenshot showing the failure case or wrong classification

## 4. Failure Case Tied to a Lab Output

One failure case happened when the AI classified a local environmental complaint into a department. The report involved heat and waste buildup near senior residents. The AI placed it under a public health category, which made sense because the issue affected people’s health.

However, if the AI had sent the complaint to the wrong department, the result could be serious. For example, if it was sent only to public works, the city might clean up the trash but ignore the heat and air pollution risks. This would mean the visible part of the problem gets fixed, but the health danger remains.

This is especially harmful for senior residents in East San Jose. Many of them may not have the digital skills to report the same problem again. If the AI makes a mistake the first time, the residents may not get another chance to explain the full problem. The people who pay the price are the elderly residents, because their health and safety are still at risk.

Another failure from Lab 3 is that the AI can miss problems that are not easy to see in a photo. For example, if a senior living center has no air conditioning during extreme heat, a photo may just look like a normal building. The AI may not understand that people inside are in danger. This shows that AI works better for visible problems, like smoke or trash, but it can fail when the problem is hidden.

## 5. Oversight Decision and One Change

### Oversight Decision

This system should not send reports directly to departments without human review. A real person should check the AI’s decision before a work order is created, especially when the report involves seniors, health risks, smoke, heat, or emergency situations.

The AI can help organize the information, but it should not be the final decision-maker. A city worker, public health worker, or trained reviewer should confirm the urgency and department before action is taken.

### Tradeoff

The benefit of human review is that it can reduce mistakes. It helps make sure the complaint goes to the right department and that important health risks are not ignored.

The tradeoff is that human review may take more time. Reports may not move as fast as fully automated AI routing. However, for vulnerable groups like senior residents, accuracy is more important than speed.

### One Change to Improve the System

One change I would make is to add a “vulnerable resident or health risk” flag. If a report mentions seniors, breathing problems, extreme heat, smoke, coughing, or poor air quality, the system should automatically mark it for human review.

This change would help protect senior residents because their reports would not be treated like normal trash or road complaints. The city would know that the issue may involve health and safety, not just cleanup.

### Tradeoff

The benefit is that serious reports would get more attention and would be less likely to be ignored.

The tradeoff is that more reports may need human review, which could increase work for city staff. Still, this is worth it because missing a serious health risk could harm elderly residents.
