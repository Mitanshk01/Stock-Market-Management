# Stock-Market-Management
This is a CLI operated DBMS for Stock Market , built using Python and MySQL with CRUD language

DNA project-4 1
DNA project-4
team 26
contributors Rhythm , Mitansh , Khushi Goyal
Video
Demo
https://iiitaphydmy.sharepoint.com/:v:/g/personal/rhythm_aggarwal_students_iiit_ac_in/EaKtOi29lS9PgG0DdzGSmUBu7ZqR-VdLwNNd7_8rPFh6g?e=dVS3Qo
Queries Supported By the DBMS
INSERT
insert FAVORITES [Company_Name]
insert COMPANIES [Company_Name Founder_ID Sector StockUID DividendYield]
Note: if the user is admin one more insert query will be supported
insert COMPANIES [Company_Name] [Founder ID] [Sector] [stock Unique ID] [Dividend yield]
DELETE
delete FAVORITES [Company_Name]
delete USER
SEARCH
search COMPANIES [starting letter]
UPDATE
update USER [new email-id]
update COMPANY [Prev_Company_Name New_Company_Name]
DNA project-4 2
update DIVIDEND [Company_Name New_Dividend_Yield]
SELECT
select COMPANIES [company-sector]
AGGREGATE
aggregate COMPANIES [company-sector]
ANALYSIS
analysis BOD% [Min.Percentage of stocks held by BOD]
analysis FAVORITES
GRAPH ANALYSIS
The CLI also supports graph based analysis of a COMPANY stock price on a particular date
plot COMPANIES [Company Name]
