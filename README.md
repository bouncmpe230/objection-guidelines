# Objection Guidelines
For objections, please follow the steps below:

1. **Create a New Branch Named `objection`:**
   - Clone your repository:
     ```bash
     git clone https://github.com/bouncmpe230/homework1-<student_id>
     ```
   - Create a new branch:
     ```bash
     git checkout -b objection
     ```
   - Make the necessary changes to fix the issues that caused test case failures. Ensure these changes reflect the output you got on your platform (OS+Docker, OS+virtual machine, etc.).
   - Commit your changes:
     ```bash
     git commit -m "Fix issues for objection" --all
     ```
   - Push the changes to the new branch:
     ```bash
     git push --set-upstream origin objection
     ```

2. **Create a Pull Request:**
   - Go to your repository on GitHub and create a pull request from the `objection` branch to the `main` branch.
     ![PR](https://github.com/bouncmpe230/objection-guidelines/assets/9639399/a2921c57-d9ce-4800-bc7b-f514c5b157dc)

   - Use [the following template](.github/pull_request_template.md) for your pull request:

   ```markdown
   ## Objection Submission

   ### Description

   Provide a brief overview of the changes made to address the grading issues.

   ### Changes Made

   List and describe each change made in the codebase:
   - **File:** `parse.c`
     - **Line:** 42
     - **Change:** Fixed the typo.
   - **File:** `Makefile`
     - **Change:** Updated to include additional libraries for proper compilation.

   ### Test Cases

   List the test cases you are objecting to and provide detailed reasons:
   - **Test Case 2:** 
     - **Issue:** The expected output was incorrect due to a typo.
     - **Fix:** Fixed the typo.
   - **Test Case 5:** 
     - **Issue:** The test environment had a configuration mismatch.
     - **Fix:** Updated the environment setup script to match the required configuration.

   ### Outputs (if applicable)

   Attach relevant output screenshots or logs to support your objection:
   - **Output for Test Case 2:**
     - Screenshot/Log: ![Test Case 2 Output](link-to-screenshot)
   - **Output for Test Case 5:**
     - Screenshot/Log: ![Test Case 5 Output](link-to-screenshot)

   ### Additional Comments

   Provide any additional comments or explanations that may help in reviewing your objection.```
   
Please follow these guidelines to ensure a smooth objection process. If you have any questions or need further assistance, feel free to reach out.

