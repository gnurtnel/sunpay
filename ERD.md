       

### <a id="documentation-body"></a>

![Hackolade image](/erd/image1.png?raw=true)

MongoDB Physical Model
----------------------

#### Schema for:

Model name: New Model

Author:

Version:

File name:

File path:

Printed On: Tue Jan 19 2021 14:20:31 GMT+0700 (Indochina Time)

Created with: [Hackolade](https://hackolade.com/) - Visual data modeling for NoSQL and multimodel databases

### <a id="contents"></a>

*   [1. Model](#model)
*   [2. Databases](#containers)
    *   [2.1 sunpay](#5eb3bee0-5a25-11eb-a046-d590fdb8e2e4)
        
        [2.1.2. Collections](#5eb3bee0-5a25-11eb-a046-d590fdb8e2e4-children)
        
        [2.1.2.1 customer](#5e015ed0-5a25-11eb-a046-d590fdb8e2e4)
        
        [2.1.2.2 news](#5e024930-5a25-11eb-a046-d590fdb8e2e4)
        
        [2.1.2.3 notification](#5e029751-5a25-11eb-a046-d590fdb8e2e4)
        
        [2.1.2.4 order](#5e033391-5a25-11eb-a046-d590fdb8e2e4)
        
        [2.1.2.5 promotion](#5e03a8c0-5a25-11eb-a046-d590fdb8e2e4)
        
        [2.1.2.6 push_token](#5e03f6e3-5a25-11eb-a046-d590fdb8e2e4)
        
        [2.1.2.7 store](#5e044501-5a25-11eb-a046-d590fdb8e2e4)
        
        [2.1.2.8 system_setting](#5e049321-5a25-11eb-a046-d590fdb8e2e4)
        
        [2.1.2.9 transaction](#5e04e140-5a25-11eb-a046-d590fdb8e2e4)
        
        [2.1.2.10 vendor](#5e052f61-5a25-11eb-a046-d590fdb8e2e4)
        
        [2.1.2.11 vendor_contract](#5e05cba1-5a25-11eb-a046-d590fdb8e2e4)
        

### <a id="model"></a>

##### 1\. Model

##### 1.1 Model **New Model**

##### 1.1.1 **New Model** Entity Relationship Diagram

![Hackolade image](/erd/image2.png?raw=true)

##### 1.1.2 **New Model** Properties

##### 1.1.2.1 **Details** tab

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td><span>Model name</span></td><td>New Model</td></tr><tr><td><span>Technical name</span></td><td></td></tr><tr><td><span>Description</span></td><td><div class="docs-markdown"></div></td></tr><tr><td><span>Author</span></td><td></td></tr><tr><td><span>Version</span></td><td></td></tr><tr><td><span>DB vendor</span></td><td>MongoDB</td></tr><tr><td><span>DB version</span></td><td>v4.0</td></tr><tr><td><span>Comments</span></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.3 **New Model** DB Definitions

### <a id="containers"></a>

##### 2\. Databases

### <a id="5eb3bee0-5a25-11eb-a046-d590fdb8e2e4"></a>2.1 Database **sunpay**

![Hackolade image](/erd/image3.png?raw=true)

##### 2.1.1 **sunpay** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Database name</td><td>sunpay</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Enable sharding</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5eb3bee0-5a25-11eb-a046-d590fdb8e2e4-children"></a>2.1.2 **sunpay** Collections

### <a id="5e015ed0-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.1 Collection **customer**

##### 2.1.2.1.1 **customer** Tree Diagram

![Hackolade image](/erd/image4.png?raw=true)

##### 2.1.2.1.2 **customer** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Collection name</td><td>customer</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Database</td><td><a href=#5eb3bee0-5a25-11eb-a046-d590fdb8e2e4>sunpay</a></td></tr><tr><td>Capped</td><td></td></tr><tr><td>Size</td><td></td></tr><tr><td>Max</td><td></td></tr><tr><td>Storage engine</td><td>WiredTiger</td></tr><tr><td>Config String</td><td></td></tr><tr><td>Validation level</td><td>Off</td></tr><tr><td>Validation action</td><td>Warn</td></tr><tr><td>Additional properties</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.1.3 **customer** Fields

<table><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5dfcf200-5a25-11eb-a046-d590fdb8e2e4>_id</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd1913-5a25-11eb-a046-d590fdb8e2e4>created_at</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd191a-5a25-11eb-a046-d590fdb8e2e4>updated_at</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd1917-5a25-11eb-a046-d590fdb8e2e4>name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd1914-5a25-11eb-a046-d590fdb8e2e4>email</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd1911-5a25-11eb-a046-d590fdb8e2e4>avatar</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd1918-5a25-11eb-a046-d590fdb8e2e4>phone</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd191b-5a25-11eb-a046-d590fdb8e2e4>verified</a></td><td class="no-break-word">boolean</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd1910-5a25-11eb-a046-d590fdb8e2e4>accrue_point</a></td><td class="no-break-word">integer32</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd1912-5a25-11eb-a046-d590fdb8e2e4>balance</a></td><td class="no-break-word">integer32</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd1915-5a25-11eb-a046-d590fdb8e2e4>fname</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd1916-5a25-11eb-a046-d590fdb8e2e4>lname</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd1919-5a25-11eb-a046-d590fdb8e2e4>uid</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfcf200-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.1.3.1 Field **\_id**

##### 2.1.2.1.3.1.1 **\_id** Tree Diagram

![Hackolade image](/erd/image5.png?raw=true)

##### 2.1.2.1.3.1.2 **\_id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>_id</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>i5T5vunW1iIpTec4AlG8</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd1913-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.1.3.2 Field **created\_at**

##### 2.1.2.1.3.2.1 **created\_at** Tree Diagram

![Hackolade image](/erd/image6.png?raw=true)

##### 2.1.2.1.3.2.2 **created\_at** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>created_at</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>1609258718</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd191a-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.1.3.3 Field **updated\_at**

##### 2.1.2.1.3.3.1 **updated\_at** Tree Diagram

![Hackolade image](/erd/image7.png?raw=true)

##### 2.1.2.1.3.3.2 **updated\_at** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>updated_at</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>1611023036</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd1917-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.1.3.4 Field **name**

##### 2.1.2.1.3.4.1 **name** Tree Diagram

![Hackolade image](/erd/image8.png?raw=true)

##### 2.1.2.1.3.4.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>TonyPhong</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd1914-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.1.3.5 Field **email**

##### 2.1.2.1.3.5.1 **email** Tree Diagram

![Hackolade image](/erd/image9.png?raw=true)

##### 2.1.2.1.3.5.2 **email** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>email</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>sunwon.vn@gmail.com</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd1911-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.1.3.6 Field **avatar**

##### 2.1.2.1.3.6.1 **avatar** Tree Diagram

![Hackolade image](/erd/image10.png?raw=true)

##### 2.1.2.1.3.6.2 **avatar** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>avatar</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd1918-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.1.3.7 Field **phone**

##### 2.1.2.1.3.7.1 **phone** Tree Diagram

![Hackolade image](/erd/image11.png?raw=true)

##### 2.1.2.1.3.7.2 **phone** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>phone</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>+84906516688</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd191b-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.1.3.8 Field **verified**

##### 2.1.2.1.3.8.1 **verified** Tree Diagram

![Hackolade image](/erd/image12.png?raw=true)

##### 2.1.2.1.3.8.2 **verified** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>verified</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>boolean</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Sample</td><td>false</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd1910-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.1.3.9 Field **accrue\_point**

##### 2.1.2.1.3.9.1 **accrue\_point** Tree Diagram

![Hackolade image](/erd/image13.png?raw=true)

##### 2.1.2.1.3.9.2 **accrue\_point** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>accrue_point</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>false</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>0</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd1912-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.1.3.10 Field **balance**

##### 2.1.2.1.3.10.1 **balance** Tree Diagram

![Hackolade image](/erd/image14.png?raw=true)

##### 2.1.2.1.3.10.2 **balance** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>balance</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>false</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>4060000</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd1915-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.1.3.11 Field **fname**

##### 2.1.2.1.3.11.1 **fname** Tree Diagram

![Hackolade image](/erd/image15.png?raw=true)

##### 2.1.2.1.3.11.2 **fname** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>fname</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>false</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>hoang</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd1916-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.1.3.12 Field **lname**

##### 2.1.2.1.3.12.1 **lname** Tree Diagram

![Hackolade image](/erd/image16.png?raw=true)

##### 2.1.2.1.3.12.2 **lname** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>lname</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>false</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>tuan</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd1919-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.1.3.13 Field **uid**

##### 2.1.2.1.3.13.1 **uid** Tree Diagram

![Hackolade image](/erd/image17.png?raw=true)

##### 2.1.2.1.3.13.2 **uid** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>uid</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>false</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>oKusofOF9FWLjSnlS11cDTndf173</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.1.4 **customer** Indexes

<table class="index-table"><thead><tr><td class="table-property-column">Property</td><td class="table-column-property">_id_</td></tr></thead><tbody><tr><td>Name</td><td class="table-column-indexes">_id_</td></tr><tr><td>Key</td><td class="table-column-indexes">_id('ascending')</td></tr><tr><td>Hashed</td><td class="table-column-indexes"></td></tr><tr><td>Unique</td><td class="table-column-indexes"></td></tr><tr><td>Drop duplicates</td><td class="table-column-indexes"></td></tr><tr><td>Sparse</td><td class="table-column-indexes"></td></tr><tr><td>Background indexing</td><td class="table-column-indexes"></td></tr><tr><td>Partial filter exp</td><td class="table-column-indexes"></td></tr><tr><td>Expire after (seconds)</td><td class="table-column-indexes"></td></tr><tr><td>Storage engine</td><td class="table-column-indexes"></td></tr><tr><td>Comments</td><td class="table-column-indexes"></td></tr></tbody></table>

##### 2.1.2.1.5 **customer** JSON Schema

```
{
    "$schema": "http://json-schema.org/draft-04/schema#",
    "type": "object",
    "title": "customer",
    "properties": {
        "_id": {
            "type": "string"
        },
        "created_at": {
            "type": "integer"
        },
        "updated_at": {
            "type": "integer"
        },
        "name": {
            "type": "string"
        },
        "email": {
            "type": "string"
        },
        "avatar": {
            "type": "string"
        },
        "phone": {
            "type": "string"
        },
        "verified": {
            "type": "boolean"
        },
        "accrue_point": {
            "type": "integer"
        },
        "balance": {
            "type": "integer"
        },
        "fname": {
            "type": "string"
        },
        "lname": {
            "type": "string"
        },
        "uid": {
            "type": "string"
        }
    },
    "required": [
        "_id",
        "created_at",
        "updated_at",
        "name",
        "email",
        "avatar",
        "phone",
        "verified"
    ]
}
```

##### 2.1.2.1.6 **customer** JSON data

```
{
    "_id": "i5T5vunW1iIpTec4AlG8",
    "created_at": 1609258718,
    "updated_at": 1611023036,
    "name": "TonyPhong",
    "email": "sunwon.vn@gmail.com",
    "avatar": "Lorem",
    "phone": "+84906516688",
    "verified": false,
    "accrue_point": 0,
    "balance": 4060000,
    "fname": "hoang",
    "lname": "tuan",
    "uid": "oKusofOF9FWLjSnlS11cDTndf173"
}
```

##### 2.1.2.1.7 **customer** Target Script

```
use sunpay;

db.createCollection( "customer",{
    "storageEngine": {
        "wiredTiger": {}
    },
    "capped": false,
    "validator": {
        "$jsonSchema": {
            "bsonType": "object",
            "title": "customer",
            "properties": {
                "_id": {
                    "bsonType": "string"
                },
                "created_at": {
                    "bsonType": "int"
                },
                "updated_at": {
                    "bsonType": "int"
                },
                "name": {
                    "bsonType": "string"
                },
                "email": {
                    "bsonType": "string"
                },
                "avatar": {
                    "bsonType": "string"
                },
                "phone": {
                    "bsonType": "string"
                },
                "verified": {
                    "bsonType": "bool"
                },
                "accrue_point": {
                    "bsonType": "int"
                },
                "balance": {
                    "bsonType": "int"
                },
                "fname": {
                    "bsonType": "string"
                },
                "lname": {
                    "bsonType": "string"
                },
                "uid": {
                    "bsonType": "string"
                }
            },
            "required": [
                "_id",
                "created_at",
                "updated_at",
                "name",
                "email",
                "avatar",
                "phone",
                "verified"
            ]
        }
    },
    "validationLevel": "off",
    "validationAction": "warn"
});
db.customer.createIndex(
{
    "_id": 1
},
{
    "name": "_id_"
}
);

```

### <a id="5e024930-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.2 Collection **news**

##### 2.1.2.2.1 **news** Tree Diagram

![Hackolade image](/erd/image18.png?raw=true)

##### 2.1.2.2.2 **news** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Collection name</td><td>news</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Database</td><td><a href=#5eb3bee0-5a25-11eb-a046-d590fdb8e2e4>sunpay</a></td></tr><tr><td>Capped</td><td></td></tr><tr><td>Size</td><td></td></tr><tr><td>Max</td><td></td></tr><tr><td>Storage engine</td><td>WiredTiger</td></tr><tr><td>Config String</td><td></td></tr><tr><td>Validation level</td><td>Off</td></tr><tr><td>Validation action</td><td>Warn</td></tr><tr><td>Additional properties</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.2.3 **news** Fields

<table><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5dfd191c-5a25-11eb-a046-d590fdb8e2e4>_id</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd191e-5a25-11eb-a046-d590fdb8e2e4>created_at</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd1922-5a25-11eb-a046-d590fdb8e2e4>updated_at</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd1921-5a25-11eb-a046-d590fdb8e2e4>title</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd191d-5a25-11eb-a046-d590fdb8e2e4>content</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd191f-5a25-11eb-a046-d590fdb8e2e4>publish</a></td><td class="no-break-word">boolean</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd1920-5a25-11eb-a046-d590fdb8e2e4>thumb</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd1923-5a25-11eb-a046-d590fdb8e2e4>url</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd191c-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.2.3.1 Field **\_id**

##### 2.1.2.2.3.1.1 **\_id** Tree Diagram

![Hackolade image](/erd/image19.png?raw=true)

##### 2.1.2.2.3.1.2 **\_id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>_id</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>6s037Tz1ZqjzkaBWnNzU</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd191e-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.2.3.2 Field **created\_at**

##### 2.1.2.2.3.2.1 **created\_at** Tree Diagram

![Hackolade image](/erd/image20.png?raw=true)

##### 2.1.2.2.3.2.2 **created\_at** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>created_at</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>1601401000</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd1922-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.2.3.3 Field **updated\_at**

##### 2.1.2.2.3.3.1 **updated\_at** Tree Diagram

![Hackolade image](/erd/image21.png?raw=true)

##### 2.1.2.2.3.3.2 **updated\_at** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>updated_at</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>1602654850</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd1921-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.2.3.4 Field **title**

##### 2.1.2.2.3.4.1 **title** Tree Diagram

![Hackolade image](/erd/image22.png?raw=true)

##### 2.1.2.2.3.4.2 **title** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>title</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>Ghế massage 3D SG986 cao cấp. Khuyến mại shock trừ 30% vào giá</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd191d-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.2.3.5 Field **content**

##### 2.1.2.2.3.5.1 **content** Tree Diagram

![Hackolade image](/erd/image23.png?raw=true)

##### 2.1.2.2.3.5.2 **content** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>content</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>&lt;p&gt;a&lt;/p&gt;</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd191f-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.2.3.6 Field **publish**

##### 2.1.2.2.3.6.1 **publish** Tree Diagram

![Hackolade image](/erd/image24.png?raw=true)

##### 2.1.2.2.3.6.2 **publish** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>publish</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>boolean</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Sample</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd1920-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.2.3.7 Field **thumb**

##### 2.1.2.2.3.7.1 **thumb** Tree Diagram

![Hackolade image](/erd/image25.png?raw=true)

##### 2.1.2.2.3.7.2 **thumb** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>thumb</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>https://mirascan.s3-ap-southeast-1.amazonaws.com/thumb_1U1my7OJdlaliZlHRosG</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd1923-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.2.3.8 Field **url**

##### 2.1.2.2.3.8.1 **url** Tree Diagram

![Hackolade image](/erd/image26.png?raw=true)

##### 2.1.2.2.3.8.2 **url** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>url</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>false</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>https://sunwon.vn/san-pham/ghe-massage-3d-sg986-cao-cap</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.2.4 **news** Indexes

<table class="index-table"><thead><tr><td class="table-property-column">Property</td><td class="table-column-property">_id_</td></tr></thead><tbody><tr><td>Name</td><td class="table-column-indexes">_id_</td></tr><tr><td>Key</td><td class="table-column-indexes">_id('ascending')</td></tr><tr><td>Hashed</td><td class="table-column-indexes"></td></tr><tr><td>Unique</td><td class="table-column-indexes"></td></tr><tr><td>Drop duplicates</td><td class="table-column-indexes"></td></tr><tr><td>Sparse</td><td class="table-column-indexes"></td></tr><tr><td>Background indexing</td><td class="table-column-indexes"></td></tr><tr><td>Partial filter exp</td><td class="table-column-indexes"></td></tr><tr><td>Expire after (seconds)</td><td class="table-column-indexes"></td></tr><tr><td>Storage engine</td><td class="table-column-indexes"></td></tr><tr><td>Comments</td><td class="table-column-indexes"></td></tr></tbody></table>

##### 2.1.2.2.5 **news** JSON Schema

```
{
    "$schema": "http://json-schema.org/draft-04/schema#",
    "type": "object",
    "title": "news",
    "properties": {
        "_id": {
            "type": "string"
        },
        "created_at": {
            "type": "integer"
        },
        "updated_at": {
            "type": "integer"
        },
        "title": {
            "type": "string"
        },
        "content": {
            "type": "string"
        },
        "publish": {
            "type": "boolean"
        },
        "thumb": {
            "type": "string"
        },
        "url": {
            "type": "string"
        }
    },
    "required": [
        "_id",
        "created_at",
        "updated_at",
        "title",
        "content",
        "publish",
        "thumb"
    ]
}
```

##### 2.1.2.2.6 **news** JSON data

```
{
    "_id": "6s037Tz1ZqjzkaBWnNzU",
    "created_at": 1601401000,
    "updated_at": 1602654850,
    "title": "Ghế massage 3D SG986 cao cấp. Khuyến mại shock trừ 30% vào giá",
    "content": "<p>a</p>",
    "publish": true,
    "thumb": "https://mirascan.s3-ap-southeast-1.amazonaws.com/thumb_1U1my7OJdlaliZlHRosG",
    "url": "https://sunwon.vn/san-pham/ghe-massage-3d-sg986-cao-cap"
}
```

##### 2.1.2.2.7 **news** Target Script

```
use sunpay;

db.createCollection( "news",{
    "storageEngine": {
        "wiredTiger": {}
    },
    "capped": false,
    "validator": {
        "$jsonSchema": {
            "bsonType": "object",
            "title": "news",
            "properties": {
                "_id": {
                    "bsonType": "string"
                },
                "created_at": {
                    "bsonType": "int"
                },
                "updated_at": {
                    "bsonType": "int"
                },
                "title": {
                    "bsonType": "string"
                },
                "content": {
                    "bsonType": "string"
                },
                "publish": {
                    "bsonType": "bool"
                },
                "thumb": {
                    "bsonType": "string"
                },
                "url": {
                    "bsonType": "string"
                }
            },
            "required": [
                "_id",
                "created_at",
                "updated_at",
                "title",
                "content",
                "publish",
                "thumb"
            ]
        }
    },
    "validationLevel": "off",
    "validationAction": "warn"
});
db.news.createIndex(
{
    "_id": 1
},
{
    "name": "_id_"
}
);

```

### <a id="5e029751-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.3 Collection **notification**

##### 2.1.2.3.1 **notification** Tree Diagram

![Hackolade image](/erd/image27.png?raw=true)

##### 2.1.2.3.2 **notification** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Collection name</td><td>notification</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Database</td><td><a href=#5eb3bee0-5a25-11eb-a046-d590fdb8e2e4>sunpay</a></td></tr><tr><td>Capped</td><td></td></tr><tr><td>Size</td><td></td></tr><tr><td>Max</td><td></td></tr><tr><td>Storage engine</td><td>WiredTiger</td></tr><tr><td>Config String</td><td></td></tr><tr><td>Validation level</td><td>Off</td></tr><tr><td>Validation action</td><td>Warn</td></tr><tr><td>Additional properties</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3 **notification** Fields

<table><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5dfd4020-5a25-11eb-a046-d590fdb8e2e4>_id</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd4022-5a25-11eb-a046-d590fdb8e2e4>created_at</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd402b-5a25-11eb-a046-d590fdb8e2e4>updated_at</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd4026-5a25-11eb-a046-d590fdb8e2e4>type</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd4025-5a25-11eb-a046-d590fdb8e2e4>title</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd4021-5a25-11eb-a046-d590fdb8e2e4>content</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd402c-5a25-11eb-a046-d590fdb8e2e4>url</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd4023-5a25-11eb-a046-d590fdb8e2e4>created_by</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd4024-5a25-11eb-a046-d590fdb8e2e4>hidden_uids</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5e02be60-5a25-11eb-a046-d590fdb8e2e4>[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5e029753-5a25-11eb-a046-d590fdb8e2e4>oneOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd4027-5a25-11eb-a046-d590fdb8e2e4>[0]</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd4028-5a25-11eb-a046-d590fdb8e2e4>uid</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5e02be61-5a25-11eb-a046-d590fdb8e2e4>[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd4029-5a25-11eb-a046-d590fdb8e2e4>[1]</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd402a-5a25-11eb-a046-d590fdb8e2e4>uid</a></td><td class="no-break-word">null</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd4020-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.3.3.1 Field **\_id**

##### 2.1.2.3.3.1.1 **\_id** Tree Diagram

![Hackolade image](/erd/image28.png?raw=true)

##### 2.1.2.3.3.1.2 **\_id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>_id</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>gX850ETZE8Ez195HPDsE</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd4022-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.3.3.2 Field **created\_at**

##### 2.1.2.3.3.2.1 **created\_at** Tree Diagram

![Hackolade image](/erd/image29.png?raw=true)

##### 2.1.2.3.3.2.2 **created\_at** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>created_at</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>1609258718</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd402b-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.3.3.3 Field **updated\_at**

##### 2.1.2.3.3.3.1 **updated\_at** Tree Diagram

![Hackolade image](/erd/image30.png?raw=true)

##### 2.1.2.3.3.3.2 **updated\_at** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>updated_at</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>1609258718</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd4026-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.3.3.4 Field **type**

##### 2.1.2.3.3.4.1 **type** Tree Diagram

![Hackolade image](/erd/image31.png?raw=true)

##### 2.1.2.3.3.4.2 **type** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>type</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>private</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd4025-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.3.3.5 Field **title**

##### 2.1.2.3.3.5.1 **title** Tree Diagram

![Hackolade image](/erd/image32.png?raw=true)

##### 2.1.2.3.3.5.2 **title** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>title</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>Chào mừng TonyPhong</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd4021-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.3.3.6 Field **content**

##### 2.1.2.3.3.6.1 **content** Tree Diagram

![Hackolade image](/erd/image33.png?raw=true)

##### 2.1.2.3.3.6.2 **content** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>content</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>Cảm ơn TonyPhong đã sử dụng dịch vụ của Sunpay.. Sunwon tặng bạn 10000 để sử dụng dịch vụ của Sunwon</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd402c-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.3.3.7 Field **url**

##### 2.1.2.3.3.7.1 **url** Tree Diagram

![Hackolade image](/erd/image34.png?raw=true)

##### 2.1.2.3.3.7.2 **url** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>url</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd4023-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.3.3.8 Field **created\_by**

##### 2.1.2.3.3.8.1 **created\_by** Tree Diagram

![Hackolade image](/erd/image35.png?raw=true)

##### 2.1.2.3.3.8.2 **created\_by** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>created_by</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>system</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd4024-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.3.3.9 Field **hidden\_uids**

##### 2.1.2.3.3.9.1 **hidden\_uids** Tree Diagram

![Hackolade image](/erd/image36.png?raw=true)

##### 2.1.2.3.3.9.2 **hidden\_uids** Hierarchy

Parent field: **notification**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5e02be60-5a25-11eb-a046-d590fdb8e2e4>[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3.9.3 **hidden\_uids** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>hidden_uids</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>false</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Min items</td><td></td></tr><tr><td>Max items</td><td></td></tr><tr><td>Unique items</td><td></td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5e02be60-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.3.3.10 Field **\[0\]**

##### 2.1.2.3.3.10.1 **\[0\]** Tree Diagram

![Hackolade image](/erd/image37.png?raw=true)

##### 2.1.2.3.3.10.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Primary key</td><td></td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>LanU4BNJ50AkyLCWtQgJ</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5e029753-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.3.3.11 Field **oneOf**

##### 2.1.2.3.3.11.1 **oneOf** Tree Diagram

![Hackolade image](/erd/image38.png?raw=true)

##### 2.1.2.3.3.11.2 **oneOf** Hierarchy

Parent field: **notification**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5dfd4027-5a25-11eb-a046-d590fdb8e2e4>[0]</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd4029-5a25-11eb-a046-d590fdb8e2e4>[1]</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3.11.3 **oneOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>oneOf</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd4027-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.3.3.12 Field **\[0\]**

##### 2.1.2.3.3.12.1 **\[0\]** Tree Diagram

![Hackolade image](/erd/image39.png?raw=true)

##### 2.1.2.3.3.12.2 **\[0\]** Hierarchy

Parent field: **oneOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5dfd4028-5a25-11eb-a046-d590fdb8e2e4>uid</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3.12.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Required</td><td></td></tr><tr><td>Min Properties</td><td></td></tr><tr><td>Max Properties</td><td></td></tr><tr><td>Additional properties</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd4028-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.3.3.13 Field **uid**

##### 2.1.2.3.3.13.1 **uid** Tree Diagram

![Hackolade image](/erd/image40.png?raw=true)

##### 2.1.2.3.3.13.2 **uid** Hierarchy

Parent field: **\[0\]**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5e02be61-5a25-11eb-a046-d590fdb8e2e4>[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3.13.3 **uid** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>uid</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td></td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Min items</td><td></td></tr><tr><td>Max items</td><td></td></tr><tr><td>Unique items</td><td></td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5e02be61-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.3.3.14 Field **\[0\]**

##### 2.1.2.3.3.14.1 **\[0\]** Tree Diagram

![Hackolade image](/erd/image41.png?raw=true)

##### 2.1.2.3.3.14.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Primary key</td><td></td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd4029-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.3.3.15 Field **\[1\]**

##### 2.1.2.3.3.15.1 **\[1\]** Tree Diagram

![Hackolade image](/erd/image42.png?raw=true)

##### 2.1.2.3.3.15.2 **\[1\]** Hierarchy

Parent field: **oneOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5dfd402a-5a25-11eb-a046-d590fdb8e2e4>uid</a></td><td class="no-break-word">null</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.3.15.3 **\[1\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Required</td><td></td></tr><tr><td>Min Properties</td><td></td></tr><tr><td>Max Properties</td><td></td></tr><tr><td>Additional properties</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd402a-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.3.3.16 Field **uid**

##### 2.1.2.3.3.16.1 **uid** Tree Diagram

![Hackolade image](/erd/image43.png?raw=true)

##### 2.1.2.3.3.16.2 **uid** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>uid</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>null</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.3.4 **notification** Indexes

<table class="index-table"><thead><tr><td class="table-property-column">Property</td><td class="table-column-property">_id_</td></tr></thead><tbody><tr><td>Name</td><td class="table-column-indexes">_id_</td></tr><tr><td>Key</td><td class="table-column-indexes">_id('ascending')</td></tr><tr><td>Hashed</td><td class="table-column-indexes"></td></tr><tr><td>Unique</td><td class="table-column-indexes"></td></tr><tr><td>Drop duplicates</td><td class="table-column-indexes"></td></tr><tr><td>Sparse</td><td class="table-column-indexes"></td></tr><tr><td>Background indexing</td><td class="table-column-indexes"></td></tr><tr><td>Partial filter exp</td><td class="table-column-indexes"></td></tr><tr><td>Expire after (seconds)</td><td class="table-column-indexes"></td></tr><tr><td>Storage engine</td><td class="table-column-indexes"></td></tr><tr><td>Comments</td><td class="table-column-indexes"></td></tr></tbody></table>

##### 2.1.2.3.5 **notification** JSON Schema

```
{
    "$schema": "http://json-schema.org/draft-04/schema#",
    "type": "object",
    "title": "notification",
    "properties": {
        "_id": {
            "type": "string"
        },
        "created_at": {
            "type": "integer"
        },
        "updated_at": {
            "type": "integer"
        },
        "type": {
            "type": "string"
        },
        "title": {
            "type": "string"
        },
        "content": {
            "type": "string"
        },
        "url": {
            "type": "string"
        },
        "created_by": {
            "type": "string"
        },
        "hidden_uids": {
            "type": "array",
            "additionalItems": true,
            "items": {
                "type": "string"
            }
        }
    },
    "additionalProperties": true,
    "oneOf": [
        {
            "type": "object",
            "properties": {
                "uid": {
                    "type": "array",
                    "additionalItems": true,
                    "items": {
                        "type": "string"
                    }
                }
            },
            "additionalProperties": true
        },
        {
            "type": "object",
            "properties": {
                "uid": {
                    "type": "null"
                }
            },
            "additionalProperties": true
        }
    ],
    "required": [
        "_id",
        "created_at",
        "updated_at",
        "type",
        "title",
        "content",
        "url",
        "created_by"
    ]
}
```

##### 2.1.2.3.6 **notification** JSON data

```
{
    "_id": "gX850ETZE8Ez195HPDsE",
    "created_at": 1609258718,
    "updated_at": 1609258718,
    "type": "private",
    "title": "Chào mừng TonyPhong",
    "content": "Cảm ơn TonyPhong đã sử dụng dịch vụ của Sunpay.. Sunwon tặng bạn 10000 để sử dụng dịch vụ của Sunwon",
    "url": "Lorem",
    "created_by": "system",
    "hidden_uids": [
        "LanU4BNJ50AkyLCWtQgJ"
    ],
    "uid": [
        "Lorem"
    ]
}
```

##### 2.1.2.3.7 **notification** Target Script

```
use sunpay;

db.createCollection( "notification",{
    "storageEngine": {
        "wiredTiger": {}
    },
    "capped": false,
    "validator": {
        "$jsonSchema": {
            "bsonType": "object",
            "title": "notification",
            "properties": {
                "_id": {
                    "bsonType": "string"
                },
                "created_at": {
                    "bsonType": "int"
                },
                "updated_at": {
                    "bsonType": "int"
                },
                "type": {
                    "bsonType": "string"
                },
                "title": {
                    "bsonType": "string"
                },
                "content": {
                    "bsonType": "string"
                },
                "url": {
                    "bsonType": "string"
                },
                "created_by": {
                    "bsonType": "string"
                },
                "hidden_uids": {
                    "bsonType": "array",
                    "additionalItems": true,
                    "items": {
                        "bsonType": "string"
                    }
                }
            },
            "additionalProperties": true,
            "oneOf": [
                {
                    "bsonType": "object",
                    "properties": {
                        "uid": {
                            "bsonType": "array",
                            "additionalItems": true,
                            "items": {
                                "bsonType": "string"
                            }
                        }
                    },
                    "additionalProperties": true
                },
                {
                    "bsonType": "object",
                    "properties": {
                        "uid": {
                            "bsonType": "null"
                        }
                    },
                    "additionalProperties": true
                }
            ],
            "required": [
                "_id",
                "created_at",
                "updated_at",
                "type",
                "title",
                "content",
                "url",
                "created_by"
            ]
        }
    },
    "validationLevel": "off",
    "validationAction": "warn"
});
db.notification.createIndex(
{
    "_id": 1
},
{
    "name": "_id_"
}
);

```

### <a id="5e033391-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.4 Collection **order**

##### 2.1.2.4.1 **order** Tree Diagram

![Hackolade image](/erd/image44.png?raw=true)

##### 2.1.2.4.2 **order** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Collection name</td><td>order</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Database</td><td><a href=#5eb3bee0-5a25-11eb-a046-d590fdb8e2e4>sunpay</a></td></tr><tr><td>Capped</td><td></td></tr><tr><td>Size</td><td></td></tr><tr><td>Max</td><td></td></tr><tr><td>Storage engine</td><td>WiredTiger</td></tr><tr><td>Config String</td><td></td></tr><tr><td>Validation level</td><td>Off</td></tr><tr><td>Validation action</td><td>Warn</td></tr><tr><td>Additional properties</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.3 **order** Fields

<table><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5dfd6730-5a25-11eb-a046-d590fdb8e2e4>_id</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6732-5a25-11eb-a046-d590fdb8e2e4>created_at</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd673b-5a25-11eb-a046-d590fdb8e2e4>updated_at</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6736-5a25-11eb-a046-d590fdb8e2e4>name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6731-5a25-11eb-a046-d590fdb8e2e4>amount</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6733-5a25-11eb-a046-d590fdb8e2e4>discount_amount</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6735-5a25-11eb-a046-d590fdb8e2e4>machine_type</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6734-5a25-11eb-a046-d590fdb8e2e4>machine_id</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6737-5a25-11eb-a046-d590fdb8e2e4>promotion_id</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6738-5a25-11eb-a046-d590fdb8e2e4>ref_id</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd673a-5a25-11eb-a046-d590fdb8e2e4>uid</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6739-5a25-11eb-a046-d590fdb8e2e4>status</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6730-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.4.3.1 Field **\_id**

##### 2.1.2.4.3.1.1 **\_id** Tree Diagram

![Hackolade image](/erd/image45.png?raw=true)

##### 2.1.2.4.3.1.2 **\_id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>_id</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>MqAM1Y4dJi6MMz2P8spp</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6732-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.4.3.2 Field **created\_at**

##### 2.1.2.4.3.2.1 **created\_at** Tree Diagram

![Hackolade image](/erd/image46.png?raw=true)

##### 2.1.2.4.3.2.2 **created\_at** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>created_at</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>1604405085</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd673b-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.4.3.3 Field **updated\_at**

##### 2.1.2.4.3.3.1 **updated\_at** Tree Diagram

![Hackolade image](/erd/image47.png?raw=true)

##### 2.1.2.4.3.3.2 **updated\_at** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>updated_at</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>1604405085</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6736-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.4.3.4 Field **name**

##### 2.1.2.4.3.4.1 **name** Tree Diagram

![Hackolade image](/erd/image48.png?raw=true)

##### 2.1.2.4.3.4.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>Thanh toán máy giặt 1000 VNĐ</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6731-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.4.3.5 Field **amount**

##### 2.1.2.4.3.5.1 **amount** Tree Diagram

![Hackolade image](/erd/image49.png?raw=true)

##### 2.1.2.4.3.5.2 **amount** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>amount</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>10000</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6733-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.4.3.6 Field **discount\_amount**

##### 2.1.2.4.3.6.1 **discount\_amount** Tree Diagram

![Hackolade image](/erd/image50.png?raw=true)

##### 2.1.2.4.3.6.2 **discount\_amount** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>discount_amount</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>0</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6735-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.4.3.7 Field **machine\_type**

##### 2.1.2.4.3.7.1 **machine\_type** Tree Diagram

![Hackolade image](/erd/image51.png?raw=true)

##### 2.1.2.4.3.7.2 **machine\_type** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>machine_type</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>wsc</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6734-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.4.3.8 Field **machine\_id**

##### 2.1.2.4.3.8.1 **machine\_id** Tree Diagram

![Hackolade image](/erd/image52.png?raw=true)

##### 2.1.2.4.3.8.2 **machine\_id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>machine_id</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>VPHCMsay</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6737-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.4.3.9 Field **promotion\_id**

##### 2.1.2.4.3.9.1 **promotion\_id** Tree Diagram

![Hackolade image](/erd/image53.png?raw=true)

##### 2.1.2.4.3.9.2 **promotion\_id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>promotion_id</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6738-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.4.3.10 Field **ref\_id**

##### 2.1.2.4.3.10.1 **ref\_id** Tree Diagram

![Hackolade image](/erd/image54.png?raw=true)

##### 2.1.2.4.3.10.2 **ref\_id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>ref_id</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd673a-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.4.3.11 Field **uid**

##### 2.1.2.4.3.11.1 **uid** Tree Diagram

![Hackolade image](/erd/image55.png?raw=true)

##### 2.1.2.4.3.11.2 **uid** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>uid</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>Ewxz12GcGJaiTN3OojIias33M4u2</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6739-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.4.3.12 Field **status**

##### 2.1.2.4.3.12.1 **status** Tree Diagram

![Hackolade image](/erd/image56.png?raw=true)

##### 2.1.2.4.3.12.2 **status** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>status</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.4.4 **order** Indexes

<table class="index-table"><thead><tr><td class="table-property-column">Property</td><td class="table-column-property">_id_</td></tr></thead><tbody><tr><td>Name</td><td class="table-column-indexes">_id_</td></tr><tr><td>Key</td><td class="table-column-indexes">_id('ascending')</td></tr><tr><td>Hashed</td><td class="table-column-indexes"></td></tr><tr><td>Unique</td><td class="table-column-indexes"></td></tr><tr><td>Drop duplicates</td><td class="table-column-indexes"></td></tr><tr><td>Sparse</td><td class="table-column-indexes"></td></tr><tr><td>Background indexing</td><td class="table-column-indexes"></td></tr><tr><td>Partial filter exp</td><td class="table-column-indexes"></td></tr><tr><td>Expire after (seconds)</td><td class="table-column-indexes"></td></tr><tr><td>Storage engine</td><td class="table-column-indexes"></td></tr><tr><td>Comments</td><td class="table-column-indexes"></td></tr></tbody></table>

##### 2.1.2.4.5 **order** JSON Schema

```
{
    "$schema": "http://json-schema.org/draft-04/schema#",
    "type": "object",
    "title": "order",
    "properties": {
        "_id": {
            "type": "string"
        },
        "created_at": {
            "type": "integer"
        },
        "updated_at": {
            "type": "integer"
        },
        "name": {
            "type": "string"
        },
        "amount": {
            "type": "integer"
        },
        "discount_amount": {
            "type": "integer"
        },
        "machine_type": {
            "type": "string"
        },
        "machine_id": {
            "type": "string"
        },
        "promotion_id": {
            "type": "string"
        },
        "ref_id": {
            "type": "string"
        },
        "uid": {
            "type": "string"
        },
        "status": {
            "type": "string"
        }
    },
    "required": [
        "_id",
        "created_at",
        "updated_at",
        "name",
        "amount",
        "discount_amount",
        "machine_type",
        "machine_id",
        "promotion_id",
        "ref_id",
        "uid",
        "status"
    ]
}
```

##### 2.1.2.4.6 **order** JSON data

```
{
    "_id": "MqAM1Y4dJi6MMz2P8spp",
    "created_at": 1604405085,
    "updated_at": 1604405085,
    "name": "Thanh toán máy giặt 1000 VNĐ",
    "amount": 10000,
    "discount_amount": 0,
    "machine_type": "wsc",
    "machine_id": "VPHCMsay",
    "promotion_id": "Lorem",
    "ref_id": "Lorem",
    "uid": "Ewxz12GcGJaiTN3OojIias33M4u2",
    "status": "Lorem"
}
```

##### 2.1.2.4.7 **order** Target Script

```
use sunpay;

db.createCollection( "order",{
    "storageEngine": {
        "wiredTiger": {}
    },
    "capped": false,
    "validator": {
        "$jsonSchema": {
            "bsonType": "object",
            "title": "order",
            "properties": {
                "_id": {
                    "bsonType": "string"
                },
                "created_at": {
                    "bsonType": "int"
                },
                "updated_at": {
                    "bsonType": "int"
                },
                "name": {
                    "bsonType": "string"
                },
                "amount": {
                    "bsonType": "int"
                },
                "discount_amount": {
                    "bsonType": "int"
                },
                "machine_type": {
                    "bsonType": "string"
                },
                "machine_id": {
                    "bsonType": "string"
                },
                "promotion_id": {
                    "bsonType": "string"
                },
                "ref_id": {
                    "bsonType": "string"
                },
                "uid": {
                    "bsonType": "string"
                },
                "status": {
                    "bsonType": "string"
                }
            },
            "required": [
                "_id",
                "created_at",
                "updated_at",
                "name",
                "amount",
                "discount_amount",
                "machine_type",
                "machine_id",
                "promotion_id",
                "ref_id",
                "uid",
                "status"
            ]
        }
    },
    "validationLevel": "off",
    "validationAction": "warn"
});
db.order.createIndex(
{
    "_id": 1
},
{
    "name": "_id_"
}
);

```

### <a id="5e03a8c0-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.5 Collection **promotion**

##### 2.1.2.5.1 **promotion** Tree Diagram

![Hackolade image](/erd/image57.png?raw=true)

##### 2.1.2.5.2 **promotion** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Collection name</td><td>promotion</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Database</td><td><a href=#5eb3bee0-5a25-11eb-a046-d590fdb8e2e4>sunpay</a></td></tr><tr><td>Capped</td><td></td></tr><tr><td>Size</td><td></td></tr><tr><td>Max</td><td></td></tr><tr><td>Storage engine</td><td>WiredTiger</td></tr><tr><td>Config String</td><td></td></tr><tr><td>Validation level</td><td>Off</td></tr><tr><td>Validation action</td><td>Warn</td></tr><tr><td>Additional properties</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3 **promotion** Fields

<table><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5dfd673c-5a25-11eb-a046-d590fdb8e2e4>_id</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6740-5a25-11eb-a046-d590fdb8e2e4>created_at</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd674a-5a25-11eb-a046-d590fdb8e2e4>updated_at</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6749-5a25-11eb-a046-d590fdb8e2e4>title</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd673f-5a25-11eb-a046-d590fdb8e2e4>content</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd673e-5a25-11eb-a046-d590fdb8e2e4>code</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd673d-5a25-11eb-a046-d590fdb8e2e4>amount</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6747-5a25-11eb-a046-d590fdb8e2e4>percent</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6742-5a25-11eb-a046-d590fdb8e2e4>machine_types</a></td><td class="no-break-word">array</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5e03a8c3-5a25-11eb-a046-d590fdb8e2e4>[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6748-5a25-11eb-a046-d590fdb8e2e4>start_at</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6741-5a25-11eb-a046-d590fdb8e2e4>end_at</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5e03a8c2-5a25-11eb-a046-d590fdb8e2e4>oneOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6743-5a25-11eb-a046-d590fdb8e2e4>[0]</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6744-5a25-11eb-a046-d590fdb8e2e4>machines</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6745-5a25-11eb-a046-d590fdb8e2e4>[1]</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6746-5a25-11eb-a046-d590fdb8e2e4>machines</a></td><td class="no-break-word">null</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd673c-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.5.3.1 Field **\_id**

##### 2.1.2.5.3.1.1 **\_id** Tree Diagram

![Hackolade image](/erd/image58.png?raw=true)

##### 2.1.2.5.3.1.2 **\_id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>_id</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>FXp6kX3BDDmt3BZI5KWy</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6740-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.5.3.2 Field **created\_at**

##### 2.1.2.5.3.2.1 **created\_at** Tree Diagram

![Hackolade image](/erd/image59.png?raw=true)

##### 2.1.2.5.3.2.2 **created\_at** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>created_at</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>1601313323</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd674a-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.5.3.3 Field **updated\_at**

##### 2.1.2.5.3.3.1 **updated\_at** Tree Diagram

![Hackolade image](/erd/image60.png?raw=true)

##### 2.1.2.5.3.3.2 **updated\_at** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>updated_at</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>1601313024</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6749-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.5.3.4 Field **title**

##### 2.1.2.5.3.4.1 **title** Tree Diagram

![Hackolade image](/erd/image61.png?raw=true)

##### 2.1.2.5.3.4.2 **title** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>title</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>3123 3123 123 12</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd673f-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.5.3.5 Field **content**

##### 2.1.2.5.3.5.1 **content** Tree Diagram

![Hackolade image](/erd/image62.png?raw=true)

##### 2.1.2.5.3.5.2 **content** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>content</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>123</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd673e-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.5.3.6 Field **code**

##### 2.1.2.5.3.6.1 **code** Tree Diagram

![Hackolade image](/erd/image63.png?raw=true)

##### 2.1.2.5.3.6.2 **code** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>code</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>1233 123 12</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd673d-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.5.3.7 Field **amount**

##### 2.1.2.5.3.7.1 **amount** Tree Diagram

![Hackolade image](/erd/image64.png?raw=true)

##### 2.1.2.5.3.7.2 **amount** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>amount</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>312331231</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6747-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.5.3.8 Field **percent**

##### 2.1.2.5.3.8.1 **percent** Tree Diagram

![Hackolade image](/erd/image65.png?raw=true)

##### 2.1.2.5.3.8.2 **percent** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>percent</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>123</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6742-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.5.3.9 Field **machine\_types**

##### 2.1.2.5.3.9.1 **machine\_types** Tree Diagram

![Hackolade image](/erd/image66.png?raw=true)

##### 2.1.2.5.3.9.2 **machine\_types** Hierarchy

Parent field: **promotion**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5e03a8c3-5a25-11eb-a046-d590fdb8e2e4>[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.9.3 **machine\_types** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>machine_types</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Min items</td><td></td></tr><tr><td>Max items</td><td></td></tr><tr><td>Unique items</td><td></td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5e03a8c3-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.5.3.10 Field **\[0\]**

##### 2.1.2.5.3.10.1 **\[0\]** Tree Diagram

![Hackolade image](/erd/image67.png?raw=true)

##### 2.1.2.5.3.10.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Primary key</td><td></td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>msc</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6748-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.5.3.11 Field **start\_at**

##### 2.1.2.5.3.11.1 **start\_at** Tree Diagram

![Hackolade image](/erd/image68.png?raw=true)

##### 2.1.2.5.3.11.2 **start\_at** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>start_at</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>1601312400</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6741-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.5.3.12 Field **end\_at**

##### 2.1.2.5.3.12.1 **end\_at** Tree Diagram

![Hackolade image](/erd/image69.png?raw=true)

##### 2.1.2.5.3.12.2 **end\_at** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>end_at</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>1604025502</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5e03a8c2-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.5.3.13 Field **oneOf**

##### 2.1.2.5.3.13.1 **oneOf** Tree Diagram

![Hackolade image](/erd/image70.png?raw=true)

##### 2.1.2.5.3.13.2 **oneOf** Hierarchy

Parent field: **promotion**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5dfd6743-5a25-11eb-a046-d590fdb8e2e4>[0]</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6745-5a25-11eb-a046-d590fdb8e2e4>[1]</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.13.3 **oneOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>oneOf</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6743-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.5.3.14 Field **\[0\]**

##### 2.1.2.5.3.14.1 **\[0\]** Tree Diagram

![Hackolade image](/erd/image71.png?raw=true)

##### 2.1.2.5.3.14.2 **\[0\]** Hierarchy

Parent field: **oneOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5dfd6744-5a25-11eb-a046-d590fdb8e2e4>machines</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.14.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Required</td><td></td></tr><tr><td>Min Properties</td><td></td></tr><tr><td>Max Properties</td><td></td></tr><tr><td>Additional properties</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6744-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.5.3.15 Field **machines**

##### 2.1.2.5.3.15.1 **machines** Tree Diagram

![Hackolade image](/erd/image72.png?raw=true)

##### 2.1.2.5.3.15.2 **machines** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>machines</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td></td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Min items</td><td></td></tr><tr><td>Max items</td><td></td></tr><tr><td>Unique items</td><td></td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6745-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.5.3.16 Field **\[1\]**

##### 2.1.2.5.3.16.1 **\[1\]** Tree Diagram

![Hackolade image](/erd/image73.png?raw=true)

##### 2.1.2.5.3.16.2 **\[1\]** Hierarchy

Parent field: **oneOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5dfd6746-5a25-11eb-a046-d590fdb8e2e4>machines</a></td><td class="no-break-word">null</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.3.16.3 **\[1\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Required</td><td></td></tr><tr><td>Min Properties</td><td></td></tr><tr><td>Max Properties</td><td></td></tr><tr><td>Additional properties</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6746-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.5.3.17 Field **machines**

##### 2.1.2.5.3.17.1 **machines** Tree Diagram

![Hackolade image](/erd/image74.png?raw=true)

##### 2.1.2.5.3.17.2 **machines** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>machines</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>null</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.5.4 **promotion** Indexes

<table class="index-table"><thead><tr><td class="table-property-column">Property</td><td class="table-column-property">_id_</td></tr></thead><tbody><tr><td>Name</td><td class="table-column-indexes">_id_</td></tr><tr><td>Key</td><td class="table-column-indexes">_id('ascending')</td></tr><tr><td>Hashed</td><td class="table-column-indexes"></td></tr><tr><td>Unique</td><td class="table-column-indexes"></td></tr><tr><td>Drop duplicates</td><td class="table-column-indexes"></td></tr><tr><td>Sparse</td><td class="table-column-indexes"></td></tr><tr><td>Background indexing</td><td class="table-column-indexes"></td></tr><tr><td>Partial filter exp</td><td class="table-column-indexes"></td></tr><tr><td>Expire after (seconds)</td><td class="table-column-indexes"></td></tr><tr><td>Storage engine</td><td class="table-column-indexes"></td></tr><tr><td>Comments</td><td class="table-column-indexes"></td></tr></tbody></table>

##### 2.1.2.5.5 **promotion** JSON Schema

```
{
    "$schema": "http://json-schema.org/draft-04/schema#",
    "type": "object",
    "title": "promotion",
    "properties": {
        "_id": {
            "type": "string"
        },
        "created_at": {
            "type": "integer"
        },
        "updated_at": {
            "type": "integer"
        },
        "title": {
            "type": "string"
        },
        "content": {
            "type": "string"
        },
        "code": {
            "type": "string"
        },
        "amount": {
            "type": "integer"
        },
        "percent": {
            "type": "integer"
        },
        "machine_types": {
            "type": "array",
            "additionalItems": true,
            "items": {
                "type": "string"
            }
        },
        "start_at": {
            "type": "integer"
        },
        "end_at": {
            "type": "integer"
        }
    },
    "additionalProperties": true,
    "oneOf": [
        {
            "type": "object",
            "properties": {
                "machines": {
                    "type": "array",
                    "additionalItems": true
                }
            },
            "additionalProperties": true
        },
        {
            "type": "object",
            "properties": {
                "machines": {
                    "type": "null"
                }
            },
            "additionalProperties": true
        }
    ],
    "required": [
        "_id",
        "created_at",
        "updated_at",
        "title",
        "content",
        "code",
        "amount",
        "percent",
        "machine_types",
        "start_at",
        "end_at"
    ]
}
```

##### 2.1.2.5.6 **promotion** JSON data

```
{
    "_id": "FXp6kX3BDDmt3BZI5KWy",
    "created_at": 1601313323,
    "updated_at": 1601313024,
    "title": "3123 3123 123 12",
    "content": "123",
    "code": "1233 123 12",
    "amount": 312331231,
    "percent": 123,
    "machine_types": [
        "msc"
    ],
    "start_at": 1601312400,
    "end_at": 1604025502,
    "machines": []
}
```

##### 2.1.2.5.7 **promotion** Target Script

```
use sunpay;

db.createCollection( "promotion",{
    "storageEngine": {
        "wiredTiger": {}
    },
    "capped": false,
    "validator": {
        "$jsonSchema": {
            "bsonType": "object",
            "title": "promotion",
            "properties": {
                "_id": {
                    "bsonType": "string"
                },
                "created_at": {
                    "bsonType": "int"
                },
                "updated_at": {
                    "bsonType": "int"
                },
                "title": {
                    "bsonType": "string"
                },
                "content": {
                    "bsonType": "string"
                },
                "code": {
                    "bsonType": "string"
                },
                "amount": {
                    "bsonType": "int"
                },
                "percent": {
                    "bsonType": "int"
                },
                "machine_types": {
                    "bsonType": "array",
                    "additionalItems": true,
                    "items": {
                        "bsonType": "string"
                    }
                },
                "start_at": {
                    "bsonType": "int"
                },
                "end_at": {
                    "bsonType": "int"
                }
            },
            "additionalProperties": true,
            "oneOf": [
                {
                    "bsonType": "object",
                    "properties": {
                        "machines": {
                            "bsonType": "array",
                            "additionalItems": true
                        }
                    },
                    "additionalProperties": true
                },
                {
                    "bsonType": "object",
                    "properties": {
                        "machines": {
                            "bsonType": "null"
                        }
                    },
                    "additionalProperties": true
                }
            ],
            "required": [
                "_id",
                "created_at",
                "updated_at",
                "title",
                "content",
                "code",
                "amount",
                "percent",
                "machine_types",
                "start_at",
                "end_at"
            ]
        }
    },
    "validationLevel": "off",
    "validationAction": "warn"
});
db.promotion.createIndex(
{
    "_id": 1
},
{
    "name": "_id_"
}
);

```

### <a id="5e03f6e3-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.6 Collection **push\_token**

##### 2.1.2.6.1 **push\_token** Tree Diagram

![Hackolade image](/erd/image75.png?raw=true)

##### 2.1.2.6.2 **push\_token** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Collection name</td><td>push_token</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Database</td><td><a href=#5eb3bee0-5a25-11eb-a046-d590fdb8e2e4>sunpay</a></td></tr><tr><td>Capped</td><td></td></tr><tr><td>Size</td><td></td></tr><tr><td>Max</td><td></td></tr><tr><td>Storage engine</td><td>WiredTiger</td></tr><tr><td>Config String</td><td></td></tr><tr><td>Validation level</td><td>Off</td></tr><tr><td>Validation action</td><td>Warn</td></tr><tr><td>Additional properties</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.6.3 **push\_token** Fields

<table><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5dfd674b-5a25-11eb-a046-d590fdb8e2e4>_id</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd674c-5a25-11eb-a046-d590fdb8e2e4>created_at</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd674f-5a25-11eb-a046-d590fdb8e2e4>updated_at</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd674e-5a25-11eb-a046-d590fdb8e2e4>uid</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd674d-5a25-11eb-a046-d590fdb8e2e4>token</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd674b-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.6.3.1 Field **\_id**

##### 2.1.2.6.3.1.1 **\_id** Tree Diagram

![Hackolade image](/erd/image76.png?raw=true)

##### 2.1.2.6.3.1.2 **\_id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>_id</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>XzM3FHohgDa1U1nhx8xk</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd674c-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.6.3.2 Field **created\_at**

##### 2.1.2.6.3.2.1 **created\_at** Tree Diagram

![Hackolade image](/erd/image77.png?raw=true)

##### 2.1.2.6.3.2.2 **created\_at** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>created_at</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>1609258722</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd674f-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.6.3.3 Field **updated\_at**

##### 2.1.2.6.3.3.1 **updated\_at** Tree Diagram

![Hackolade image](/erd/image78.png?raw=true)

##### 2.1.2.6.3.3.2 **updated\_at** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>updated_at</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>1611040322</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd674e-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.6.3.4 Field **uid**

##### 2.1.2.6.3.4.1 **uid** Tree Diagram

![Hackolade image](/erd/image79.png?raw=true)

##### 2.1.2.6.3.4.2 **uid** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>uid</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>oKusofOF9FWLjSnlS11cDTndf173</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd674d-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.6.3.5 Field **token**

##### 2.1.2.6.3.5.1 **token** Tree Diagram

![Hackolade image](/erd/image80.png?raw=true)

##### 2.1.2.6.3.5.2 **token** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>token</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>cvjRzV0fTDyGNwZsDn9rko:APA91bGyLgmDUS_-98O1ofYxzmEZTY-6scBga1rlovdDReAqNU5W4GluMjEJVbuvaQFJJo8DzYQ6575umZ7fYRbvzSqDdAU0Tm-JmyUAr2u8cJV7N8wNCMtfKe-HjVdXyXxS_Ws89WGB</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.6.4 **push\_token** Indexes

<table class="index-table"><thead><tr><td class="table-property-column">Property</td><td class="table-column-property">_id_</td></tr></thead><tbody><tr><td>Name</td><td class="table-column-indexes">_id_</td></tr><tr><td>Key</td><td class="table-column-indexes">_id('ascending')</td></tr><tr><td>Hashed</td><td class="table-column-indexes"></td></tr><tr><td>Unique</td><td class="table-column-indexes"></td></tr><tr><td>Drop duplicates</td><td class="table-column-indexes"></td></tr><tr><td>Sparse</td><td class="table-column-indexes"></td></tr><tr><td>Background indexing</td><td class="table-column-indexes"></td></tr><tr><td>Partial filter exp</td><td class="table-column-indexes"></td></tr><tr><td>Expire after (seconds)</td><td class="table-column-indexes"></td></tr><tr><td>Storage engine</td><td class="table-column-indexes"></td></tr><tr><td>Comments</td><td class="table-column-indexes"></td></tr></tbody></table>

##### 2.1.2.6.5 **push\_token** JSON Schema

```
{
    "$schema": "http://json-schema.org/draft-04/schema#",
    "type": "object",
    "title": "push_token",
    "properties": {
        "_id": {
            "type": "string"
        },
        "created_at": {
            "type": "integer"
        },
        "updated_at": {
            "type": "integer"
        },
        "uid": {
            "type": "string"
        },
        "token": {
            "type": "string"
        }
    },
    "required": [
        "_id",
        "created_at",
        "updated_at",
        "uid",
        "token"
    ]
}
```

##### 2.1.2.6.6 **push\_token** JSON data

```
{
    "_id": "XzM3FHohgDa1U1nhx8xk",
    "created_at": 1609258722,
    "updated_at": 1611040322,
    "uid": "oKusofOF9FWLjSnlS11cDTndf173",
    "token": "cvjRzV0fTDyGNwZsDn9rko:APA91bGyLgmDUS_-98O1ofYxzmEZTY-6scBga1rlovdDReAqNU5W4GluMjEJVbuvaQFJJo8DzYQ6575umZ7fYRbvzSqDdAU0Tm-JmyUAr2u8cJV7N8wNCMtfKe-HjVdXyXxS_Ws89WGB"
}
```

##### 2.1.2.6.7 **push\_token** Target Script

```
use sunpay;

db.createCollection( "push_token",{
    "storageEngine": {
        "wiredTiger": {}
    },
    "capped": false,
    "validator": {
        "$jsonSchema": {
            "bsonType": "object",
            "title": "push_token",
            "properties": {
                "_id": {
                    "bsonType": "string"
                },
                "created_at": {
                    "bsonType": "int"
                },
                "updated_at": {
                    "bsonType": "int"
                },
                "uid": {
                    "bsonType": "string"
                },
                "token": {
                    "bsonType": "string"
                }
            },
            "required": [
                "_id",
                "created_at",
                "updated_at",
                "uid",
                "token"
            ]
        }
    },
    "validationLevel": "off",
    "validationAction": "warn"
});
db.push_token.createIndex(
{
    "_id": 1
},
{
    "name": "_id_"
}
);

```

### <a id="5e044501-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.7 Collection **store**

##### 2.1.2.7.1 **store** Tree Diagram

![Hackolade image](/erd/image81.png?raw=true)

##### 2.1.2.7.2 **store** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Collection name</td><td>store</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Database</td><td><a href=#5eb3bee0-5a25-11eb-a046-d590fdb8e2e4>sunpay</a></td></tr><tr><td>Capped</td><td></td></tr><tr><td>Size</td><td></td></tr><tr><td>Max</td><td></td></tr><tr><td>Storage engine</td><td>WiredTiger</td></tr><tr><td>Config String</td><td></td></tr><tr><td>Validation level</td><td>Off</td></tr><tr><td>Validation action</td><td>Warn</td></tr><tr><td>Additional properties</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.7.3 **store** Fields

<table><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5dfd6750-5a25-11eb-a046-d590fdb8e2e4>_id</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6752-5a25-11eb-a046-d590fdb8e2e4>created_at</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e40-5a25-11eb-a046-d590fdb8e2e4>updated_at</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6756-5a25-11eb-a046-d590fdb8e2e4>name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6757-5a25-11eb-a046-d590fdb8e2e4>phone</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6755-5a25-11eb-a046-d590fdb8e2e4>models</a></td><td class="no-break-word">array</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5e046c10-5a25-11eb-a046-d590fdb8e2e4>[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6751-5a25-11eb-a046-d590fdb8e2e4>address</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6753-5a25-11eb-a046-d590fdb8e2e4>lat</a></td><td class="no-break-word">double</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd6754-5a25-11eb-a046-d590fdb8e2e4>lng</a></td><td class="no-break-word">double</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6750-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.7.3.1 Field **\_id**

##### 2.1.2.7.3.1.1 **\_id** Tree Diagram

![Hackolade image](/erd/image82.png?raw=true)

##### 2.1.2.7.3.1.2 **\_id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>_id</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>mH7jPvrpBxAREKl1U3ML</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6752-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.7.3.2 Field **created\_at**

##### 2.1.2.7.3.2.1 **created\_at** Tree Diagram

![Hackolade image](/erd/image83.png?raw=true)

##### 2.1.2.7.3.2.2 **created\_at** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>created_at</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>1602514373</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e40-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.7.3.3 Field **updated\_at**

##### 2.1.2.7.3.3.1 **updated\_at** Tree Diagram

![Hackolade image](/erd/image84.png?raw=true)

##### 2.1.2.7.3.3.2 **updated\_at** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>updated_at</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>1602654724</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6756-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.7.3.4 Field **name**

##### 2.1.2.7.3.4.1 **name** Tree Diagram

![Hackolade image](/erd/image85.png?raw=true)

##### 2.1.2.7.3.4.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>Giặt sấy Mễ Trì</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6757-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.7.3.5 Field **phone**

##### 2.1.2.7.3.5.1 **phone** Tree Diagram

![Hackolade image](/erd/image86.png?raw=true)

##### 2.1.2.7.3.5.2 **phone** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>phone</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>0985336213</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6755-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.7.3.6 Field **models**

##### 2.1.2.7.3.6.1 **models** Tree Diagram

![Hackolade image](/erd/image87.png?raw=true)

##### 2.1.2.7.3.6.2 **models** Hierarchy

Parent field: **store**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5e046c10-5a25-11eb-a046-d590fdb8e2e4>[0]</a></td><td class="no-break-word">string</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.7.3.6.3 **models** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>models</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Min items</td><td></td></tr><tr><td>Max items</td><td></td></tr><tr><td>Unique items</td><td></td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5e046c10-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.7.3.7 Field **\[0\]**

##### 2.1.2.7.3.7.1 **\[0\]** Tree Diagram

![Hackolade image](/erd/image88.png?raw=true)

##### 2.1.2.7.3.7.2 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Primary key</td><td></td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>wsc</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6751-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.7.3.8 Field **address**

##### 2.1.2.7.3.8.1 **address** Tree Diagram

![Hackolade image](/erd/image89.png?raw=true)

##### 2.1.2.7.3.8.2 **address** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>address</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>35 Mễ Trì, Từ Liêm, Hà Nội, Việt Nam</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6753-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.7.3.9 Field **lat**

##### 2.1.2.7.3.9.1 **lat** Tree Diagram

![Hackolade image](/erd/image90.png?raw=true)

##### 2.1.2.7.3.9.2 **lat** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>lat</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>double</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>21.019182205200195</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd6754-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.7.3.10 Field **lng**

##### 2.1.2.7.3.10.1 **lng** Tree Diagram

![Hackolade image](/erd/image91.png?raw=true)

##### 2.1.2.7.3.10.2 **lng** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>lng</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>double</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>105.79998016357422</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.7.4 **store** Indexes

<table class="index-table"><thead><tr><td class="table-property-column">Property</td><td class="table-column-property">_id_</td></tr></thead><tbody><tr><td>Name</td><td class="table-column-indexes">_id_</td></tr><tr><td>Key</td><td class="table-column-indexes">_id('ascending')</td></tr><tr><td>Hashed</td><td class="table-column-indexes"></td></tr><tr><td>Unique</td><td class="table-column-indexes"></td></tr><tr><td>Drop duplicates</td><td class="table-column-indexes"></td></tr><tr><td>Sparse</td><td class="table-column-indexes"></td></tr><tr><td>Background indexing</td><td class="table-column-indexes"></td></tr><tr><td>Partial filter exp</td><td class="table-column-indexes"></td></tr><tr><td>Expire after (seconds)</td><td class="table-column-indexes"></td></tr><tr><td>Storage engine</td><td class="table-column-indexes"></td></tr><tr><td>Comments</td><td class="table-column-indexes"></td></tr></tbody></table>

##### 2.1.2.7.5 **store** JSON Schema

```
{
    "$schema": "http://json-schema.org/draft-04/schema#",
    "type": "object",
    "title": "store",
    "properties": {
        "_id": {
            "type": "string"
        },
        "created_at": {
            "type": "integer"
        },
        "updated_at": {
            "type": "integer"
        },
        "name": {
            "type": "string"
        },
        "phone": {
            "type": "string"
        },
        "models": {
            "type": "array",
            "additionalItems": true,
            "items": {
                "type": "string"
            }
        },
        "address": {
            "type": "string"
        },
        "lat": {
            "type": "number"
        },
        "lng": {
            "type": "number"
        }
    },
    "required": [
        "_id",
        "created_at",
        "updated_at",
        "name",
        "phone",
        "models",
        "address",
        "lat",
        "lng"
    ]
}
```

##### 2.1.2.7.6 **store** JSON data

```
{
    "_id": "mH7jPvrpBxAREKl1U3ML",
    "created_at": 1602514373,
    "updated_at": 1602654724,
    "name": "Giặt sấy Mễ Trì",
    "phone": "0985336213",
    "models": [
        "wsc"
    ],
    "address": "35 Mễ Trì, Từ Liêm, Hà Nội, Việt Nam",
    "lat": 21.019182205200195,
    "lng": 105.79998016357422
}
```

##### 2.1.2.7.7 **store** Target Script

```
use sunpay;

db.createCollection( "store",{
    "storageEngine": {
        "wiredTiger": {}
    },
    "capped": false,
    "validator": {
        "$jsonSchema": {
            "bsonType": "object",
            "title": "store",
            "properties": {
                "_id": {
                    "bsonType": "string"
                },
                "created_at": {
                    "bsonType": "int"
                },
                "updated_at": {
                    "bsonType": "int"
                },
                "name": {
                    "bsonType": "string"
                },
                "phone": {
                    "bsonType": "string"
                },
                "models": {
                    "bsonType": "array",
                    "additionalItems": true,
                    "items": {
                        "bsonType": "string"
                    }
                },
                "address": {
                    "bsonType": "string"
                },
                "lat": {
                    "bsonType": "double"
                },
                "lng": {
                    "bsonType": "double"
                }
            },
            "required": [
                "_id",
                "created_at",
                "updated_at",
                "name",
                "phone",
                "models",
                "address",
                "lat",
                "lng"
            ]
        }
    },
    "validationLevel": "off",
    "validationAction": "warn"
});
db.store.createIndex(
{
    "_id": 1
},
{
    "name": "_id_"
}
);

```

### <a id="5e049321-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.8 Collection **system\_setting**

##### 2.1.2.8.1 **system\_setting** Tree Diagram

![Hackolade image](/erd/image92.png?raw=true)

##### 2.1.2.8.2 **system\_setting** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Collection name</td><td>system_setting</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Database</td><td><a href=#5eb3bee0-5a25-11eb-a046-d590fdb8e2e4>sunpay</a></td></tr><tr><td>Capped</td><td></td></tr><tr><td>Size</td><td></td></tr><tr><td>Max</td><td></td></tr><tr><td>Storage engine</td><td>WiredTiger</td></tr><tr><td>Config String</td><td></td></tr><tr><td>Validation level</td><td>Off</td></tr><tr><td>Validation action</td><td>Warn</td></tr><tr><td>Additional properties</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.8.3 **system\_setting** Fields

<table><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5dfd8e41-5a25-11eb-a046-d590fdb8e2e4>_id</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e45-5a25-11eb-a046-d590fdb8e2e4>new_user_greeting_msg</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e46-5a25-11eb-a046-d590fdb8e2e4>new_user_promotion_amount</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e44-5a25-11eb-a046-d590fdb8e2e4>loyalty_program_one_point_to_money</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e43-5a25-11eb-a046-d590fdb8e2e4>loyalty_program_money_to_one_point</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e42-5a25-11eb-a046-d590fdb8e2e4>created_at</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e47-5a25-11eb-a046-d590fdb8e2e4>updated_at</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e41-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.8.3.1 Field **\_id**

##### 2.1.2.8.3.1.1 **\_id** Tree Diagram

![Hackolade image](/erd/image93.png?raw=true)

##### 2.1.2.8.3.1.2 **\_id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>_id</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>system_setting</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e45-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.8.3.2 Field **new\_user\_greeting\_msg**

##### 2.1.2.8.3.2.1 **new\_user\_greeting\_msg** Tree Diagram

![Hackolade image](/erd/image94.png?raw=true)

##### 2.1.2.8.3.2.2 **new\_user\_greeting\_msg** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>new_user_greeting_msg</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>Chào mừng khách hàng đã sử dụng app thanh toán dịch vụ của Sunwon Việt Nam</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e46-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.8.3.3 Field **new\_user\_promotion\_amount**

##### 2.1.2.8.3.3.1 **new\_user\_promotion\_amount** Tree Diagram

![Hackolade image](/erd/image95.png?raw=true)

##### 2.1.2.8.3.3.2 **new\_user\_promotion\_amount** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>new_user_promotion_amount</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>10000</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e44-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.8.3.4 Field **loyalty\_program\_one\_point\_to\_money**

##### 2.1.2.8.3.4.1 **loyalty\_program\_one\_point\_to\_money** Tree Diagram

![Hackolade image](/erd/image96.png?raw=true)

##### 2.1.2.8.3.4.2 **loyalty\_program\_one\_point\_to\_money** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>loyalty_program_one_point_to_money</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>200</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e43-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.8.3.5 Field **loyalty\_program\_money\_to\_one\_point**

##### 2.1.2.8.3.5.1 **loyalty\_program\_money\_to\_one\_point** Tree Diagram

![Hackolade image](/erd/image97.png?raw=true)

##### 2.1.2.8.3.5.2 **loyalty\_program\_money\_to\_one\_point** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>loyalty_program_money_to_one_point</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>600</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e42-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.8.3.6 Field **created\_at**

##### 2.1.2.8.3.6.1 **created\_at** Tree Diagram

![Hackolade image](/erd/image98.png?raw=true)

##### 2.1.2.8.3.6.2 **created\_at** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>created_at</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>1602518199</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e47-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.8.3.7 Field **updated\_at**

##### 2.1.2.8.3.7.1 **updated\_at** Tree Diagram

![Hackolade image](/erd/image99.png?raw=true)

##### 2.1.2.8.3.7.2 **updated\_at** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>updated_at</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>1602521015</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.8.4 **system\_setting** Indexes

<table class="index-table"><thead><tr><td class="table-property-column">Property</td><td class="table-column-property">_id_</td></tr></thead><tbody><tr><td>Name</td><td class="table-column-indexes">_id_</td></tr><tr><td>Key</td><td class="table-column-indexes">_id('ascending')</td></tr><tr><td>Hashed</td><td class="table-column-indexes"></td></tr><tr><td>Unique</td><td class="table-column-indexes"></td></tr><tr><td>Drop duplicates</td><td class="table-column-indexes"></td></tr><tr><td>Sparse</td><td class="table-column-indexes"></td></tr><tr><td>Background indexing</td><td class="table-column-indexes"></td></tr><tr><td>Partial filter exp</td><td class="table-column-indexes"></td></tr><tr><td>Expire after (seconds)</td><td class="table-column-indexes"></td></tr><tr><td>Storage engine</td><td class="table-column-indexes"></td></tr><tr><td>Comments</td><td class="table-column-indexes"></td></tr></tbody></table>

##### 2.1.2.8.5 **system\_setting** JSON Schema

```
{
    "$schema": "http://json-schema.org/draft-04/schema#",
    "type": "object",
    "title": "system_setting",
    "properties": {
        "_id": {
            "type": "string"
        },
        "new_user_greeting_msg": {
            "type": "string"
        },
        "new_user_promotion_amount": {
            "type": "integer"
        },
        "loyalty_program_one_point_to_money": {
            "type": "integer"
        },
        "loyalty_program_money_to_one_point": {
            "type": "integer"
        },
        "created_at": {
            "type": "integer"
        },
        "updated_at": {
            "type": "integer"
        }
    },
    "required": [
        "_id",
        "new_user_greeting_msg",
        "new_user_promotion_amount",
        "loyalty_program_one_point_to_money",
        "loyalty_program_money_to_one_point",
        "created_at",
        "updated_at"
    ]
}
```

##### 2.1.2.8.6 **system\_setting** JSON data

```
{
    "_id": "system_setting",
    "new_user_greeting_msg": "Chào mừng khách hàng đã sử dụng app thanh toán dịch vụ của Sunwon Việt Nam",
    "new_user_promotion_amount": 10000,
    "loyalty_program_one_point_to_money": 200,
    "loyalty_program_money_to_one_point": 600,
    "created_at": 1602518199,
    "updated_at": 1602521015
}
```

##### 2.1.2.8.7 **system\_setting** Target Script

```
use sunpay;

db.createCollection( "system_setting",{
    "storageEngine": {
        "wiredTiger": {}
    },
    "capped": false,
    "validator": {
        "$jsonSchema": {
            "bsonType": "object",
            "title": "system_setting",
            "properties": {
                "_id": {
                    "bsonType": "string"
                },
                "new_user_greeting_msg": {
                    "bsonType": "string"
                },
                "new_user_promotion_amount": {
                    "bsonType": "int"
                },
                "loyalty_program_one_point_to_money": {
                    "bsonType": "int"
                },
                "loyalty_program_money_to_one_point": {
                    "bsonType": "int"
                },
                "created_at": {
                    "bsonType": "int"
                },
                "updated_at": {
                    "bsonType": "int"
                }
            },
            "required": [
                "_id",
                "new_user_greeting_msg",
                "new_user_promotion_amount",
                "loyalty_program_one_point_to_money",
                "loyalty_program_money_to_one_point",
                "created_at",
                "updated_at"
            ]
        }
    },
    "validationLevel": "off",
    "validationAction": "warn"
});
db.system_setting.createIndex(
{
    "_id": 1
},
{
    "name": "_id_"
}
);

```

### <a id="5e04e140-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.9 Collection **transaction**

##### 2.1.2.9.1 **transaction** Tree Diagram

![Hackolade image](/erd/image100.png?raw=true)

##### 2.1.2.9.2 **transaction** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Collection name</td><td>transaction</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Database</td><td><a href=#5eb3bee0-5a25-11eb-a046-d590fdb8e2e4>sunpay</a></td></tr><tr><td>Capped</td><td></td></tr><tr><td>Size</td><td></td></tr><tr><td>Max</td><td></td></tr><tr><td>Storage engine</td><td>WiredTiger</td></tr><tr><td>Config String</td><td></td></tr><tr><td>Validation level</td><td>Off</td></tr><tr><td>Validation action</td><td>Warn</td></tr><tr><td>Additional properties</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.9.3 **transaction** Fields

<table><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5dfd8e48-5a25-11eb-a046-d590fdb8e2e4>_id</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e4a-5a25-11eb-a046-d590fdb8e2e4>created_at</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e50-5a25-11eb-a046-d590fdb8e2e4>updated_at</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e4d-5a25-11eb-a046-d590fdb8e2e4>name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e4f-5a25-11eb-a046-d590fdb8e2e4>type</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e4e-5a25-11eb-a046-d590fdb8e2e4>state</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e49-5a25-11eb-a046-d590fdb8e2e4>amount</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e4b-5a25-11eb-a046-d590fdb8e2e4>customer_id</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e4c-5a25-11eb-a046-d590fdb8e2e4>momo_transaction_id</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e51-5a25-11eb-a046-d590fdb8e2e4>zalopay_transaction_id</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e48-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.9.3.1 Field **\_id**

##### 2.1.2.9.3.1.1 **\_id** Tree Diagram

![Hackolade image](/erd/image101.png?raw=true)

##### 2.1.2.9.3.1.2 **\_id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>_id</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>QtsncCr6Jj7jc2cw0DWo</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e4a-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.9.3.2 Field **created\_at**

##### 2.1.2.9.3.2.1 **created\_at** Tree Diagram

![Hackolade image](/erd/image102.png?raw=true)

##### 2.1.2.9.3.2.2 **created\_at** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>created_at</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>1609323868</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e50-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.9.3.3 Field **updated\_at**

##### 2.1.2.9.3.3.1 **updated\_at** Tree Diagram

![Hackolade image](/erd/image103.png?raw=true)

##### 2.1.2.9.3.3.2 **updated\_at** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>updated_at</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>1609323887</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e4d-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.9.3.4 Field **name**

##### 2.1.2.9.3.4.1 **name** Tree Diagram

![Hackolade image](/erd/image104.png?raw=true)

##### 2.1.2.9.3.4.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>Nạp tiền ứng dụng Sunpay</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e4f-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.9.3.5 Field **type**

##### 2.1.2.9.3.5.1 **type** Tree Diagram

![Hackolade image](/erd/image105.png?raw=true)

##### 2.1.2.9.3.5.2 **type** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>type</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>charge</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e4e-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.9.3.6 Field **state**

##### 2.1.2.9.3.6.1 **state** Tree Diagram

![Hackolade image](/erd/image106.png?raw=true)

##### 2.1.2.9.3.6.2 **state** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>state</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>success</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e49-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.9.3.7 Field **amount**

##### 2.1.2.9.3.7.1 **amount** Tree Diagram

![Hackolade image](/erd/image107.png?raw=true)

##### 2.1.2.9.3.7.2 **amount** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>amount</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>10965000</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e4b-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.9.3.8 Field **customer\_id**

##### 2.1.2.9.3.8.1 **customer\_id** Tree Diagram

![Hackolade image](/erd/image108.png?raw=true)

##### 2.1.2.9.3.8.2 **customer\_id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>customer_id</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>5BLUdsJUITZdPncRJnj2JqaAfz73</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e4c-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.9.3.9 Field **momo\_transaction\_id**

##### 2.1.2.9.3.9.1 **momo\_transaction\_id** Tree Diagram

![Hackolade image](/erd/image109.png?raw=true)

##### 2.1.2.9.3.9.2 **momo\_transaction\_id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>momo_transaction_id</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e51-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.9.3.10 Field **zalopay\_transaction\_id**

##### 2.1.2.9.3.10.1 **zalopay\_transaction\_id** Tree Diagram

![Hackolade image](/erd/image110.png?raw=true)

##### 2.1.2.9.3.10.2 **zalopay\_transaction\_id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>zalopay_transaction_id</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>201230000008161YY789vK</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.9.4 **transaction** Indexes

<table class="index-table"><thead><tr><td class="table-property-column">Property</td><td class="table-column-property">_id_</td></tr></thead><tbody><tr><td>Name</td><td class="table-column-indexes">_id_</td></tr><tr><td>Key</td><td class="table-column-indexes">_id('ascending')</td></tr><tr><td>Hashed</td><td class="table-column-indexes"></td></tr><tr><td>Unique</td><td class="table-column-indexes"></td></tr><tr><td>Drop duplicates</td><td class="table-column-indexes"></td></tr><tr><td>Sparse</td><td class="table-column-indexes"></td></tr><tr><td>Background indexing</td><td class="table-column-indexes"></td></tr><tr><td>Partial filter exp</td><td class="table-column-indexes"></td></tr><tr><td>Expire after (seconds)</td><td class="table-column-indexes"></td></tr><tr><td>Storage engine</td><td class="table-column-indexes"></td></tr><tr><td>Comments</td><td class="table-column-indexes"></td></tr></tbody></table>

##### 2.1.2.9.5 **transaction** JSON Schema

```
{
    "$schema": "http://json-schema.org/draft-04/schema#",
    "type": "object",
    "title": "transaction",
    "properties": {
        "_id": {
            "type": "string"
        },
        "created_at": {
            "type": "integer"
        },
        "updated_at": {
            "type": "integer"
        },
        "name": {
            "type": "string"
        },
        "type": {
            "type": "string"
        },
        "state": {
            "type": "string"
        },
        "amount": {
            "type": "integer"
        },
        "customer_id": {
            "type": "string"
        },
        "momo_transaction_id": {
            "type": "string"
        },
        "zalopay_transaction_id": {
            "type": "string"
        }
    },
    "required": [
        "_id",
        "created_at",
        "updated_at",
        "name",
        "type",
        "state",
        "amount",
        "customer_id",
        "momo_transaction_id",
        "zalopay_transaction_id"
    ]
}
```

##### 2.1.2.9.6 **transaction** JSON data

```
{
    "_id": "QtsncCr6Jj7jc2cw0DWo",
    "created_at": 1609323868,
    "updated_at": 1609323887,
    "name": "Nạp tiền ứng dụng Sunpay ",
    "type": "charge",
    "state": "success",
    "amount": 10965000,
    "customer_id": "5BLUdsJUITZdPncRJnj2JqaAfz73",
    "momo_transaction_id": "Lorem",
    "zalopay_transaction_id": "201230000008161YY789vK"
}
```

##### 2.1.2.9.7 **transaction** Target Script

```
use sunpay;

db.createCollection( "transaction",{
    "storageEngine": {
        "wiredTiger": {}
    },
    "capped": false,
    "validator": {
        "$jsonSchema": {
            "bsonType": "object",
            "title": "transaction",
            "properties": {
                "_id": {
                    "bsonType": "string"
                },
                "created_at": {
                    "bsonType": "int"
                },
                "updated_at": {
                    "bsonType": "int"
                },
                "name": {
                    "bsonType": "string"
                },
                "type": {
                    "bsonType": "string"
                },
                "state": {
                    "bsonType": "string"
                },
                "amount": {
                    "bsonType": "int"
                },
                "customer_id": {
                    "bsonType": "string"
                },
                "momo_transaction_id": {
                    "bsonType": "string"
                },
                "zalopay_transaction_id": {
                    "bsonType": "string"
                }
            },
            "required": [
                "_id",
                "created_at",
                "updated_at",
                "name",
                "type",
                "state",
                "amount",
                "customer_id",
                "momo_transaction_id",
                "zalopay_transaction_id"
            ]
        }
    },
    "validationLevel": "off",
    "validationAction": "warn"
});
db.transaction.createIndex(
{
    "_id": 1
},
{
    "name": "_id_"
}
);

```

### <a id="5e052f61-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.10 Collection **vendor**

##### 2.1.2.10.1 **vendor** Tree Diagram

![Hackolade image](/erd/image111.png?raw=true)

##### 2.1.2.10.2 **vendor** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Collection name</td><td>vendor</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Database</td><td><a href=#5eb3bee0-5a25-11eb-a046-d590fdb8e2e4>sunpay</a></td></tr><tr><td>Capped</td><td></td></tr><tr><td>Size</td><td></td></tr><tr><td>Max</td><td></td></tr><tr><td>Storage engine</td><td>WiredTiger</td></tr><tr><td>Config String</td><td></td></tr><tr><td>Validation level</td><td>Off</td></tr><tr><td>Validation action</td><td>Warn</td></tr><tr><td>Additional properties</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.10.3 **vendor** Fields

<table><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5dfd8e52-5a25-11eb-a046-d590fdb8e2e4>_id</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e54-5a25-11eb-a046-d590fdb8e2e4>created_at</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e61-5a25-11eb-a046-d590fdb8e2e4>updated_at</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e5f-5a25-11eb-a046-d590fdb8e2e4>name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e59-5a25-11eb-a046-d590fdb8e2e4>email</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e5b-5a25-11eb-a046-d590fdb8e2e4>information</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e60-5a25-11eb-a046-d590fdb8e2e4>password</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e53-5a25-11eb-a046-d590fdb8e2e4>activated</a></td><td class="no-break-word">boolean</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e5a-5a25-11eb-a046-d590fdb8e2e4>expired_at</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e5c-5a25-11eb-a046-d590fdb8e2e4>momo_access_key</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e5e-5a25-11eb-a046-d590fdb8e2e4>momo_secret_key</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e5d-5a25-11eb-a046-d590fdb8e2e4>momo_partner_code</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e62-5a25-11eb-a046-d590fdb8e2e4>zlpay_app_id</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e63-5a25-11eb-a046-d590fdb8e2e4>zlpay_app_user</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e64-5a25-11eb-a046-d590fdb8e2e4>zlpay_key1</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e65-5a25-11eb-a046-d590fdb8e2e4>zlpay_key2</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5e052f63-5a25-11eb-a046-d590fdb8e2e4>oneOf</a></td><td class="no-break-word">choice</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e55-5a25-11eb-a046-d590fdb8e2e4>[0]</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e56-5a25-11eb-a046-d590fdb8e2e4>device_id</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e57-5a25-11eb-a046-d590fdb8e2e4>[1]</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e58-5a25-11eb-a046-d590fdb8e2e4>device_id</a></td><td class="no-break-word">null</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e52-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.10.3.1 Field **\_id**

##### 2.1.2.10.3.1.1 **\_id** Tree Diagram

![Hackolade image](/erd/image112.png?raw=true)

##### 2.1.2.10.3.1.2 **\_id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>_id</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>2QehADstUMZf18lRVXWa</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e54-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.10.3.2 Field **created\_at**

##### 2.1.2.10.3.2.1 **created\_at** Tree Diagram

![Hackolade image](/erd/image113.png?raw=true)

##### 2.1.2.10.3.2.2 **created\_at** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>created_at</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>1610298679</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e61-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.10.3.3 Field **updated\_at**

##### 2.1.2.10.3.3.1 **updated\_at** Tree Diagram

![Hackolade image](/erd/image114.png?raw=true)

##### 2.1.2.10.3.3.2 **updated\_at** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>updated_at</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>1610378684</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e5f-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.10.3.4 Field **name**

##### 2.1.2.10.3.4.1 **name** Tree Diagram

![Hackolade image](/erd/image115.png?raw=true)

##### 2.1.2.10.3.4.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>test</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e59-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.10.3.5 Field **email**

##### 2.1.2.10.3.5.1 **email** Tree Diagram

![Hackolade image](/erd/image116.png?raw=true)

##### 2.1.2.10.3.5.2 **email** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>email</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>123123@a.com</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e5b-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.10.3.6 Field **information**

##### 2.1.2.10.3.6.1 **information** Tree Diagram

![Hackolade image](/erd/image117.png?raw=true)

##### 2.1.2.10.3.6.2 **information** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>information</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>cxzczxc</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e60-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.10.3.7 Field **password**

##### 2.1.2.10.3.7.1 **password** Tree Diagram

![Hackolade image](/erd/image118.png?raw=true)

##### 2.1.2.10.3.7.2 **password** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>password</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>123456</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e53-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.10.3.8 Field **activated**

##### 2.1.2.10.3.8.1 **activated** Tree Diagram

![Hackolade image](/erd/image119.png?raw=true)

##### 2.1.2.10.3.8.2 **activated** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>activated</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>boolean</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Sample</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e5a-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.10.3.9 Field **expired\_at**

##### 2.1.2.10.3.9.1 **expired\_at** Tree Diagram

![Hackolade image](/erd/image120.png?raw=true)

##### 2.1.2.10.3.9.2 **expired\_at** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>expired_at</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>0</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e5c-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.10.3.10 Field **momo\_access\_key**

##### 2.1.2.10.3.10.1 **momo\_access\_key** Tree Diagram

![Hackolade image](/erd/image121.png?raw=true)

##### 2.1.2.10.3.10.2 **momo\_access\_key** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>momo_access_key</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e5e-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.10.3.11 Field **momo\_secret\_key**

##### 2.1.2.10.3.11.1 **momo\_secret\_key** Tree Diagram

![Hackolade image](/erd/image122.png?raw=true)

##### 2.1.2.10.3.11.2 **momo\_secret\_key** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>momo_secret_key</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e5d-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.10.3.12 Field **momo\_partner\_code**

##### 2.1.2.10.3.12.1 **momo\_partner\_code** Tree Diagram

![Hackolade image](/erd/image123.png?raw=true)

##### 2.1.2.10.3.12.2 **momo\_partner\_code** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>momo_partner_code</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e62-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.10.3.13 Field **zlpay\_app\_id**

##### 2.1.2.10.3.13.1 **zlpay\_app\_id** Tree Diagram

![Hackolade image](/erd/image124.png?raw=true)

##### 2.1.2.10.3.13.2 **zlpay\_app\_id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>zlpay_app_id</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e63-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.10.3.14 Field **zlpay\_app\_user**

##### 2.1.2.10.3.14.1 **zlpay\_app\_user** Tree Diagram

![Hackolade image](/erd/image125.png?raw=true)

##### 2.1.2.10.3.14.2 **zlpay\_app\_user** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>zlpay_app_user</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e64-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.10.3.15 Field **zlpay\_key1**

##### 2.1.2.10.3.15.1 **zlpay\_key1** Tree Diagram

![Hackolade image](/erd/image126.png?raw=true)

##### 2.1.2.10.3.15.2 **zlpay\_key1** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>zlpay_key1</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e65-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.10.3.16 Field **zlpay\_key2**

##### 2.1.2.10.3.16.1 **zlpay\_key2** Tree Diagram

![Hackolade image](/erd/image127.png?raw=true)

##### 2.1.2.10.3.16.2 **zlpay\_key2** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>zlpay_key2</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5e052f63-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.10.3.17 Field **oneOf**

##### 2.1.2.10.3.17.1 **oneOf** Tree Diagram

![Hackolade image](/erd/image128.png?raw=true)

##### 2.1.2.10.3.17.2 **oneOf** Hierarchy

Parent field: **vendor**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5dfd8e55-5a25-11eb-a046-d590fdb8e2e4>[0]</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e57-5a25-11eb-a046-d590fdb8e2e4>[1]</a></td><td class="no-break-word">subschema</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.10.3.17.3 **oneOf** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Choice</td><td>oneOf</td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e55-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.10.3.18 Field **\[0\]**

##### 2.1.2.10.3.18.1 **\[0\]** Tree Diagram

![Hackolade image](/erd/image129.png?raw=true)

##### 2.1.2.10.3.18.2 **\[0\]** Hierarchy

Parent field: **oneOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5dfd8e56-5a25-11eb-a046-d590fdb8e2e4>device_id</a></td><td class="no-break-word">array</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.10.3.18.3 **\[0\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Required</td><td></td></tr><tr><td>Min Properties</td><td></td></tr><tr><td>Max Properties</td><td></td></tr><tr><td>Additional properties</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e56-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.10.3.19 Field **device\_id**

##### 2.1.2.10.3.19.1 **device\_id** Tree Diagram

![Hackolade image](/erd/image130.png?raw=true)

##### 2.1.2.10.3.19.2 **device\_id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>device_id</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>array</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td></td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Min items</td><td></td></tr><tr><td>Max items</td><td></td></tr><tr><td>Unique items</td><td></td></tr><tr><td>Additional items</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e57-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.10.3.20 Field **\[1\]**

##### 2.1.2.10.3.20.1 **\[1\]** Tree Diagram

![Hackolade image](/erd/image131.png?raw=true)

##### 2.1.2.10.3.20.2 **\[1\]** Hierarchy

Parent field: **oneOf**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5dfd8e58-5a25-11eb-a046-d590fdb8e2e4>device_id</a></td><td class="no-break-word">null</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.10.3.20.3 **\[1\]** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Display name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Required</td><td></td></tr><tr><td>Min Properties</td><td></td></tr><tr><td>Max Properties</td><td></td></tr><tr><td>Additional properties</td><td>true</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e58-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.10.3.21 Field **device\_id**

##### 2.1.2.10.3.21.1 **device\_id** Tree Diagram

![Hackolade image](/erd/image132.png?raw=true)

##### 2.1.2.10.3.21.2 **device\_id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>device_id</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>null</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.10.4 **vendor** Indexes

<table class="index-table"><thead><tr><td class="table-property-column">Property</td><td class="table-column-property">_id_</td></tr></thead><tbody><tr><td>Name</td><td class="table-column-indexes">_id_</td></tr><tr><td>Key</td><td class="table-column-indexes">_id('ascending')</td></tr><tr><td>Hashed</td><td class="table-column-indexes"></td></tr><tr><td>Unique</td><td class="table-column-indexes"></td></tr><tr><td>Drop duplicates</td><td class="table-column-indexes"></td></tr><tr><td>Sparse</td><td class="table-column-indexes"></td></tr><tr><td>Background indexing</td><td class="table-column-indexes"></td></tr><tr><td>Partial filter exp</td><td class="table-column-indexes"></td></tr><tr><td>Expire after (seconds)</td><td class="table-column-indexes"></td></tr><tr><td>Storage engine</td><td class="table-column-indexes"></td></tr><tr><td>Comments</td><td class="table-column-indexes"></td></tr></tbody></table>

##### 2.1.2.10.5 **vendor** JSON Schema

```
{
    "$schema": "http://json-schema.org/draft-04/schema#",
    "type": "object",
    "title": "vendor",
    "properties": {
        "_id": {
            "type": "string"
        },
        "created_at": {
            "type": "integer"
        },
        "updated_at": {
            "type": "integer"
        },
        "name": {
            "type": "string"
        },
        "email": {
            "type": "string"
        },
        "information": {
            "type": "string"
        },
        "password": {
            "type": "string"
        },
        "activated": {
            "type": "boolean"
        },
        "expired_at": {
            "type": "integer"
        },
        "momo_access_key": {
            "type": "string"
        },
        "momo_secret_key": {
            "type": "string"
        },
        "momo_partner_code": {
            "type": "string"
        },
        "zlpay_app_id": {
            "type": "string"
        },
        "zlpay_app_user": {
            "type": "string"
        },
        "zlpay_key1": {
            "type": "string"
        },
        "zlpay_key2": {
            "type": "string"
        }
    },
    "additionalProperties": true,
    "oneOf": [
        {
            "type": "object",
            "properties": {
                "device_id": {
                    "type": "array",
                    "additionalItems": true
                }
            },
            "additionalProperties": true
        },
        {
            "type": "object",
            "properties": {
                "device_id": {
                    "type": "null"
                }
            },
            "additionalProperties": true
        }
    ],
    "required": [
        "_id",
        "created_at",
        "updated_at",
        "name",
        "email",
        "information",
        "password",
        "activated",
        "expired_at",
        "momo_access_key",
        "momo_secret_key",
        "momo_partner_code",
        "zlpay_app_id",
        "zlpay_app_user",
        "zlpay_key1",
        "zlpay_key2"
    ]
}
```

##### 2.1.2.10.6 **vendor** JSON data

```
{
    "_id": "2QehADstUMZf18lRVXWa",
    "created_at": 1610298679,
    "updated_at": 1610378684,
    "name": "test",
    "email": "123123@a.com",
    "information": "cxzczxc",
    "password": "123456",
    "activated": true,
    "expired_at": 0,
    "momo_access_key": "Lorem",
    "momo_secret_key": "Lorem",
    "momo_partner_code": "Lorem",
    "zlpay_app_id": "Lorem",
    "zlpay_app_user": "Lorem",
    "zlpay_key1": "Lorem",
    "zlpay_key2": "Lorem",
    "device_id": []
}
```

##### 2.1.2.10.7 **vendor** Target Script

```
use sunpay;

db.createCollection( "vendor",{
    "storageEngine": {
        "wiredTiger": {}
    },
    "capped": false,
    "validator": {
        "$jsonSchema": {
            "bsonType": "object",
            "title": "vendor",
            "properties": {
                "_id": {
                    "bsonType": "string"
                },
                "created_at": {
                    "bsonType": "int"
                },
                "updated_at": {
                    "bsonType": "int"
                },
                "name": {
                    "bsonType": "string"
                },
                "email": {
                    "bsonType": "string"
                },
                "information": {
                    "bsonType": "string"
                },
                "password": {
                    "bsonType": "string"
                },
                "activated": {
                    "bsonType": "bool"
                },
                "expired_at": {
                    "bsonType": "int"
                },
                "momo_access_key": {
                    "bsonType": "string"
                },
                "momo_secret_key": {
                    "bsonType": "string"
                },
                "momo_partner_code": {
                    "bsonType": "string"
                },
                "zlpay_app_id": {
                    "bsonType": "string"
                },
                "zlpay_app_user": {
                    "bsonType": "string"
                },
                "zlpay_key1": {
                    "bsonType": "string"
                },
                "zlpay_key2": {
                    "bsonType": "string"
                }
            },
            "additionalProperties": true,
            "oneOf": [
                {
                    "bsonType": "object",
                    "properties": {
                        "device_id": {
                            "bsonType": "array",
                            "additionalItems": true
                        }
                    },
                    "additionalProperties": true
                },
                {
                    "bsonType": "object",
                    "properties": {
                        "device_id": {
                            "bsonType": "null"
                        }
                    },
                    "additionalProperties": true
                }
            ],
            "required": [
                "_id",
                "created_at",
                "updated_at",
                "name",
                "email",
                "information",
                "password",
                "activated",
                "expired_at",
                "momo_access_key",
                "momo_secret_key",
                "momo_partner_code",
                "zlpay_app_id",
                "zlpay_app_user",
                "zlpay_key1",
                "zlpay_key2"
            ]
        }
    },
    "validationLevel": "off",
    "validationAction": "warn"
});
db.vendor.createIndex(
{
    "_id": 1
},
{
    "name": "_id_"
}
);

```

### <a id="5e05cba1-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.11 Collection **vendor\_contract**

##### 2.1.2.11.1 **vendor\_contract** Tree Diagram

![Hackolade image](/erd/image133.png?raw=true)

##### 2.1.2.11.2 **vendor\_contract** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Collection name</td><td>vendor_contract</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Database</td><td><a href=#5eb3bee0-5a25-11eb-a046-d590fdb8e2e4>sunpay</a></td></tr><tr><td>Capped</td><td></td></tr><tr><td>Size</td><td></td></tr><tr><td>Max</td><td></td></tr><tr><td>Storage engine</td><td>WiredTiger</td></tr><tr><td>Config String</td><td></td></tr><tr><td>Validation level</td><td>Off</td></tr><tr><td>Validation action</td><td>Warn</td></tr><tr><td>Additional properties</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.11.3 **vendor\_contract** Fields

<table><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#5dfd8e66-5a25-11eb-a046-d590fdb8e2e4>_id</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e67-5a25-11eb-a046-d590fdb8e2e4>created_at</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e6e-5a25-11eb-a046-d590fdb8e2e4>updated_at</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e6b-5a25-11eb-a046-d590fdb8e2e4>name</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e6a-5a25-11eb-a046-d590fdb8e2e4>information</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e6d-5a25-11eb-a046-d590fdb8e2e4>renew_price</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e6c-5a25-11eb-a046-d590fdb8e2e4>price</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e69-5a25-11eb-a046-d590fdb8e2e4>expired_at</a></td><td class="no-break-word">integer32</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e68-5a25-11eb-a046-d590fdb8e2e4>device_id</a></td><td class="no-break-word">null</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#5dfd8e6f-5a25-11eb-a046-d590fdb8e2e4>vendor_id</a></td><td class="no-break-word">string</td><td>true</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e66-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.11.3.1 Field **\_id**

##### 2.1.2.11.3.1.1 **\_id** Tree Diagram

![Hackolade image](/erd/image134.png?raw=true)

##### 2.1.2.11.3.1.2 **\_id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>_id</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>XW8jsBwLOr9FJ1VNRS5B</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e67-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.11.3.2 Field **created\_at**

##### 2.1.2.11.3.2.1 **created\_at** Tree Diagram

![Hackolade image](/erd/image135.png?raw=true)

##### 2.1.2.11.3.2.2 **created\_at** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>created_at</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>1610383446</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e6e-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.11.3.3 Field **updated\_at**

##### 2.1.2.11.3.3.1 **updated\_at** Tree Diagram

![Hackolade image](/erd/image136.png?raw=true)

##### 2.1.2.11.3.3.2 **updated\_at** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>updated_at</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>1610384690</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e6b-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.11.3.4 Field **name**

##### 2.1.2.11.3.4.1 **name** Tree Diagram

![Hackolade image](/erd/image137.png?raw=true)

##### 2.1.2.11.3.4.2 **name** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>name</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>dsadas</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e6a-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.11.3.5 Field **information**

##### 2.1.2.11.3.5.1 **information** Tree Diagram

![Hackolade image](/erd/image138.png?raw=true)

##### 2.1.2.11.3.5.2 **information** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>information</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>cfsdv</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e6d-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.11.3.6 Field **renew\_price**

##### 2.1.2.11.3.6.1 **renew\_price** Tree Diagram

![Hackolade image](/erd/image139.png?raw=true)

##### 2.1.2.11.3.6.2 **renew\_price** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>renew_price</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>10000</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e6c-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.11.3.7 Field **price**

##### 2.1.2.11.3.7.1 **price** Tree Diagram

![Hackolade image](/erd/image140.png?raw=true)

##### 2.1.2.11.3.7.2 **price** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>price</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>10000000</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e69-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.11.3.8 Field **expired\_at**

##### 2.1.2.11.3.8.1 **expired\_at** Tree Diagram

![Hackolade image](/erd/image141.png?raw=true)

##### 2.1.2.11.3.8.2 **expired\_at** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>expired_at</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>numeric</td></tr><tr><td>Subtype</td><td>integer32</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Unit</td><td></td></tr><tr><td>Min value</td><td></td></tr><tr><td>Excl min</td><td></td></tr><tr><td>Max value</td><td></td></tr><tr><td>Excl max</td><td></td></tr><tr><td>Multiple of</td><td></td></tr><tr><td>Divisible by</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>1614877200</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e68-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.11.3.9 Field **device\_id**

##### 2.1.2.11.3.9.1 **device\_id** Tree Diagram

![Hackolade image](/erd/image142.png?raw=true)

##### 2.1.2.11.3.9.2 **device\_id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>device_id</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>null</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="5dfd8e6f-5a25-11eb-a046-d590fdb8e2e4"></a>2.1.2.11.3.10 Field **vendor\_id**

##### 2.1.2.11.3.10.1 **vendor\_id** Tree Diagram

![Hackolade image](/erd/image143.png?raw=true)

##### 2.1.2.11.3.10.2 **vendor\_id** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>vendor_id</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Type</td><td>string</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependencies</td><td></td></tr><tr><td>Required</td><td>true</td></tr><tr><td>Primary key</td><td>false</td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Default</td><td></td></tr><tr><td>Min length</td><td></td></tr><tr><td>Max length</td><td></td></tr><tr><td>Pattern</td><td></td></tr><tr><td>Format</td><td></td></tr><tr><td>Enum</td><td></td></tr><tr><td>Sample</td><td>k5pUxlem59E5xuy7ws76</td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.11.4 **vendor\_contract** Indexes

<table class="index-table"><thead><tr><td class="table-property-column">Property</td><td class="table-column-property">_id_</td></tr></thead><tbody><tr><td>Name</td><td class="table-column-indexes">_id_</td></tr><tr><td>Key</td><td class="table-column-indexes">_id('ascending')</td></tr><tr><td>Hashed</td><td class="table-column-indexes"></td></tr><tr><td>Unique</td><td class="table-column-indexes"></td></tr><tr><td>Drop duplicates</td><td class="table-column-indexes"></td></tr><tr><td>Sparse</td><td class="table-column-indexes"></td></tr><tr><td>Background indexing</td><td class="table-column-indexes"></td></tr><tr><td>Partial filter exp</td><td class="table-column-indexes"></td></tr><tr><td>Expire after (seconds)</td><td class="table-column-indexes"></td></tr><tr><td>Storage engine</td><td class="table-column-indexes"></td></tr><tr><td>Comments</td><td class="table-column-indexes"></td></tr></tbody></table>

##### 2.1.2.11.5 **vendor\_contract** JSON Schema

```
{
    "$schema": "http://json-schema.org/draft-04/schema#",
    "type": "object",
    "title": "vendor_contract",
    "properties": {
        "_id": {
            "type": "string"
        },
        "created_at": {
            "type": "integer"
        },
        "updated_at": {
            "type": "integer"
        },
        "name": {
            "type": "string"
        },
        "information": {
            "type": "string"
        },
        "renew_price": {
            "type": "integer"
        },
        "price": {
            "type": "integer"
        },
        "expired_at": {
            "type": "integer"
        },
        "device_id": {
            "type": "null"
        },
        "vendor_id": {
            "type": "string"
        }
    },
    "required": [
        "_id",
        "created_at",
        "updated_at",
        "name",
        "information",
        "renew_price",
        "price",
        "expired_at",
        "vendor_id"
    ]
}
```

##### 2.1.2.11.6 **vendor\_contract** JSON data

```
{
    "_id": "XW8jsBwLOr9FJ1VNRS5B",
    "created_at": 1610383446,
    "updated_at": 1610384690,
    "name": "dsadas",
    "information": "cfsdv",
    "renew_price": 10000,
    "price": 10000000,
    "expired_at": 1614877200,
    "device_id": null,
    "vendor_id": "k5pUxlem59E5xuy7ws76"
}
```

##### 2.1.2.11.7 **vendor\_contract** Target Script

```
use sunpay;

db.createCollection( "vendor_contract",{
    "storageEngine": {
        "wiredTiger": {}
    },
    "capped": false,
    "validator": {
        "$jsonSchema": {
            "bsonType": "object",
            "title": "vendor_contract",
            "properties": {
                "_id": {
                    "bsonType": "string"
                },
                "created_at": {
                    "bsonType": "int"
                },
                "updated_at": {
                    "bsonType": "int"
                },
                "name": {
                    "bsonType": "string"
                },
                "information": {
                    "bsonType": "string"
                },
                "renew_price": {
                    "bsonType": "int"
                },
                "price": {
                    "bsonType": "int"
                },
                "expired_at": {
                    "bsonType": "int"
                },
                "device_id": {
                    "bsonType": "null"
                },
                "vendor_id": {
                    "bsonType": "string"
                }
            },
            "required": [
                "_id",
                "created_at",
                "updated_at",
                "name",
                "information",
                "renew_price",
                "price",
                "expired_at",
                "vendor_id"
            ]
        }
    },
    "validationLevel": "off",
    "validationAction": "warn"
});
db.vendor_contract.createIndex(
{
    "_id": 1
},
{
    "name": "_id_"
}
);

```

### <a id="edges"></a>