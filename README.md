# evoting

## About The Project
## Functionalities

We have three user categories:

- Admin
- Election Officer
- Voters

Each functionality mentioned below is bundled with a user category and can be accessed by login into the particular user category.

1. User Registration:
    - An election officer/admin can register himself/herself by providing appropriate information.
2. Login for Election Officer and Admin:
    - Standard Spring login-authentication system is used to validate the user trying to login.
    - Based on the group the user belongs to he/she is redirected to the specified pages of the group.
3. Creation and Managing Political Party:
    - Admin has to enter the name of the political party name along with other details.
    - A political party  is then generated if details are found to be valid.
4. Creation and Managing Constituency:
    - Admin has to enter the name of the constituency name along with other details.
    - A constituency  is then generated if details are found to be valid.
5. Managing Candidates:
    - Admin has to enter the name of the candidate along with other details like political party affiliation and constituency they belong to.
    - A candidate  is then generated if details are found to be valid.
6. Managing Elections:
    - Admin has to conduct elections  along with other details 
    - An election  is then generated if details are found to be valid.
7. Adding Voters:
    - The Admin or Election Officer adds voters to Elections and details will be added.
    - If details are correct then a unique token will be generated. Token will be given to voters.
8. Conducting Election:
    - Elections can be started by Admin after adding political parties, Candidates and details of election.
9. Cast a Vote:
    - The Voters will provide a token number in the e-voting window that will redirect them to details.
    - If details are correct a voter can cast a vote for his candidate.  
10. Viewing Result:
    - The Admin or Election Officer can view the result.
    - Result will be declared who is winning the election, which party is first, % voting done etc.
11. Https and SSL enabled on server:
    - For security purposes we enabled SSL and https protocols on application.
    - So data transferred through server and client will be secure and encrypted. It provides secrecy of data in application.
    - Key pair generated through keytool utility that is required to run both applications.
12. Token Generation:
    - Whenever a voter added then a unique token generated valid for 3 hrs.
    - That will provide authentication and uniqueness to the application.
