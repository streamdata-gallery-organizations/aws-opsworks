---
name: AWS OpsWorks
x-slug: aws-opsworks
description: AWS OpsWorks is a configuration management service that uses Chef, an
  automation platform that treats server configurations as code. OpsWorks uses Chef
  to automate how servers are configured, deployed, and managed across your Amazon
  Elastic Compute Cloud (Amazon EC2) instances or on-premises compute environments.
  OpsWorks has two offerings, AWS Opsworks for Chef Automate, and AWS OpsWorks Stacks.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
x-kinRank: "10"
x-alexaRank: "0"
tags: AWS OpsWorks
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/apis.md
specificationVersion: "0.14"
apis:
- name: AWS OpsWorks API Assign Instance
  x-api-slug: aws-opsworks-api
  description: Assign a registered instance to a layer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=AssignInstance
  tags: Assign,Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionassigninstance-get-openapi.md
- name: AWS OpsWorks API Assign Volume
  x-api-slug: aws-opsworks-api
  description: Assigns one of the stack's registered Amazon EBS volumes to a specified
    instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=AssignVolume
  tags: Assign,Volume
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionassignvolume-get-openapi.md
- name: AWS OpsWorks API Associate Elastic IP
  x-api-slug: aws-opsworks-api
  description: Associates one of the stack's registered Elastic IP addresses with
    a specified instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=AssociateElasticIp
  tags: Associate,Elastic,IP Addresses
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionassociateelasticip-get-openapi.md
- name: AWS OpsWorks API Attach Elastic Load Balancer
  x-api-slug: aws-opsworks-api
  description: Attaches an Elastic Load Balancing load balancer to a specified layer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=AttachElasticLoadBalancer
  tags: Attach,Elastic,Load,Balancer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionattachelasticloadbalancer-get-openapi.md
- name: AWS OpsWorks API Clone Stack
  x-api-slug: aws-opsworks-api
  description: Creates a clone of a specified stack.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=CloneStack
  tags: Clone,Stack
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionclonestack-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionclonestack-get-openapi.md
- name: AWS OpsWorks API Create App
  x-api-slug: aws-opsworks-api
  description: Creates an app for a specified stack.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=CreateApp
  tags: App
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actioncreateapp-get-openapi.md
- name: AWS OpsWorks API Create Deployment
  x-api-slug: aws-opsworks-api
  description: Runs deployment or stack commands.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=CreateDeployment
  tags: Deployment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actioncreatedeployment-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actioncreatedeployment-get-openapi.md
