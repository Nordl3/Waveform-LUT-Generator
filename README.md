
# Wave LUT Generator Setup Instructions (Windows)

### Step 1: Install Python
1. Download and install Python from [python.org](https://www.python.org/downloads/).
2. **Important**: During installation, check the box that says **"Add Python to PATH"**.

### Step 2: Install Required Libraries
1. Open **Command Prompt** (search for "cmd" in the Start menu).
2. Run this command to install the necessary libraries:
   ```bash
   pip install numpy matplotlib ipywidgets notebook
   ```

### Step 3: Download the Notebook File
- Save the `Wave LUT Generator_V-3.1.ipynb` file to an easy-to-access folder (like **Documents**).

### Step 4: Run Jupyter Notebook
1. Open **Command Prompt**.
2. Run:
   ```bash
   jupyter notebook
   ```
3. A browser will open automatically. In the file explorer on the page, navigate to the folder where you saved the notebook and click on `Wave LUT Generator_V-3.1.ipynb`.

### Step 5: Generate Waveforms
1. **Run all cells**: Go to **Cell** > **Run All** in the Jupyter menu.
2. **Adjust waveform settings**: Use the sliders to customize your waveform.
3. **Export LUTs**: Scroll to **Cell 3** and press `SHIFT + ENTER` to export your LUTs.

### Step 6: Locate the Output Files
After running the notebook and exporting your LUTs:

The output files will be saved in the same folder where you placed the Wave LUT Generator_V-3.1.ipynb file.
Open File Explorer and navigate to that folder.
The LUT files should be named according to how they are defined in the notebook (e.g., myLUT_1.txt and myLUT_1.png or similar).
