# Hidden costs of coffee 
**Concept:**
Dr. Gino Baudry (EPFL, gino.baudry[at]epfl.ch)

## Setup

Install <a href="https://www.knime.com/downloads" target="_blank">KNIME Analytics platform</a> (recommended version 4.6 or higher)

## KNIME workspace
Run KNIME as an administrator and choose a Workspace. This can be setup at your convenience, but you must put the repository at the root of your Workspace. 

## Code
Open the workflow in KNIME (workflow\hidden-costs-coffee-git). 

## Data
Input and unprocesseced data can be found in \data.
Ouput data can be exported using the Excel writer node in the workflow (configure the write path first in the node) 
Blue nodes aima to visualise the data (right click: interactive node)

## Computation
Click right on any node and execute the flow, or execute all at once.

## Debug 
Should reader nodes fail, ensure that the path of the CSV readers is right (data can be found in \data)
Same goes for dictionaries (dictionary can be found in \data\dictonary)
