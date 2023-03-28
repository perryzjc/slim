# Test Files

## Overview

This directory is designed to provide an assortment of files containing various secret types. The purpose is to verify the open-source tool detect secret's ability to detect different kinds of secrets as proposed by community members. The directory includes the types of secrets mentioned by community members in the [issue ticket](https://github.com/NASA-AMMOS/slim/issues/89) and other potential secret formats.

## Types of Secret

### Ⅰ. Secret Types Proposed by Community Members

1. AWS credential information ([ref](https://github.com/NASA-AMMOS/slim/issues/89#:~:text=AWS%20credential%20information))
2. IPs, username / passwords, ARNs, security-groups ([ref](https://github.com/NASA-AMMOS/slim/issues/89#:~:text=information%20such%20as-,IPs%2C%20username%20/%20passwords%2C%20ARNs%2C%20security%2Dgroups,-A%20GitHub%2Dside))
3. Absolute file paths ([ref](https://github.com/NASA-AMMOS/slim/issues/89#:~:text=One%20other%20idea%3A-,absolute%20file%20paths,-%2D%20not%20sure%20how))
4. sg's, vpc's, subnets, aws account numbers, ami's, bucket names, ip addresses, hostnames, roles, arn's, usernames, internal url's, and passwords. ([ref](https://github.com/NASA-AMMOS/slim/issues/89#:~:text=our%20infrastructure%20including-,sg%27s%2C%20vpc%27s%2C%20subnets%2C%20aws%20account%20numbers%2C%20ami%27s%2C%20bucket%20names%2C%20ip%20addresses%2C%20hostnames%2C%20roles%2C%20arn%27s%2C%20usernames%2C%20internal%20url%27s%2C%20and%20passwords.,-%F0%9F%91%80))

### Ⅱ. Other Types of Secrets

`detect secret` also includes built-in plugins capable of detecting other types of secrets.