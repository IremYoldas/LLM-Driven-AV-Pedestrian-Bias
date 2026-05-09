# LLM-Driven Autonomous Vehicles Inherit Human Driver Biases in Pedestrian Yielding: Results and Implications From A New Benchmark
Irem Yoldas, Jie Zhang, Odinaldo Rodrigues,  Martim Brandao

<p align="center">
  <img src="https://github.com/user-attachments/assets/bd0aa0fb-2bc6-476d-a1eb-aec2b1edf323" width="48%" />
  <img src="https://github.com/user-attachments/assets/2180e530-aeb3-4b59-9016-89cc5bc73b6b" width="48%" />
</p>


💥 This repo contains the VLM (Self Consistency) test and the LLM (All Else Being Equal) test of our benchmark in our paper. 

Due to space limitations, you can find the graphs that we were unable to include in the paper article here!

# Self Consistency (SC) Test
In SC test:
1. First we ask whether the pedestrian has an intention to cross and is able to cross safely if the vehicle does not stop as **Roud-1**.
2. Ask questions about demographic information and whether the autonomous vehicle will stop or not as **Round-2**.

## Dataset Access

Due to GitHub file size limitations, the SC test images that we used are hosted externally.

You can download them here: [Google Drive Link](https://drive.google.com/drive/folders/1NdwOvkvfzkvKgKbUstkWZccC2GKJvno9?usp=drive_link)

# All Else Being Equal (AEBE) Test

In LLM Prompts file, you can find two questions:
1. For generating written scenarios via images
2. A question to be added at the end of the written scenarios for the prompt

In _json_ file, you can find every written scenario that we used!

## Dataset Access

Due to GitHub file size limitations, the AEBE test scenarios are hosted externally.

You can download them here: [Google Drive Link](https://drive.google.com/file/d/1-tpGFphaqTpMgQzuAJRDWje1tSYKkovJ/view?usp=sharing)

# Citation
If you think this repo or paper is useful, do not forget to cite our paper, please: 
