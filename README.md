# LendingClub Project- PySpark


lending club dataset- 1.7GB
1 file (csv format)
118 columns
2+ million records

Read the csv file
project is not done on a single file
atleast 3-4 files are required to do this project

---------------------------------------
we can create 4 datasets out of it
and the datasets are mentioned here

customers_data (borrowers details)
member_id, emp_title, emp_length, home_ownership, annual_inc, addr_state, zip_code, country, grade, sub_grade,verification_status, tot_hi_cred_lim , application_type , annual_inc_joint , verification_status_joint

loans_data
loan_id- will be unique , member_id- ideally one member can have many loans, loan_amnt, funded_amnt , term, int_rate, installment, issue_d, loan_status, purpose, title

loan_repayments
loan_id- primary key, total_rec_prncp, total_rec_int , total_rec_late_fee , installment , last_pymt_amt, last_pymt_d, next_pymnt_d

loan_defaulters
member_id , delinq_2yrs , delinq_amnt , pub_rec , pub_rec_bankruptcies , inq_last_6mths , total_rec_late_fee, mths_since_last_delinq, mths_since_last_record

REFER DATA DICTIONARY FILE ATTACHED FOR DESCRIPTION OF THE COLUMNS

