# Dispersivity_MS

The repo provides AEM model code used for quantifying $\alpha_{Tv}$ and $\alpha_{Th}$ and includes site database which are used in 
the model. IPYNB file provides the analysis of the obtained results including graphical output used in the documentation.

All contents of the repo are licensed under [CC-BY-4.0 wordings](https://creativecommons.org/licenses/by/4.0/deed.en) - basically credit the original author for their efforts.

# Using the inverse AEM model

The source Python codes are in the "**SRC**" directory. The simulation workflow is as follows:

- Start with the **Main.Py** - here the model option: **Inverse** is to be selected
- Use **Inverse-config.json** file from the **SRC** directory: the _model input and output control_ can be made in this json file.
- Run **Main.py** to simulate the input placed in the **Inverse-config.json** file
- The model output will be stored in a local directory provided indicated in the json file.


# Model result analysis

These are available as a Jupyternotebook (IPYNB) files. 
  
  - Download the IPYNB file locally (Field_Vertical.ipynb, Field_horizontal.ipynb, Lab_dispersivity.ipynb or Additional.ipynb) from the **ipynb** folder
  - Download the corresponding **.xlsx** file from the **database** folder
  - Make required changes in the **PATH** where the downloaded **.xlsx** files are available - **MAKE SURE THIS IS ALWAYS DONE**
  - Make sure to have required (open-source Python libraries such as numpy, matplotlib, scipy, pandas and LMFIT) installed in your Python setup
  - Excute the ipynb file to obtain numerical results or graphics
  
  
> **The source code are updated and some details mentioned above may not apply. Pls. raise an issue in the GitHub in such a case**