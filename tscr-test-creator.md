---
name: tscr-test-creator
description: Create tests, exams, assessment worksheets, answer keys, and grading rubrics for the Computer Systems and Networks Technician vocational course, qualification code 481RA118. Use when the user requests assessment material on hardware, computer assembly, preventive maintenance, troubleshooting, operating systems, computer architecture, networking, or related course topics.
---

# TSCR Test Creator

## 1. Purpose

Create complete, balanced, technically accurate, and print-ready assessment materials for the vocational course **Técnico/a de Sistemas de Computação e Redes**, qualification code and title **481RA118**, when this qualification context is relevant to the user's request.

The default language for student-facing material is **Portuguese (Portugal)**. Use European Portuguese spelling, terminology, and phrasing. Keep standard technical names, command names, protocol names, product names, and official qualification or unit codes accurate.

## 2. When to Use This Skill

Use this skill when the user asks to create or revise any of the following:

- Tests, exams, quizzes, or assessment worksheets.
- Multiple-choice, short-answer, identification, practical, or scenario-based questions.
- Answer keys and detailed grading criteria.
- Assessment material about hardware, computer assembly, preventive maintenance, troubleshooting, operating systems, computer architecture, networking, BIOS/UEFI, safety procedures, or related topics in the course.
- A print-ready assessment document based on a specified course unit, learning outcome, or topic.

If the user provides a specific course unit, syllabus, learning outcomes, reference document, or list of topics, use that material as the primary source. Do not claim that content is officially required unless the supplied material supports that claim.

## 3. Core Principles

### 3.1 Technical accuracy

- Use technically precise terminology.
- Preserve standard technical names and official terminology where appropriate.
- Do not invent technical specifications, official curriculum requirements, or unit codes.
- If a question depends on a version, configuration, or product-specific detail, state the relevant context or ask for clarification when necessary.
- Ensure that each question has a defensible answer and that the answer key matches the question exactly.

### 3.2 Practical context

Where appropriate to the topic and learner level, use realistic situations such as:

- Diagnosing a computer that will not start.
- Identifying or replacing a hardware component.
- Selecting compatible components for a stated use case.
- Performing preventive maintenance safely.
- Troubleshooting an operating system or network configuration.
- Interpreting BIOS/UEFI settings, error messages, commands, or test results.

Do not force a practical scenario into every question if a direct knowledge question is more appropriate.

### 3.3 Clear assessment and grading

- State the score assigned to every question or sub-question.
- Unless the user specifies another scale, the total score must be exactly **20 points**.
- Make the scoring breakdown transparent and easy to verify.
- Award partial credit where appropriate and define the criteria.
- Ensure the answer key and rubric cover every question.
- Do not assign points to an answer key in a way that conflicts with the score shown on the student paper.

### 3.4 Fairness and accessibility

- Match difficulty to the stated age, year, course unit, learning outcomes, and learner level.
- Use clear, direct instructions.
- Avoid ambiguous wording, trick questions, and irrelevant complexity.
- Ensure multiple-choice questions have one clearly best answer unless the question explicitly says otherwise.
- Make distractors plausible but unambiguously incorrect in the stated context.
- Avoid giving away the answer through wording, option length, or inconsistent grammar.
- Do not test content that has not been specified or reasonably established by the supplied learning materials without flagging the assumption.

## 4. Information to Establish

Use details supplied by the user. If a missing detail materially affects the result, ask a concise follow-up question. Otherwise, proceed with reasonable defaults and make them visible in the document.

Relevant details may include:

- School or institution name.
- Course name and qualification code.
- Course unit, module, or subject.
- Assessment topic and learning outcomes.
- Learner year, age, or level.
- Assessment duration.
- Desired question types and number of questions.
- Whether the answer key should be included in the same file or provided separately.
- Any required institutional template or grading scale.

### Default settings

When the user has not specified alternatives:

- Language: Portuguese (Portugal).
- Total score: 20 points.
- Duration: 90 minutes.
- Format: print-ready Markdown that can be copied into a word processor.
- Structure: three groups, adapted when necessary to the subject.
- Include a separate answer key and detailed grading rubric after the student test, clearly separated so it can be removed before printing for students.

Do not invent a school name, date, course unit code, or official learning outcome. Use a clearly marked placeholder or omit the field when appropriate.

## 5. Standard Assessment Structure

Use the following structure as the default. Adapt it when the user requests a different format or when the subject requires a different assessment design.

~~~markdown
# [Nome da escola ou instituição]

**Curso:** Técnico/a de Sistemas de Computação e Redes  
**Código da qualificação:** 481RA118  
**UFCD / UC / Módulo:** [Código e designação, se fornecidos]  
**Disciplina:** [Designação, se aplicável]  
**Nome:** ______________________________________________  
**N.º:** __________ **Turma:** __________ **Data:** ____ / ____ / ______  
**Duração:** 90 minutos  
**Cotação total:** 20 valores

## [Título do teste]

### Instruções
- Lê todas as perguntas com atenção.
- Responde de forma clara e organizada.
- Nas perguntas de escolha múltipla, seleciona apenas uma opção, salvo indicação em contrário.
- Apresenta os cálculos ou a justificação sempre que forem solicitados.
- Respeita as regras de segurança aplicáveis às tarefas práticas.

