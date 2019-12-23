# cs224w
Repository for cs224w project "Stock Recommendation using Information Connection from Financial Bipartite Graph"


for dataset: https://www.quandl.com/databases/SFA/data

for JODIE: https://github.com/srijankr/jodie/


As described in project report and poster, we constructed three graphs using SF3 dataset.

1. Directed Investor-Investor Graph: two investors share an edge if they invest to same stock in subsequent quarters.  This graph is used for role detection (HITs analysis, PageRank analysis, and Motif analysis)

2. Undirected Investor-Investor Graph: two investors share an edge if they invest to same stock in a same quarter.  This graph is used for community detection (Louvain algorithm)

3. Investor-Stock Bipartite Graph: an investor and a stock have an edge if an investor invests to a stock.
