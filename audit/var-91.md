# Chain Variable Transaction 91

## Changes

This transaction adds preliminary support for POC-V11 region parameters, updates data_aggregation_version and election_version.

## Version threshold

None

## Transaction

```
[{1081857,
  [{blockchain_txn_vars_v1_pb,[{blockchain_var_v1_pb,"data_aggregation_version",
                                                     "int",<<"3">>},
                               {blockchain_var_v1_pb,"election_version","int",<<"6">>},
                               {blockchain_var_v1_pb,"region_as923_1_params","binary",
                                                     <<10,53,8,128,212,155,184,3,16,200,208,7,24,160,1,34,38,
                                                       10,4,8,6,16,25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,
                                                       16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,2,10,53,8,192,
                                                       238,167,184,3,16,200,208,7,24,160,1,34,38,10,4,8,6,16,
                                                       25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,
                                                       2,16,139,1,10,5,8,1,16,128,2,10,53,8,128,137,180,184,3,
                                                       16,200,208,7,24,160,1,34,38,10,4,8,6,16,25,10,4,8,5,16,
                                                       25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,139,1,10,
                                                       5,8,1,16,128,2,10,53,8,192,163,192,184,3,16,200,208,7,
                                                       24,160,1,34,38,10,4,8,6,16,25,10,4,8,5,16,25,10,4,8,4,
                                                       16,25,10,4,8,3,16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,
                                                       2,10,53,8,128,190,204,184,3,16,200,208,7,24,160,1,34,
                                                       38,10,4,8,6,16,25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,
                                                       3,16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,2,10,53,8,
                                                       192,216,216,184,3,16,200,208,7,24,160,1,34,38,10,4,8,6,
                                                       16,25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,10,
                                                       5,8,2,16,139,1,10,5,8,1,16,128,2,10,53,8,128,243,228,
                                                       184,3,16,200,208,7,24,160,1,34,38,10,4,8,6,16,25,10,4,
                                                       8,5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,
                                                       139,1,10,5,8,1,16,128,2,10,53,8,192,141,241,184,3,16,
                                                       200,208,7,24,160,1,34,38,10,4,8,6,16,25,10,4,8,5,16,25,
                                                       10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,139,1,10,5,8,
                                                       1,16,128,2>>},
                               {blockchain_var_v1_pb,"region_as923_2_params","binary",
                                                     <<10,53,8,192,229,173,183,3,16,200,208,7,24,160,1,34,38,
                                                       10,4,8,6,16,25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,
                                                       16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,2,10,53,8,128,
                                                       128,186,183,3,16,200,208,7,24,160,1,34,38,10,4,8,6,16,
                                                       25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,
                                                       2,16,139,1,10,5,8,1,16,128,2,10,53,8,192,154,198,183,3,
                                                       16,200,208,7,24,160,1,34,38,10,4,8,6,16,25,10,4,8,5,16,
                                                       25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,139,1,10,
                                                       5,8,1,16,128,2,10,53,8,128,181,210,183,3,16,200,208,7,
                                                       24,160,1,34,38,10,4,8,6,16,25,10,4,8,5,16,25,10,4,8,4,
                                                       16,25,10,4,8,3,16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,
                                                       2,10,53,8,192,207,222,183,3,16,200,208,7,24,160,1,34,
                                                       38,10,4,8,6,16,25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,
                                                       3,16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,2,10,53,8,
                                                       128,234,234,183,3,16,200,208,7,24,160,1,34,38,10,4,8,6,
                                                       16,25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,10,
                                                       5,8,2,16,139,1,10,5,8,1,16,128,2,10,53,8,192,132,247,
                                                       183,3,16,200,208,7,24,160,1,34,38,10,4,8,6,16,25,10,4,
                                                       8,5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,
                                                       139,1,10,5,8,1,16,128,2,10,53,8,128,159,131,184,3,16,
                                                       200,208,7,24,160,1,34,38,10,4,8,6,16,25,10,4,8,5,16,25,
                                                       10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,139,1,10,5,8,
                                                       1,16,128,2>>},
                               {blockchain_var_v1_pb,"region_as923_3_params","binary",
                                                     <<10,53,8,192,233,136,181,3,16,200,208,7,24,160,1,34,38,
                                                       10,4,8,6,16,25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,
                                                       16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,2,10,53,8,128,
                                                       132,149,181,3,16,200,208,7,24,160,1,34,38,10,4,8,6,16,
                                                       25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,
                                                       2,16,139,1,10,5,8,1,16,128,2,10,53,8,192,158,161,181,3,
                                                       16,200,208,7,24,160,1,34,38,10,4,8,6,16,25,10,4,8,5,16,
                                                       25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,139,1,10,
                                                       5,8,1,16,128,2,10,53,8,128,185,173,181,3,16,200,208,7,
                                                       24,160,1,34,38,10,4,8,6,16,25,10,4,8,5,16,25,10,4,8,4,
                                                       16,25,10,4,8,3,16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,
                                                       2,10,53,8,192,211,185,181,3,16,200,208,7,24,160,1,34,
                                                       38,10,4,8,6,16,25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,
                                                       3,16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,2,10,53,8,
                                                       128,238,197,181,3,16,200,208,7,24,160,1,34,38,10,4,8,6,
                                                       16,25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,10,
                                                       5,8,2,16,139,1,10,5,8,1,16,128,2,10,53,8,192,136,210,
                                                       181,3,16,200,208,7,24,160,1,34,38,10,4,8,6,16,25,10,4,
                                                       8,5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,
                                                       139,1,10,5,8,1,16,128,2,10,53,8,128,163,222,181,3,16,
                                                       200,208,7,24,160,1,34,38,10,4,8,6,16,25,10,4,8,5,16,25,
                                                       10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,139,1,10,5,8,
                                                       1,16,128,2>>},
                               {blockchain_var_v1_pb,"region_as923_4_params","binary",
                                                     <<10,53,8,160,198,179,181,3,16,200,208,7,24,160,1,34,38,
                                                       10,4,8,6,16,25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,
                                                       16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,2,10,53,8,224,
                                                       224,191,181,3,16,200,208,7,24,160,1,34,38,10,4,8,6,16,
                                                       25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,
                                                       2,16,139,1,10,5,8,1,16,128,2,10,53,8,160,251,203,181,3,
                                                       16,200,208,7,24,160,1,34,38,10,4,8,6,16,25,10,4,8,5,16,
                                                       25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,139,1,10,
                                                       5,8,1,16,128,2,10,53,8,224,149,216,181,3,16,200,208,7,
                                                       24,160,1,34,38,10,4,8,6,16,25,10,4,8,5,16,25,10,4,8,4,
                                                       16,25,10,4,8,3,16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,
                                                       2,10,53,8,160,176,228,181,3,16,200,208,7,24,160,1,34,
                                                       38,10,4,8,6,16,25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,
                                                       3,16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,2,10,53,8,
                                                       224,202,240,181,3,16,200,208,7,24,160,1,34,38,10,4,8,6,
                                                       16,25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,10,
                                                       5,8,2,16,139,1,10,5,8,1,16,128,2,10,53,8,160,229,252,
                                                       181,3,16,200,208,7,24,160,1,34,38,10,4,8,6,16,25,10,4,
                                                       8,5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,
                                                       139,1,10,5,8,1,16,128,2,10,53,8,224,255,136,182,3,16,
                                                       200,208,7,24,160,1,34,38,10,4,8,6,16,25,10,4,8,5,16,25,
                                                       10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,139,1,10,5,8,
                                                       1,16,128,2>>},
                               {blockchain_var_v1_pb,"region_au915_params","binary", 
                                                     <<10,53,8,128,132,149,181,3,16,200,208,7,24,172,2,34,38,
                                                       10,4,8,6,16,25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,
                                                       16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,2,10,53,8,192,
                                                       158,161,181,3,16,200,208,7,24,172,2,34,38,10,4,8,6,16,
                                                       25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,
                                                       2,16,139,1,10,5,8,1,16,128,2,10,53,8,128,185,173,181,3,
                                                       16,200,208,7,24,172,2,34,38,10,4,8,6,16,25,10,4,8,5,16,
                                                       25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,139,1,10,
                                                       5,8,1,16,128,2,10,53,8,192,211,185,181,3,16,200,208,7,
                                                       24,172,2,34,38,10,4,8,6,16,25,10,4,8,5,16,25,10,4,8,4,
                                                       16,25,10,4,8,3,16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,
                                                       2,10,53,8,128,238,197,181,3,16,200,208,7,24,172,2,34,
                                                       38,10,4,8,6,16,25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,
                                                       3,16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,2,10,53,8,
                                                       192,136,210,181,3,16,200,208,7,24,172,2,34,38,10,4,8,6,
                                                       16,25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,10,
                                                       5,8,2,16,139,1,10,5,8,1,16,128,2,10,53,8,128,163,222,
                                                       181,3,16,200,208,7,24,172,2,34,38,10,4,8,6,16,25,10,4,
                                                       8,5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,
                                                       139,1,10,5,8,1,16,128,2,10,53,8,192,189,234,181,3,16,
                                                       200,208,7,24,172,2,34,38,10,4,8,6,16,25,10,4,8,5,16,25,
                                                       10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,139,1,10,5,8,
                                                       1,16,128,2>>},
                               {blockchain_var_v1_pb,"region_cn470_params","binary",
                                                     <<10,53,8,224,178,241,231,1,16,200,208,7,24,191,1,34,38,
                                                       10,4,8,6,16,25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,
                                                       16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,2,10,53,8,160,
                                                       205,253,231,1,16,200,208,7,24,191,1,34,38,10,4,8,6,16,
                                                       25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,
                                                       2,16,139,1,10,5,8,1,16,128,2,10,53,8,224,231,137,232,1,
                                                       16,200,208,7,24,191,1,34,38,10,4,8,6,16,25,10,4,8,5,16,
                                                       25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,139,1,10,
                                                       5,8,1,16,128,2,10,53,8,160,130,150,232,1,16,200,208,7,
                                                       24,191,1,34,38,10,4,8,6,16,25,10,4,8,5,16,25,10,4,8,4,
                                                       16,25,10,4,8,3,16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,
                                                       2,10,53,8,224,156,162,232,1,16,200,208,7,24,191,1,34,
                                                       38,10,4,8,6,16,25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,
                                                       3,16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,2,10,53,8,
                                                       160,183,174,232,1,16,200,208,7,24,191,1,34,38,10,4,8,6,
                                                       16,25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,10,
                                                       5,8,2,16,139,1,10,5,8,1,16,128,2,10,53,8,224,209,186,
                                                       232,1,16,200,208,7,24,191,1,34,38,10,4,8,6,16,25,10,4,
                                                       8,5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,
                                                       139,1,10,5,8,1,16,128,2,10,53,8,160,236,198,232,1,16,
                                                       200,208,7,24,191,1,34,38,10,4,8,6,16,25,10,4,8,5,16,25,
                                                       10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,139,1,10,5,8,
                                                       1,16,128,2>>},
                               {blockchain_var_v1_pb,"region_eu433_params","binary",
                                                     <<10,51,8,252,241,211,20,16,200,208,7,24,121,34,38,10,4,
                                                       8,6,16,25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,
                                                       10,5,8,2,16,139,1,10,5,8,1,16,128,2,10,51,8,156,142,
                                                       213,20,16,200,208,7,24,121,34,38,10,4,8,6,16,25,10,4,8,
                                                       5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,139,
                                                       1,10,5,8,1,16,128,2,10,51,8,188,170,214,20,16,200,208,
                                                       7,24,121,34,38,10,4,8,6,16,25,10,4,8,5,16,25,10,4,8,4,
                                                       16,25,10,4,8,3,16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,
                                                       2>>},
                               {blockchain_var_v1_pb,"region_eu868_params","binary",
                                                     <<10,35,8,224,202,187,157,3,16,200,208,7,24,161,1,34,20,
                                                       10,4,8,6,16,65,10,5,8,3,16,129,1,10,5,8,2,16,238,1,10,
                                                       35,8,160,229,199,157,3,16,200,208,7,24,161,1,34,20,10,
                                                       4,8,6,16,65,10,5,8,3,16,129,1,10,5,8,2,16,238,1,10,35,
                                                       8,224,255,211,157,3,16,200,208,7,24,161,1,34,20,10,4,8,
                                                       6,16,65,10,5,8,3,16,129,1,10,5,8,2,16,238,1,10,35,8,
                                                       160,154,224,157,3,16,200,208,7,24,161,1,34,20,10,4,8,6,
                                                       16,65,10,5,8,3,16,129,1,10,5,8,2,16,238,1,10,35,8,224,
                                                       180,236,157,3,16,200,208,7,24,161,1,34,20,10,4,8,6,16,
                                                       65,10,5,8,3,16,129,1,10,5,8,2,16,238,1,10,35,8,160,207,
                                                       248,157,3,16,200,208,7,24,161,1,34,20,10,4,8,6,16,65,
                                                       10,5,8,3,16,129,1,10,5,8,2,16,238,1,10,35,8,224,233,
                                                       132,158,3,16,200,208,7,24,161,1,34,20,10,4,8,6,16,65,
                                                       10,5,8,3,16,129,1,10,5,8,2,16,238,1,10,35,8,160,132,
                                                       145,158,3,16,200,208,7,24,161,1,34,20,10,4,8,6,16,65,
                                                       10,5,8,3,16,129,1,10,5,8,2,16,238,1>>},
                               {blockchain_var_v1_pb,"region_in865_params","binary",
                                                     <<10,53,8,228,156,191,156,3,16,200,208,7,24,172,2,34,38,
                                                       10,4,8,6,16,25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,
                                                       16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,2,10,53,8,132,
                                                       253,211,156,3,16,200,208,7,24,172,2,34,38,10,4,8,6,16,
                                                       25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,
                                                       2,16,139,1,10,5,8,1,16,128,2,10,53,8,232,195,247,156,3,
                                                       16,200,208,7,24,172,2,34,38,10,4,8,6,16,25,10,4,8,5,16,
                                                       25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,139,1,10,
                                                       5,8,1,16,128,2>>},
                               {blockchain_var_v1_pb,"region_kr920_params","binary",
                                                     <<10,53,8,160,194,216,183,3,16,200,208,7,24,140,1,34,38,
                                                       10,4,8,6,16,25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,
                                                       16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,2,10,53,8,224,
                                                       220,228,183,3,16,200,208,7,24,140,1,34,38,10,4,8,6,16,
                                                       25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,
                                                       2,16,139,1,10,5,8,1,16,128,2,10,53,8,160,247,240,183,3,
                                                       16,200,208,7,24,140,1,34,38,10,4,8,6,16,25,10,4,8,5,16,
                                                       25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,139,1,10,
                                                       5,8,1,16,128,2,10,53,8,224,145,253,183,3,16,200,208,7,
                                                       24,140,1,34,38,10,4,8,6,16,25,10,4,8,5,16,25,10,4,8,4,
                                                       16,25,10,4,8,3,16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,
                                                       2,10,53,8,160,172,137,184,3,16,200,208,7,24,140,1,34,
                                                       38,10,4,8,6,16,25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,
                                                       3,16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,2,10,53,8,
                                                       224,198,149,184,3,16,200,208,7,24,140,1,34,38,10,4,8,6,
                                                       16,25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,10,
                                                       5,8,2,16,139,1,10,5,8,1,16,128,2,10,53,8,160,225,161,
                                                       184,3,16,200,208,7,24,140,1,34,38,10,4,8,6,16,25,10,4,
                                                       8,5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,
                                                       139,1,10,5,8,1,16,128,2>>},
                               {blockchain_var_v1_pb,"region_ru864_params","binary",
                                                     <<10,53,8,160,189,132,156,3,16,200,208,7,24,160,1,34,38,
                                                       10,4,8,6,16,25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,
                                                       16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,2,10,53,8,224,
                                                       215,144,156,3,16,200,208,7,24,160,1,34,38,10,4,8,6,16,
                                                       25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,
                                                       2,16,139,1,10,5,8,1,16,128,2,10,53,8,160,242,156,156,3,
                                                       16,200,208,7,24,160,1,34,38,10,4,8,6,16,25,10,4,8,5,16,
                                                       25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,139,1,10,
                                                       5,8,1,16,128,2,10,53,8,224,140,169,156,3,16,200,208,7,
                                                       24,160,1,34,38,10,4,8,6,16,25,10,4,8,5,16,25,10,4,8,4,
                                                       16,25,10,4,8,3,16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,
                                                       2,10,53,8,160,167,181,156,3,16,200,208,7,24,160,1,34,
                                                       38,10,4,8,6,16,25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,
                                                       3,16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,2,10,53,8,
                                                       160,185,169,158,3,16,200,208,7,24,160,1,34,38,10,4,8,6,
                                                       16,25,10,4,8,5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,10,
                                                       5,8,2,16,139,1,10,5,8,1,16,128,2,10,53,8,224,211,181,
                                                       158,3,16,200,208,7,24,160,1,34,38,10,4,8,6,16,25,10,4,
                                                       8,5,16,25,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,
                                                       139,1,10,5,8,1,16,128,2>>},
                               {blockchain_var_v1_pb,"region_us915_params","binary",
                                                     <<10,41,8,224,214,129,175,3,16,200,208,7,24,232,2,34,26,
                                                       10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,139,1,10,5,8,
                                                       1,16,128,2,10,41,8,160,241,141,175,3,16,200,208,7,24,
                                                       232,2,34,26,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,
                                                       139,1,10,5,8,1,16,128,2,10,41,8,224,139,154,175,3,16,
                                                       200,208,7,24,232,2,34,26,10,4,8,4,16,25,10,4,8,3,16,67,
                                                       10,5,8,2,16,139,1,10,5,8,1,16,128,2,10,41,8,160,166,
                                                       166,175,3,16,200,208,7,24,232,2,34,26,10,4,8,4,16,25,
                                                       10,4,8,3,16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,2,10,
                                                       41,8,224,192,178,175,3,16,200,208,7,24,232,2,34,26,10,
                                                       4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,139,1,10,5,8,1,
                                                       16,128,2,10,41,8,160,219,190,175,3,16,200,208,7,24,232,
                                                       2,34,26,10,4,8,4,16,25,10,4,8,3,16,67,10,5,8,2,16,139,
                                                       1,10,5,8,1,16,128,2,10,41,8,224,245,202,175,3,16,200,
                                                       208,7,24,232,2,34,26,10,4,8,4,16,25,10,4,8,3,16,67,10,
                                                       5,8,2,16,139,1,10,5,8,1,16,128,2,10,41,8,160,144,215,
                                                       175,3,16,200,208,7,24,232,2,34,26,10,4,8,4,16,25,10,4,
                                                       8,3,16,67,10,5,8,2,16,139,1,10,5,8,1,16,128,2>>},
                               {blockchain_var_v1_pb,"regulatory_regions","binary",
                                                     <<"region_as923_1,region_as923_2,region_as923_3,region_as923_4,region_au915,region_cn470,region_eu433,region_eu868,region_in865,region_kr920,region_ru864,region_us915">>}],
                              0,
                              <<48,69,2,33,0,165,28,12,87,134,87,50,50,59,97,231,5,48,
                                208,102,141,190,206,182,215,47,104,210,167,19,112,235,
                                68,211,119,213,204,2,32,5,174,213,179,227,22,15,149,77,
                                85,238,184,35,160,213,133,231,218,145,24,126,40,102,137,
                                23,76,162,60,3,150,132,27>>,
                              <<>>,<<>>,[],[],91,[],[],[]}]}]
```

## Acceptance block

1081857

## Acceptance block time

Tue Nov  2 11:17:48 PM UTC 2021
