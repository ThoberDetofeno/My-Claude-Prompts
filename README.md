# My Claude Prompts
Welcome to the "My Claude Prompts" repository! This is a collection of prompt examples to be used with the Claude model.



## :spiral_notepad: Crafting the Perfect Cover Letter with Claude
Create personalized, engaging cover letters painless by the power of Claude.

A well-crafted cover letter can make all the difference in landing a job. It's essential to ensure that your cover letter doesn't come across as cold or machine-generated. In this prompt, we'll show you how to harness the Claude to compose a compelling cover letter that customize with human authenticity.

AI can analyze job descriptions and fine-tune your letter to match specific requirements and keywords, significantly increasing your chances of grabbing employers' attention.

First of all, gather Information all the necessary information before engaging with Claude. This includes your name, curriculum details, the company's informations, and the job description you're applying for. It's also helpful to have a clear understanding of the job requirements and the company culture.

It's essential to review and edit the cover letter for clarity, coherence, and any potential AI-generated phrasing. 

Finally, choose a good cover letter template and good luck.


```html
You are applying for a job and need a cover letter that allows you to show a personal side of yourself and demonstrate why you are qualified for the position.
Craft a professional cover letter for {{position title}} at {{company name}}.

<input>
    <company>
        {{company description}}
    </company>
    <job>
        {{job description}}
    </job>
    <experience>
        {{experience or resume}}
    </experience>
    <Name>
        {{My name}}
    </Name>
    <Phone>
        {{Phone number}}
    <email>
        {{email}}
    </email>
</input>

To write a good motivation letter is necessary following steps:
<thinking>
    Write an Header
    Write a Salutation
    Write an introduction.
    Expand your outline for your body paragraph
    Conclude your motivation letter.
    Letter ending and signature
</thinking>

Here is an example:
<example>
    {{Get here some examples: https://www.indeed.com/career-advice/cover-letter-samples}}
</example>

<instructions>
    The <job> tag refers to job description or vacancy.
    The <experience> tag refers about my experiences, skills and qualifications. 
    The <company> tag refers to the company offering the job.
    Generate a cover letter highlighting my skills and qualification for the job (<job> tag) at company (<company> tag).
    The cover letter should be write in a formal tone.
    The cover letter should highlights my experiences (<experience> tag) considering the job description.
    Do not highlight in the cover letter the job requirements that I do not have experience with.
    Before answering, please think about the question within <thinking></thinking> XML tags. 
</instructions>

```

See more tips [HERE](https://www.extern.com/post/chatgpt-cover-letter)

## :spiral_notepad: Using AI to identify Impact Level of an Incident 


```html
You are an incident specialist who is responsible for analyzing impact of an incident. An impact analysis is a process that involves examining the possible consequences of a potential change to a business. Analysing the impact of an incident helps in assessing the extent of damage, implications on operations, and potential risks associated with the event.

<incident>
    <title>
        {{incident title}}
    </title>
    <description>
        {{incident description}}
    </description>
    <category>
        {{incident title}}
    </category>
    <prioritization>
        {{incident title}}
    </prioritization>
    <severity>
        {{incident title}}
    </severity>
    <resolution>
        {{incident title}}
    </resolution>
</incident>
Impact level is expressed as a value of Low, Moderate, or High.
Low impact refers: 
- A minimal number of staff are affected and/or able to deliver an acceptable service but this requires extra effort.
- A minimal number of customers are affected and/or inconvenienced but not in a significant way.
- The financial impact of the Incident is (for example) likely to be less than $1,000.
- e damage to the reputation of the business is likely to be minimal.
Moderate impact refers: 
- A moderate number of staff are affected and/or not able to do their job properly.
- A moderate number of customers are affected and/or inconvenienced in some way.
- The financial impact of the Incident is (for example) likely to exceed $1,000 but will not be more than $10,000.
- The damage to the reputation of the business is likely to be moderate.

High impact refers: 
- A large number of staff are affected and/or not able to do their job.
- A large number of customers are affected and/or acutely disadvantaged in some way.
- The financial impact of the Incident is (for example) likely to exceed $10,000.
- The damage to the reputation of the business is likely to be high.
- Loss of data integrity, availability, temporal context, or other context can have catastrophic consequences.

The <incident> tag refers all information about an incident.
The <description> tag refers a incident description.
The <category> tag refers the kind of incident .
The <prioritization> tag refers the prioritization of incident.
The <severity> tag refers the severity of incident.
The <resolution> tag refers a description about the resolution of incident.

First all, analise all information about the incident and after choose the most appropriate Impact level.
The response should be a single text that represents a Impact Level that is most appropriate for the Incident.
Do not return an explanation of why you selected it.
```
