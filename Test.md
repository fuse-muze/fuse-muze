# bondbond - Directus’s Flow

<p align="center">
<img src="https://dev-bondbond.lynnlemon.com/static/media/bondbond_logo.41266b83aec9c2434555.png" alt="bondbond-icon" width="150"/>
<img src="https://cdn.iconscout.com/icon/free/png-256/free-danger-electric-electricity-lightning-voltage-zap-high-37933.png" alt="zap-icon" width="100"/>
<img src="https://d4.alternativeto.net/-4gurA08If2BjbP5ngviPJS-KkhNXcC1vlqoKbasXoo/rs:fit:280:280:0/g:ce:0:0/exar:1/YWJzOi8vZGlzdC9pY29ucy9kaXJlY3R1c18yMDkzOTIucG5n.png" alt="directus-icon" width=150 />
</p>

---
## 📋 Table of Flow
 - [Create Customer Community Profile Flow](#create-customer-community-profile-flow )

## ⚡ Create Customer Community Profile Flow

This hook is designed to detect when a new user has been created, triggering Directus to create a customer with community data in the customer community collection.
### Diagram :
```mermaid
graph LR
A[On Customer created] -- created customer --> B[Create customer community] 
```
### Step :
    1. trigger when customer created
    2. create new field in customer community profile