- name: AWS OpsWorks API Create Instance
  x-api-slug: aws-opsworks-api
  description: Creates an instance in a specified stack.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=CreateInstance
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actioncreateinstance-get-openapi.md
- name: AWS OpsWorks API Create Layer
  x-api-slug: aws-opsworks-api
  description: Creates a layer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=CreateLayer
  tags: Layer
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actioncreatelayer-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actioncreatelayer-get-openapi.md
- name: AWS OpsWorks API Create Stack
  x-api-slug: aws-opsworks-api
  description: Creates a new stack.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=CreateStack
  tags: Stack
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actioncreatestack-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actioncreatestack-get-openapi.md
- name: AWS OpsWorks API Create User Profile
  x-api-slug: aws-opsworks-api
  description: Creates a new user profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=CreateUserProfile
  tags: User,Profile
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actioncreateuserprofile-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actioncreateuserprofile-get-openapi.md
- name: AWS OpsWorks API Delete App
  x-api-slug: aws-opsworks-api
  description: Deletes a specified app.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DeleteApp
  tags: App
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondeleteapp-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondeleteapp-get-openapi.md
- name: AWS OpsWorks API Delete Instance
  x-api-slug: aws-opsworks-api
  description: Deletes a specified instance, which terminates the associated Amazon
    EC2 instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DeleteInstance
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondeleteinstance-get-openapi.md
- name: AWS OpsWorks API Delete Layer
  x-api-slug: aws-opsworks-api
  description: Deletes a specified layer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DeleteLayer
  tags: Layer
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondeletelayer-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondeletelayer-get-openapi.md
- name: AWS OpsWorks API Delete Stack
  x-api-slug: aws-opsworks-api
  description: Deletes a specified stack.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DeleteStack
  tags: Stack
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondeletestack-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondeletestack-get-openapi.md
- name: AWS OpsWorks API Delete User Profile
  x-api-slug: aws-opsworks-api
  description: Deletes a user profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DeleteUserProfile
  tags: User,Profile
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondeleteuserprofile-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondeleteuserprofile-get-openapi.md
- name: AWS OpsWorks API Deregister Ecs Cluster
  x-api-slug: aws-opsworks-api
  description: Deregisters a specified Amazon ECS cluster from a stack.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DeregisterEcsCluster
  tags: Deregister,Ecs,Cluster
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionderegisterecscluster-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionderegisterecscluster-get-openapi.md
- name: AWS OpsWorks API Deregister Elastic IP
  x-api-slug: aws-opsworks-api
  description: Deregisters a specified Elastic IP address.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DeregisterElasticIp
  tags: Deregister,Elastic,IP Addresses
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionderegisterelasticip-get-openapi.md
- name: AWS OpsWorks API Deregister Instance
  x-api-slug: aws-opsworks-api
  description: Deregister a registered Amazon EC2 or on-premises instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DeregisterInstance
  tags: Deregister,Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionderegisterinstance-get-openapi.md
- name: AWS OpsWorks API Deregister Rds Db Instance
  x-api-slug: aws-opsworks-api
  description: Deregisters an Amazon RDS instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DeregisterRdsDbInstance
  tags: Deregister,Rds,Db,Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionderegisterrdsdbinstance-get-openapi.md
- name: AWS OpsWorks API Deregister Volume
  x-api-slug: aws-opsworks-api
  description: Deregisters an Amazon EBS volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DeregisterVolume
  tags: Deregister,Volume
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionderegistervolume-get-openapi.md
- name: AWS OpsWorks API Describe Agent Versions
  x-api-slug: aws-opsworks-api
  description: Describes the available AWS OpsWorks Stacks agent versions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DescribeAgentVersions
  tags: Describe,Agent,Versions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondescribeagentversions-get-openapi.md
- name: AWS OpsWorks API Describe Apps
  x-api-slug: aws-opsworks-api
  description: Requests a description of a specified set of apps.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DescribeApps
  tags: Describe,Apps
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondescribeapps-get-openapi.md
- name: AWS OpsWorks API Describe Commands
  x-api-slug: aws-opsworks-api
  description: Describes the results of specified commands.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DescribeCommands
  tags: Describe,Commands
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondescribecommands-get-openapi.md
- name: AWS OpsWorks API Describe Deployments
  x-api-slug: aws-opsworks-api
  description: Requests a description of a specified set of deployments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DescribeDeployments
  tags: Describe,Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondescribedeployments-get-openapi.md
- name: AWS OpsWorks API Describe Ecs Clusters
  x-api-slug: aws-opsworks-api
  description: Describes Amazon ECS clusters that are registered with a stack.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DescribeEcsClusters
  tags: Describe,Ecs,Clusters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondescribeecsclusters-get-openapi.md
- name: AWS OpsWorks API Describes Elastic IPs
  x-api-slug: aws-opsworks-api
  description: Describes Elastic IPs
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DescribeElasticIps
  tags: Describes,Elastic,IP Addressess
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondescribeelasticips-get-openapi.md
- name: AWS OpsWorks API Describe Elastic Load Balancers
  x-api-slug: aws-opsworks-api
  description: Describes a stack's Elastic Load Balancing instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DescribeElasticLoadBalancers
  tags: Describe,Elastic,Load,Balancers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondescribeelasticloadbalancers-get-openapi.md
