
## LensAPI Oracle
The LensAPI Oracle is a versatile solution that empowers developers to perform aggregations and complex queries of Lens data via web and mobile applications using HTTP requests. As the popularity of SocialFi platforms like Lens continues to rise, the demand for Oracles capable of bringing various data types on-chain through APIs has grown significantly. The Phala Network's LensAPI Oracle addresses this demand by providing developers with a customizable, no-code Oracle template. With this template, developers can deploy tailored Oracles in a matter of minutes.

## Introduction
The LensAPI Oracle serves as a bridge between your smart contracts and Lens data, enabling seamless interaction between the two. Developers can utilize HTTP requests to retrieve Lens data and execute aggregations and complex queries. The Oracle template is designed to be highly flexible and easily deployable, ensuring that developers can integrate it into their projects with minimal effort.

## Features
. Query Lens user and post stats using profile IDs.
. Perform aggregations and complex queries with Lens data.
. Deploy customizable, no-code Oracles quickly and efficiently.

## Usage
The LensAPI Oracle enables developers to interact with Lens data through two main APIs: User Stats API and Post Stats API.


## User Stats API
The User Stats API allows you to retrieve information about Lens users based on their profile IDs. The following fields are available for querying:

. Total followers
. Total followings

# Example usage:
GET /user-stats?profile_id=<PROFILE_ID>


# Post Stats API
The Post Stats API enables you to gather data related to Lens posts. The available fields for querying are:

. Total posts
. Total comments
. Total mirrors
. Total publications

# Example usage:
GET /post-stats?profile_id=<PROFILE_ID>



## Check my  deployed consumer contract on mumbai polygon.
<https://mumbai.polygonscan.com/address/0x7E9022b9d3FE53330A884227166a73F828FFef73

# Attestor address
0xd62dcaa6d27ad95f9c00db40d8d06d6afc93bea8

