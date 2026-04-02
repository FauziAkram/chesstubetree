\# ChessTubeTree



ChessTubeTree is a unified rating list for the world's strongest chess engines. 



This project provides a real-time, interactive ranking table that calculates a "Main Rating" based on a weighted average of several independent computer chess rating pools.



\### ✨ Features

\* \*\*Dynamic Weighted Average:\*\* Users can adjust the weight of each source list to calculate their own custom rankings.

\* \*\*Pool Scaling:\*\* Automatically applies 1.07x and 1.02x multipliers to normalize differences in rating scales across different testing environments.

\* \*\*Interactive Filtering:\*\* Filter engines by Family, Language (C++, Rust, etc.), Access (Public/Private), and more.

\* \*\*Theme Support:\*\* Switch between Dark Mode, Classic Wooden, and Terminal Hacker themes.



\### 📊 Methodology

To calculate the \*\*Main Rating\*\*, we use data from five major rating lists. Because these lists use different anchors, we scale them as follows before averaging:

\* \*\*CCRL 40/40:\*\* 1.07x

\* \*\*CCRL Blitz:\*\* 1.02x

\* \*\*Ipman:\*\* 1.07x

\* \*\*CEGT:\*\* 1.07x

\* \*\*SP-CC:\*\* 1.00x (Baseline)



\### 🙏 Credits \& Data Sources

We would like to thank the following organizations and individuals for providing the testing data that makes this list possible:



\* \*\*CCRL (Computer Chess Rating Lists)\*\*

&#x20; \* \[https://computerchess.org.uk/4040/rating\_list\_all.html]()

&#x20; \* \[https://computerchess.org.uk/404/]()

\* \*\*SP-CC (Strategy Puzzles - Computer Chess)\*\*

&#x20; \* \[https://www.sp-cc.de/]()

\* \*\*Ipman Chess\*\*

&#x20; \* \[https://ipmanchess.yolasite.com/r9-7945hx.php]()

\* \*\*CEGT (Chess Engine Grand Tournament)\*\*

&#x20; \* \[http://www.cegt.net/40\_40%20Rating%20List/40\_40%20All%20Versions/rangliste.html]()



\### 🛠️ Contribute

Feel free to contact me if you notice any problems, mistakes, bugs, or if you have any suggestions or feedback.

