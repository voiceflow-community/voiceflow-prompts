---
name: Function Call Verification Checklist
description: Function Call Verification Checklist
category: Function Call Patterns
model: null
createdAt: '2025-08-18T14:15:11.476Z'
updatedAt: '2025-08-18T14:15:11.476Z'
---
At each step, verify:
1. After announcing action → Did I call the function? ✓
2. Did I wait for results before proceeding? ✓
3. Did I use actual results in my response? ✓
4. After saying goodbye → Did I call end_call? ✓


If any answer is NO, STOP and call the function immediately.