- name: AWS OpsWorks API Describe Instances
  x-api-slug: aws-opsworks-api
  description: Requests a description of a set of instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DescribeInstances
  tags: Describe,Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondescribeinstances-get-openapi.md
- name: AWS OpsWorks API Describe Layers
  x-api-slug: aws-opsworks-api
  description: Requests a description of one or more layers in a specified stack.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DescribeLayers
  tags: Describe,Layers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondescribelayers-get-openapi.md
- name: AWS OpsWorks API Describe Load Based Auto Scaling
  x-api-slug: aws-opsworks-api
  description: Describes load-based auto scaling configurations for specified layers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DescribeLoadBasedAutoScaling
  tags: Describe,Load,Based,Auto,Scaling
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondescribeloadbasedautoscaling-get-openapi.md
- name: AWS OpsWorks API Describe My User Profile
  x-api-slug: aws-opsworks-api
  description: Describes a user's SSH information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DescribeMyUserProfile
  tags: Describe,My,User,Profile
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondescribemyuserprofile-get-openapi.md
- name: AWS OpsWorks API Describe Permissions
  x-api-slug: aws-opsworks-api
  description: Describes the permissions for a specified stack.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DescribePermissions
  tags: Describe,Permissions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondescribepermissions-get-openapi.md
- name: AWS OpsWorks API Describe Raid Arrays
  x-api-slug: aws-opsworks-api
  description: Describe an instance's RAID arrays.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DescribeRaidArrays
  tags: Describe,Raid,Arrays
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondescriberaidarrays-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondescriberaidarrays-get-openapi.md
- name: AWS OpsWorks API Describe Rds Db Instances
  x-api-slug: aws-opsworks-api
  description: Describes Amazon RDS instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DescribeRdsDbInstances
  tags: Describe,Rds,Db,Instances
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondescriberdsdbinstances-get-openapi.md
- name: AWS OpsWorks API Describe Service Errors
  x-api-slug: aws-opsworks-api
  description: Describes AWS OpsWorks Stacks service errors.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DescribeServiceErrors
  tags: Describe,Service,Errors
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondescribeserviceerrors-get-openapi.md
- name: AWS OpsWorks API Describe Stack Provisioning Parameters
  x-api-slug: aws-opsworks-api
  description: Requests a description of a stack's provisioning parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DescribeStackProvisioningParameters
  tags: Describe,Stack,Provisioning,Parameters
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondescribestackprovisioningparameters-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondescribestackprovisioningparameters-get-openapi.md
- name: AWS OpsWorks API Describe Stacks
  x-api-slug: aws-opsworks-api
  description: Requests a description of one or more stacks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DescribeStacks
  tags: Describe,Stacks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondescribestacks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondescribestacks-get-openapi.md
- name: AWS OpsWorks API Describe Stack Summary
  x-api-slug: aws-opsworks-api
  description: |-
    Describes the number of layers and apps in a specified stack, and the number of instances in
          each state, such as running_setup or online.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DescribeStackSummary
  tags: Describe,Stack,Summary
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondescribestacksummary-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondescribestacksummary-get-openapi.md
- name: AWS OpsWorks API Describe Time Based Auto Scaling
  x-api-slug: aws-opsworks-api
  description: Describes time-based auto scaling configurations for specified instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DescribeTimeBasedAutoScaling
  tags: Describe,Time,Based,Auto,Scaling
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondescribetimebasedautoscaling-get-openapi.md
- name: AWS OpsWorks API Describe User Profiles
  x-api-slug: aws-opsworks-api
  description: Describe specified users.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DescribeUserProfiles
  tags: Describe,User,Profiles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondescribeuserprofiles-get-openapi.md
- name: AWS OpsWorks API Describe Volumes
  x-api-slug: aws-opsworks-api
  description: Describes an instance's Amazon EBS volumes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DescribeVolumes
  tags: Describe,Volumes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondescribevolumes-get-openapi.md
