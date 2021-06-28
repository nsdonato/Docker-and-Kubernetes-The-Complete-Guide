# Curso: Docker and kubernets the complete guide

# Link:

https://santec.udemy.com/course/docker-and-kubernetes-the-complete-guide

# Contenido del curso:

# Section 1: Dive Into Docker!

    1. Finished Code and Diagrams

    2. Join Our Community!

    3. Why Use Docker?

    4. What is Docker?

    5. Docker for Mac/Windows

    6. Installing Docker on MacOS

    7. Installing Docker for Windows Home users

    8. Installing Docker for Windows Profressional

    9. More Windows Professional Setup

    10. One Last Piece of Windows Professional Setup

    11. Installing Docker on Linux

    12. Using the Docker Client

    13. But Really...What's a Container?

    14. How's Docker Running on Your Computer?

# Section 2: Manipulating Containers with the Docker Client

    15. Docker Run in Detail

    16. Overriding Default Commands

    17. Listing Running Containers

    18. Container Lifecycle

    19. Restarting Stopped Containers

    20. Removing Stopped Containers

    21. Retrieving Log Outputs

    22. Stopping Containers

    23. Multi-Command Containers

    24. Executing Commands in Running Containers

    25. The Purpose of the IT Flag

    26. Getting a Command Prompt in a Container

    27. Starting with a Shell

    28. Container Isolation

# Section 3: Building Custom Images Through Docker Server

    29. Creating Docker Images 23:10

    30. Buildkit for Docker Desktop v2.4.0+ and Edge

    31. Building a Dockerfile

    32. Dockerfile Teardown

    33. What's a Base Image?

    34. The Build Process in Detail

    35. A Brief Recap

    36. Rebuilds with Cache

    37. Tagging an Image

    38. Quick Note for Windows Users

    39. Manual Image Generation with Docker Commit

# Section 4: Making Real Projects with Docker

    40. Project Outline

    41. Node Server Setup

    42. A Few Planned Errors

    43. Required WORKDIR update - "Could not detect node name", "idealTree" errors

    44. Base Image Issues

    45. A Few Missing Files

    46. Copying Build Files

    47. Container Port Mapping

    48. Specifying a Working Directory

    49. Unnecessary Rebuilds

    50. Minimizing Cache Busting and Rebuilds

# Section 5: Docker Compose with Multiple Local Containers

    51. App Overview

    52. App Server Starter Code

    53. Assembling a Dockerfile

    54. Introducing Docker Compose

    55. Docker Compose Files

    56. Networking with Docker Compose

    57. Docker Compose Commands

    58. Stopping Docker Compose Containers

    59. Container Maintenance with Compose

    60. Automatic Container Restarts

    61. Container Status with Docker Compose

# Section 6: Creating a Production-Grade Workflow

    62. Development Workflow

    63. Flow Specifics

    64. Docker's Purpose

    65. Project Generation

    66. Create React App Generation

    67. More on Project Generation

    68. Necessary Commands

    69. Creating the Dev Dockerfile

    70. Duplicating Dependencies

    71. React App Exits Immediately with Docker Run Command

    72. Starting the Container

    73. Docker Volumes

    74. Windows not Detecting Changes - WSL2 Update

    75. Bookmarking Volumes

    76. React App Exited With Code 0

    77. Shorthand with Docker Compose

    78. Overriding Dockerfile Selection

    79. Windows not Detecting Changes - Docker Compose

    80. Do We Need Copy?

    81. Executing Tests

    82. Live Updating Tests

    83. Docker Compose for Running Tests

    84. Tests Not Re-running on Windows

    85. Attaching to Web container

    86. Shortcomings on Testing

    87. Need for Nginx

    88. Multi-Step Docker Builds

    89. Named Builders and AWS

    90. Implementing Multi-Step Builds

    91. Running Nginx

# Section 7: Continuous Integration and Deployment with AWS

    92. Services Overview

    93. Github Setup

    94. Important Info about Travis Registration - Do Not Skip

    95. Travis CI Setup

    96. Travis YML File Configuration

    97. Required Travis Script Updates

    98. A Touch More Travis Setup

    99. Automatic Build Creation

    100. Important info about AWS Platform Versions

    101. AWS Elastic Beanstalk

    102. More on Elastic Beanstalk

    103. Travis Config for Deployment

    104. Travis Keys Update and Account Migration

    105. Automated Deployments

    106. Exposing Ports Through the Dockerfile

    107. AWS Build Still Failing?

    108. Workflow With Github

    109. Redeploy on Pull Request Merge

    110. Deployment Wrapup

    111. Environment Cleanup

    112. AWS Configuration Cheat Sheet

    113. Finished Project Code with Updates Applied

