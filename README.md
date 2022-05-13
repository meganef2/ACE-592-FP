# ACE 592 - Final Group Project
## Illinois Farm Lease Type and Crop Insurance
### Jake Toma, Caleb Reed, Caden Heyen, Megan Finfrock, Cassidy Thomas

This readme file explains the organization of the repository and the background of the project. 

The data for this analysis includes county-level data from the Illinois Farm Business Farm Management (FBFM) system and Summary of Business data from the United States Department of Agriculture Risk Management Agency. 
Using this data, the group analyzes trends in farm data regaring coverage levels of crop insurance and types of land ownership. This project will also examine whether risk preferences predict Illinois farmland lease types, as well as what the shift in lease types over time implies about changes in risk preferences.

The directory "ACE 592 Final Project" contains a majority of the code for this project. This code should be ran in the sequence of occurence provided in the directory. This includes the initial reading in and cleaning of the data, as well as plotting maps and graphs of trends over time. This directory was created as a group on one computer during meetings.

The variables for the crop insurance can be further explained by the following:
   
    Commodity Year: The identifier that represents the year in which the crop/commodity is normally harvested and indicates the policy year for which coverage was provided.
    
    State Code: The FIPS code that denotes the State in which the insured farm is located.
   
    State Abbreviation:	USPS state abbreviation
    
    County Code: A FIPS code indicating the county in which the insured farm is located
    
    County Name: Name of the county
    
    Commodity Code: The Risk Management Agency (RMA) code that denotes the crop/commodity for which the policy is issued.
    
    Commodity Name: Name of the crop/commodity
    
    Insurance Plan Code: Code that denotes the type of insurance coverage is selected for the insured crop (e.g.APH, Revenue, Dollar, etc.)
    
    Insurance Plan Name Abbreviation: Abbreviation of the Insurance Plan Name
    
    Coverage Level: Elected by the insured, its complement is the deductible.  The base to which it applies differs by insurance plan (e.g. - yield, revenue, dollar, or inventory).  Expressed as a decimal
    
    Policies Sold Count: The number of policies reported to RMA as being sold.
    
    Net Reported Quantity: Number of acres, tons, pounds, etc. reported as being planted adjusted by the insured’s share in the commodity. (e.g. reported acres * insured’s share)


Additionally, the FBFM data includes the following variables:
    
    Year
    
    FBFM Code: Denotes county
    
    Debt_to_asset: The average debt/asset ratio for farms in the county.
    
    Cash_acres: Total cash rented acres in the county.
    
    Share_acres: Total share rented acres in the county.
    
    Owned_acres: Total owned acres in the county.
    
    SPR: The average soil productivity rating for farms in the county.
    
    
## Data Directories
The directory titled "d01" houses all of the files concerning the FBFM lease type data.

The directory titled "d02" contains all of the Illinois shapefile data. 

The directory title "d03" consist of each year of the insurance data.

Lastly, the directory "ACE 592 Final Paper" is the write-up for the project. 