### Grupo I, Escolha múltipla
[Questões de resposta única, com opções claramente identificadas.]

### Grupo II, Resposta curta e identificação
[Questões de definição, identificação de componentes, portas, comandos, procedimentos ou etapas.]

### Grupo III, Estudo de caso e resolução de problemas
[Problemas práticos, diagnóstico de avarias, análise de configurações ou aplicação de procedimentos.]

---

# Grelha de correção e critérios de classificação
[Respostas esperadas, critérios de atribuição de pontos e cálculo da cotação total.]
~~~

The three-group structure is a default, not an absolute requirement. Change the groups when a practical task, laboratory assessment, project, or other format better matches the user's request.

## 6. Question Design Rules

### 6.1 Multiple-choice questions

- State the question or problem clearly.
- Provide options labelled A, B, C, and D unless another format is requested.
- Ensure there is one correct answer by default.
- Keep the options similar in style and level of detail.
- Avoid “all of the above” and “none of the above” unless there is a clear pedagogical reason.
- Mark the score for each question.
- Do not reveal the correct answer in the student version.

### 6.2 Short-answer and identification questions

- Specify exactly what the learner must identify, explain, compare, list, or describe.
- Indicate the expected number of items when relevant.
- State the score for the question and, where useful, the points per item.
- Accept technically equivalent wording when the meaning is correct.

### 6.3 Case studies and troubleshooting questions

- Provide enough information for the problem to be solved.
- Distinguish given facts from assumptions.
- Ask for concrete actions, diagnoses, explanations, or justifications.
- Ensure the model answer follows logically from the scenario.
- For safety-related questions, do not reward unsafe procedures.

### 6.4 Practical tasks

When creating a practical assessment:

- List the equipment, software, files, or tools required, where known.
- State the task, constraints, expected result, and evidence to be submitted.
- Include relevant safety and data-protection precautions.
- Provide observable grading criteria.
- Do not assume access to equipment or software that the user has not identified, unless it is clearly marked as an assumption.

## 7. Answer Key and Detailed Grading

Always include an answer key when requested. Under the default settings, include it after the student version under a clearly marked heading so it can be removed before distribution.

For each question:

1. Give the correct answer or an acceptable model response.
2. Explain the key reasoning when this helps consistent marking.
3. State the score available.
4. Describe partial-credit criteria where applicable.
5. Identify acceptable equivalent answers when relevant.

For multiple-choice questions, provide the correct option and a concise explanation where useful.

For open questions, use a rubric that identifies the elements required for full credit. Avoid vague criteria such as “good answer” without explaining what earns the points.

## 8. Scoring and Validation

Before presenting the assessment, perform these checks:

- Add all question and sub-question scores.
- Confirm that the total equals exactly 20 points unless the user requested a different total.
- Confirm that each question's displayed score matches the grading rubric.
- Confirm that every question has a corresponding answer or grading criterion.
- Check that no answer key contradicts the question.
- Check multiple-choice questions for unintended ambiguity or multiple correct answers.
- Confirm that the number of questions and the duration are reasonable for the stated learner level.
- Make sure the assessment covers the supplied topics and learning outcomes without unsupported claims.

If the total does not equal the intended score, revise the distribution before presenting the final material. Do not simply state that the total is correct without checking the arithmetic.

## 9. Print-Ready Formatting

- Use clear headings and consistent numbering.
- Leave sufficient space for written answers when appropriate.
- Include fields for name and date unless the user requests otherwise.
- Separate the student assessment from the answer key.
- Avoid decorative elements that make printing difficult.
- Use tables only when they improve readability.
- If the user requests a Word document or another file format, provide that format when file creation is available. Otherwise, provide clean content that can be copied into the requested application.

## 10. Interaction and Output Behaviour

- If the user gives a clear topic and enough information, create the assessment directly instead of asking unnecessary questions.
- If an essential detail is missing, ask one concise question.
- If a reasonable default can be used, proceed and state the default.
- If the user asks to revise an existing test, preserve correct and useful content unless asked to replace it.
- If source documents are supplied, base the assessment on those documents and do not silently add unsupported syllabus content.
- Clearly flag any assumptions or information that needs confirmation.
- Use Portuguese (Portugal) for student-facing assessment material, explanations, answer keys, and grading criteria unless the user asks for another language.

## 11. Final Quality Checklist

Before delivering the result, verify:

- [ ] The content matches the requested course unit and topic.
- [ ] The language is Portuguese (Portugal), unless otherwise requested.
- [ ] Technical terminology is accurate and consistent.
- [ ] The instructions are clear.
- [ ] Each question displays its score.
- [ ] The total score is correct.
- [ ] The answer key matches the questions.
- [ ] The grading rubric supports consistent marking.
- [ ] The student version is separated from the answer key.
- [ ] The layout is suitable for printing.
- [ ] Any assumptions, placeholders, or unverified official details are clearly identified.

Deliver the finished assessment in a clean, usable format. Do not describe internal reasoning; provide the assessment and any concise notes the user needs to use it.
