# ChessTubeTree

ChessTubeTree is a unified rating list for the world's strongest chess engines. 

This project provides an interactive ranking table that calculates a **Main Rating** based on a weighted average of several independent computer chess rating pools.

### ✨ Features

* **Dynamic Weighted Average:** Users can adjust the weight of each source list to calculate their own custom rankings.
* **Smart View Toggle:** Switch between viewing every engine version or the **"Best Version Only"** (which automatically shows only the top-rated version for each engine family).
* **Pool Scaling:** Automatically applies normalization multipliers to different rating pools to ensure a fair and accurate "Main Rating."
* **Interactive Filtering:** Filter engines by Family, Language (C++, Rust, etc.), Access (Public/Private), and Release Year. Dropdown menus auto-close for a cleaner experience.
* **Theme Support:** Switch between **Dark Mode**, **Classic Wooden**, and **Terminal Hacker** themes.

### 📊 Methodology

To calculate the **Main Rating**, we use data from five major rating lists. Because these lists use different anchors and hardware scales, we normalize them as follows before averaging:

* **CCRL 40/40:** 1.05x
* **Ipman:** 1.06x
* **CEGT:** 1.05x
* **CCRL Blitz:** 1.00x (Baseline)
* **SP-CC:** 1.00x (Baseline)

On the website, these are displayed as **Original Rating (Scaled Rating)** for full transparency.

### 🙏 Credits & Data Sources

We would like to thank the following organizations and individuals for providing the testing data that makes this list possible:

* **CCRL (Computer Chess Rating Lists)**
  * [40/40 List](https://computerchess.org.uk/4040/rating_list_all.html)
  * [Blitz List](https://computerchess.org.uk/404/rating_list_all.html)
* **SP-CC (Strategy Puzzles - Computer Chess)**
  * [Official Website](https://www.sp-cc.de/)
* **Ipman Chess**
  * [Rating Benchmarks](https://ipmanchess.yolasite.com/r9-7945hx.php)
* **CEGT (Chess Engine Grand Tournament)**
  * [40/20 Rating List](http://www.cegt.net/40_40%20Rating%20List/40_40%20All%20Versions/rangliste.html)

### 🛠️ Contribute

Feel free to contact me if you notice any problems, mistakes, bugs, or if you have any suggestions or feedback.