- name: AWS OpsWorks API Detach Elastic Load Balancer
  x-api-slug: aws-opsworks-api
  description: Detaches a specified Elastic Load Balancing instance from its layer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DetachElasticLoadBalancer
  tags: Detach,Elastic,Load,Balancer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondetachelasticloadbalancer-get-openapi.md
- name: AWS OpsWorks API Disassociate Elastic Ip
  x-api-slug: aws-opsworks-api
  description: Disassociates an Elastic IP address from its instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=DisassociateElasticIp
  tags: Disassociate,Elastic,Ip
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiondisassociateelasticip-get-openapi.md
- name: AWS OpsWorks API Get Hostname Suggestion
  x-api-slug: aws-opsworks-api
  description: Gets a generated host name for the specified layer, based on the current
    host name theme.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=GetHostnameSuggestion
  tags: Hostname,Suggestion
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiongethostnamesuggestion-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiongethostnamesuggestion-get-openapi.md
- name: AWS OpsWorks API Grant Access
  x-api-slug: aws-opsworks-api
  description: NoteThis action can be used only with Windows stacks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=GrantAccess
  tags: Grant,Access
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiongrantaccess-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actiongrantaccess-get-openapi.md
- name: AWS OpsWorks API Reboot Instance
  x-api-slug: aws-opsworks-api
  description: Reboots a specified instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=RebootInstance
  tags: Reboot,Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionrebootinstance-get-openapi.md
- name: AWS OpsWorks API Register Ecs Cluster
  x-api-slug: aws-opsworks-api
  description: Registers a specified Amazon ECS cluster with a stack.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=RegisterEcsCluster
  tags: Register,Ecs,Cluster
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionregisterecscluster-get-openapi.md
- name: AWS OpsWorks API Register Elastic Ip
  x-api-slug: aws-opsworks-api
  description: Registers an Elastic IP address with a specified stack.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=RegisterElasticIp
  tags: Register,Elastic,Ip
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionregisterelasticip-get-openapi.md
- name: AWS OpsWorks API Register Instance
  x-api-slug: aws-opsworks-api
  description: Registers instances that were created outside of AWS OpsWorks Stacks
    with a specified stack.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=RegisterInstance
  tags: Register,Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionregisterinstance-get-openapi.md
- name: AWS OpsWorks API Register Rds Db Instance
  x-api-slug: aws-opsworks-api
  description: Registers an Amazon RDS instance with a stack.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=RegisterRdsDbInstance
  tags: Register,Rds,Db,Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionregisterrdsdbinstance-get-openapi.md
- name: AWS OpsWorks API Register Volume
  x-api-slug: aws-opsworks-api
  description: Registers an Amazon EBS volume with a specified stack.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=RegisterVolume
  tags: Register,Volume
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionregistervolume-get-openapi.md
- name: AWS OpsWorks API Set Load Based Auto Scaling
  x-api-slug: aws-opsworks-api
  description: Specify the load-based auto scaling configuration for a specified layer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=SetLoadBasedAutoScaling
  tags: Set,Load,Based,Auto,Scaling
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionsetloadbasedautoscaling-get-openapi.md
- name: AWS OpsWorks API Set Permission
  x-api-slug: aws-opsworks-api
  description: Specifies a user's permissions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=SetPermission
  tags: Set,Permission
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionsetpermission-get-openapi.md
- name: AWS OpsWorks API Set Time Based Auto Scaling
  x-api-slug: aws-opsworks-api
  description: Specify the time-based auto scaling configuration for a specified instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=SetTimeBasedAutoScaling
  tags: Set,Time,Based,Auto,Scaling
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionsettimebasedautoscaling-get-openapi.md
- name: AWS OpsWorks API Start Instance
  x-api-slug: aws-opsworks-api
  description: Starts a specified instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=StartInstance
  tags: Start,Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionstartinstance-get-openapi.md
- name: AWS OpsWorks API Start Stack
  x-api-slug: aws-opsworks-api
  description: Starts a stack's instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=StartStack
  tags: Start,Stack
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionstartstack-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionstartstack-get-openapi.md
- name: AWS OpsWorks API Stop Instance
  x-api-slug: aws-opsworks-api
  description: Stops a specified instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=StopInstance
  tags: Stop,Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionstopinstance-get-openapi.md
