# Artifact Submission Template for SLE

## Author Information
- **Names:**
- **Affiliations:**
- **Emails:**

## Associated Paper Information
- **Title:**
- **Abstract:**

## Documentation
- **Link to the code repository:**
- Describe the structure of the artifact and provide a brief overview of the contents.

---

## Artifact Evaluation Environment

### System Specifications Used by Authors
- **Operating System:**
- **CPU:**
- **Memory:**
- **Disk Space:**
- **GPU (if applicable):**

### Estimated Hardware Requirements for Evaluation
- **Minimum required CPU:**
- **Minimum required Memory:**
- **Minimum required Disk Space:**
- **Minimum required GPU (if applicable):**

### Compatibility Considerations
- **Known compatibility issues of the container/VM:**


## Kick-the-Tires
This section should provide a simple and quick way for the reviewer to check whether all dependencies are correctly installed and that all scripts run without errors. The goal is not to run the full evaluation but to verify that the artifact is functional.

### Steps to Perform a Quick Test
1. **Setup Instructions:** Describe the minimal steps needed to set up the environment.
2. **Run a Sample Command:** Provide a single command or a few minimal commands that verify the artifact is working.
3. **Expected Output:** Describe what the expected output should be.
4. **Troubleshooting:** List common issues and their possible solutions if the setup fails.

## Full Evaluation
For all experimental claims made in the paper, please provide the following:

1. **Reference to the Experimental Claim:** Quote or reference the claim from the paper.
2. **Reproduction Steps:** Explain how this claim can be reproduced using the artifact.
   - Example: *“The results presented in Figure 3 can be reproduced by executing `run_experiment.sh` with the configuration file `config_figure3.json`.”*
3. **Expected Output:** Clearly describe what the expected output should be.
4. **Estimated Runtime (Optional):** Provide an estimate of how long the full evaluation will take.
5. **Potential Issues:** List any known challenges in reproducing the results and how to mitigate them.

