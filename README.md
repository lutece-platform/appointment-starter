# Appointment starter

## Introduction

The "Appointment Starter" package offers a pre-selected set of Lutece plugins focused on appointments, providing the following features:

 
* Appointment management
* ​​Process management for handling form responses
* Assignment of these responses to entities or administrators
* Generation of PDF, CSV, and other files
* Sending notifications
* All basic Lutece features (user management, permissions, roles, profiles, etc.)
* etc.

The "Appointment Starter" package can be used directly or as a starting point for building a more complete Lutece site by adding other necessary plugins related to:

 
* authentication type
* statistical tracking
* specific business functionalities
* etc.

## Configuration

Declare the Appointment Starter as a dependency in the lutece site pom.xml

```

<dependency>
	<groupId>fr.paris.lutece.starters</groupId>
	<artifactId>appointment-starter</artifactId>
	<version>[x.y.z]</version>
	<type>jar</type>
</dependency>

```

## Usage

 **DB generation** 

To create Database automatically, activate the liquibase engine by overriding the property :

```

liquibase.enabled.at.startup=true

```


[Maven documentation and reports](https://dev.lutece.paris.fr/plugins/forms-starter/)




