Files:

survey1anon.csv - data survey markets 1, anonymized
survey2anon.csv - data survey markets 2, anonymized
survey_script.R - R script to calculate survey means, standard deviation in response, and expertize-weighted mean

trades_report1anon.csv - trading data from market 1, test trades removed, anonymized
trades_report2anon.csv - trading data from market 2, test trades removed, anonymized
trades_report12anon.csv - trading data from market 1 and two merged (for more convenient analysis), anonymized
market_analysis_psych1_final.R - R script to calculate volume, trades, traders per market for markets1; plot fig S1A
market_analysis_psych2_final.R - R script to calculate volume, trades, traders per market for markets2; plot fig S1A
market_analysis_pooled_final.R - R script to calculate trading data over both markets

data4Rmerged_final_20151027.csv - synthesises all relevant data in one table
p_analysis_merged_additional_figs.R - analyses data from merged table, calculates p's, figures, including additional versions 

1. Survey data

Markets 1: sent 04.01.2014 from Anna Dreber.
col 1: participant - omitted
col 2-70: three successive columns correspond to hypothesis [xx].
          h[XX] confirms that the hypothesis has been displayed
          q[xx]a gives the estimated probability from 0 ... 100
          q[xx]b gives self-rated expertize from 1 ... 5
Output enters Table S1. Values checked 27.10.2015
Row 2 omitted because the hypothesis was changed after survey but before market.

Market 2: sent 14.10.2015 from Anna Dreber.
col 1: participant - omitted
col 2-64: three successive columns correspond to hypothesis [xx].
          h[XX] confirms that the hypothesis has been displayed
          q[xx]a gives the estimated probability from 0 ... 100
          q[xx]b gives self-rated expertize from 1 ... 5
Output enters Table S1. Values checked 27.10.2015


2. Trading data

trades_report1anon.csv - Trading in Market 1: as obtained by Consensus Point. (test trades removed, anonymized)
*Market Name - "Replicator Market"
*Market ID - 14	
User ID	- unique trader identifier
*First Name - omitted
*Last Name - omitted
*Username - omitted
*Email - omitted
Question Title - Hypothesis name
Question ID - identifier
Outcome Title - either "Yes" or "No": Yes - long position; No - short position
*Outcome ID - Question x Outcome identifier
*Order ID - identifier	
Order Quantity - traded volume
Order Type - "buy" or "sell": increase or decrease a long or short position
Order Cost - cost (cash paid for traded volume)
*Placed Successfully - transaction successful
*Date - date of transaction

* indicates data not used.
Output enters Table S5. Values checked 27.10.2015
generates portfolio figure panel A


trades_report2anon.csv - Trading in Market 2: as obtained by Consensus Point. (test trades removed, anonymized)
Analogous column identifiers as in trading data from market 1.
Output enters Table S6. Values checked 27.10.2015
generates portfolio figure panel B

trades_report_merged_anon.csv - merged file with the trading data for the two markets
Analogous column identifiers as in trading data from market 1.


3. Combined data, calculation of the p's
data4Rmerged_final_20151027.csv
Hypothesis #	
Hypothesis	
Outcome of original study	
Outcome of replication (yes/no)	
Market price	
Survey result	
Weighted survey result	
Original N	
Original power	
Replication N	
Replication power	
Replication p-value	
NumberOfTrades	
Vol	
sdev_survey