# Section 8: Building a Multi-Container Application

    114. Single Container Deployment Issues

    115. Application Overview

    116. A Quick Note

    117. Application Architecture

    118. Worker Process Setup

    119. Important note about PG module version

    120. Express API Setup

    121. Important Update for Table Query

    122. Connecting to Postgres

    123. More Express API Setup

    124. Create React App Generation

    125. Generating the React App

    126. Fetching Data in the React App

    127. Rendering Logic in the App

    128. Exporting the Fib Class

    129. Routing in the React App

# Section 9: "Dockerizing" Multiple Services

    130. Checkpoint Files

    131. Checkpoint Catchup

    132. Reminder on -it flag

    133. Dockerizing a React App - Again!

    134. Important Node Image Version Update

    135. Dockerizing Generic Node Apps

    136. Adding Postgres as a Service

    137. Docker-compose Config

    138. Postgres Database Required Fixes and Updates

    139. Environment Variables with Docker Compose

    140. Required Client Service Update and Worker Environment Variables

    141. The Worker and Client Services

    142. Nginx Path Routing

    143. Routing with Nginx

    144. Building a Custom Nginx Image

    145. Starting Up Docker Compose

    146. Nginx connect() failed - Connection refused while connecting to upstream

    147. Troubleshooting Startup Bugs

    148. Opening Websocket Connections

# Section 10: A Continuous Integration Workflow for Multiple Images

    149. Production Multi-Container Deployments

    150. Important Node Image Version Update

    151. Production Dockerfiles

    152. Multiple Nginx Instances

    153. Nginx fix for React Router

    154. Altering Nginx's Listen Port

    155. Cleaning Up Tests

    156. Github and Travis CI Setup

    157. Fix for Failing Travis Builds

    158. Travis Configuration Setup

    159. Pushing Images to Docker Hub

    160. Successful Image Building

# Section 11: Multi-Container Deployments to AWS

    161. Multi-Container Definition Files

    162. Finding Docs on Container Definitions

    163. Adding Container Definitions to DockerRun

    164. More Container Definitions

    165. Forming Container Links

    166. AWS Configuration Cheat Sheet - Updated for new UI

    167. Creating the EB Environment

    168. Managed Data Service Providers

    169. Overview of AWS VPC's and Security Groups

    170. RDS Database Creation

    171. ElastiCache Redis Creation

    172. Creating a Custom Security Group

    173. Applying Security Groups to Resources

    174. Setting Environment Variables

    175. IAM Keys for Deployment

    176. Travis Keys Update

    177. Travis Deploy Script

    178. Container Memory Allocations

    179. Verifying Deployment

    180. A Quick App Change

    181. Making Changes

    182. Cleaning Up AWS Resources

    183. AWS Configuration Cheat Sheet

    184. Finished Project Code with Updates Applied

# Section 12: Onwards to Kubernetes!

    185. The Why's and What's of Kubernetes

    186. Kubernetes in Development and Production

    187. Docker Desktop's Kubernetes Setup and Installation - macOS

    188. Docker Desktop's Kubernetes Setup and Installation - Windows

    189. Updated Minikube Install and Setup Info - macOS

    190. Minikube Setup on MacOS

    191. Minikube Setup on Windows

    192. Minikube Setup on Linux

    193. Mapping Existing Knowledge

    194. Quick Note to Prevent an Error

    195. Adding Configuration Files

    196. Object Types and API Versions

    197. Running Containers in Pods

    198. Service Config Files in Depth

    199. Connecting to Running Containers

    200. The Entire Deployment Flow

    201. Imperative vs Declarative Deployments

# Section 13: Maintaining Sets of Containers with Deployments

    202. Updating Existing Objects

    203. Declarative Updates in Action

    204. Limitations in Config Updates

    205. Running Containers with Deployments

    206. Quick Note to Prevent an Error

    207. Deployment Configuration Files

    208. Walking Through the Deployment Config

    209. Applying a Deployment

    210. Why Use Services?

    211. Scaling and Changing Deployments

    212. Updating Deployment Images

    213. Rebuilding the Client Image

    214. Triggering Deployment Updates

    215. Imperatively Updating a Deployment's Image

    216. Reminder for Docker Desktop's Kubernetes Users

    217. Multiple Docker Installations

    218. Reconfiguring Docker CLI

    219. Why Mess with Docker in the Node?

