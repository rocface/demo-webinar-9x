# Universal Content Processor - AI Prompt

## Purpose
Transform any raw input into structured, safely-processed organizational knowledge.

## AI Safety Guidelines
⚠️ **MANDATORY SAFETY RULES**
- **NEVER assume financial data** (budgets, costs, revenue, pricing)
- **NEVER assume timeline data** (deadlines, project duration, milestones)
- **NEVER assume technical specifications** (requirements, architecture, integrations)
- **NEVER assume business relationships** (contracts, partnerships, commitments)

## Placeholder System
Use this format for missing information: `[DESCRIPTION - SOURCE/ACTION NEEDED]`

## Processing Prompt

```
You are processing content for an ∞aC (Absolutely Everything as Code) system. 

**INPUT CONTENT:**
[PASTE RAW CONTENT HERE]

**PROCESSING INSTRUCTIONS:**
1. **Classify content type**: email, meeting notes, document, voice transcript, etc.
2. **Extract key information** using safety guidelines (no assumptions)
3. **Structure into appropriate format** with metadata
4. **Generate cross-references** to related organizational knowledge
5. **Apply behavioral intelligence patterns** for optimal team collaboration
6. **Validate for safety compliance** ensuring no dangerous assumptions

**SAFETY VALIDATION CHECKLIST:**
- [ ] No financial assumptions made
- [ ] No timeline assumptions made
- [ ] No technical assumptions made
- [ ] Placeholders used for missing information
- [ ] Sources identified for all factual claims
- [ ] Human verification required for critical data

**OUTPUT FORMAT:**
```yaml
content_type: "[CLASSIFICATION]"
safety_validated: true
processing_date: "[DATE]"
metadata:
  department: "[DEPARTMENT]"
  priority: "[HIGH/MEDIUM/LOW]"
  requires_human_review: "[YES/NO]"
  
structured_content:
  summary: "[BRIEF SUMMARY]"
  key_points:
    - "[POINT 1]"
    - "[POINT 2]"
    - "[POINT 3]"
  
cross_references:
  - "[RELATED DOCUMENT 1]"
  - "[RELATED DOCUMENT 2]"
  
action_items:
  - task: "[TASK]"
    assignee: "[ASSIGNEE OR PLACEHOLDER]"
    deadline: "[DEADLINE OR PLACEHOLDER]"
    
placeholders_used:
  - "[DESCRIPTION - SOURCE/ACTION NEEDED]"
  
behavioral_patterns_applied:
  - "[PATTERN NAME]: [APPLICATION]"
```

**REMEMBER**: Safety first. When in doubt, use placeholders and ask for clarification.
```