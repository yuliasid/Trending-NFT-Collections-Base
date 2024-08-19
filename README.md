# NFT Collection Ranking on Base

## Project Overview
This project analyzes NFT collections on the Base, ranking them based on minting activity and creator influence using the EigenTrust algorithm.

## Key Features
- Data collection from Base (last 30 days, limited to 100,000 records)
- Calculation of localtrust and pretrust scores
- Application of EigenTrust algorithm for final ranking
- List of top trending NFT collections

## Limitations
- Dataset limited to 100,000 records, which may not represent the entire ecosystem
- Analysis covers only the last 30 days of activity
- Results may be biased towards high-value or recent transactions due to data limitations

## Results
The analysis provides a ranking of NFT collections based on their calculated scores. The top collections represent those with the highest combination of minting activity and creator influence.

## Post-Deadline Update
**Important Note:** After the official submission deadline, I discovered that I had forgotten to run the final version of the modified code in my initial submission. As a result, I've updated the repository with the correct output from the properly executed analysis. 
This update was made on 19 of August - commit bf57a74; predeadline commit was 96d1147 (there is an error in the last part of the code that was not run correctly and gave the same scores for the collections).

While this update occurred after the deadline, it represents a more accurate reflection of the intended analysis. I apologize for any confusion this may have caused and appreciate your understanding.

## Future Improvements
- Expand the dataset to cover a larger number of transactions
- Implement time series analysis to track trends over longer periods
