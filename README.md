Note: g-code files ends with "2mm" uses the new feeler gauge block provide by Bambu Lab in their updated wiki page. 
https://wiki.bambulab.com/en/h2/manual-bed-leveling
https://wiki.bambulab.com/h2/troubleshooting/manual-bed-leveling/%E6%89%8B%E5%8A%A8%E8%B0%83%E5%B9%B3%E8%BE%85%E5%8A%A9%E5%9D%97.3mf

1. **Initial Setup with Nozzle:**

    - The right nozzle will move directly above the first bed tramming point, and the heat bed will raise until it’s near the nozzle.
    - Slide a piece of paper between the nozzle and the bed. Adjust the bed screw until you feel slight resistance when moving the paper.
    - You’ll have **1 minute** to complete this step.

2. **Swap to Indicator Mount:**

    - The heat bed will lower, and the toolhead will move to the offset position, aligning the dial indicator tip directly above the first tramming point.
    - Remove the right nozzle and install the indicator mount with the indicator pre-installed.
    - You’ll have **1 minute** to complete this step.

3. **Zero the Dial:**

    - Once the heat bed raises to the final position, **zero the dial**.
    - For each tramming point, you’ll have **30 seconds** to adjust the screw.

4. **Tramming Adjustment:**

    - At each tramming point, adjust the screw until the dial reads as close to **0.00mm** as possible.

5. **Repeat Rounds:**

    - The process will repeat for **up to 10 rounds**.

6. **Stopping Criteria:**

    - You may stop early if, at the end of any round, **all points read 0.00mm** and **no adjustments were made** during that round.
