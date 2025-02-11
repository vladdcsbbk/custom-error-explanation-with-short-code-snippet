# custom-assistant-example-error-augmentation
This assistant example is designed to explain student programming error messages.

It provides plain English explanations of 2-3 sentences, as well as a possible fix.
The code snippet as part of the possible fix will be less than 3 lines of code, that only suggests a fix for the error - it may or may not be correct in terms of the solution of the assignment

It also has special instructions that define assistant behavior in case students have used prompts in the input function.

Tweak the `systemPrompt` or `userPrompt` to change/edit/update custom explanations or if you'd prefer a certain style of explanation. 
