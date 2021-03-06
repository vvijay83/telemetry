# Network Event Description

This data-set is generated from one router (leaf7) in the Telemetry lab. 
The data-set was created by retrieving several MDT collections with a
cadence of 10s over a period of 5 hours and 28 minutes.

## Collected YANG paths

The Yang paths collected in this data-set are as follows:

  - Cisco-IOS-XR-nto-misc-oper:memory-summary/nodes/node/summary → 1 csv file
  - Cisco-IOS-XR-wdsysmon-fd-oper:system-monitoring/cpu-utilization → 1 csv file
  - Cisco-IOS-XR-ipv6-io-oper:ipv6-io → 1 csv file
  - Cisco-IOS-XR-ipv4-io-oper:ipv4-network/nodes/node/statistics/traffic → 1 csv file
  - Cisco-IOS-XR-ip-tcp-oper:tcp → 2 csv files
    - nodes/node/statistics/ipv4-traffic
    - nodes/node/statistics/ipv6-traffic
  - Cisco-IOS-XR-fib-common-oper:fib-statistics → 1 csv files
  - Cisco-IOS-XR-ip-tcp-oper:tcp-connection → 6 csv files
    - nodes/node/brief-informations/brief-information
    - nodes/node/detail-informations/detail-information
    - nodes/node/extended-information/display-types/display-type/connection-id
    - nodes/node/statistics/clients/client
    - nodes/node/statistics/pcbs/pcb
    - nodes/node/statistics/summary
  - Cisco-IOS-XR-ip-tcp-oper:tcp-nsr → 7 csv files
    - nodes/node/client/brief-clients/brief-client
    - nodes/node/client/detail-clients/detail-client
    - nodes/node/session-set/brief-sets/brief-set
    - nodes/node/session-set/detail-sets/detail-set
    - nodes/node/statistics/statistic-clients/statistic-client
    - nodes/node/statistics/statistic-sets/statistic-set
    - nodes/node/statistics/summary
  - Cisco-IOS-XR-ip-bfd-oper:bfd/counters → 1 csv file
  - Cisco-IOS-XR-ip-bfd-oper:bfd/session-briefs → 1 csv file
  - Cisco-IOS-XR-ip-bfd-oper:bfd/summary → 1 file
  - Cisco-IOS-XR-ip-bfd-oper:bfd/client-details/client-detail/brief → 1 csv file
  - Cisco-IOS-XR-pfi-im-cmd-oper:interfaces/interface-summary/interface-type → 1 csv file
  - Cisco-IOS-XR-pfi-im-cmd-oper:interfaces/interface-briefs/interface-brief → 1 csv file
  - Cisco-IOS-XR-pfi-im-cmd-oper:interfaces/interface-xr/interface → 1 csv file
  - Cisco-IOS-XR-ipv4-bgp-oper:bgp/instances/instance/instance-active/default-vrf/afs/af/af-process-info/global → 1 csv file
  - Cisco-IOS-XR-ipv4-bgp-oper:bgp/instances/instance/instance-active/default-vrf/process-info → 1 csv file
  - Cisco-IOS-XR-drivers-media-eth-oper:ethernet-interface/statistics/statistic → 1 csv file
  - Cisco-IOS-XR-infra-statsd-oper:infra-statistics/interfaces/interface[interface-name=Hu*] → 16 csv files
    - cache/data-rate
    - cache/generic-counters
    - cache/interfaces-mib-counters
    - cache/protocols/protocol
    - data-rate
    - generic-counters
    - interfaces-mib-counters
    - latest/data-rate
    - latest/generic-counters
    - latest/interfaces-mib-counters
    - latest/protocols/protocol
    - total/data-rate
    - total/generic-counters
    - total/interfaces-mib-counters
    - total/protocols/protocol
  - Cisco-show-bfd-all → 1 csv
  - Cisco-show-interface → 1 csv
  
 In total a dataset of 6622 features can be generated by merging the 48 mentioned csv files. Timestamps of the different collections  can be aligned using linear interpolation. Over the course of the data-collection, a set of changes were applied to the lab network: Interfaces and bi-directional forwarding detection (BFD) sessions were enabled/disabled. The corresponding timestamps for the inserted events can be found in the events csv-file. 