# Section 14: A Multi-Container App with Kubernetes

    220. The Path to Production

    221. Checkpoint Files

    222. A Quick Checkpoint

    223. Recreating the Deployment

    224. NodePort vs ClusterIP Services

    225. The ClusterIP Config

    226. Applying Multiple Files with Kubectl

    227. Express API Deployment Config

    228. Cluster IP for the Express API

    229. Combining Config Into Single Files

    230. The Worker Deployment

    231. Reapplying a Batch of Config Files

    232. Creating and Applying Redis Config

    233. Important Note about Expected Postgres Error

    234. Last Set of Boring Config!

    235. The Need for Volumes with Databases

    236. Kubernetes Volumes

    237. Volumes vs Persistent Volumes

    238. Persistent Volumes vs Persistent Volume Claims

    239. Claim Config Files

    240. Persistent Volume Access Modes

    241. Where Does Kubernetes Allocate Persistent Volumes?

    242. Designating a PVC in a Pod Template

    243. Applying a PVC

    244. Defining Environment Variables

    245. Adding Environment Variables to Config

    246. Creating an Encoded Secret

    247. Postgres Environment Variable Fix

    248. Passing Secrets as Environment Variables

    249. Environment Variables as Strings

# Section 15: Handling Traffic with Ingress Controllers

    250. Load Balancer Services

    251. A Quick Note on Ingresses

    252. One Other Quick Note!

    253. Behind the Scenes of Ingress

    254. More Behind the Scenes of Ingress

    255. Optional Reading on Ingress Nginx

    256. Docker Driver and Ingress - IMPORTANT

    257. Update on Ingress Nginx Mandatory Commands

    258. Setting up Ingress Locally with Minikube

    259. Setting up Ingress with Docker Desktop's Kubernetes

    260. Ingress Update "this.state.seenIndexes.map is not a function" / 404 errors

    261. Creating the Ingress Configuration

    262. Testing Ingress Locally

    263. The Minikube Dashboard

    264. Docker Desktop's Kubernetes Dashboard

# Section 16: Kubernetes Production Deployment

    265. The Deployment Process

    266. Google Cloud vs AWS for Kubernetes

    267. Creating a Git Repo

    268. Linking the Github Repo to Travis

    269. Free Google Cloud Credits

    270. Creating a Google Cloud Project

    271. Linking a Billing Account

    272. Updated GKE creation steps for new Google Cloud UI

    273. Kubernetes Engine Init

    274. Creating a Cluster with Google Cloud

    275. Don't Forget to Cleanup!

    276. Kubernetes Dashboard on Google Cloud

    277. Travis Deployment Overview

    278. Installing the Google Cloud SDK

    279. Updated Service Account steps for new GCP UI

    280. Generating a Service Account

    281. Ruby Version Fix

    282. Running Travis CLI in a Container

    283. Travis Login Issues, "iv undefined" or "repository not known"

    284. Encrypting a Service Account File

    285. More Google Cloud CLI Config

    286. Fix For Failing Travis Builds

    287. Running Tests with Travis

    288. Custom Deployment Providers

    289. Unique Deployment Images

    290. Unique Tags for Built Images

    291. Updating the Deployment Script

    292. Configuring the GCloud CLI on Cloud Console

    293. Creating a Secret on Google Cloud

    294. Helm v3 Update

    295. Helm Setup

    296. Kubernetes Security with RBAC

    297. Assigning Tiller a Service Account

    298. Ingress-Nginx with Helm

    299. Quick Note about the Default

    300. The Result of Ingress-Nginx

    301. Finally - Deployment!

    302. Did I Really Type That?

    303. Verifying Deployment

    304. A Workflow for Changing in Prod

    305. Merging a PR for Deployment

    306. That's It! What's Next? 2min

    307. Completed Code For Google Cloud Deployment

# Section 17: HTTPS Setup with Kubernetes

    308. HTTPS Setup Overview

    309. Domain Purchase

    310. Domain Name Setup

    311. Required Updates for Cert Manager Install

    312. Cert Manager Install

    313. How to Wire Up Cert Manager

    314. Required Update for Issuer

    315. Issuer Config File

    316. Required Update for the Certificate

    317. Certificate Config File

    318. Deploying Changes

    319. No Resources Found?

    320. Verifying the Certificate

    321. Required Update for the HTTPS Ingress

    322. Ingress Config for HTTPS

    323. It Worked!

    324. Google Cloud Cleanup

    325. Local Environment Cleanup

# Section 18: Local Development with Skaffold

    326. Awkward Local Development

    327. Installing Skaffold

    328. The Skaffold Config File

    329. Skaffold Sync Update and Example Source Code

    330. Live Sync Changes

    331. Automatic Shutdown

    332. Testing Live Sync with the API Server

# Section 19: Extras
