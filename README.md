# vector_configs
Configuration files and VRL script for useful log files, data sources, and forensic artifacts. Used with vector.dev

# VRL Scripts

## 1. Azure NSG Flow Logs

Samples: https://learn.microsoft.com/en-us/azure/network-watcher/nsg-flow-logs-overview

Please note this only works on V2 of NSG Flow Logs. Based on the sample for V1 given in the link above it contains a nested 'records' field that the VRL provided here does not handle.

VRL Script: [link](nsg_flow_logs.vrl)

## 2. Azure VNET Flow Logs

Samples: https://learn.microsoft.com/en-us/azure/network-watcher/vnet-flow-logs-overview

VRL Script: [link](vnet_flow_logs.vrl)