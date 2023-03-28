# iEEG-preprocess-using-MNE
This repository includes iEEG preprocessing pipelines using MNE-python(https://mne.tools/stable/index.html) for iEEG datasets with applied stimulation.
Public datasets are processed including:

# 1 --> https://dabi.loni.usc.edu/dsi/W4SNQ7HR49RL 

This iEEG dataset is from the below publication investigating single pulse stimulation responses in the human brain:
Paulk AC, Zelmann R, Crocker B, Widge AS, Dougherty DD, Eskandar EN, et al. Local and distant cortical responses to single pulse intracranial stimulation in the human brain are differentially modulated by specific stimulation parameters. Brain Stimul 2022. 15: 15:491–508. Available from: https://www.sciencedirect.com/science/article/pii/S1935861X22000456

This dataset is organized in iEEG-BIDS format (https://www.nature.com/articles/s41597-019-0105-7). So, we use MNE-BIDS(https://mne.tools/mne-bids/stable/index.html) to automaticly load the data. The pipeline is in xxx.ipynb

# 2 --> https://memory.psych.upenn.edu/RAM_Public_Data 

This iEEG dataset is from RESTORING ACTIVE MEMORY (RAM) project (https://memory.psych.upenn.edu/RAM) to develop a fully implantable device that can electrically stimulate the brain to improve memory function.

This dataset is organized in RAM-customized format (not iEEG-BIDS). So we manually design the pipeline using MNE to load the data. The pipeline is in xxx.ipynb
