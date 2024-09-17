# My Claude Prompts
Welcome to the "My Claude Prompts" repository! This is a collection of prompt examples to be used with the Claude model.



## 🚀 Crafting the Perfect Cover Letter with Claude



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
Before answering, please think about the question within <thinking></thinking> XML. 
</instructions>

```

See more tips [HERE](https://www.extern.com/post/chatgpt-cover-letter)