- name: AWS OpsWorks API Stop Stack
  x-api-slug: aws-opsworks-api
  description: Stops a specified stack.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=StopStack
  tags: Stop,Stack
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionstopstack-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionstopstack-get-openapi.md
- name: AWS OpsWorks API Unassign Instance
  x-api-slug: aws-opsworks-api
  description: Unassigns a registered instance from all of it's layers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=UnassignInstance
  tags: Unassign,Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionunassigninstance-get-openapi.md
- name: AWS OpsWorks API Unassign Volume
  x-api-slug: aws-opsworks-api
  description: Unassigns an assigned Amazon EBS volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=UnassignVolume
  tags: Unassign,Volume
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionunassignvolume-get-openapi.md
- name: AWS OpsWorks API Update App
  x-api-slug: aws-opsworks-api
  description: Updates a specified app.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=UpdateApp
  tags: App
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionupdateapp-get-openapi.md
- name: AWS OpsWorks API Update Elastic Ip
  x-api-slug: aws-opsworks-api
  description: Updates a registered Elastic IP address's name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=UpdateElasticIp
  tags: Elastic,Ip
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionupdateelasticip-get-openapi.md
- name: AWS OpsWorks API Update Instance
  x-api-slug: aws-opsworks-api
  description: Updates a specified instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=UpdateInstance
  tags: Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionupdateinstance-get-openapi.md
- name: AWS OpsWorks API Update Layer
  x-api-slug: aws-opsworks-api
  description: Updates a specified layer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=UpdateLayer
  tags: Layer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionupdatelayer-get-openapi.md
- name: AWS OpsWorks API Update My User Profile
  x-api-slug: aws-opsworks-api
  description: Updates a user's SSH public key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=UpdateMyUserProfile
  tags: My,User,Profile
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionupdatemyuserprofile-get-openapi.md
- name: AWS OpsWorks API Update Rds Db Instance
  x-api-slug: aws-opsworks-api
  description: Updates an Amazon RDS instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=UpdateRdsDbInstance
  tags: Rds,Db,Instance
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionupdaterdsdbinstance-get-openapi.md
- name: AWS OpsWorks API Update Stack
  x-api-slug: aws-opsworks-api
  description: Updates a specified stack.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=UpdateStack
  tags: Stack
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionupdatestack-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionupdatestack-get-openapi.md
- name: AWS OpsWorks API Update User Profile
  x-api-slug: aws-opsworks-api
  description: Updates a specified user profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=UpdateUserProfile
  tags: User,Profile
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionupdateuserprofile-get-openapi.md
- name: AWS OpsWorks API Update Volume
  x-api-slug: aws-opsworks-api
  description: Updates an Amazon EBS volume's name or mount point.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: ://///?Action=UpdateVolume
  tags: Volume
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/actionupdatevolume-get-openapi.md
- name: AWS OpsWorks API
  x-api-slug: aws-opsworks-api
  description: AWS OpsWorks is a configuration management service that uses Chef,
    an automation platform that treats server configurations as code. OpsWorks uses
    Chef to automate how servers are configured, deployed, and managed across your
    Amazon Elastic Compute Cloud (Amazon EC2) instances or on-premises compute environments.
    OpsWorks has two offerings, AWS Opsworks for Chef Automate, and AWS OpsWorks Stacks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSOpsWorks.png
  humanURL: https://aws.amazon.com/opsworks/
  baseURL: :///
  tags: AWS OpsWorks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-opsworks/master/_listings/aws-opsworks/openapi.md
x-common:
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/userguide/cli-chap-welcome.html
- type: x-documentation
  url: http://docs.aws.amazon.com/opsworks/latest/APIReference/Welcome.html
- type: x-website
  url: https://aws.amazon.com/opsworks/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---