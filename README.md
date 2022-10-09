# Kaleido-Project-Mac

- Deployed `nginx` on Kubernetes cluster using `terraform`

<img width="1430" alt="Screen Shot 2022-10-04 at 1 55 01 PM" src="https://user-images.githubusercontent.com/36927669/193900405-02436b7d-1453-44fc-862e-60ff9662cc82.png">

- Deployed Quorum implementation of Ethereum + IPFS cluster as well

  Steps:
    - Go inside `simple_env` and run `terraform init`
    - Now after the successful run, type `terraform apply` and you'll be prompted to enter `api_key` that you can get from Kaleido's Profile Section.
    - You're nodes and IPFS cluster should be created on the Kaleido's Environment Dashboard.
    
    <img width="1440" alt="Screen Shot 2022-10-04 at 9 04 14 PM" src="https://user-images.githubusercontent.com/36927669/193957569-4b9d1909-2d59-4c21-9a85-b82e478299ea.png">

- Set up the Sandbox and Firefly Dashboard manually

![Screen Shot 2022-10-05 at 12 53 30 AM (2)](https://user-images.githubusercontent.com/36927669/193984160-bf221b7b-5c34-4940-9dde-7329f65025a7.png)

- Followed the doc to find out how to deploy smart contract for `simplestorage.sol`

<img width="1440" alt="Screen Shot 2022-10-06 at 6 44 13 PM" src="https://user-images.githubusercontent.com/36927669/194432121-0c68cb4b-3ea6-4268-9b19-c11af76fe77e.png">

- Smart Contract Deployed
<img width="1440" alt="Screen Shot 2022-10-08 at 4 55 33 PM" src="https://user-images.githubusercontent.com/36927669/194727841-c32ddfee-8cbf-45a9-a2bb-9981c56309f6.png">


- `Postgres` setup complete using `make deps`
<img width="1440" alt="Screen Shot 2022-10-09 at 2 12 21 PM" src="https://user-images.githubusercontent.com/36927669/194772915-649118f6-4c58-4dfa-9457-0155779e83dd.png">

- All charts installed using `make test` - using the original values given inside yaml files

<img width="1440" alt="Screen Shot 2022-10-09 at 2 12 07 PM" src="https://user-images.githubusercontent.com/36927669/194772949-5e70b12c-aeea-4dab-9884-98a0411d970e.png">


