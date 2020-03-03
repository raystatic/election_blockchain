# Election Based On Blockchain

## pre-requisites

### Install node
### https://nodejs.org/en/download/

### Install Ganache
### https://www.trufflesuite.com/ganache

### Install truffle
### https://www.trufflesuite.com/docs/truffle/getting-started/installation


## ganache should be running before hand

## to setup project run "npm install" after cloning

## After changes in contracts you need to migrate contracts as a new copy by runnig "truffle migrate --reset"

## to compile transaction run "truffle compile"

## to run tests of contracts run "truffle test"

## to run project on lite-server, run "npm run dev"

### Project Tour

### Initial View

#### Initially both the candidates have 
![1](https://user-images.githubusercontent.com/31301266/75688746-0d060600-5cc6-11ea-8c0d-4da75cff8dc3.png)

#### Confirm transaction for candidate 1
![2_confrm_txn_for_cand1](https://user-images.githubusercontent.com/31301266/75685818-3708f980-5cc1-11ea-8bef-5459824395d7.png)

#### Now Candidate 1 has 1 vote
![3_voted_for_cand1](https://user-images.githubusercontent.com/31301266/75685827-3a03ea00-5cc1-11ea-98a6-40a5d49c548d.png)

#### Once Voted from one account, user cannot vote again, so now we need to import another account
![4_import_another_account](https://user-images.githubusercontent.com/31301266/75685833-3bcdad80-5cc1-11ea-8778-cdcfbcc701e9.png)

#### After confirmation for candidate 2, now candidate 2 also has one vote
![5_cand2_txn_confrm](https://user-images.githubusercontent.com/31301266/75685837-3cfeda80-5cc1-11ea-8eb1-b0d5bbe05cd7.png)
