# ERC 721 NFT Project

1. This Contract I have Created Three User's Who can do mint NFT's and also set limit In these User's
      WhiteList Admin
      WhiteList User
      public user
    
###### WhiteList Admin
           - Only Owner can add or remove WhiteList Admin Address
           - WhiteList Admin Set and Update BaseURI
           - I have set WhiteList Admin NFt's minting Limit 
###### WhiteList User
           - Only Owner can add or remove WhiteList User Address
           - I have set WhiteList User NFT's minting limit 
###### public user   
           - I have set Public User NFt's Limit 
           - Everyone Can mint Public NFT's

## Owner just mint public NFT's

*Checks*
   - All Contract function can be pause and unpause by the Owner of the Contract
   - Only Owner can active or deActive public Sales
   - Contract have Default BaseURi function can be set by WhiteList Admin Address
   - EveryOne can mint as Public but in WhiteList user Minting only WhiteUser can mint and same as WhiteLsit Admin 
   - We have reserved a limit for Each WhiteList Admin , WhiteList User and Public User One address can mint upto 5 NFT's IF an Address have minting 5 NFT's then it Can't Mint More NFT's
   - IF MAx Limit , WhiteList Admin , WhiteList User , Public User is Zero(0) then no one can not mint 
   - If tokenID will be 0 then cannot NFt's
   - When Public Sales are Active then WhiteList NFt's add in Public Limit And whiteList limit will be 0.
   - We can check WhiteList Admin Address that address is admin list or not and same as WhiteList User.
   - If public sales are active You can't call again ActivePublic Function same as DeActivePublic.
   - IF WhiteList User Already in list you can't add this address in again.
   - IF WhiteLIst Admin Alreadt is List you can't Add this address in again.
   
   *Best Regards*
   
   


