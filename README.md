# Black Forest Labs API Nodes for ComfyUI

This setup allows you to integrate and access BFL's API directly from within your ComfyUI workflow.

## Installation Instructions

### Step 1: Add `bfl_api.py` to Your ComfyUI Environment
- Clone this repo in your `ComfyUI/custom_nodes` directory.

### Step 2: Set Up Your BFL API Key
- To authenticate your requests, you need to provide your **BFL API key** from the [Black Forest Labs API](https://api.bfl.ml). 
  
  There are two ways to provide your key to ComfyUI:

  1. **Environment Variable Method (Recommended)**
     - Export your BFL API key as an environment variable:
       ```bash
       export BFL_API_KEY=<your_api_key_here>
       ```
  2. **Text File Method**
     - Alternatively, insert your API key into a file named `bfl_api_key.txt`.
     - Ensure that the `bfl_api_key.txt` file is placed in the same directory as `bfl_api.py`.

### Step 3: Restart ComfyUI
- Restart ComfyUI if already open

### Step 4: Insert a FLUX API Node into Your Workflow
- Once ComfyUI has restarted, you can now insert a **FLUX API Node** such as **FLUX 1.1 [pro]** into your workflow.
- To get started quickly, drag and drop the following node image into your workflow:

  ![ComfyUI_temp_qkhdn_00005_](https://github.com/user-attachments/assets/ad9ff10a-ad71-44f3-aa2b-24d18e2a23a9)

### Step 5: Enjoy the nodes

## Troubleshooting

- **Invalid API Key Error**: Ensure your API key is correctly set either in the environment variable or the `bfl_api_key.txt` file.
- **Node Not Appearing**: Confirm that `bfl_api.py` is placed somewhere in `ComfyUI/custom_nodes` and restart ComfyUI.

For more information about the Black Forest Labs API, visit the [Black Forest Labs API](https://api.bfl.ml).

--- 
