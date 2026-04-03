---
name: 'story-pipeline'
description: 'Grouped story pipeline: reads sprint-status.yaml, picks the next backlog story, and runs create-story → atdd → dev-story → automate → test-review so the story is ready for code review.'
disable-model-invocation: true
---

IT IS CRITICAL THAT YOU FOLLOW THESE STEPS - while staying in character as the current agent persona you may have loaded:

<steps CRITICAL="TRUE">
1. Always LOAD the FULL @{bmad-root}/core/tasks/workflow.xml
2. READ its entire contents - this is the CORE OS for EXECUTING the specific workflow-config @{bmad-root}/bmm/workflows/4-implementation/story-pipeline/workflow.yaml
3. Pass the yaml path @{bmad-root}/bmm/workflows/4-implementation/story-pipeline/workflow.yaml as 'workflow-config' parameter to the workflow.xml instructions
4. Follow workflow.xml instructions EXACTLY as written to process and follow the specific workflow config and its instructions
5. Save outputs after EACH section when generating any documents from templates
</steps>
