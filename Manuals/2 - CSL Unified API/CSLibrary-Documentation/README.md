<a name='assembly'></a>
# CSLibrary

## Contents

[**Download Full Documentation**](./CS203X_CS463_C_Sharp_CSLibrary_API_Document.zip)

- [ACID](#T-CSLibrary-Constants-ACID 'CSLibrary.Constants.ACID')
  - [APACS](#F-CSLibrary-Constants-ACID-APACS 'CSLibrary.Constants.ACID.APACS')
  - [APACSX](#F-CSLibrary-Constants-ACID-APACSX 'CSLibrary.Constants.ACID.APACSX')
  - [GS1](#F-CSLibrary-Constants-ACID-GS1 'CSLibrary.Constants.ACID.GS1')
  - [NEN](#F-CSLibrary-Constants-ACID-NEN 'CSLibrary.Constants.ACID.NEN')
  - [UNKNOWN](#F-CSLibrary-Constants-ACID-UNKNOWN 'CSLibrary.Constants.ACID.UNKNOWN')
- [Action](#T-CSLibrary-Constants-Action 'CSLibrary.Constants.Action')
  - [ASLINVA_DSLINVB](#F-CSLibrary-Constants-Action-ASLINVA_DSLINVB 'CSLibrary.Constants.Action.ASLINVA_DSLINVB')
  - [ASLINVA_NOTHING](#F-CSLibrary-Constants-Action-ASLINVA_NOTHING 'CSLibrary.Constants.Action.ASLINVA_NOTHING')
  - [DSLINVB_ASLINVA](#F-CSLibrary-Constants-Action-DSLINVB_ASLINVA 'CSLibrary.Constants.Action.DSLINVB_ASLINVA')
  - [DSLINVB_NOTHING](#F-CSLibrary-Constants-Action-DSLINVB_NOTHING 'CSLibrary.Constants.Action.DSLINVB_NOTHING')
  - [NOTHING_ASLINVA](#F-CSLibrary-Constants-Action-NOTHING_ASLINVA 'CSLibrary.Constants.Action.NOTHING_ASLINVA')
  - [NOTHING_DSLINVB](#F-CSLibrary-Constants-Action-NOTHING_DSLINVB 'CSLibrary.Constants.Action.NOTHING_DSLINVB')
  - [NOTHING_NSLINVS](#F-CSLibrary-Constants-Action-NOTHING_NSLINVS 'CSLibrary.Constants.Action.NOTHING_NSLINVS')
  - [NSLINVS_NOTHING](#F-CSLibrary-Constants-Action-NSLINVS_NOTHING 'CSLibrary.Constants.Action.NSLINVS_NOTHING')
  - [UNKNOWN](#F-CSLibrary-Constants-Action-UNKNOWN 'CSLibrary.Constants.Action.UNKNOWN')
- [Antenna](#T-CSLibrary-Antenna 'CSLibrary.Antenna')
  - [#ctor()](#M-CSLibrary-Antenna-#ctor 'CSLibrary.Antenna.#ctor')
  - [#ctor(port)](#M-CSLibrary-Antenna-#ctor-System-UInt32- 'CSLibrary.Antenna.#ctor(System.UInt32)')
  - [#ctor(port,state,powerLevel,dwellTime,numberInventoryCycles,antennaSenseThreshold)](#M-CSLibrary-Antenna-#ctor-System-UInt32,CSLibrary-Constants-AntennaPortState,System-UInt32,System-UInt32,System-UInt32,System-UInt32,System-UInt32,System-Boolean,System-Boolean,CSLibrary-Constants-SingulationAlgorithm,System-UInt32,System-Boolean,System-UInt32,System-Boolean,System-UInt32,System-UInt32- 'CSLibrary.Antenna.#ctor(System.UInt32,CSLibrary.Constants.AntennaPortState,System.UInt32,System.UInt32,System.UInt32,System.UInt32,System.UInt32,System.Boolean,System.Boolean,CSLibrary.Constants.SingulationAlgorithm,System.UInt32,System.Boolean,System.UInt32,System.Boolean,System.UInt32,System.UInt32)')
  - [#ctor(antenna)](#M-CSLibrary-Antenna-#ctor-CSLibrary-Antenna- 'CSLibrary.Antenna.#ctor(CSLibrary.Antenna)')
  - [POWER_MAXIMUM](#F-CSLibrary-Antenna-POWER_MAXIMUM 'CSLibrary.Antenna.POWER_MAXIMUM')
  - [POWER_MINIMUM](#F-CSLibrary-Antenna-POWER_MINIMUM 'CSLibrary.Antenna.POWER_MINIMUM')
  - [RX_LOGICAL_MAXIMUM](#F-CSLibrary-Antenna-RX_LOGICAL_MAXIMUM 'CSLibrary.Antenna.RX_LOGICAL_MAXIMUM')
  - [RX_LOGICAL_MINIMUM](#F-CSLibrary-Antenna-RX_LOGICAL_MINIMUM 'CSLibrary.Antenna.RX_LOGICAL_MINIMUM')
  - [TX_LOGICAL_MAXIMUM](#F-CSLibrary-Antenna-TX_LOGICAL_MAXIMUM 'CSLibrary.Antenna.TX_LOGICAL_MAXIMUM')
  - [TX_LOGICAL_MINIMUM](#F-CSLibrary-Antenna-TX_LOGICAL_MINIMUM 'CSLibrary.Antenna.TX_LOGICAL_MINIMUM')
  - [AntennaSenseThreshold](#P-CSLibrary-Antenna-AntennaSenseThreshold 'CSLibrary.Antenna.AntennaSenseThreshold')
  - [AntennaSenseValue](#P-CSLibrary-Antenna-AntennaSenseValue 'CSLibrary.Antenna.AntennaSenseValue')
  - [DwellTime](#P-CSLibrary-Antenna-DwellTime 'CSLibrary.Antenna.DwellTime')
  - [EASAlarm](#P-CSLibrary-Antenna-EASAlarm 'CSLibrary.Antenna.EASAlarm')
  - [EnableLocalFreq](#P-CSLibrary-Antenna-EnableLocalFreq 'CSLibrary.Antenna.EnableLocalFreq')
  - [EnableLocalInv](#P-CSLibrary-Antenna-EnableLocalInv 'CSLibrary.Antenna.EnableLocalInv')
  - [EnableLocalProfile](#P-CSLibrary-Antenna-EnableLocalProfile 'CSLibrary.Antenna.EnableLocalProfile')
  - [FreqChannel](#P-CSLibrary-Antenna-FreqChannel 'CSLibrary.Antenna.FreqChannel')
  - [InventoryAlgorithm](#P-CSLibrary-Antenna-InventoryAlgorithm 'CSLibrary.Antenna.InventoryAlgorithm')
  - [LinkProfile](#P-CSLibrary-Antenna-LinkProfile 'CSLibrary.Antenna.LinkProfile')
  - [NumberInventoryCycles](#P-CSLibrary-Antenna-NumberInventoryCycles 'CSLibrary.Antenna.NumberInventoryCycles')
  - [PhysicalRxPort](#P-CSLibrary-Antenna-PhysicalRxPort 'CSLibrary.Antenna.PhysicalRxPort')
  - [PhysicalTxPort](#P-CSLibrary-Antenna-PhysicalTxPort 'CSLibrary.Antenna.PhysicalTxPort')
  - [Port](#P-CSLibrary-Antenna-Port 'CSLibrary.Antenna.Port')
  - [PowerLevel](#P-CSLibrary-Antenna-PowerLevel 'CSLibrary.Antenna.PowerLevel')
  - [StartQ](#P-CSLibrary-Antenna-StartQ 'CSLibrary.Antenna.StartQ')
  - [State](#P-CSLibrary-Antenna-State 'CSLibrary.Antenna.State')
  - [Copy(from)](#M-CSLibrary-Antenna-Copy-CSLibrary-Antenna- 'CSLibrary.Antenna.Copy(CSLibrary.Antenna)')
  - [Equals(obj)](#M-CSLibrary-Antenna-Equals-System-Object- 'CSLibrary.Antenna.Equals(System.Object)')
  - [Equals(rhs)](#M-CSLibrary-Antenna-Equals-CSLibrary-Antenna- 'CSLibrary.Antenna.Equals(CSLibrary.Antenna)')
  - [GetHashCode()](#M-CSLibrary-Antenna-GetHashCode 'CSLibrary.Antenna.GetHashCode')
  - [Load(transport)](#M-CSLibrary-Antenna-Load-CSLibrary-HighLevelInterface- 'CSLibrary.Antenna.Load(CSLibrary.HighLevelInterface)')
  - [Store(transport)](#M-CSLibrary-Antenna-Store-CSLibrary-HighLevelInterface- 'CSLibrary.Antenna.Store(CSLibrary.HighLevelInterface)')
- [AntennaConfig](#T-CSLibrary-AntennaConfig 'CSLibrary.AntennaConfig')
  - [#ctor(port)](#M-CSLibrary-AntennaConfig-#ctor-System-UInt32- 'CSLibrary.AntennaConfig.#ctor(System.UInt32)')
  - [#ctor(source)](#M-CSLibrary-AntennaConfig-#ctor-CSLibrary-AntennaConfig- 'CSLibrary.AntennaConfig.#ctor(CSLibrary.AntennaConfig)')
  - [AntennaSenseThreshold](#P-CSLibrary-AntennaConfig-AntennaSenseThreshold 'CSLibrary.AntennaConfig.AntennaSenseThreshold')
  - [DwellTime](#P-CSLibrary-AntennaConfig-DwellTime 'CSLibrary.AntennaConfig.DwellTime')
  - [NumberInventoryCycles](#P-CSLibrary-AntennaConfig-NumberInventoryCycles 'CSLibrary.AntennaConfig.NumberInventoryCycles')
  - [PhysicalRxPort](#P-CSLibrary-AntennaConfig-PhysicalRxPort 'CSLibrary.AntennaConfig.PhysicalRxPort')
  - [PhysicalTxPort](#P-CSLibrary-AntennaConfig-PhysicalTxPort 'CSLibrary.AntennaConfig.PhysicalTxPort')
  - [Port](#P-CSLibrary-AntennaConfig-Port 'CSLibrary.AntennaConfig.Port')
  - [PowerLevel](#P-CSLibrary-AntennaConfig-PowerLevel 'CSLibrary.AntennaConfig.PowerLevel')
  - [Copy(from)](#M-CSLibrary-AntennaConfig-Copy-CSLibrary-AntennaConfig- 'CSLibrary.AntennaConfig.Copy(CSLibrary.AntennaConfig)')
  - [Equals(obj)](#M-CSLibrary-AntennaConfig-Equals-System-Object- 'CSLibrary.AntennaConfig.Equals(System.Object)')
  - [Equals(rhs)](#M-CSLibrary-AntennaConfig-Equals-CSLibrary-AntennaConfig- 'CSLibrary.AntennaConfig.Equals(CSLibrary.AntennaConfig)')
  - [GetHashCode()](#M-CSLibrary-AntennaConfig-GetHashCode 'CSLibrary.AntennaConfig.GetHashCode')
  - [Load(transport)](#M-CSLibrary-AntennaConfig-Load-CSLibrary-HighLevelInterface- 'CSLibrary.AntennaConfig.Load(CSLibrary.HighLevelInterface)')
  - [Store(transport)](#M-CSLibrary-AntennaConfig-Store-CSLibrary-HighLevelInterface- 'CSLibrary.AntennaConfig.Store(CSLibrary.HighLevelInterface)')
- [AntennaList](#T-CSLibrary-AntennaList 'CSLibrary.AntennaList')
  - [#ctor()](#M-CSLibrary-AntennaList-#ctor 'CSLibrary.AntennaList.#ctor')
  - [#ctor(capacity)](#M-CSLibrary-AntennaList-#ctor-System-Int32- 'CSLibrary.AntennaList.#ctor(System.Int32)')
  - [#ctor(enumerable)](#M-CSLibrary-AntennaList-#ctor-System-Collections-Generic-IEnumerable{CSLibrary-Antenna}- 'CSLibrary.AntennaList.#ctor(System.Collections.Generic.IEnumerable{CSLibrary.Antenna})')
  - [#ctor(enumerable,deepCopy)](#M-CSLibrary-AntennaList-#ctor-System-Collections-Generic-IEnumerable{CSLibrary-Antenna},System-Boolean- 'CSLibrary.AntennaList.#ctor(System.Collections.Generic.IEnumerable{CSLibrary.Antenna},System.Boolean)')
  - [DEFAULT_ANTENNA_LIST](#F-CSLibrary-AntennaList-DEFAULT_ANTENNA_LIST 'CSLibrary.AntennaList.DEFAULT_ANTENNA_LIST')
- [AntennaPort](#T-CSLibrary-Constants-AntennaPort 'CSLibrary.Constants.AntennaPort')
  - [PORT_00](#F-CSLibrary-Constants-AntennaPort-PORT_00 'CSLibrary.Constants.AntennaPort.PORT_00')
  - [PORT_01](#F-CSLibrary-Constants-AntennaPort-PORT_01 'CSLibrary.Constants.AntennaPort.PORT_01')
  - [PORT_02](#F-CSLibrary-Constants-AntennaPort-PORT_02 'CSLibrary.Constants.AntennaPort.PORT_02')
  - [PORT_03](#F-CSLibrary-Constants-AntennaPort-PORT_03 'CSLibrary.Constants.AntennaPort.PORT_03')
  - [PORT_04](#F-CSLibrary-Constants-AntennaPort-PORT_04 'CSLibrary.Constants.AntennaPort.PORT_04')
  - [PORT_05](#F-CSLibrary-Constants-AntennaPort-PORT_05 'CSLibrary.Constants.AntennaPort.PORT_05')
  - [PORT_06](#F-CSLibrary-Constants-AntennaPort-PORT_06 'CSLibrary.Constants.AntennaPort.PORT_06')
  - [PORT_07](#F-CSLibrary-Constants-AntennaPort-PORT_07 'CSLibrary.Constants.AntennaPort.PORT_07')
  - [PORT_08](#F-CSLibrary-Constants-AntennaPort-PORT_08 'CSLibrary.Constants.AntennaPort.PORT_08')
  - [PORT_09](#F-CSLibrary-Constants-AntennaPort-PORT_09 'CSLibrary.Constants.AntennaPort.PORT_09')
  - [PORT_10](#F-CSLibrary-Constants-AntennaPort-PORT_10 'CSLibrary.Constants.AntennaPort.PORT_10')
  - [PORT_11](#F-CSLibrary-Constants-AntennaPort-PORT_11 'CSLibrary.Constants.AntennaPort.PORT_11')
  - [PORT_12](#F-CSLibrary-Constants-AntennaPort-PORT_12 'CSLibrary.Constants.AntennaPort.PORT_12')
  - [PORT_13](#F-CSLibrary-Constants-AntennaPort-PORT_13 'CSLibrary.Constants.AntennaPort.PORT_13')
  - [PORT_14](#F-CSLibrary-Constants-AntennaPort-PORT_14 'CSLibrary.Constants.AntennaPort.PORT_14')
  - [PORT_15](#F-CSLibrary-Constants-AntennaPort-PORT_15 'CSLibrary.Constants.AntennaPort.PORT_15')
  - [UNKNOWN](#F-CSLibrary-Constants-AntennaPort-UNKNOWN 'CSLibrary.Constants.AntennaPort.UNKNOWN')
- [AntennaPortCollections](#T-CSLibrary-Structures-AntennaPortCollections 'CSLibrary.Structures.AntennaPortCollections')
  - [#ctor()](#M-CSLibrary-Structures-AntennaPortCollections-#ctor 'CSLibrary.Structures.AntennaPortCollections.#ctor')
  - [#ctor(capacity)](#M-CSLibrary-Structures-AntennaPortCollections-#ctor-System-Int32- 'CSLibrary.Structures.AntennaPortCollections.#ctor(System.Int32)')
  - [#ctor(collection)](#M-CSLibrary-Structures-AntennaPortCollections-#ctor-System-Collections-Generic-IEnumerable{CSLibrary-Constants-AntennaPort}- 'CSLibrary.Structures.AntennaPortCollections.#ctor(System.Collections.Generic.IEnumerable{CSLibrary.Constants.AntennaPort})')
- [AntennaPortConfig](#T-CSLibrary-Structures-AntennaPortConfig 'CSLibrary.Structures.AntennaPortConfig')
  - [#ctor()](#M-CSLibrary-Structures-AntennaPortConfig-#ctor 'CSLibrary.Structures.AntennaPortConfig.#ctor')
  - [antennaSenseThreshold](#F-CSLibrary-Structures-AntennaPortConfig-antennaSenseThreshold 'CSLibrary.Structures.AntennaPortConfig.antennaSenseThreshold')
  - [dwellTime](#F-CSLibrary-Structures-AntennaPortConfig-dwellTime 'CSLibrary.Structures.AntennaPortConfig.dwellTime')
  - [length_](#F-CSLibrary-Structures-AntennaPortConfig-length_ 'CSLibrary.Structures.AntennaPortConfig.length_')
  - [numberInventoryCycles](#F-CSLibrary-Structures-AntennaPortConfig-numberInventoryCycles 'CSLibrary.Structures.AntennaPortConfig.numberInventoryCycles')
  - [physicalRxPort](#F-CSLibrary-Structures-AntennaPortConfig-physicalRxPort 'CSLibrary.Structures.AntennaPortConfig.physicalRxPort')
  - [physicalTxPort](#F-CSLibrary-Structures-AntennaPortConfig-physicalTxPort 'CSLibrary.Structures.AntennaPortConfig.physicalTxPort')
  - [powerLevel](#F-CSLibrary-Structures-AntennaPortConfig-powerLevel 'CSLibrary.Structures.AntennaPortConfig.powerLevel')
  - [length](#P-CSLibrary-Structures-AntennaPortConfig-length 'CSLibrary.Structures.AntennaPortConfig.length')
- [AntennaPortState](#T-CSLibrary-Constants-AntennaPortState 'CSLibrary.Constants.AntennaPortState')
  - [DISABLED](#F-CSLibrary-Constants-AntennaPortState-DISABLED 'CSLibrary.Constants.AntennaPortState.DISABLED')
  - [ENABLED](#F-CSLibrary-Constants-AntennaPortState-ENABLED 'CSLibrary.Constants.AntennaPortState.ENABLED')
  - [UNKNOWN](#F-CSLibrary-Constants-AntennaPortState-UNKNOWN 'CSLibrary.Constants.AntennaPortState.UNKNOWN')
- [AntennaPortStatus](#T-CSLibrary-Structures-AntennaPortStatus 'CSLibrary.Structures.AntennaPortStatus')
  - [#ctor()](#M-CSLibrary-Structures-AntennaPortStatus-#ctor 'CSLibrary.Structures.AntennaPortStatus.#ctor')
  - [antennaSenseValue](#F-CSLibrary-Structures-AntennaPortStatus-antennaSenseValue 'CSLibrary.Structures.AntennaPortStatus.antennaSenseValue')
  - [easAlarm](#F-CSLibrary-Structures-AntennaPortStatus-easAlarm 'CSLibrary.Structures.AntennaPortStatus.easAlarm')
  - [enableLocalFreq](#F-CSLibrary-Structures-AntennaPortStatus-enableLocalFreq 'CSLibrary.Structures.AntennaPortStatus.enableLocalFreq')
  - [enableLocalInv](#F-CSLibrary-Structures-AntennaPortStatus-enableLocalInv 'CSLibrary.Structures.AntennaPortStatus.enableLocalInv')
  - [enableLocalProfile](#F-CSLibrary-Structures-AntennaPortStatus-enableLocalProfile 'CSLibrary.Structures.AntennaPortStatus.enableLocalProfile')
  - [freqChn](#F-CSLibrary-Structures-AntennaPortStatus-freqChn 'CSLibrary.Structures.AntennaPortStatus.freqChn')
  - [inv_algo](#F-CSLibrary-Structures-AntennaPortStatus-inv_algo 'CSLibrary.Structures.AntennaPortStatus.inv_algo')
  - [length_](#F-CSLibrary-Structures-AntennaPortStatus-length_ 'CSLibrary.Structures.AntennaPortStatus.length_')
  - [profile](#F-CSLibrary-Structures-AntennaPortStatus-profile 'CSLibrary.Structures.AntennaPortStatus.profile')
  - [startQ](#F-CSLibrary-Structures-AntennaPortStatus-startQ 'CSLibrary.Structures.AntennaPortStatus.startQ')
  - [state](#F-CSLibrary-Structures-AntennaPortStatus-state 'CSLibrary.Structures.AntennaPortStatus.state')
  - [length](#P-CSLibrary-Structures-AntennaPortStatus-length 'CSLibrary.Structures.AntennaPortStatus.length')
- [AntennaSequenceMode](#T-CSLibrary-Constants-AntennaSequenceMode 'CSLibrary.Constants.AntennaSequenceMode')
  - [NORMAL](#F-CSLibrary-Constants-AntennaSequenceMode-NORMAL 'CSLibrary.Constants.AntennaSequenceMode.NORMAL')
  - [SEQUENCE](#F-CSLibrary-Constants-AntennaSequenceMode-SEQUENCE 'CSLibrary.Constants.AntennaSequenceMode.SEQUENCE')
  - [SEQUENCE_SMART_CHECK](#F-CSLibrary-Constants-AntennaSequenceMode-SEQUENCE_SMART_CHECK 'CSLibrary.Constants.AntennaSequenceMode.SEQUENCE_SMART_CHECK')
  - [SMART_CHECK](#F-CSLibrary-Constants-AntennaSequenceMode-SMART_CHECK 'CSLibrary.Constants.AntennaSequenceMode.SMART_CHECK')
  - [UNKNOWN](#F-CSLibrary-Constants-AntennaSequenceMode-UNKNOWN 'CSLibrary.Constants.AntennaSequenceMode.UNKNOWN')
- [AntennaStatus](#T-CSLibrary-AntennaStatus 'CSLibrary.AntennaStatus')
  - [#ctor(port)](#M-CSLibrary-AntennaStatus-#ctor-System-UInt32- 'CSLibrary.AntennaStatus.#ctor(System.UInt32)')
  - [#ctor(source)](#M-CSLibrary-AntennaStatus-#ctor-CSLibrary-AntennaStatus- 'CSLibrary.AntennaStatus.#ctor(CSLibrary.AntennaStatus)')
  - [AntennaSenseValue](#P-CSLibrary-AntennaStatus-AntennaSenseValue 'CSLibrary.AntennaStatus.AntennaSenseValue')
  - [Port](#P-CSLibrary-AntennaStatus-Port 'CSLibrary.AntennaStatus.Port')
  - [State](#P-CSLibrary-AntennaStatus-State 'CSLibrary.AntennaStatus.State')
  - [Copy(from)](#M-CSLibrary-AntennaStatus-Copy-CSLibrary-AntennaStatus- 'CSLibrary.AntennaStatus.Copy(CSLibrary.AntennaStatus)')
  - [Equals(obj)](#M-CSLibrary-AntennaStatus-Equals-System-Object- 'CSLibrary.AntennaStatus.Equals(System.Object)')
  - [Equals(rhs)](#M-CSLibrary-AntennaStatus-Equals-CSLibrary-AntennaStatus- 'CSLibrary.AntennaStatus.Equals(CSLibrary.AntennaStatus)')
  - [GetHashCode()](#M-CSLibrary-AntennaStatus-GetHashCode 'CSLibrary.AntennaStatus.GetHashCode')
  - [Load(transport)](#M-CSLibrary-AntennaStatus-Load-CSLibrary-HighLevelInterface- 'CSLibrary.AntennaStatus.Load(CSLibrary.HighLevelInterface)')
  - [Store(transport)](#M-CSLibrary-AntennaStatus-Store-CSLibrary-HighLevelInterface- 'CSLibrary.AntennaStatus.Store(CSLibrary.HighLevelInterface)')
- [AssignResult](#T-CSLibrary-Net-AssignResult 'CSLibrary.Net.AssignResult')
  - [ACCEPTED](#F-CSLibrary-Net-AssignResult-ACCEPTED 'CSLibrary.Net.AssignResult.ACCEPTED')
  - [REJECTED](#F-CSLibrary-Net-AssignResult-REJECTED 'CSLibrary.Net.AssignResult.REJECTED')
  - [STARTED](#F-CSLibrary-Net-AssignResult-STARTED 'CSLibrary.Net.AssignResult.STARTED')
  - [TIMEOUT](#F-CSLibrary-Net-AssignResult-TIMEOUT 'CSLibrary.Net.AssignResult.TIMEOUT')
  - [UNKNOWN](#F-CSLibrary-Net-AssignResult-UNKNOWN 'CSLibrary.Net.AssignResult.UNKNOWN')
- [BNK1_MSK_FILTER_CFG](#T-CSLibrary-Structures-BNK1_MSK_FILTER_CFG 'CSLibrary.Structures.BNK1_MSK_FILTER_CFG')
  - [#ctor()](#M-CSLibrary-Structures-BNK1_MSK_FILTER_CFG-#ctor 'CSLibrary.Structures.BNK1_MSK_FILTER_CFG.#ctor')
  - [#ctor()](#M-CSLibrary-Structures-BNK1_MSK_FILTER_CFG-#ctor-System-String- 'CSLibrary.Structures.BNK1_MSK_FILTER_CFG.#ctor(System.String)')
  - [#ctor(enable,match,offset,count)](#M-CSLibrary-Structures-BNK1_MSK_FILTER_CFG-#ctor-System-Boolean,System-Boolean,System-Int32,System-String- 'CSLibrary.Structures.BNK1_MSK_FILTER_CFG.#ctor(System.Boolean,System.Boolean,System.Int32,System.String)')
  - [enable](#F-CSLibrary-Structures-BNK1_MSK_FILTER_CFG-enable 'CSLibrary.Structures.BNK1_MSK_FILTER_CFG.enable')
  - [length](#F-CSLibrary-Structures-BNK1_MSK_FILTER_CFG-length 'CSLibrary.Structures.BNK1_MSK_FILTER_CFG.length')
  - [mask](#F-CSLibrary-Structures-BNK1_MSK_FILTER_CFG-mask 'CSLibrary.Structures.BNK1_MSK_FILTER_CFG.mask')
  - [match](#F-CSLibrary-Structures-BNK1_MSK_FILTER_CFG-match 'CSLibrary.Structures.BNK1_MSK_FILTER_CFG.match')
  - [offset](#F-CSLibrary-Structures-BNK1_MSK_FILTER_CFG-offset 'CSLibrary.Structures.BNK1_MSK_FILTER_CFG.offset')
- [BandState](#T-CSLibrary-Constants-BandState 'CSLibrary.Constants.BandState')
  - [DISABLE](#F-CSLibrary-Constants-BandState-DISABLE 'CSLibrary.Constants.BandState.DISABLE')
  - [ENABLE](#F-CSLibrary-Constants-BandState-ENABLE 'CSLibrary.Constants.BandState.ENABLE')
  - [UNKNOWN](#F-CSLibrary-Constants-BandState-UNKNOWN 'CSLibrary.Constants.BandState.UNKNOWN')
- [Bank](#T-CSLibrary-Constants-Bank 'CSLibrary.Constants.Bank')
  - [ACC_PWD](#F-CSLibrary-Constants-Bank-ACC_PWD 'CSLibrary.Constants.Bank.ACC_PWD')
  - [EPC](#F-CSLibrary-Constants-Bank-EPC 'CSLibrary.Constants.Bank.EPC')
  - [KILL_PWD](#F-CSLibrary-Constants-Bank-KILL_PWD 'CSLibrary.Constants.Bank.KILL_PWD')
  - [PC](#F-CSLibrary-Constants-Bank-PC 'CSLibrary.Constants.Bank.PC')
  - [SPECIAL](#F-CSLibrary-Constants-Bank-SPECIAL 'CSLibrary.Constants.Bank.SPECIAL')
  - [TID](#F-CSLibrary-Constants-Bank-TID 'CSLibrary.Constants.Bank.TID')
  - [UNKNOWN](#F-CSLibrary-Constants-Bank-UNKNOWN 'CSLibrary.Constants.Bank.UNKNOWN')
  - [USER](#F-CSLibrary-Constants-Bank-USER 'CSLibrary.Constants.Bank.USER')
- [BatteryType](#T-CSLibrary-Structures-BatteryType 'CSLibrary.Structures.BatteryType')
  - [B1_5V](#F-CSLibrary-Structures-BatteryType-B1_5V 'CSLibrary.Structures.BatteryType.B1_5V')
  - [B3V](#F-CSLibrary-Structures-BatteryType-B3V 'CSLibrary.Structures.BatteryType.B3V')
- [BlockEraseCmdParms](#T-CSLibrary-Structures-BlockEraseCmdParms 'CSLibrary.Structures.BlockEraseCmdParms')
  - [#ctor()](#M-CSLibrary-Structures-BlockEraseCmdParms-#ctor-CSLibrary-Constants-MemoryBank,System-UInt16,System-UInt16- 'CSLibrary.Structures.BlockEraseCmdParms.#ctor(CSLibrary.Constants.MemoryBank,System.UInt16,System.UInt16)')
  - [bank](#F-CSLibrary-Structures-BlockEraseCmdParms-bank 'CSLibrary.Structures.BlockEraseCmdParms.bank')
  - [count](#F-CSLibrary-Structures-BlockEraseCmdParms-count 'CSLibrary.Structures.BlockEraseCmdParms.count')
  - [offset](#F-CSLibrary-Structures-BlockEraseCmdParms-offset 'CSLibrary.Structures.BlockEraseCmdParms.offset')
- [BlockEraseParms](#T-CSLibrary-Structures-BlockEraseParms 'CSLibrary.Structures.BlockEraseParms')
- [BlockWriteCmdParms](#T-CSLibrary-Structures-BlockWriteCmdParms 'CSLibrary.Structures.BlockWriteCmdParms')
  - [#ctor()](#M-CSLibrary-Structures-BlockWriteCmdParms-#ctor-CSLibrary-Constants-MemoryBank,System-UInt16,System-UInt16,System-UInt16[]- 'CSLibrary.Structures.BlockWriteCmdParms.#ctor(CSLibrary.Constants.MemoryBank,System.UInt16,System.UInt16,System.UInt16[])')
  - [bank](#F-CSLibrary-Structures-BlockWriteCmdParms-bank 'CSLibrary.Structures.BlockWriteCmdParms.bank')
  - [count](#F-CSLibrary-Structures-BlockWriteCmdParms-count 'CSLibrary.Structures.BlockWriteCmdParms.count')
  - [offset](#F-CSLibrary-Structures-BlockWriteCmdParms-offset 'CSLibrary.Structures.BlockWriteCmdParms.offset')
  - [pData](#F-CSLibrary-Structures-BlockWriteCmdParms-pData 'CSLibrary.Structures.BlockWriteCmdParms.pData')
  - [Dispose()](#M-CSLibrary-Structures-BlockWriteCmdParms-Dispose 'CSLibrary.Structures.BlockWriteCmdParms.Dispose')
- [BlockWriteParms](#T-CSLibrary-Structures-BlockWriteParms 'CSLibrary.Structures.BlockWriteParms')
  - [accessPassword](#F-CSLibrary-Structures-BlockWriteParms-accessPassword 'CSLibrary.Structures.BlockWriteParms.accessPassword')
  - [blockWriteCmdParms](#F-CSLibrary-Structures-BlockWriteParms-blockWriteCmdParms 'CSLibrary.Structures.BlockWriteParms.blockWriteCmdParms')
  - [common](#F-CSLibrary-Structures-BlockWriteParms-common 'CSLibrary.Structures.BlockWriteParms.common')
  - [length](#F-CSLibrary-Structures-BlockWriteParms-length 'CSLibrary.Structures.BlockWriteParms.length')
- [CLAccessFifoParms](#T-CSLibrary-Structures-CLAccessFifoParms 'CSLibrary.Structures.CLAccessFifoParms')
  - [#ctor()](#M-CSLibrary-Structures-CLAccessFifoParms-#ctor 'CSLibrary.Structures.CLAccessFifoParms.#ctor')
  - [AccessFIFOData](#F-CSLibrary-Structures-CLAccessFifoParms-AccessFIFOData 'CSLibrary.Structures.CLAccessFifoParms.AccessFIFOData')
- [CLGetBatLvParms](#T-CSLibrary-Structures-CLGetBatLvParms 'CSLibrary.Structures.CLGetBatLvParms')
  - [#ctor()](#M-CSLibrary-Structures-CLGetBatLvParms-#ctor 'CSLibrary.Structures.CLGetBatLvParms.#ctor')
  - [BatLvData](#F-CSLibrary-Structures-CLGetBatLvParms-BatLvData 'CSLibrary.Structures.CLGetBatLvParms.BatLvData')
  - [BatteryLevel](#P-CSLibrary-Structures-CLGetBatLvParms-BatteryLevel 'CSLibrary.Structures.CLGetBatLvParms.BatteryLevel')
  - [BatteryValue](#P-CSLibrary-Structures-CLGetBatLvParms-BatteryValue 'CSLibrary.Structures.CLGetBatLvParms.BatteryValue')
- [CLGetCalDataParms](#T-CSLibrary-Structures-CLGetCalDataParms 'CSLibrary.Structures.CLGetCalDataParms')
  - [#ctor()](#M-CSLibrary-Structures-CLGetCalDataParms-#ctor 'CSLibrary.Structures.CLGetCalDataParms.#ctor')
  - [CalData](#F-CSLibrary-Structures-CLGetCalDataParms-CalData 'CSLibrary.Structures.CLGetCalDataParms.CalData')
- [CLGetLogStateParms](#T-CSLibrary-Structures-CLGetLogStateParms 'CSLibrary.Structures.CLGetLogStateParms')
  - [#ctor()](#M-CSLibrary-Structures-CLGetLogStateParms-#ctor 'CSLibrary.Structures.CLGetLogStateParms.#ctor')
  - [LogStateData](#F-CSLibrary-Structures-CLGetLogStateParms-LogStateData 'CSLibrary.Structures.CLGetLogStateParms.LogStateData')
  - [ADErr](#P-CSLibrary-Structures-CLGetLogStateParms-ADErr 'CSLibrary.Structures.CLGetLogStateParms.ADErr')
  - [ExtLower](#P-CSLibrary-Structures-CLGetLogStateParms-ExtLower 'CSLibrary.Structures.CLGetLogStateParms.ExtLower')
  - [MeasurementAddressPointer](#P-CSLibrary-Structures-CLGetLogStateParms-MeasurementAddressPointer 'CSLibrary.Structures.CLGetLogStateParms.MeasurementAddressPointer')
  - [NumberOfMeasurements](#P-CSLibrary-Structures-CLGetLogStateParms-NumberOfMeasurements 'CSLibrary.Structures.CLGetLogStateParms.NumberOfMeasurements')
  - [NumberOfMemoryReplacements](#P-CSLibrary-Structures-CLGetLogStateParms-NumberOfMemoryReplacements 'CSLibrary.Structures.CLGetLogStateParms.NumberOfMemoryReplacements')
  - [ShelfLifeHighError](#P-CSLibrary-Structures-CLGetLogStateParms-ShelfLifeHighError 'CSLibrary.Structures.CLGetLogStateParms.ShelfLifeHighError')
- [CLGetMesurementSetupParms](#T-CSLibrary-Structures-CLGetMesurementSetupParms 'CSLibrary.Structures.CLGetMesurementSetupParms')
  - [#ctor()](#M-CSLibrary-Structures-CLGetMesurementSetupParms-#ctor 'CSLibrary.Structures.CLGetMesurementSetupParms.#ctor')
  - [StartTime](#P-CSLibrary-Structures-CLGetMesurementSetupParms-StartTime 'CSLibrary.Structures.CLGetMesurementSetupParms.StartTime')
- [CLGetSensorValueParms](#T-CSLibrary-Structures-CLGetSensorValueParms 'CSLibrary.Structures.CLGetSensorValueParms')
  - [SensorValueData](#F-CSLibrary-Structures-CLGetSensorValueParms-SensorValueData 'CSLibrary.Structures.CLGetSensorValueParms.SensorValueData')
  - [ADError](#P-CSLibrary-Structures-CLGetSensorValueParms-ADError 'CSLibrary.Structures.CLGetSensorValueParms.ADError')
  - [RangeLimit](#P-CSLibrary-Structures-CLGetSensorValueParms-RangeLimit 'CSLibrary.Structures.CLGetSensorValueParms.RangeLimit')
  - [SensorType](#P-CSLibrary-Structures-CLGetSensorValueParms-SensorType 'CSLibrary.Structures.CLGetSensorValueParms.SensorType')
  - [SensorValue](#P-CSLibrary-Structures-CLGetSensorValueParms-SensorValue 'CSLibrary.Structures.CLGetSensorValueParms.SensorValue')
- [CLInitParms](#T-CSLibrary-Structures-CLInitParms 'CSLibrary.Structures.CLInitParms')
  - [#ctor()](#M-CSLibrary-Structures-CLInitParms-#ctor 'CSLibrary.Structures.CLInitParms.#ctor')
  - [DelayMode](#P-CSLibrary-Structures-CLInitParms-DelayMode 'CSLibrary.Structures.CLInitParms.DelayMode')
  - [DelayTime](#P-CSLibrary-Structures-CLInitParms-DelayTime 'CSLibrary.Structures.CLInitParms.DelayTime')
  - [TimerEnable](#P-CSLibrary-Structures-CLInitParms-TimerEnable 'CSLibrary.Structures.CLInitParms.TimerEnable')
- [CLOpenAreaParms](#T-CSLibrary-Structures-CLOpenAreaParms 'CSLibrary.Structures.CLOpenAreaParms')
  - [#ctor()](#M-CSLibrary-Structures-CLOpenAreaParms-#ctor 'CSLibrary.Structures.CLOpenAreaParms.#ctor')
- [CLSetCalDataParms](#T-CSLibrary-Structures-CLSetCalDataParms 'CSLibrary.Structures.CLSetCalDataParms')
- [CLSetLogLimitsParms](#T-CSLibrary-Structures-CLSetLogLimitsParms 'CSLibrary.Structures.CLSetLogLimitsParms')
  - [#ctor()](#M-CSLibrary-Structures-CLSetLogLimitsParms-#ctor 'CSLibrary.Structures.CLSetLogLimitsParms.#ctor')
- [CLSetLogModeParms](#T-CSLibrary-Structures-CLSetLogModeParms 'CSLibrary.Structures.CLSetLogModeParms')
  - [#ctor()](#M-CSLibrary-Structures-CLSetLogModeParms-#ctor 'CSLibrary.Structures.CLSetLogModeParms.#ctor')
  - [BatteryCheckEnable](#P-CSLibrary-Structures-CLSetLogModeParms-BatteryCheckEnable 'CSLibrary.Structures.CLSetLogModeParms.BatteryCheckEnable')
  - [Ext1SensorEnable](#P-CSLibrary-Structures-CLSetLogModeParms-Ext1SensorEnable 'CSLibrary.Structures.CLSetLogModeParms.Ext1SensorEnable')
  - [Ext2SensorEnable](#P-CSLibrary-Structures-CLSetLogModeParms-Ext2SensorEnable 'CSLibrary.Structures.CLSetLogModeParms.Ext2SensorEnable')
  - [LogInterval](#P-CSLibrary-Structures-CLSetLogModeParms-LogInterval 'CSLibrary.Structures.CLSetLogModeParms.LogInterval')
  - [StorageRule](#P-CSLibrary-Structures-CLSetLogModeParms-StorageRule 'CSLibrary.Structures.CLSetLogModeParms.StorageRule')
  - [TempSensorEnable](#P-CSLibrary-Structures-CLSetLogModeParms-TempSensorEnable 'CSLibrary.Structures.CLSetLogModeParms.TempSensorEnable')
- [CLSetPasswordParms](#T-CSLibrary-Structures-CLSetPasswordParms 'CSLibrary.Structures.CLSetPasswordParms')
  - [#ctor()](#M-CSLibrary-Structures-CLSetPasswordParms-#ctor 'CSLibrary.Structures.CLSetPasswordParms.#ctor')
  - [Password](#P-CSLibrary-Structures-CLSetPasswordParms-Password 'CSLibrary.Structures.CLSetPasswordParms.Password')
  - [PasswordLevel](#P-CSLibrary-Structures-CLSetPasswordParms-PasswordLevel 'CSLibrary.Structures.CLSetPasswordParms.PasswordLevel')
- [CLSetSFEParaParms](#T-CSLibrary-Structures-CLSetSFEParaParms 'CSLibrary.Structures.CLSetSFEParaParms')
  - [AutorangeDisable](#P-CSLibrary-Structures-CLSetSFEParaParms-AutorangeDisable 'CSLibrary.Structures.CLSetSFEParaParms.AutorangeDisable')
  - [EXT1](#P-CSLibrary-Structures-CLSetSFEParaParms-EXT1 'CSLibrary.Structures.CLSetSFEParaParms.EXT1')
  - [EXT2](#P-CSLibrary-Structures-CLSetSFEParaParms-EXT2 'CSLibrary.Structures.CLSetSFEParaParms.EXT2')
  - [Rang](#P-CSLibrary-Structures-CLSetSFEParaParms-Rang 'CSLibrary.Structures.CLSetSFEParaParms.Rang')
  - [Seti](#P-CSLibrary-Structures-CLSetSFEParaParms-Seti 'CSLibrary.Structures.CLSetSFEParaParms.Seti')
  - [VerigfySensorID](#P-CSLibrary-Structures-CLSetSFEParaParms-VerigfySensorID 'CSLibrary.Structures.CLSetSFEParaParms.VerigfySensorID')
- [CLSetShelfLifeParms](#T-CSLibrary-Structures-CLSetShelfLifeParms 'CSLibrary.Structures.CLSetShelfLifeParms')
  - [#ctor()](#M-CSLibrary-Structures-CLSetShelfLifeParms-#ctor 'CSLibrary.Structures.CLSetShelfLifeParms.#ctor')
- [CLStartLogParms](#T-CSLibrary-Structures-CLStartLogParms 'CSLibrary.Structures.CLStartLogParms')
  - [#ctor()](#M-CSLibrary-Structures-CLStartLogParms-#ctor 'CSLibrary.Structures.CLStartLogParms.#ctor')
  - [Day](#P-CSLibrary-Structures-CLStartLogParms-Day 'CSLibrary.Structures.CLStartLogParms.Day')
  - [Hour](#P-CSLibrary-Structures-CLStartLogParms-Hour 'CSLibrary.Structures.CLStartLogParms.Hour')
  - [Minute](#P-CSLibrary-Structures-CLStartLogParms-Minute 'CSLibrary.Structures.CLStartLogParms.Minute')
  - [Month](#P-CSLibrary-Structures-CLStartLogParms-Month 'CSLibrary.Structures.CLStartLogParms.Month')
  - [Second](#P-CSLibrary-Structures-CLStartLogParms-Second 'CSLibrary.Structures.CLStartLogParms.Second')
  - [Year](#P-CSLibrary-Structures-CLStartLogParms-Year 'CSLibrary.Structures.CLStartLogParms.Year')
- [CSLibraryOperationParms](#T-CSLibrary-Structures-CSLibraryOperationParms 'CSLibrary.Structures.CSLibraryOperationParms')
  - [CarrierWave](#F-CSLibrary-Structures-CSLibraryOperationParms-CarrierWave 'CSLibrary.Structures.CSLibraryOperationParms.CarrierWave')
  - [TagBlockLock](#F-CSLibrary-Structures-CSLibraryOperationParms-TagBlockLock 'CSLibrary.Structures.CSLibraryOperationParms.TagBlockLock')
  - [TagBlockWrite](#F-CSLibrary-Structures-CSLibraryOperationParms-TagBlockWrite 'CSLibrary.Structures.CSLibraryOperationParms.TagBlockWrite')
  - [TagFilter](#F-CSLibrary-Structures-CSLibraryOperationParms-TagFilter 'CSLibrary.Structures.CSLibraryOperationParms.TagFilter')
  - [TagGeneralSelected](#F-CSLibrary-Structures-CSLibraryOperationParms-TagGeneralSelected 'CSLibrary.Structures.CSLibraryOperationParms.TagGeneralSelected')
  - [TagInventory](#F-CSLibrary-Structures-CSLibraryOperationParms-TagInventory 'CSLibrary.Structures.CSLibraryOperationParms.TagInventory')
  - [TagKill](#F-CSLibrary-Structures-CSLibraryOperationParms-TagKill 'CSLibrary.Structures.CSLibraryOperationParms.TagKill')
  - [TagLock](#F-CSLibrary-Structures-CSLibraryOperationParms-TagLock 'CSLibrary.Structures.CSLibraryOperationParms.TagLock')
  - [TagPostMatch](#F-CSLibrary-Structures-CSLibraryOperationParms-TagPostMatch 'CSLibrary.Structures.CSLibraryOperationParms.TagPostMatch')
  - [TagRanging](#F-CSLibrary-Structures-CSLibraryOperationParms-TagRanging 'CSLibrary.Structures.CSLibraryOperationParms.TagRanging')
  - [TagRead](#F-CSLibrary-Structures-CSLibraryOperationParms-TagRead 'CSLibrary.Structures.CSLibraryOperationParms.TagRead')
  - [TagReadAccPwd](#F-CSLibrary-Structures-CSLibraryOperationParms-TagReadAccPwd 'CSLibrary.Structures.CSLibraryOperationParms.TagReadAccPwd')
  - [TagReadEPC](#F-CSLibrary-Structures-CSLibraryOperationParms-TagReadEPC 'CSLibrary.Structures.CSLibraryOperationParms.TagReadEPC')
  - [TagReadKillPwd](#F-CSLibrary-Structures-CSLibraryOperationParms-TagReadKillPwd 'CSLibrary.Structures.CSLibraryOperationParms.TagReadKillPwd')
  - [TagReadPC](#F-CSLibrary-Structures-CSLibraryOperationParms-TagReadPC 'CSLibrary.Structures.CSLibraryOperationParms.TagReadPC')
  - [TagReadProtect](#F-CSLibrary-Structures-CSLibraryOperationParms-TagReadProtect 'CSLibrary.Structures.CSLibraryOperationParms.TagReadProtect')
  - [TagReadTid](#F-CSLibrary-Structures-CSLibraryOperationParms-TagReadTid 'CSLibrary.Structures.CSLibraryOperationParms.TagReadTid')
  - [TagReadUser](#F-CSLibrary-Structures-CSLibraryOperationParms-TagReadUser 'CSLibrary.Structures.CSLibraryOperationParms.TagReadUser')
  - [TagResetReadProtect](#F-CSLibrary-Structures-CSLibraryOperationParms-TagResetReadProtect 'CSLibrary.Structures.CSLibraryOperationParms.TagResetReadProtect')
  - [TagSearchOne](#F-CSLibrary-Structures-CSLibraryOperationParms-TagSearchOne 'CSLibrary.Structures.CSLibraryOperationParms.TagSearchOne')
  - [TagSelected](#F-CSLibrary-Structures-CSLibraryOperationParms-TagSelected 'CSLibrary.Structures.CSLibraryOperationParms.TagSelected')
  - [TagWrite](#F-CSLibrary-Structures-CSLibraryOperationParms-TagWrite 'CSLibrary.Structures.CSLibraryOperationParms.TagWrite')
  - [TagWriteAccPwd](#F-CSLibrary-Structures-CSLibraryOperationParms-TagWriteAccPwd 'CSLibrary.Structures.CSLibraryOperationParms.TagWriteAccPwd')
  - [TagWriteEPC](#F-CSLibrary-Structures-CSLibraryOperationParms-TagWriteEPC 'CSLibrary.Structures.CSLibraryOperationParms.TagWriteEPC')
  - [TagWriteKillPwd](#F-CSLibrary-Structures-CSLibraryOperationParms-TagWriteKillPwd 'CSLibrary.Structures.CSLibraryOperationParms.TagWriteKillPwd')
  - [TagWritePC](#F-CSLibrary-Structures-CSLibraryOperationParms-TagWritePC 'CSLibrary.Structures.CSLibraryOperationParms.TagWritePC')
  - [TagWriteUser](#F-CSLibrary-Structures-CSLibraryOperationParms-TagWriteUser 'CSLibrary.Structures.CSLibraryOperationParms.TagWriteUser')
- [CallbackType](#T-CSLibrary-Constants-CallbackType 'CSLibrary.Constants.CallbackType')
  - [TAG_EASALARM](#F-CSLibrary-Constants-CallbackType-TAG_EASALARM 'CSLibrary.Constants.CallbackType.TAG_EASALARM')
  - [TAG_INVENTORY](#F-CSLibrary-Constants-CallbackType-TAG_INVENTORY 'CSLibrary.Constants.CallbackType.TAG_INVENTORY')
  - [TAG_RANGING](#F-CSLibrary-Constants-CallbackType-TAG_RANGING 'CSLibrary.Constants.CallbackType.TAG_RANGING')
  - [TAG_SEARCHING](#F-CSLibrary-Constants-CallbackType-TAG_SEARCHING 'CSLibrary.Constants.CallbackType.TAG_SEARCHING')
  - [UNKNOWN](#F-CSLibrary-Constants-CallbackType-UNKNOWN 'CSLibrary.Constants.CallbackType.UNKNOWN')
- [CarrierWaveParms](#T-CSLibrary-Structures-CarrierWaveParms 'CSLibrary.Structures.CarrierWaveParms')
  - [dataMode](#F-CSLibrary-Structures-CarrierWaveParms-dataMode 'CSLibrary.Structures.CarrierWaveParms.dataMode')
- [ChangeEASParms](#T-CSLibrary-Structures-ChangeEASParms 'CSLibrary.Structures.ChangeEASParms')
  - [accessPassword](#F-CSLibrary-Structures-ChangeEASParms-accessPassword 'CSLibrary.Structures.ChangeEASParms.accessPassword')
  - [enableEAS](#F-CSLibrary-Structures-ChangeEASParms-enableEAS 'CSLibrary.Structures.ChangeEASParms.enableEAS')
  - [retryCount](#F-CSLibrary-Structures-ChangeEASParms-retryCount 'CSLibrary.Structures.ChangeEASParms.retryCount')
- [CommonParms](#T-CSLibrary-Structures-CommonParms 'CSLibrary.Structures.CommonParms')
  - [callback](#F-CSLibrary-Structures-CommonParms-callback 'CSLibrary.Structures.CommonParms.callback')
  - [callbackCode](#F-CSLibrary-Structures-CommonParms-callbackCode 'CSLibrary.Structures.CommonParms.callbackCode')
  - [context](#F-CSLibrary-Structures-CommonParms-context 'CSLibrary.Structures.CommonParms.context')
  - [tagStopCount](#F-CSLibrary-Structures-CommonParms-tagStopCount 'CSLibrary.Structures.CommonParms.tagStopCount')
- [CoreDebug](#T-CSLibrary-Diagnostics-CoreDebug 'CSLibrary.Diagnostics.CoreDebug')
  - [Enable](#P-CSLibrary-Diagnostics-CoreDebug-Enable 'CSLibrary.Diagnostics.CoreDebug.Enable')
- [DEVICE_STATUS](#T-CSLibrary-Structures-DEVICE_STATUS 'CSLibrary.Structures.DEVICE_STATUS')
  - [IsCRCFilter](#F-CSLibrary-Structures-DEVICE_STATUS-IsCRCFilter 'CSLibrary.Structures.DEVICE_STATUS.IsCRCFilter')
  - [IsConnected](#F-CSLibrary-Structures-DEVICE_STATUS-IsConnected 'CSLibrary.Structures.DEVICE_STATUS.IsConnected')
  - [IsErrorReset](#F-CSLibrary-Structures-DEVICE_STATUS-IsErrorReset 'CSLibrary.Structures.DEVICE_STATUS.IsErrorReset')
  - [IsKeepAlive](#F-CSLibrary-Structures-DEVICE_STATUS-IsKeepAlive 'CSLibrary.Structures.DEVICE_STATUS.IsKeepAlive')
  - [IsPowerOn](#F-CSLibrary-Structures-DEVICE_STATUS-IsPowerOn 'CSLibrary.Structures.DEVICE_STATUS.IsPowerOn')
  - [GetElapsedTime()](#M-CSLibrary-Structures-DEVICE_STATUS-GetElapsedTime 'CSLibrary.Structures.DEVICE_STATUS.GetElapsedTime')
- [DataDifference](#T-CSLibrary-Constants-DataDifference 'CSLibrary.Constants.DataDifference')
  - [HALF_TARI](#F-CSLibrary-Constants-DataDifference-HALF_TARI 'CSLibrary.Constants.DataDifference.HALF_TARI')
  - [ONE_TARI](#F-CSLibrary-Constants-DataDifference-ONE_TARI 'CSLibrary.Constants.DataDifference.ONE_TARI')
  - [UNKNOWN](#F-CSLibrary-Constants-DataDifference-UNKNOWN 'CSLibrary.Constants.DataDifference.UNKNOWN')
- [DeviceFinderArgs](#T-CSLibrary-Net-DeviceFinderArgs 'CSLibrary.Net.DeviceFinderArgs')
  - [#ctor(data)](#M-CSLibrary-Net-DeviceFinderArgs-#ctor-CSLibrary-Net-DeviceInfomation- 'CSLibrary.Net.DeviceFinderArgs.#ctor(CSLibrary.Net.DeviceInfomation)')
  - [Found](#P-CSLibrary-Net-DeviceFinderArgs-Found 'CSLibrary.Net.DeviceFinderArgs.Found')
- [DeviceInfomation](#T-CSLibrary-Net-DeviceInfomation 'CSLibrary.Net.DeviceInfomation')
  - [ConnectMode](#F-CSLibrary-Net-DeviceInfomation-ConnectMode 'CSLibrary.Net.DeviceInfomation.ConnectMode')
  - [DHCPEnabled](#F-CSLibrary-Net-DeviceInfomation-DHCPEnabled 'CSLibrary.Net.DeviceInfomation.DHCPEnabled')
  - [DHCPRetry](#F-CSLibrary-Net-DeviceInfomation-DHCPRetry 'CSLibrary.Net.DeviceInfomation.DHCPRetry')
  - [Description](#F-CSLibrary-Net-DeviceInfomation-Description 'CSLibrary.Net.DeviceInfomation.Description')
  - [DeviceName](#F-CSLibrary-Net-DeviceInfomation-DeviceName 'CSLibrary.Net.DeviceInfomation.DeviceName')
  - [Gateway](#F-CSLibrary-Net-DeviceInfomation-Gateway 'CSLibrary.Net.DeviceInfomation.Gateway')
  - [GatewayCheckResetMode](#F-CSLibrary-Net-DeviceInfomation-GatewayCheckResetMode 'CSLibrary.Net.DeviceInfomation.GatewayCheckResetMode')
  - [IPAddress](#F-CSLibrary-Net-DeviceInfomation-IPAddress 'CSLibrary.Net.DeviceInfomation.IPAddress')
  - [MACAddress](#F-CSLibrary-Net-DeviceInfomation-MACAddress 'CSLibrary.Net.DeviceInfomation.MACAddress')
  - [Mode](#F-CSLibrary-Net-DeviceInfomation-Mode 'CSLibrary.Net.DeviceInfomation.Mode')
  - [Port](#F-CSLibrary-Net-DeviceInfomation-Port 'CSLibrary.Net.DeviceInfomation.Port')
  - [SubnetMask](#F-CSLibrary-Net-DeviceInfomation-SubnetMask 'CSLibrary.Net.DeviceInfomation.SubnetMask')
  - [TimeElapsedNetwork](#F-CSLibrary-Net-DeviceInfomation-TimeElapsedNetwork 'CSLibrary.Net.DeviceInfomation.TimeElapsedNetwork')
  - [TimeElapsedPowerOn](#F-CSLibrary-Net-DeviceInfomation-TimeElapsedPowerOn 'CSLibrary.Net.DeviceInfomation.TimeElapsedPowerOn')
  - [TrustedServer](#F-CSLibrary-Net-DeviceInfomation-TrustedServer 'CSLibrary.Net.DeviceInfomation.TrustedServer')
  - [TrustedServerEnabled](#F-CSLibrary-Net-DeviceInfomation-TrustedServerEnabled 'CSLibrary.Net.DeviceInfomation.TrustedServerEnabled')
- [DivideRatio](#T-CSLibrary-Constants-DivideRatio 'CSLibrary.Constants.DivideRatio')
  - [RATIO_64DIV3](#F-CSLibrary-Constants-DivideRatio-RATIO_64DIV3 'CSLibrary.Constants.DivideRatio.RATIO_64DIV3')
  - [RATIO_8](#F-CSLibrary-Constants-DivideRatio-RATIO_8 'CSLibrary.Constants.DivideRatio.RATIO_8')
  - [UNKNOWN](#F-CSLibrary-Constants-DivideRatio-UNKNOWN 'CSLibrary.Constants.DivideRatio.UNKNOWN')
- [DriverVersion](#T-CSLibrary-Structures-DriverVersion 'CSLibrary.Structures.DriverVersion')
  - [#ctor()](#M-CSLibrary-Structures-DriverVersion-#ctor 'CSLibrary.Structures.DriverVersion.#ctor')
- [DynamicQParms](#T-CSLibrary-Structures-DynamicQParms 'CSLibrary.Structures.DynamicQParms')
  - [maxQValue](#F-CSLibrary-Structures-DynamicQParms-maxQValue 'CSLibrary.Structures.DynamicQParms.maxQValue')
  - [minQValue](#F-CSLibrary-Structures-DynamicQParms-minQValue 'CSLibrary.Structures.DynamicQParms.minQValue')
  - [retryCount](#F-CSLibrary-Structures-DynamicQParms-retryCount 'CSLibrary.Structures.DynamicQParms.retryCount')
  - [startQValue](#F-CSLibrary-Structures-DynamicQParms-startQValue 'CSLibrary.Structures.DynamicQParms.startQValue')
  - [thresholdMultiplier](#F-CSLibrary-Structures-DynamicQParms-thresholdMultiplier 'CSLibrary.Structures.DynamicQParms.thresholdMultiplier')
  - [toggleTarget](#F-CSLibrary-Structures-DynamicQParms-toggleTarget 'CSLibrary.Structures.DynamicQParms.toggleTarget')
- [EASParms](#T-CSLibrary-Structures-EASParms 'CSLibrary.Structures.EASParms')
  - [accessPassword](#F-CSLibrary-Structures-EASParms-accessPassword 'CSLibrary.Structures.EASParms.accessPassword')
  - [common](#F-CSLibrary-Structures-EASParms-common 'CSLibrary.Structures.EASParms.common')
  - [easCmdParms](#F-CSLibrary-Structures-EASParms-easCmdParms 'CSLibrary.Structures.EASParms.easCmdParms')
  - [length](#F-CSLibrary-Structures-EASParms-length 'CSLibrary.Structures.EASParms.length')
- [ECreationDisposition](#T-CSLibrary-Utils-NativeIOControl-ECreationDisposition 'CSLibrary.Utils.NativeIOControl.ECreationDisposition')
  - [CreateAlways](#F-CSLibrary-Utils-NativeIOControl-ECreationDisposition-CreateAlways 'CSLibrary.Utils.NativeIOControl.ECreationDisposition.CreateAlways')
  - [New](#F-CSLibrary-Utils-NativeIOControl-ECreationDisposition-New 'CSLibrary.Utils.NativeIOControl.ECreationDisposition.New')
  - [OpenAlways](#F-CSLibrary-Utils-NativeIOControl-ECreationDisposition-OpenAlways 'CSLibrary.Utils.NativeIOControl.ECreationDisposition.OpenAlways')
  - [OpenExisting](#F-CSLibrary-Utils-NativeIOControl-ECreationDisposition-OpenExisting 'CSLibrary.Utils.NativeIOControl.ECreationDisposition.OpenExisting')
  - [TruncateExisting](#F-CSLibrary-Utils-NativeIOControl-ECreationDisposition-TruncateExisting 'CSLibrary.Utils.NativeIOControl.ECreationDisposition.TruncateExisting')
- [EFileAccess](#T-CSLibrary-Utils-NativeIOControl-EFileAccess 'CSLibrary.Utils.NativeIOControl.EFileAccess')
  - [GenericAll](#F-CSLibrary-Utils-NativeIOControl-EFileAccess-GenericAll 'CSLibrary.Utils.NativeIOControl.EFileAccess.GenericAll')
  - [GenericExecute](#F-CSLibrary-Utils-NativeIOControl-EFileAccess-GenericExecute 'CSLibrary.Utils.NativeIOControl.EFileAccess.GenericExecute')
  - [GenericRead](#F-CSLibrary-Utils-NativeIOControl-EFileAccess-GenericRead 'CSLibrary.Utils.NativeIOControl.EFileAccess.GenericRead')
  - [GenericWrite](#F-CSLibrary-Utils-NativeIOControl-EFileAccess-GenericWrite 'CSLibrary.Utils.NativeIOControl.EFileAccess.GenericWrite')
- [EFileShare](#T-CSLibrary-Utils-NativeIOControl-EFileShare 'CSLibrary.Utils.NativeIOControl.EFileShare')
  - [Delete](#F-CSLibrary-Utils-NativeIOControl-EFileShare-Delete 'CSLibrary.Utils.NativeIOControl.EFileShare.Delete')
  - [None](#F-CSLibrary-Utils-NativeIOControl-EFileShare-None 'CSLibrary.Utils.NativeIOControl.EFileShare.None')
  - [Read](#F-CSLibrary-Utils-NativeIOControl-EFileShare-Read 'CSLibrary.Utils.NativeIOControl.EFileShare.Read')
  - [Write](#F-CSLibrary-Utils-NativeIOControl-EFileShare-Write 'CSLibrary.Utils.NativeIOControl.EFileShare.Write')
- [EnableSwitch](#T-CSLibrary-Structures-EnableSwitch 'CSLibrary.Structures.EnableSwitch')
  - [Disable](#F-CSLibrary-Structures-EnableSwitch-Disable 'CSLibrary.Structures.EnableSwitch.Disable')
  - [Enable](#F-CSLibrary-Structures-EnableSwitch-Enable 'CSLibrary.Structures.EnableSwitch.Enable')
- [EpcMDID](#T-CSLibrary-Constants-EpcMDID 'CSLibrary.Constants.EpcMDID')
  - [Alien_Technology](#F-CSLibrary-Constants-EpcMDID-Alien_Technology 'CSLibrary.Constants.EpcMDID.Alien_Technology')
  - [Alien_Technology_with_xTid](#F-CSLibrary-Constants-EpcMDID-Alien_Technology_with_xTid 'CSLibrary.Constants.EpcMDID.Alien_Technology_with_xTid')
  - [Atmel](#F-CSLibrary-Constants-EpcMDID-Atmel 'CSLibrary.Constants.EpcMDID.Atmel')
  - [Atmel_with_xTid](#F-CSLibrary-Constants-EpcMDID-Atmel_with_xTid 'CSLibrary.Constants.EpcMDID.Atmel_with_xTid')
  - [CAEN_Productivity_Engineering_Gesellschaft_fuer_IC_Design_mbH](#F-CSLibrary-Constants-EpcMDID-CAEN_Productivity_Engineering_Gesellschaft_fuer_IC_Design_mbH 'CSLibrary.Constants.EpcMDID.CAEN_Productivity_Engineering_Gesellschaft_fuer_IC_Design_mbH')
  - [CAEN_Productivity_Engineering_Gesellschaft_fuer_IC_Design_mbH_with_xTid](#F-CSLibrary-Constants-EpcMDID-CAEN_Productivity_Engineering_Gesellschaft_fuer_IC_Design_mbH_with_xTid 'CSLibrary.Constants.EpcMDID.CAEN_Productivity_Engineering_Gesellschaft_fuer_IC_Design_mbH_with_xTid')
  - [CAEN_RFID_srl](#F-CSLibrary-Constants-EpcMDID-CAEN_RFID_srl 'CSLibrary.Constants.EpcMDID.CAEN_RFID_srl')
  - [CAEN_RFID_srl_with_xTid](#F-CSLibrary-Constants-EpcMDID-CAEN_RFID_srl_with_xTid 'CSLibrary.Constants.EpcMDID.CAEN_RFID_srl_with_xTid')
  - [EM_Microelectronics](#F-CSLibrary-Constants-EpcMDID-EM_Microelectronics 'CSLibrary.Constants.EpcMDID.EM_Microelectronics')
  - [EM_Microelectronics_with_xTid](#F-CSLibrary-Constants-EpcMDID-EM_Microelectronics_with_xTid 'CSLibrary.Constants.EpcMDID.EM_Microelectronics_with_xTid')
  - [EP_Microelectronics](#F-CSLibrary-Constants-EpcMDID-EP_Microelectronics 'CSLibrary.Constants.EpcMDID.EP_Microelectronics')
  - [EP_Microelectronics_with_xTid](#F-CSLibrary-Constants-EpcMDID-EP_Microelectronics_with_xTid 'CSLibrary.Constants.EpcMDID.EP_Microelectronics_with_xTid')
  - [Fujitsu](#F-CSLibrary-Constants-EpcMDID-Fujitsu 'CSLibrary.Constants.EpcMDID.Fujitsu')
  - [Fujitsu_with_xTid](#F-CSLibrary-Constants-EpcMDID-Fujitsu_with_xTid 'CSLibrary.Constants.EpcMDID.Fujitsu_with_xTid')
  - [Impinj](#F-CSLibrary-Constants-EpcMDID-Impinj 'CSLibrary.Constants.EpcMDID.Impinj')
  - [Impinj_with_xTid](#F-CSLibrary-Constants-EpcMDID-Impinj_with_xTid 'CSLibrary.Constants.EpcMDID.Impinj_with_xTid')
  - [Intelleflex](#F-CSLibrary-Constants-EpcMDID-Intelleflex 'CSLibrary.Constants.EpcMDID.Intelleflex')
  - [Intelleflex_with_xTid](#F-CSLibrary-Constants-EpcMDID-Intelleflex_with_xTid 'CSLibrary.Constants.EpcMDID.Intelleflex_with_xTid')
  - [LSIS](#F-CSLibrary-Constants-EpcMDID-LSIS 'CSLibrary.Constants.EpcMDID.LSIS')
  - [LSIS_with_xTid](#F-CSLibrary-Constants-EpcMDID-LSIS_with_xTid 'CSLibrary.Constants.EpcMDID.LSIS_with_xTid')
  - [Motorola](#F-CSLibrary-Constants-EpcMDID-Motorola 'CSLibrary.Constants.EpcMDID.Motorola')
  - [Motorola_with_xTid](#F-CSLibrary-Constants-EpcMDID-Motorola_with_xTid 'CSLibrary.Constants.EpcMDID.Motorola_with_xTid')
  - [Mstar](#F-CSLibrary-Constants-EpcMDID-Mstar 'CSLibrary.Constants.EpcMDID.Mstar')
  - [Mstar_with_xTid](#F-CSLibrary-Constants-EpcMDID-Mstar_with_xTid 'CSLibrary.Constants.EpcMDID.Mstar_with_xTid')
  - [NXP](#F-CSLibrary-Constants-EpcMDID-NXP 'CSLibrary.Constants.EpcMDID.NXP')
  - [NXP_with_xTid](#F-CSLibrary-Constants-EpcMDID-NXP_with_xTid 'CSLibrary.Constants.EpcMDID.NXP_with_xTid')
  - [Quanray_Electronics](#F-CSLibrary-Constants-EpcMDID-Quanray_Electronics 'CSLibrary.Constants.EpcMDID.Quanray_Electronics')
  - [Quanray_Electronics_with_xTid](#F-CSLibrary-Constants-EpcMDID-Quanray_Electronics_with_xTid 'CSLibrary.Constants.EpcMDID.Quanray_Electronics_with_xTid')
  - [Renesas_Technology_Corp](#F-CSLibrary-Constants-EpcMDID-Renesas_Technology_Corp 'CSLibrary.Constants.EpcMDID.Renesas_Technology_Corp')
  - [Renesas_Technology_Corp_with_xTid](#F-CSLibrary-Constants-EpcMDID-Renesas_Technology_Corp_with_xTid 'CSLibrary.Constants.EpcMDID.Renesas_Technology_Corp_with_xTid')
  - [ST_Microelectronics](#F-CSLibrary-Constants-EpcMDID-ST_Microelectronics 'CSLibrary.Constants.EpcMDID.ST_Microelectronics')
  - [ST_Microelectronics_with_xTid](#F-CSLibrary-Constants-EpcMDID-ST_Microelectronics_with_xTid 'CSLibrary.Constants.EpcMDID.ST_Microelectronics_with_xTid')
  - [Sentech_Snd_Bhd](#F-CSLibrary-Constants-EpcMDID-Sentech_Snd_Bhd 'CSLibrary.Constants.EpcMDID.Sentech_Snd_Bhd')
  - [Sentech_Snd_Bhd_with_xTid](#F-CSLibrary-Constants-EpcMDID-Sentech_Snd_Bhd_with_xTid 'CSLibrary.Constants.EpcMDID.Sentech_Snd_Bhd_with_xTid')
  - [Texas_Instruments](#F-CSLibrary-Constants-EpcMDID-Texas_Instruments 'CSLibrary.Constants.EpcMDID.Texas_Instruments')
  - [Texas_Instruments_with_xTid](#F-CSLibrary-Constants-EpcMDID-Texas_Instruments_with_xTid 'CSLibrary.Constants.EpcMDID.Texas_Instruments_with_xTid')
  - [Tyco_International](#F-CSLibrary-Constants-EpcMDID-Tyco_International 'CSLibrary.Constants.EpcMDID.Tyco_International')
  - [Tyco_International_with_xTid](#F-CSLibrary-Constants-EpcMDID-Tyco_International_with_xTid 'CSLibrary.Constants.EpcMDID.Tyco_International_with_xTid')
  - [UNKNOWN](#F-CSLibrary-Constants-EpcMDID-UNKNOWN 'CSLibrary.Constants.EpcMDID.UNKNOWN')
- [ErrorBit](#T-CSLibrary-Structures-ErrorBit 'CSLibrary.Structures.ErrorBit')
  - [Error](#F-CSLibrary-Structures-ErrorBit-Error 'CSLibrary.Structures.ErrorBit.Error')
  - [OK](#F-CSLibrary-Structures-ErrorBit-OK 'CSLibrary.Structures.ErrorBit.OK')
- [ErrorCode](#T-CSLibrary-Constants-ErrorCode 'CSLibrary.Constants.ErrorCode')
  - [CRC_INVALID](#F-CSLibrary-Constants-ErrorCode-CRC_INVALID 'CSLibrary.Constants.ErrorCode.CRC_INVALID')
  - [FUNC_RETURN_FAILED](#F-CSLibrary-Constants-ErrorCode-FUNC_RETURN_FAILED 'CSLibrary.Constants.ErrorCode.FUNC_RETURN_FAILED')
  - [INVALID_TAG](#F-CSLibrary-Constants-ErrorCode-INVALID_TAG 'CSLibrary.Constants.ErrorCode.INVALID_TAG')
  - [MAC_ERROR](#F-CSLibrary-Constants-ErrorCode-MAC_ERROR 'CSLibrary.Constants.ErrorCode.MAC_ERROR')
  - [MAX_RETRY_OVER](#F-CSLibrary-Constants-ErrorCode-MAX_RETRY_OVER 'CSLibrary.Constants.ErrorCode.MAX_RETRY_OVER')
  - [PARSE_PKT_ERROR](#F-CSLibrary-Constants-ErrorCode-PARSE_PKT_ERROR 'CSLibrary.Constants.ErrorCode.PARSE_PKT_ERROR')
  - [SYSTEM_ERROR](#F-CSLibrary-Constants-ErrorCode-SYSTEM_ERROR 'CSLibrary.Constants.ErrorCode.SYSTEM_ERROR')
  - [TAG_NOT_FOUND](#F-CSLibrary-Constants-ErrorCode-TAG_NOT_FOUND 'CSLibrary.Constants.ErrorCode.TAG_NOT_FOUND')
  - [UNKNOWN](#F-CSLibrary-Constants-ErrorCode-UNKNOWN 'CSLibrary.Constants.ErrorCode.UNKNOWN')
  - [WRITTEN_DATA_INVALID](#F-CSLibrary-Constants-ErrorCode-WRITTEN_DATA_INVALID 'CSLibrary.Constants.ErrorCode.WRITTEN_DATA_INVALID')
- [ErrorType](#T-CSLibrary-Constants-ErrorType 'CSLibrary.Constants.ErrorType')
  - [COMMON](#F-CSLibrary-Constants-ErrorType-COMMON 'CSLibrary.Constants.ErrorType.COMMON')
  - [INVENTORY](#F-CSLibrary-Constants-ErrorType-INVENTORY 'CSLibrary.Constants.ErrorType.INVENTORY')
  - [KILL](#F-CSLibrary-Constants-ErrorType-KILL 'CSLibrary.Constants.ErrorType.KILL')
  - [LOCK](#F-CSLibrary-Constants-ErrorType-LOCK 'CSLibrary.Constants.ErrorType.LOCK')
  - [MAC](#F-CSLibrary-Constants-ErrorType-MAC 'CSLibrary.Constants.ErrorType.MAC')
  - [READ](#F-CSLibrary-Constants-ErrorType-READ 'CSLibrary.Constants.ErrorType.READ')
  - [UNKNOWN](#F-CSLibrary-Constants-ErrorType-UNKNOWN 'CSLibrary.Constants.ErrorType.UNKNOWN')
  - [WRITE](#F-CSLibrary-Constants-ErrorType-WRITE 'CSLibrary.Constants.ErrorType.WRITE')
- [Ext1SensorType](#T-CSLibrary-Structures-Ext1SensorType 'CSLibrary.Structures.Ext1SensorType')
  - [ACExcitation](#F-CSLibrary-Structures-Ext1SensorType-ACExcitation 'CSLibrary.Structures.Ext1SensorType.ACExcitation')
  - [HighImpedanceInput](#F-CSLibrary-Structures-Ext1SensorType-HighImpedanceInput 'CSLibrary.Structures.Ext1SensorType.HighImpedanceInput')
  - [LinerResistiveSensor](#F-CSLibrary-Structures-Ext1SensorType-LinerResistiveSensor 'CSLibrary.Structures.Ext1SensorType.LinerResistiveSensor')
- [Ext2SensorType](#T-CSLibrary-Structures-Ext2SensorType 'CSLibrary.Structures.Ext2SensorType')
  - [HighImpedanceInput](#F-CSLibrary-Structures-Ext2SensorType-HighImpedanceInput 'CSLibrary.Structures.Ext2SensorType.HighImpedanceInput')
  - [LinerConductiveSensor](#F-CSLibrary-Structures-Ext2SensorType-LinerConductiveSensor 'CSLibrary.Structures.Ext2SensorType.LinerConductiveSensor')
- [ExtendedKillCommand](#T-CSLibrary-Constants-ExtendedKillCommand 'CSLibrary.Constants.ExtendedKillCommand')
  - [DISABLE_PERMALOCK](#F-CSLibrary-Constants-ExtendedKillCommand-DISABLE_PERMALOCK 'CSLibrary.Constants.ExtendedKillCommand.DISABLE_PERMALOCK')
  - [DISABLE_USER_MEMORY](#F-CSLibrary-Constants-ExtendedKillCommand-DISABLE_USER_MEMORY 'CSLibrary.Constants.ExtendedKillCommand.DISABLE_USER_MEMORY')
  - [NORMAL](#F-CSLibrary-Constants-ExtendedKillCommand-NORMAL 'CSLibrary.Constants.ExtendedKillCommand.NORMAL')
  - [UNKNOWN](#F-CSLibrary-Constants-ExtendedKillCommand-UNKNOWN 'CSLibrary.Constants.ExtendedKillCommand.UNKNOWN')
  - [UNLOCK_ALL_BANKS](#F-CSLibrary-Constants-ExtendedKillCommand-UNLOCK_ALL_BANKS 'CSLibrary.Constants.ExtendedKillCommand.UNLOCK_ALL_BANKS')
- [FIFOSubcommand](#T-CSLibrary-Structures-FIFOSubcommand 'CSLibrary.Structures.FIFOSubcommand')
  - [ReadData](#F-CSLibrary-Structures-FIFOSubcommand-ReadData 'CSLibrary.Structures.FIFOSubcommand.ReadData')
  - [ReadStatus](#F-CSLibrary-Structures-FIFOSubcommand-ReadStatus 'CSLibrary.Structures.FIFOSubcommand.ReadStatus')
  - [WriteData](#F-CSLibrary-Structures-FIFOSubcommand-WriteData 'CSLibrary.Structures.FIFOSubcommand.WriteData')
- [FeedbackResistor](#T-CSLibrary-Structures-FeedbackResistor 'CSLibrary.Structures.FeedbackResistor')
  - [R185K](#F-CSLibrary-Structures-FeedbackResistor-R185K 'CSLibrary.Structures.FeedbackResistor.R185K')
  - [R1875K](#F-CSLibrary-Structures-FeedbackResistor-R1875K 'CSLibrary.Structures.FeedbackResistor.R1875K')
  - [R3875K](#F-CSLibrary-Structures-FeedbackResistor-R3875K 'CSLibrary.Structures.FeedbackResistor.R3875K')
  - [R400K](#F-CSLibrary-Structures-FeedbackResistor-R400K 'CSLibrary.Structures.FeedbackResistor.R400K')
  - [R875K](#F-CSLibrary-Structures-FeedbackResistor-R875K 'CSLibrary.Structures.FeedbackResistor.R875K')
- [FixedQParms](#T-CSLibrary-Structures-FixedQParms 'CSLibrary.Structures.FixedQParms')
  - [#ctor()](#M-CSLibrary-Structures-FixedQParms-#ctor 'CSLibrary.Structures.FixedQParms.#ctor')
  - [#ctor(qValue,retryCount,toggleTarget,repeatUntilNoTags)](#M-CSLibrary-Structures-FixedQParms-#ctor-System-UInt32,System-UInt32,System-UInt32,System-UInt32- 'CSLibrary.Structures.FixedQParms.#ctor(System.UInt32,System.UInt32,System.UInt32,System.UInt32)')
  - [qValue](#F-CSLibrary-Structures-FixedQParms-qValue 'CSLibrary.Structures.FixedQParms.qValue')
  - [repeatUntilNoTags](#F-CSLibrary-Structures-FixedQParms-repeatUntilNoTags 'CSLibrary.Structures.FixedQParms.repeatUntilNoTags')
  - [retryCount](#F-CSLibrary-Structures-FixedQParms-retryCount 'CSLibrary.Structures.FixedQParms.retryCount')
  - [toggleTarget](#F-CSLibrary-Structures-FixedQParms-toggleTarget 'CSLibrary.Structures.FixedQParms.toggleTarget')
- [FreqAgileMode](#T-CSLibrary-Constants-FreqAgileMode 'CSLibrary.Constants.FreqAgileMode')
  - [DISABLE](#F-CSLibrary-Constants-FreqAgileMode-DISABLE 'CSLibrary.Constants.FreqAgileMode.DISABLE')
  - [ENABLE](#F-CSLibrary-Constants-FreqAgileMode-ENABLE 'CSLibrary.Constants.FreqAgileMode.ENABLE')
- [FrequencyBandParms](#T-CSLibrary-Structures-FrequencyBandParms 'CSLibrary.Structures.FrequencyBandParms')
  - [AffinityBand](#F-CSLibrary-Structures-FrequencyBandParms-AffinityBand 'CSLibrary.Structures.FrequencyBandParms.AffinityBand')
  - [Band](#F-CSLibrary-Structures-FrequencyBandParms-Band 'CSLibrary.Structures.FrequencyBandParms.Band')
  - [DivideRatio](#F-CSLibrary-Structures-FrequencyBandParms-DivideRatio 'CSLibrary.Structures.FrequencyBandParms.DivideRatio')
  - [Frequency](#F-CSLibrary-Structures-FrequencyBandParms-Frequency 'CSLibrary.Structures.FrequencyBandParms.Frequency')
  - [GuardBand](#F-CSLibrary-Structures-FrequencyBandParms-GuardBand 'CSLibrary.Structures.FrequencyBandParms.GuardBand')
  - [MaximumDACBand](#F-CSLibrary-Structures-FrequencyBandParms-MaximumDACBand 'CSLibrary.Structures.FrequencyBandParms.MaximumDACBand')
  - [MinimumDACBand](#F-CSLibrary-Structures-FrequencyBandParms-MinimumDACBand 'CSLibrary.Structures.FrequencyBandParms.MinimumDACBand')
  - [MultiplyRatio](#F-CSLibrary-Structures-FrequencyBandParms-MultiplyRatio 'CSLibrary.Structures.FrequencyBandParms.MultiplyRatio')
  - [State](#F-CSLibrary-Structures-FrequencyBandParms-State 'CSLibrary.Structures.FrequencyBandParms.State')
- [FwUpdateFlags](#T-CSLibrary-Constants-FwUpdateFlags 'CSLibrary.Constants.FwUpdateFlags')
  - [NVMEM_UPDATE](#F-CSLibrary-Constants-FwUpdateFlags-NVMEM_UPDATE 'CSLibrary.Constants.FwUpdateFlags.NVMEM_UPDATE')
  - [NVMEM_UPDATE_APP](#F-CSLibrary-Constants-FwUpdateFlags-NVMEM_UPDATE_APP 'CSLibrary.Constants.FwUpdateFlags.NVMEM_UPDATE_APP')
  - [NVMEM_UPDATE_APP_TEST](#F-CSLibrary-Constants-FwUpdateFlags-NVMEM_UPDATE_APP_TEST 'CSLibrary.Constants.FwUpdateFlags.NVMEM_UPDATE_APP_TEST')
  - [NVMEM_UPDATE_BL](#F-CSLibrary-Constants-FwUpdateFlags-NVMEM_UPDATE_BL 'CSLibrary.Constants.FwUpdateFlags.NVMEM_UPDATE_BL')
  - [NVMEM_UPDATE_BL_TEST](#F-CSLibrary-Constants-FwUpdateFlags-NVMEM_UPDATE_BL_TEST 'CSLibrary.Constants.FwUpdateFlags.NVMEM_UPDATE_BL_TEST')
  - [NVMEM_UPDATE_TEST](#F-CSLibrary-Constants-FwUpdateFlags-NVMEM_UPDATE_TEST 'CSLibrary.Constants.FwUpdateFlags.NVMEM_UPDATE_TEST')
- [G2ConfigParms](#T-CSLibrary-Structures-G2ConfigParms 'CSLibrary.Structures.G2ConfigParms')
  - [#ctor()](#M-CSLibrary-Structures-G2ConfigParms-#ctor 'CSLibrary.Structures.G2ConfigParms.#ctor')
  - [DigitalOutput](#F-CSLibrary-Structures-G2ConfigParms-DigitalOutput 'CSLibrary.Structures.G2ConfigParms.DigitalOutput')
  - [ExternalSupply](#F-CSLibrary-Structures-G2ConfigParms-ExternalSupply 'CSLibrary.Structures.G2ConfigParms.ExternalSupply')
  - [InvertDigitalOutput](#F-CSLibrary-Structures-G2ConfigParms-InvertDigitalOutput 'CSLibrary.Structures.G2ConfigParms.InvertDigitalOutput')
  - [MaxBackscatterStrength](#F-CSLibrary-Structures-G2ConfigParms-MaxBackscatterStrength 'CSLibrary.Structures.G2ConfigParms.MaxBackscatterStrength')
  - [PSFAlarm](#F-CSLibrary-Structures-G2ConfigParms-PSFAlarm 'CSLibrary.Structures.G2ConfigParms.PSFAlarm')
  - [ReadProtectEPC](#F-CSLibrary-Structures-G2ConfigParms-ReadProtectEPC 'CSLibrary.Structures.G2ConfigParms.ReadProtectEPC')
  - [ReadProtectTID](#F-CSLibrary-Structures-G2ConfigParms-ReadProtectTID 'CSLibrary.Structures.G2ConfigParms.ReadProtectTID')
  - [ReadRangeReduction](#F-CSLibrary-Structures-G2ConfigParms-ReadRangeReduction 'CSLibrary.Structures.G2ConfigParms.ReadRangeReduction')
  - [TempetrAlarm](#F-CSLibrary-Structures-G2ConfigParms-TempetrAlarm 'CSLibrary.Structures.G2ConfigParms.TempetrAlarm')
  - [TransparentMode](#F-CSLibrary-Structures-G2ConfigParms-TransparentMode 'CSLibrary.Structures.G2ConfigParms.TransparentMode')
  - [TransparentModeData](#F-CSLibrary-Structures-G2ConfigParms-TransparentModeData 'CSLibrary.Structures.G2ConfigParms.TransparentModeData')
  - [accessPassword](#F-CSLibrary-Structures-G2ConfigParms-accessPassword 'CSLibrary.Structures.G2ConfigParms.accessPassword')
- [GPIOTrigger](#T-CSLibrary-Constants-GPIOTrigger 'CSLibrary.Constants.GPIOTrigger')
  - [ANY_TRIGGER](#F-CSLibrary-Constants-GPIOTrigger-ANY_TRIGGER 'CSLibrary.Constants.GPIOTrigger.ANY_TRIGGER')
  - [FALLING_EDGE](#F-CSLibrary-Constants-GPIOTrigger-FALLING_EDGE 'CSLibrary.Constants.GPIOTrigger.FALLING_EDGE')
  - [OFF](#F-CSLibrary-Constants-GPIOTrigger-OFF 'CSLibrary.Constants.GPIOTrigger.OFF')
  - [RISING_EDGE](#F-CSLibrary-Constants-GPIOTrigger-RISING_EDGE 'CSLibrary.Constants.GPIOTrigger.RISING_EDGE')
- [GPI_INTERRUPT_CALLBACK](#T-CSLibrary-Structures-GPI_INTERRUPT_CALLBACK 'CSLibrary.Structures.GPI_INTERRUPT_CALLBACK')
- [GUID](#T-CSLibrary-Tools-GUID 'CSLibrary.Tools.GUID')
  - [Gen12BitUID()](#M-CSLibrary-Tools-GUID-Gen12BitUID 'CSLibrary.Tools.GUID.Gen12BitUID')
  - [Gen24BitUID()](#M-CSLibrary-Tools-GUID-Gen24BitUID 'CSLibrary.Tools.GUID.Gen24BitUID')
  - [Gen48BitUID()](#M-CSLibrary-Tools-GUID-Gen48BitUID 'CSLibrary.Tools.GUID.Gen48BitUID')
  - [Gen96BitUID()](#M-CSLibrary-Tools-GUID-Gen96BitUID 'CSLibrary.Tools.GUID.Gen96BitUID')
- [GpioPin](#T-CSLibrary-Constants-GpioPin 'CSLibrary.Constants.GpioPin')
  - [PIN_0](#F-CSLibrary-Constants-GpioPin-PIN_0 'CSLibrary.Constants.GpioPin.PIN_0')
  - [PIN_1](#F-CSLibrary-Constants-GpioPin-PIN_1 'CSLibrary.Constants.GpioPin.PIN_1')
  - [PIN_2](#F-CSLibrary-Constants-GpioPin-PIN_2 'CSLibrary.Constants.GpioPin.PIN_2')
  - [PIN_3](#F-CSLibrary-Constants-GpioPin-PIN_3 'CSLibrary.Constants.GpioPin.PIN_3')
- [HST_INV_EPC_MATCH_CFG](#T-CSLibrary-Structures-HST_INV_EPC_MATCH_CFG 'CSLibrary.Structures.HST_INV_EPC_MATCH_CFG')
  - [#ctor()](#M-CSLibrary-Structures-HST_INV_EPC_MATCH_CFG-#ctor 'CSLibrary.Structures.HST_INV_EPC_MATCH_CFG.#ctor')
  - [#ctor(data)](#M-CSLibrary-Structures-HST_INV_EPC_MATCH_CFG-#ctor-System-UInt32- 'CSLibrary.Structures.HST_INV_EPC_MATCH_CFG.#ctor(System.UInt32)')
  - [#ctor(enable,match,offset,count)](#M-CSLibrary-Structures-HST_INV_EPC_MATCH_CFG-#ctor-System-Boolean,System-Boolean,System-UInt32,System-UInt32- 'CSLibrary.Structures.HST_INV_EPC_MATCH_CFG.#ctor(System.Boolean,System.Boolean,System.UInt32,System.UInt32)')
  - [count](#P-CSLibrary-Structures-HST_INV_EPC_MATCH_CFG-count 'CSLibrary.Structures.HST_INV_EPC_MATCH_CFG.count')
  - [enable](#P-CSLibrary-Structures-HST_INV_EPC_MATCH_CFG-enable 'CSLibrary.Structures.HST_INV_EPC_MATCH_CFG.enable')
  - [match](#P-CSLibrary-Structures-HST_INV_EPC_MATCH_CFG-match 'CSLibrary.Structures.HST_INV_EPC_MATCH_CFG.match')
  - [offset](#P-CSLibrary-Structures-HST_INV_EPC_MATCH_CFG-offset 'CSLibrary.Structures.HST_INV_EPC_MATCH_CFG.offset')
  - [value](#P-CSLibrary-Structures-HST_INV_EPC_MATCH_CFG-value 'CSLibrary.Structures.HST_INV_EPC_MATCH_CFG.value')
  - [#cctor()](#M-CSLibrary-Structures-HST_INV_EPC_MATCH_CFG-#cctor 'CSLibrary.Structures.HST_INV_EPC_MATCH_CFG.#cctor')
- [Hex](#T-CSLibrary-Text-Hex 'CSLibrary.Text.Hex')
- [HexEncoding](#T-CSLibrary-Text-HexEncoding 'CSLibrary.Text.HexEncoding')
  - [Compare(source,target)](#M-CSLibrary-Text-HexEncoding-Compare-System-String,System-String- 'CSLibrary.Text.HexEncoding.Compare(System.String,System.String)')
  - [Compare(source,target)](#M-CSLibrary-Text-HexEncoding-Compare-System-Byte[],System-Byte[]- 'CSLibrary.Text.HexEncoding.Compare(System.Byte[],System.Byte[])')
  - [Compare(source,target,size)](#M-CSLibrary-Text-HexEncoding-Compare-System-Byte[],System-Byte[],System-Int32- 'CSLibrary.Text.HexEncoding.Compare(System.Byte[],System.Byte[],System.Int32)')
  - [Compare\`\`1(a,b)](#M-CSLibrary-Text-HexEncoding-Compare``1-``0[],``0[]- 'CSLibrary.Text.HexEncoding.Compare``1(``0[],``0[])')
  - [Copy(src,dst,count)](#M-CSLibrary-Text-HexEncoding-Copy-System-Byte[],System-Byte[],System-Int32- 'CSLibrary.Text.HexEncoding.Copy(System.Byte[],System.Byte[],System.Int32)')
  - [Copy(src,dst,dstIndex,count)](#M-CSLibrary-Text-HexEncoding-Copy-System-Byte[],System-Byte[],System-Int32,System-Int32- 'CSLibrary.Text.HexEncoding.Copy(System.Byte[],System.Byte[],System.Int32,System.Int32)')
  - [Copy(src,srcIndex,dst,dstIndex,count)](#M-CSLibrary-Text-HexEncoding-Copy-System-Byte[],System-Int32,System-Byte[],System-Int32,System-Int32- 'CSLibrary.Text.HexEncoding.Copy(System.Byte[],System.Int32,System.Byte[],System.Int32,System.Int32)')
  - [GenPostMatchMask(hexString)](#M-CSLibrary-Text-HexEncoding-GenPostMatchMask-System-String- 'CSLibrary.Text.HexEncoding.GenPostMatchMask(System.String)')
  - [GenSelectMask(hexString)](#M-CSLibrary-Text-HexEncoding-GenSelectMask-System-String- 'CSLibrary.Text.HexEncoding.GenSelectMask(System.String)')
  - [GetBitCount(hexString)](#M-CSLibrary-Text-HexEncoding-GetBitCount-System-String- 'CSLibrary.Text.HexEncoding.GetBitCount(System.String)')
  - [GetBitCount(bytes)](#M-CSLibrary-Text-HexEncoding-GetBitCount-System-Byte[]- 'CSLibrary.Text.HexEncoding.GetBitCount(System.Byte[])')
  - [GetByteCount(hexString)](#M-CSLibrary-Text-HexEncoding-GetByteCount-System-String- 'CSLibrary.Text.HexEncoding.GetByteCount(System.String)')
  - [GetWordCount(hexString)](#M-CSLibrary-Text-HexEncoding-GetWordCount-System-String- 'CSLibrary.Text.HexEncoding.GetWordCount(System.String)')
  - [HexToByte(hex)](#M-CSLibrary-Text-HexEncoding-HexToByte-System-String- 'CSLibrary.Text.HexEncoding.HexToByte(System.String)')
  - [IsHexFormat(hexString)](#M-CSLibrary-Text-HexEncoding-IsHexFormat-System-String- 'CSLibrary.Text.HexEncoding.IsHexFormat(System.String)')
  - [ToBinary(source,offset,length)](#M-CSLibrary-Text-HexEncoding-ToBinary-System-Byte[],System-UInt32,System-UInt32- 'CSLibrary.Text.HexEncoding.ToBinary(System.Byte[],System.UInt32,System.UInt32)')
  - [ToByte(hexString)](#M-CSLibrary-Text-HexEncoding-ToByte-System-String- 'CSLibrary.Text.HexEncoding.ToByte(System.String)')
  - [ToBytes(hexString)](#M-CSLibrary-Text-HexEncoding-ToBytes-System-String- 'CSLibrary.Text.HexEncoding.ToBytes(System.String)')
  - [ToBytes(data)](#M-CSLibrary-Text-HexEncoding-ToBytes-System-UInt16[]- 'CSLibrary.Text.HexEncoding.ToBytes(System.UInt16[])')
  - [ToBytes(data,count)](#M-CSLibrary-Text-HexEncoding-ToBytes-System-UInt16[],System-Int32- 'CSLibrary.Text.HexEncoding.ToBytes(System.UInt16[],System.Int32)')
  - [ToInt16(buffer,offset)](#M-CSLibrary-Text-HexEncoding-ToInt16-System-Byte[],System-Int32- 'CSLibrary.Text.HexEncoding.ToInt16(System.Byte[],System.Int32)')
  - [ToShorts(Input)](#M-CSLibrary-Text-HexEncoding-ToShorts-System-Byte[]- 'CSLibrary.Text.HexEncoding.ToShorts(System.Byte[])')
  - [ToString(bytes)](#M-CSLibrary-Text-HexEncoding-ToString-System-Byte[]- 'CSLibrary.Text.HexEncoding.ToString(System.Byte[])')
  - [ToString(bytes,length)](#M-CSLibrary-Text-HexEncoding-ToString-System-Byte[],System-Int32- 'CSLibrary.Text.HexEncoding.ToString(System.Byte[],System.Int32)')
  - [ToString(bytes,offset,count)](#M-CSLibrary-Text-HexEncoding-ToString-System-Byte[],System-UInt32,System-UInt32- 'CSLibrary.Text.HexEncoding.ToString(System.Byte[],System.UInt32,System.UInt32)')
  - [ToString(data)](#M-CSLibrary-Text-HexEncoding-ToString-System-UInt16[]- 'CSLibrary.Text.HexEncoding.ToString(System.UInt16[])')
  - [ToString(data,offset,count)](#M-CSLibrary-Text-HexEncoding-ToString-System-UInt16[],System-UInt32,System-UInt32- 'CSLibrary.Text.HexEncoding.ToString(System.UInt16[],System.UInt32,System.UInt32)')
  - [ToUInt16(buffer,offset)](#M-CSLibrary-Text-HexEncoding-ToUInt16-System-Byte[],System-Int32- 'CSLibrary.Text.HexEncoding.ToUInt16(System.Byte[],System.Int32)')
  - [ToUInt32(buffer,offset)](#M-CSLibrary-Text-HexEncoding-ToUInt32-System-Byte[],System-Int32- 'CSLibrary.Text.HexEncoding.ToUInt32(System.Byte[],System.Int32)')
  - [ToUInt32(hexString)](#M-CSLibrary-Text-HexEncoding-ToUInt32-System-String- 'CSLibrary.Text.HexEncoding.ToUInt32(System.String)')
  - [ToUInt64(buffer,offset)](#M-CSLibrary-Text-HexEncoding-ToUInt64-System-Byte[],System-Int32- 'CSLibrary.Text.HexEncoding.ToUInt64(System.Byte[],System.Int32)')
  - [ToUshort(str)](#M-CSLibrary-Text-HexEncoding-ToUshort-System-String- 'CSLibrary.Text.HexEncoding.ToUshort(System.String)')
  - [ToUshorts(Input)](#M-CSLibrary-Text-HexEncoding-ToUshorts-System-Byte[]- 'CSLibrary.Text.HexEncoding.ToUshorts(System.Byte[])')
  - [ToUshorts(Input)](#M-CSLibrary-Text-HexEncoding-ToUshorts-System-String- 'CSLibrary.Text.HexEncoding.ToUshorts(System.String)')
- [HighLevelInterface](#T-CSLibrary-HighLevelInterface 'CSLibrary.HighLevelInterface')
  - [#ctor()](#M-CSLibrary-HighLevelInterface-#ctor 'CSLibrary.HighLevelInterface.#ctor')
  - [AUSTableOfFreq](#F-CSLibrary-HighLevelInterface-AUSTableOfFreq 'CSLibrary.HighLevelInterface.AUSTableOfFreq')
  - [AUS_CHN_CNT](#F-CSLibrary-HighLevelInterface-AUS_CHN_CNT 'CSLibrary.HighLevelInterface.AUS_CHN_CNT')
  - [BR1_CHN_CNT](#F-CSLibrary-HighLevelInterface-BR1_CHN_CNT 'CSLibrary.HighLevelInterface.BR1_CHN_CNT')
  - [BR2_CHN_CNT](#F-CSLibrary-HighLevelInterface-BR2_CHN_CNT 'CSLibrary.HighLevelInterface.BR2_CHN_CNT')
  - [BR3_CHN_CNT](#F-CSLibrary-HighLevelInterface-BR3_CHN_CNT 'CSLibrary.HighLevelInterface.BR3_CHN_CNT')
  - [BR4_CHN_CNT](#F-CSLibrary-HighLevelInterface-BR4_CHN_CNT 'CSLibrary.HighLevelInterface.BR4_CHN_CNT')
  - [BR5_CHN_CNT](#F-CSLibrary-HighLevelInterface-BR5_CHN_CNT 'CSLibrary.HighLevelInterface.BR5_CHN_CNT')
  - [CHN10TableOfFreq](#F-CSLibrary-HighLevelInterface-CHN10TableOfFreq 'CSLibrary.HighLevelInterface.CHN10TableOfFreq')
  - [CHN11TableOfFreq](#F-CSLibrary-HighLevelInterface-CHN11TableOfFreq 'CSLibrary.HighLevelInterface.CHN11TableOfFreq')
  - [CHN12TableOfFreq](#F-CSLibrary-HighLevelInterface-CHN12TableOfFreq 'CSLibrary.HighLevelInterface.CHN12TableOfFreq')
  - [CHN1TableOfFreq](#F-CSLibrary-HighLevelInterface-CHN1TableOfFreq 'CSLibrary.HighLevelInterface.CHN1TableOfFreq')
  - [CHN2TableOfFreq](#F-CSLibrary-HighLevelInterface-CHN2TableOfFreq 'CSLibrary.HighLevelInterface.CHN2TableOfFreq')
  - [CHN3TableOfFreq](#F-CSLibrary-HighLevelInterface-CHN3TableOfFreq 'CSLibrary.HighLevelInterface.CHN3TableOfFreq')
  - [CHN4TableOfFreq](#F-CSLibrary-HighLevelInterface-CHN4TableOfFreq 'CSLibrary.HighLevelInterface.CHN4TableOfFreq')
  - [CHN5TableOfFreq](#F-CSLibrary-HighLevelInterface-CHN5TableOfFreq 'CSLibrary.HighLevelInterface.CHN5TableOfFreq')
  - [CHN6TableOfFreq](#F-CSLibrary-HighLevelInterface-CHN6TableOfFreq 'CSLibrary.HighLevelInterface.CHN6TableOfFreq')
  - [CHN7TableOfFreq](#F-CSLibrary-HighLevelInterface-CHN7TableOfFreq 'CSLibrary.HighLevelInterface.CHN7TableOfFreq')
  - [CHN8TableOfFreq](#F-CSLibrary-HighLevelInterface-CHN8TableOfFreq 'CSLibrary.HighLevelInterface.CHN8TableOfFreq')
  - [CHN9TableOfFreq](#F-CSLibrary-HighLevelInterface-CHN9TableOfFreq 'CSLibrary.HighLevelInterface.CHN9TableOfFreq')
  - [CHNTableOfFreq](#F-CSLibrary-HighLevelInterface-CHNTableOfFreq 'CSLibrary.HighLevelInterface.CHNTableOfFreq')
  - [CN1_CHN_CNT](#F-CSLibrary-HighLevelInterface-CN1_CHN_CNT 'CSLibrary.HighLevelInterface.CN1_CHN_CNT')
  - [CN9_CHN_CNT](#F-CSLibrary-HighLevelInterface-CN9_CHN_CNT 'CSLibrary.HighLevelInterface.CN9_CHN_CNT')
  - [CN_CHN_CNT](#F-CSLibrary-HighLevelInterface-CN_CHN_CNT 'CSLibrary.HighLevelInterface.CN_CHN_CNT')
  - [CurrentPath](#F-CSLibrary-HighLevelInterface-CurrentPath 'CSLibrary.HighLevelInterface.CurrentPath')
  - [ETSITableOfFreq](#F-CSLibrary-HighLevelInterface-ETSITableOfFreq 'CSLibrary.HighLevelInterface.ETSITableOfFreq')
  - [ETSIUPPERBAND_CHN_CNT](#F-CSLibrary-HighLevelInterface-ETSIUPPERBAND_CHN_CNT 'CSLibrary.HighLevelInterface.ETSIUPPERBAND_CHN_CNT')
  - [ETSI_CHN_CNT](#F-CSLibrary-HighLevelInterface-ETSI_CHN_CNT 'CSLibrary.HighLevelInterface.ETSI_CHN_CNT')
  - [FCCTableOfFreq](#F-CSLibrary-HighLevelInterface-FCCTableOfFreq 'CSLibrary.HighLevelInterface.FCCTableOfFreq')
  - [FCC_CHN_CNT](#F-CSLibrary-HighLevelInterface-FCC_CHN_CNT 'CSLibrary.HighLevelInterface.FCC_CHN_CNT')
  - [HKTableOfFreq](#F-CSLibrary-HighLevelInterface-HKTableOfFreq 'CSLibrary.HighLevelInterface.HKTableOfFreq')
  - [HK_CHN_CNT](#F-CSLibrary-HighLevelInterface-HK_CHN_CNT 'CSLibrary.HighLevelInterface.HK_CHN_CNT')
  - [IDATableOfFreq](#F-CSLibrary-HighLevelInterface-IDATableOfFreq 'CSLibrary.HighLevelInterface.IDATableOfFreq')
  - [IDA_CHN_CNT](#F-CSLibrary-HighLevelInterface-IDA_CHN_CNT 'CSLibrary.HighLevelInterface.IDA_CHN_CNT')
  - [IDTableOfFreq](#F-CSLibrary-HighLevelInterface-IDTableOfFreq 'CSLibrary.HighLevelInterface.IDTableOfFreq')
  - [ID_CHN_CNT](#F-CSLibrary-HighLevelInterface-ID_CHN_CNT 'CSLibrary.HighLevelInterface.ID_CHN_CNT')
  - [JE_CHN_CNT](#F-CSLibrary-HighLevelInterface-JE_CHN_CNT 'CSLibrary.HighLevelInterface.JE_CHN_CNT')
  - [JPN2012TableOfFreq](#F-CSLibrary-HighLevelInterface-JPN2012TableOfFreq 'CSLibrary.HighLevelInterface.JPN2012TableOfFreq')
  - [JPN2012_CHN_CNT](#F-CSLibrary-HighLevelInterface-JPN2012_CHN_CNT 'CSLibrary.HighLevelInterface.JPN2012_CHN_CNT')
  - [JPN2019TableOfFreq](#F-CSLibrary-HighLevelInterface-JPN2019TableOfFreq 'CSLibrary.HighLevelInterface.JPN2019TableOfFreq')
  - [JPN2019_CHN_CNT](#F-CSLibrary-HighLevelInterface-JPN2019_CHN_CNT 'CSLibrary.HighLevelInterface.JPN2019_CHN_CNT')
  - [JPNTableOfFreq](#F-CSLibrary-HighLevelInterface-JPNTableOfFreq 'CSLibrary.HighLevelInterface.JPNTableOfFreq')
  - [JPNTableOfFreq29](#F-CSLibrary-HighLevelInterface-JPNTableOfFreq29 'CSLibrary.HighLevelInterface.JPNTableOfFreq29')
  - [JPN_CHN_CNT](#F-CSLibrary-HighLevelInterface-JPN_CHN_CNT 'CSLibrary.HighLevelInterface.JPN_CHN_CNT')
  - [KRTableOfFreq](#F-CSLibrary-HighLevelInterface-KRTableOfFreq 'CSLibrary.HighLevelInterface.KRTableOfFreq')
  - [KR_CHN_CNT](#F-CSLibrary-HighLevelInterface-KR_CHN_CNT 'CSLibrary.HighLevelInterface.KR_CHN_CNT')
  - [LH1_CHN_CNT](#F-CSLibrary-HighLevelInterface-LH1_CHN_CNT 'CSLibrary.HighLevelInterface.LH1_CHN_CNT')
  - [LH2_CHN_CNT](#F-CSLibrary-HighLevelInterface-LH2_CHN_CNT 'CSLibrary.HighLevelInterface.LH2_CHN_CNT')
  - [LH_CHN_CNT](#F-CSLibrary-HighLevelInterface-LH_CHN_CNT 'CSLibrary.HighLevelInterface.LH_CHN_CNT')
  - [MYSTableOfFreq](#F-CSLibrary-HighLevelInterface-MYSTableOfFreq 'CSLibrary.HighLevelInterface.MYSTableOfFreq')
  - [MYS_CHN_CNT](#F-CSLibrary-HighLevelInterface-MYS_CHN_CNT 'CSLibrary.HighLevelInterface.MYS_CHN_CNT')
  - [MacErrorCode](#F-CSLibrary-HighLevelInterface-MacErrorCode 'CSLibrary.HighLevelInterface.MacErrorCode')
  - [NZ_CHN_CNT](#F-CSLibrary-HighLevelInterface-NZ_CHN_CNT 'CSLibrary.HighLevelInterface.NZ_CHN_CNT')
  - [OFCATableOfFreq](#F-CSLibrary-HighLevelInterface-OFCATableOfFreq 'CSLibrary.HighLevelInterface.OFCATableOfFreq')
  - [OFCA_CHN_CNT](#F-CSLibrary-HighLevelInterface-OFCA_CHN_CNT 'CSLibrary.HighLevelInterface.OFCA_CHN_CNT')
  - [PH_CHN_CNT](#F-CSLibrary-HighLevelInterface-PH_CHN_CNT 'CSLibrary.HighLevelInterface.PH_CHN_CNT')
  - [SAHopping_CHN_CNT](#F-CSLibrary-HighLevelInterface-SAHopping_CHN_CNT 'CSLibrary.HighLevelInterface.SAHopping_CHN_CNT')
  - [TW2_CHN_CNT](#F-CSLibrary-HighLevelInterface-TW2_CHN_CNT 'CSLibrary.HighLevelInterface.TW2_CHN_CNT')
  - [TWTableOfFreq](#F-CSLibrary-HighLevelInterface-TWTableOfFreq 'CSLibrary.HighLevelInterface.TWTableOfFreq')
  - [TW_CHN_CNT](#F-CSLibrary-HighLevelInterface-TW_CHN_CNT 'CSLibrary.HighLevelInterface.TW_CHN_CNT')
  - [UH1TableOfFreq](#F-CSLibrary-HighLevelInterface-UH1TableOfFreq 'CSLibrary.HighLevelInterface.UH1TableOfFreq')
  - [UH1_CHN_CNT](#F-CSLibrary-HighLevelInterface-UH1_CHN_CNT 'CSLibrary.HighLevelInterface.UH1_CHN_CNT')
  - [UH2TableOfFreq](#F-CSLibrary-HighLevelInterface-UH2TableOfFreq 'CSLibrary.HighLevelInterface.UH2TableOfFreq')
  - [UH2_CHN_CNT](#F-CSLibrary-HighLevelInterface-UH2_CHN_CNT 'CSLibrary.HighLevelInterface.UH2_CHN_CNT')
  - [VE_CHN_CNT](#F-CSLibrary-HighLevelInterface-VE_CHN_CNT 'CSLibrary.HighLevelInterface.VE_CHN_CNT')
  - [ZATableOfFreq](#F-CSLibrary-HighLevelInterface-ZATableOfFreq 'CSLibrary.HighLevelInterface.ZATableOfFreq')
  - [ZA_CHN_CNT](#F-CSLibrary-HighLevelInterface-ZA_CHN_CNT 'CSLibrary.HighLevelInterface.ZA_CHN_CNT')
  - [_RegisterAccessLock](#F-CSLibrary-HighLevelInterface-_RegisterAccessLock 'CSLibrary.HighLevelInterface._RegisterAccessLock')
  - [m_oem_machine](#F-CSLibrary-HighLevelInterface-m_oem_machine 'CSLibrary.HighLevelInterface.m_oem_machine')
  - [AntennaPortSequence](#P-CSLibrary-HighLevelInterface-AntennaPortSequence 'CSLibrary.HighLevelInterface.AntennaPortSequence')
  - [AntennaSequenceSize](#P-CSLibrary-HighLevelInterface-AntennaSequenceSize 'CSLibrary.HighLevelInterface.AntennaSequenceSize')
  - [CurrentFreqChannelIndex](#P-CSLibrary-HighLevelInterface-CurrentFreqChannelIndex 'CSLibrary.HighLevelInterface.CurrentFreqChannelIndex')
  - [CurrentInterfaceType](#P-CSLibrary-HighLevelInterface-CurrentInterfaceType 'CSLibrary.HighLevelInterface.CurrentInterfaceType')
  - [DeviceNameOrIP](#P-CSLibrary-HighLevelInterface-DeviceNameOrIP 'CSLibrary.HighLevelInterface.DeviceNameOrIP')
  - [IPAddress](#P-CSLibrary-HighLevelInterface-IPAddress 'CSLibrary.HighLevelInterface.IPAddress')
  - [IsFixedChannel](#P-CSLibrary-HighLevelInterface-IsFixedChannel 'CSLibrary.HighLevelInterface.IsFixedChannel')
  - [IsFixedChannelOnly](#P-CSLibrary-HighLevelInterface-IsFixedChannelOnly 'CSLibrary.HighLevelInterface.IsFixedChannelOnly')
  - [IsHoppingChannelOnly](#P-CSLibrary-HighLevelInterface-IsHoppingChannelOnly 'CSLibrary.HighLevelInterface.IsHoppingChannelOnly')
  - [LBT_ON](#P-CSLibrary-HighLevelInterface-LBT_ON 'CSLibrary.HighLevelInterface.LBT_ON')
  - [LastErrorMessage](#P-CSLibrary-HighLevelInterface-LastErrorMessage 'CSLibrary.HighLevelInterface.LastErrorMessage')
  - [LastResultCode](#P-CSLibrary-HighLevelInterface-LastResultCode 'CSLibrary.HighLevelInterface.LastResultCode')
  - [MacAddress](#P-CSLibrary-HighLevelInterface-MacAddress 'CSLibrary.HighLevelInterface.MacAddress')
  - [Name](#P-CSLibrary-HighLevelInterface-Name 'CSLibrary.HighLevelInterface.Name')
  - [Options](#P-CSLibrary-HighLevelInterface-Options 'CSLibrary.HighLevelInterface.Options')
  - [ReconnectTimeout](#P-CSLibrary-HighLevelInterface-ReconnectTimeout 'CSLibrary.HighLevelInterface.ReconnectTimeout')
  - [SelectedChannel](#P-CSLibrary-HighLevelInterface-SelectedChannel 'CSLibrary.HighLevelInterface.SelectedChannel')
  - [SelectedFrequencyBand](#P-CSLibrary-HighLevelInterface-SelectedFrequencyBand 'CSLibrary.HighLevelInterface.SelectedFrequencyBand')
  - [SelectedLinkProfile](#P-CSLibrary-HighLevelInterface-SelectedLinkProfile 'CSLibrary.HighLevelInterface.SelectedLinkProfile')
  - [SelectedPowerLevel](#P-CSLibrary-HighLevelInterface-SelectedPowerLevel 'CSLibrary.HighLevelInterface.SelectedPowerLevel')
  - [SelectedRegionCode](#P-CSLibrary-HighLevelInterface-SelectedRegionCode 'CSLibrary.HighLevelInterface.SelectedRegionCode')
  - [State](#P-CSLibrary-HighLevelInterface-State 'CSLibrary.HighLevelInterface.State')
  - [COMM_AdapterCommand()](#M-CSLibrary-HighLevelInterface-COMM_AdapterCommand-CSLibrary-HighLevelInterface-READERCMD- 'CSLibrary.HighLevelInterface.COMM_AdapterCommand(CSLibrary.HighLevelInterface.READERCMD)')
  - [COMM_Disconnect()](#M-CSLibrary-HighLevelInterface-COMM_Disconnect 'CSLibrary.HighLevelInterface.COMM_Disconnect')
  - [COMM_READER_Recv()](#M-CSLibrary-HighLevelInterface-COMM_READER_Recv-System-Byte[],System-Int32,System-Int32,System-UInt32- 'CSLibrary.HighLevelInterface.COMM_READER_Recv(System.Byte[],System.Int32,System.Int32,System.UInt32)')
  - [COMM_READER_Send()](#M-CSLibrary-HighLevelInterface-COMM_READER_Send-System-Byte[],System-Int32,System-Int32,System-Int32- 'CSLibrary.HighLevelInterface.COMM_READER_Send(System.Byte[],System.Int32,System.Int32,System.Int32)')
  - [COMM_Reboot(cmd)](#M-CSLibrary-HighLevelInterface-COMM_Reboot 'CSLibrary.HighLevelInterface.COMM_Reboot')
  - [CUST_18K6CTagBlockWrite(bank,offset,count,data,password,retry,flags)](#M-CSLibrary-HighLevelInterface-CUST_18K6CTagBlockWrite-CSLibrary-Constants-MemoryBank,System-UInt32,System-UInt32,System-UInt16[],System-UInt32,System-UInt32,System-UInt32,CSLibrary-Constants-SelectFlags- 'CSLibrary.HighLevelInterface.CUST_18K6CTagBlockWrite(CSLibrary.Constants.MemoryBank,System.UInt32,System.UInt32,System.UInt16[],System.UInt32,System.UInt32,System.UInt32,CSLibrary.Constants.SelectFlags)')
  - [CUST_18K6CTagWrite(bank,offset,count,data,password,retry,flags)](#M-CSLibrary-HighLevelInterface-CUST_18K6CTagWrite-CSLibrary-Constants-MemoryBank,System-UInt32,System-UInt32,System-UInt16[],System-UInt32,System-UInt32,System-UInt32,CSLibrary-Constants-SelectFlags- 'CSLibrary.HighLevelInterface.CUST_18K6CTagWrite(CSLibrary.Constants.MemoryBank,System.UInt32,System.UInt32,System.UInt16[],System.UInt32,System.UInt32,System.UInt32,CSLibrary.Constants.SelectFlags)')
  - [CheckStatus()](#M-CSLibrary-HighLevelInterface-CheckStatus-CSLibrary-Structures-DEVICE_STATUS@- 'CSLibrary.HighLevelInterface.CheckStatus(CSLibrary.Structures.DEVICE_STATUS@)')
  - [CheckStatus()](#M-CSLibrary-HighLevelInterface-CheckStatus-System-String,System-String,CSLibrary-Structures-DEVICE_STATUS@- 'CSLibrary.HighLevelInterface.CheckStatus(System.String,System.String,CSLibrary.Structures.DEVICE_STATUS@)')
  - [CheckStatus()](#M-CSLibrary-HighLevelInterface-CheckStatus-System-String,CSLibrary-Structures-DEVICE_STATUS@- 'CSLibrary.HighLevelInterface.CheckStatus(System.String,CSLibrary.Structures.DEVICE_STATUS@)')
  - [ColdChain_StartTemperatureLog(StartTime,Interval,Offset)](#M-CSLibrary-HighLevelInterface-ColdChain_StartTemperatureLog-System-UInt32,System-UInt16,System-Byte- 'CSLibrary.HighLevelInterface.ColdChain_StartTemperatureLog(System.UInt32,System.UInt16,System.Byte)')
  - [Connect()](#M-CSLibrary-HighLevelInterface-Connect 'CSLibrary.HighLevelInterface.Connect')
  - [Connect(ipAddress,timeout,libraryDebug)](#M-CSLibrary-HighLevelInterface-Connect-System-String,System-Int32,System-Boolean- 'CSLibrary.HighLevelInterface.Connect(System.String,System.Int32,System.Boolean)')
  - [CreateDynamicQParms(startQValue,maxQValue,minQValue,retryCount,toggleTarget,thresholdMultiplier)](#M-CSLibrary-HighLevelInterface-CreateDynamicQParms-System-UInt32,System-UInt32,System-UInt32,System-UInt32,System-UInt32,System-UInt32- 'CSLibrary.HighLevelInterface.CreateDynamicQParms(System.UInt32,System.UInt32,System.UInt32,System.UInt32,System.UInt32,System.UInt32)')
  - [CreateFixedQParms(qValue,retryCount,toggleTarget,repeatUntilNoTags)](#M-CSLibrary-HighLevelInterface-CreateFixedQParms-System-UInt32,System-UInt32,System-UInt32,System-UInt32- 'CSLibrary.HighLevelInterface.CreateFixedQParms(System.UInt32,System.UInt32,System.UInt32,System.UInt32)')
  - [CreatePostMatchCriteria(Offset,Count,match,bTarget)](#M-CSLibrary-HighLevelInterface-CreatePostMatchCriteria-System-UInt32,System-UInt32,System-Boolean,System-Byte[]- 'CSLibrary.HighLevelInterface.CreatePostMatchCriteria(System.UInt32,System.UInt32,System.Boolean,System.Byte[])')
  - [CreateSelectCriteria(Offset,Count,bnk,action,target,enableTruncate,bTarget)](#M-CSLibrary-HighLevelInterface-CreateSelectCriteria-System-UInt32,System-UInt32,CSLibrary-Constants-MemoryBank,CSLibrary-Constants-Action,CSLibrary-Constants-Target,System-Boolean,System-Byte[]- 'CSLibrary.HighLevelInterface.CreateSelectCriteria(System.UInt32,System.UInt32,CSLibrary.Constants.MemoryBank,CSLibrary.Constants.Action,CSLibrary.Constants.Target,System.Boolean,System.Byte[])')
  - [CreateTagGroup(select,session,target)](#M-CSLibrary-HighLevelInterface-CreateTagGroup-CSLibrary-Constants-Selected,CSLibrary-Constants-Session,CSLibrary-Constants-SessionTarget- 'CSLibrary.HighLevelInterface.CreateTagGroup(CSLibrary.Constants.Selected,CSLibrary.Constants.Session,CSLibrary.Constants.SessionTarget)')
  - [DirectSearch(IP)](#M-CSLibrary-HighLevelInterface-DirectSearch-System-Net-IPAddress,CSLibrary-Net-DeviceInfomation@- 'CSLibrary.HighLevelInterface.DirectSearch(System.Net.IPAddress,CSLibrary.Net.DeviceInfomation@)')
  - [Disconnect()](#M-CSLibrary-HighLevelInterface-Disconnect 'CSLibrary.HighLevelInterface.Disconnect')
  - [Dispose()](#M-CSLibrary-HighLevelInterface-Dispose 'CSLibrary.HighLevelInterface.Dispose')
  - [EngBypassReadRegister(address,value)](#M-CSLibrary-HighLevelInterface-EngBypassReadRegister-System-UInt16,System-UInt16@- 'CSLibrary.HighLevelInterface.EngBypassReadRegister(System.UInt16,System.UInt16@)')
  - [EngBypassWriteRegister(address,value)](#M-CSLibrary-HighLevelInterface-EngBypassWriteRegister-System-UInt16,System-UInt16- 'CSLibrary.HighLevelInterface.EngBypassWriteRegister(System.UInt16,System.UInt16)')
  - [EngGetReaderDataFormat(mode)](#M-CSLibrary-HighLevelInterface-EngGetReaderDataFormat-CSLibrary-Constants-ResponseMode@- 'CSLibrary.HighLevelInterface.EngGetReaderDataFormat(CSLibrary.Constants.ResponseMode@)')
  - [EngModeEnable(Password)](#M-CSLibrary-HighLevelInterface-EngModeEnable-System-String- 'CSLibrary.HighLevelInterface.EngModeEnable(System.String)')
  - [EngReadOemData(address,value)](#M-CSLibrary-HighLevelInterface-EngReadOemData-System-UInt32,System-UInt32@- 'CSLibrary.HighLevelInterface.EngReadOemData(System.UInt32,System.UInt32@)')
  - [EngReadRegister()](#M-CSLibrary-HighLevelInterface-EngReadRegister-System-UInt16,System-UInt32@- 'CSLibrary.HighLevelInterface.EngReadRegister(System.UInt16,System.UInt32@)')
  - [EngSetInterface(Mode)](#M-CSLibrary-HighLevelInterface-EngSetInterface-CSLibrary-HighLevelInterface-INTERFACETYPE- 'CSLibrary.HighLevelInterface.EngSetInterface(CSLibrary.HighLevelInterface.INTERFACETYPE)')
  - [EngSetReaderDataFormat(mode)](#M-CSLibrary-HighLevelInterface-EngSetReaderDataFormat-CSLibrary-Constants-ResponseMode- 'CSLibrary.HighLevelInterface.EngSetReaderDataFormat(CSLibrary.Constants.ResponseMode)')
  - [EngTest_TransmitRandomData(enable,randomPattern)](#M-CSLibrary-HighLevelInterface-EngTest_TransmitRandomData-System-Boolean,System-Int32- 'CSLibrary.HighLevelInterface.EngTest_TransmitRandomData(System.Boolean,System.Int32)')
  - [EngUpdateFirmware(length,pImage,flags)](#M-CSLibrary-HighLevelInterface-EngUpdateFirmware-System-UInt32,CSLibrary-Structures-NonVolatileMemoryBlock[],CSLibrary-Constants-FwUpdateFlags- 'CSLibrary.HighLevelInterface.EngUpdateFirmware(System.UInt32,CSLibrary.Structures.NonVolatileMemoryBlock[],CSLibrary.Constants.FwUpdateFlags)')
  - [EngWriteOemData(address,value)](#M-CSLibrary-HighLevelInterface-EngWriteOemData-System-UInt32,System-UInt32- 'CSLibrary.HighLevelInterface.EngWriteOemData(System.UInt32,System.UInt32)')
  - [EngWriteRegister()](#M-CSLibrary-HighLevelInterface-EngWriteRegister-System-UInt16,System-UInt32- 'CSLibrary.HighLevelInterface.EngWriteRegister(System.UInt16,System.UInt32)')
  - [Finalize()](#M-CSLibrary-HighLevelInterface-Finalize 'CSLibrary.HighLevelInterface.Finalize')
  - [FireOnFirmwareUpgradeEvent(Offset)](#M-CSLibrary-HighLevelInterface-FireOnFirmwareUpgradeEvent-System-UInt64- 'CSLibrary.HighLevelInterface.FireOnFirmwareUpgradeEvent(System.UInt64)')
  - [ForceReset()](#M-CSLibrary-HighLevelInterface-ForceReset 'CSLibrary.HighLevelInterface.ForceReset')
  - [ForceReset()](#M-CSLibrary-HighLevelInterface-ForceReset-System-String,System-String- 'CSLibrary.HighLevelInterface.ForceReset(System.String,System.String)')
  - [ForceReset()](#M-CSLibrary-HighLevelInterface-ForceReset-System-String- 'CSLibrary.HighLevelInterface.ForceReset(System.String)')
  - [GetActiveLinkProfile(region)](#M-CSLibrary-HighLevelInterface-GetActiveLinkProfile-CSLibrary-Constants-RegionCode- 'CSLibrary.HighLevelInterface.GetActiveLinkProfile(CSLibrary.Constants.RegionCode)')
  - [GetActiveLinkProfile()](#M-CSLibrary-HighLevelInterface-GetActiveLinkProfile 'CSLibrary.HighLevelInterface.GetActiveLinkProfile')
  - [GetActiveLinkProfileInfo()](#M-CSLibrary-HighLevelInterface-GetActiveLinkProfileInfo 'CSLibrary.HighLevelInterface.GetActiveLinkProfileInfo')
  - [GetActiveLinkProfileInfo()](#M-CSLibrary-HighLevelInterface-GetActiveLinkProfileInfo-System-UInt32- 'CSLibrary.HighLevelInterface.GetActiveLinkProfileInfo(System.UInt32)')
  - [GetActiveMaxPowerLevel()](#M-CSLibrary-HighLevelInterface-GetActiveMaxPowerLevel-CSLibrary-Constants-RegionCode- 'CSLibrary.HighLevelInterface.GetActiveMaxPowerLevel(CSLibrary.Constants.RegionCode)')
  - [GetActiveMaxPowerLevel()](#M-CSLibrary-HighLevelInterface-GetActiveMaxPowerLevel 'CSLibrary.HighLevelInterface.GetActiveMaxPowerLevel')
  - [GetActiveRegionCode()](#M-CSLibrary-HighLevelInterface-GetActiveRegionCode 'CSLibrary.HighLevelInterface.GetActiveRegionCode')
  - [GetAntennaPortConfiguration(antenna)](#M-CSLibrary-HighLevelInterface-GetAntennaPortConfiguration-CSLibrary-Structures-AntennaPortConfig@- 'CSLibrary.HighLevelInterface.GetAntennaPortConfiguration(CSLibrary.Structures.AntennaPortConfig@)')
  - [GetAntennaPortConfiguration(port,antenna)](#M-CSLibrary-HighLevelInterface-GetAntennaPortConfiguration-System-UInt32,CSLibrary-Structures-AntennaPortConfig@- 'CSLibrary.HighLevelInterface.GetAntennaPortConfiguration(System.UInt32,CSLibrary.Structures.AntennaPortConfig@)')
  - [GetAntennaPortStatus(portStatus)](#M-CSLibrary-HighLevelInterface-GetAntennaPortStatus-CSLibrary-Structures-AntennaPortStatus- 'CSLibrary.HighLevelInterface.GetAntennaPortStatus(CSLibrary.Structures.AntennaPortStatus)')
  - [GetAntennaPortStatus(port,portStatus)](#M-CSLibrary-HighLevelInterface-GetAntennaPortStatus-System-UInt32,CSLibrary-Structures-AntennaPortStatus- 'CSLibrary.HighLevelInterface.GetAntennaPortStatus(System.UInt32,CSLibrary.Structures.AntennaPortStatus)')
  - [GetAntennaSequence(sequence)](#M-CSLibrary-HighLevelInterface-GetAntennaSequence-System-Byte[]- 'CSLibrary.HighLevelInterface.GetAntennaSequence(System.Byte[])')
  - [GetAntennaSequence(sequence,sequenceSize,mode)](#M-CSLibrary-HighLevelInterface-GetAntennaSequence-System-Byte[],System-UInt32@,CSLibrary-Constants-AntennaSequenceMode@- 'CSLibrary.HighLevelInterface.GetAntennaSequence(System.Byte[],System.UInt32@,CSLibrary.Constants.AntennaSequenceMode@)')
  - [GetAvailableFrequencyTable(region)](#M-CSLibrary-HighLevelInterface-GetAvailableFrequencyTable-CSLibrary-Constants-RegionCode- 'CSLibrary.HighLevelInterface.GetAvailableFrequencyTable(CSLibrary.Constants.RegionCode)')
  - [GetAvailableFrequencyTable()](#M-CSLibrary-HighLevelInterface-GetAvailableFrequencyTable 'CSLibrary.HighLevelInterface.GetAvailableFrequencyTable')
  - [GetBootLoaderVersion(version)](#M-CSLibrary-HighLevelInterface-GetBootLoaderVersion-CSLibrary-Structures-Version- 'CSLibrary.HighLevelInterface.GetBootLoaderVersion(CSLibrary.Structures.Version)')
  - [GetC51AppVersion()](#M-CSLibrary-HighLevelInterface-GetC51AppVersion 'CSLibrary.HighLevelInterface.GetC51AppVersion')
  - [GetC51BootLoaderVersion()](#M-CSLibrary-HighLevelInterface-GetC51BootLoaderVersion 'CSLibrary.HighLevelInterface.GetC51BootLoaderVersion')
  - [GetCSLibraryVersion()](#M-CSLibrary-HighLevelInterface-GetCSLibraryVersion 'CSLibrary.HighLevelInterface.GetCSLibraryVersion')
  - [GetCountryCode()](#M-CSLibrary-HighLevelInterface-GetCountryCode-System-UInt32@- 'CSLibrary.HighLevelInterface.GetCountryCode(System.UInt32@)')
  - [GetCurrentFrequencyTable()](#M-CSLibrary-HighLevelInterface-GetCurrentFrequencyTable 'CSLibrary.HighLevelInterface.GetCurrentFrequencyTable')
  - [GetCurrentLinkProfile()](#M-CSLibrary-HighLevelInterface-GetCurrentLinkProfile-System-UInt32@- 'CSLibrary.HighLevelInterface.GetCurrentLinkProfile(System.UInt32@)')
  - [GetCurrentSingulationAlgorithm(SingulationAlgorithm)](#M-CSLibrary-HighLevelInterface-GetCurrentSingulationAlgorithm-CSLibrary-Constants-SingulationAlgorithm@- 'CSLibrary.HighLevelInterface.GetCurrentSingulationAlgorithm(CSLibrary.Constants.SingulationAlgorithm@)')
  - [GetCurrentTemperature()](#M-CSLibrary-HighLevelInterface-GetCurrentTemperature-CSLibrary-Structures-TemperatureParms@- 'CSLibrary.HighLevelInterface.GetCurrentTemperature(CSLibrary.Structures.TemperatureParms@)')
  - [GetDriverVersion()](#M-CSLibrary-HighLevelInterface-GetDriverVersion 'CSLibrary.HighLevelInterface.GetDriverVersion')
  - [GetDynamicQParms(parms)](#M-CSLibrary-HighLevelInterface-GetDynamicQParms-CSLibrary-Structures-DynamicQParms- 'CSLibrary.HighLevelInterface.GetDynamicQParms(CSLibrary.Structures.DynamicQParms)')
  - [GetFirmwareVersion()](#M-CSLibrary-HighLevelInterface-GetFirmwareVersion 'CSLibrary.HighLevelInterface.GetFirmwareVersion')
  - [GetFixedQParms(fixedQ)](#M-CSLibrary-HighLevelInterface-GetFixedQParms-CSLibrary-Structures-FixedQParms- 'CSLibrary.HighLevelInterface.GetFixedQParms(CSLibrary.Structures.FixedQParms)')
  - [GetForwardPowerLevel()](#M-CSLibrary-HighLevelInterface-GetForwardPowerLevel-System-UInt32@- 'CSLibrary.HighLevelInterface.GetForwardPowerLevel(System.UInt32@)')
  - [GetFrequencyBand(m_radioIndex,frequencySelector,freq)](#M-CSLibrary-HighLevelInterface-GetFrequencyBand-System-UInt32,CSLibrary-Structures-FrequencyBandParms@- 'CSLibrary.HighLevelInterface.GetFrequencyBand(System.UInt32,CSLibrary.Structures.FrequencyBandParms@)')
  - [GetFrequencyCompensation(coeff0,coeff1)](#M-CSLibrary-HighLevelInterface-GetFrequencyCompensation-System-UInt32@,System-UInt32@- 'CSLibrary.HighLevelInterface.GetFrequencyCompensation(System.UInt32@,System.UInt32@)')
  - [GetGPI0(ip,HL)](#M-CSLibrary-HighLevelInterface-GetGPI0-System-String,System-Int32@- 'CSLibrary.HighLevelInterface.GetGPI0(System.String,System.Int32@)')
  - [GetGPI0Status()](#M-CSLibrary-HighLevelInterface-GetGPI0Status-System-String,System-Boolean@- 'CSLibrary.HighLevelInterface.GetGPI0Status(System.String,System.Boolean@)')
  - [GetGPI0Status()](#M-CSLibrary-HighLevelInterface-GetGPI0Status-System-Boolean@- 'CSLibrary.HighLevelInterface.GetGPI0Status(System.Boolean@)')
  - [GetGPI1Status()](#M-CSLibrary-HighLevelInterface-GetGPI1Status-System-String,System-Boolean@- 'CSLibrary.HighLevelInterface.GetGPI1Status(System.String,System.Boolean@)')
  - [GetGPI1Status()](#M-CSLibrary-HighLevelInterface-GetGPI1Status-System-Boolean@- 'CSLibrary.HighLevelInterface.GetGPI1Status(System.Boolean@)')
  - [GetGPI2Status()](#M-CSLibrary-HighLevelInterface-GetGPI2Status-System-String,System-Boolean@- 'CSLibrary.HighLevelInterface.GetGPI2Status(System.String,System.Boolean@)')
  - [GetGPI2Status()](#M-CSLibrary-HighLevelInterface-GetGPI2Status-System-Boolean@- 'CSLibrary.HighLevelInterface.GetGPI2Status(System.Boolean@)')
  - [GetGPI3Status()](#M-CSLibrary-HighLevelInterface-GetGPI3Status-System-String,System-Boolean@- 'CSLibrary.HighLevelInterface.GetGPI3Status(System.String,System.Boolean@)')
  - [GetGPI3Status()](#M-CSLibrary-HighLevelInterface-GetGPI3Status-System-Boolean@- 'CSLibrary.HighLevelInterface.GetGPI3Status(System.Boolean@)')
  - [GetGPIInterrupt()](#M-CSLibrary-HighLevelInterface-GetGPIInterrupt-System-String,CSLibrary-Constants-GPIOTrigger@,CSLibrary-Constants-GPIOTrigger@- 'CSLibrary.HighLevelInterface.GetGPIInterrupt(System.String,CSLibrary.Constants.GPIOTrigger@,CSLibrary.Constants.GPIOTrigger@)')
  - [GetGPIInterrupt()](#M-CSLibrary-HighLevelInterface-GetGPIInterrupt-CSLibrary-Constants-GPIOTrigger@,CSLibrary-Constants-GPIOTrigger@- 'CSLibrary.HighLevelInterface.GetGPIInterrupt(CSLibrary.Constants.GPIOTrigger@,CSLibrary.Constants.GPIOTrigger@)')
  - [GetGPIStatus()](#M-CSLibrary-HighLevelInterface-GetGPIStatus-System-String,System-Boolean@,System-Boolean@,System-Boolean@,System-Boolean@- 'CSLibrary.HighLevelInterface.GetGPIStatus(System.String,System.Boolean@,System.Boolean@,System.Boolean@,System.Boolean@)')
  - [GetGPIStatus()](#M-CSLibrary-HighLevelInterface-GetGPIStatus-System-String,System-Boolean@,System-Boolean@- 'CSLibrary.HighLevelInterface.GetGPIStatus(System.String,System.Boolean@,System.Boolean@)')
  - [GetGPIStatus()](#M-CSLibrary-HighLevelInterface-GetGPIStatus-System-Boolean@,System-Boolean@,System-Boolean@,System-Boolean@- 'CSLibrary.HighLevelInterface.GetGPIStatus(System.Boolean@,System.Boolean@,System.Boolean@,System.Boolean@)')
  - [GetGPIStatus()](#M-CSLibrary-HighLevelInterface-GetGPIStatus-System-Boolean@,System-Boolean@- 'CSLibrary.HighLevelInterface.GetGPIStatus(System.Boolean@,System.Boolean@)')
  - [GetGPO0Status()](#M-CSLibrary-HighLevelInterface-GetGPO0Status-System-String,System-Boolean@- 'CSLibrary.HighLevelInterface.GetGPO0Status(System.String,System.Boolean@)')
  - [GetGPO0Status()](#M-CSLibrary-HighLevelInterface-GetGPO0Status-System-Boolean@- 'CSLibrary.HighLevelInterface.GetGPO0Status(System.Boolean@)')
  - [GetGPO1Status()](#M-CSLibrary-HighLevelInterface-GetGPO1Status-System-String,System-Boolean@- 'CSLibrary.HighLevelInterface.GetGPO1Status(System.String,System.Boolean@)')
  - [GetGPO1Status()](#M-CSLibrary-HighLevelInterface-GetGPO1Status-System-Boolean@- 'CSLibrary.HighLevelInterface.GetGPO1Status(System.Boolean@)')
  - [GetGPO2Status()](#M-CSLibrary-HighLevelInterface-GetGPO2Status-System-String,System-Boolean@- 'CSLibrary.HighLevelInterface.GetGPO2Status(System.String,System.Boolean@)')
  - [GetGPO2Status()](#M-CSLibrary-HighLevelInterface-GetGPO2Status-System-Boolean@- 'CSLibrary.HighLevelInterface.GetGPO2Status(System.Boolean@)')
  - [GetGPO3Status()](#M-CSLibrary-HighLevelInterface-GetGPO3Status-System-String,System-Boolean@- 'CSLibrary.HighLevelInterface.GetGPO3Status(System.String,System.Boolean@)')
  - [GetGPO3Status()](#M-CSLibrary-HighLevelInterface-GetGPO3Status-System-Boolean@- 'CSLibrary.HighLevelInterface.GetGPO3Status(System.Boolean@)')
  - [GetGPOStatus()](#M-CSLibrary-HighLevelInterface-GetGPOStatus-System-String,System-Boolean@,System-Boolean@,System-Boolean@,System-Boolean@- 'CSLibrary.HighLevelInterface.GetGPOStatus(System.String,System.Boolean@,System.Boolean@,System.Boolean@,System.Boolean@)')
  - [GetGPOStatus()](#M-CSLibrary-HighLevelInterface-GetGPOStatus-System-String,System-Boolean@,System-Boolean@- 'CSLibrary.HighLevelInterface.GetGPOStatus(System.String,System.Boolean@,System.Boolean@)')
  - [GetGPOStatus()](#M-CSLibrary-HighLevelInterface-GetGPOStatus-System-Boolean@,System-Boolean@,System-Boolean@,System-Boolean@- 'CSLibrary.HighLevelInterface.GetGPOStatus(System.Boolean@,System.Boolean@,System.Boolean@,System.Boolean@)')
  - [GetGPOStatus()](#M-CSLibrary-HighLevelInterface-GetGPOStatus-System-Boolean@,System-Boolean@- 'CSLibrary.HighLevelInterface.GetGPOStatus(System.Boolean@,System.Boolean@)')
  - [GetHardwareVersion()](#M-CSLibrary-HighLevelInterface-GetHardwareVersion 'CSLibrary.HighLevelInterface.GetHardwareVersion')
  - [GetImageVersion()](#M-CSLibrary-HighLevelInterface-GetImageVersion 'CSLibrary.HighLevelInterface.GetImageVersion')
  - [GetImageVersion(version)](#M-CSLibrary-HighLevelInterface-GetImageVersion-CSLibrary-Structures-Version- 'CSLibrary.HighLevelInterface.GetImageVersion(CSLibrary.Structures.Version)')
  - [GetInventoryCount(count)](#M-CSLibrary-HighLevelInterface-GetInventoryCount-System-UInt32@- 'CSLibrary.HighLevelInterface.GetInventoryCount(System.UInt32@)')
  - [GetInventoryCount(antennaPort,count)](#M-CSLibrary-HighLevelInterface-GetInventoryCount-System-UInt32,System-UInt32@- 'CSLibrary.HighLevelInterface.GetInventoryCount(System.UInt32,System.UInt32@)')
  - [GetInventoryDuration(duration)](#M-CSLibrary-HighLevelInterface-GetInventoryDuration-System-UInt32@- 'CSLibrary.HighLevelInterface.GetInventoryDuration(System.UInt32@)')
  - [GetInventoryDuration(antennaPort,duration)](#M-CSLibrary-HighLevelInterface-GetInventoryDuration-System-UInt32,System-UInt32@- 'CSLibrary.HighLevelInterface.GetInventoryDuration(System.UInt32,System.UInt32@)')
  - [GetMacErrorCode()](#M-CSLibrary-HighLevelInterface-GetMacErrorCode-System-UInt32@- 'CSLibrary.HighLevelInterface.GetMacErrorCode(System.UInt32@)')
  - [GetManufactureDate()](#M-CSLibrary-HighLevelInterface-GetManufactureDate 'CSLibrary.HighLevelInterface.GetManufactureDate')
  - [GetMaxForwardPowerLevel(MaxPowerLevel)](#M-CSLibrary-HighLevelInterface-GetMaxForwardPowerLevel-System-UInt32@- 'CSLibrary.HighLevelInterface.GetMaxForwardPowerLevel(System.UInt32@)')
  - [GetOperationMode(cycles,mode,sequenceSize)](#M-CSLibrary-HighLevelInterface-GetOperationMode-System-UInt16@,CSLibrary-Constants-AntennaSequenceMode@,System-UInt32@- 'CSLibrary.HighLevelInterface.GetOperationMode(System.UInt16@,CSLibrary.Constants.AntennaSequenceMode@,System.UInt32@)')
  - [GetOperationMode(mode)](#M-CSLibrary-HighLevelInterface-GetOperationMode-CSLibrary-Constants-RadioOperationMode@- 'CSLibrary.HighLevelInterface.GetOperationMode(CSLibrary.Constants.RadioOperationMode@)')
  - [GetPCBAssemblyCode()](#M-CSLibrary-HighLevelInterface-GetPCBAssemblyCode 'CSLibrary.HighLevelInterface.GetPCBAssemblyCode')
  - [GetPowerLevel()](#M-CSLibrary-HighLevelInterface-GetPowerLevel-System-UInt32@- 'CSLibrary.HighLevelInterface.GetPowerLevel(System.UInt32@)')
  - [GetPowerLevel()](#M-CSLibrary-HighLevelInterface-GetPowerLevel-System-UInt32,System-UInt32@- 'CSLibrary.HighLevelInterface.GetPowerLevel(System.UInt32,System.UInt32@)')
  - [GetPowerState(state)](#M-CSLibrary-HighLevelInterface-GetPowerState-CSLibrary-Constants-RadioPowerState@- 'CSLibrary.HighLevelInterface.GetPowerState(CSLibrary.Constants.RadioPowerState@)')
  - [GetRadioResponseDataMode()](#M-CSLibrary-HighLevelInterface-GetRadioResponseDataMode-CSLibrary-Constants-ResponseMode@- 'CSLibrary.HighLevelInterface.GetRadioResponseDataMode(CSLibrary.Constants.ResponseMode@)')
  - [GetReadTagIndStatus(mode)](#M-CSLibrary-HighLevelInterface-GetReadTagIndStatus-System-Byte@- 'CSLibrary.HighLevelInterface.GetReadTagIndStatus(System.Byte@)')
  - [GetReversedPowerLevel()](#M-CSLibrary-HighLevelInterface-GetReversedPowerLevel-System-Int32@- 'CSLibrary.HighLevelInterface.GetReversedPowerLevel(System.Int32@)')
  - [GetRfidCompensation()](#M-CSLibrary-HighLevelInterface-GetRfidCompensation-System-Boolean@- 'CSLibrary.HighLevelInterface.GetRfidCompensation(System.Boolean@)')
  - [GetRfidLibraryVersion()](#M-CSLibrary-HighLevelInterface-GetRfidLibraryVersion 'CSLibrary.HighLevelInterface.GetRfidLibraryVersion')
  - [GetSelectCriteria(pCrit)](#M-CSLibrary-HighLevelInterface-GetSelectCriteria-CSLibrary-Structures-SelectCriteria@- 'CSLibrary.HighLevelInterface.GetSelectCriteria(CSLibrary.Structures.SelectCriteria@)')
  - [GetSiliconVersion()](#M-CSLibrary-HighLevelInterface-GetSiliconVersion 'CSLibrary.HighLevelInterface.GetSiliconVersion')
  - [GetSingulationAlgorithmParms(alg,parms)](#M-CSLibrary-HighLevelInterface-GetSingulationAlgorithmParms-CSLibrary-Constants-SingulationAlgorithm,CSLibrary-Structures-SingulationAlgorithmParms- 'CSLibrary.HighLevelInterface.GetSingulationAlgorithmParms(CSLibrary.Constants.SingulationAlgorithm,CSLibrary.Structures.SingulationAlgorithmParms)')
  - [GetSoftwareMaxPowerLevel()](#M-CSLibrary-HighLevelInterface-GetSoftwareMaxPowerLevel-CSLibrary-Constants-RegionCode- 'CSLibrary.HighLevelInterface.GetSoftwareMaxPowerLevel(CSLibrary.Constants.RegionCode)')
  - [GetTagGroup(tagGroup)](#M-CSLibrary-HighLevelInterface-GetTagGroup-CSLibrary-Structures-TagGroup- 'CSLibrary.HighLevelInterface.GetTagGroup(CSLibrary.Structures.TagGroup)')
  - [GetTemperatureCompensation(coeff0,coeff1)](#M-CSLibrary-HighLevelInterface-GetTemperatureCompensation-System-UInt32@,System-UInt32@- 'CSLibrary.HighLevelInterface.GetTemperatureCompensation(System.UInt32@,System.UInt32@)')
  - [GetThresholdTemperature()](#M-CSLibrary-HighLevelInterface-GetThresholdTemperature-CSLibrary-Structures-ThresholdTemperatureParms@- 'CSLibrary.HighLevelInterface.GetThresholdTemperature(CSLibrary.Structures.ThresholdTemperatureParms@)')
  - [MacBypassReadRegister(address,value)](#M-CSLibrary-HighLevelInterface-MacBypassReadRegister-System-UInt16,System-UInt16@- 'CSLibrary.HighLevelInterface.MacBypassReadRegister(System.UInt16,System.UInt16@)')
  - [MacBypassWriteRegister(address,value)](#M-CSLibrary-HighLevelInterface-MacBypassWriteRegister-System-UInt16,System-UInt16- 'CSLibrary.HighLevelInterface.MacBypassWriteRegister(System.UInt16,System.UInt16)')
  - [MacClearError()](#M-CSLibrary-HighLevelInterface-MacClearError 'CSLibrary.HighLevelInterface.MacClearError')
  - [MacErrorIsFatal(macErrCode)](#M-CSLibrary-HighLevelInterface-MacErrorIsFatal-System-UInt32- 'CSLibrary.HighLevelInterface.MacErrorIsFatal(System.UInt32)')
  - [MacErrorIsNegligible(macErrCode)](#M-CSLibrary-HighLevelInterface-MacErrorIsNegligible-System-UInt32- 'CSLibrary.HighLevelInterface.MacErrorIsNegligible(System.UInt32)')
  - [MacErrorIsOverheat(macErrCode)](#M-CSLibrary-HighLevelInterface-MacErrorIsOverheat-System-UInt32- 'CSLibrary.HighLevelInterface.MacErrorIsOverheat(System.UInt32)')
  - [MacReadOemData(address,data)](#M-CSLibrary-HighLevelInterface-MacReadOemData-System-UInt32,System-UInt32[]- 'CSLibrary.HighLevelInterface.MacReadOemData(System.UInt32,System.UInt32[])')
  - [MacWriteOemData(address,data)](#M-CSLibrary-HighLevelInterface-MacWriteOemData-System-UInt32,System-UInt32[]- 'CSLibrary.HighLevelInterface.MacWriteOemData(System.UInt32,System.UInt32[])')
  - [R2000RSSINB(cmd)](#M-CSLibrary-HighLevelInterface-R2000RSSINB-System-Byte- 'CSLibrary.HighLevelInterface.R2000RSSINB(System.Byte)')
  - [Reconnect(FailureRetries)](#M-CSLibrary-HighLevelInterface-Reconnect-System-Int32- 'CSLibrary.HighLevelInterface.Reconnect(System.Int32)')
  - [SERIAL_Recv(buffer,offset,size,timeout)](#M-CSLibrary-HighLevelInterface-SERIAL_Recv-System-Byte[],System-Int32,System-Int32,System-UInt32- 'CSLibrary.HighLevelInterface.SERIAL_Recv(System.Byte[],System.Int32,System.Int32,System.UInt32)')
  - [SERIAL_Recv(buffer,offset,size,timeout)](#M-CSLibrary-HighLevelInterface-SERIAL_Recv-System-IO-Ports-SerialPort,System-Byte[],System-Int32,System-Int32,System-UInt32- 'CSLibrary.HighLevelInterface.SERIAL_Recv(System.IO.Ports.SerialPort,System.Byte[],System.Int32,System.Int32,System.UInt32)')
  - [Set5VPowerOut(onoff)](#M-CSLibrary-HighLevelInterface-Set5VPowerOut-System-Boolean- 'CSLibrary.HighLevelInterface.Set5VPowerOut(System.Boolean)')
  - [SetAgileChannels(prof)](#M-CSLibrary-HighLevelInterface-SetAgileChannels-CSLibrary-Constants-RegionCode- 'CSLibrary.HighLevelInterface.SetAgileChannels(CSLibrary.Constants.RegionCode)')
  - [SetAntennaPortConfiguration(antenna)](#M-CSLibrary-HighLevelInterface-SetAntennaPortConfiguration-CSLibrary-Structures-AntennaPortConfig- 'CSLibrary.HighLevelInterface.SetAntennaPortConfiguration(CSLibrary.Structures.AntennaPortConfig)')
  - [SetAntennaPortConfiguration(port,antenna)](#M-CSLibrary-HighLevelInterface-SetAntennaPortConfiguration-System-UInt32,CSLibrary-Structures-AntennaPortConfig- 'CSLibrary.HighLevelInterface.SetAntennaPortConfiguration(System.UInt32,CSLibrary.Structures.AntennaPortConfig)')
  - [SetAntennaPortState(portState)](#M-CSLibrary-HighLevelInterface-SetAntennaPortState-CSLibrary-Constants-AntennaPortState- 'CSLibrary.HighLevelInterface.SetAntennaPortState(CSLibrary.Constants.AntennaPortState)')
  - [SetAntennaPortState(port,portState)](#M-CSLibrary-HighLevelInterface-SetAntennaPortState-System-UInt32,CSLibrary-Constants-AntennaPortState- 'CSLibrary.HighLevelInterface.SetAntennaPortState(System.UInt32,CSLibrary.Constants.AntennaPortState)')
  - [SetAntennaPortStatus(portStatus)](#M-CSLibrary-HighLevelInterface-SetAntennaPortStatus-CSLibrary-Structures-AntennaPortStatus- 'CSLibrary.HighLevelInterface.SetAntennaPortStatus(CSLibrary.Structures.AntennaPortStatus)')
  - [SetAntennaPortStatus(port,portStatus)](#M-CSLibrary-HighLevelInterface-SetAntennaPortStatus-System-UInt32,CSLibrary-Structures-AntennaPortStatus- 'CSLibrary.HighLevelInterface.SetAntennaPortStatus(System.UInt32,CSLibrary.Structures.AntennaPortStatus)')
  - [SetAntennaSequence(sequenceSize)](#M-CSLibrary-HighLevelInterface-SetAntennaSequence-System-Int32- 'CSLibrary.HighLevelInterface.SetAntennaSequence(System.Int32)')
  - [SetAntennaSequence(sequence)](#M-CSLibrary-HighLevelInterface-SetAntennaSequence-System-Byte[]- 'CSLibrary.HighLevelInterface.SetAntennaSequence(System.Byte[])')
  - [SetAntennaSequence(sequence,sequenceSize,sequenceMode)](#M-CSLibrary-HighLevelInterface-SetAntennaSequence-System-Byte[],System-UInt32,CSLibrary-Constants-AntennaSequenceMode- 'CSLibrary.HighLevelInterface.SetAntennaSequence(System.Byte[],System.UInt32,CSLibrary.Constants.AntennaSequenceMode)')
  - [SetAntennaSequence(sequenceMode,sequenceSize,sequence)](#M-CSLibrary-HighLevelInterface-SetAntennaSequence-CSLibrary-Constants-AntennaSequenceMode,System-Int32,CSLibrary-Structures-AntennaPortCollections- 'CSLibrary.HighLevelInterface.SetAntennaSequence(CSLibrary.Constants.AntennaSequenceMode,System.Int32,CSLibrary.Structures.AntennaPortCollections)')
  - [SetCurrentLinkProfile(profile)](#M-CSLibrary-HighLevelInterface-SetCurrentLinkProfile-System-UInt32- 'CSLibrary.HighLevelInterface.SetCurrentLinkProfile(System.UInt32)')
  - [SetCurrentLinkProfile(profile,extenLO)](#M-CSLibrary-HighLevelInterface-SetCurrentLinkProfile-System-UInt32,System-Boolean- 'CSLibrary.HighLevelInterface.SetCurrentLinkProfile(System.UInt32,System.Boolean)')
  - [SetCurrentSingulationAlgorithm(SingulationAlgorithm)](#M-CSLibrary-HighLevelInterface-SetCurrentSingulationAlgorithm-CSLibrary-Constants-SingulationAlgorithm- 'CSLibrary.HighLevelInterface.SetCurrentSingulationAlgorithm(CSLibrary.Constants.SingulationAlgorithm)')
  - [SetDefaultAntennaList()](#M-CSLibrary-HighLevelInterface-SetDefaultAntennaList 'CSLibrary.HighLevelInterface.SetDefaultAntennaList')
  - [SetDynamicQParms(StartQValue,MinQValue,MaxQValue,RetryCount,ThresholdMultiplier,ToggleTarget)](#M-CSLibrary-HighLevelInterface-SetDynamicQParms-System-UInt32,System-UInt32,System-UInt32,System-UInt32,System-UInt32,System-UInt32- 'CSLibrary.HighLevelInterface.SetDynamicQParms(System.UInt32,System.UInt32,System.UInt32,System.UInt32,System.UInt32,System.UInt32)')
  - [SetDynamicQParms()](#M-CSLibrary-HighLevelInterface-SetDynamicQParms-CSLibrary-Structures-DynamicQParms- 'CSLibrary.HighLevelInterface.SetDynamicQParms(CSLibrary.Structures.DynamicQParms)')
  - [SetDynamicQParms()](#M-CSLibrary-HighLevelInterface-SetDynamicQParms 'CSLibrary.HighLevelInterface.SetDynamicQParms')
  - [SetFixedChannel(prof,channel,LBTcfg)](#M-CSLibrary-HighLevelInterface-SetFixedChannel-CSLibrary-Constants-RegionCode,System-UInt32,CSLibrary-Constants-LBT- 'CSLibrary.HighLevelInterface.SetFixedChannel(CSLibrary.Constants.RegionCode,System.UInt32,CSLibrary.Constants.LBT)')
  - [SetFixedChannel(channel,LBTcfg)](#M-CSLibrary-HighLevelInterface-SetFixedChannel-System-UInt32,CSLibrary-Constants-LBT- 'CSLibrary.HighLevelInterface.SetFixedChannel(System.UInt32,CSLibrary.Constants.LBT)')
  - [SetFixedChannel(channel)](#M-CSLibrary-HighLevelInterface-SetFixedChannel-System-UInt32- 'CSLibrary.HighLevelInterface.SetFixedChannel(System.UInt32)')
  - [SetFixedChannel()](#M-CSLibrary-HighLevelInterface-SetFixedChannel 'CSLibrary.HighLevelInterface.SetFixedChannel')
  - [SetFixedQParms(QValue,RetryCount,ToggleTarget,RepeatUnitNoTags)](#M-CSLibrary-HighLevelInterface-SetFixedQParms-System-UInt32,System-UInt32,System-UInt32,System-UInt32- 'CSLibrary.HighLevelInterface.SetFixedQParms(System.UInt32,System.UInt32,System.UInt32,System.UInt32)')
  - [SetFixedQParms()](#M-CSLibrary-HighLevelInterface-SetFixedQParms-CSLibrary-Structures-FixedQParms- 'CSLibrary.HighLevelInterface.SetFixedQParms(CSLibrary.Structures.FixedQParms)')
  - [SetFixedQParms()](#M-CSLibrary-HighLevelInterface-SetFixedQParms 'CSLibrary.HighLevelInterface.SetFixedQParms')
  - [SetFrequencyBand(m_radioIndex,frequencySelector,config,multdiv,pllcc)](#M-CSLibrary-HighLevelInterface-SetFrequencyBand-System-UInt32,CSLibrary-Constants-BandState,System-UInt32,System-UInt32- 'CSLibrary.HighLevelInterface.SetFrequencyBand(System.UInt32,CSLibrary.Constants.BandState,System.UInt32,System.UInt32)')
  - [SetFrequencyCompensation(coeff0,coeff1)](#M-CSLibrary-HighLevelInterface-SetFrequencyCompensation-System-UInt32,System-UInt32- 'CSLibrary.HighLevelInterface.SetFrequencyCompensation(System.UInt32,System.UInt32)')
  - [SetGPI0Interrupt()](#M-CSLibrary-HighLevelInterface-SetGPI0Interrupt-System-String,CSLibrary-Constants-GPIOTrigger- 'CSLibrary.HighLevelInterface.SetGPI0Interrupt(System.String,CSLibrary.Constants.GPIOTrigger)')
  - [SetGPI0Interrupt()](#M-CSLibrary-HighLevelInterface-SetGPI0Interrupt-CSLibrary-Constants-GPIOTrigger- 'CSLibrary.HighLevelInterface.SetGPI0Interrupt(CSLibrary.Constants.GPIOTrigger)')
  - [SetGPI1Interrupt()](#M-CSLibrary-HighLevelInterface-SetGPI1Interrupt-System-String,CSLibrary-Constants-GPIOTrigger- 'CSLibrary.HighLevelInterface.SetGPI1Interrupt(System.String,CSLibrary.Constants.GPIOTrigger)')
  - [SetGPI1Interrupt()](#M-CSLibrary-HighLevelInterface-SetGPI1Interrupt-CSLibrary-Constants-GPIOTrigger- 'CSLibrary.HighLevelInterface.SetGPI1Interrupt(CSLibrary.Constants.GPIOTrigger)')
  - [SetGPO0Status()](#M-CSLibrary-HighLevelInterface-SetGPO0Status-System-Boolean- 'CSLibrary.HighLevelInterface.SetGPO0Status(System.Boolean)')
  - [SetGPO0Status()](#M-CSLibrary-HighLevelInterface-SetGPO0Status-System-String,System-Boolean- 'CSLibrary.HighLevelInterface.SetGPO0Status(System.String,System.Boolean)')
  - [SetGPO1Status()](#M-CSLibrary-HighLevelInterface-SetGPO1Status-System-Boolean- 'CSLibrary.HighLevelInterface.SetGPO1Status(System.Boolean)')
  - [SetGPO1Status()](#M-CSLibrary-HighLevelInterface-SetGPO1Status-System-String,System-Boolean- 'CSLibrary.HighLevelInterface.SetGPO1Status(System.String,System.Boolean)')
  - [SetGPO2Status()](#M-CSLibrary-HighLevelInterface-SetGPO2Status-System-Boolean- 'CSLibrary.HighLevelInterface.SetGPO2Status(System.Boolean)')
  - [SetGPO2Status()](#M-CSLibrary-HighLevelInterface-SetGPO2Status-System-String,System-Boolean- 'CSLibrary.HighLevelInterface.SetGPO2Status(System.String,System.Boolean)')
  - [SetGPO3Status()](#M-CSLibrary-HighLevelInterface-SetGPO3Status-System-Boolean- 'CSLibrary.HighLevelInterface.SetGPO3Status(System.Boolean)')
  - [SetGPO3Status()](#M-CSLibrary-HighLevelInterface-SetGPO3Status-System-String,System-Boolean- 'CSLibrary.HighLevelInterface.SetGPO3Status(System.String,System.Boolean)')
  - [SetHoppingChannels(prof)](#M-CSLibrary-HighLevelInterface-SetHoppingChannels-CSLibrary-Constants-RegionCode- 'CSLibrary.HighLevelInterface.SetHoppingChannels(CSLibrary.Constants.RegionCode)')
  - [SetHoppingChannels()](#M-CSLibrary-HighLevelInterface-SetHoppingChannels 'CSLibrary.HighLevelInterface.SetHoppingChannels')
  - [SetInterface(Mode)](#M-CSLibrary-HighLevelInterface-SetInterface-CSLibrary-HighLevelInterface-INTERFACETYPE- 'CSLibrary.HighLevelInterface.SetInterface(CSLibrary.HighLevelInterface.INTERFACETYPE)')
  - [SetInventoryCycle(cycle)](#M-CSLibrary-HighLevelInterface-SetInventoryCycle-System-UInt32- 'CSLibrary.HighLevelInterface.SetInventoryCycle(System.UInt32)')
  - [SetInventoryCycle(antennaPort,cycle)](#M-CSLibrary-HighLevelInterface-SetInventoryCycle-System-UInt32,System-UInt32- 'CSLibrary.HighLevelInterface.SetInventoryCycle(System.UInt32,System.UInt32)')
  - [SetInventoryDuration(duration)](#M-CSLibrary-HighLevelInterface-SetInventoryDuration-System-UInt32- 'CSLibrary.HighLevelInterface.SetInventoryDuration(System.UInt32)')
  - [SetInventoryDuration(antennaPort,duration)](#M-CSLibrary-HighLevelInterface-SetInventoryDuration-System-UInt32,System-UInt32- 'CSLibrary.HighLevelInterface.SetInventoryDuration(System.UInt32,System.UInt32)')
  - [SetLNA(rflna_high_comp_norm,rflna_gain_norm,iflna_gain_norm,ifagc_gain_norm,ifagc_gain_norm)](#M-CSLibrary-HighLevelInterface-SetLNA-System-Int32,System-Int32,System-Int32,System-Int32- 'CSLibrary.HighLevelInterface.SetLNA(System.Int32,System.Int32,System.Int32,System.Int32)')
  - [SetMaxForwardPowerLevel(MaxPowerLevel)](#M-CSLibrary-HighLevelInterface-SetMaxForwardPowerLevel-System-UInt32- 'CSLibrary.HighLevelInterface.SetMaxForwardPowerLevel(System.UInt32)')
  - [SetOperationMode(cycles,mode,sequenceSize)](#M-CSLibrary-HighLevelInterface-SetOperationMode-System-UInt16,CSLibrary-Constants-AntennaSequenceMode,System-UInt32- 'CSLibrary.HighLevelInterface.SetOperationMode(System.UInt16,CSLibrary.Constants.AntennaSequenceMode,System.UInt32)')
  - [SetOperationMode(mode)](#M-CSLibrary-HighLevelInterface-SetOperationMode-CSLibrary-Constants-RadioOperationMode- 'CSLibrary.HighLevelInterface.SetOperationMode(CSLibrary.Constants.RadioOperationMode)')
  - [SetOperationMode(operationMode,sequenceMode,sequenceSize)](#M-CSLibrary-HighLevelInterface-SetOperationMode-CSLibrary-Constants-RadioOperationMode,CSLibrary-Constants-AntennaSequenceMode,System-Int32- 'CSLibrary.HighLevelInterface.SetOperationMode(CSLibrary.Constants.RadioOperationMode,CSLibrary.Constants.AntennaSequenceMode,System.Int32)')
  - [SetPostMatchCriteria(postmatch)](#M-CSLibrary-HighLevelInterface-SetPostMatchCriteria-CSLibrary-Structures-SingulationCriterion[]- 'CSLibrary.HighLevelInterface.SetPostMatchCriteria(CSLibrary.Structures.SingulationCriterion[])')
  - [SetPowerLevel(pwrlevel)](#M-CSLibrary-HighLevelInterface-SetPowerLevel-System-UInt32- 'CSLibrary.HighLevelInterface.SetPowerLevel(System.UInt32)')
  - [SetPowerLevel(antennaPort,pwrlevel)](#M-CSLibrary-HighLevelInterface-SetPowerLevel-System-UInt32,System-UInt32- 'CSLibrary.HighLevelInterface.SetPowerLevel(System.UInt32,System.UInt32)')
  - [SetPowerState(powerState)](#M-CSLibrary-HighLevelInterface-SetPowerState-CSLibrary-Constants-RadioPowerState- 'CSLibrary.HighLevelInterface.SetPowerState(CSLibrary.Constants.RadioPowerState)')
  - [SetRadioResponseDataMode(mode)](#M-CSLibrary-HighLevelInterface-SetRadioResponseDataMode-CSLibrary-Constants-ResponseMode- 'CSLibrary.HighLevelInterface.SetRadioResponseDataMode(CSLibrary.Constants.ResponseMode)')
  - [SetReadTagInd(mode)](#M-CSLibrary-HighLevelInterface-SetReadTagInd-System-Byte- 'CSLibrary.HighLevelInterface.SetReadTagInd(System.Byte)')
  - [SetRfidCompensation()](#M-CSLibrary-HighLevelInterface-SetRfidCompensation-System-Boolean- 'CSLibrary.HighLevelInterface.SetRfidCompensation(System.Boolean)')
  - [SetSelectCriteria(critlist)](#M-CSLibrary-HighLevelInterface-SetSelectCriteria-CSLibrary-Structures-SelectCriterion[]- 'CSLibrary.HighLevelInterface.SetSelectCriteria(CSLibrary.Structures.SelectCriterion[])')
  - [SetSingulationAlgorithmParms(alg,parms)](#M-CSLibrary-HighLevelInterface-SetSingulationAlgorithmParms-CSLibrary-Constants-SingulationAlgorithm,CSLibrary-Structures-SingulationAlgorithmParms- 'CSLibrary.HighLevelInterface.SetSingulationAlgorithmParms(CSLibrary.Constants.SingulationAlgorithm,CSLibrary.Structures.SingulationAlgorithmParms)')
  - [SetTagGroup(gpSelect)](#M-CSLibrary-HighLevelInterface-SetTagGroup-CSLibrary-Constants-Selected- 'CSLibrary.HighLevelInterface.SetTagGroup(CSLibrary.Constants.Selected)')
  - [SetTagGroup(gpSelect,gpSession,gpSessionTarget)](#M-CSLibrary-HighLevelInterface-SetTagGroup-CSLibrary-Constants-Selected,CSLibrary-Constants-Session,CSLibrary-Constants-SessionTarget- 'CSLibrary.HighLevelInterface.SetTagGroup(CSLibrary.Constants.Selected,CSLibrary.Constants.Session,CSLibrary.Constants.SessionTarget)')
  - [SetTagGroup(tagGroup)](#M-CSLibrary-HighLevelInterface-SetTagGroup-CSLibrary-Structures-TagGroup- 'CSLibrary.HighLevelInterface.SetTagGroup(CSLibrary.Structures.TagGroup)')
  - [SetTemperatureCompensation(coeff0,coeff1)](#M-CSLibrary-HighLevelInterface-SetTemperatureCompensation-System-UInt32,System-UInt32- 'CSLibrary.HighLevelInterface.SetTemperatureCompensation(System.UInt32,System.UInt32)')
  - [SetThresholdTemperature(ambient,xcver,patemp,padeta)](#M-CSLibrary-HighLevelInterface-SetThresholdTemperature-System-UInt32,System-UInt32,System-UInt32,System-UInt32- 'CSLibrary.HighLevelInterface.SetThresholdTemperature(System.UInt32,System.UInt32,System.UInt32,System.UInt32)')
  - [Setup18K6CBlockWriteRegisters(WriteBank,WriteOffset,WriteSize,WriteBuf,BufOffset)](#M-CSLibrary-HighLevelInterface-Setup18K6CBlockWriteRegisters-CSLibrary-Constants-MemoryBank,System-UInt32,System-UInt32,System-UInt16[],System-UInt32- 'CSLibrary.HighLevelInterface.Setup18K6CBlockWriteRegisters(CSLibrary.Constants.MemoryBank,System.UInt32,System.UInt32,System.UInt16[],System.UInt32)')
  - [StartOperation(opertion,bWait)](#M-CSLibrary-HighLevelInterface-StartOperation-CSLibrary-Constants-Operation,System-Boolean- 'CSLibrary.HighLevelInterface.StartOperation(CSLibrary.Constants.Operation,System.Boolean)')
  - [StartPollGPIStatus()](#M-CSLibrary-HighLevelInterface-StartPollGPIStatus-CSLibrary-Structures-GPI_INTERRUPT_CALLBACK- 'CSLibrary.HighLevelInterface.StartPollGPIStatus(CSLibrary.Structures.GPI_INTERRUPT_CALLBACK)')
  - [StartUdpPollGPIStatus(func)](#M-CSLibrary-HighLevelInterface-StartUdpPollGPIStatus-CSLibrary-Structures-GPI_INTERRUPT_CALLBACK- 'CSLibrary.HighLevelInterface.StartUdpPollGPIStatus(CSLibrary.Structures.GPI_INTERRUPT_CALLBACK)')
  - [StopPollGPIStatus()](#M-CSLibrary-HighLevelInterface-StopPollGPIStatus 'CSLibrary.HighLevelInterface.StopPollGPIStatus')
  - [SyncInventory(tagStopCount,callback,flags)](#M-CSLibrary-HighLevelInterface-SyncInventory-System-Byte,CSLibrary-Structures-InventoryCallbackDelegate,CSLibrary-Constants-SelectFlags- 'CSLibrary.HighLevelInterface.SyncInventory(System.Byte,CSLibrary.Structures.InventoryCallbackDelegate,CSLibrary.Constants.SelectFlags)')
  - [SyncKill(killPassword,killCmd,tagStopCount,callback,flags)](#M-CSLibrary-HighLevelInterface-SyncKill-System-UInt32,CSLibrary-Constants-ExtendedKillCommand,System-Byte,CSLibrary-Structures-TagAccessCallbackDelegate,CSLibrary-Constants-SelectFlags- 'CSLibrary.HighLevelInterface.SyncKill(System.UInt32,CSLibrary.Constants.ExtendedKillCommand,System.Byte,CSLibrary.Structures.TagAccessCallbackDelegate,CSLibrary.Constants.SelectFlags)')
  - [SyncLock(password,kilMemoryBank,accMemoryBank,epcMemoryBank,tidMemoryBank,usrMemoryBank,tagStopCount,callback,flags)](#M-CSLibrary-HighLevelInterface-SyncLock-System-UInt32,CSLibrary-Constants-Permission,CSLibrary-Constants-Permission,CSLibrary-Constants-Permission,CSLibrary-Constants-Permission,CSLibrary-Constants-Permission,System-Byte,CSLibrary-Structures-TagAccessCallbackDelegate,CSLibrary-Constants-SelectFlags- 'CSLibrary.HighLevelInterface.SyncLock(System.UInt32,CSLibrary.Constants.Permission,CSLibrary.Constants.Permission,CSLibrary.Constants.Permission,CSLibrary.Constants.Permission,CSLibrary.Constants.Permission,System.Byte,CSLibrary.Structures.TagAccessCallbackDelegate,CSLibrary.Constants.SelectFlags)')
  - [SyncMatch(offset,count,bank,target,action,enableTruncate,mask)](#M-CSLibrary-HighLevelInterface-SyncMatch-System-UInt16,System-UInt16,CSLibrary-Constants-MemoryBank,CSLibrary-Constants-Target,CSLibrary-Constants-Action,System-Boolean,CSLibrary-Structures-S_MASK- 'CSLibrary.HighLevelInterface.SyncMatch(System.UInt16,System.UInt16,CSLibrary.Constants.MemoryBank,CSLibrary.Constants.Target,CSLibrary.Constants.Action,System.Boolean,CSLibrary.Structures.S_MASK)')
  - [SyncRead(offset,count,bank,password,tagStopCount,callback,flags)](#M-CSLibrary-HighLevelInterface-SyncRead-System-UInt16,System-UInt16,CSLibrary-Constants-MemoryBank,System-UInt32,System-Byte,CSLibrary-Structures-TagAccessCallbackDelegate,CSLibrary-Constants-SelectFlags- 'CSLibrary.HighLevelInterface.SyncRead(System.UInt16,System.UInt16,CSLibrary.Constants.MemoryBank,System.UInt32,System.Byte,CSLibrary.Structures.TagAccessCallbackDelegate,CSLibrary.Constants.SelectFlags)')
  - [SyncWrite(offset,count,bank,password,tagStopCount,data,callback,flags)](#M-CSLibrary-HighLevelInterface-SyncWrite-System-UInt16,System-UInt16,CSLibrary-Constants-MemoryBank,System-UInt32,System-Byte,System-UInt16[],CSLibrary-Structures-TagAccessCallbackDelegate,CSLibrary-Constants-SelectFlags- 'CSLibrary.HighLevelInterface.SyncWrite(System.UInt16,System.UInt16,CSLibrary.Constants.MemoryBank,System.UInt32,System.Byte,System.UInt16[],CSLibrary.Structures.TagAccessCallbackDelegate,CSLibrary.Constants.SelectFlags)')
  - [SyncWrite(offset,count,bank,password,tagStopCount,data,callback,flags)](#M-CSLibrary-HighLevelInterface-SyncWrite-System-UInt16[],System-UInt16,CSLibrary-Constants-MemoryBank,System-UInt32,System-Byte,System-UInt16[],CSLibrary-Structures-TagAccessCallbackDelegate,CSLibrary-Constants-SelectFlags- 'CSLibrary.HighLevelInterface.SyncWrite(System.UInt16[],System.UInt16,CSLibrary.Constants.MemoryBank,System.UInt32,System.Byte,System.UInt16[],CSLibrary.Structures.TagAccessCallbackDelegate,CSLibrary.Constants.SelectFlags)')
  - [TurnCarrierWaveOff()](#M-CSLibrary-HighLevelInterface-TurnCarrierWaveOff 'CSLibrary.HighLevelInterface.TurnCarrierWaveOff')
  - [TurnCarrierWaveOn()](#M-CSLibrary-HighLevelInterface-TurnCarrierWaveOn-System-Boolean- 'CSLibrary.HighLevelInterface.TurnCarrierWaveOn(System.Boolean)')
  - [UDPKeepAliveOff()](#M-CSLibrary-HighLevelInterface-UDPKeepAliveOff 'CSLibrary.HighLevelInterface.UDPKeepAliveOff')
  - [UDPKeepAliveOff()](#M-CSLibrary-HighLevelInterface-UDPKeepAliveOff-System-String- 'CSLibrary.HighLevelInterface.UDPKeepAliveOff(System.String)')
  - [UDPKeepAliveOn()](#M-CSLibrary-HighLevelInterface-UDPKeepAliveOn 'CSLibrary.HighLevelInterface.UDPKeepAliveOn')
  - [UDPKeepAliveOn()](#M-CSLibrary-HighLevelInterface-UDPKeepAliveOn-System-String- 'CSLibrary.HighLevelInterface.UDPKeepAliveOn(System.String)')
- [IBANK](#T-CSLibrary-Structures-IBANK 'CSLibrary.Structures.IBANK')
  - [GetLength()](#M-CSLibrary-Structures-IBANK-GetLength 'CSLibrary.Structures.IBANK.GetLength')
  - [ToBytes()](#M-CSLibrary-Structures-IBANK-ToBytes 'CSLibrary.Structures.IBANK.ToBytes')
  - [ToShorts()](#M-CSLibrary-Structures-IBANK-ToShorts 'CSLibrary.Structures.IBANK.ToShorts')
  - [ToString()](#M-CSLibrary-Structures-IBANK-ToString 'CSLibrary.Structures.IBANK.ToString')
  - [ToUshorts()](#M-CSLibrary-Structures-IBANK-ToUshorts 'CSLibrary.Structures.IBANK.ToUshorts')
- [INTERFACETYPE](#T-CSLibrary-HighLevelInterface-INTERFACETYPE 'CSLibrary.HighLevelInterface.INTERFACETYPE')
  - [IPV4](#F-CSLibrary-HighLevelInterface-INTERFACETYPE-IPV4 'CSLibrary.HighLevelInterface.INTERFACETYPE.IPV4')
  - [SERIAL](#F-CSLibrary-HighLevelInterface-INTERFACETYPE-SERIAL 'CSLibrary.HighLevelInterface.INTERFACETYPE.SERIAL')
  - [UNKNOWN](#F-CSLibrary-HighLevelInterface-INTERFACETYPE-UNKNOWN 'CSLibrary.HighLevelInterface.INTERFACETYPE.UNKNOWN')
  - [USB](#F-CSLibrary-HighLevelInterface-INTERFACETYPE-USB 'CSLibrary.HighLevelInterface.INTERFACETYPE.USB')
- [INVENTORY_PKT](#T-CSLibrary-Structures-INVENTORY_PKT 'CSLibrary.Structures.INVENTORY_PKT')
  - [#ctor(flags,ms,rssi,ana_ctrl,ana_port,isTruncate,pc,epc)](#M-CSLibrary-Structures-INVENTORY_PKT-#ctor-System-Byte,System-UInt32,System-Single,System-UInt16,System-UInt16,System-Boolean,System-String,System-String- 'CSLibrary.Structures.INVENTORY_PKT.#ctor(System.Byte,System.UInt32,System.Single,System.UInt16,System.UInt16,System.Boolean,System.String,System.String)')
  - [ana_ctrl](#F-CSLibrary-Structures-INVENTORY_PKT-ana_ctrl 'CSLibrary.Structures.INVENTORY_PKT.ana_ctrl')
  - [ana_port](#F-CSLibrary-Structures-INVENTORY_PKT-ana_port 'CSLibrary.Structures.INVENTORY_PKT.ana_port')
  - [epc](#F-CSLibrary-Structures-INVENTORY_PKT-epc 'CSLibrary.Structures.INVENTORY_PKT.epc')
  - [isTruncate](#F-CSLibrary-Structures-INVENTORY_PKT-isTruncate 'CSLibrary.Structures.INVENTORY_PKT.isTruncate')
  - [ms_ctr](#F-CSLibrary-Structures-INVENTORY_PKT-ms_ctr 'CSLibrary.Structures.INVENTORY_PKT.ms_ctr')
  - [pc](#F-CSLibrary-Structures-INVENTORY_PKT-pc 'CSLibrary.Structures.INVENTORY_PKT.pc')
  - [rssi](#F-CSLibrary-Structures-INVENTORY_PKT-rssi 'CSLibrary.Structures.INVENTORY_PKT.rssi')
  - [IsCRCInvalid](#P-CSLibrary-Structures-INVENTORY_PKT-IsCRCInvalid 'CSLibrary.Structures.INVENTORY_PKT.IsCRCInvalid')
- [IP](#T-CSLibrary-Net-IP 'CSLibrary.Net.IP')
  - [Address](#F-CSLibrary-Net-IP-Address 'CSLibrary.Net.IP.Address')
  - [ToString()](#M-CSLibrary-Net-IP-ToString 'CSLibrary.Net.IP.ToString')
  - [op_Implicit(ip)](#M-CSLibrary-Net-IP-op_Implicit-CSLibrary-Net-IP-~System-String 'CSLibrary.Net.IP.op_Implicit(CSLibrary.Net.IP)~System.String')
  - [op_Implicit(ip)](#M-CSLibrary-Net-IP-op_Implicit-CSLibrary-Net-IP-~System-Int64 'CSLibrary.Net.IP.op_Implicit(CSLibrary.Net.IP)~System.Int64')
- [InternalCustCmdEASParms](#T-CSLibrary-Structures-InternalCustCmdEASParms 'CSLibrary.Structures.InternalCustCmdEASParms')
  - [#ctor()](#M-CSLibrary-Structures-InternalCustCmdEASParms-#ctor 'CSLibrary.Structures.InternalCustCmdEASParms.#ctor')
  - [accessPassword](#F-CSLibrary-Structures-InternalCustCmdEASParms-accessPassword 'CSLibrary.Structures.InternalCustCmdEASParms.accessPassword')
  - [enable](#F-CSLibrary-Structures-InternalCustCmdEASParms-enable 'CSLibrary.Structures.InternalCustCmdEASParms.enable')
  - [length](#F-CSLibrary-Structures-InternalCustCmdEASParms-length 'CSLibrary.Structures.InternalCustCmdEASParms.length')
  - [retry](#F-CSLibrary-Structures-InternalCustCmdEASParms-retry 'CSLibrary.Structures.InternalCustCmdEASParms.retry')
- [InternalCustCmdTagReadProtectParms](#T-CSLibrary-Structures-InternalCustCmdTagReadProtectParms 'CSLibrary.Structures.InternalCustCmdTagReadProtectParms')
  - [#ctor()](#M-CSLibrary-Structures-InternalCustCmdTagReadProtectParms-#ctor 'CSLibrary.Structures.InternalCustCmdTagReadProtectParms.#ctor')
  - [accessPassword](#F-CSLibrary-Structures-InternalCustCmdTagReadProtectParms-accessPassword 'CSLibrary.Structures.InternalCustCmdTagReadProtectParms.accessPassword')
  - [length_](#F-CSLibrary-Structures-InternalCustCmdTagReadProtectParms-length_ 'CSLibrary.Structures.InternalCustCmdTagReadProtectParms.length_')
  - [retry](#F-CSLibrary-Structures-InternalCustCmdTagReadProtectParms-retry 'CSLibrary.Structures.InternalCustCmdTagReadProtectParms.retry')
- [InternalTagInventoryParms](#T-CSLibrary-Structures-InternalTagInventoryParms 'CSLibrary.Structures.InternalTagInventoryParms')
  - [#ctor()](#M-CSLibrary-Structures-InternalTagInventoryParms-#ctor 'CSLibrary.Structures.InternalTagInventoryParms.#ctor')
  - [flags](#F-CSLibrary-Structures-InternalTagInventoryParms-flags 'CSLibrary.Structures.InternalTagInventoryParms.flags')
  - [tagStopCount](#F-CSLibrary-Structures-InternalTagInventoryParms-tagStopCount 'CSLibrary.Structures.InternalTagInventoryParms.tagStopCount')
- [InternalTagRangingParms](#T-CSLibrary-Structures-InternalTagRangingParms 'CSLibrary.Structures.InternalTagRangingParms')
  - [#ctor()](#M-CSLibrary-Structures-InternalTagRangingParms-#ctor 'CSLibrary.Structures.InternalTagRangingParms.#ctor')
  - [flags](#F-CSLibrary-Structures-InternalTagRangingParms-flags 'CSLibrary.Structures.InternalTagRangingParms.flags')
  - [length](#F-CSLibrary-Structures-InternalTagRangingParms-length 'CSLibrary.Structures.InternalTagRangingParms.length')
  - [tagStopCount](#F-CSLibrary-Structures-InternalTagRangingParms-tagStopCount 'CSLibrary.Structures.InternalTagRangingParms.tagStopCount')
- [InternalTagReadProtectParms](#T-CSLibrary-Structures-InternalTagReadProtectParms 'CSLibrary.Structures.InternalTagReadProtectParms')
  - [#ctor()](#M-CSLibrary-Structures-InternalTagReadProtectParms-#ctor 'CSLibrary.Structures.InternalTagReadProtectParms.#ctor')
  - [accessPassword](#F-CSLibrary-Structures-InternalTagReadProtectParms-accessPassword 'CSLibrary.Structures.InternalTagReadProtectParms.accessPassword')
  - [common](#F-CSLibrary-Structures-InternalTagReadProtectParms-common 'CSLibrary.Structures.InternalTagReadProtectParms.common')
  - [length_](#F-CSLibrary-Structures-InternalTagReadProtectParms-length_ 'CSLibrary.Structures.InternalTagReadProtectParms.length_')
- [InternalTagSearchOneParms](#T-CSLibrary-Structures-InternalTagSearchOneParms 'CSLibrary.Structures.InternalTagSearchOneParms')
  - [#ctor()](#M-CSLibrary-Structures-InternalTagSearchOneParms-#ctor 'CSLibrary.Structures.InternalTagSearchOneParms.#ctor')
  - [avgRssi](#F-CSLibrary-Structures-InternalTagSearchOneParms-avgRssi 'CSLibrary.Structures.InternalTagSearchOneParms.avgRssi')
  - [length](#F-CSLibrary-Structures-InternalTagSearchOneParms-length 'CSLibrary.Structures.InternalTagSearchOneParms.length')
- [InventoryCallbackDelegate](#T-CSLibrary-Structures-InventoryCallbackDelegate 'CSLibrary.Structures.InventoryCallbackDelegate')
- [InventoryParms](#T-CSLibrary-Structures-InventoryParms 'CSLibrary.Structures.InventoryParms')
  - [#ctor(initial)](#M-CSLibrary-Structures-InventoryParms-#ctor-System-Boolean- 'CSLibrary.Structures.InventoryParms.#ctor(System.Boolean)')
  - [common](#F-CSLibrary-Structures-InventoryParms-common 'CSLibrary.Structures.InventoryParms.common')
- [IsoMDID](#T-CSLibrary-Constants-IsoMDID 'CSLibrary.Constants.IsoMDID')
  - [AMIC](#F-CSLibrary-Constants-IsoMDID-AMIC 'CSLibrary.Constants.IsoMDID.AMIC')
  - [ASK](#F-CSLibrary-Constants-IsoMDID-ASK 'CSLibrary.Constants.IsoMDID.ASK')
  - [ATMEL](#F-CSLibrary-Constants-IsoMDID-ATMEL 'CSLibrary.Constants.IsoMDID.ATMEL')
  - [Alliance](#F-CSLibrary-Constants-IsoMDID-Alliance 'CSLibrary.Constants.IsoMDID.Alliance')
  - [Belling](#F-CSLibrary-Constants-IsoMDID-Belling 'CSLibrary.Constants.IsoMDID.Belling')
  - [Broadcom](#F-CSLibrary-Constants-IsoMDID-Broadcom 'CSLibrary.Constants.IsoMDID.Broadcom')
  - [Cylink](#F-CSLibrary-Constants-IsoMDID-Cylink 'CSLibrary.Constants.IsoMDID.Cylink')
  - [Cypak](#F-CSLibrary-Constants-IsoMDID-Cypak 'CSLibrary.Constants.IsoMDID.Cypak')
  - [Dallas](#F-CSLibrary-Constants-IsoMDID-Dallas 'CSLibrary.Constants.IsoMDID.Dallas')
  - [EM](#F-CSLibrary-Constants-IsoMDID-EM 'CSLibrary.Constants.IsoMDID.EM')
  - [Emosyn](#F-CSLibrary-Constants-IsoMDID-Emosyn 'CSLibrary.Constants.IsoMDID.Emosyn')
  - [EmosynEM](#F-CSLibrary-Constants-IsoMDID-EmosynEM 'CSLibrary.Constants.IsoMDID.EmosynEM')
  - [Fudan](#F-CSLibrary-Constants-IsoMDID-Fudan 'CSLibrary.Constants.IsoMDID.Fudan')
  - [Fujitsu](#F-CSLibrary-Constants-IsoMDID-Fujitsu 'CSLibrary.Constants.IsoMDID.Fujitsu')
  - [Hitachi](#F-CSLibrary-Constants-IsoMDID-Hitachi 'CSLibrary.Constants.IsoMDID.Hitachi')
  - [HitachiULSI](#F-CSLibrary-Constants-IsoMDID-HitachiULSI 'CSLibrary.Constants.IsoMDID.HitachiULSI')
  - [Hynix](#F-CSLibrary-Constants-IsoMDID-Hynix 'CSLibrary.Constants.IsoMDID.Hynix')
  - [INSIDE](#F-CSLibrary-Constants-IsoMDID-INSIDE 'CSLibrary.Constants.IsoMDID.INSIDE')
  - [Impinj](#F-CSLibrary-Constants-IsoMDID-Impinj 'CSLibrary.Constants.IsoMDID.Impinj')
  - [Infineon](#F-CSLibrary-Constants-IsoMDID-Infineon 'CSLibrary.Constants.IsoMDID.Infineon')
  - [Innovision](#F-CSLibrary-Constants-IsoMDID-Innovision 'CSLibrary.Constants.IsoMDID.Innovision')
  - [KSW](#F-CSLibrary-Constants-IsoMDID-KSW 'CSLibrary.Constants.IsoMDID.KSW')
  - [LG](#F-CSLibrary-Constants-IsoMDID-LG 'CSLibrary.Constants.IsoMDID.LG')
  - [MStar](#F-CSLibrary-Constants-IsoMDID-MStar 'CSLibrary.Constants.IsoMDID.MStar')
  - [Magellan](#F-CSLibrary-Constants-IsoMDID-Magellan 'CSLibrary.Constants.IsoMDID.Magellan')
  - [Malaysia](#F-CSLibrary-Constants-IsoMDID-Malaysia 'CSLibrary.Constants.IsoMDID.Malaysia')
  - [Masktech](#F-CSLibrary-Constants-IsoMDID-Masktech 'CSLibrary.Constants.IsoMDID.Masktech')
  - [Matsushita](#F-CSLibrary-Constants-IsoMDID-Matsushita 'CSLibrary.Constants.IsoMDID.Matsushita')
  - [Melexis](#F-CSLibrary-Constants-IsoMDID-Melexis 'CSLibrary.Constants.IsoMDID.Melexis')
  - [Mitsubishi](#F-CSLibrary-Constants-IsoMDID-Mitsubishi 'CSLibrary.Constants.IsoMDID.Mitsubishi')
  - [Motorola](#F-CSLibrary-Constants-IsoMDID-Motorola 'CSLibrary.Constants.IsoMDID.Motorola')
  - [NEC](#F-CSLibrary-Constants-IsoMDID-NEC 'CSLibrary.Constants.IsoMDID.NEC')
  - [ORGA](#F-CSLibrary-Constants-IsoMDID-ORGA 'CSLibrary.Constants.IsoMDID.ORGA')
  - [Oki](#F-CSLibrary-Constants-IsoMDID-Oki 'CSLibrary.Constants.IsoMDID.Oki')
  - [Philips](#F-CSLibrary-Constants-IsoMDID-Philips 'CSLibrary.Constants.IsoMDID.Philips')
  - [RFIDsec](#F-CSLibrary-Constants-IsoMDID-RFIDsec 'CSLibrary.Constants.IsoMDID.RFIDsec')
  - [Renesas](#F-CSLibrary-Constants-IsoMDID-Renesas 'CSLibrary.Constants.IsoMDID.Renesas')
  - [Ricoh](#F-CSLibrary-Constants-IsoMDID-Ricoh 'CSLibrary.Constants.IsoMDID.Ricoh')
  - [SHARP](#F-CSLibrary-Constants-IsoMDID-SHARP 'CSLibrary.Constants.IsoMDID.SHARP')
  - [STM](#F-CSLibrary-Constants-IsoMDID-STM 'CSLibrary.Constants.IsoMDID.STM')
  - [Samsung](#F-CSLibrary-Constants-IsoMDID-Samsung 'CSLibrary.Constants.IsoMDID.Samsung')
  - [Schweizer](#F-CSLibrary-Constants-IsoMDID-Schweizer 'CSLibrary.Constants.IsoMDID.Schweizer')
  - [Sony](#F-CSLibrary-Constants-IsoMDID-Sony 'CSLibrary.Constants.IsoMDID.Sony')
  - [TAGSYS](#F-CSLibrary-Constants-IsoMDID-TAGSYS 'CSLibrary.Constants.IsoMDID.TAGSYS')
  - [Texas](#F-CSLibrary-Constants-IsoMDID-Texas 'CSLibrary.Constants.IsoMDID.Texas')
  - [Toshiba](#F-CSLibrary-Constants-IsoMDID-Toshiba 'CSLibrary.Constants.IsoMDID.Toshiba')
  - [Transcore](#F-CSLibrary-Constants-IsoMDID-Transcore 'CSLibrary.Constants.IsoMDID.Transcore')
  - [UNKNOWN](#F-CSLibrary-Constants-IsoMDID-UNKNOWN 'CSLibrary.Constants.IsoMDID.UNKNOWN')
  - [Unicore](#F-CSLibrary-Constants-IsoMDID-Unicore 'CSLibrary.Constants.IsoMDID.Unicore')
  - [XICOR](#F-CSLibrary-Constants-IsoMDID-XICOR 'CSLibrary.Constants.IsoMDID.XICOR')
  - [ZMD](#F-CSLibrary-Constants-IsoMDID-ZMD 'CSLibrary.Constants.IsoMDID.ZMD')
  - [eeDar](#F-CSLibrary-Constants-IsoMDID-eeDar 'CSLibrary.Constants.IsoMDID.eeDar')
- [KillCmdParms](#T-CSLibrary-Structures-KillCmdParms 'CSLibrary.Structures.KillCmdParms')
  - [#ctor(initial)](#M-CSLibrary-Structures-KillCmdParms-#ctor-System-Boolean- 'CSLibrary.Structures.KillCmdParms.#ctor(System.Boolean)')
  - [killPassword](#F-CSLibrary-Structures-KillCmdParms-killPassword 'CSLibrary.Structures.KillCmdParms.killPassword')
- [KillParms](#T-CSLibrary-Structures-KillParms 'CSLibrary.Structures.KillParms')
  - [#ctor(initial)](#M-CSLibrary-Structures-KillParms-#ctor-System-Boolean- 'CSLibrary.Structures.KillParms.#ctor(System.Boolean)')
  - [accessPassword](#F-CSLibrary-Structures-KillParms-accessPassword 'CSLibrary.Structures.KillParms.accessPassword')
  - [common](#F-CSLibrary-Structures-KillParms-common 'CSLibrary.Structures.KillParms.common')
  - [killCmdParms](#F-CSLibrary-Structures-KillParms-killCmdParms 'CSLibrary.Structures.KillParms.killCmdParms')
  - [length](#F-CSLibrary-Structures-KillParms-length 'CSLibrary.Structures.KillParms.length')
- [LBT](#T-CSLibrary-Constants-LBT 'CSLibrary.Constants.LBT')
  - [OFF](#F-CSLibrary-Constants-LBT-OFF 'CSLibrary.Constants.LBT.OFF')
  - [ON](#F-CSLibrary-Constants-LBT-ON 'CSLibrary.Constants.LBT.ON')
  - [SCAN](#F-CSLibrary-Constants-LBT-SCAN 'CSLibrary.Constants.LBT.SCAN')
- [LibraryVersion](#T-CSLibrary-Structures-LibraryVersion 'CSLibrary.Structures.LibraryVersion')
  - [#ctor()](#M-CSLibrary-Structures-LibraryVersion-#ctor 'CSLibrary.Structures.LibraryVersion.#ctor')
- [LinkProfileInfo](#T-CSLibrary-LinkProfileInfo 'CSLibrary.LinkProfileInfo')
  - [#ctor(linkProfile)](#M-CSLibrary-LinkProfileInfo-#ctor-CSLibrary-Structures-RadioLinkProfile- 'CSLibrary.LinkProfileInfo.#ctor(CSLibrary.Structures.RadioLinkProfile)')
  - [DenseReaderMode](#P-CSLibrary-LinkProfileInfo-DenseReaderMode 'CSLibrary.LinkProfileInfo.DenseReaderMode')
  - [Description](#P-CSLibrary-LinkProfileInfo-Description 'CSLibrary.LinkProfileInfo.Description')
  - [Enabled](#P-CSLibrary-LinkProfileInfo-Enabled 'CSLibrary.LinkProfileInfo.Enabled')
  - [LinkProfileConfig](#P-CSLibrary-LinkProfileInfo-LinkProfileConfig 'CSLibrary.LinkProfileInfo.LinkProfileConfig')
  - [Name](#P-CSLibrary-LinkProfileInfo-Name 'CSLibrary.LinkProfileInfo.Name')
  - [NarrowbandRssiSamples](#P-CSLibrary-LinkProfileInfo-NarrowbandRssiSamples 'CSLibrary.LinkProfileInfo.NarrowbandRssiSamples')
  - [ProfileId](#P-CSLibrary-LinkProfileInfo-ProfileId 'CSLibrary.LinkProfileInfo.ProfileId')
  - [ProfileProtocol](#P-CSLibrary-LinkProfileInfo-ProfileProtocol 'CSLibrary.LinkProfileInfo.ProfileProtocol')
  - [ProfileUniqueId](#P-CSLibrary-LinkProfileInfo-ProfileUniqueId 'CSLibrary.LinkProfileInfo.ProfileUniqueId')
  - [ProfileVersion](#P-CSLibrary-LinkProfileInfo-ProfileVersion 'CSLibrary.LinkProfileInfo.ProfileVersion')
  - [RealtimeNarrowbandRssiSamples](#P-CSLibrary-LinkProfileInfo-RealtimeNarrowbandRssiSamples 'CSLibrary.LinkProfileInfo.RealtimeNarrowbandRssiSamples')
  - [RealtimeRssiEnabled](#P-CSLibrary-LinkProfileInfo-RealtimeRssiEnabled 'CSLibrary.LinkProfileInfo.RealtimeRssiEnabled')
  - [RealtimeWidebandRssiSamples](#P-CSLibrary-LinkProfileInfo-RealtimeWidebandRssiSamples 'CSLibrary.LinkProfileInfo.RealtimeWidebandRssiSamples')
  - [WidebandRssiSamples](#P-CSLibrary-LinkProfileInfo-WidebandRssiSamples 'CSLibrary.LinkProfileInfo.WidebandRssiSamples')
  - [ToString()](#M-CSLibrary-LinkProfileInfo-ToString 'CSLibrary.LinkProfileInfo.ToString')
- [LockCmdParms](#T-CSLibrary-Structures-LockCmdParms 'CSLibrary.Structures.LockCmdParms')
  - [length](#F-CSLibrary-Structures-LockCmdParms-length 'CSLibrary.Structures.LockCmdParms.length')
  - [permissions](#F-CSLibrary-Structures-LockCmdParms-permissions 'CSLibrary.Structures.LockCmdParms.permissions')
- [LockParms](#T-CSLibrary-Structures-LockParms 'CSLibrary.Structures.LockParms')
  - [accessPassword](#F-CSLibrary-Structures-LockParms-accessPassword 'CSLibrary.Structures.LockParms.accessPassword')
  - [common](#F-CSLibrary-Structures-LockParms-common 'CSLibrary.Structures.LockParms.common')
  - [length](#F-CSLibrary-Structures-LockParms-length 'CSLibrary.Structures.LockParms.length')
  - [lockCmdParms](#F-CSLibrary-Structures-LockParms-lockCmdParms 'CSLibrary.Structures.LockParms.lockCmdParms')
- [LoggingForm](#T-CSLibrary-Structures-LoggingForm 'CSLibrary.Structures.LoggingForm')
- [MAC](#T-CSLibrary-Net-MAC 'CSLibrary.Net.MAC')
  - [Address](#F-CSLibrary-Net-MAC-Address 'CSLibrary.Net.MAC.Address')
  - [Equals(obj)](#M-CSLibrary-Net-MAC-Equals-System-Object- 'CSLibrary.Net.MAC.Equals(System.Object)')
  - [Parse(address)](#M-CSLibrary-Net-MAC-Parse-System-String- 'CSLibrary.Net.MAC.Parse(System.String)')
  - [ToString()](#M-CSLibrary-Net-MAC-ToString 'CSLibrary.Net.MAC.ToString')
  - [op_Implicit(mac)](#M-CSLibrary-Net-MAC-op_Implicit-CSLibrary-Net-MAC-~System-String 'CSLibrary.Net.MAC.op_Implicit(CSLibrary.Net.MAC)~System.String')
- [MacRegister](#T-CSLibrary-HighLevelInterface-MacRegister 'CSLibrary.HighLevelInterface.MacRegister')
- [MacResetType](#T-CSLibrary-Constants-MacResetType 'CSLibrary.Constants.MacResetType')
  - [SOFT](#F-CSLibrary-Constants-MacResetType-SOFT 'CSLibrary.Constants.MacResetType.SOFT')
  - [UNKNOWN](#F-CSLibrary-Constants-MacResetType-UNKNOWN 'CSLibrary.Constants.MacResetType.UNKNOWN')
- [MacVersion](#T-CSLibrary-Structures-MacVersion 'CSLibrary.Structures.MacVersion')
  - [#ctor()](#M-CSLibrary-Structures-MacVersion-#ctor 'CSLibrary.Structures.MacVersion.#ctor')
  - [#ctor(major,minor,patch)](#M-CSLibrary-Structures-MacVersion-#ctor-System-UInt32,System-UInt32,System-UInt32- 'CSLibrary.Structures.MacVersion.#ctor(System.UInt32,System.UInt32,System.UInt32)')
- [Machine](#T-CSLibrary-Constants-Machine 'CSLibrary.Constants.Machine')
- [MemoryBank](#T-CSLibrary-Constants-MemoryBank 'CSLibrary.Constants.MemoryBank')
  - [BANK0](#F-CSLibrary-Constants-MemoryBank-BANK0 'CSLibrary.Constants.MemoryBank.BANK0')
  - [BANK1](#F-CSLibrary-Constants-MemoryBank-BANK1 'CSLibrary.Constants.MemoryBank.BANK1')
  - [BANK2](#F-CSLibrary-Constants-MemoryBank-BANK2 'CSLibrary.Constants.MemoryBank.BANK2')
  - [BANK3](#F-CSLibrary-Constants-MemoryBank-BANK3 'CSLibrary.Constants.MemoryBank.BANK3')
  - [EPC](#F-CSLibrary-Constants-MemoryBank-EPC 'CSLibrary.Constants.MemoryBank.EPC')
  - [RESERVED](#F-CSLibrary-Constants-MemoryBank-RESERVED 'CSLibrary.Constants.MemoryBank.RESERVED')
  - [TID](#F-CSLibrary-Constants-MemoryBank-TID 'CSLibrary.Constants.MemoryBank.TID')
  - [UNKNOWN](#F-CSLibrary-Constants-MemoryBank-UNKNOWN 'CSLibrary.Constants.MemoryBank.UNKNOWN')
  - [USER](#F-CSLibrary-Constants-MemoryBank-USER 'CSLibrary.Constants.MemoryBank.USER')
- [MillerNumber](#T-CSLibrary-Constants-MillerNumber 'CSLibrary.Constants.MillerNumber')
  - [NUMBER_2](#F-CSLibrary-Constants-MillerNumber-NUMBER_2 'CSLibrary.Constants.MillerNumber.NUMBER_2')
  - [NUMBER_4](#F-CSLibrary-Constants-MillerNumber-NUMBER_4 'CSLibrary.Constants.MillerNumber.NUMBER_4')
  - [NUMBER_8](#F-CSLibrary-Constants-MillerNumber-NUMBER_8 'CSLibrary.Constants.MillerNumber.NUMBER_8')
  - [NUMBER_FM0](#F-CSLibrary-Constants-MillerNumber-NUMBER_FM0 'CSLibrary.Constants.MillerNumber.NUMBER_FM0')
  - [UNKNOWN](#F-CSLibrary-Constants-MillerNumber-UNKNOWN 'CSLibrary.Constants.MillerNumber.UNKNOWN')
- [Mode](#T-CSLibrary-Net-Mode 'CSLibrary.Net.Mode')
  - [Bootloader](#F-CSLibrary-Net-Mode-Bootloader 'CSLibrary.Net.Mode.Bootloader')
  - [Normal](#F-CSLibrary-Net-Mode-Normal 'CSLibrary.Net.Mode.Normal')
  - [NormalSerial](#F-CSLibrary-Net-Mode-NormalSerial 'CSLibrary.Net.Mode.NormalSerial')
  - [NormalUsb](#F-CSLibrary-Net-Mode-NormalUsb 'CSLibrary.Net.Mode.NormalUsb')
  - [Unknown](#F-CSLibrary-Net-Mode-Unknown 'CSLibrary.Net.Mode.Unknown')
- [Modes](#T-CSLibrary-Net-Modes 'CSLibrary.Net.Modes')
- [ModulationType](#T-CSLibrary-Constants-ModulationType 'CSLibrary.Constants.ModulationType')
  - [DSB_ASK](#F-CSLibrary-Constants-ModulationType-DSB_ASK 'CSLibrary.Constants.ModulationType.DSB_ASK')
  - [PR_ASK](#F-CSLibrary-Constants-ModulationType-PR_ASK 'CSLibrary.Constants.ModulationType.PR_ASK')
  - [SSB_ASK](#F-CSLibrary-Constants-ModulationType-SSB_ASK 'CSLibrary.Constants.ModulationType.SSB_ASK')
  - [UNKNOWN](#F-CSLibrary-Constants-ModulationType-UNKNOWN 'CSLibrary.Constants.ModulationType.UNKNOWN')
- [NetFinder](#T-CSLibrary-Net-NetFinder 'CSLibrary.Net.NetFinder')
  - [#ctor()](#M-CSLibrary-Net-NetFinder-#ctor 'CSLibrary.Net.NetFinder.#ctor')
  - [LastError](#P-CSLibrary-Net-NetFinder-LastError 'CSLibrary.Net.NetFinder.LastError')
  - [Operation](#P-CSLibrary-Net-NetFinder-Operation 'CSLibrary.Net.NetFinder.Operation')
  - [Radios](#P-CSLibrary-Net-NetFinder-Radios 'CSLibrary.Net.NetFinder.Radios')
  - [AssignDevice(targetMacAddress,ipAddressTo,trustedServerAddress,trustedServerEnabled)](#M-CSLibrary-Net-NetFinder-AssignDevice-System-Byte[],System-Byte[],System-Byte[],System-Boolean- 'CSLibrary.Net.NetFinder.AssignDevice(System.Byte[],System.Byte[],System.Byte[],System.Boolean)')
  - [AssignDevice(targetMacAddress,ipAddressTo,DHCPRetry,DHCPEnabled)](#M-CSLibrary-Net-NetFinder-AssignDevice-System-Byte[],System-Byte[],System-Byte,System-Boolean- 'CSLibrary.Net.NetFinder.AssignDevice(System.Byte[],System.Byte[],System.Byte,System.Boolean)')
  - [AssignDevice(targetMacAddress,ipAddressTo,deviceName,DHCPRetry,DHCPEnabled)](#M-CSLibrary-Net-NetFinder-AssignDevice-System-Byte[],System-Byte[],System-String,System-Byte,System-Boolean- 'CSLibrary.Net.NetFinder.AssignDevice(System.Byte[],System.Byte[],System.String,System.Byte,System.Boolean)')
  - [AssignDevice(targetMacAddress,ipAddressTo,deviceName,DHCPRetry,DHCPEnabled,trustedServerAddress,trustedServerEnabled,subnet,gateway)](#M-CSLibrary-Net-NetFinder-AssignDevice-System-Byte[],System-Byte[],System-String,System-Byte,System-Boolean,System-Byte[],System-Boolean,System-Byte[],System-Byte[],System-Int32- 'CSLibrary.Net.NetFinder.AssignDevice(System.Byte[],System.Byte[],System.String,System.Byte,System.Boolean,System.Byte[],System.Boolean,System.Byte[],System.Byte[],System.Int32)')
  - [AsyncUpdateEboot(IP,ebootfile)](#M-CSLibrary-Net-NetFinder-AsyncUpdateEboot-System-String,System-String- 'CSLibrary.Net.NetFinder.AsyncUpdateEboot(System.String,System.String)')
  - [AsyncUpdateImage(IP,imagefile)](#M-CSLibrary-Net-NetFinder-AsyncUpdateImage-System-String,System-String- 'CSLibrary.Net.NetFinder.AsyncUpdateImage(System.String,System.String)')
  - [ClearDeviceList()](#M-CSLibrary-Net-NetFinder-ClearDeviceList 'CSLibrary.Net.NetFinder.ClearDeviceList')
  - [CreateAckPacket(blockNr)](#M-CSLibrary-Net-NetFinder-CreateAckPacket-System-Int32- 'CSLibrary.Net.NetFinder.CreateAckPacket(System.Int32)')
  - [CreateDataPacket(blockNr,data)](#M-CSLibrary-Net-NetFinder-CreateDataPacket-System-Int32,System-Byte[]- 'CSLibrary.Net.NetFinder.CreateDataPacket(System.Int32,System.Byte[])')
  - [CreateRequestPacket(opCode,remoteFile,tftpMode)](#M-CSLibrary-Net-NetFinder-CreateRequestPacket-CSLibrary-Net-Opcodes,System-String,CSLibrary-Net-Modes- 'CSLibrary.Net.NetFinder.CreateRequestPacket(CSLibrary.Net.Opcodes,System.String,CSLibrary.Net.Modes)')
  - [Dispose()](#M-CSLibrary-Net-NetFinder-Dispose 'CSLibrary.Net.NetFinder.Dispose')
  - [GetApiMode()](#M-CSLibrary-Net-NetFinder-GetApiMode-System-String- 'CSLibrary.Net.NetFinder.GetApiMode(System.String)')
  - [GetPoeInfo()](#M-CSLibrary-Net-NetFinder-GetPoeInfo-System-String,System-Byte@,System-UInt16@,System-UInt16@- 'CSLibrary.Net.NetFinder.GetPoeInfo(System.String,System.Byte@,System.UInt16@,System.UInt16@)')
  - [GetTagIndicationMode()](#M-CSLibrary-Net-NetFinder-GetTagIndicationMode-System-String- 'CSLibrary.Net.NetFinder.GetTagIndicationMode(System.String)')
  - [ResearchDevice()](#M-CSLibrary-Net-NetFinder-ResearchDevice 'CSLibrary.Net.NetFinder.ResearchDevice')
  - [SearchDevice()](#M-CSLibrary-Net-NetFinder-SearchDevice 'CSLibrary.Net.NetFinder.SearchDevice')
  - [SearchDevice()](#M-CSLibrary-Net-NetFinder-SearchDevice-System-Net-IPAddress- 'CSLibrary.Net.NetFinder.SearchDevice(System.Net.IPAddress)')
  - [SearchSerialDeivce()](#M-CSLibrary-Net-NetFinder-SearchSerialDeivce 'CSLibrary.Net.NetFinder.SearchSerialDeivce')
  - [SearchUsbDevice()](#M-CSLibrary-Net-NetFinder-SearchUsbDevice 'CSLibrary.Net.NetFinder.SearchUsbDevice')
  - [SetApiMode()](#M-CSLibrary-Net-NetFinder-SetApiMode-System-String,CSLibrary-Net-ApiMode- 'CSLibrary.Net.NetFinder.SetApiMode(System.String,CSLibrary.Net.ApiMode)')
  - [SetPoePower()](#M-CSLibrary-Net-NetFinder-SetPoePower-System-String,System-UInt16- 'CSLibrary.Net.NetFinder.SetPoePower(System.String,System.UInt16)')
  - [SetTagIndicationMode()](#M-CSLibrary-Net-NetFinder-SetTagIndicationMode-System-String,System-Byte- 'CSLibrary.Net.NetFinder.SetTagIndicationMode(System.String,System.Byte)')
  - [Stop()](#M-CSLibrary-Net-NetFinder-Stop 'CSLibrary.Net.NetFinder.Stop')
- [NonVolatileMemoryBlock](#T-CSLibrary-Structures-NonVolatileMemoryBlock 'CSLibrary.Structures.NonVolatileMemoryBlock')
  - [#ctor()](#M-CSLibrary-Structures-NonVolatileMemoryBlock-#ctor 'CSLibrary.Structures.NonVolatileMemoryBlock.#ctor')
  - [address](#F-CSLibrary-Structures-NonVolatileMemoryBlock-address 'CSLibrary.Structures.NonVolatileMemoryBlock.address')
  - [flags](#F-CSLibrary-Structures-NonVolatileMemoryBlock-flags 'CSLibrary.Structures.NonVolatileMemoryBlock.flags')
  - [length](#F-CSLibrary-Structures-NonVolatileMemoryBlock-length 'CSLibrary.Structures.NonVolatileMemoryBlock.length')
  - [pData](#F-CSLibrary-Structures-NonVolatileMemoryBlock-pData 'CSLibrary.Structures.NonVolatileMemoryBlock.pData')
- [OnAccessCompletedEventArgs](#T-CSLibrary-Events-OnAccessCompletedEventArgs 'CSLibrary.Events.OnAccessCompletedEventArgs')
  - [#ctor(success,bank,access,data)](#M-CSLibrary-Events-OnAccessCompletedEventArgs-#ctor-System-Boolean,CSLibrary-Constants-Bank,CSLibrary-Constants-TagAccess,CSLibrary-Structures-IBANK- 'CSLibrary.Events.OnAccessCompletedEventArgs.#ctor(System.Boolean,CSLibrary.Constants.Bank,CSLibrary.Constants.TagAccess,CSLibrary.Structures.IBANK)')
  - [access](#F-CSLibrary-Events-OnAccessCompletedEventArgs-access 'CSLibrary.Events.OnAccessCompletedEventArgs.access')
  - [bank](#F-CSLibrary-Events-OnAccessCompletedEventArgs-bank 'CSLibrary.Events.OnAccessCompletedEventArgs.bank')
  - [data](#F-CSLibrary-Events-OnAccessCompletedEventArgs-data 'CSLibrary.Events.OnAccessCompletedEventArgs.data')
  - [success](#F-CSLibrary-Events-OnAccessCompletedEventArgs-success 'CSLibrary.Events.OnAccessCompletedEventArgs.success')
- [OnAsyncCallbackEventArgs](#T-CSLibrary-Events-OnAsyncCallbackEventArgs 'CSLibrary.Events.OnAsyncCallbackEventArgs')
  - [#ctor(info,type)](#M-CSLibrary-Events-OnAsyncCallbackEventArgs-#ctor-CSLibrary-Structures-TagCallbackInfo,CSLibrary-Constants-CallbackType- 'CSLibrary.Events.OnAsyncCallbackEventArgs.#ctor(CSLibrary.Structures.TagCallbackInfo,CSLibrary.Constants.CallbackType)')
  - [Cancel](#F-CSLibrary-Events-OnAsyncCallbackEventArgs-Cancel 'CSLibrary.Events.OnAsyncCallbackEventArgs.Cancel')
  - [info](#F-CSLibrary-Events-OnAsyncCallbackEventArgs-info 'CSLibrary.Events.OnAsyncCallbackEventArgs.info')
  - [type](#F-CSLibrary-Events-OnAsyncCallbackEventArgs-type 'CSLibrary.Events.OnAsyncCallbackEventArgs.type')
- [OnFirmwareUpgradeEventArgs](#T-CSLibrary-Events-OnFirmwareUpgradeEventArgs 'CSLibrary.Events.OnFirmwareUpgradeEventArgs')
  - [#ctor(state)](#M-CSLibrary-Events-OnFirmwareUpgradeEventArgs-#ctor-System-UInt64- 'CSLibrary.Events.OnFirmwareUpgradeEventArgs.#ctor(System.UInt64)')
  - [CurrentUpdateOffset](#F-CSLibrary-Events-OnFirmwareUpgradeEventArgs-CurrentUpdateOffset 'CSLibrary.Events.OnFirmwareUpgradeEventArgs.CurrentUpdateOffset')
- [OnStateChangedEventArgs](#T-CSLibrary-Events-OnStateChangedEventArgs 'CSLibrary.Events.OnStateChangedEventArgs')
  - [#ctor(state)](#M-CSLibrary-Events-OnStateChangedEventArgs-#ctor-CSLibrary-Constants-RFState- 'CSLibrary.Events.OnStateChangedEventArgs.#ctor(CSLibrary.Constants.RFState)')
  - [state](#F-CSLibrary-Events-OnStateChangedEventArgs-state 'CSLibrary.Events.OnStateChangedEventArgs.state')
- [Opcodes](#T-CSLibrary-Net-Opcodes 'CSLibrary.Net.Opcodes')
- [Operation](#T-CSLibrary-Constants-Operation 'CSLibrary.Constants.Operation')
  - [CL_ACCESS_FIFO](#F-CSLibrary-Constants-Operation-CL_ACCESS_FIFO 'CSLibrary.Constants.Operation.CL_ACCESS_FIFO')
  - [CL_END_LOG](#F-CSLibrary-Constants-Operation-CL_END_LOG 'CSLibrary.Constants.Operation.CL_END_LOG')
  - [CL_GET_BAT_LV](#F-CSLibrary-Constants-Operation-CL_GET_BAT_LV 'CSLibrary.Constants.Operation.CL_GET_BAT_LV')
  - [CL_GET_CAL_DATA](#F-CSLibrary-Constants-Operation-CL_GET_CAL_DATA 'CSLibrary.Constants.Operation.CL_GET_CAL_DATA')
  - [CL_GET_LOG_STATE](#F-CSLibrary-Constants-Operation-CL_GET_LOG_STATE 'CSLibrary.Constants.Operation.CL_GET_LOG_STATE')
  - [CL_GET_MEASUREMENT_SETUP](#F-CSLibrary-Constants-Operation-CL_GET_MEASUREMENT_SETUP 'CSLibrary.Constants.Operation.CL_GET_MEASUREMENT_SETUP')
  - [CL_GET_SENSOR_VALUE](#F-CSLibrary-Constants-Operation-CL_GET_SENSOR_VALUE 'CSLibrary.Constants.Operation.CL_GET_SENSOR_VALUE')
  - [CL_INIT](#F-CSLibrary-Constants-Operation-CL_INIT 'CSLibrary.Constants.Operation.CL_INIT')
  - [CL_OPEN_AREA](#F-CSLibrary-Constants-Operation-CL_OPEN_AREA 'CSLibrary.Constants.Operation.CL_OPEN_AREA')
  - [CL_SET_CAL_DATA](#F-CSLibrary-Constants-Operation-CL_SET_CAL_DATA 'CSLibrary.Constants.Operation.CL_SET_CAL_DATA')
  - [CL_SET_LOG_LIMITS](#F-CSLibrary-Constants-Operation-CL_SET_LOG_LIMITS 'CSLibrary.Constants.Operation.CL_SET_LOG_LIMITS')
  - [CL_SET_LOG_MODE](#F-CSLibrary-Constants-Operation-CL_SET_LOG_MODE 'CSLibrary.Constants.Operation.CL_SET_LOG_MODE')
  - [CL_SET_PASSWORD](#F-CSLibrary-Constants-Operation-CL_SET_PASSWORD 'CSLibrary.Constants.Operation.CL_SET_PASSWORD')
  - [CL_SET_SFE_PARA](#F-CSLibrary-Constants-Operation-CL_SET_SFE_PARA 'CSLibrary.Constants.Operation.CL_SET_SFE_PARA')
  - [CL_SET_SHELF_LIFE](#F-CSLibrary-Constants-Operation-CL_SET_SHELF_LIFE 'CSLibrary.Constants.Operation.CL_SET_SHELF_LIFE')
  - [CL_START_LOG](#F-CSLibrary-Constants-Operation-CL_START_LOG 'CSLibrary.Constants.Operation.CL_START_LOG')
  - [EAS_ALARM](#F-CSLibrary-Constants-Operation-EAS_ALARM 'CSLibrary.Constants.Operation.EAS_ALARM')
  - [EAS_CONFIG](#F-CSLibrary-Constants-Operation-EAS_CONFIG 'CSLibrary.Constants.Operation.EAS_CONFIG')
  - [EM4324_GetUid](#F-CSLibrary-Constants-Operation-EM4324_GetUid 'CSLibrary.Constants.Operation.EM4324_GetUid')
  - [EM4325_GetUid](#F-CSLibrary-Constants-Operation-EM4325_GetUid 'CSLibrary.Constants.Operation.EM4325_GetUid')
  - [EM_GetSensorData](#F-CSLibrary-Constants-Operation-EM_GetSensorData 'CSLibrary.Constants.Operation.EM_GetSensorData')
  - [EM_ResetAlarms](#F-CSLibrary-Constants-Operation-EM_ResetAlarms 'CSLibrary.Constants.Operation.EM_ResetAlarms')
  - [EM_SPI](#F-CSLibrary-Constants-Operation-EM_SPI 'CSLibrary.Constants.Operation.EM_SPI')
  - [EM_SPIAlarm](#F-CSLibrary-Constants-Operation-EM_SPIAlarm 'CSLibrary.Constants.Operation.EM_SPIAlarm')
  - [EM_SPIBoot](#F-CSLibrary-Constants-Operation-EM_SPIBoot 'CSLibrary.Constants.Operation.EM_SPIBoot')
  - [EM_SPIGetSensorData](#F-CSLibrary-Constants-Operation-EM_SPIGetSensorData 'CSLibrary.Constants.Operation.EM_SPIGetSensorData')
  - [EM_SPIReadPage](#F-CSLibrary-Constants-Operation-EM_SPIReadPage 'CSLibrary.Constants.Operation.EM_SPIReadPage')
  - [EM_SPIReadRegisterFileWord](#F-CSLibrary-Constants-Operation-EM_SPIReadRegisterFileWord 'CSLibrary.Constants.Operation.EM_SPIReadRegisterFileWord')
  - [EM_SPIReadWord](#F-CSLibrary-Constants-Operation-EM_SPIReadWord 'CSLibrary.Constants.Operation.EM_SPIReadWord')
  - [EM_SPIReqRN](#F-CSLibrary-Constants-Operation-EM_SPIReqRN 'CSLibrary.Constants.Operation.EM_SPIReqRN')
  - [EM_SPIRequestStatus](#F-CSLibrary-Constants-Operation-EM_SPIRequestStatus 'CSLibrary.Constants.Operation.EM_SPIRequestStatus')
  - [EM_SPISetClock](#F-CSLibrary-Constants-Operation-EM_SPISetClock 'CSLibrary.Constants.Operation.EM_SPISetClock')
  - [EM_SPISetFlags](#F-CSLibrary-Constants-Operation-EM_SPISetFlags 'CSLibrary.Constants.Operation.EM_SPISetFlags')
  - [EM_SPITransponder](#F-CSLibrary-Constants-Operation-EM_SPITransponder 'CSLibrary.Constants.Operation.EM_SPITransponder')
  - [EM_SPIWritePage](#F-CSLibrary-Constants-Operation-EM_SPIWritePage 'CSLibrary.Constants.Operation.EM_SPIWritePage')
  - [EM_SPIWriteRegisterFileWord](#F-CSLibrary-Constants-Operation-EM_SPIWriteRegisterFileWord 'CSLibrary.Constants.Operation.EM_SPIWriteRegisterFileWord')
  - [EM_SPIWriteWord](#F-CSLibrary-Constants-Operation-EM_SPIWriteWord 'CSLibrary.Constants.Operation.EM_SPIWriteWord')
  - [G2_CHANGE_CONFIG](#F-CSLibrary-Constants-Operation-G2_CHANGE_CONFIG 'CSLibrary.Constants.Operation.G2_CHANGE_CONFIG')
  - [G2_CHANGE_EAS](#F-CSLibrary-Constants-Operation-G2_CHANGE_EAS 'CSLibrary.Constants.Operation.G2_CHANGE_EAS')
  - [G2_EAS_ALARM](#F-CSLibrary-Constants-Operation-G2_EAS_ALARM 'CSLibrary.Constants.Operation.G2_EAS_ALARM')
  - [G2_READ_PROTECT](#F-CSLibrary-Constants-Operation-G2_READ_PROTECT 'CSLibrary.Constants.Operation.G2_READ_PROTECT')
  - [G2_RESET_READ_PROTECT](#F-CSLibrary-Constants-Operation-G2_RESET_READ_PROTECT 'CSLibrary.Constants.Operation.G2_RESET_READ_PROTECT')
  - [QT_COMMAND](#F-CSLibrary-Constants-Operation-QT_COMMAND 'CSLibrary.Constants.Operation.QT_COMMAND')
  - [TAG_BLOCK_PERMALOCK](#F-CSLibrary-Constants-Operation-TAG_BLOCK_PERMALOCK 'CSLibrary.Constants.Operation.TAG_BLOCK_PERMALOCK')
  - [TAG_BLOCK_WRITE](#F-CSLibrary-Constants-Operation-TAG_BLOCK_WRITE 'CSLibrary.Constants.Operation.TAG_BLOCK_WRITE')
  - [TAG_INVENTORY](#F-CSLibrary-Constants-Operation-TAG_INVENTORY 'CSLibrary.Constants.Operation.TAG_INVENTORY')
  - [TAG_KILL](#F-CSLibrary-Constants-Operation-TAG_KILL 'CSLibrary.Constants.Operation.TAG_KILL')
  - [TAG_LOCK](#F-CSLibrary-Constants-Operation-TAG_LOCK 'CSLibrary.Constants.Operation.TAG_LOCK')
  - [TAG_PREFILTER](#F-CSLibrary-Constants-Operation-TAG_PREFILTER 'CSLibrary.Constants.Operation.TAG_PREFILTER')
  - [TAG_RANGING](#F-CSLibrary-Constants-Operation-TAG_RANGING 'CSLibrary.Constants.Operation.TAG_RANGING')
  - [TAG_READ](#F-CSLibrary-Constants-Operation-TAG_READ 'CSLibrary.Constants.Operation.TAG_READ')
  - [TAG_READ_ACC_PWD](#F-CSLibrary-Constants-Operation-TAG_READ_ACC_PWD 'CSLibrary.Constants.Operation.TAG_READ_ACC_PWD')
  - [TAG_READ_EPC](#F-CSLibrary-Constants-Operation-TAG_READ_EPC 'CSLibrary.Constants.Operation.TAG_READ_EPC')
  - [TAG_READ_KILL_PWD](#F-CSLibrary-Constants-Operation-TAG_READ_KILL_PWD 'CSLibrary.Constants.Operation.TAG_READ_KILL_PWD')
  - [TAG_READ_PC](#F-CSLibrary-Constants-Operation-TAG_READ_PC 'CSLibrary.Constants.Operation.TAG_READ_PC')
  - [TAG_READ_PROTECT](#F-CSLibrary-Constants-Operation-TAG_READ_PROTECT 'CSLibrary.Constants.Operation.TAG_READ_PROTECT')
  - [TAG_READ_TID](#F-CSLibrary-Constants-Operation-TAG_READ_TID 'CSLibrary.Constants.Operation.TAG_READ_TID')
  - [TAG_READ_USER](#F-CSLibrary-Constants-Operation-TAG_READ_USER 'CSLibrary.Constants.Operation.TAG_READ_USER')
  - [TAG_RESET_READ_PROTECT](#F-CSLibrary-Constants-Operation-TAG_RESET_READ_PROTECT 'CSLibrary.Constants.Operation.TAG_RESET_READ_PROTECT')
  - [TAG_SEARCHING](#F-CSLibrary-Constants-Operation-TAG_SEARCHING 'CSLibrary.Constants.Operation.TAG_SEARCHING')
  - [TAG_SELECTED](#F-CSLibrary-Constants-Operation-TAG_SELECTED 'CSLibrary.Constants.Operation.TAG_SELECTED')
  - [TAG_WRITE](#F-CSLibrary-Constants-Operation-TAG_WRITE 'CSLibrary.Constants.Operation.TAG_WRITE')
  - [TAG_WRITE_ACC_PWD](#F-CSLibrary-Constants-Operation-TAG_WRITE_ACC_PWD 'CSLibrary.Constants.Operation.TAG_WRITE_ACC_PWD')
  - [TAG_WRITE_EPC](#F-CSLibrary-Constants-Operation-TAG_WRITE_EPC 'CSLibrary.Constants.Operation.TAG_WRITE_EPC')
  - [TAG_WRITE_KILL_PWD](#F-CSLibrary-Constants-Operation-TAG_WRITE_KILL_PWD 'CSLibrary.Constants.Operation.TAG_WRITE_KILL_PWD')
  - [TAG_WRITE_PC](#F-CSLibrary-Constants-Operation-TAG_WRITE_PC 'CSLibrary.Constants.Operation.TAG_WRITE_PC')
  - [TAG_WRITE_USER](#F-CSLibrary-Constants-Operation-TAG_WRITE_USER 'CSLibrary.Constants.Operation.TAG_WRITE_USER')
  - [UNKNOWN](#F-CSLibrary-Constants-Operation-UNKNOWN 'CSLibrary.Constants.Operation.UNKNOWN')
- [OptType](#T-CSLibrary-Constants-OptType 'CSLibrary.Constants.OptType')
- [PacketBitMap](#T-CSLibrary-Constants-PacketBitMap 'CSLibrary.Constants.PacketBitMap')
  - [accessErrorFlag](#F-CSLibrary-Constants-PacketBitMap-accessErrorFlag 'CSLibrary.Constants.PacketBitMap.accessErrorFlag')
  - [crcResult](#F-CSLibrary-Constants-PacketBitMap-crcResult 'CSLibrary.Constants.PacketBitMap.crcResult')
- [PasswordLevel](#T-CSLibrary-Structures-PasswordLevel 'CSLibrary.Structures.PasswordLevel')
  - [Application](#F-CSLibrary-Structures-PasswordLevel-Application 'CSLibrary.Structures.PasswordLevel.Application')
  - [Measurement](#F-CSLibrary-Structures-PasswordLevel-Measurement 'CSLibrary.Structures.PasswordLevel.Measurement')
  - [System](#F-CSLibrary-Structures-PasswordLevel-System 'CSLibrary.Structures.PasswordLevel.System')
- [PermalockCmdParms](#T-CSLibrary-Structures-PermalockCmdParms 'CSLibrary.Structures.PermalockCmdParms')
  - [#ctor()](#M-CSLibrary-Structures-PermalockCmdParms-#ctor-CSLibrary-Constants-PermalockFlags,System-UInt16,System-UInt16,System-UInt16[]- 'CSLibrary.Structures.PermalockCmdParms.#ctor(CSLibrary.Constants.PermalockFlags,System.UInt16,System.UInt16,System.UInt16[])')
  - [count](#F-CSLibrary-Structures-PermalockCmdParms-count 'CSLibrary.Structures.PermalockCmdParms.count')
  - [flags](#F-CSLibrary-Structures-PermalockCmdParms-flags 'CSLibrary.Structures.PermalockCmdParms.flags')
  - [offset](#F-CSLibrary-Structures-PermalockCmdParms-offset 'CSLibrary.Structures.PermalockCmdParms.offset')
  - [pData](#F-CSLibrary-Structures-PermalockCmdParms-pData 'CSLibrary.Structures.PermalockCmdParms.pData')
  - [Dispose()](#M-CSLibrary-Structures-PermalockCmdParms-Dispose 'CSLibrary.Structures.PermalockCmdParms.Dispose')
- [PermalockFlags](#T-CSLibrary-Constants-PermalockFlags 'CSLibrary.Constants.PermalockFlags')
  - [GET_VALUE](#F-CSLibrary-Constants-PermalockFlags-GET_VALUE 'CSLibrary.Constants.PermalockFlags.GET_VALUE')
  - [SET_VALUE](#F-CSLibrary-Constants-PermalockFlags-SET_VALUE 'CSLibrary.Constants.PermalockFlags.SET_VALUE')
- [PermalockParms](#T-CSLibrary-Structures-PermalockParms 'CSLibrary.Structures.PermalockParms')
  - [accessPassword](#F-CSLibrary-Structures-PermalockParms-accessPassword 'CSLibrary.Structures.PermalockParms.accessPassword')
  - [common](#F-CSLibrary-Structures-PermalockParms-common 'CSLibrary.Structures.PermalockParms.common')
  - [length](#F-CSLibrary-Structures-PermalockParms-length 'CSLibrary.Structures.PermalockParms.length')
  - [permalockCmdParms](#F-CSLibrary-Structures-PermalockParms-permalockCmdParms 'CSLibrary.Structures.PermalockParms.permalockCmdParms')
- [Permission](#T-CSLibrary-Constants-Permission 'CSLibrary.Constants.Permission')
  - [LOCK](#F-CSLibrary-Constants-Permission-LOCK 'CSLibrary.Constants.Permission.LOCK')
  - [P_LOCK](#F-CSLibrary-Constants-Permission-P_LOCK 'CSLibrary.Constants.Permission.P_LOCK')
  - [P_UNLOCK](#F-CSLibrary-Constants-Permission-P_UNLOCK 'CSLibrary.Constants.Permission.P_UNLOCK')
  - [UNCHANGED](#F-CSLibrary-Constants-Permission-UNCHANGED 'CSLibrary.Constants.Permission.UNCHANGED')
  - [UNKNOWN](#F-CSLibrary-Constants-Permission-UNKNOWN 'CSLibrary.Constants.Permission.UNKNOWN')
  - [UNLOCK](#F-CSLibrary-Constants-Permission-UNLOCK 'CSLibrary.Constants.Permission.UNLOCK')
- [ProfileConfig](#T-CSLibrary-Structures-ProfileConfig 'CSLibrary.Structures.ProfileConfig')
  - [#ctor()](#M-CSLibrary-Structures-ProfileConfig-#ctor 'CSLibrary.Structures.ProfileConfig.#ctor')
  - [length_](#F-CSLibrary-Structures-ProfileConfig-length_ 'CSLibrary.Structures.ProfileConfig.length_')
  - [length](#P-CSLibrary-Structures-ProfileConfig-length 'CSLibrary.Structures.ProfileConfig.length')
- [QTCommandParms](#T-CSLibrary-Structures-QTCommandParms 'CSLibrary.Structures.QTCommandParms')
  - [#ctor()](#M-CSLibrary-Structures-QTCommandParms-#ctor 'CSLibrary.Structures.QTCommandParms.#ctor')
  - [MEM](#F-CSLibrary-Structures-QTCommandParms-MEM 'CSLibrary.Structures.QTCommandParms.MEM')
  - [RW](#F-CSLibrary-Structures-QTCommandParms-RW 'CSLibrary.Structures.QTCommandParms.RW')
  - [SR](#F-CSLibrary-Structures-QTCommandParms-SR 'CSLibrary.Structures.QTCommandParms.SR')
  - [TP](#F-CSLibrary-Structures-QTCommandParms-TP 'CSLibrary.Structures.QTCommandParms.TP')
  - [accessPassword](#F-CSLibrary-Structures-QTCommandParms-accessPassword 'CSLibrary.Structures.QTCommandParms.accessPassword')
- [QTCtrlType](#T-CSLibrary-Constants-QTCtrlType 'CSLibrary.Constants.QTCtrlType')
- [QTMemMapType](#T-CSLibrary-Constants-QTMemMapType 'CSLibrary.Constants.QTMemMapType')
- [QTMode](#T-CSLibrary-Structures-QTMode 'CSLibrary.Structures.QTMode')
  - [PermPrivate](#F-CSLibrary-Structures-QTMode-PermPrivate 'CSLibrary.Structures.QTMode.PermPrivate')
  - [PermPublic](#F-CSLibrary-Structures-QTMode-PermPublic 'CSLibrary.Structures.QTMode.PermPublic')
  - [TempPrivate](#F-CSLibrary-Structures-QTMode-TempPrivate 'CSLibrary.Structures.QTMode.TempPrivate')
  - [TempPublic](#F-CSLibrary-Structures-QTMode-TempPublic 'CSLibrary.Structures.QTMode.TempPublic')
- [QTPersistenceType](#T-CSLibrary-Constants-QTPersistenceType 'CSLibrary.Constants.QTPersistenceType')
- [QTShortRangeType](#T-CSLibrary-Constants-QTShortRangeType 'CSLibrary.Constants.QTShortRangeType')
- [QueryParms](#T-CSLibrary-Structures-QueryParms 'CSLibrary.Structures.QueryParms')
  - [#ctor()](#M-CSLibrary-Structures-QueryParms-#ctor 'CSLibrary.Structures.QueryParms.#ctor')
  - [singulationParms](#F-CSLibrary-Structures-QueryParms-singulationParms 'CSLibrary.Structures.QueryParms.singulationParms')
  - [tagGroup](#F-CSLibrary-Structures-QueryParms-tagGroup 'CSLibrary.Structures.QueryParms.tagGroup')
- [RFID_18K6C](#T-CSLibrary-Constants-RFID_18K6C 'CSLibrary.Constants.RFID_18K6C')
  - [ACCESS](#F-CSLibrary-Constants-RFID_18K6C-ACCESS 'CSLibrary.Constants.RFID_18K6C.ACCESS')
  - [ACK](#F-CSLibrary-Constants-RFID_18K6C-ACK 'CSLibrary.Constants.RFID_18K6C.ACK')
  - [BLOCKERASE](#F-CSLibrary-Constants-RFID_18K6C-BLOCKERASE 'CSLibrary.Constants.RFID_18K6C.BLOCKERASE')
  - [BLOCKWRITE](#F-CSLibrary-Constants-RFID_18K6C-BLOCKWRITE 'CSLibrary.Constants.RFID_18K6C.BLOCKWRITE')
  - [KILL](#F-CSLibrary-Constants-RFID_18K6C-KILL 'CSLibrary.Constants.RFID_18K6C.KILL')
  - [LOCK](#F-CSLibrary-Constants-RFID_18K6C-LOCK 'CSLibrary.Constants.RFID_18K6C.LOCK')
  - [NAK](#F-CSLibrary-Constants-RFID_18K6C-NAK 'CSLibrary.Constants.RFID_18K6C.NAK')
  - [QT](#F-CSLibrary-Constants-RFID_18K6C-QT 'CSLibrary.Constants.RFID_18K6C.QT')
  - [QUERY](#F-CSLibrary-Constants-RFID_18K6C-QUERY 'CSLibrary.Constants.RFID_18K6C.QUERY')
  - [QUERYADJ](#F-CSLibrary-Constants-RFID_18K6C-QUERYADJ 'CSLibrary.Constants.RFID_18K6C.QUERYADJ')
  - [QUERYREP](#F-CSLibrary-Constants-RFID_18K6C-QUERYREP 'CSLibrary.Constants.RFID_18K6C.QUERYREP')
  - [READ](#F-CSLibrary-Constants-RFID_18K6C-READ 'CSLibrary.Constants.RFID_18K6C.READ')
  - [REQRN](#F-CSLibrary-Constants-RFID_18K6C-REQRN 'CSLibrary.Constants.RFID_18K6C.REQRN')
  - [SELECT](#F-CSLibrary-Constants-RFID_18K6C-SELECT 'CSLibrary.Constants.RFID_18K6C.SELECT')
  - [UNKNOWN](#F-CSLibrary-Constants-RFID_18K6C-UNKNOWN 'CSLibrary.Constants.RFID_18K6C.UNKNOWN')
  - [WRITE](#F-CSLibrary-Constants-RFID_18K6C-WRITE 'CSLibrary.Constants.RFID_18K6C.WRITE')
- [RFID_ACCESS](#T-CSLibrary-Constants-RFID_ACCESS 'CSLibrary.Constants.RFID_ACCESS')
  - [ACK_TIMEOUT](#F-CSLibrary-Constants-RFID_ACCESS-ACK_TIMEOUT 'CSLibrary.Constants.RFID_ACCESS.ACK_TIMEOUT')
  - [CRC_INVALID](#F-CSLibrary-Constants-RFID_ACCESS-CRC_INVALID 'CSLibrary.Constants.RFID_ACCESS.CRC_INVALID')
  - [CRC_INVALID_ON_KILL](#F-CSLibrary-Constants-RFID_ACCESS-CRC_INVALID_ON_KILL 'CSLibrary.Constants.RFID_ACCESS.CRC_INVALID_ON_KILL')
  - [CRC_INVALID_ON_READ](#F-CSLibrary-Constants-RFID_ACCESS-CRC_INVALID_ON_READ 'CSLibrary.Constants.RFID_ACCESS.CRC_INVALID_ON_READ')
  - [CRC_INVALID_ON_WRITE](#F-CSLibrary-Constants-RFID_ACCESS-CRC_INVALID_ON_WRITE 'CSLibrary.Constants.RFID_ACCESS.CRC_INVALID_ON_WRITE')
  - [GENERAL_ERR](#F-CSLibrary-Constants-RFID_ACCESS-GENERAL_ERR 'CSLibrary.Constants.RFID_ACCESS.GENERAL_ERR')
  - [INSUFFICIENT_POWER_TO_WRITE](#F-CSLibrary-Constants-RFID_ACCESS-INSUFFICIENT_POWER_TO_WRITE 'CSLibrary.Constants.RFID_ACCESS.INSUFFICIENT_POWER_TO_WRITE')
  - [INVALID_HANDLE_ON_KILL_CMD](#F-CSLibrary-Constants-RFID_ACCESS-INVALID_HANDLE_ON_KILL_CMD 'CSLibrary.Constants.RFID_ACCESS.INVALID_HANDLE_ON_KILL_CMD')
  - [MEMORY_LOCATION_NOT_EXIST](#F-CSLibrary-Constants-RFID_ACCESS-MEMORY_LOCATION_NOT_EXIST 'CSLibrary.Constants.RFID_ACCESS.MEMORY_LOCATION_NOT_EXIST')
  - [NOT_SUPPORTED](#F-CSLibrary-Constants-RFID_ACCESS-NOT_SUPPORTED 'CSLibrary.Constants.RFID_ACCESS.NOT_SUPPORTED')
  - [PERMISSION_DENIED](#F-CSLibrary-Constants-RFID_ACCESS-PERMISSION_DENIED 'CSLibrary.Constants.RFID_ACCESS.PERMISSION_DENIED')
  - [PROBLEM_TRANSMITTING_KILL_CMD](#F-CSLibrary-Constants-RFID_ACCESS-PROBLEM_TRANSMITTING_KILL_CMD 'CSLibrary.Constants.RFID_ACCESS.PROBLEM_TRANSMITTING_KILL_CMD')
  - [PROBLEM_TRANSMITTING_TAG_CMD](#F-CSLibrary-Constants-RFID_ACCESS-PROBLEM_TRANSMITTING_TAG_CMD 'CSLibrary.Constants.RFID_ACCESS.PROBLEM_TRANSMITTING_TAG_CMD')
  - [READ_TIMEOUT](#F-CSLibrary-Constants-RFID_ACCESS-READ_TIMEOUT 'CSLibrary.Constants.RFID_ACCESS.READ_TIMEOUT')
  - [REQ_TAG_HANDLE_FAILED](#F-CSLibrary-Constants-RFID_ACCESS-REQ_TAG_HANDLE_FAILED 'CSLibrary.Constants.RFID_ACCESS.REQ_TAG_HANDLE_FAILED')
  - [RESP_TIMEOUT](#F-CSLibrary-Constants-RFID_ACCESS-RESP_TIMEOUT 'CSLibrary.Constants.RFID_ACCESS.RESP_TIMEOUT')
  - [SUCCESS](#F-CSLibrary-Constants-RFID_ACCESS-SUCCESS 'CSLibrary.Constants.RFID_ACCESS.SUCCESS')
  - [UNKNOWN](#F-CSLibrary-Constants-RFID_ACCESS-UNKNOWN 'CSLibrary.Constants.RFID_ACCESS.UNKNOWN')
  - [WRITE_RETRY_EXCEEDED](#F-CSLibrary-Constants-RFID_ACCESS-WRITE_RETRY_EXCEEDED 'CSLibrary.Constants.RFID_ACCESS.WRITE_RETRY_EXCEEDED')
  - [WRITE_VERIFY_FAILED](#F-CSLibrary-Constants-RFID_ACCESS-WRITE_VERIFY_FAILED 'CSLibrary.Constants.RFID_ACCESS.WRITE_VERIFY_FAILED')
- [RFID_COMMAND_TYPE_18K6C](#T-CSLibrary-Constants-RFID_COMMAND_TYPE_18K6C 'CSLibrary.Constants.RFID_COMMAND_TYPE_18K6C')
  - [INVENTORY](#F-CSLibrary-Constants-RFID_COMMAND_TYPE_18K6C-INVENTORY 'CSLibrary.Constants.RFID_COMMAND_TYPE_18K6C.INVENTORY')
  - [KILL](#F-CSLibrary-Constants-RFID_COMMAND_TYPE_18K6C-KILL 'CSLibrary.Constants.RFID_COMMAND_TYPE_18K6C.KILL')
  - [LOCK](#F-CSLibrary-Constants-RFID_COMMAND_TYPE_18K6C-LOCK 'CSLibrary.Constants.RFID_COMMAND_TYPE_18K6C.LOCK')
  - [READ](#F-CSLibrary-Constants-RFID_COMMAND_TYPE_18K6C-READ 'CSLibrary.Constants.RFID_COMMAND_TYPE_18K6C.READ')
  - [WRITE](#F-CSLibrary-Constants-RFID_COMMAND_TYPE_18K6C-WRITE 'CSLibrary.Constants.RFID_COMMAND_TYPE_18K6C.WRITE')
- [RFID_PACKET_COMMAND_END](#T-CSLibrary-Structures-RFID_PACKET_COMMAND_END 'CSLibrary.Structures.RFID_PACKET_COMMAND_END')
  - [cmn](#F-CSLibrary-Structures-RFID_PACKET_COMMAND_END-cmn 'CSLibrary.Structures.RFID_PACKET_COMMAND_END.cmn')
- [RFID_PACKET_COMMON](#T-CSLibrary-Structures-RFID_PACKET_COMMON 'CSLibrary.Structures.RFID_PACKET_COMMON')
  - [flags](#F-CSLibrary-Structures-RFID_PACKET_COMMON-flags 'CSLibrary.Structures.RFID_PACKET_COMMON.flags')
  - [pkt_len](#F-CSLibrary-Structures-RFID_PACKET_COMMON-pkt_len 'CSLibrary.Structures.RFID_PACKET_COMMON.pkt_len')
  - [pkt_type](#F-CSLibrary-Structures-RFID_PACKET_COMMON-pkt_type 'CSLibrary.Structures.RFID_PACKET_COMMON.pkt_type')
  - [pkt_ver](#F-CSLibrary-Structures-RFID_PACKET_COMMON-pkt_ver 'CSLibrary.Structures.RFID_PACKET_COMMON.pkt_ver')
  - [res0](#F-CSLibrary-Structures-RFID_PACKET_COMMON-res0 'CSLibrary.Structures.RFID_PACKET_COMMON.res0')
- [RFID_PACKET_TYPE](#T-CSLibrary-Constants-RFID_PACKET_TYPE 'CSLibrary.Constants.RFID_PACKET_TYPE')
  - [ANTENNA_BEGIN](#F-CSLibrary-Constants-RFID_PACKET_TYPE-ANTENNA_BEGIN 'CSLibrary.Constants.RFID_PACKET_TYPE.ANTENNA_BEGIN')
  - [ANTENNA_CYCLE_BEGIN](#F-CSLibrary-Constants-RFID_PACKET_TYPE-ANTENNA_CYCLE_BEGIN 'CSLibrary.Constants.RFID_PACKET_TYPE.ANTENNA_CYCLE_BEGIN')
  - [ANTENNA_CYCLE_END](#F-CSLibrary-Constants-RFID_PACKET_TYPE-ANTENNA_CYCLE_END 'CSLibrary.Constants.RFID_PACKET_TYPE.ANTENNA_CYCLE_END')
  - [ANTENNA_END](#F-CSLibrary-Constants-RFID_PACKET_TYPE-ANTENNA_END 'CSLibrary.Constants.RFID_PACKET_TYPE.ANTENNA_END')
  - [CARRIER_INFO](#F-CSLibrary-Constants-RFID_PACKET_TYPE-CARRIER_INFO 'CSLibrary.Constants.RFID_PACKET_TYPE.CARRIER_INFO')
  - [COMMAND_BEGIN](#F-CSLibrary-Constants-RFID_PACKET_TYPE-COMMAND_BEGIN 'CSLibrary.Constants.RFID_PACKET_TYPE.COMMAND_BEGIN')
  - [COMMAND_END](#F-CSLibrary-Constants-RFID_PACKET_TYPE-COMMAND_END 'CSLibrary.Constants.RFID_PACKET_TYPE.COMMAND_END')
  - [CYCCFG_EVT](#F-CSLibrary-Constants-RFID_PACKET_TYPE-CYCCFG_EVT 'CSLibrary.Constants.RFID_PACKET_TYPE.CYCCFG_EVT')
  - [INVENTORY_CYCLE_BEGIN](#F-CSLibrary-Constants-RFID_PACKET_TYPE-INVENTORY_CYCLE_BEGIN 'CSLibrary.Constants.RFID_PACKET_TYPE.INVENTORY_CYCLE_BEGIN')
  - [INVENTORY_CYCLE_END](#F-CSLibrary-Constants-RFID_PACKET_TYPE-INVENTORY_CYCLE_END 'CSLibrary.Constants.RFID_PACKET_TYPE.INVENTORY_CYCLE_END')
  - [INVENTORY_CYCLE_END_DIAGS](#F-CSLibrary-Constants-RFID_PACKET_TYPE-INVENTORY_CYCLE_END_DIAGS 'CSLibrary.Constants.RFID_PACKET_TYPE.INVENTORY_CYCLE_END_DIAGS')
  - [ISO18K6C_INVENTORY](#F-CSLibrary-Constants-RFID_PACKET_TYPE-ISO18K6C_INVENTORY 'CSLibrary.Constants.RFID_PACKET_TYPE.ISO18K6C_INVENTORY')
  - [ISO18K6C_INVENTORY_DIAGS](#F-CSLibrary-Constants-RFID_PACKET_TYPE-ISO18K6C_INVENTORY_DIAGS 'CSLibrary.Constants.RFID_PACKET_TYPE.ISO18K6C_INVENTORY_DIAGS')
  - [ISO18K6C_INVENTORY_ROUND_BEGIN](#F-CSLibrary-Constants-RFID_PACKET_TYPE-ISO18K6C_INVENTORY_ROUND_BEGIN 'CSLibrary.Constants.RFID_PACKET_TYPE.ISO18K6C_INVENTORY_ROUND_BEGIN')
  - [ISO18K6C_INVENTORY_ROUND_BEGIN_DIAGS](#F-CSLibrary-Constants-RFID_PACKET_TYPE-ISO18K6C_INVENTORY_ROUND_BEGIN_DIAGS 'CSLibrary.Constants.RFID_PACKET_TYPE.ISO18K6C_INVENTORY_ROUND_BEGIN_DIAGS')
  - [ISO18K6C_INVENTORY_ROUND_END](#F-CSLibrary-Constants-RFID_PACKET_TYPE-ISO18K6C_INVENTORY_ROUND_END 'CSLibrary.Constants.RFID_PACKET_TYPE.ISO18K6C_INVENTORY_ROUND_END')
  - [ISO18K6C_INVENTORY_ROUND_END_DIAGS](#F-CSLibrary-Constants-RFID_PACKET_TYPE-ISO18K6C_INVENTORY_ROUND_END_DIAGS 'CSLibrary.Constants.RFID_PACKET_TYPE.ISO18K6C_INVENTORY_ROUND_END_DIAGS')
  - [ISO18K6C_TAG_ACCESS](#F-CSLibrary-Constants-RFID_PACKET_TYPE-ISO18K6C_TAG_ACCESS 'CSLibrary.Constants.RFID_PACKET_TYPE.ISO18K6C_TAG_ACCESS')
  - [NONCRITICAL_FAULT](#F-CSLibrary-Constants-RFID_PACKET_TYPE-NONCRITICAL_FAULT 'CSLibrary.Constants.RFID_PACKET_TYPE.NONCRITICAL_FAULT')
  - [RES0](#F-CSLibrary-Constants-RFID_PACKET_TYPE-RES0 'CSLibrary.Constants.RFID_PACKET_TYPE.RES0')
  - [RES1](#F-CSLibrary-Constants-RFID_PACKET_TYPE-RES1 'CSLibrary.Constants.RFID_PACKET_TYPE.RES1')
  - [RES2](#F-CSLibrary-Constants-RFID_PACKET_TYPE-RES2 'CSLibrary.Constants.RFID_PACKET_TYPE.RES2')
  - [RES3](#F-CSLibrary-Constants-RFID_PACKET_TYPE-RES3 'CSLibrary.Constants.RFID_PACKET_TYPE.RES3')
  - [RES4](#F-CSLibrary-Constants-RFID_PACKET_TYPE-RES4 'CSLibrary.Constants.RFID_PACKET_TYPE.RES4')
- [RFState](#T-CSLibrary-Constants-RFState 'CSLibrary.Constants.RFState')
  - [ABORT](#F-CSLibrary-Constants-RFState-ABORT 'CSLibrary.Constants.RFState.ABORT')
  - [ANT_CYCLE_END](#F-CSLibrary-Constants-RFState-ANT_CYCLE_END 'CSLibrary.Constants.RFState.ANT_CYCLE_END')
  - [BUFFER_FULL](#F-CSLibrary-Constants-RFState-BUFFER_FULL 'CSLibrary.Constants.RFState.BUFFER_FULL')
  - [BUSY](#F-CSLibrary-Constants-RFState-BUSY 'CSLibrary.Constants.RFState.BUSY')
  - [CARRIER_INFO](#F-CSLibrary-Constants-RFState-CARRIER_INFO 'CSLibrary.Constants.RFState.CARRIER_INFO')
  - [CH_BUSY](#F-CSLibrary-Constants-RFState-CH_BUSY 'CSLibrary.Constants.RFState.CH_BUSY')
  - [CH_CLEAR](#F-CSLibrary-Constants-RFState-CH_CLEAR 'CSLibrary.Constants.RFState.CH_CLEAR')
  - [DISCONNECTED](#F-CSLibrary-Constants-RFState-DISCONNECTED 'CSLibrary.Constants.RFState.DISCONNECTED')
  - [EAS_ALARM](#F-CSLibrary-Constants-RFState-EAS_ALARM 'CSLibrary.Constants.RFState.EAS_ALARM')
  - [ENGTESTRESULT](#F-CSLibrary-Constants-RFState-ENGTESTRESULT 'CSLibrary.Constants.RFState.ENGTESTRESULT')
  - [ERROR](#F-CSLibrary-Constants-RFState-ERROR 'CSLibrary.Constants.RFState.ERROR')
  - [IDLE](#F-CSLibrary-Constants-RFState-IDLE 'CSLibrary.Constants.RFState.IDLE')
  - [INVENTORY_CYCLE_BEGIN](#F-CSLibrary-Constants-RFState-INVENTORY_CYCLE_BEGIN 'CSLibrary.Constants.RFState.INVENTORY_CYCLE_BEGIN')
  - [INVENTORY_CYCLE_END_DIAGNOSTICS](#F-CSLibrary-Constants-RFState-INVENTORY_CYCLE_END_DIAGNOSTICS 'CSLibrary.Constants.RFState.INVENTORY_CYCLE_END_DIAGNOSTICS')
  - [INVENTORY_MAC_ERROR](#F-CSLibrary-Constants-RFState-INVENTORY_MAC_ERROR 'CSLibrary.Constants.RFState.INVENTORY_MAC_ERROR')
  - [INVENTORY_ROUND_BEGIN](#F-CSLibrary-Constants-RFState-INVENTORY_ROUND_BEGIN 'CSLibrary.Constants.RFState.INVENTORY_ROUND_BEGIN')
  - [INVENTORY_ROUND_BEGIN_DIAGNOSTICS](#F-CSLibrary-Constants-RFState-INVENTORY_ROUND_BEGIN_DIAGNOSTICS 'CSLibrary.Constants.RFState.INVENTORY_ROUND_BEGIN_DIAGNOSTICS')
  - [INVENTORY_ROUND_END](#F-CSLibrary-Constants-RFState-INVENTORY_ROUND_END 'CSLibrary.Constants.RFState.INVENTORY_ROUND_END')
  - [INVENTORY_ROUND_END_DIAGNOSTICS](#F-CSLibrary-Constants-RFState-INVENTORY_ROUND_END_DIAGNOSTICS 'CSLibrary.Constants.RFState.INVENTORY_ROUND_END_DIAGNOSTICS')
  - [RESET](#F-CSLibrary-Constants-RFState-RESET 'CSLibrary.Constants.RFState.RESET')
  - [SHUTDOWN](#F-CSLibrary-Constants-RFState-SHUTDOWN 'CSLibrary.Constants.RFState.SHUTDOWN')
  - [UNKNOWN](#F-CSLibrary-Constants-RFState-UNKNOWN 'CSLibrary.Constants.RFState.UNKNOWN')
- [RadioInformation](#T-CSLibrary-Structures-RadioInformation 'CSLibrary.Structures.RadioInformation')
  - [#ctor()](#M-CSLibrary-Structures-RadioInformation-#ctor 'CSLibrary.Structures.RadioInformation.#ctor')
  - [cookie](#F-CSLibrary-Structures-RadioInformation-cookie 'CSLibrary.Structures.RadioInformation.cookie')
  - [driverVersion](#F-CSLibrary-Structures-RadioInformation-driverVersion 'CSLibrary.Structures.RadioInformation.driverVersion')
  - [idLength](#F-CSLibrary-Structures-RadioInformation-idLength 'CSLibrary.Structures.RadioInformation.idLength')
  - [length](#F-CSLibrary-Structures-RadioInformation-length 'CSLibrary.Structures.RadioInformation.length')
  - [uniqueId](#F-CSLibrary-Structures-RadioInformation-uniqueId 'CSLibrary.Structures.RadioInformation.uniqueId')
- [RadioLinkProfile](#T-CSLibrary-Structures-RadioLinkProfile 'CSLibrary.Structures.RadioLinkProfile')
  - [#ctor()](#M-CSLibrary-Structures-RadioLinkProfile-#ctor 'CSLibrary.Structures.RadioLinkProfile.#ctor')
  - [denseReaderMode](#F-CSLibrary-Structures-RadioLinkProfile-denseReaderMode 'CSLibrary.Structures.RadioLinkProfile.denseReaderMode')
  - [enabled](#F-CSLibrary-Structures-RadioLinkProfile-enabled 'CSLibrary.Structures.RadioLinkProfile.enabled')
  - [length_](#F-CSLibrary-Structures-RadioLinkProfile-length_ 'CSLibrary.Structures.RadioLinkProfile.length_')
  - [narrowbandRssiSamples](#F-CSLibrary-Structures-RadioLinkProfile-narrowbandRssiSamples 'CSLibrary.Structures.RadioLinkProfile.narrowbandRssiSamples')
  - [profileConfig_](#F-CSLibrary-Structures-RadioLinkProfile-profileConfig_ 'CSLibrary.Structures.RadioLinkProfile.profileConfig_')
  - [profileId](#F-CSLibrary-Structures-RadioLinkProfile-profileId 'CSLibrary.Structures.RadioLinkProfile.profileId')
  - [profileProtocol_](#F-CSLibrary-Structures-RadioLinkProfile-profileProtocol_ 'CSLibrary.Structures.RadioLinkProfile.profileProtocol_')
  - [profileVersion](#F-CSLibrary-Structures-RadioLinkProfile-profileVersion 'CSLibrary.Structures.RadioLinkProfile.profileVersion')
  - [realtimeNarrowbandRssiSamples](#F-CSLibrary-Structures-RadioLinkProfile-realtimeNarrowbandRssiSamples 'CSLibrary.Structures.RadioLinkProfile.realtimeNarrowbandRssiSamples')
  - [realtimeRssiEnabled](#F-CSLibrary-Structures-RadioLinkProfile-realtimeRssiEnabled 'CSLibrary.Structures.RadioLinkProfile.realtimeRssiEnabled')
  - [realtimeWidebandRssiSamples](#F-CSLibrary-Structures-RadioLinkProfile-realtimeWidebandRssiSamples 'CSLibrary.Structures.RadioLinkProfile.realtimeWidebandRssiSamples')
  - [widebandRssiSamples](#F-CSLibrary-Structures-RadioLinkProfile-widebandRssiSamples 'CSLibrary.Structures.RadioLinkProfile.widebandRssiSamples')
  - [length](#P-CSLibrary-Structures-RadioLinkProfile-length 'CSLibrary.Structures.RadioLinkProfile.length')
  - [profileConfig](#P-CSLibrary-Structures-RadioLinkProfile-profileConfig 'CSLibrary.Structures.RadioLinkProfile.profileConfig')
  - [profileProtocol](#P-CSLibrary-Structures-RadioLinkProfile-profileProtocol 'CSLibrary.Structures.RadioLinkProfile.profileProtocol')
- [RadioLinkProfileConfig](#T-CSLibrary-Structures-RadioLinkProfileConfig 'CSLibrary.Structures.RadioLinkProfileConfig')
  - [#ctor()](#M-CSLibrary-Structures-RadioLinkProfileConfig-#ctor 'CSLibrary.Structures.RadioLinkProfileConfig.#ctor')
  - [data01Difference](#F-CSLibrary-Structures-RadioLinkProfileConfig-data01Difference 'CSLibrary.Structures.RadioLinkProfileConfig.data01Difference')
  - [divideRatio](#F-CSLibrary-Structures-RadioLinkProfileConfig-divideRatio 'CSLibrary.Structures.RadioLinkProfileConfig.divideRatio')
  - [millerNumber](#F-CSLibrary-Structures-RadioLinkProfileConfig-millerNumber 'CSLibrary.Structures.RadioLinkProfileConfig.millerNumber')
  - [minT2Delay](#F-CSLibrary-Structures-RadioLinkProfileConfig-minT2Delay 'CSLibrary.Structures.RadioLinkProfileConfig.minT2Delay')
  - [modulationType](#F-CSLibrary-Structures-RadioLinkProfileConfig-modulationType 'CSLibrary.Structures.RadioLinkProfileConfig.modulationType')
  - [pulseWidth](#F-CSLibrary-Structures-RadioLinkProfileConfig-pulseWidth 'CSLibrary.Structures.RadioLinkProfileConfig.pulseWidth')
  - [rtCalibration](#F-CSLibrary-Structures-RadioLinkProfileConfig-rtCalibration 'CSLibrary.Structures.RadioLinkProfileConfig.rtCalibration')
  - [rxDelay](#F-CSLibrary-Structures-RadioLinkProfileConfig-rxDelay 'CSLibrary.Structures.RadioLinkProfileConfig.rxDelay')
  - [tari](#F-CSLibrary-Structures-RadioLinkProfileConfig-tari 'CSLibrary.Structures.RadioLinkProfileConfig.tari')
  - [trCalibration](#F-CSLibrary-Structures-RadioLinkProfileConfig-trCalibration 'CSLibrary.Structures.RadioLinkProfileConfig.trCalibration')
  - [trLinkFrequency](#F-CSLibrary-Structures-RadioLinkProfileConfig-trLinkFrequency 'CSLibrary.Structures.RadioLinkProfileConfig.trLinkFrequency')
  - [txPropagationDelay](#F-CSLibrary-Structures-RadioLinkProfileConfig-txPropagationDelay 'CSLibrary.Structures.RadioLinkProfileConfig.txPropagationDelay')
  - [varT2Delay](#F-CSLibrary-Structures-RadioLinkProfileConfig-varT2Delay 'CSLibrary.Structures.RadioLinkProfileConfig.varT2Delay')
- [RadioOperationMode](#T-CSLibrary-Constants-RadioOperationMode 'CSLibrary.Constants.RadioOperationMode')
  - [CONTINUOUS](#F-CSLibrary-Constants-RadioOperationMode-CONTINUOUS 'CSLibrary.Constants.RadioOperationMode.CONTINUOUS')
  - [NONCONTINUOUS](#F-CSLibrary-Constants-RadioOperationMode-NONCONTINUOUS 'CSLibrary.Constants.RadioOperationMode.NONCONTINUOUS')
  - [UNKNOWN](#F-CSLibrary-Constants-RadioOperationMode-UNKNOWN 'CSLibrary.Constants.RadioOperationMode.UNKNOWN')
- [RadioPowerState](#T-CSLibrary-Constants-RadioPowerState 'CSLibrary.Constants.RadioPowerState')
  - [FULL](#F-CSLibrary-Constants-RadioPowerState-FULL 'CSLibrary.Constants.RadioPowerState.FULL')
  - [STANDBY](#F-CSLibrary-Constants-RadioPowerState-STANDBY 'CSLibrary.Constants.RadioPowerState.STANDBY')
  - [UNKNOWN](#F-CSLibrary-Constants-RadioPowerState-UNKNOWN 'CSLibrary.Constants.RadioPowerState.UNKNOWN')
- [RadioProtocol](#T-CSLibrary-Constants-RadioProtocol 'CSLibrary.Constants.RadioProtocol')
  - [ISO18K6C](#F-CSLibrary-Constants-RadioProtocol-ISO18K6C 'CSLibrary.Constants.RadioProtocol.ISO18K6C')
  - [UNKNOWN](#F-CSLibrary-Constants-RadioProtocol-UNKNOWN 'CSLibrary.Constants.RadioProtocol.UNKNOWN')
- [Read2BandsCmdParms](#T-CSLibrary-Structures-Read2BandsCmdParms 'CSLibrary.Structures.Read2BandsCmdParms')
  - [#ctor(initial)](#M-CSLibrary-Structures-Read2BandsCmdParms-#ctor-System-Boolean- 'CSLibrary.Structures.Read2BandsCmdParms.#ctor(System.Boolean)')
  - [bank1](#F-CSLibrary-Structures-Read2BandsCmdParms-bank1 'CSLibrary.Structures.Read2BandsCmdParms.bank1')
  - [bank2](#F-CSLibrary-Structures-Read2BandsCmdParms-bank2 'CSLibrary.Structures.Read2BandsCmdParms.bank2')
  - [count1](#F-CSLibrary-Structures-Read2BandsCmdParms-count1 'CSLibrary.Structures.Read2BandsCmdParms.count1')
  - [count2](#F-CSLibrary-Structures-Read2BandsCmdParms-count2 'CSLibrary.Structures.Read2BandsCmdParms.count2')
  - [length](#F-CSLibrary-Structures-Read2BandsCmdParms-length 'CSLibrary.Structures.Read2BandsCmdParms.length')
  - [offset1](#F-CSLibrary-Structures-Read2BandsCmdParms-offset1 'CSLibrary.Structures.Read2BandsCmdParms.offset1')
  - [offset2](#F-CSLibrary-Structures-Read2BandsCmdParms-offset2 'CSLibrary.Structures.Read2BandsCmdParms.offset2')
- [ReadCmdParms](#T-CSLibrary-Structures-ReadCmdParms 'CSLibrary.Structures.ReadCmdParms')
  - [#ctor(initial)](#M-CSLibrary-Structures-ReadCmdParms-#ctor-System-Boolean- 'CSLibrary.Structures.ReadCmdParms.#ctor(System.Boolean)')
  - [bank](#F-CSLibrary-Structures-ReadCmdParms-bank 'CSLibrary.Structures.ReadCmdParms.bank')
  - [count](#F-CSLibrary-Structures-ReadCmdParms-count 'CSLibrary.Structures.ReadCmdParms.count')
  - [length](#F-CSLibrary-Structures-ReadCmdParms-length 'CSLibrary.Structures.ReadCmdParms.length')
  - [offset](#F-CSLibrary-Structures-ReadCmdParms-offset 'CSLibrary.Structures.ReadCmdParms.offset')
- [ReadParms](#T-CSLibrary-Structures-ReadParms 'CSLibrary.Structures.ReadParms')
  - [#ctor(initial)](#M-CSLibrary-Structures-ReadParms-#ctor-System-Boolean- 'CSLibrary.Structures.ReadParms.#ctor(System.Boolean)')
  - [accessPassword](#F-CSLibrary-Structures-ReadParms-accessPassword 'CSLibrary.Structures.ReadParms.accessPassword')
  - [common](#F-CSLibrary-Structures-ReadParms-common 'CSLibrary.Structures.ReadParms.common')
  - [length](#F-CSLibrary-Structures-ReadParms-length 'CSLibrary.Structures.ReadParms.length')
  - [readCmdParms](#F-CSLibrary-Structures-ReadParms-readCmdParms 'CSLibrary.Structures.ReadParms.readCmdParms')
- [ReadProtectParms](#T-CSLibrary-Structures-ReadProtectParms 'CSLibrary.Structures.ReadProtectParms')
  - [accessPassword](#F-CSLibrary-Structures-ReadProtectParms-accessPassword 'CSLibrary.Structures.ReadProtectParms.accessPassword')
  - [common](#F-CSLibrary-Structures-ReadProtectParms-common 'CSLibrary.Structures.ReadProtectParms.common')
  - [length](#F-CSLibrary-Structures-ReadProtectParms-length 'CSLibrary.Structures.ReadProtectParms.length')
- [RecvOperation](#T-CSLibrary-Net-RecvOperation 'CSLibrary.Net.RecvOperation')
  - [ASSIGN](#F-CSLibrary-Net-RecvOperation-ASSIGN 'CSLibrary.Net.RecvOperation.ASSIGN')
  - [CLOSED](#F-CSLibrary-Net-RecvOperation-CLOSED 'CSLibrary.Net.RecvOperation.CLOSED')
  - [IDLE](#F-CSLibrary-Net-RecvOperation-IDLE 'CSLibrary.Net.RecvOperation.IDLE')
  - [SEARCH](#F-CSLibrary-Net-RecvOperation-SEARCH 'CSLibrary.Net.RecvOperation.SEARCH')
  - [UPDATE](#F-CSLibrary-Net-RecvOperation-UPDATE 'CSLibrary.Net.RecvOperation.UPDATE')
- [RegionCode](#T-CSLibrary-Constants-RegionCode 'CSLibrary.Constants.RegionCode')
  - [AR](#F-CSLibrary-Constants-RegionCode-AR 'CSLibrary.Constants.RegionCode.AR')
  - [AU](#F-CSLibrary-Constants-RegionCode-AU 'CSLibrary.Constants.RegionCode.AU')
  - [BR1](#F-CSLibrary-Constants-RegionCode-BR1 'CSLibrary.Constants.RegionCode.BR1')
  - [BR2](#F-CSLibrary-Constants-RegionCode-BR2 'CSLibrary.Constants.RegionCode.BR2')
  - [BR3](#F-CSLibrary-Constants-RegionCode-BR3 'CSLibrary.Constants.RegionCode.BR3')
  - [BR4](#F-CSLibrary-Constants-RegionCode-BR4 'CSLibrary.Constants.RegionCode.BR4')
  - [BR5](#F-CSLibrary-Constants-RegionCode-BR5 'CSLibrary.Constants.RegionCode.BR5')
  - [CL](#F-CSLibrary-Constants-RegionCode-CL 'CSLibrary.Constants.RegionCode.CL')
  - [CN](#F-CSLibrary-Constants-RegionCode-CN 'CSLibrary.Constants.RegionCode.CN')
  - [CO](#F-CSLibrary-Constants-RegionCode-CO 'CSLibrary.Constants.RegionCode.CO')
  - [CR](#F-CSLibrary-Constants-RegionCode-CR 'CSLibrary.Constants.RegionCode.CR')
  - [CURRENT](#F-CSLibrary-Constants-RegionCode-CURRENT 'CSLibrary.Constants.RegionCode.CURRENT')
  - [DO](#F-CSLibrary-Constants-RegionCode-DO 'CSLibrary.Constants.RegionCode.DO')
  - [ETSI](#F-CSLibrary-Constants-RegionCode-ETSI 'CSLibrary.Constants.RegionCode.ETSI')
  - [ETSIUPPERBAND](#F-CSLibrary-Constants-RegionCode-ETSIUPPERBAND 'CSLibrary.Constants.RegionCode.ETSIUPPERBAND')
  - [FCC](#F-CSLibrary-Constants-RegionCode-FCC 'CSLibrary.Constants.RegionCode.FCC')
  - [G800](#F-CSLibrary-Constants-RegionCode-G800 'CSLibrary.Constants.RegionCode.G800')
  - [HK](#F-CSLibrary-Constants-RegionCode-HK 'CSLibrary.Constants.RegionCode.HK')
  - [HK50](#F-CSLibrary-Constants-RegionCode-HK50 'CSLibrary.Constants.RegionCode.HK50')
  - [HK8](#F-CSLibrary-Constants-RegionCode-HK8 'CSLibrary.Constants.RegionCode.HK8')
  - [ID](#F-CSLibrary-Constants-RegionCode-ID 'CSLibrary.Constants.RegionCode.ID')
  - [IN](#F-CSLibrary-Constants-RegionCode-IN 'CSLibrary.Constants.RegionCode.IN')
  - [JE](#F-CSLibrary-Constants-RegionCode-JE 'CSLibrary.Constants.RegionCode.JE')
  - [JP](#F-CSLibrary-Constants-RegionCode-JP 'CSLibrary.Constants.RegionCode.JP')
  - [KR](#F-CSLibrary-Constants-RegionCode-KR 'CSLibrary.Constants.RegionCode.KR')
  - [LH](#F-CSLibrary-Constants-RegionCode-LH 'CSLibrary.Constants.RegionCode.LH')
  - [LH1](#F-CSLibrary-Constants-RegionCode-LH1 'CSLibrary.Constants.RegionCode.LH1')
  - [LH2](#F-CSLibrary-Constants-RegionCode-LH2 'CSLibrary.Constants.RegionCode.LH2')
  - [MX](#F-CSLibrary-Constants-RegionCode-MX 'CSLibrary.Constants.RegionCode.MX')
  - [MY](#F-CSLibrary-Constants-RegionCode-MY 'CSLibrary.Constants.RegionCode.MY')
  - [NZ](#F-CSLibrary-Constants-RegionCode-NZ 'CSLibrary.Constants.RegionCode.NZ')
  - [PA](#F-CSLibrary-Constants-RegionCode-PA 'CSLibrary.Constants.RegionCode.PA')
  - [PE](#F-CSLibrary-Constants-RegionCode-PE 'CSLibrary.Constants.RegionCode.PE')
  - [PH](#F-CSLibrary-Constants-RegionCode-PH 'CSLibrary.Constants.RegionCode.PH')
  - [SAHOPPING](#F-CSLibrary-Constants-RegionCode-SAHOPPING 'CSLibrary.Constants.RegionCode.SAHOPPING')
  - [SG](#F-CSLibrary-Constants-RegionCode-SG 'CSLibrary.Constants.RegionCode.SG')
  - [TH](#F-CSLibrary-Constants-RegionCode-TH 'CSLibrary.Constants.RegionCode.TH')
  - [TW](#F-CSLibrary-Constants-RegionCode-TW 'CSLibrary.Constants.RegionCode.TW')
  - [UH1](#F-CSLibrary-Constants-RegionCode-UH1 'CSLibrary.Constants.RegionCode.UH1')
  - [UH2](#F-CSLibrary-Constants-RegionCode-UH2 'CSLibrary.Constants.RegionCode.UH2')
  - [UNKNOWN](#F-CSLibrary-Constants-RegionCode-UNKNOWN 'CSLibrary.Constants.RegionCode.UNKNOWN')
  - [UY](#F-CSLibrary-Constants-RegionCode-UY 'CSLibrary.Constants.RegionCode.UY')
  - [VE](#F-CSLibrary-Constants-RegionCode-VE 'CSLibrary.Constants.RegionCode.VE')
  - [VI](#F-CSLibrary-Constants-RegionCode-VI 'CSLibrary.Constants.RegionCode.VI')
  - [ZA](#F-CSLibrary-Constants-RegionCode-ZA 'CSLibrary.Constants.RegionCode.ZA')
- [ResponseMode](#T-CSLibrary-Constants-ResponseMode 'CSLibrary.Constants.ResponseMode')
  - [COMPACT](#F-CSLibrary-Constants-ResponseMode-COMPACT 'CSLibrary.Constants.ResponseMode.COMPACT')
  - [EXTENDED](#F-CSLibrary-Constants-ResponseMode-EXTENDED 'CSLibrary.Constants.ResponseMode.EXTENDED')
  - [NORMAL](#F-CSLibrary-Constants-ResponseMode-NORMAL 'CSLibrary.Constants.ResponseMode.NORMAL')
  - [UNKNOWN](#F-CSLibrary-Constants-ResponseMode-UNKNOWN 'CSLibrary.Constants.ResponseMode.UNKNOWN')
- [ResponseType](#T-CSLibrary-Constants-ResponseType 'CSLibrary.Constants.ResponseType')
  - [DATA](#F-CSLibrary-Constants-ResponseType-DATA 'CSLibrary.Constants.ResponseType.DATA')
  - [UNKNOWN](#F-CSLibrary-Constants-ResponseType-UNKNOWN 'CSLibrary.Constants.ResponseType.UNKNOWN')
- [Result](#T-CSLibrary-Constants-Result 'CSLibrary.Constants.Result')
- [Result](#T-CSLibrary-Net-Result 'CSLibrary.Net.Result')
  - [ALREADY_OPEN](#F-CSLibrary-Constants-Result-ALREADY_OPEN 'CSLibrary.Constants.Result.ALREADY_OPEN')
  - [BUFFER_TOO_SMALL](#F-CSLibrary-Constants-Result-BUFFER_TOO_SMALL 'CSLibrary.Constants.Result.BUFFER_TOO_SMALL')
  - [CHECK_STATUS_FAIL](#F-CSLibrary-Constants-Result-CHECK_STATUS_FAIL 'CSLibrary.Constants.Result.CHECK_STATUS_FAIL')
  - [CURRENTLY_NOT_ALLOWED](#F-CSLibrary-Constants-Result-CURRENTLY_NOT_ALLOWED 'CSLibrary.Constants.Result.CURRENTLY_NOT_ALLOWED')
  - [DEVICE_CONNECTED](#F-CSLibrary-Constants-Result-DEVICE_CONNECTED 'CSLibrary.Constants.Result.DEVICE_CONNECTED')
  - [DEVICE_NOT_SUPPORT](#F-CSLibrary-Constants-Result-DEVICE_NOT_SUPPORT 'CSLibrary.Constants.Result.DEVICE_NOT_SUPPORT')
  - [DRIVER_LOAD](#F-CSLibrary-Constants-Result-DRIVER_LOAD 'CSLibrary.Constants.Result.DRIVER_LOAD')
  - [DRIVER_MISMATCH](#F-CSLibrary-Constants-Result-DRIVER_MISMATCH 'CSLibrary.Constants.Result.DRIVER_MISMATCH')
  - [EMULATION_MODE](#F-CSLibrary-Constants-Result-EMULATION_MODE 'CSLibrary.Constants.Result.EMULATION_MODE')
  - [FAILURE](#F-CSLibrary-Constants-Result-FAILURE 'CSLibrary.Constants.Result.FAILURE')
  - [FIRMWARE_TOO_OLD](#F-CSLibrary-Constants-Result-FIRMWARE_TOO_OLD 'CSLibrary.Constants.Result.FIRMWARE_TOO_OLD')
  - [INVALID_ANTENNA](#F-CSLibrary-Constants-Result-INVALID_ANTENNA 'CSLibrary.Constants.Result.INVALID_ANTENNA')
  - [INVALID_HANDLE](#F-CSLibrary-Constants-Result-INVALID_HANDLE 'CSLibrary.Constants.Result.INVALID_HANDLE')
  - [INVALID_OEM_COUNTRY_CODE](#F-CSLibrary-Constants-Result-INVALID_OEM_COUNTRY_CODE 'CSLibrary.Constants.Result.INVALID_OEM_COUNTRY_CODE')
  - [INVALID_PARAMETER](#F-CSLibrary-Constants-Result-INVALID_PARAMETER 'CSLibrary.Constants.Result.INVALID_PARAMETER')
  - [MAC_ERROR](#F-CSLibrary-Constants-Result-MAC_ERROR 'CSLibrary.Constants.Result.MAC_ERROR')
  - [MAX_RETRY_EXIT](#F-CSLibrary-Constants-Result-MAX_RETRY_EXIT 'CSLibrary.Constants.Result.MAX_RETRY_EXIT')
  - [NETWORK_LOST](#F-CSLibrary-Constants-Result-NETWORK_LOST 'CSLibrary.Constants.Result.NETWORK_LOST')
  - [NETWORK_RESET](#F-CSLibrary-Constants-Result-NETWORK_RESET 'CSLibrary.Constants.Result.NETWORK_RESET')
  - [NONVOLATILE_INIT_FAILED](#F-CSLibrary-Constants-Result-NONVOLATILE_INIT_FAILED 'CSLibrary.Constants.Result.NONVOLATILE_INIT_FAILED')
  - [NONVOLATILE_OUT_OF_BOUNDS](#F-CSLibrary-Constants-Result-NONVOLATILE_OUT_OF_BOUNDS 'CSLibrary.Constants.Result.NONVOLATILE_OUT_OF_BOUNDS')
  - [NONVOLATILE_WRITE_FAILED](#F-CSLibrary-Constants-Result-NONVOLATILE_WRITE_FAILED 'CSLibrary.Constants.Result.NONVOLATILE_WRITE_FAILED')
  - [NOT_INITIALIZED](#F-CSLibrary-Constants-Result-NOT_INITIALIZED 'CSLibrary.Constants.Result.NOT_INITIALIZED')
  - [NOT_SUPPORTED](#F-CSLibrary-Constants-Result-NOT_SUPPORTED 'CSLibrary.Constants.Result.NOT_SUPPORTED')
  - [NO_SUCH_RADIO](#F-CSLibrary-Constants-Result-NO_SUCH_RADIO 'CSLibrary.Constants.Result.NO_SUCH_RADIO')
  - [NO_TAG_FOUND](#F-CSLibrary-Constants-Result-NO_TAG_FOUND 'CSLibrary.Constants.Result.NO_TAG_FOUND')
  - [OK](#F-CSLibrary-Constants-Result-OK 'CSLibrary.Constants.Result.OK')
  - [OPERATION_CANCELLED](#F-CSLibrary-Constants-Result-OPERATION_CANCELLED 'CSLibrary.Constants.Result.OPERATION_CANCELLED')
  - [OUT_OF_MEMORY](#F-CSLibrary-Constants-Result-OUT_OF_MEMORY 'CSLibrary.Constants.Result.OUT_OF_MEMORY')
  - [POWER_DOWN_FAIL](#F-CSLibrary-Constants-Result-POWER_DOWN_FAIL 'CSLibrary.Constants.Result.POWER_DOWN_FAIL')
  - [POWER_UP_FAIL](#F-CSLibrary-Constants-Result-POWER_UP_FAIL 'CSLibrary.Constants.Result.POWER_UP_FAIL')
  - [PREALLOCATED_BUFFER_FULL](#F-CSLibrary-Constants-Result-PREALLOCATED_BUFFER_FULL 'CSLibrary.Constants.Result.PREALLOCATED_BUFFER_FULL')
  - [RADIO_BUSY](#F-CSLibrary-Constants-Result-RADIO_BUSY 'CSLibrary.Constants.Result.RADIO_BUSY')
  - [RADIO_FAILURE](#F-CSLibrary-Constants-Result-RADIO_FAILURE 'CSLibrary.Constants.Result.RADIO_FAILURE')
  - [RADIO_NOT_PRESENT](#F-CSLibrary-Constants-Result-RADIO_NOT_PRESENT 'CSLibrary.Constants.Result.RADIO_NOT_PRESENT')
  - [RADIO_NOT_RESPONDING](#F-CSLibrary-Constants-Result-RADIO_NOT_RESPONDING 'CSLibrary.Constants.Result.RADIO_NOT_RESPONDING')
  - [RECEIVE_OVERFLOW](#F-CSLibrary-Constants-Result-RECEIVE_OVERFLOW 'CSLibrary.Constants.Result.RECEIVE_OVERFLOW')
  - [SYSTEM_CATCH_EXCEPTION](#F-CSLibrary-Constants-Result-SYSTEM_CATCH_EXCEPTION 'CSLibrary.Constants.Result.SYSTEM_CATCH_EXCEPTION')
  - [THREAD_ERROR](#F-CSLibrary-Constants-Result-THREAD_ERROR 'CSLibrary.Constants.Result.THREAD_ERROR')
  - [UNDER_CONSTRUCTION](#F-CSLibrary-Constants-Result-UNDER_CONSTRUCTION 'CSLibrary.Constants.Result.UNDER_CONSTRUCTION')
  - [UNKNOWN_OPERATION](#F-CSLibrary-Constants-Result-UNKNOWN_OPERATION 'CSLibrary.Constants.Result.UNKNOWN_OPERATION')
  - [BUILD_ASSIGN_BUFFER_FAIL](#F-CSLibrary-Net-Result-BUILD_ASSIGN_BUFFER_FAIL 'CSLibrary.Net.Result.BUILD_ASSIGN_BUFFER_FAIL')
  - [DATA_NOT_FOUND](#F-CSLibrary-Net-Result-DATA_NOT_FOUND 'CSLibrary.Net.Result.DATA_NOT_FOUND')
  - [FAIL](#F-CSLibrary-Net-Result-FAIL 'CSLibrary.Net.Result.FAIL')
  - [INVALID_PARAMETER](#F-CSLibrary-Net-Result-INVALID_PARAMETER 'CSLibrary.Net.Result.INVALID_PARAMETER')
  - [NO_CHANGED](#F-CSLibrary-Net-Result-NO_CHANGED 'CSLibrary.Net.Result.NO_CHANGED')
  - [OK](#F-CSLibrary-Net-Result-OK 'CSLibrary.Net.Result.OK')
  - [OPERATION_BUSY](#F-CSLibrary-Net-Result-OPERATION_BUSY 'CSLibrary.Net.Result.OPERATION_BUSY')
  - [SEND_ASSIGN_FAIL](#F-CSLibrary-Net-Result-SEND_ASSIGN_FAIL 'CSLibrary.Net.Result.SEND_ASSIGN_FAIL')
  - [UNKNOWN](#F-CSLibrary-Net-Result-UNKNOWN 'CSLibrary.Net.Result.UNKNOWN')
- [ResultArgs](#T-CSLibrary-Net-ResultArgs 'CSLibrary.Net.ResultArgs')
  - [#ctor(Result)](#M-CSLibrary-Net-ResultArgs-#ctor-CSLibrary-Net-AssignResult- 'CSLibrary.Net.ResultArgs.#ctor(CSLibrary.Net.AssignResult)')
  - [Result](#P-CSLibrary-Net-ResultArgs-Result 'CSLibrary.Net.ResultArgs.Result')
- [S_DATA](#T-CSLibrary-Structures-S_DATA 'CSLibrary.Structures.S_DATA')
  - [#ctor()](#M-CSLibrary-Structures-S_DATA-#ctor 'CSLibrary.Structures.S_DATA.#ctor')
  - [#ctor(src)](#M-CSLibrary-Structures-S_DATA-#ctor-System-String- 'CSLibrary.Structures.S_DATA.#ctor(System.String)')
  - [#ctor(src)](#M-CSLibrary-Structures-S_DATA-#ctor-System-Byte[]- 'CSLibrary.Structures.S_DATA.#ctor(System.Byte[])')
  - [#ctor(src)](#M-CSLibrary-Structures-S_DATA-#ctor-System-UInt16[]- 'CSLibrary.Structures.S_DATA.#ctor(System.UInt16[])')
  - [CompareTo(item)](#M-CSLibrary-Structures-S_DATA-CompareTo-System-Object- 'CSLibrary.Structures.S_DATA.CompareTo(System.Object)')
  - [GetLength()](#M-CSLibrary-Structures-S_DATA-GetLength 'CSLibrary.Structures.S_DATA.GetLength')
  - [ToBytes()](#M-CSLibrary-Structures-S_DATA-ToBytes 'CSLibrary.Structures.S_DATA.ToBytes')
  - [ToShorts()](#M-CSLibrary-Structures-S_DATA-ToShorts 'CSLibrary.Structures.S_DATA.ToShorts')
  - [ToString()](#M-CSLibrary-Structures-S_DATA-ToString 'CSLibrary.Structures.S_DATA.ToString')
  - [ToUshorts()](#M-CSLibrary-Structures-S_DATA-ToUshorts 'CSLibrary.Structures.S_DATA.ToUshorts')
- [S_EPC](#T-CSLibrary-Structures-S_EPC 'CSLibrary.Structures.S_EPC')
  - [#ctor()](#M-CSLibrary-Structures-S_EPC-#ctor 'CSLibrary.Structures.S_EPC.#ctor')
  - [#ctor(epc)](#M-CSLibrary-Structures-S_EPC-#ctor-System-String- 'CSLibrary.Structures.S_EPC.#ctor(System.String)')
  - [#ctor(epc)](#M-CSLibrary-Structures-S_EPC-#ctor-System-UInt16[]- 'CSLibrary.Structures.S_EPC.#ctor(System.UInt16[])')
  - [#ctor(epc,count)](#M-CSLibrary-Structures-S_EPC-#ctor-System-UInt16[],System-Int32- 'CSLibrary.Structures.S_EPC.#ctor(System.UInt16[],System.Int32)')
  - [#ctor(epc)](#M-CSLibrary-Structures-S_EPC-#ctor-System-Byte[]- 'CSLibrary.Structures.S_EPC.#ctor(System.Byte[])')
  - [CompareTo(item)](#M-CSLibrary-Structures-S_EPC-CompareTo-System-Object- 'CSLibrary.Structures.S_EPC.CompareTo(System.Object)')
  - [GetLength()](#M-CSLibrary-Structures-S_EPC-GetLength 'CSLibrary.Structures.S_EPC.GetLength')
  - [ToBytes()](#M-CSLibrary-Structures-S_EPC-ToBytes 'CSLibrary.Structures.S_EPC.ToBytes')
  - [ToShorts()](#M-CSLibrary-Structures-S_EPC-ToShorts 'CSLibrary.Structures.S_EPC.ToShorts')
  - [ToString()](#M-CSLibrary-Structures-S_EPC-ToString 'CSLibrary.Structures.S_EPC.ToString')
  - [ToUshorts()](#M-CSLibrary-Structures-S_EPC-ToUshorts 'CSLibrary.Structures.S_EPC.ToUshorts')
- [S_MASK](#T-CSLibrary-Structures-S_MASK 'CSLibrary.Structures.S_MASK')
  - [#ctor(mask)](#M-CSLibrary-Structures-S_MASK-#ctor-System-String- 'CSLibrary.Structures.S_MASK.#ctor(System.String)')
  - [#ctor(mask)](#M-CSLibrary-Structures-S_MASK-#ctor-System-Byte[]- 'CSLibrary.Structures.S_MASK.#ctor(System.Byte[])')
  - [#ctor(mask)](#M-CSLibrary-Structures-S_MASK-#ctor-System-UInt16[]- 'CSLibrary.Structures.S_MASK.#ctor(System.UInt16[])')
  - [#ctor(mask,count)](#M-CSLibrary-Structures-S_MASK-#ctor-System-Byte[],System-UInt32- 'CSLibrary.Structures.S_MASK.#ctor(System.Byte[],System.UInt32)')
  - [m_mask](#F-CSLibrary-Structures-S_MASK-m_mask 'CSLibrary.Structures.S_MASK.m_mask')
  - [Length](#P-CSLibrary-Structures-S_MASK-Length 'CSLibrary.Structures.S_MASK.Length')
  - [CompareTo(item)](#M-CSLibrary-Structures-S_MASK-CompareTo-System-Object- 'CSLibrary.Structures.S_MASK.CompareTo(System.Object)')
  - [GetLength()](#M-CSLibrary-Structures-S_MASK-GetLength 'CSLibrary.Structures.S_MASK.GetLength')
  - [ToBytes()](#M-CSLibrary-Structures-S_MASK-ToBytes 'CSLibrary.Structures.S_MASK.ToBytes')
  - [ToShorts()](#M-CSLibrary-Structures-S_MASK-ToShorts 'CSLibrary.Structures.S_MASK.ToShorts')
  - [ToString()](#M-CSLibrary-Structures-S_MASK-ToString 'CSLibrary.Structures.S_MASK.ToString')
  - [ToUshorts()](#M-CSLibrary-Structures-S_MASK-ToUshorts 'CSLibrary.Structures.S_MASK.ToUshorts')
  - [op_Implicit()](#M-CSLibrary-Structures-S_MASK-op_Implicit-CSLibrary-Structures-S_MASK-~System-String 'CSLibrary.Structures.S_MASK.op_Implicit(CSLibrary.Structures.S_MASK)~System.String')
  - [op_Implicit()](#M-CSLibrary-Structures-S_MASK-op_Implicit-CSLibrary-Structures-S_MASK-~System-UInt16[] 'CSLibrary.Structures.S_MASK.op_Implicit(CSLibrary.Structures.S_MASK)~System.UInt16[]')
  - [op_Implicit()](#M-CSLibrary-Structures-S_MASK-op_Implicit-System-UInt16[]-~CSLibrary-Structures-S_MASK 'CSLibrary.Structures.S_MASK.op_Implicit(System.UInt16[])~CSLibrary.Structures.S_MASK')
- [S_PC](#T-CSLibrary-Structures-S_PC 'CSLibrary.Structures.S_PC')
  - [#ctor()](#M-CSLibrary-Structures-S_PC-#ctor 'CSLibrary.Structures.S_PC.#ctor')
  - [#ctor(pc)](#M-CSLibrary-Structures-S_PC-#ctor-System-String- 'CSLibrary.Structures.S_PC.#ctor(System.String)')
  - [#ctor(pc)](#M-CSLibrary-Structures-S_PC-#ctor-System-UInt16- 'CSLibrary.Structures.S_PC.#ctor(System.UInt16)')
  - [EPCLength](#P-CSLibrary-Structures-S_PC-EPCLength 'CSLibrary.Structures.S_PC.EPCLength')
  - [UMI](#P-CSLibrary-Structures-S_PC-UMI 'CSLibrary.Structures.S_PC.UMI')
  - [XI](#P-CSLibrary-Structures-S_PC-XI 'CSLibrary.Structures.S_PC.XI')
  - [CompareTo(item)](#M-CSLibrary-Structures-S_PC-CompareTo-System-Object- 'CSLibrary.Structures.S_PC.CompareTo(System.Object)')
  - [GetLength()](#M-CSLibrary-Structures-S_PC-GetLength 'CSLibrary.Structures.S_PC.GetLength')
  - [ToBytes()](#M-CSLibrary-Structures-S_PC-ToBytes 'CSLibrary.Structures.S_PC.ToBytes')
  - [ToShorts()](#M-CSLibrary-Structures-S_PC-ToShorts 'CSLibrary.Structures.S_PC.ToShorts')
  - [ToString()](#M-CSLibrary-Structures-S_PC-ToString 'CSLibrary.Structures.S_PC.ToString')
  - [ToUshorts()](#M-CSLibrary-Structures-S_PC-ToUshorts 'CSLibrary.Structures.S_PC.ToUshorts')
- [S_PWD](#T-CSLibrary-Structures-S_PWD 'CSLibrary.Structures.S_PWD')
  - [#ctor()](#M-CSLibrary-Structures-S_PWD-#ctor 'CSLibrary.Structures.S_PWD.#ctor')
  - [#ctor(data)](#M-CSLibrary-Structures-S_PWD-#ctor-System-String- 'CSLibrary.Structures.S_PWD.#ctor(System.String)')
  - [#ctor(pwd)](#M-CSLibrary-Structures-S_PWD-#ctor-System-UInt32- 'CSLibrary.Structures.S_PWD.#ctor(System.UInt32)')
  - [m_pwd](#P-CSLibrary-Structures-S_PWD-m_pwd 'CSLibrary.Structures.S_PWD.m_pwd')
  - [CompareTo(item)](#M-CSLibrary-Structures-S_PWD-CompareTo-System-Object- 'CSLibrary.Structures.S_PWD.CompareTo(System.Object)')
  - [GetLength()](#M-CSLibrary-Structures-S_PWD-GetLength 'CSLibrary.Structures.S_PWD.GetLength')
  - [ToBytes()](#M-CSLibrary-Structures-S_PWD-ToBytes 'CSLibrary.Structures.S_PWD.ToBytes')
  - [ToShorts()](#M-CSLibrary-Structures-S_PWD-ToShorts 'CSLibrary.Structures.S_PWD.ToShorts')
  - [ToString()](#M-CSLibrary-Structures-S_PWD-ToString 'CSLibrary.Structures.S_PWD.ToString')
  - [ToUshorts()](#M-CSLibrary-Structures-S_PWD-ToUshorts 'CSLibrary.Structures.S_PWD.ToUshorts')
- [S_TID](#T-CSLibrary-Structures-S_TID 'CSLibrary.Structures.S_TID')
  - [#ctor()](#M-CSLibrary-Structures-S_TID-#ctor 'CSLibrary.Structures.S_TID.#ctor')
  - [#ctor(tid)](#M-CSLibrary-Structures-S_TID-#ctor-System-String- 'CSLibrary.Structures.S_TID.#ctor(System.String)')
  - [#ctor(tid)](#M-CSLibrary-Structures-S_TID-#ctor-System-UInt16[]- 'CSLibrary.Structures.S_TID.#ctor(System.UInt16[])')
  - [#ctor(tid,count)](#M-CSLibrary-Structures-S_TID-#ctor-System-UInt16[],System-Int32- 'CSLibrary.Structures.S_TID.#ctor(System.UInt16[],System.Int32)')
  - [GetACID](#P-CSLibrary-Structures-S_TID-GetACID 'CSLibrary.Structures.S_TID.GetACID')
  - [GetEpcID](#P-CSLibrary-Structures-S_TID-GetEpcID 'CSLibrary.Structures.S_TID.GetEpcID')
  - [GetIsoID](#P-CSLibrary-Structures-S_TID-GetIsoID 'CSLibrary.Structures.S_TID.GetIsoID')
  - [CompareTo(item)](#M-CSLibrary-Structures-S_TID-CompareTo-System-Object- 'CSLibrary.Structures.S_TID.CompareTo(System.Object)')
  - [GetLength()](#M-CSLibrary-Structures-S_TID-GetLength 'CSLibrary.Structures.S_TID.GetLength')
  - [ToBytes()](#M-CSLibrary-Structures-S_TID-ToBytes 'CSLibrary.Structures.S_TID.ToBytes')
  - [ToShorts()](#M-CSLibrary-Structures-S_TID-ToShorts 'CSLibrary.Structures.S_TID.ToShorts')
  - [ToString()](#M-CSLibrary-Structures-S_TID-ToString 'CSLibrary.Structures.S_TID.ToString')
  - [ToUshorts()](#M-CSLibrary-Structures-S_TID-ToUshorts 'CSLibrary.Structures.S_TID.ToUshorts')
- [S_XPC_W1](#T-CSLibrary-Structures-S_XPC_W1 'CSLibrary.Structures.S_XPC_W1')
  - [#ctor()](#M-CSLibrary-Structures-S_XPC_W1-#ctor 'CSLibrary.Structures.S_XPC_W1.#ctor')
  - [#ctor(pc)](#M-CSLibrary-Structures-S_XPC_W1-#ctor-System-String- 'CSLibrary.Structures.S_XPC_W1.#ctor(System.String)')
  - [#ctor(pc)](#M-CSLibrary-Structures-S_XPC_W1-#ctor-System-UInt16- 'CSLibrary.Structures.S_XPC_W1.#ctor(System.UInt16)')
  - [XEB](#P-CSLibrary-Structures-S_XPC_W1-XEB 'CSLibrary.Structures.S_XPC_W1.XEB')
  - [CompareTo(item)](#M-CSLibrary-Structures-S_XPC_W1-CompareTo-System-Object- 'CSLibrary.Structures.S_XPC_W1.CompareTo(System.Object)')
  - [GetLength()](#M-CSLibrary-Structures-S_XPC_W1-GetLength 'CSLibrary.Structures.S_XPC_W1.GetLength')
  - [ToBytes()](#M-CSLibrary-Structures-S_XPC_W1-ToBytes 'CSLibrary.Structures.S_XPC_W1.ToBytes')
  - [ToShorts()](#M-CSLibrary-Structures-S_XPC_W1-ToShorts 'CSLibrary.Structures.S_XPC_W1.ToShorts')
  - [ToString()](#M-CSLibrary-Structures-S_XPC_W1-ToString 'CSLibrary.Structures.S_XPC_W1.ToString')
  - [ToUshorts()](#M-CSLibrary-Structures-S_XPC_W1-ToUshorts 'CSLibrary.Structures.S_XPC_W1.ToUshorts')
- [S_XPC_W2](#T-CSLibrary-Structures-S_XPC_W2 'CSLibrary.Structures.S_XPC_W2')
  - [#ctor()](#M-CSLibrary-Structures-S_XPC_W2-#ctor 'CSLibrary.Structures.S_XPC_W2.#ctor')
  - [#ctor(pc)](#M-CSLibrary-Structures-S_XPC_W2-#ctor-System-String- 'CSLibrary.Structures.S_XPC_W2.#ctor(System.String)')
  - [#ctor(pc)](#M-CSLibrary-Structures-S_XPC_W2-#ctor-System-UInt16- 'CSLibrary.Structures.S_XPC_W2.#ctor(System.UInt16)')
  - [CompareTo(item)](#M-CSLibrary-Structures-S_XPC_W2-CompareTo-System-Object- 'CSLibrary.Structures.S_XPC_W2.CompareTo(System.Object)')
  - [GetLength()](#M-CSLibrary-Structures-S_XPC_W2-GetLength 'CSLibrary.Structures.S_XPC_W2.GetLength')
  - [ToBytes()](#M-CSLibrary-Structures-S_XPC_W2-ToBytes 'CSLibrary.Structures.S_XPC_W2.ToBytes')
  - [ToShorts()](#M-CSLibrary-Structures-S_XPC_W2-ToShorts 'CSLibrary.Structures.S_XPC_W2.ToShorts')
  - [ToString()](#M-CSLibrary-Structures-S_XPC_W2-ToString 'CSLibrary.Structures.S_XPC_W2.ToString')
  - [ToUshorts()](#M-CSLibrary-Structures-S_XPC_W2-ToUshorts 'CSLibrary.Structures.S_XPC_W2.ToUshorts')
- [SelectAction](#T-CSLibrary-Structures-SelectAction 'CSLibrary.Structures.SelectAction')
  - [#ctor()](#M-CSLibrary-Structures-SelectAction-#ctor 'CSLibrary.Structures.SelectAction.#ctor')
  - [#ctor(target,action,enableTruncate)](#M-CSLibrary-Structures-SelectAction-#ctor-CSLibrary-Constants-Target,CSLibrary-Constants-Action,System-Int32- 'CSLibrary.Structures.SelectAction.#ctor(CSLibrary.Constants.Target,CSLibrary.Constants.Action,System.Int32)')
  - [action](#F-CSLibrary-Structures-SelectAction-action 'CSLibrary.Structures.SelectAction.action')
  - [enableTruncate](#F-CSLibrary-Structures-SelectAction-enableTruncate 'CSLibrary.Structures.SelectAction.enableTruncate')
  - [target](#F-CSLibrary-Structures-SelectAction-target 'CSLibrary.Structures.SelectAction.target')
- [SelectCriteria](#T-CSLibrary-Structures-SelectCriteria 'CSLibrary.Structures.SelectCriteria')
  - [#ctor()](#M-CSLibrary-Structures-SelectCriteria-#ctor 'CSLibrary.Structures.SelectCriteria.#ctor')
  - [countCriteria](#F-CSLibrary-Structures-SelectCriteria-countCriteria 'CSLibrary.Structures.SelectCriteria.countCriteria')
  - [pCriteria](#F-CSLibrary-Structures-SelectCriteria-pCriteria 'CSLibrary.Structures.SelectCriteria.pCriteria')
- [SelectCriterion](#T-CSLibrary-Structures-SelectCriterion 'CSLibrary.Structures.SelectCriterion')
  - [#ctor()](#M-CSLibrary-Structures-SelectCriterion-#ctor 'CSLibrary.Structures.SelectCriterion.#ctor')
  - [action](#F-CSLibrary-Structures-SelectCriterion-action 'CSLibrary.Structures.SelectCriterion.action')
  - [mask](#F-CSLibrary-Structures-SelectCriterion-mask 'CSLibrary.Structures.SelectCriterion.mask')
- [SelectFlags](#T-CSLibrary-Constants-SelectFlags 'CSLibrary.Constants.SelectFlags')
  - [DISABLE_INVENTORY](#F-CSLibrary-Constants-SelectFlags-DISABLE_INVENTORY 'CSLibrary.Constants.SelectFlags.DISABLE_INVENTORY')
  - [POSTMATCH](#F-CSLibrary-Constants-SelectFlags-POSTMATCH 'CSLibrary.Constants.SelectFlags.POSTMATCH')
  - [POST_MATCH](#F-CSLibrary-Constants-SelectFlags-POST_MATCH 'CSLibrary.Constants.SelectFlags.POST_MATCH')
  - [READ1BANK](#F-CSLibrary-Constants-SelectFlags-READ1BANK 'CSLibrary.Constants.SelectFlags.READ1BANK')
  - [READ2BANK](#F-CSLibrary-Constants-SelectFlags-READ2BANK 'CSLibrary.Constants.SelectFlags.READ2BANK')
  - [SELECT](#F-CSLibrary-Constants-SelectFlags-SELECT 'CSLibrary.Constants.SelectFlags.SELECT')
  - [UNKNOWN](#F-CSLibrary-Constants-SelectFlags-UNKNOWN 'CSLibrary.Constants.SelectFlags.UNKNOWN')
  - [ZERO](#F-CSLibrary-Constants-SelectFlags-ZERO 'CSLibrary.Constants.SelectFlags.ZERO')
- [SelectMask](#T-CSLibrary-Structures-SelectMask 'CSLibrary.Structures.SelectMask')
  - [#ctor()](#M-CSLibrary-Structures-SelectMask-#ctor 'CSLibrary.Structures.SelectMask.#ctor')
  - [#ctor(bank,offset,count,epc)](#M-CSLibrary-Structures-SelectMask-#ctor-CSLibrary-Constants-MemoryBank,System-UInt32,System-UInt32,System-Byte[]- 'CSLibrary.Structures.SelectMask.#ctor(CSLibrary.Constants.MemoryBank,System.UInt32,System.UInt32,System.Byte[])')
  - [bank](#F-CSLibrary-Structures-SelectMask-bank 'CSLibrary.Structures.SelectMask.bank')
  - [count](#F-CSLibrary-Structures-SelectMask-count 'CSLibrary.Structures.SelectMask.count')
  - [m_mask](#F-CSLibrary-Structures-SelectMask-m_mask 'CSLibrary.Structures.SelectMask.m_mask')
  - [offset](#F-CSLibrary-Structures-SelectMask-offset 'CSLibrary.Structures.SelectMask.offset')
  - [mask](#P-CSLibrary-Structures-SelectMask-mask 'CSLibrary.Structures.SelectMask.mask')
- [SelectMaskFlags](#T-CSLibrary-Constants-SelectMaskFlags 'CSLibrary.Constants.SelectMaskFlags')
  - [DISABLE_ALL](#F-CSLibrary-Constants-SelectMaskFlags-DISABLE_ALL 'CSLibrary.Constants.SelectMaskFlags.DISABLE_ALL')
  - [ENABLE_ALL](#F-CSLibrary-Constants-SelectMaskFlags-ENABLE_ALL 'CSLibrary.Constants.SelectMaskFlags.ENABLE_ALL')
  - [ENABLE_NON_MATCH](#F-CSLibrary-Constants-SelectMaskFlags-ENABLE_NON_MATCH 'CSLibrary.Constants.SelectMaskFlags.ENABLE_NON_MATCH')
  - [ENABLE_PC_MASK](#F-CSLibrary-Constants-SelectMaskFlags-ENABLE_PC_MASK 'CSLibrary.Constants.SelectMaskFlags.ENABLE_PC_MASK')
  - [ENABLE_TOGGLE](#F-CSLibrary-Constants-SelectMaskFlags-ENABLE_TOGGLE 'CSLibrary.Constants.SelectMaskFlags.ENABLE_TOGGLE')
- [Selected](#T-CSLibrary-Constants-Selected 'CSLibrary.Constants.Selected')
  - [ALL](#F-CSLibrary-Constants-Selected-ALL 'CSLibrary.Constants.Selected.ALL')
  - [ASSERTED](#F-CSLibrary-Constants-Selected-ASSERTED 'CSLibrary.Constants.Selected.ASSERTED')
  - [DEASSERTED](#F-CSLibrary-Constants-Selected-DEASSERTED 'CSLibrary.Constants.Selected.DEASSERTED')
  - [UNKNOWN](#F-CSLibrary-Constants-Selected-UNKNOWN 'CSLibrary.Constants.Selected.UNKNOWN')
- [Sensor](#T-CSLibrary-Structures-Sensor 'CSLibrary.Structures.Sensor')
- [Session](#T-CSLibrary-Constants-Session 'CSLibrary.Constants.Session')
  - [S0](#F-CSLibrary-Constants-Session-S0 'CSLibrary.Constants.Session.S0')
  - [S1](#F-CSLibrary-Constants-Session-S1 'CSLibrary.Constants.Session.S1')
  - [S2](#F-CSLibrary-Constants-Session-S2 'CSLibrary.Constants.Session.S2')
  - [S3](#F-CSLibrary-Constants-Session-S3 'CSLibrary.Constants.Session.S3')
  - [UNKNOWN](#F-CSLibrary-Constants-Session-UNKNOWN 'CSLibrary.Constants.Session.UNKNOWN')
- [SessionTarget](#T-CSLibrary-Constants-SessionTarget 'CSLibrary.Constants.SessionTarget')
  - [A](#F-CSLibrary-Constants-SessionTarget-A 'CSLibrary.Constants.SessionTarget.A')
  - [B](#F-CSLibrary-Constants-SessionTarget-B 'CSLibrary.Constants.SessionTarget.B')
  - [UNKNOWN](#F-CSLibrary-Constants-SessionTarget-UNKNOWN 'CSLibrary.Constants.SessionTarget.UNKNOWN')
- [SingulationAlgorithm](#T-CSLibrary-Constants-SingulationAlgorithm 'CSLibrary.Constants.SingulationAlgorithm')
  - [DYNAMICQ](#F-CSLibrary-Constants-SingulationAlgorithm-DYNAMICQ 'CSLibrary.Constants.SingulationAlgorithm.DYNAMICQ')
  - [FIXEDQ](#F-CSLibrary-Constants-SingulationAlgorithm-FIXEDQ 'CSLibrary.Constants.SingulationAlgorithm.FIXEDQ')
  - [UNKNOWN](#F-CSLibrary-Constants-SingulationAlgorithm-UNKNOWN 'CSLibrary.Constants.SingulationAlgorithm.UNKNOWN')
- [SingulationAlgorithmParms](#T-CSLibrary-Structures-SingulationAlgorithmParms 'CSLibrary.Structures.SingulationAlgorithmParms')
  - [#ctor()](#M-CSLibrary-Structures-SingulationAlgorithmParms-#ctor 'CSLibrary.Structures.SingulationAlgorithmParms.#ctor')
  - [length_](#F-CSLibrary-Structures-SingulationAlgorithmParms-length_ 'CSLibrary.Structures.SingulationAlgorithmParms.length_')
  - [length](#P-CSLibrary-Structures-SingulationAlgorithmParms-length 'CSLibrary.Structures.SingulationAlgorithmParms.length')
- [SingulationCriteria](#T-CSLibrary-Structures-SingulationCriteria 'CSLibrary.Structures.SingulationCriteria')
  - [#ctor()](#M-CSLibrary-Structures-SingulationCriteria-#ctor 'CSLibrary.Structures.SingulationCriteria.#ctor')
  - [countCriteria](#F-CSLibrary-Structures-SingulationCriteria-countCriteria 'CSLibrary.Structures.SingulationCriteria.countCriteria')
  - [pCriteria](#F-CSLibrary-Structures-SingulationCriteria-pCriteria 'CSLibrary.Structures.SingulationCriteria.pCriteria')
- [SingulationCriterion](#T-CSLibrary-Structures-SingulationCriterion 'CSLibrary.Structures.SingulationCriterion')
  - [#ctor()](#M-CSLibrary-Structures-SingulationCriterion-#ctor 'CSLibrary.Structures.SingulationCriterion.#ctor')
  - [mask](#F-CSLibrary-Structures-SingulationCriterion-mask 'CSLibrary.Structures.SingulationCriterion.mask')
  - [match](#F-CSLibrary-Structures-SingulationCriterion-match 'CSLibrary.Structures.SingulationCriterion.match')
- [SingulationMask](#T-CSLibrary-Structures-SingulationMask 'CSLibrary.Structures.SingulationMask')
  - [#ctor()](#M-CSLibrary-Structures-SingulationMask-#ctor 'CSLibrary.Structures.SingulationMask.#ctor')
  - [#ctor(offset,count,mask)](#M-CSLibrary-Structures-SingulationMask-#ctor-System-UInt32,System-UInt32,System-Byte[]- 'CSLibrary.Structures.SingulationMask.#ctor(System.UInt32,System.UInt32,System.Byte[])')
  - [count](#F-CSLibrary-Structures-SingulationMask-count 'CSLibrary.Structures.SingulationMask.count')
  - [m_mask](#F-CSLibrary-Structures-SingulationMask-m_mask 'CSLibrary.Structures.SingulationMask.m_mask')
  - [offset](#F-CSLibrary-Structures-SingulationMask-offset 'CSLibrary.Structures.SingulationMask.offset')
  - [mask](#P-CSLibrary-Structures-SingulationMask-mask 'CSLibrary.Structures.SingulationMask.mask')
- [Sound](#T-CSLibrary-Tools-Sound 'CSLibrary.Tools.Sound')
  - [Beep(frequency,duration)](#M-CSLibrary-Tools-Sound-Beep-System-UInt32,System-UInt32- 'CSLibrary.Tools.Sound.Beep(System.UInt32,System.UInt32)')
- [StorageRule](#T-CSLibrary-Structures-StorageRule 'CSLibrary.Structures.StorageRule')
  - [Normal](#F-CSLibrary-Structures-StorageRule-Normal 'CSLibrary.Structures.StorageRule.Normal')
  - [Rolling](#F-CSLibrary-Structures-StorageRule-Rolling 'CSLibrary.Structures.StorageRule.Rolling')
- [TAG_ACCESS_PKT](#T-CSLibrary-Structures-TAG_ACCESS_PKT 'CSLibrary.Structures.TAG_ACCESS_PKT')
  - [#ctor(flags,cmd,ms,errorCode,data)](#M-CSLibrary-Structures-TAG_ACCESS_PKT-#ctor-System-Byte,CSLibrary-Constants-RFID_18K6C,System-UInt32,CSLibrary-Constants-TAG_BACKSCATTERED_ERROR,System-Byte[]- 'CSLibrary.Structures.TAG_ACCESS_PKT.#ctor(System.Byte,CSLibrary.Constants.RFID_18K6C,System.UInt32,CSLibrary.Constants.TAG_BACKSCATTERED_ERROR,System.Byte[])')
  - [cmd](#F-CSLibrary-Structures-TAG_ACCESS_PKT-cmd 'CSLibrary.Structures.TAG_ACCESS_PKT.cmd')
  - [data](#F-CSLibrary-Structures-TAG_ACCESS_PKT-data 'CSLibrary.Structures.TAG_ACCESS_PKT.data')
  - [errorCode](#F-CSLibrary-Structures-TAG_ACCESS_PKT-errorCode 'CSLibrary.Structures.TAG_ACCESS_PKT.errorCode')
  - [ms_ctr](#F-CSLibrary-Structures-TAG_ACCESS_PKT-ms_ctr 'CSLibrary.Structures.TAG_ACCESS_PKT.ms_ctr')
  - [IsAckTimeout](#P-CSLibrary-Structures-TAG_ACCESS_PKT-IsAckTimeout 'CSLibrary.Structures.TAG_ACCESS_PKT.IsAckTimeout')
  - [IsBackscatterError](#P-CSLibrary-Structures-TAG_ACCESS_PKT-IsBackscatterError 'CSLibrary.Structures.TAG_ACCESS_PKT.IsBackscatterError')
  - [IsCRCInvalid](#P-CSLibrary-Structures-TAG_ACCESS_PKT-IsCRCInvalid 'CSLibrary.Structures.TAG_ACCESS_PKT.IsCRCInvalid')
  - [IsError](#P-CSLibrary-Structures-TAG_ACCESS_PKT-IsError 'CSLibrary.Structures.TAG_ACCESS_PKT.IsError')
- [TAG_BACKSCATTERED_ERROR](#T-CSLibrary-Constants-TAG_BACKSCATTERED_ERROR 'CSLibrary.Constants.TAG_BACKSCATTERED_ERROR')
  - [INSUFFICIENT_POWER](#F-CSLibrary-Constants-TAG_BACKSCATTERED_ERROR-INSUFFICIENT_POWER 'CSLibrary.Constants.TAG_BACKSCATTERED_ERROR.INSUFFICIENT_POWER')
  - [MEMORY_LOCKED](#F-CSLibrary-Constants-TAG_BACKSCATTERED_ERROR-MEMORY_LOCKED 'CSLibrary.Constants.TAG_BACKSCATTERED_ERROR.MEMORY_LOCKED')
  - [MEMORY_OVERRUN](#F-CSLibrary-Constants-TAG_BACKSCATTERED_ERROR-MEMORY_OVERRUN 'CSLibrary.Constants.TAG_BACKSCATTERED_ERROR.MEMORY_OVERRUN')
  - [NON_SPECIFIC_ERROR](#F-CSLibrary-Constants-TAG_BACKSCATTERED_ERROR-NON_SPECIFIC_ERROR 'CSLibrary.Constants.TAG_BACKSCATTERED_ERROR.NON_SPECIFIC_ERROR')
  - [OTHER_ERROR](#F-CSLibrary-Constants-TAG_BACKSCATTERED_ERROR-OTHER_ERROR 'CSLibrary.Constants.TAG_BACKSCATTERED_ERROR.OTHER_ERROR')
- [TAG_BLOCK_WRITE_PARMS](#T-CSLibrary-Structures-TAG_BLOCK_WRITE_PARMS 'CSLibrary.Structures.TAG_BLOCK_WRITE_PARMS')
  - [accessPassword](#F-CSLibrary-Structures-TAG_BLOCK_WRITE_PARMS-accessPassword 'CSLibrary.Structures.TAG_BLOCK_WRITE_PARMS.accessPassword')
  - [bank](#F-CSLibrary-Structures-TAG_BLOCK_WRITE_PARMS-bank 'CSLibrary.Structures.TAG_BLOCK_WRITE_PARMS.bank')
  - [count](#F-CSLibrary-Structures-TAG_BLOCK_WRITE_PARMS-count 'CSLibrary.Structures.TAG_BLOCK_WRITE_PARMS.count')
  - [flags](#F-CSLibrary-Structures-TAG_BLOCK_WRITE_PARMS-flags 'CSLibrary.Structures.TAG_BLOCK_WRITE_PARMS.flags')
  - [offset](#F-CSLibrary-Structures-TAG_BLOCK_WRITE_PARMS-offset 'CSLibrary.Structures.TAG_BLOCK_WRITE_PARMS.offset')
  - [pData](#F-CSLibrary-Structures-TAG_BLOCK_WRITE_PARMS-pData 'CSLibrary.Structures.TAG_BLOCK_WRITE_PARMS.pData')
  - [retryCount](#F-CSLibrary-Structures-TAG_BLOCK_WRITE_PARMS-retryCount 'CSLibrary.Structures.TAG_BLOCK_WRITE_PARMS.retryCount')
- [TFTPException](#T-CSLibrary-Net-TFTPException 'CSLibrary.Net.TFTPException')
  - [#ctor(errCode,errMsg)](#M-CSLibrary-Net-TFTPException-#ctor-System-Int32,System-String- 'CSLibrary.Net.TFTPException.#ctor(System.Int32,System.String)')
  - [ErrorCode](#F-CSLibrary-Net-TFTPException-ErrorCode 'CSLibrary.Net.TFTPException.ErrorCode')
  - [ErrorMessage](#F-CSLibrary-Net-TFTPException-ErrorMessage 'CSLibrary.Net.TFTPException.ErrorMessage')
  - [ToString()](#M-CSLibrary-Net-TFTPException-ToString 'CSLibrary.Net.TFTPException.ToString')
- [TagAccess](#T-CSLibrary-Constants-TagAccess 'CSLibrary.Constants.TagAccess')
  - [BLOCKWRITE](#F-CSLibrary-Constants-TagAccess-BLOCKWRITE 'CSLibrary.Constants.TagAccess.BLOCKWRITE')
  - [CHANGEEAS](#F-CSLibrary-Constants-TagAccess-CHANGEEAS 'CSLibrary.Constants.TagAccess.CHANGEEAS')
  - [ERASE](#F-CSLibrary-Constants-TagAccess-ERASE 'CSLibrary.Constants.TagAccess.ERASE')
  - [KILL](#F-CSLibrary-Constants-TagAccess-KILL 'CSLibrary.Constants.TagAccess.KILL')
  - [LOCK](#F-CSLibrary-Constants-TagAccess-LOCK 'CSLibrary.Constants.TagAccess.LOCK')
  - [READ](#F-CSLibrary-Constants-TagAccess-READ 'CSLibrary.Constants.TagAccess.READ')
  - [UNKNOWN](#F-CSLibrary-Constants-TagAccess-UNKNOWN 'CSLibrary.Constants.TagAccess.UNKNOWN')
  - [WRITE](#F-CSLibrary-Constants-TagAccess-WRITE 'CSLibrary.Constants.TagAccess.WRITE')
- [TagAccessCallbackDelegate](#T-CSLibrary-Structures-TagAccessCallbackDelegate 'CSLibrary.Structures.TagAccessCallbackDelegate')
- [TagBlockPermalockParms](#T-CSLibrary-Structures-TagBlockPermalockParms 'CSLibrary.Structures.TagBlockPermalockParms')
  - [#ctor()](#M-CSLibrary-Structures-TagBlockPermalockParms-#ctor 'CSLibrary.Structures.TagBlockPermalockParms.#ctor')
  - [accessPassword](#F-CSLibrary-Structures-TagBlockPermalockParms-accessPassword 'CSLibrary.Structures.TagBlockPermalockParms.accessPassword')
  - [count](#F-CSLibrary-Structures-TagBlockPermalockParms-count 'CSLibrary.Structures.TagBlockPermalockParms.count')
  - [flags](#F-CSLibrary-Structures-TagBlockPermalockParms-flags 'CSLibrary.Structures.TagBlockPermalockParms.flags')
  - [length](#F-CSLibrary-Structures-TagBlockPermalockParms-length 'CSLibrary.Structures.TagBlockPermalockParms.length')
  - [mask](#F-CSLibrary-Structures-TagBlockPermalockParms-mask 'CSLibrary.Structures.TagBlockPermalockParms.mask')
  - [offset](#F-CSLibrary-Structures-TagBlockPermalockParms-offset 'CSLibrary.Structures.TagBlockPermalockParms.offset')
  - [retryCount](#F-CSLibrary-Structures-TagBlockPermalockParms-retryCount 'CSLibrary.Structures.TagBlockPermalockParms.retryCount')
  - [setPermalock](#F-CSLibrary-Structures-TagBlockPermalockParms-setPermalock 'CSLibrary.Structures.TagBlockPermalockParms.setPermalock')
- [TagCallbackInfo](#T-CSLibrary-Structures-TagCallbackInfo 'CSLibrary.Structures.TagCallbackInfo')
  - [#ctor(index,rssi,count,antennaPort,pc,epc,ms_ctr,name)](#M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Int32,System-Single,System-UInt32,System-UInt32,System-Byte,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-UInt32,System-String- 'CSLibrary.Structures.TagCallbackInfo.#ctor(System.Int32,System.Single,System.UInt32,System.UInt32,System.Byte,CSLibrary.Structures.S_PC,CSLibrary.Structures.S_EPC,System.UInt32,System.String)')
  - [#ctor(index,rssi,count,antennaPort,freqChannel,pc,epc,ms_ctr,name)](#M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Int32,System-Single,System-UInt32,System-Byte,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-UInt16[],System-UInt16[],System-UInt32,System-UInt16,System-String- 'CSLibrary.Structures.TagCallbackInfo.#ctor(System.Int32,System.Single,System.UInt32,System.Byte,CSLibrary.Structures.S_PC,CSLibrary.Structures.S_EPC,System.UInt16[],System.UInt16[],System.UInt32,System.UInt16,System.String)')
  - [#ctor(index,rssi,count,antennaPort,freqChannel,pc,epc,ms_ctr,name)](#M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Int32,System-Single,System-UInt32,System-Byte,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_XPC_W1,CSLibrary-Structures-S_XPC_W2,CSLibrary-Structures-S_EPC,System-UInt16[],System-UInt16[],System-UInt32,System-UInt16,System-String- 'CSLibrary.Structures.TagCallbackInfo.#ctor(System.Int32,System.Single,System.UInt32,System.Byte,CSLibrary.Structures.S_PC,CSLibrary.Structures.S_XPC_W1,CSLibrary.Structures.S_XPC_W2,CSLibrary.Structures.S_EPC,System.UInt16[],System.UInt16[],System.UInt32,System.UInt16,System.String)')
  - [#ctor(index,rssi,count,antennaPort,pc,epc,name)](#M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Int32,System-Single,System-UInt32,System-UInt32,System-Byte,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-String- 'CSLibrary.Structures.TagCallbackInfo.#ctor(System.Int32,System.Single,System.UInt32,System.UInt32,System.Byte,CSLibrary.Structures.S_PC,CSLibrary.Structures.S_EPC,System.String)')
  - [#ctor(rssi,pc,epc,name)](#M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Single,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-String- 'CSLibrary.Structures.TagCallbackInfo.#ctor(System.Single,CSLibrary.Structures.S_PC,CSLibrary.Structures.S_EPC,System.String)')
  - [#ctor(index,pc,epc,name)](#M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Int32,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-String- 'CSLibrary.Structures.TagCallbackInfo.#ctor(System.Int32,CSLibrary.Structures.S_PC,CSLibrary.Structures.S_EPC,System.String)')
  - [#ctor(pc,epc,name)](#M-CSLibrary-Structures-TagCallbackInfo-#ctor-CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-String- 'CSLibrary.Structures.TagCallbackInfo.#ctor(CSLibrary.Structures.S_PC,CSLibrary.Structures.S_EPC,System.String)')
  - [#ctor(index,rssi,count,pc,xpc_w1,xpc_w2,epc,ms_ctr)](#M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Int32,System-Single,System-UInt32,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_XPC_W1,CSLibrary-Structures-S_XPC_W2,CSLibrary-Structures-S_EPC,System-UInt32- 'CSLibrary.Structures.TagCallbackInfo.#ctor(System.Int32,System.Single,System.UInt32,CSLibrary.Structures.S_PC,CSLibrary.Structures.S_XPC_W1,CSLibrary.Structures.S_XPC_W2,CSLibrary.Structures.S_EPC,System.UInt32)')
  - [#ctor(index,rssi,count,pc,epc,ms_ctr)](#M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Int32,System-Single,System-UInt32,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-UInt32- 'CSLibrary.Structures.TagCallbackInfo.#ctor(System.Int32,System.Single,System.UInt32,CSLibrary.Structures.S_PC,CSLibrary.Structures.S_EPC,System.UInt32)')
  - [#ctor(index,rssi,count,pc,epc)](#M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Int32,System-Single,System-UInt32,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC- 'CSLibrary.Structures.TagCallbackInfo.#ctor(System.Int32,System.Single,System.UInt32,CSLibrary.Structures.S_PC,CSLibrary.Structures.S_EPC)')
  - [#ctor(index,rssi,count,pc,epc)](#M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Int32,System-Single,System-UInt32,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-UInt16- 'CSLibrary.Structures.TagCallbackInfo.#ctor(System.Int32,System.Single,System.UInt32,CSLibrary.Structures.S_PC,CSLibrary.Structures.S_EPC,System.UInt16)')
  - [#ctor(rssi,pc,epc)](#M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Single,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-UInt32- 'CSLibrary.Structures.TagCallbackInfo.#ctor(System.Single,CSLibrary.Structures.S_PC,CSLibrary.Structures.S_EPC,System.UInt32)')
  - [#ctor(rssi,pc,epc)](#M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Single,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-UInt32,System-UInt16- 'CSLibrary.Structures.TagCallbackInfo.#ctor(System.Single,CSLibrary.Structures.S_PC,CSLibrary.Structures.S_EPC,System.UInt32,System.UInt16)')
  - [#ctor(rssi,pc,epc)](#M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Single,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC- 'CSLibrary.Structures.TagCallbackInfo.#ctor(System.Single,CSLibrary.Structures.S_PC,CSLibrary.Structures.S_EPC)')
  - [#ctor(crcInvalid,rssi,pc,epc,readerName)](#M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Boolean,System-Single,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-String- 'CSLibrary.Structures.TagCallbackInfo.#ctor(System.Boolean,System.Single,CSLibrary.Structures.S_PC,CSLibrary.Structures.S_EPC,System.String)')
  - [#ctor(crcInvalid,rssi,antennaPort,pc,epc,ms_ctr,readerName)](#M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Boolean,System-Single,System-UInt32,System-Byte,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-UInt32,System-UInt16,System-String- 'CSLibrary.Structures.TagCallbackInfo.#ctor(System.Boolean,System.Single,System.UInt32,System.Byte,CSLibrary.Structures.S_PC,CSLibrary.Structures.S_EPC,System.UInt32,System.UInt16,System.String)')
  - [#ctor(crcInvalid,rssi,antennaPort,pc,epc,ms_ctr,readerName)](#M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Boolean,System-Single,System-UInt32,System-Byte,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-UInt32,System-String- 'CSLibrary.Structures.TagCallbackInfo.#ctor(System.Boolean,System.Single,System.UInt32,System.Byte,CSLibrary.Structures.S_PC,CSLibrary.Structures.S_EPC,CSLibrary.Structures.S_PC,CSLibrary.Structures.S_EPC,System.UInt32,System.String)')
  - [#ctor(crcInvalid,rssi,antennaPort,pc,epc,readerName)](#M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Boolean,System-Single,System-UInt32,System-Byte,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-String- 'CSLibrary.Structures.TagCallbackInfo.#ctor(System.Boolean,System.Single,System.UInt32,System.Byte,CSLibrary.Structures.S_PC,CSLibrary.Structures.S_EPC,System.String)')
  - [#ctor(index,pc,epc)](#M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Int32,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC- 'CSLibrary.Structures.TagCallbackInfo.#ctor(System.Int32,CSLibrary.Structures.S_PC,CSLibrary.Structures.S_EPC)')
  - [#ctor(pc,epc)](#M-CSLibrary-Structures-TagCallbackInfo-#ctor-CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC- 'CSLibrary.Structures.TagCallbackInfo.#ctor(CSLibrary.Structures.S_PC,CSLibrary.Structures.S_EPC)')
  - [#ctor()](#M-CSLibrary-Structures-TagCallbackInfo-#ctor 'CSLibrary.Structures.TagCallbackInfo.#ctor')
  - [Bank1Data](#F-CSLibrary-Structures-TagCallbackInfo-Bank1Data 'CSLibrary.Structures.TagCallbackInfo.Bank1Data')
  - [Bank2Data](#F-CSLibrary-Structures-TagCallbackInfo-Bank2Data 'CSLibrary.Structures.TagCallbackInfo.Bank2Data')
  - [antennaPort](#F-CSLibrary-Structures-TagCallbackInfo-antennaPort 'CSLibrary.Structures.TagCallbackInfo.antennaPort')
  - [count](#F-CSLibrary-Structures-TagCallbackInfo-count 'CSLibrary.Structures.TagCallbackInfo.count')
  - [crc16](#F-CSLibrary-Structures-TagCallbackInfo-crc16 'CSLibrary.Structures.TagCallbackInfo.crc16')
  - [crcInvalid](#F-CSLibrary-Structures-TagCallbackInfo-crcInvalid 'CSLibrary.Structures.TagCallbackInfo.crcInvalid')
  - [epc](#F-CSLibrary-Structures-TagCallbackInfo-epc 'CSLibrary.Structures.TagCallbackInfo.epc')
  - [epcpublic](#F-CSLibrary-Structures-TagCallbackInfo-epcpublic 'CSLibrary.Structures.TagCallbackInfo.epcpublic')
  - [epcpublicstrlen](#F-CSLibrary-Structures-TagCallbackInfo-epcpublicstrlen 'CSLibrary.Structures.TagCallbackInfo.epcpublicstrlen')
  - [epcstrlen](#F-CSLibrary-Structures-TagCallbackInfo-epcstrlen 'CSLibrary.Structures.TagCallbackInfo.epcstrlen')
  - [freqChannel](#F-CSLibrary-Structures-TagCallbackInfo-freqChannel 'CSLibrary.Structures.TagCallbackInfo.freqChannel')
  - [index](#F-CSLibrary-Structures-TagCallbackInfo-index 'CSLibrary.Structures.TagCallbackInfo.index')
  - [ms_ctr](#F-CSLibrary-Structures-TagCallbackInfo-ms_ctr 'CSLibrary.Structures.TagCallbackInfo.ms_ctr')
  - [name](#F-CSLibrary-Structures-TagCallbackInfo-name 'CSLibrary.Structures.TagCallbackInfo.name')
  - [pc](#F-CSLibrary-Structures-TagCallbackInfo-pc 'CSLibrary.Structures.TagCallbackInfo.pc')
  - [pcpublic](#F-CSLibrary-Structures-TagCallbackInfo-pcpublic 'CSLibrary.Structures.TagCallbackInfo.pcpublic')
  - [receiveTime](#F-CSLibrary-Structures-TagCallbackInfo-receiveTime 'CSLibrary.Structures.TagCallbackInfo.receiveTime')
  - [rssi](#F-CSLibrary-Structures-TagCallbackInfo-rssi 'CSLibrary.Structures.TagCallbackInfo.rssi')
  - [xpc_w1](#F-CSLibrary-Structures-TagCallbackInfo-xpc_w1 'CSLibrary.Structures.TagCallbackInfo.xpc_w1')
  - [xpc_w2](#F-CSLibrary-Structures-TagCallbackInfo-xpc_w2 'CSLibrary.Structures.TagCallbackInfo.xpc_w2')
- [TagGeneralSelectedParms](#T-CSLibrary-Structures-TagGeneralSelectedParms 'CSLibrary.Structures.TagGeneralSelectedParms')
  - [#ctor()](#M-CSLibrary-Structures-TagGeneralSelectedParms-#ctor 'CSLibrary.Structures.TagGeneralSelectedParms.#ctor')
  - [Mask](#F-CSLibrary-Structures-TagGeneralSelectedParms-Mask 'CSLibrary.Structures.TagGeneralSelectedParms.Mask')
  - [MaskLength](#F-CSLibrary-Structures-TagGeneralSelectedParms-MaskLength 'CSLibrary.Structures.TagGeneralSelectedParms.MaskLength')
  - [MaskOffset](#F-CSLibrary-Structures-TagGeneralSelectedParms-MaskOffset 'CSLibrary.Structures.TagGeneralSelectedParms.MaskOffset')
  - [ParallelEncoding](#F-CSLibrary-Structures-TagGeneralSelectedParms-ParallelEncoding 'CSLibrary.Structures.TagGeneralSelectedParms.ParallelEncoding')
  - [bank](#F-CSLibrary-Structures-TagGeneralSelectedParms-bank 'CSLibrary.Structures.TagGeneralSelectedParms.bank')
  - [epcMask](#F-CSLibrary-Structures-TagGeneralSelectedParms-epcMask 'CSLibrary.Structures.TagGeneralSelectedParms.epcMask')
  - [epcMaskLength](#F-CSLibrary-Structures-TagGeneralSelectedParms-epcMaskLength 'CSLibrary.Structures.TagGeneralSelectedParms.epcMaskLength')
  - [epcMaskOffset](#F-CSLibrary-Structures-TagGeneralSelectedParms-epcMaskOffset 'CSLibrary.Structures.TagGeneralSelectedParms.epcMaskOffset')
  - [flags](#F-CSLibrary-Structures-TagGeneralSelectedParms-flags 'CSLibrary.Structures.TagGeneralSelectedParms.flags')
- [TagGroup](#T-CSLibrary-Structures-TagGroup 'CSLibrary.Structures.TagGroup')
  - [#ctor()](#M-CSLibrary-Structures-TagGroup-#ctor 'CSLibrary.Structures.TagGroup.#ctor')
  - [#ctor(selected,session,target)](#M-CSLibrary-Structures-TagGroup-#ctor-CSLibrary-Constants-Selected,CSLibrary-Constants-Session,CSLibrary-Constants-SessionTarget- 'CSLibrary.Structures.TagGroup.#ctor(CSLibrary.Constants.Selected,CSLibrary.Constants.Session,CSLibrary.Constants.SessionTarget)')
  - [selected](#F-CSLibrary-Structures-TagGroup-selected 'CSLibrary.Structures.TagGroup.selected')
  - [session](#F-CSLibrary-Structures-TagGroup-session 'CSLibrary.Structures.TagGroup.session')
  - [target](#F-CSLibrary-Structures-TagGroup-target 'CSLibrary.Structures.TagGroup.target')
- [TagInventoryParms](#T-CSLibrary-Structures-TagInventoryParms 'CSLibrary.Structures.TagInventoryParms')
  - [accessPassword](#F-CSLibrary-Structures-TagInventoryParms-accessPassword 'CSLibrary.Structures.TagInventoryParms.accessPassword')
  - [bank1](#F-CSLibrary-Structures-TagInventoryParms-bank1 'CSLibrary.Structures.TagInventoryParms.bank1')
  - [bank2](#F-CSLibrary-Structures-TagInventoryParms-bank2 'CSLibrary.Structures.TagInventoryParms.bank2')
  - [count1](#F-CSLibrary-Structures-TagInventoryParms-count1 'CSLibrary.Structures.TagInventoryParms.count1')
  - [count2](#F-CSLibrary-Structures-TagInventoryParms-count2 'CSLibrary.Structures.TagInventoryParms.count2')
  - [flags](#F-CSLibrary-Structures-TagInventoryParms-flags 'CSLibrary.Structures.TagInventoryParms.flags')
  - [multibanks](#F-CSLibrary-Structures-TagInventoryParms-multibanks 'CSLibrary.Structures.TagInventoryParms.multibanks')
  - [offset1](#F-CSLibrary-Structures-TagInventoryParms-offset1 'CSLibrary.Structures.TagInventoryParms.offset1')
  - [offset2](#F-CSLibrary-Structures-TagInventoryParms-offset2 'CSLibrary.Structures.TagInventoryParms.offset2')
  - [tagStopCount](#F-CSLibrary-Structures-TagInventoryParms-tagStopCount 'CSLibrary.Structures.TagInventoryParms.tagStopCount')
- [TagKillParms](#T-CSLibrary-Structures-TagKillParms 'CSLibrary.Structures.TagKillParms')
  - [#ctor()](#M-CSLibrary-Structures-TagKillParms-#ctor 'CSLibrary.Structures.TagKillParms.#ctor')
  - [accessPassword](#F-CSLibrary-Structures-TagKillParms-accessPassword 'CSLibrary.Structures.TagKillParms.accessPassword')
  - [extCommand](#F-CSLibrary-Structures-TagKillParms-extCommand 'CSLibrary.Structures.TagKillParms.extCommand')
  - [flags](#F-CSLibrary-Structures-TagKillParms-flags 'CSLibrary.Structures.TagKillParms.flags')
  - [killPassword](#F-CSLibrary-Structures-TagKillParms-killPassword 'CSLibrary.Structures.TagKillParms.killPassword')
  - [retryCount](#F-CSLibrary-Structures-TagKillParms-retryCount 'CSLibrary.Structures.TagKillParms.retryCount')
- [TagLockParms](#T-CSLibrary-Structures-TagLockParms 'CSLibrary.Structures.TagLockParms')
  - [#ctor()](#M-CSLibrary-Structures-TagLockParms-#ctor 'CSLibrary.Structures.TagLockParms.#ctor')
  - [accessPassword](#F-CSLibrary-Structures-TagLockParms-accessPassword 'CSLibrary.Structures.TagLockParms.accessPassword')
  - [accessPasswordPermissions](#F-CSLibrary-Structures-TagLockParms-accessPasswordPermissions 'CSLibrary.Structures.TagLockParms.accessPasswordPermissions')
  - [epcMemoryBankPermissions](#F-CSLibrary-Structures-TagLockParms-epcMemoryBankPermissions 'CSLibrary.Structures.TagLockParms.epcMemoryBankPermissions')
  - [flags](#F-CSLibrary-Structures-TagLockParms-flags 'CSLibrary.Structures.TagLockParms.flags')
  - [killPasswordPermissions](#F-CSLibrary-Structures-TagLockParms-killPasswordPermissions 'CSLibrary.Structures.TagLockParms.killPasswordPermissions')
  - [length](#F-CSLibrary-Structures-TagLockParms-length 'CSLibrary.Structures.TagLockParms.length')
  - [retryCount](#F-CSLibrary-Structures-TagLockParms-retryCount 'CSLibrary.Structures.TagLockParms.retryCount')
  - [tidMemoryBankPermissions](#F-CSLibrary-Structures-TagLockParms-tidMemoryBankPermissions 'CSLibrary.Structures.TagLockParms.tidMemoryBankPermissions')
  - [userMemoryBankPermissions](#F-CSLibrary-Structures-TagLockParms-userMemoryBankPermissions 'CSLibrary.Structures.TagLockParms.userMemoryBankPermissions')
- [TagPerm](#T-CSLibrary-Structures-TagPerm 'CSLibrary.Structures.TagPerm')
  - [accessPasswordPermissions](#F-CSLibrary-Structures-TagPerm-accessPasswordPermissions 'CSLibrary.Structures.TagPerm.accessPasswordPermissions')
  - [epcMemoryBankPermissions](#F-CSLibrary-Structures-TagPerm-epcMemoryBankPermissions 'CSLibrary.Structures.TagPerm.epcMemoryBankPermissions')
  - [killPasswordPermissions](#F-CSLibrary-Structures-TagPerm-killPasswordPermissions 'CSLibrary.Structures.TagPerm.killPasswordPermissions')
  - [tidMemoryBankPermissions](#F-CSLibrary-Structures-TagPerm-tidMemoryBankPermissions 'CSLibrary.Structures.TagPerm.tidMemoryBankPermissions')
  - [userMemoryBankPermissions](#F-CSLibrary-Structures-TagPerm-userMemoryBankPermissions 'CSLibrary.Structures.TagPerm.userMemoryBankPermissions')
- [TagPostMachParms](#T-CSLibrary-Structures-TagPostMachParms 'CSLibrary.Structures.TagPostMachParms')
  - [#ctor()](#M-CSLibrary-Structures-TagPostMachParms-#ctor 'CSLibrary.Structures.TagPostMachParms.#ctor')
  - [count](#F-CSLibrary-Structures-TagPostMachParms-count 'CSLibrary.Structures.TagPostMachParms.count')
  - [mask](#F-CSLibrary-Structures-TagPostMachParms-mask 'CSLibrary.Structures.TagPostMachParms.mask')
  - [offset](#F-CSLibrary-Structures-TagPostMachParms-offset 'CSLibrary.Structures.TagPostMachParms.offset')
  - [toggleTarget](#F-CSLibrary-Structures-TagPostMachParms-toggleTarget 'CSLibrary.Structures.TagPostMachParms.toggleTarget')
- [TagRangingParms](#T-CSLibrary-Structures-TagRangingParms 'CSLibrary.Structures.TagRangingParms')
  - [QTMode](#F-CSLibrary-Structures-TagRangingParms-QTMode 'CSLibrary.Structures.TagRangingParms.QTMode')
  - [accessPassword](#F-CSLibrary-Structures-TagRangingParms-accessPassword 'CSLibrary.Structures.TagRangingParms.accessPassword')
  - [bank1](#F-CSLibrary-Structures-TagRangingParms-bank1 'CSLibrary.Structures.TagRangingParms.bank1')
  - [bank2](#F-CSLibrary-Structures-TagRangingParms-bank2 'CSLibrary.Structures.TagRangingParms.bank2')
  - [count1](#F-CSLibrary-Structures-TagRangingParms-count1 'CSLibrary.Structures.TagRangingParms.count1')
  - [count2](#F-CSLibrary-Structures-TagRangingParms-count2 'CSLibrary.Structures.TagRangingParms.count2')
  - [fastid](#F-CSLibrary-Structures-TagRangingParms-fastid 'CSLibrary.Structures.TagRangingParms.fastid')
  - [flags](#F-CSLibrary-Structures-TagRangingParms-flags 'CSLibrary.Structures.TagRangingParms.flags')
  - [focus](#F-CSLibrary-Structures-TagRangingParms-focus 'CSLibrary.Structures.TagRangingParms.focus')
  - [multibanks](#F-CSLibrary-Structures-TagRangingParms-multibanks 'CSLibrary.Structures.TagRangingParms.multibanks')
  - [offset1](#F-CSLibrary-Structures-TagRangingParms-offset1 'CSLibrary.Structures.TagRangingParms.offset1')
  - [offset2](#F-CSLibrary-Structures-TagRangingParms-offset2 'CSLibrary.Structures.TagRangingParms.offset2')
  - [retry](#F-CSLibrary-Structures-TagRangingParms-retry 'CSLibrary.Structures.TagRangingParms.retry')
  - [tagStopCount](#F-CSLibrary-Structures-TagRangingParms-tagStopCount 'CSLibrary.Structures.TagRangingParms.tagStopCount')
- [TagReadEpcParms](#T-CSLibrary-Structures-TagReadEpcParms 'CSLibrary.Structures.TagReadEpcParms')
  - [#ctor()](#M-CSLibrary-Structures-TagReadEpcParms-#ctor 'CSLibrary.Structures.TagReadEpcParms.#ctor')
  - [accessPassword](#F-CSLibrary-Structures-TagReadEpcParms-accessPassword 'CSLibrary.Structures.TagReadEpcParms.accessPassword')
  - [count](#F-CSLibrary-Structures-TagReadEpcParms-count 'CSLibrary.Structures.TagReadEpcParms.count')
  - [m_epc](#F-CSLibrary-Structures-TagReadEpcParms-m_epc 'CSLibrary.Structures.TagReadEpcParms.m_epc')
  - [offset](#F-CSLibrary-Structures-TagReadEpcParms-offset 'CSLibrary.Structures.TagReadEpcParms.offset')
  - [retryCount](#F-CSLibrary-Structures-TagReadEpcParms-retryCount 'CSLibrary.Structures.TagReadEpcParms.retryCount')
  - [epc](#P-CSLibrary-Structures-TagReadEpcParms-epc 'CSLibrary.Structures.TagReadEpcParms.epc')
- [TagReadParms](#T-CSLibrary-Structures-TagReadParms 'CSLibrary.Structures.TagReadParms')
  - [#ctor()](#M-CSLibrary-Structures-TagReadParms-#ctor 'CSLibrary.Structures.TagReadParms.#ctor')
  - [accessPassword](#F-CSLibrary-Structures-TagReadParms-accessPassword 'CSLibrary.Structures.TagReadParms.accessPassword')
  - [count](#F-CSLibrary-Structures-TagReadParms-count 'CSLibrary.Structures.TagReadParms.count')
  - [m_pData](#F-CSLibrary-Structures-TagReadParms-m_pData 'CSLibrary.Structures.TagReadParms.m_pData')
  - [offset](#F-CSLibrary-Structures-TagReadParms-offset 'CSLibrary.Structures.TagReadParms.offset')
  - [retryCount](#F-CSLibrary-Structures-TagReadParms-retryCount 'CSLibrary.Structures.TagReadParms.retryCount')
  - [pData](#P-CSLibrary-Structures-TagReadParms-pData 'CSLibrary.Structures.TagReadParms.pData')
- [TagReadPcParms](#T-CSLibrary-Structures-TagReadPcParms 'CSLibrary.Structures.TagReadPcParms')
  - [#ctor()](#M-CSLibrary-Structures-TagReadPcParms-#ctor 'CSLibrary.Structures.TagReadPcParms.#ctor')
  - [accessPassword](#F-CSLibrary-Structures-TagReadPcParms-accessPassword 'CSLibrary.Structures.TagReadPcParms.accessPassword')
  - [m_pc](#F-CSLibrary-Structures-TagReadPcParms-m_pc 'CSLibrary.Structures.TagReadPcParms.m_pc')
  - [retryCount](#F-CSLibrary-Structures-TagReadPcParms-retryCount 'CSLibrary.Structures.TagReadPcParms.retryCount')
  - [pc](#P-CSLibrary-Structures-TagReadPcParms-pc 'CSLibrary.Structures.TagReadPcParms.pc')
- [TagReadProtectParms](#T-CSLibrary-Structures-TagReadProtectParms 'CSLibrary.Structures.TagReadProtectParms')
  - [accessPassword](#F-CSLibrary-Structures-TagReadProtectParms-accessPassword 'CSLibrary.Structures.TagReadProtectParms.accessPassword')
  - [flags](#F-CSLibrary-Structures-TagReadProtectParms-flags 'CSLibrary.Structures.TagReadProtectParms.flags')
  - [retryCount](#F-CSLibrary-Structures-TagReadProtectParms-retryCount 'CSLibrary.Structures.TagReadProtectParms.retryCount')
- [TagReadPwdParms](#T-CSLibrary-Structures-TagReadPwdParms 'CSLibrary.Structures.TagReadPwdParms')
  - [#ctor()](#M-CSLibrary-Structures-TagReadPwdParms-#ctor 'CSLibrary.Structures.TagReadPwdParms.#ctor')
  - [accessPassword](#F-CSLibrary-Structures-TagReadPwdParms-accessPassword 'CSLibrary.Structures.TagReadPwdParms.accessPassword')
  - [m_password](#F-CSLibrary-Structures-TagReadPwdParms-m_password 'CSLibrary.Structures.TagReadPwdParms.m_password')
  - [retryCount](#F-CSLibrary-Structures-TagReadPwdParms-retryCount 'CSLibrary.Structures.TagReadPwdParms.retryCount')
  - [password](#P-CSLibrary-Structures-TagReadPwdParms-password 'CSLibrary.Structures.TagReadPwdParms.password')
- [TagReadTidParms](#T-CSLibrary-Structures-TagReadTidParms 'CSLibrary.Structures.TagReadTidParms')
  - [#ctor()](#M-CSLibrary-Structures-TagReadTidParms-#ctor 'CSLibrary.Structures.TagReadTidParms.#ctor')
  - [accessPassword](#F-CSLibrary-Structures-TagReadTidParms-accessPassword 'CSLibrary.Structures.TagReadTidParms.accessPassword')
  - [count](#F-CSLibrary-Structures-TagReadTidParms-count 'CSLibrary.Structures.TagReadTidParms.count')
  - [offset](#F-CSLibrary-Structures-TagReadTidParms-offset 'CSLibrary.Structures.TagReadTidParms.offset')
  - [pData](#F-CSLibrary-Structures-TagReadTidParms-pData 'CSLibrary.Structures.TagReadTidParms.pData')
  - [retryCount](#F-CSLibrary-Structures-TagReadTidParms-retryCount 'CSLibrary.Structures.TagReadTidParms.retryCount')
  - [tid](#P-CSLibrary-Structures-TagReadTidParms-tid 'CSLibrary.Structures.TagReadTidParms.tid')
- [TagReadUserParms](#T-CSLibrary-Structures-TagReadUserParms 'CSLibrary.Structures.TagReadUserParms')
  - [#ctor()](#M-CSLibrary-Structures-TagReadUserParms-#ctor 'CSLibrary.Structures.TagReadUserParms.#ctor')
  - [accessPassword](#F-CSLibrary-Structures-TagReadUserParms-accessPassword 'CSLibrary.Structures.TagReadUserParms.accessPassword')
  - [count](#F-CSLibrary-Structures-TagReadUserParms-count 'CSLibrary.Structures.TagReadUserParms.count')
  - [m_pData](#F-CSLibrary-Structures-TagReadUserParms-m_pData 'CSLibrary.Structures.TagReadUserParms.m_pData')
  - [offset](#F-CSLibrary-Structures-TagReadUserParms-offset 'CSLibrary.Structures.TagReadUserParms.offset')
  - [retryCount](#F-CSLibrary-Structures-TagReadUserParms-retryCount 'CSLibrary.Structures.TagReadUserParms.retryCount')
  - [pData](#P-CSLibrary-Structures-TagReadUserParms-pData 'CSLibrary.Structures.TagReadUserParms.pData')
- [TagSearchingParms](#T-CSLibrary-Structures-TagSearchingParms 'CSLibrary.Structures.TagSearchingParms')
  - [avgRssi](#F-CSLibrary-Structures-TagSearchingParms-avgRssi 'CSLibrary.Structures.TagSearchingParms.avgRssi')
- [TagSelectedParms](#T-CSLibrary-Structures-TagSelectedParms 'CSLibrary.Structures.TagSelectedParms')
  - [#ctor()](#M-CSLibrary-Structures-TagSelectedParms-#ctor 'CSLibrary.Structures.TagSelectedParms.#ctor')
  - [Mask](#F-CSLibrary-Structures-TagSelectedParms-Mask 'CSLibrary.Structures.TagSelectedParms.Mask')
  - [MaskLength](#F-CSLibrary-Structures-TagSelectedParms-MaskLength 'CSLibrary.Structures.TagSelectedParms.MaskLength')
  - [MaskOffset](#F-CSLibrary-Structures-TagSelectedParms-MaskOffset 'CSLibrary.Structures.TagSelectedParms.MaskOffset')
  - [ParallelEncoding](#F-CSLibrary-Structures-TagSelectedParms-ParallelEncoding 'CSLibrary.Structures.TagSelectedParms.ParallelEncoding')
  - [Qvalue](#F-CSLibrary-Structures-TagSelectedParms-Qvalue 'CSLibrary.Structures.TagSelectedParms.Qvalue')
  - [bank](#F-CSLibrary-Structures-TagSelectedParms-bank 'CSLibrary.Structures.TagSelectedParms.bank')
  - [epcMask](#F-CSLibrary-Structures-TagSelectedParms-epcMask 'CSLibrary.Structures.TagSelectedParms.epcMask')
  - [epcMaskLength](#F-CSLibrary-Structures-TagSelectedParms-epcMaskLength 'CSLibrary.Structures.TagSelectedParms.epcMaskLength')
  - [epcMaskOffset](#F-CSLibrary-Structures-TagSelectedParms-epcMaskOffset 'CSLibrary.Structures.TagSelectedParms.epcMaskOffset')
  - [flags](#F-CSLibrary-Structures-TagSelectedParms-flags 'CSLibrary.Structures.TagSelectedParms.flags')
- [TagWriteEpcParms](#T-CSLibrary-Structures-TagWriteEpcParms 'CSLibrary.Structures.TagWriteEpcParms')
  - [#ctor()](#M-CSLibrary-Structures-TagWriteEpcParms-#ctor 'CSLibrary.Structures.TagWriteEpcParms.#ctor')
  - [accessPassword](#F-CSLibrary-Structures-TagWriteEpcParms-accessPassword 'CSLibrary.Structures.TagWriteEpcParms.accessPassword')
  - [count](#F-CSLibrary-Structures-TagWriteEpcParms-count 'CSLibrary.Structures.TagWriteEpcParms.count')
  - [epc](#F-CSLibrary-Structures-TagWriteEpcParms-epc 'CSLibrary.Structures.TagWriteEpcParms.epc')
  - [offset](#F-CSLibrary-Structures-TagWriteEpcParms-offset 'CSLibrary.Structures.TagWriteEpcParms.offset')
  - [retryCount](#F-CSLibrary-Structures-TagWriteEpcParms-retryCount 'CSLibrary.Structures.TagWriteEpcParms.retryCount')
  - [writeRetryCount](#F-CSLibrary-Structures-TagWriteEpcParms-writeRetryCount 'CSLibrary.Structures.TagWriteEpcParms.writeRetryCount')
- [TagWriteParms](#T-CSLibrary-Structures-TagWriteParms 'CSLibrary.Structures.TagWriteParms')
  - [accessPassword](#F-CSLibrary-Structures-TagWriteParms-accessPassword 'CSLibrary.Structures.TagWriteParms.accessPassword')
  - [count](#F-CSLibrary-Structures-TagWriteParms-count 'CSLibrary.Structures.TagWriteParms.count')
  - [flags](#F-CSLibrary-Structures-TagWriteParms-flags 'CSLibrary.Structures.TagWriteParms.flags')
  - [offset](#F-CSLibrary-Structures-TagWriteParms-offset 'CSLibrary.Structures.TagWriteParms.offset')
  - [pData](#F-CSLibrary-Structures-TagWriteParms-pData 'CSLibrary.Structures.TagWriteParms.pData')
  - [retryCount](#F-CSLibrary-Structures-TagWriteParms-retryCount 'CSLibrary.Structures.TagWriteParms.retryCount')
  - [writeRetryCount](#F-CSLibrary-Structures-TagWriteParms-writeRetryCount 'CSLibrary.Structures.TagWriteParms.writeRetryCount')
- [TagWritePcParms](#T-CSLibrary-Structures-TagWritePcParms 'CSLibrary.Structures.TagWritePcParms')
  - [accessPassword](#F-CSLibrary-Structures-TagWritePcParms-accessPassword 'CSLibrary.Structures.TagWritePcParms.accessPassword')
  - [flags](#F-CSLibrary-Structures-TagWritePcParms-flags 'CSLibrary.Structures.TagWritePcParms.flags')
  - [pc](#F-CSLibrary-Structures-TagWritePcParms-pc 'CSLibrary.Structures.TagWritePcParms.pc')
  - [retryCount](#F-CSLibrary-Structures-TagWritePcParms-retryCount 'CSLibrary.Structures.TagWritePcParms.retryCount')
  - [writeRetryCount](#F-CSLibrary-Structures-TagWritePcParms-writeRetryCount 'CSLibrary.Structures.TagWritePcParms.writeRetryCount')
- [TagWritePwdParms](#T-CSLibrary-Structures-TagWritePwdParms 'CSLibrary.Structures.TagWritePwdParms')
  - [accessPassword](#F-CSLibrary-Structures-TagWritePwdParms-accessPassword 'CSLibrary.Structures.TagWritePwdParms.accessPassword')
  - [flags](#F-CSLibrary-Structures-TagWritePwdParms-flags 'CSLibrary.Structures.TagWritePwdParms.flags')
  - [password](#F-CSLibrary-Structures-TagWritePwdParms-password 'CSLibrary.Structures.TagWritePwdParms.password')
  - [retryCount](#F-CSLibrary-Structures-TagWritePwdParms-retryCount 'CSLibrary.Structures.TagWritePwdParms.retryCount')
  - [writeRetryCount](#F-CSLibrary-Structures-TagWritePwdParms-writeRetryCount 'CSLibrary.Structures.TagWritePwdParms.writeRetryCount')
- [TagWriteUserParms](#T-CSLibrary-Structures-TagWriteUserParms 'CSLibrary.Structures.TagWriteUserParms')
  - [accessPassword](#F-CSLibrary-Structures-TagWriteUserParms-accessPassword 'CSLibrary.Structures.TagWriteUserParms.accessPassword')
  - [count](#F-CSLibrary-Structures-TagWriteUserParms-count 'CSLibrary.Structures.TagWriteUserParms.count')
  - [flags](#F-CSLibrary-Structures-TagWriteUserParms-flags 'CSLibrary.Structures.TagWriteUserParms.flags')
  - [offset](#F-CSLibrary-Structures-TagWriteUserParms-offset 'CSLibrary.Structures.TagWriteUserParms.offset')
  - [pData](#F-CSLibrary-Structures-TagWriteUserParms-pData 'CSLibrary.Structures.TagWriteUserParms.pData')
  - [retryCount](#F-CSLibrary-Structures-TagWriteUserParms-retryCount 'CSLibrary.Structures.TagWriteUserParms.retryCount')
  - [writeRetryCount](#F-CSLibrary-Structures-TagWriteUserParms-writeRetryCount 'CSLibrary.Structures.TagWriteUserParms.writeRetryCount')
- [Target](#T-CSLibrary-Constants-Target 'CSLibrary.Constants.Target')
  - [S0](#F-CSLibrary-Constants-Target-S0 'CSLibrary.Constants.Target.S0')
  - [S1](#F-CSLibrary-Constants-Target-S1 'CSLibrary.Constants.Target.S1')
  - [S2](#F-CSLibrary-Constants-Target-S2 'CSLibrary.Constants.Target.S2')
  - [S3](#F-CSLibrary-Constants-Target-S3 'CSLibrary.Constants.Target.S3')
  - [SELECTED](#F-CSLibrary-Constants-Target-SELECTED 'CSLibrary.Constants.Target.SELECTED')
  - [UNKNOWN](#F-CSLibrary-Constants-Target-UNKNOWN 'CSLibrary.Constants.Target.UNKNOWN')
- [TemperatureParms](#T-CSLibrary-Structures-TemperatureParms 'CSLibrary.Structures.TemperatureParms')
  - [amb](#F-CSLibrary-Structures-TemperatureParms-amb 'CSLibrary.Structures.TemperatureParms.amb')
  - [pwramp](#F-CSLibrary-Structures-TemperatureParms-pwramp 'CSLibrary.Structures.TemperatureParms.pwramp')
  - [xcvr](#F-CSLibrary-Structures-TemperatureParms-xcvr 'CSLibrary.Structures.TemperatureParms.xcvr')
- [ThresholdTemperatureParms](#T-CSLibrary-Structures-ThresholdTemperatureParms 'CSLibrary.Structures.ThresholdTemperatureParms')
  - [amb](#F-CSLibrary-Structures-ThresholdTemperatureParms-amb 'CSLibrary.Structures.ThresholdTemperatureParms.amb')
  - [delta](#F-CSLibrary-Structures-ThresholdTemperatureParms-delta 'CSLibrary.Structures.ThresholdTemperatureParms.delta')
  - [pwramp](#F-CSLibrary-Structures-ThresholdTemperatureParms-pwramp 'CSLibrary.Structures.ThresholdTemperatureParms.pwramp')
  - [xcvr](#F-CSLibrary-Structures-ThresholdTemperatureParms-xcvr 'CSLibrary.Structures.ThresholdTemperatureParms.xcvr')
- [TimeEvent](#T-CSLibrary-Net-TimeEvent 'CSLibrary.Net.TimeEvent')
  - [days](#F-CSLibrary-Net-TimeEvent-days 'CSLibrary.Net.TimeEvent.days')
  - [hours](#F-CSLibrary-Net-TimeEvent-hours 'CSLibrary.Net.TimeEvent.hours')
  - [minutes](#F-CSLibrary-Net-TimeEvent-minutes 'CSLibrary.Net.TimeEvent.minutes')
  - [name](#F-CSLibrary-Net-TimeEvent-name 'CSLibrary.Net.TimeEvent.name')
  - [seconds](#F-CSLibrary-Net-TimeEvent-seconds 'CSLibrary.Net.TimeEvent.seconds')
- [UpdatePercentArgs](#T-CSLibrary-Net-UpdatePercentArgs 'CSLibrary.Net.UpdatePercentArgs')
  - [#ctor(percent)](#M-CSLibrary-Net-UpdatePercentArgs-#ctor-System-Int32- 'CSLibrary.Net.UpdatePercentArgs.#ctor(System.Int32)')
  - [Percent](#P-CSLibrary-Net-UpdatePercentArgs-Percent 'CSLibrary.Net.UpdatePercentArgs.Percent')
- [UpdateResult](#T-CSLibrary-Net-UpdateResult 'CSLibrary.Net.UpdateResult')
  - [FAIL](#F-CSLibrary-Net-UpdateResult-FAIL 'CSLibrary.Net.UpdateResult.FAIL')
  - [SUCCESS](#F-CSLibrary-Net-UpdateResult-SUCCESS 'CSLibrary.Net.UpdateResult.SUCCESS')
- [UpdateResultArgs](#T-CSLibrary-Net-UpdateResultArgs 'CSLibrary.Net.UpdateResultArgs')
  - [#ctor(Result)](#M-CSLibrary-Net-UpdateResultArgs-#ctor-CSLibrary-Net-UpdateResult- 'CSLibrary.Net.UpdateResultArgs.#ctor(CSLibrary.Net.UpdateResult)')
  - [Result](#P-CSLibrary-Net-UpdateResultArgs-Result 'CSLibrary.Net.UpdateResultArgs.Result')
- [Version](#T-CSLibrary-Structures-Version 'CSLibrary.Structures.Version')
  - [#ctor()](#M-CSLibrary-Structures-Version-#ctor 'CSLibrary.Structures.Version.#ctor')
  - [major](#F-CSLibrary-Structures-Version-major 'CSLibrary.Structures.Version.major')
  - [minor](#F-CSLibrary-Structures-Version-minor 'CSLibrary.Structures.Version.minor')
  - [patch](#F-CSLibrary-Structures-Version-patch 'CSLibrary.Structures.Version.patch')
  - [ToString()](#M-CSLibrary-Structures-Version-ToString 'CSLibrary.Structures.Version.ToString')
- [Win32](#T-CSLibrary-Win32 'CSLibrary.Win32')
  - [GetExitCodeThread(dest,src,size)](#M-CSLibrary-Win32-GetExitCodeThread-System-UInt32,System-UInt32@- 'CSLibrary.Win32.GetExitCodeThread(System.UInt32,System.UInt32@)')
  - [_lrotl(value,shift)](#M-CSLibrary-Win32-_lrotl-System-UInt32,System-UInt32- 'CSLibrary.Win32._lrotl(System.UInt32,System.UInt32)')
  - [_lrotr(value,shift)](#M-CSLibrary-Win32-_lrotr-System-UInt32,System-UInt32- 'CSLibrary.Win32._lrotr(System.UInt32,System.UInt32)')
  - [memcmp(src1,src2,size)](#M-CSLibrary-Win32-memcmp-System-Byte[],System-Byte[],System-Int32- 'CSLibrary.Win32.memcmp(System.Byte[],System.Byte[],System.Int32)')
- [WriteParms](#T-CSLibrary-Structures-WriteParms 'CSLibrary.Structures.WriteParms')
  - [#ctor(initial)](#M-CSLibrary-Structures-WriteParms-#ctor-System-Boolean- 'CSLibrary.Structures.WriteParms.#ctor(System.Boolean)')
  - [accessPassword](#F-CSLibrary-Structures-WriteParms-accessPassword 'CSLibrary.Structures.WriteParms.accessPassword')
  - [common](#F-CSLibrary-Structures-WriteParms-common 'CSLibrary.Structures.WriteParms.common')
  - [length](#F-CSLibrary-Structures-WriteParms-length 'CSLibrary.Structures.WriteParms.length')
  - [writeRandomParms](#F-CSLibrary-Structures-WriteParms-writeRandomParms 'CSLibrary.Structures.WriteParms.writeRandomParms')
  - [writeSequentialParms](#F-CSLibrary-Structures-WriteParms-writeSequentialParms 'CSLibrary.Structures.WriteParms.writeSequentialParms')
  - [writeType](#F-CSLibrary-Structures-WriteParms-writeType 'CSLibrary.Structures.WriteParms.writeType')
- [WriteRandomParms](#T-CSLibrary-Structures-WriteRandomParms 'CSLibrary.Structures.WriteRandomParms')
  - [#ctor(bnk,count,offset,data)](#M-CSLibrary-Structures-WriteRandomParms-#ctor-CSLibrary-Constants-MemoryBank,System-UInt16,System-UInt16[],System-UInt16[]- 'CSLibrary.Structures.WriteRandomParms.#ctor(CSLibrary.Constants.MemoryBank,System.UInt16,System.UInt16[],System.UInt16[])')
  - [bank](#F-CSLibrary-Structures-WriteRandomParms-bank 'CSLibrary.Structures.WriteRandomParms.bank')
  - [count](#F-CSLibrary-Structures-WriteRandomParms-count 'CSLibrary.Structures.WriteRandomParms.count')
  - [length](#F-CSLibrary-Structures-WriteRandomParms-length 'CSLibrary.Structures.WriteRandomParms.length')
  - [pData](#F-CSLibrary-Structures-WriteRandomParms-pData 'CSLibrary.Structures.WriteRandomParms.pData')
  - [pOffset](#F-CSLibrary-Structures-WriteRandomParms-pOffset 'CSLibrary.Structures.WriteRandomParms.pOffset')
  - [reserved](#F-CSLibrary-Structures-WriteRandomParms-reserved 'CSLibrary.Structures.WriteRandomParms.reserved')
  - [Dispose()](#M-CSLibrary-Structures-WriteRandomParms-Dispose 'CSLibrary.Structures.WriteRandomParms.Dispose')
- [WriteSequentialParms](#T-CSLibrary-Structures-WriteSequentialParms 'CSLibrary.Structures.WriteSequentialParms')
  - [#ctor(bnk,count,offset,data)](#M-CSLibrary-Structures-WriteSequentialParms-#ctor-CSLibrary-Constants-MemoryBank,System-UInt16,System-UInt16,System-UInt16[]- 'CSLibrary.Structures.WriteSequentialParms.#ctor(CSLibrary.Constants.MemoryBank,System.UInt16,System.UInt16,System.UInt16[])')
  - [bank](#F-CSLibrary-Structures-WriteSequentialParms-bank 'CSLibrary.Structures.WriteSequentialParms.bank')
  - [count](#F-CSLibrary-Structures-WriteSequentialParms-count 'CSLibrary.Structures.WriteSequentialParms.count')
  - [length](#F-CSLibrary-Structures-WriteSequentialParms-length 'CSLibrary.Structures.WriteSequentialParms.length')
  - [offset](#F-CSLibrary-Structures-WriteSequentialParms-offset 'CSLibrary.Structures.WriteSequentialParms.offset')
  - [pData](#F-CSLibrary-Structures-WriteSequentialParms-pData 'CSLibrary.Structures.WriteSequentialParms.pData')
  - [reserved](#F-CSLibrary-Structures-WriteSequentialParms-reserved 'CSLibrary.Structures.WriteSequentialParms.reserved')
  - [Dispose()](#M-CSLibrary-Structures-WriteSequentialParms-Dispose 'CSLibrary.Structures.WriteSequentialParms.Dispose')
- [WriteType](#T-CSLibrary-Constants-WriteType 'CSLibrary.Constants.WriteType')
  - [RANDOM](#F-CSLibrary-Constants-WriteType-RANDOM 'CSLibrary.Constants.WriteType.RANDOM')
  - [SEQUENTIAL](#F-CSLibrary-Constants-WriteType-SEQUENTIAL 'CSLibrary.Constants.WriteType.SEQUENTIAL')
  - [UNKNOWN](#F-CSLibrary-Constants-WriteType-UNKNOWN 'CSLibrary.Constants.WriteType.UNKNOWN')
- [oldHex](#T-CSLibrary-Text-oldHex 'CSLibrary.Text.oldHex')
  - [Compare(source,target)](#M-CSLibrary-Text-oldHex-Compare-System-String,System-String- 'CSLibrary.Text.oldHex.Compare(System.String,System.String)')
  - [Compare(source,target)](#M-CSLibrary-Text-oldHex-Compare-System-Byte[],System-Byte[]- 'CSLibrary.Text.oldHex.Compare(System.Byte[],System.Byte[])')
  - [Compare(source,target,size)](#M-CSLibrary-Text-oldHex-Compare-System-Byte[],System-Byte[],System-Int32- 'CSLibrary.Text.oldHex.Compare(System.Byte[],System.Byte[],System.Int32)')
  - [Compare\`\`1(a,b)](#M-CSLibrary-Text-oldHex-Compare``1-``0[],``0[]- 'CSLibrary.Text.oldHex.Compare``1(``0[],``0[])')
  - [Copy(src,dst,count)](#M-CSLibrary-Text-oldHex-Copy-System-Byte[],System-Byte[],System-Int32- 'CSLibrary.Text.oldHex.Copy(System.Byte[],System.Byte[],System.Int32)')
  - [Copy(src,dst,dstIndex,count)](#M-CSLibrary-Text-oldHex-Copy-System-Byte[],System-Byte[],System-Int32,System-Int32- 'CSLibrary.Text.oldHex.Copy(System.Byte[],System.Byte[],System.Int32,System.Int32)')
  - [Copy(src,srcIndex,dst,dstIndex,count)](#M-CSLibrary-Text-oldHex-Copy-System-Byte[],System-Int32,System-Byte[],System-Int32,System-Int32- 'CSLibrary.Text.oldHex.Copy(System.Byte[],System.Int32,System.Byte[],System.Int32,System.Int32)')
  - [GenPostMatchMask(hexString)](#M-CSLibrary-Text-oldHex-GenPostMatchMask-System-String- 'CSLibrary.Text.oldHex.GenPostMatchMask(System.String)')
  - [GenSelectMask(hexString)](#M-CSLibrary-Text-oldHex-GenSelectMask-System-String- 'CSLibrary.Text.oldHex.GenSelectMask(System.String)')
  - [GetBitCount(hexString)](#M-CSLibrary-Text-oldHex-GetBitCount-System-String- 'CSLibrary.Text.oldHex.GetBitCount(System.String)')
  - [GetBitCount(bytes)](#M-CSLibrary-Text-oldHex-GetBitCount-System-Byte[]- 'CSLibrary.Text.oldHex.GetBitCount(System.Byte[])')
  - [GetByteCount(hexString)](#M-CSLibrary-Text-oldHex-GetByteCount-System-String- 'CSLibrary.Text.oldHex.GetByteCount(System.String)')
  - [GetWordCount(hexString)](#M-CSLibrary-Text-oldHex-GetWordCount-System-String- 'CSLibrary.Text.oldHex.GetWordCount(System.String)')
  - [HexToByte(hex)](#M-CSLibrary-Text-oldHex-HexToByte-System-String- 'CSLibrary.Text.oldHex.HexToByte(System.String)')
  - [IsHexFormat(hexString)](#M-CSLibrary-Text-oldHex-IsHexFormat-System-String- 'CSLibrary.Text.oldHex.IsHexFormat(System.String)')
  - [ToByte(hexString)](#M-CSLibrary-Text-oldHex-ToByte-System-String- 'CSLibrary.Text.oldHex.ToByte(System.String)')
  - [ToBytes(hexString)](#M-CSLibrary-Text-oldHex-ToBytes-System-String- 'CSLibrary.Text.oldHex.ToBytes(System.String)')
  - [ToBytes(data)](#M-CSLibrary-Text-oldHex-ToBytes-System-UInt16[]- 'CSLibrary.Text.oldHex.ToBytes(System.UInt16[])')
  - [ToInt16(buffer,offset)](#M-CSLibrary-Text-oldHex-ToInt16-System-Byte[],System-Int32- 'CSLibrary.Text.oldHex.ToInt16(System.Byte[],System.Int32)')
  - [ToString(bytes)](#M-CSLibrary-Text-oldHex-ToString-System-Byte[]- 'CSLibrary.Text.oldHex.ToString(System.Byte[])')
  - [ToString(bytes,offset,count)](#M-CSLibrary-Text-oldHex-ToString-System-Byte[],System-UInt32,System-UInt32- 'CSLibrary.Text.oldHex.ToString(System.Byte[],System.UInt32,System.UInt32)')
  - [ToString(data)](#M-CSLibrary-Text-oldHex-ToString-System-UInt16[]- 'CSLibrary.Text.oldHex.ToString(System.UInt16[])')
  - [ToString(data,offset,count)](#M-CSLibrary-Text-oldHex-ToString-System-UInt16[],System-UInt32,System-UInt32- 'CSLibrary.Text.oldHex.ToString(System.UInt16[],System.UInt32,System.UInt32)')
  - [ToUInt16(buffer,offset)](#M-CSLibrary-Text-oldHex-ToUInt16-System-Byte[],System-Int32- 'CSLibrary.Text.oldHex.ToUInt16(System.Byte[],System.Int32)')
  - [ToUInt32(buffer,offset)](#M-CSLibrary-Text-oldHex-ToUInt32-System-Byte[],System-Int32- 'CSLibrary.Text.oldHex.ToUInt32(System.Byte[],System.Int32)')
  - [ToUInt32(hexString)](#M-CSLibrary-Text-oldHex-ToUInt32-System-String- 'CSLibrary.Text.oldHex.ToUInt32(System.String)')
  - [ToUInt64(buffer,offset)](#M-CSLibrary-Text-oldHex-ToUInt64-System-Byte[],System-Int32- 'CSLibrary.Text.oldHex.ToUInt64(System.Byte[],System.Int32)')
  - [ToUshort(str)](#M-CSLibrary-Text-oldHex-ToUshort-System-String- 'CSLibrary.Text.oldHex.ToUshort(System.String)')
  - [ToUshorts(Input)](#M-CSLibrary-Text-oldHex-ToUshorts-System-Byte[]- 'CSLibrary.Text.oldHex.ToUshorts(System.Byte[])')
  - [ToUshorts(Input)](#M-CSLibrary-Text-oldHex-ToUshorts-System-String- 'CSLibrary.Text.oldHex.ToUshorts(System.String)')

<a name='T-CSLibrary-Constants-ACID'></a>
## ACID `type`

##### Namespace

CSLibrary.Constants

##### Summary

Allocation Class Identifier

<a name='F-CSLibrary-Constants-ACID-APACS'></a>
### APACS `constants`

##### Summary

ISO/IEC 7816-6 registration authority

<a name='F-CSLibrary-Constants-ACID-APACSX'></a>
### APACSX `constants`

##### Summary

ISO/IEC 7816-6 registration authority(includes memory size and XTID Header)

<a name='F-CSLibrary-Constants-ACID-GS1'></a>
### GS1 `constants`

##### Summary

EPCglobal

<a name='F-CSLibrary-Constants-ACID-NEN'></a>
### NEN `constants`

##### Summary

ISO/TS 14816 registration authority

<a name='F-CSLibrary-Constants-ACID-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown authority

<a name='T-CSLibrary-Constants-Action'></a>
## Action `type`

##### Namespace

CSLibrary.Constants

##### Summary

Specifies the action that will be applied to the tag populations (i.e, the 
matching and non-matching tags).

<a name='F-CSLibrary-Constants-Action-ASLINVA_DSLINVB'></a>
### ASLINVA_DSLINVB `constants`

##### Summary

Match : Assert SL or inventoried -> A      
Non-Match : Deassert SL or inventoried -> B

<a name='F-CSLibrary-Constants-Action-ASLINVA_NOTHING'></a>
### ASLINVA_NOTHING `constants`

##### Summary

Match : Assert SL or inventoried -> A
Non-Match : Nothing

<a name='F-CSLibrary-Constants-Action-DSLINVB_ASLINVA'></a>
### DSLINVB_ASLINVA `constants`

##### Summary

Match : Deassert SL or inventoried -> B
Non-Match : Assert SL or inventoried -> A

<a name='F-CSLibrary-Constants-Action-DSLINVB_NOTHING'></a>
### DSLINVB_NOTHING `constants`

##### Summary

Match : Deassert SL or inventoried -> B
Non-Match : Nothing

<a name='F-CSLibrary-Constants-Action-NOTHING_ASLINVA'></a>
### NOTHING_ASLINVA `constants`

##### Summary

Match : Nothing 
Non-Match : Assert SL or inventoried -> A

<a name='F-CSLibrary-Constants-Action-NOTHING_DSLINVB'></a>
### NOTHING_DSLINVB `constants`

##### Summary

Match : Nothing
Non-Match : Deassert SL or inventoried -> B

<a name='F-CSLibrary-Constants-Action-NOTHING_NSLINVS'></a>
### NOTHING_NSLINVS `constants`

##### Summary

Match : Nothing 
Non-Match : Negate SL or (A -> B, B -> A)

<a name='F-CSLibrary-Constants-Action-NSLINVS_NOTHING'></a>
### NSLINVS_NOTHING `constants`

##### Summary

Match : Negate SL or (A -> B, B -> A)
Non-Match : Nothing

<a name='F-CSLibrary-Constants-Action-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown action

<a name='T-CSLibrary-Antenna'></a>
## Antenna `type`

##### Namespace

CSLibrary

##### Summary

Antenna

<a name='M-CSLibrary-Antenna-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='M-CSLibrary-Antenna-#ctor-System-UInt32-'></a>
### #ctor(port) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| port | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |

<a name='M-CSLibrary-Antenna-#ctor-System-UInt32,CSLibrary-Constants-AntennaPortState,System-UInt32,System-UInt32,System-UInt32,System-UInt32,System-UInt32,System-Boolean,System-Boolean,CSLibrary-Constants-SingulationAlgorithm,System-UInt32,System-Boolean,System-UInt32,System-Boolean,System-UInt32,System-UInt32-'></a>
### #ctor(port,state,powerLevel,dwellTime,numberInventoryCycles,antennaSenseThreshold) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| port | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| state | [CSLibrary.Constants.AntennaPortState](#T-CSLibrary-Constants-AntennaPortState 'CSLibrary.Constants.AntennaPortState') |  |
| powerLevel | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| dwellTime | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| numberInventoryCycles | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| antennaSenseThreshold | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |

<a name='M-CSLibrary-Antenna-#ctor-CSLibrary-Antenna-'></a>
### #ctor(antenna) `constructor`

##### Summary

Copy Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| antenna | [CSLibrary.Antenna](#T-CSLibrary-Antenna 'CSLibrary.Antenna') |  |

<a name='F-CSLibrary-Antenna-POWER_MAXIMUM'></a>
### POWER_MAXIMUM `constants`

##### Summary

POWER_MAXIMUM

<a name='F-CSLibrary-Antenna-POWER_MINIMUM'></a>
### POWER_MINIMUM `constants`

##### Summary

POWER_MINIMUM

<a name='F-CSLibrary-Antenna-RX_LOGICAL_MAXIMUM'></a>
### RX_LOGICAL_MAXIMUM `constants`

##### Summary

RX_LOGICAL_MAXIMUM

<a name='F-CSLibrary-Antenna-RX_LOGICAL_MINIMUM'></a>
### RX_LOGICAL_MINIMUM `constants`

##### Summary

RX_LOGICAL_MINIMUM

<a name='F-CSLibrary-Antenna-TX_LOGICAL_MAXIMUM'></a>
### TX_LOGICAL_MAXIMUM `constants`

##### Summary

TX_LOGICAL_MAXIMUM

<a name='F-CSLibrary-Antenna-TX_LOGICAL_MINIMUM'></a>
### TX_LOGICAL_MINIMUM `constants`

##### Summary

TX_LOGICAL_MINIMUM

<a name='P-CSLibrary-Antenna-AntennaSenseThreshold'></a>
### AntennaSenseThreshold `property`

##### Summary

The measured resistance, specified in ohms, above which 
the antenna-sense resistance should be considered to be 
an open circuit (i.e., a disconnected antenna).  If it is 
detected that the antenna-sense resistance is above the 
threshold, the carrier wave will not be turned on in order 
to protect the circuit. 
NOTE:  This value, while appearing in the per-antenna 
configuration is actually a system-wide setting in the 
current release.  Changing it will Result in the value being 
changed for all antennas.  To prevent unintentionally 
changing this value for all antennas, it is best to first 
retrieve the antenna configuration for the antenna for 
which configuration will be changed, update the fields that 
should be changed, and then set the configuration.

<a name='P-CSLibrary-Antenna-AntennaSenseValue'></a>
### AntennaSenseValue `property`

##### Summary

The stored value from the last measurement of the 
antenna-sense resistor for the logical antenna port's 
physical transmit antenna port.  The last measurement 
taken occurred the last time that the carrier wave was 
turned on for this antenna port ¨C note that this means that 
when retrieving the logical antenna port's status, this does 
not Result in an active measurement of the antenna-sense 
resistor.  This value is specified in ohms.

<a name='P-CSLibrary-Antenna-DwellTime'></a>
### DwellTime `property`

##### Summary

Specifies the maximum amount of time, in milliseconds, 
that may be spent on the logical antenna port during a 
tag-protocol-operation cycle before switching to the next 
enabled antenna port.  A value of zero indicates that there 
is no maximum dwell time for this antenna port.  If this 
parameter is zero, then numberInventoryCycles may 
not be zero. 
See  for the effect of antenna-port dwell time and number 
of inventory cycles on the amount of time spent on an 
antenna port during a single tag-protocol-operation cycle. 
NOTE:  when performing any non-inventory ISO 18000-6C tag
access operation (i.e., read, write, kill, or lock), the
radio module ignores the dwell time for the antenna port 
which is used for the tag-protocol operation.

<a name='P-CSLibrary-Antenna-EASAlarm'></a>
### EASAlarm `property`

##### Summary

EAS Alarm

<a name='P-CSLibrary-Antenna-EnableLocalFreq'></a>
### EnableLocalFreq `property`

##### Summary

Enable local frequency

<a name='P-CSLibrary-Antenna-EnableLocalInv'></a>
### EnableLocalInv `property`

##### Summary

Enable local inventory parameter

<a name='P-CSLibrary-Antenna-EnableLocalProfile'></a>
### EnableLocalProfile `property`

##### Summary

Enable local link profile

<a name='P-CSLibrary-Antenna-FreqChannel'></a>
### FreqChannel `property`

##### Summary

Frequency channel

<a name='P-CSLibrary-Antenna-InventoryAlgorithm'></a>
### InventoryAlgorithm `property`

##### Summary

Inventory algorithm

<a name='P-CSLibrary-Antenna-LinkProfile'></a>
### LinkProfile `property`

##### Summary

LinkProfile

<a name='P-CSLibrary-Antenna-NumberInventoryCycles'></a>
### NumberInventoryCycles `property`

##### Summary

Specifies the maximum number of inventory cycles to 
attempt on the antenna port during a tag-protocol-
operation cycle before switching to the next enabled 
antenna port.  An inventory cycle consists of one or more 
executions of the singulation algorithm for a particular 
inventory-session target (i.e., A or B).  If the singulation 
algorithm [SING-ALG] is configured to toggle the 
inventory-session, executing the singulation algorithm for 
inventory session A and inventory session B counts as 
two inventory cycles.  A value of zero indicates that there 
is no maximum number of inventory cycles for this 
antenna port.  If this parameter is zero, then dwellTime 
may not be zero. 
See  for the effect of antenna-port dwell time and number 
of inventory cycles on the amount of time spent on an 
antenna port during a single tag-protocol-operation cycle. 
NOTE:  when performing any non-inventory ISO 18000-
6C tag access operation (i.e., read, write, kill, or lock), the 
radio module ignores the number of inventory cycles for 
the antenna port which is used for the tag-protocol 
operation.

<a name='P-CSLibrary-Antenna-PhysicalRxPort'></a>
### PhysicalRxPort `property`

##### Summary

The physical transmit port that this logical antenna port is 
mapped to.  Consult [MAC-EDS] for the valid physical 
receive antenna ports.  In version 1.1, when calling 
RFID_AntennaPortSetConfiguration this value 
must be the same as the value in physcialRxPort.

<a name='P-CSLibrary-Antenna-PhysicalTxPort'></a>
### PhysicalTxPort `property`

##### Summary

The physical receive port that this logical antenna port is 
mapped to.  Consult [MAC-EDS] for the valid physical 
receive antenna ports.  In version 1.1, when calling 
RFID_AntennaPortSetConfiguration this value 
must be the same as the value in physicalTxPort.

<a name='P-CSLibrary-Antenna-Port'></a>
### Port `property`

##### Summary

Antenna port number

<a name='P-CSLibrary-Antenna-PowerLevel'></a>
### PowerLevel `property`

##### Summary

The power level for the logical antenna port's physical 
transmit antenna.  This value is specified in 0.1 (i.e., 
1/10th) dBm. Note that all radio modules may not support 
setting an antenna port's power level at 1/10th dBm 
resolutions.  The dBm rounding/truncation policy is left to 
the radio module and is outside the scope of the RFID 
Reader Library.

<a name='P-CSLibrary-Antenna-StartQ'></a>
### StartQ `property`

##### Summary

Inventory StartQ

<a name='P-CSLibrary-Antenna-State'></a>
### State `property`

##### Summary

Get the state of the logical antenna port.

<a name='M-CSLibrary-Antenna-Copy-CSLibrary-Antenna-'></a>
### Copy(from) `method`

##### Summary

Copy from Antenna

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| from | [CSLibrary.Antenna](#T-CSLibrary-Antenna 'CSLibrary.Antenna') |  |

<a name='M-CSLibrary-Antenna-Equals-System-Object-'></a>
### Equals(obj) `method`

##### Summary

Check equal

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| obj | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') |  |

<a name='M-CSLibrary-Antenna-Equals-CSLibrary-Antenna-'></a>
### Equals(rhs) `method`

##### Summary

Check equal

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| rhs | [CSLibrary.Antenna](#T-CSLibrary-Antenna 'CSLibrary.Antenna') |  |

<a name='M-CSLibrary-Antenna-GetHashCode'></a>
### GetHashCode() `method`

##### Summary

TODO: provide real hash return value

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Antenna-Load-CSLibrary-HighLevelInterface-'></a>
### Load(transport) `method`

##### Summary

Load antenna port info

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| transport | [CSLibrary.HighLevelInterface](#T-CSLibrary-HighLevelInterface 'CSLibrary.HighLevelInterface') |  |

<a name='M-CSLibrary-Antenna-Store-CSLibrary-HighLevelInterface-'></a>
### Store(transport) `method`

##### Summary

Store antenna port info

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| transport | [CSLibrary.HighLevelInterface](#T-CSLibrary-HighLevelInterface 'CSLibrary.HighLevelInterface') |  |

<a name='T-CSLibrary-AntennaConfig'></a>
## AntennaConfig `type`

##### Namespace

CSLibrary

<a name='M-CSLibrary-AntennaConfig-#ctor-System-UInt32-'></a>
### #ctor(port) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| port | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |

<a name='M-CSLibrary-AntennaConfig-#ctor-CSLibrary-AntennaConfig-'></a>
### #ctor(source) `constructor`

##### Summary

Copy Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| source | [CSLibrary.AntennaConfig](#T-CSLibrary-AntennaConfig 'CSLibrary.AntennaConfig') |  |

<a name='P-CSLibrary-AntennaConfig-AntennaSenseThreshold'></a>
### AntennaSenseThreshold `property`

##### Summary

The measured resistance, specified in ohms, above which 
the antenna-sense resistance should be considered to be 
an open circuit (i.e., a disconnected antenna).  If it is 
detected that the antenna-sense resistance is above the 
threshold, the carrier wave will not be turned on in order 
to protect the circuit. 
NOTE:  This value, while appearing in the per-antenna 
configuration is actually a system-wide setting in the 
current release.  Changing it will Result in the value being 
changed for all antennas.  To prevent unintentionally 
changing this value for all antennas, it is best to first 
retrieve the antenna configuration for the antenna for 
which configuration will be changed, update the fields that 
should be changed, and then set the configuration.

<a name='P-CSLibrary-AntennaConfig-DwellTime'></a>
### DwellTime `property`

##### Summary

Specifies the maximum amount of time, in milliseconds, 
that may be spent on the logical antenna port during a 
tag-protocol-operation cycle before switching to the next 
enabled antenna port.  A value of zero indicates that there 
is no maximum dwell time for this antenna port.  If this 
parameter is zero, then numberInventoryCycles may 
not be zero. 
See  for the effect of antenna-port dwell time and number 
of inventory cycles on the amount of time spent on an 
antenna port during a single tag-protocol-operation cycle. 
NOTE:  when performing any non-inventory ISO 18000-6C tag
access operation (i.e., read, write, kill, or lock), the
radio module ignores the dwell time for the antenna port 
which is used for the tag-protocol operation.

<a name='P-CSLibrary-AntennaConfig-NumberInventoryCycles'></a>
### NumberInventoryCycles `property`

##### Summary

Specifies the maximum number of inventory cycles to 
attempt on the antenna port during a tag-protocol-
operation cycle before switching to the next enabled 
antenna port.  An inventory cycle consists of one or more 
executions of the singulation algorithm for a particular 
inventory-session target (i.e., A or B).  If the singulation 
algorithm [SING-ALG] is configured to toggle the 
inventory-session, executing the singulation algorithm for 
inventory session A and inventory session B counts as 
two inventory cycles.  A value of zero indicates that there 
is no maximum number of inventory cycles for this 
antenna port.  If this parameter is zero, then dwellTime 
may not be zero. 
See  for the effect of antenna-port dwell time and number 
of inventory cycles on the amount of time spent on an 
antenna port during a single tag-protocol-operation cycle. 
NOTE:  when performing any non-inventory ISO 18000-
6C tag access operation (i.e., read, write, kill, or lock), the 
radio module ignores the number of inventory cycles for 
the antenna port which is used for the tag-protocol 
operation.

<a name='P-CSLibrary-AntennaConfig-PhysicalRxPort'></a>
### PhysicalRxPort `property`

##### Summary

The physical transmit port that this logical antenna port is 
mapped to.  Consult [MAC-EDS] for the valid physical 
receive antenna ports.  In version 1.1, when calling 
RFID_AntennaPortSetConfiguration this value 
must be the same as the value in physcialRxPort.

<a name='P-CSLibrary-AntennaConfig-PhysicalTxPort'></a>
### PhysicalTxPort `property`

##### Summary

The physical receive port that this logical antenna port is 
mapped to.  Consult [MAC-EDS] for the valid physical 
receive antenna ports.  In version 1.1, when calling 
RFID_AntennaPortSetConfiguration this value 
must be the same as the value in physicalTxPort.

<a name='P-CSLibrary-AntennaConfig-Port'></a>
### Port `property`

##### Summary

Antenna port number

<a name='P-CSLibrary-AntennaConfig-PowerLevel'></a>
### PowerLevel `property`

##### Summary

The power level for the logical antenna port's physical 
transmit antenna.  This value is specified in 0.1 (i.e., 
1/10th) dBm. Note that all radio modules may not support 
setting an antenna port's power level at 1/10th dBm 
resolutions.  The dBm rounding/truncation policy is left to 
the radio module and is outside the scope of the RFID 
Reader Library.

<a name='M-CSLibrary-AntennaConfig-Copy-CSLibrary-AntennaConfig-'></a>
### Copy(from) `method`

##### Summary

Copy from AntennaConfig

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| from | [CSLibrary.AntennaConfig](#T-CSLibrary-AntennaConfig 'CSLibrary.AntennaConfig') |  |

<a name='M-CSLibrary-AntennaConfig-Equals-System-Object-'></a>
### Equals(obj) `method`

##### Summary

Check equal

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| obj | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') |  |

<a name='M-CSLibrary-AntennaConfig-Equals-CSLibrary-AntennaConfig-'></a>
### Equals(rhs) `method`

##### Summary

Check equal

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| rhs | [CSLibrary.AntennaConfig](#T-CSLibrary-AntennaConfig 'CSLibrary.AntennaConfig') |  |

<a name='M-CSLibrary-AntennaConfig-GetHashCode'></a>
### GetHashCode() `method`

##### Summary

TODO: provide real hash return value

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-AntennaConfig-Load-CSLibrary-HighLevelInterface-'></a>
### Load(transport) `method`

##### Summary

Load Antenna config from MAC

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| transport | [CSLibrary.HighLevelInterface](#T-CSLibrary-HighLevelInterface 'CSLibrary.HighLevelInterface') |  |

<a name='M-CSLibrary-AntennaConfig-Store-CSLibrary-HighLevelInterface-'></a>
### Store(transport) `method`

##### Summary

Store Antenna config to MAC

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| transport | [CSLibrary.HighLevelInterface](#T-CSLibrary-HighLevelInterface 'CSLibrary.HighLevelInterface') |  |

<a name='T-CSLibrary-AntennaList'></a>
## AntennaList `type`

##### Namespace

CSLibrary

<a name='M-CSLibrary-AntennaList-#ctor'></a>
### #ctor() `constructor`

##### Summary

Create an empty antenna list

##### Parameters

This constructor has no parameters.

<a name='M-CSLibrary-AntennaList-#ctor-System-Int32-'></a>
### #ctor(capacity) `constructor`

##### Summary

Create an empty antenna list with initial capacity

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| capacity | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |

<a name='M-CSLibrary-AntennaList-#ctor-System-Collections-Generic-IEnumerable{CSLibrary-Antenna}-'></a>
### #ctor(enumerable) `constructor`

##### Summary

Copy an antenna list ~ no checks for dup ports

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| enumerable | [System.Collections.Generic.IEnumerable{CSLibrary.Antenna}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{CSLibrary.Antenna}') |  |

<a name='M-CSLibrary-AntennaList-#ctor-System-Collections-Generic-IEnumerable{CSLibrary-Antenna},System-Boolean-'></a>
### #ctor(enumerable,deepCopy) `constructor`

##### Summary

Copy an antenna list ~ performing a DEEP copy of
antennas if indicated

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| enumerable | [System.Collections.Generic.IEnumerable{CSLibrary.Antenna}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{CSLibrary.Antenna}') |  |
| deepCopy | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') |  |

<a name='F-CSLibrary-AntennaList-DEFAULT_ANTENNA_LIST'></a>
### DEFAULT_ANTENNA_LIST `constants`

##### Summary

Default antenna list

<a name='T-CSLibrary-Constants-AntennaPort'></a>
## AntennaPort `type`

##### Namespace

CSLibrary.Constants

##### Summary

Antenna Port Number

<a name='F-CSLibrary-Constants-AntennaPort-PORT_00'></a>
### PORT_00 `constants`

##### Summary

Physical Port 0

<a name='F-CSLibrary-Constants-AntennaPort-PORT_01'></a>
### PORT_01 `constants`

##### Summary

Physical Port 1

<a name='F-CSLibrary-Constants-AntennaPort-PORT_02'></a>
### PORT_02 `constants`

##### Summary

Physical Port 2

<a name='F-CSLibrary-Constants-AntennaPort-PORT_03'></a>
### PORT_03 `constants`

##### Summary

Physical Port 3

<a name='F-CSLibrary-Constants-AntennaPort-PORT_04'></a>
### PORT_04 `constants`

##### Summary

Physical Port 4

<a name='F-CSLibrary-Constants-AntennaPort-PORT_05'></a>
### PORT_05 `constants`

##### Summary

Physical Port 5

<a name='F-CSLibrary-Constants-AntennaPort-PORT_06'></a>
### PORT_06 `constants`

##### Summary

Physical Port 6

<a name='F-CSLibrary-Constants-AntennaPort-PORT_07'></a>
### PORT_07 `constants`

##### Summary

Physical Port 7

<a name='F-CSLibrary-Constants-AntennaPort-PORT_08'></a>
### PORT_08 `constants`

##### Summary

Physical Port 8

<a name='F-CSLibrary-Constants-AntennaPort-PORT_09'></a>
### PORT_09 `constants`

##### Summary

Physical Port 9

<a name='F-CSLibrary-Constants-AntennaPort-PORT_10'></a>
### PORT_10 `constants`

##### Summary

Physical Port 10

<a name='F-CSLibrary-Constants-AntennaPort-PORT_11'></a>
### PORT_11 `constants`

##### Summary

Physical Port 11

<a name='F-CSLibrary-Constants-AntennaPort-PORT_12'></a>
### PORT_12 `constants`

##### Summary

Physical Port 12

<a name='F-CSLibrary-Constants-AntennaPort-PORT_13'></a>
### PORT_13 `constants`

##### Summary

Physical Port 13

<a name='F-CSLibrary-Constants-AntennaPort-PORT_14'></a>
### PORT_14 `constants`

##### Summary

Physical Port 14

<a name='F-CSLibrary-Constants-AntennaPort-PORT_15'></a>
### PORT_15 `constants`

##### Summary

Physical Port 15

<a name='F-CSLibrary-Constants-AntennaPort-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown Port Number

<a name='T-CSLibrary-Structures-AntennaPortCollections'></a>
## AntennaPortCollections `type`

##### Namespace

CSLibrary.Structures

##### Summary

Antenna Port collections

<a name='M-CSLibrary-Structures-AntennaPortCollections-#ctor'></a>
### #ctor() `constructor`

##### Summary

Initializes a new instance of the AntennaPortCollections class
that is empty and has the default initial capacity.

##### Parameters

This constructor has no parameters.

<a name='M-CSLibrary-Structures-AntennaPortCollections-#ctor-System-Int32-'></a>
### #ctor(capacity) `constructor`

##### Summary

Initializes a new instance of the AntennaPortCollections class
that is empty and has the specified initial capacity.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| capacity | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | The number of elements that the new list can initially store. |

<a name='M-CSLibrary-Structures-AntennaPortCollections-#ctor-System-Collections-Generic-IEnumerable{CSLibrary-Constants-AntennaPort}-'></a>
### #ctor(collection) `constructor`

##### Summary

Initializes a new instance of the AntennaPortCollections class
that contains elements copied from the specified collection and has sufficient
capacity to accommodate the number of elements copied.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| collection | [System.Collections.Generic.IEnumerable{CSLibrary.Constants.AntennaPort}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{CSLibrary.Constants.AntennaPort}') | The collection whose elements are copied to the new list. |

<a name='T-CSLibrary-Structures-AntennaPortConfig'></a>
## AntennaPortConfig `type`

##### Namespace

CSLibrary.Structures

##### Summary

When configuring or retrieving the configuration for logical antenna ports, an 
application has several parameters that it can set/retrieve.

<a name='M-CSLibrary-Structures-AntennaPortConfig-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-AntennaPortConfig-antennaSenseThreshold'></a>
### antennaSenseThreshold `constants`

##### Summary

The measured resistance, specified in ohms, above which 
the antenna-sense resistance should be considered to be 
an open circuit (i.e., a disconnected antenna).  If it is 
detected that the antenna-sense resistance is above the 
threshold, the carrier wave will not be turned on in order 
to protect the circuit. 
NOTE:  This value, while appearing in the per-antenna 
configuration is actually a system-wide setting in the 
current release.  Changing it will Result in the value being 
changed for all antennas.  To prevent unintentionally 
changing this value for all antennas, it is best to first 
retrieve the antenna configuration for the antenna for 
which configuration will be changed, update the fields that 
should be changed, and then set the configuration.

<a name='F-CSLibrary-Structures-AntennaPortConfig-dwellTime'></a>
### dwellTime `constants`

##### Summary

Specifies the maximum amount of time, in milliseconds, 
that may be spent on the logical antenna port during a 
tag-protocol-operation cycle before switching to the next 
enabled antenna port.  A value of zero indicates that there 
is no maximum dwell time for this antenna port.  If this 
parameter is zero, then numberInventoryCycles may 
not be zero. 
See  for the effect of antenna-port dwell time and number 
of inventory cycles on the amount of time spent on an 
antenna port during a single tag-protocol-operation cycle. 
NOTE:  when performing any non-inventory ISO 18000-6C tag
access operation (i.e., read, write, kill, or lock), the
radio module ignores the dwell time for the antenna port 
which is used for the tag-protocol operation.

<a name='F-CSLibrary-Structures-AntennaPortConfig-length_'></a>
### length_ `constants`

##### Summary

Structure size

<a name='F-CSLibrary-Structures-AntennaPortConfig-numberInventoryCycles'></a>
### numberInventoryCycles `constants`

##### Summary

Specifies the maximum number of inventory cycles to 
attempt on the antenna port during a tag-protocol-
operation cycle before switching to the next enabled 
antenna port.  An inventory cycle consists of one or more 
executions of the singulation algorithm for a particular 
inventory-session target (i.e., A or B).  If the singulation 
algorithm [SING-ALG] is configured to toggle the 
inventory-session, executing the singulation algorithm for 
inventory session A and inventory session B counts as 
two inventory cycles.  A value of zero indicates that there 
is no maximum number of inventory cycles for this 
antenna port.  If this parameter is zero, then dwellTime 
may not be zero. 
See  for the effect of antenna-port dwell time and number 
of inventory cycles on the amount of time spent on an 
antenna port during a single tag-protocol-operation cycle. 
NOTE:  when performing any non-inventory ISO 18000-
6C tag access operation (i.e., read, write, kill, or lock), the 
radio module ignores the number of inventory cycles for 
the antenna port which is used for the tag-protocol 
operation.

<a name='F-CSLibrary-Structures-AntennaPortConfig-physicalRxPort'></a>
### physicalRxPort `constants`

##### Summary

The physical receive port that this logical antenna port is 
mapped to.  Consult [MAC-EDS] for the valid physical 
receive antenna ports.  In version 1.1, when calling 
RFID_AntennaPortSetConfiguration this value 
must be the same as the value in physicalTxPort.

<a name='F-CSLibrary-Structures-AntennaPortConfig-physicalTxPort'></a>
### physicalTxPort `constants`

##### Summary

The physical transmit port that this logical antenna port is 
mapped to.  Consult [MAC-EDS] for the valid physical 
receive antenna ports.  In version 1.1, when calling 
RFID_AntennaPortSetConfiguration this value 
must be the same as the value in physcialRxPort.

<a name='F-CSLibrary-Structures-AntennaPortConfig-powerLevel'></a>
### powerLevel `constants`

##### Summary

The power level for the logical antenna port's physical 
transmit antenna.  This value is specified in 0.1 (i.e., 
1/10th) dBm. Note that all radio modules may not support 
setting an antenna port's power level at 1/10th dBm 
resolutions.  The dBm rounding/truncation policy is left to 
the radio module and is outside the scope of the RFID 
Reader Library.

<a name='P-CSLibrary-Structures-AntennaPortConfig-length'></a>
### length `property`

##### Summary

Structure size

<a name='T-CSLibrary-Constants-AntennaPortState'></a>
## AntennaPortState `type`

##### Namespace

CSLibrary.Constants

##### Summary

Indicates the state of the logical antenna port.

<a name='F-CSLibrary-Constants-AntennaPortState-DISABLED'></a>
### DISABLED `constants`

##### Summary

Disable Port

<a name='F-CSLibrary-Constants-AntennaPortState-ENABLED'></a>
### ENABLED `constants`

##### Summary

Enable Port

<a name='F-CSLibrary-Constants-AntennaPortState-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown action

<a name='T-CSLibrary-Structures-AntennaPortStatus'></a>
## AntennaPortStatus `type`

##### Namespace

CSLibrary.Structures

##### Summary

The structure used to retrieve the status for a logical antenna port is defined as 
follows:

<a name='M-CSLibrary-Structures-AntennaPortStatus-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-AntennaPortStatus-antennaSenseValue'></a>
### antennaSenseValue `constants`

##### Summary

The stored value from the last measurement of the 
antenna-sense resistor for the logical antenna port's 
physical transmit antenna port.  The last measurement 
taken occurred the last time that the carrier wave was 
turned on for this antenna port – note that this means that 
when retrieving the logical antenna port's status, this does 
not Result in an active measurement of the antenna-sense 
resistor.  This value is specified in ohms.

<a name='F-CSLibrary-Structures-AntennaPortStatus-easAlarm'></a>
### easAlarm `constants`

##### Summary

EAS Alarm

<a name='F-CSLibrary-Structures-AntennaPortStatus-enableLocalFreq'></a>
### enableLocalFreq `constants`

##### Summary

Enable Local frequency

<a name='F-CSLibrary-Structures-AntennaPortStatus-enableLocalInv'></a>
### enableLocalInv `constants`

##### Summary

Enable local Inventory parameter.

<a name='F-CSLibrary-Structures-AntennaPortStatus-enableLocalProfile'></a>
### enableLocalProfile `constants`

##### Summary

Enable local profile

<a name='F-CSLibrary-Structures-AntennaPortStatus-freqChn'></a>
### freqChn `constants`

##### Summary

frequency channel to use.

<a name='F-CSLibrary-Structures-AntennaPortStatus-inv_algo'></a>
### inv_algo `constants`

##### Summary

Inventory local parameter

<a name='F-CSLibrary-Structures-AntennaPortStatus-length_'></a>
### length_ `constants`

##### Summary

Structure size

<a name='F-CSLibrary-Structures-AntennaPortStatus-profile'></a>
### profile `constants`

##### Summary

Link Profile

<a name='F-CSLibrary-Structures-AntennaPortStatus-startQ'></a>
### startQ `constants`

##### Summary

Inventory local parameter

<a name='F-CSLibrary-Structures-AntennaPortStatus-state'></a>
### state `constants`

##### Summary

Indicates the state of the logical antenna port.

<a name='P-CSLibrary-Structures-AntennaPortStatus-length'></a>
### length `property`

##### Summary

Structure size

<a name='T-CSLibrary-Constants-AntennaSequenceMode'></a>
## AntennaSequenceMode `type`

##### Namespace

CSLibrary.Constants

##### Summary

AntennaSequenceMode

<a name='F-CSLibrary-Constants-AntennaSequenceMode-NORMAL'></a>
### NORMAL `constants`

##### Summary

Normal mode

<a name='F-CSLibrary-Constants-AntennaSequenceMode-SEQUENCE'></a>
### SEQUENCE `constants`

##### Summary

Sequence Mode

<a name='F-CSLibrary-Constants-AntennaSequenceMode-SEQUENCE_SMART_CHECK'></a>
### SEQUENCE_SMART_CHECK `constants`

##### Summary

Combination of Sequence and Smart Check

<a name='F-CSLibrary-Constants-AntennaSequenceMode-SMART_CHECK'></a>
### SMART_CHECK `constants`

##### Summary

Smart check mode

<a name='F-CSLibrary-Constants-AntennaSequenceMode-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown

<a name='T-CSLibrary-AntennaStatus'></a>
## AntennaStatus `type`

##### Namespace

CSLibrary

##### Summary

Antenna Status

<a name='M-CSLibrary-AntennaStatus-#ctor-System-UInt32-'></a>
### #ctor(port) `constructor`

##### Summary

Constructor
designed to init for loading from radio

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| port | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Valid port from 0 - 15 |

<a name='M-CSLibrary-AntennaStatus-#ctor-CSLibrary-AntennaStatus-'></a>
### #ctor(source) `constructor`

##### Summary

Copy Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| source | [CSLibrary.AntennaStatus](#T-CSLibrary-AntennaStatus 'CSLibrary.AntennaStatus') |  |

<a name='P-CSLibrary-AntennaStatus-AntennaSenseValue'></a>
### AntennaSenseValue `property`

##### Summary

The stored value from the last measurement of the 
antenna-sense resistor for the logical antenna port's 
physical transmit antenna port.  The last measurement 
taken occurred the last time that the carrier wave was 
turned on for this antenna port ¨C note that this means that 
when retrieving the logical antenna port's status, this does 
not Result in an active measurement of the antenna-sense 
resistor.  This value is specified in ohms.

<a name='P-CSLibrary-AntennaStatus-Port'></a>
### Port `property`

##### Summary

Get current port number

<a name='P-CSLibrary-AntennaStatus-State'></a>
### State `property`

##### Summary

Get the state of the logical antenna port.

<a name='M-CSLibrary-AntennaStatus-Copy-CSLibrary-AntennaStatus-'></a>
### Copy(from) `method`

##### Summary

Copy from AntennaStatus

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| from | [CSLibrary.AntennaStatus](#T-CSLibrary-AntennaStatus 'CSLibrary.AntennaStatus') |  |

<a name='M-CSLibrary-AntennaStatus-Equals-System-Object-'></a>
### Equals(obj) `method`

##### Summary

check equal

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| obj | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') |  |

<a name='M-CSLibrary-AntennaStatus-Equals-CSLibrary-AntennaStatus-'></a>
### Equals(rhs) `method`

##### Summary

check equal

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| rhs | [CSLibrary.AntennaStatus](#T-CSLibrary-AntennaStatus 'CSLibrary.AntennaStatus') |  |

<a name='M-CSLibrary-AntennaStatus-GetHashCode'></a>
### GetHashCode() `method`

##### Summary

TODO: provide real hash return value

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-AntennaStatus-Load-CSLibrary-HighLevelInterface-'></a>
### Load(transport) `method`

##### Summary

Load Antenna Status from MAC

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| transport | [CSLibrary.HighLevelInterface](#T-CSLibrary-HighLevelInterface 'CSLibrary.HighLevelInterface') |  |

<a name='M-CSLibrary-AntennaStatus-Store-CSLibrary-HighLevelInterface-'></a>
### Store(transport) `method`

##### Summary

Store Antenna Status to MAC

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| transport | [CSLibrary.HighLevelInterface](#T-CSLibrary-HighLevelInterface 'CSLibrary.HighLevelInterface') |  |

<a name='T-CSLibrary-Net-AssignResult'></a>
## AssignResult `type`

##### Namespace

CSLibrary.Net

##### Summary

Result

<a name='F-CSLibrary-Net-AssignResult-ACCEPTED'></a>
### ACCEPTED `constants`

##### Summary

Accepted from device

<a name='F-CSLibrary-Net-AssignResult-REJECTED'></a>
### REJECTED `constants`

##### Summary

Rejected from device

<a name='F-CSLibrary-Net-AssignResult-STARTED'></a>
### STARTED `constants`

##### Summary

assignment started, please wait to finished

<a name='F-CSLibrary-Net-AssignResult-TIMEOUT'></a>
### TIMEOUT `constants`

##### Summary

response timeout

<a name='F-CSLibrary-Net-AssignResult-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown

<a name='T-CSLibrary-Structures-BNK1_MSK_FILTER_CFG'></a>
## BNK1_MSK_FILTER_CFG `type`

##### Namespace

CSLibrary.Structures

##### Summary

The host writes mask filter to enable matching of the bank 1 read.

<a name='M-CSLibrary-Structures-BNK1_MSK_FILTER_CFG-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='M-CSLibrary-Structures-BNK1_MSK_FILTER_CFG-#ctor-System-String-'></a>
### #ctor() `constructor`

##### Summary

Constructor
default 
enable = true
match = true
offset = 0

##### Parameters

This constructor has no parameters.

<a name='M-CSLibrary-Structures-BNK1_MSK_FILTER_CFG-#ctor-System-Boolean,System-Boolean,System-Int32,System-String-'></a>
### #ctor(enable,match,offset,count) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| enable | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') | Bank 1 mask filter enabled |
| match | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') | Determines if the associated tag-protocol operation will be 
applied to tags that match the mask or not.  A non-zero 
value indicates that the tag-protocol operation should be 
applied to tags that match the mask.  A value of zero 
indicates that the tag-protocol operation should be applied 
to tags that do not match the mask. |
| offset | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | The offset in bits, from the start of the bank 1 (PC + EPC)
, of the first bit that will be matched against the 
mask.  If offset falls beyond the end of bank 1, the tag is 
considered non-matching. |
| count | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The number of bits in the mask.  A length of zero will cause 
all tags to match.  If (offset+count) falls beyond the end 
of the bank 1, the tag is considered non-matching.  Valid 
values are 0 to 511, inclusive. |

<a name='F-CSLibrary-Structures-BNK1_MSK_FILTER_CFG-enable'></a>
### enable `constants`

##### Summary

Bank 1 mask matching enabled

<a name='F-CSLibrary-Structures-BNK1_MSK_FILTER_CFG-length'></a>
### length `constants`

##### Summary

The number of bits in the mask from offset 0.  A length of zero will cause 
all tags to match.  If (offset+count) falls beyond the end 
of the bank 1, the tag is considered non-matching.  Valid 
values are 0 to 512, inclusive.

<a name='F-CSLibrary-Structures-BNK1_MSK_FILTER_CFG-mask'></a>
### mask `constants`

##### Summary

bank 1 mask, accept "0", "1", and other value is don't care

<a name='F-CSLibrary-Structures-BNK1_MSK_FILTER_CFG-match'></a>
### match `constants`

##### Summary

Determines if the associated tag-protocol operation will be 
applied to tags that match the mask or not.  A non-zero 
value indicates that the tag-protocol operation should be 
applied to tags that match the mask.  A value of zero 
indicates that the tag-protocol operation should be applied 
to tags that do not match the mask.

<a name='F-CSLibrary-Structures-BNK1_MSK_FILTER_CFG-offset'></a>
### offset `constants`

##### Summary

The offset in bits, from the start of the Bank 1 (PC + EPC)
, of the first bit that will be matched against the 
mask.  If offset falls beyond the end of Bank 1, the tag is 
considered non-matching.

<a name='T-CSLibrary-Constants-BandState'></a>
## BandState `type`

##### Namespace

CSLibrary.Constants

##### Summary

Frequency Band State

<a name='F-CSLibrary-Constants-BandState-DISABLE'></a>
### DISABLE `constants`

##### Summary

Disable

<a name='F-CSLibrary-Constants-BandState-ENABLE'></a>
### ENABLE `constants`

##### Summary

Enable

<a name='F-CSLibrary-Constants-BandState-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknow

<a name='T-CSLibrary-Constants-Bank'></a>
## Bank `type`

##### Namespace

CSLibrary.Constants

##### Summary

Memory bank

<a name='F-CSLibrary-Constants-Bank-ACC_PWD'></a>
### ACC_PWD `constants`

##### Summary

Access password

<a name='F-CSLibrary-Constants-Bank-EPC'></a>
### EPC `constants`

##### Summary

Electronic Product Code

<a name='F-CSLibrary-Constants-Bank-KILL_PWD'></a>
### KILL_PWD `constants`

##### Summary

Kill password

<a name='F-CSLibrary-Constants-Bank-PC'></a>
### PC `constants`

##### Summary

Protocol Control

<a name='F-CSLibrary-Constants-Bank-SPECIAL'></a>
### SPECIAL `constants`

##### Summary

Special bank

<a name='F-CSLibrary-Constants-Bank-TID'></a>
### TID `constants`

##### Summary

Transponder ID

<a name='F-CSLibrary-Constants-Bank-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown bank

<a name='F-CSLibrary-Constants-Bank-USER'></a>
### USER `constants`

##### Summary

User memory

<a name='T-CSLibrary-Structures-BatteryType'></a>
## BatteryType `type`

##### Namespace

CSLibrary.Structures

##### Summary

Battery Type

<a name='F-CSLibrary-Structures-BatteryType-B1_5V'></a>
### B1_5V `constants`

##### Summary

1.5V

<a name='F-CSLibrary-Structures-BatteryType-B3V'></a>
### B3V `constants`

##### Summary

3V

<a name='T-CSLibrary-Structures-BlockEraseCmdParms'></a>
## BlockEraseCmdParms `type`

##### Namespace

CSLibrary.Structures

<a name='M-CSLibrary-Structures-BlockEraseCmdParms-#ctor-CSLibrary-Constants-MemoryBank,System-UInt16,System-UInt16-'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-BlockEraseCmdParms-bank'></a>
### bank `constants`

##### Summary

The memory bank from which to write.  Valid values are: 
MemoryBank.RESERVED 
MemoryBank.EPC  
MemoryBank.TID 
MemoryBank.USER

<a name='F-CSLibrary-Structures-BlockEraseCmdParms-count'></a>
### count `constants`

##### Summary

The number of 16-bit words to be written to the tag's specified memory 
bank.  For version 1.2 of the RFID Reader Library, this parameter must 
contain a value between 1 and 255, inclusive.

<a name='F-CSLibrary-Structures-BlockEraseCmdParms-offset'></a>
### offset `constants`

##### Summary

The number of 16-bit words that will be written.  This field must be 
between 1 and 32, inclusive.

<a name='T-CSLibrary-Structures-BlockEraseParms'></a>
## BlockEraseParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Tag Erase

<a name='T-CSLibrary-Structures-BlockWriteCmdParms'></a>
## BlockWriteCmdParms `type`

##### Namespace

CSLibrary.Structures

<a name='M-CSLibrary-Structures-BlockWriteCmdParms-#ctor-CSLibrary-Constants-MemoryBank,System-UInt16,System-UInt16,System-UInt16[]-'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-BlockWriteCmdParms-bank'></a>
### bank `constants`

##### Summary

The memory bank from which to write.  Valid values are: 
MemoryBank.RESERVED 
MemoryBank.EPC  
MemoryBank.TID 
MemoryBank.USER

<a name='F-CSLibrary-Structures-BlockWriteCmdParms-count'></a>
### count `constants`

##### Summary

The number of 16-bit words to be written to the tag's specified memory 
bank.  For version 1.2 of the RFID Reader Library, this parameter must 
contain a value between 1 and 255, inclusive.

<a name='F-CSLibrary-Structures-BlockWriteCmdParms-offset'></a>
### offset `constants`

##### Summary

The number of 16-bit words that will be written.  This field must be 
between 1 and 32, inclusive.

<a name='F-CSLibrary-Structures-BlockWriteCmdParms-pData'></a>
### pData `constants`

##### Summary

A buffer of count 16-bit values to be written 
sequentially to the tag's specified memory bank.  The high-order 
byte of pData[n] will be written to the tag's memory-bank byte at 
16-bit offset (offset+n).  The low-order byte will be written to the 
next byte.  For example, if offset is 2 and pData[0] is 0x1122, 
then the tag-memory byte at 16-bit offset 2 (byte offset 4) will have 
0x11 written to it and the next byte (byte offset 5) will have 0x22 
written to it.  This field must not be NULL.

<a name='M-CSLibrary-Structures-BlockWriteCmdParms-Dispose'></a>
### Dispose() `method`

##### Summary

Release all resources

##### Parameters

This method has no parameters.

<a name='T-CSLibrary-Structures-BlockWriteParms'></a>
## BlockWriteParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

A tag block-write command allows an application to write one or more 16-bit 
words to the specified memory bank of the ISO 18000-6C tags of interest.  The 
data returned from the block write will adhere to the format specified in [REC].  A 
Write can be performed on a contiguous set of one or more 16-bit words to one 
of the tag's memory banks.

<a name='F-CSLibrary-Structures-BlockWriteParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no access 
password.

<a name='F-CSLibrary-Structures-BlockWriteParms-blockWriteCmdParms'></a>
### blockWriteCmdParms `constants`

##### Summary

The ISO 18000-6C block write specific command paramters

<a name='F-CSLibrary-Structures-BlockWriteParms-common'></a>
### common `constants`

##### Summary

The common tag-protocol operation parameters.

<a name='F-CSLibrary-Structures-BlockWriteParms-length'></a>
### length `constants`

##### Summary

Structure size

<a name='T-CSLibrary-Structures-CLAccessFifoParms'></a>
## CLAccessFifoParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

CLAccessFifoParms

<a name='M-CSLibrary-Structures-CLAccessFifoParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-CLAccessFifoParms-AccessFIFOData'></a>
### AccessFIFOData `constants`

##### Summary

Get Sensor Value Response Data

<a name='T-CSLibrary-Structures-CLGetBatLvParms'></a>
## CLGetBatLvParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

CLGetBatLvParms

<a name='M-CSLibrary-Structures-CLGetBatLvParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-CLGetBatLvParms-BatLvData'></a>
### BatLvData `constants`

##### Summary

Get Battery Level Response Data

<a name='P-CSLibrary-Structures-CLGetBatLvParms-BatteryLevel'></a>
### BatteryLevel `property`

##### Summary

Battery volatge (V)

<a name='P-CSLibrary-Structures-CLGetBatLvParms-BatteryValue'></a>
### BatteryValue `property`

##### Summary

Battery A/D Value (0-1023)

<a name='T-CSLibrary-Structures-CLGetCalDataParms'></a>
## CLGetCalDataParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Read TID structures, configure this before read current TID

<a name='M-CSLibrary-Structures-CLGetCalDataParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-CLGetCalDataParms-CalData'></a>
### CalData `constants`

##### Summary

Response Data

<a name='T-CSLibrary-Structures-CLGetLogStateParms'></a>
## CLGetLogStateParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Get Log State

<a name='M-CSLibrary-Structures-CLGetLogStateParms-#ctor'></a>
### #ctor() `constructor`

##### Summary



##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-CLGetLogStateParms-LogStateData'></a>
### LogStateData `constants`

##### Summary

Response Data

<a name='P-CSLibrary-Structures-CLGetLogStateParms-ADErr'></a>
### ADErr `property`

##### Summary

A/D Error

<a name='P-CSLibrary-Structures-CLGetLogStateParms-ExtLower'></a>
### ExtLower `property`

##### Summary



<a name='P-CSLibrary-Structures-CLGetLogStateParms-MeasurementAddressPointer'></a>
### MeasurementAddressPointer `property`

##### Summary

Measurement Address Pointer

<a name='P-CSLibrary-Structures-CLGetLogStateParms-NumberOfMeasurements'></a>
### NumberOfMeasurements `property`

##### Summary

Number Of Measurements

<a name='P-CSLibrary-Structures-CLGetLogStateParms-NumberOfMemoryReplacements'></a>
### NumberOfMemoryReplacements `property`

##### Summary

Number Of Memory Replacements

<a name='P-CSLibrary-Structures-CLGetLogStateParms-ShelfLifeHighError'></a>
### ShelfLifeHighError `property`

##### Summary

Shelf Life High Error

<a name='T-CSLibrary-Structures-CLGetMesurementSetupParms'></a>
## CLGetMesurementSetupParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Get Mesurement Setup Response Data

<a name='M-CSLibrary-Structures-CLGetMesurementSetupParms-#ctor'></a>
### #ctor() `constructor`

##### Summary



##### Parameters

This constructor has no parameters.

<a name='P-CSLibrary-Structures-CLGetMesurementSetupParms-StartTime'></a>
### StartTime `property`

##### Summary

Get Response Data

<a name='T-CSLibrary-Structures-CLGetSensorValueParms'></a>
## CLGetSensorValueParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

CLGetSensorValueParms

<a name='F-CSLibrary-Structures-CLGetSensorValueParms-SensorValueData'></a>
### SensorValueData `constants`

##### Summary

Get Sensor Value Response Data

<a name='P-CSLibrary-Structures-CLGetSensorValueParms-ADError'></a>
### ADError `property`

##### Summary

A/D Error

<a name='P-CSLibrary-Structures-CLGetSensorValueParms-RangeLimit'></a>
### RangeLimit `property`

##### Summary

RangeLimit (0-31)

<a name='P-CSLibrary-Structures-CLGetSensorValueParms-SensorType'></a>
### SensorType `property`

##### Summary

Sensor Type

<a name='P-CSLibrary-Structures-CLGetSensorValueParms-SensorValue'></a>
### SensorValue `property`

##### Summary

Sensor Value (0-1023)

<a name='T-CSLibrary-Structures-CLInitParms'></a>
## CLInitParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

CLInitParms

<a name='M-CSLibrary-Structures-CLInitParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

constructor

##### Parameters

This constructor has no parameters.

<a name='P-CSLibrary-Structures-CLInitParms-DelayMode'></a>
### DelayMode `property`

##### Summary

Delay Time

<a name='P-CSLibrary-Structures-CLInitParms-DelayTime'></a>
### DelayTime `property`

##### Summary

Delay Time

<a name='P-CSLibrary-Structures-CLInitParms-TimerEnable'></a>
### TimerEnable `property`

##### Summary

Delay Time

<a name='T-CSLibrary-Structures-CLOpenAreaParms'></a>
## CLOpenAreaParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

CLOpenAreaParms

<a name='M-CSLibrary-Structures-CLOpenAreaParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

constructor

##### Parameters

This constructor has no parameters.

<a name='T-CSLibrary-Structures-CLSetCalDataParms'></a>
## CLSetCalDataParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

CLSetCalDataParms

<a name='T-CSLibrary-Structures-CLSetLogLimitsParms'></a>
## CLSetLogLimitsParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

CLSetLogLimitsParms

<a name='M-CSLibrary-Structures-CLSetLogLimitsParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

constructor

##### Parameters

This constructor has no parameters.

<a name='T-CSLibrary-Structures-CLSetLogModeParms'></a>
## CLSetLogModeParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

CLSetLogModeParms

<a name='M-CSLibrary-Structures-CLSetLogModeParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

constructor

##### Parameters

This constructor has no parameters.

<a name='P-CSLibrary-Structures-CLSetLogModeParms-BatteryCheckEnable'></a>
### BatteryCheckEnable `property`

##### Summary

Battery Check

<a name='P-CSLibrary-Structures-CLSetLogModeParms-Ext1SensorEnable'></a>
### Ext1SensorEnable `property`

##### Summary

External 1 sensor enable

<a name='P-CSLibrary-Structures-CLSetLogModeParms-Ext2SensorEnable'></a>
### Ext2SensorEnable `property`

##### Summary

External 2 sensor enable

<a name='P-CSLibrary-Structures-CLSetLogModeParms-LogInterval'></a>
### LogInterval `property`

##### Summary

Log interval seconds (0-32767)

<a name='P-CSLibrary-Structures-CLSetLogModeParms-StorageRule'></a>
### StorageRule `property`

##### Summary

Storage Rule (0 or 1)

<a name='P-CSLibrary-Structures-CLSetLogModeParms-TempSensorEnable'></a>
### TempSensorEnable `property`

##### Summary

Temp sensor enable

<a name='T-CSLibrary-Structures-CLSetPasswordParms'></a>
## CLSetPasswordParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

CLSetPasswordParms

<a name='M-CSLibrary-Structures-CLSetPasswordParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

constructor

##### Parameters

This constructor has no parameters.

<a name='P-CSLibrary-Structures-CLSetPasswordParms-Password'></a>
### Password `property`

##### Summary

Password

<a name='P-CSLibrary-Structures-CLSetPasswordParms-PasswordLevel'></a>
### PasswordLevel `property`

##### Summary

Password Level

<a name='T-CSLibrary-Structures-CLSetSFEParaParms'></a>
## CLSetSFEParaParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

CLSetSFEParaParms

<a name='P-CSLibrary-Structures-CLSetSFEParaParms-AutorangeDisable'></a>
### AutorangeDisable `property`

##### Summary

Range preset

<a name='P-CSLibrary-Structures-CLSetSFEParaParms-EXT1'></a>
### EXT1 `property`

##### Summary

Extenal sensor 1 type

<a name='P-CSLibrary-Structures-CLSetSFEParaParms-EXT2'></a>
### EXT2 `property`

##### Summary

Extenal sensor 2 type

<a name='P-CSLibrary-Structures-CLSetSFEParaParms-Rang'></a>
### Rang `property`

##### Summary

Resistor feedback ladder

<a name='P-CSLibrary-Structures-CLSetSFEParaParms-Seti'></a>
### Seti `property`

##### Summary

Current Source value (0.25uA pre step)

<a name='P-CSLibrary-Structures-CLSetSFEParaParms-VerigfySensorID'></a>
### VerigfySensorID `property`

##### Summary

Verify Sensor ID (0 - 3)

<a name='T-CSLibrary-Structures-CLSetShelfLifeParms'></a>
## CLSetShelfLifeParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

CLSetShelfLifeParms

<a name='M-CSLibrary-Structures-CLSetShelfLifeParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

constructor

##### Parameters

This constructor has no parameters.

<a name='T-CSLibrary-Structures-CLStartLogParms'></a>
## CLStartLogParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

CLStartLogParms

<a name='M-CSLibrary-Structures-CLStartLogParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

constructor

##### Parameters

This constructor has no parameters.

<a name='P-CSLibrary-Structures-CLStartLogParms-Day'></a>
### Day `property`

##### Summary

Day (1-31)

<a name='P-CSLibrary-Structures-CLStartLogParms-Hour'></a>
### Hour `property`

##### Summary

Hour (0-23)

<a name='P-CSLibrary-Structures-CLStartLogParms-Minute'></a>
### Minute `property`

##### Summary

Minute (0-59)

<a name='P-CSLibrary-Structures-CLStartLogParms-Month'></a>
### Month `property`

##### Summary

Month (1-12)

<a name='P-CSLibrary-Structures-CLStartLogParms-Second'></a>
### Second `property`

##### Summary

Second (0-59)

<a name='P-CSLibrary-Structures-CLStartLogParms-Year'></a>
### Year `property`

##### Summary

Year (0-63)

<a name='T-CSLibrary-Structures-CSLibraryOperationParms'></a>
## CSLibraryOperationParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Operation Paramemter

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-CarrierWave'></a>
### CarrierWave `constants`

##### Summary

Custom command for internal use.

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-TagBlockLock'></a>
### TagBlockLock `constants`

##### Summary

User Bank Perm-Lock

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-TagBlockWrite'></a>
### TagBlockWrite `constants`

##### Summary

Config this before block write

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-TagFilter'></a>
### TagFilter `constants`

##### Summary

Tag Bank 1 Filter

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-TagGeneralSelected'></a>
### TagGeneralSelected `constants`

##### Summary

Set Mask

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-TagInventory'></a>
### TagInventory `constants`

##### Summary

Config this before search

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-TagKill'></a>
### TagKill `constants`

##### Summary

Config this before kill

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-TagLock'></a>
### TagLock `constants`

##### Summary

Config this before lock

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-TagPostMatch'></a>
### TagPostMatch `constants`

##### Summary

Selected a tag for read, write, lock, kill, and search one operation

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-TagRanging'></a>
### TagRanging `constants`

##### Summary

Config this before ranging all tags

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-TagRead'></a>
### TagRead `constants`

##### Summary

Config this before read

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-TagReadAccPwd'></a>
### TagReadAccPwd `constants`

##### Summary

Config this before read Access password

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-TagReadEPC'></a>
### TagReadEPC `constants`

##### Summary

Config this before read EPC

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-TagReadKillPwd'></a>
### TagReadKillPwd `constants`

##### Summary

Config this before read Kill password

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-TagReadPC'></a>
### TagReadPC `constants`

##### Summary

Config this before read PC

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-TagReadProtect'></a>
### TagReadProtect `constants`

##### Summary

Custom command TagReadProtect

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-TagReadTid'></a>
### TagReadTid `constants`

##### Summary

Config this before read TID

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-TagReadUser'></a>
### TagReadUser `constants`

##### Summary

Config this before read USER

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-TagResetReadProtect'></a>
### TagResetReadProtect `constants`

##### Summary

Custom command TagResetReadProtect

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-TagSearchOne'></a>
### TagSearchOne `constants`

##### Summary

Config this before search one tag

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-TagSelected'></a>
### TagSelected `constants`

##### Summary

Selected a tag for read, write, lock, kill, and search one operation

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-TagWrite'></a>
### TagWrite `constants`

##### Summary

Config this before write

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-TagWriteAccPwd'></a>
### TagWriteAccPwd `constants`

##### Summary

Config this before write access password

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-TagWriteEPC'></a>
### TagWriteEPC `constants`

##### Summary

Config this before write EPC

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-TagWriteKillPwd'></a>
### TagWriteKillPwd `constants`

##### Summary

Config this before write kill password

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-TagWritePC'></a>
### TagWritePC `constants`

##### Summary

Config this before write PC

<a name='F-CSLibrary-Structures-CSLibraryOperationParms-TagWriteUser'></a>
### TagWriteUser `constants`

##### Summary

Config this before write USER

<a name='T-CSLibrary-Constants-CallbackType'></a>
## CallbackType `type`

##### Namespace

CSLibrary.Constants

##### Summary

Callback Type

<a name='F-CSLibrary-Constants-CallbackType-TAG_EASALARM'></a>
### TAG_EASALARM `constants`

##### Summary

Deletced EAS Enabled Tag

<a name='F-CSLibrary-Constants-CallbackType-TAG_INVENTORY'></a>
### TAG_INVENTORY `constants`

##### Summary

Tag Inventory, Only PC and EPC will backscatter

<a name='F-CSLibrary-Constants-CallbackType-TAG_RANGING'></a>
### TAG_RANGING `constants`

##### Summary

Ranging all tag, Only PC , EPC and RSSI will backscatter

<a name='F-CSLibrary-Constants-CallbackType-TAG_SEARCHING'></a>
### TAG_SEARCHING `constants`

##### Summary

Specific-Tag Searching, Only PC , EPC and RSSI will backscatter

<a name='F-CSLibrary-Constants-CallbackType-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown Type will not happen

<a name='T-CSLibrary-Structures-CarrierWaveParms'></a>
## CarrierWaveParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Carrier wave parms

<a name='F-CSLibrary-Structures-CarrierWaveParms-dataMode'></a>
### dataMode `constants`

##### Summary

data mode enable

<a name='T-CSLibrary-Structures-ChangeEASParms'></a>
## ChangeEASParms `type`

##### Namespace

CSLibrary.Structures

<a name='F-CSLibrary-Structures-ChangeEASParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

Access Password

<a name='F-CSLibrary-Structures-ChangeEASParms-enableEAS'></a>
### enableEAS `constants`

##### Summary

Enable/Disable EAS

<a name='F-CSLibrary-Structures-ChangeEASParms-retryCount'></a>
### retryCount `constants`

##### Summary

Retry Count

<a name='T-CSLibrary-Structures-CommonParms'></a>
## CommonParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

All tag-protocol operation functions share a common set of parameters.  These 
parameters are gathered in one place for convenience.

<a name='F-CSLibrary-Structures-CommonParms-callback'></a>
### callback `constants`

##### Summary

a callback function that the library will invoke with the 
Resulting operation-response packets.  This field must not be NULL.

<a name='F-CSLibrary-Structures-CommonParms-callbackCode'></a>
### callbackCode `constants`

##### Summary

A pointer to a 32-bit integer that upon return will contain the return 
code from the last call to the application-supplied callback function.  
If the application does not desire this information, this field may be 
NULL.

<a name='F-CSLibrary-Structures-CommonParms-context'></a>
### context `constants`

##### Summary

An application-defined value that is passed through unmodified to 
the application-specified callback function.

<a name='F-CSLibrary-Structures-CommonParms-tagStopCount'></a>
### tagStopCount `constants`

##### Summary

The maximum number of tags to which the tag-protocol operation 
will be applied.  If this number is zero, then the operation is applied 
to all tags that match the selection, and optionally post-singulation, 
match criteria (within the constraints of the antenna-port dwell time 
and inventory cycle count – see ).  If this number is non-zero, the 
antenna-port dwell-time and inventory-cycle-count constraints still 
apply, however the operation will be prematurely terminated if the 
maximum number of tags have the tag-protocol operation applied to 
them.  For version 1.0, this field may have a maximum value 1.

<a name='T-CSLibrary-Diagnostics-CoreDebug'></a>
## CoreDebug `type`

##### Namespace

CSLibrary.Diagnostics

##### Summary

CSLibrary Debugger

<a name='P-CSLibrary-Diagnostics-CoreDebug-Enable'></a>
### Enable `property`

##### Summary

Enable or Disable Debugger. You must include CSLibrary.xml in application directory.

<a name='T-CSLibrary-Structures-DEVICE_STATUS'></a>
## DEVICE_STATUS `type`

##### Namespace

CSLibrary.Structures

##### Summary

RFID Device Status Structures

<a name='F-CSLibrary-Structures-DEVICE_STATUS-IsCRCFilter'></a>
### IsCRCFilter `constants`

##### Summary

Crc filter flag

<a name='F-CSLibrary-Structures-DEVICE_STATUS-IsConnected'></a>
### IsConnected `constants`

##### Summary

Whether connection is connected or listening.

<a name='F-CSLibrary-Structures-DEVICE_STATUS-IsErrorReset'></a>
### IsErrorReset `constants`

##### Summary

Whether AutoReset is on.

<a name='F-CSLibrary-Structures-DEVICE_STATUS-IsKeepAlive'></a>
### IsKeepAlive `constants`

##### Summary

Whether UDP keep alive is on.

<a name='F-CSLibrary-Structures-DEVICE_STATUS-IsPowerOn'></a>
### IsPowerOn `constants`

##### Summary

Whether RFID is on.

<a name='M-CSLibrary-Structures-DEVICE_STATUS-GetElapsedTime'></a>
### GetElapsedTime() `method`

##### Summary

Get last elapsed time since last received packet.

##### Returns



##### Parameters

This method has no parameters.

<a name='T-CSLibrary-Constants-DataDifference'></a>
## DataDifference `type`

##### Namespace

CSLibrary.Constants

##### Summary

The difference, in Tari, between an data zero and a data one.

<a name='F-CSLibrary-Constants-DataDifference-HALF_TARI'></a>
### HALF_TARI `constants`

##### Summary

HALF_TARI

<a name='F-CSLibrary-Constants-DataDifference-ONE_TARI'></a>
### ONE_TARI `constants`

##### Summary

ONE_TARI

<a name='F-CSLibrary-Constants-DataDifference-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown

<a name='T-CSLibrary-Net-DeviceFinderArgs'></a>
## DeviceFinderArgs `type`

##### Namespace

CSLibrary.Net

##### Summary

DeviceFinder Argument

<a name='M-CSLibrary-Net-DeviceFinderArgs-#ctor-CSLibrary-Net-DeviceInfomation-'></a>
### #ctor(data) `constructor`

##### Summary

Device Finder

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| data | [CSLibrary.Net.DeviceInfomation](#T-CSLibrary-Net-DeviceInfomation 'CSLibrary.Net.DeviceInfomation') |  |

<a name='P-CSLibrary-Net-DeviceFinderArgs-Found'></a>
### Found `property`

##### Summary

Device finder information

<a name='T-CSLibrary-Net-DeviceInfomation'></a>
## DeviceInfomation `type`

##### Namespace

CSLibrary.Net

##### Summary

Netfinder information return from device

<a name='F-CSLibrary-Net-DeviceInfomation-ConnectMode'></a>
### ConnectMode `constants`

##### Summary

Connect Mode

<a name='F-CSLibrary-Net-DeviceInfomation-DHCPEnabled'></a>
### DHCPEnabled `constants`

##### Summary

enable or disable DHCP

<a name='F-CSLibrary-Net-DeviceInfomation-DHCPRetry'></a>
### DHCPRetry `constants`

##### Summary

DHCP retry

<a name='F-CSLibrary-Net-DeviceInfomation-Description'></a>
### Description `constants`

##### Summary

Mode discription

<a name='F-CSLibrary-Net-DeviceInfomation-DeviceName'></a>
### DeviceName `constants`

##### Summary

Device name, user can change it.

<a name='F-CSLibrary-Net-DeviceInfomation-Gateway'></a>
### Gateway `constants`

##### Summary

Gateway

<a name='F-CSLibrary-Net-DeviceInfomation-GatewayCheckResetMode'></a>
### GatewayCheckResetMode `constants`

##### Summary

Gateway check reset mode

<a name='F-CSLibrary-Net-DeviceInfomation-IPAddress'></a>
### IPAddress `constants`

##### Summary

IP address

<a name='F-CSLibrary-Net-DeviceInfomation-MACAddress'></a>
### MACAddress `constants`

##### Summary

MAC address

<a name='F-CSLibrary-Net-DeviceInfomation-Mode'></a>
### Mode `constants`

##### Summary

Reserved for future use

<a name='F-CSLibrary-Net-DeviceInfomation-Port'></a>
### Port `constants`

##### Summary

UDP Port

<a name='F-CSLibrary-Net-DeviceInfomation-SubnetMask'></a>
### SubnetMask `constants`

##### Summary

Subnet Mask

<a name='F-CSLibrary-Net-DeviceInfomation-TimeElapsedNetwork'></a>
### TimeElapsedNetwork `constants`

##### Summary

Total time on network

<a name='F-CSLibrary-Net-DeviceInfomation-TimeElapsedPowerOn'></a>
### TimeElapsedPowerOn `constants`

##### Summary

Total Power on time

<a name='F-CSLibrary-Net-DeviceInfomation-TrustedServer'></a>
### TrustedServer `constants`

##### Summary

Trusted hist IP

<a name='F-CSLibrary-Net-DeviceInfomation-TrustedServerEnabled'></a>
### TrustedServerEnabled `constants`

##### Summary

Inducated trusted server enable or not.

<a name='T-CSLibrary-Constants-DivideRatio'></a>
## DivideRatio `type`

##### Namespace

CSLibrary.Constants

##### Summary

The tag-to-interrogator divide ratio that is sent as part of the 
Query command.

<a name='F-CSLibrary-Constants-DivideRatio-RATIO_64DIV3'></a>
### RATIO_64DIV3 `constants`

##### Summary



<a name='F-CSLibrary-Constants-DivideRatio-RATIO_8'></a>
### RATIO_8 `constants`

##### Summary



<a name='F-CSLibrary-Constants-DivideRatio-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary



<a name='T-CSLibrary-Structures-DriverVersion'></a>
## DriverVersion `type`

##### Namespace

CSLibrary.Structures

##### Summary

Driver Version Structure

<a name='M-CSLibrary-Structures-DriverVersion-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='T-CSLibrary-Structures-DynamicQParms'></a>
## DynamicQParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

The parameters for the dynamic-Q algorithm, MAC singulation algorithm 3, (i.e., 
RFID_18K6C_SINGULATION_ALGORITHM_DYNAMICQ)

<a name='F-CSLibrary-Structures-DynamicQParms-maxQValue'></a>
### maxQValue `constants`

##### Summary

The maximum Q value to use.  Valid values are 0-15, inclusive.  
maxQValue must be greater than or equal to startQValue and 
minQValue.

<a name='F-CSLibrary-Structures-DynamicQParms-minQValue'></a>
### minQValue `constants`

##### Summary

The minimum Q value to use.  Valid values are 0-15, inclusive.  
minQValue must be less than or equal to startQValue and 
maxQValue.

<a name='F-CSLibrary-Structures-DynamicQParms-retryCount'></a>
### retryCount `constants`

##### Summary

Specifies the number of times to try another execution of 
the singulation algorithm for the specified session/target 
before either toggling the target (if toggleTarget is non-
zero) or terminating the inventory/tag access operation.  
Valid values are 0-255, inclusive.

<a name='F-CSLibrary-Structures-DynamicQParms-startQValue'></a>
### startQValue `constants`

##### Summary

The starting Q value to use.  Valid values are 0-15, inclusive.  
startQValue must be greater than or equal to minQValue and 
less than or equal to maxQValue.

<a name='F-CSLibrary-Structures-DynamicQParms-thresholdMultiplier'></a>
### thresholdMultiplier `constants`

##### Summary

The multiplier, specified in units of fourths (i.e., 0.25), that will be 
applied to the Q-adjustment threshold as part of the dynamic-Q 
algorithm.  For example, a value of 7 represents a multiplier of 
1.75.  See [MAC-EDS] for specifics on how the Q-adjustment 
threshold is used in the dynamic Q algorithm.  Valid values are 0-
255, inclusive.

<a name='F-CSLibrary-Structures-DynamicQParms-toggleTarget'></a>
### toggleTarget `constants`

##### Summary

A flag that indicates if, after performing the inventory cycle for the 
specified target (i.e., A or B), if the target should be toggled (i.e., A 
to B or B to A) and another inventory cycle run.  A non-zero value 
indicates that the target should be toggled.  A zero value indicates 
that the target should not be toggled.  Note that if the target is 
toggled, retryCount and maxQueryRepCount will also apply to the 
new target.

<a name='T-CSLibrary-Structures-EASParms'></a>
## EASParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

G2X EAS

<a name='F-CSLibrary-Structures-EASParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no access 
password.

<a name='F-CSLibrary-Structures-EASParms-common'></a>
### common `constants`

##### Summary

The common tag-protocol operation parameters.

<a name='F-CSLibrary-Structures-EASParms-easCmdParms'></a>
### easCmdParms `constants`

##### Summary

Enable EAS

<a name='F-CSLibrary-Structures-EASParms-length'></a>
### length `constants`

##### Summary

Structure size

<a name='T-CSLibrary-Utils-NativeIOControl-ECreationDisposition'></a>
## ECreationDisposition `type`

##### Namespace

CSLibrary.Utils.NativeIOControl

<a name='F-CSLibrary-Utils-NativeIOControl-ECreationDisposition-CreateAlways'></a>
### CreateAlways `constants`

##### Summary

Creates a new file, always. 
If a file exists, the function overwrites the file, clears the existing attributes, combines the specified file attributes, 
and flags with FILE_ATTRIBUTE_ARCHIVE, but does not set the security descriptor that the SECURITY_ATTRIBUTES structure specifies.

<a name='F-CSLibrary-Utils-NativeIOControl-ECreationDisposition-New'></a>
### New `constants`

##### Summary

Creates a new file. The function fails if a specified file exists.

<a name='F-CSLibrary-Utils-NativeIOControl-ECreationDisposition-OpenAlways'></a>
### OpenAlways `constants`

##### Summary

Opens a file, always. 
If a file does not exist, the function creates a file as if dwCreationDisposition is CREATE_NEW.

<a name='F-CSLibrary-Utils-NativeIOControl-ECreationDisposition-OpenExisting'></a>
### OpenExisting `constants`

##### Summary

Opens a file. The function fails if the file does not exist.

<a name='F-CSLibrary-Utils-NativeIOControl-ECreationDisposition-TruncateExisting'></a>
### TruncateExisting `constants`

##### Summary

Opens a file and truncates it so that its size is 0 (zero) bytes. The function fails if the file does not exist.
The calling process must open the file with the GENERIC_WRITE access right.

<a name='T-CSLibrary-Utils-NativeIOControl-EFileAccess'></a>
## EFileAccess `type`

##### Namespace

CSLibrary.Utils.NativeIOControl

<a name='F-CSLibrary-Utils-NativeIOControl-EFileAccess-GenericAll'></a>
### GenericAll `constants`

##### Summary



<a name='F-CSLibrary-Utils-NativeIOControl-EFileAccess-GenericExecute'></a>
### GenericExecute `constants`

##### Summary



<a name='F-CSLibrary-Utils-NativeIOControl-EFileAccess-GenericRead'></a>
### GenericRead `constants`

##### Summary



<a name='F-CSLibrary-Utils-NativeIOControl-EFileAccess-GenericWrite'></a>
### GenericWrite `constants`

##### Summary



<a name='T-CSLibrary-Utils-NativeIOControl-EFileShare'></a>
## EFileShare `type`

##### Namespace

CSLibrary.Utils.NativeIOControl

<a name='F-CSLibrary-Utils-NativeIOControl-EFileShare-Delete'></a>
### Delete `constants`

##### Summary

Enables subsequent open operations on an object to request delete access. 
Otherwise, other processes cannot open the object if they request delete access.
If this flag is not specified, but the object has been opened for delete access, the function fails.

<a name='F-CSLibrary-Utils-NativeIOControl-EFileShare-None'></a>
### None `constants`

##### Summary



<a name='F-CSLibrary-Utils-NativeIOControl-EFileShare-Read'></a>
### Read `constants`

##### Summary

Enables subsequent open operations on an object to request read access. 
Otherwise, other processes cannot open the object if they request read access. 
If this flag is not specified, but the object has been opened for read access, the function fails.

<a name='F-CSLibrary-Utils-NativeIOControl-EFileShare-Write'></a>
### Write `constants`

##### Summary

Enables subsequent open operations on an object to request write access. 
Otherwise, other processes cannot open the object if they request write access. 
If this flag is not specified, but the object has been opened for write access, the function fails.

<a name='T-CSLibrary-Structures-EnableSwitch'></a>
## EnableSwitch `type`

##### Namespace

CSLibrary.Structures

##### Summary

Enable / Disable Switch

<a name='F-CSLibrary-Structures-EnableSwitch-Disable'></a>
### Disable `constants`

##### Summary

Disable option

<a name='F-CSLibrary-Structures-EnableSwitch-Enable'></a>
### Enable `constants`

##### Summary

Enable option

<a name='T-CSLibrary-Constants-EpcMDID'></a>
## EpcMDID `type`

##### Namespace

CSLibrary.Constants

##### Summary

EPCglobal Tag Mask Designer Identifier

<a name='F-CSLibrary-Constants-EpcMDID-Alien_Technology'></a>
### Alien_Technology `constants`

##### Summary

Alien Technology

<a name='F-CSLibrary-Constants-EpcMDID-Alien_Technology_with_xTid'></a>
### Alien_Technology_with_xTid `constants`

##### Summary

Alien Technology with xTid

<a name='F-CSLibrary-Constants-EpcMDID-Atmel'></a>
### Atmel `constants`

##### Summary

Atmel

<a name='F-CSLibrary-Constants-EpcMDID-Atmel_with_xTid'></a>
### Atmel_with_xTid `constants`

##### Summary

Atmel with xTid

<a name='F-CSLibrary-Constants-EpcMDID-CAEN_Productivity_Engineering_Gesellschaft_fuer_IC_Design_mbH'></a>
### CAEN_Productivity_Engineering_Gesellschaft_fuer_IC_Design_mbH `constants`

##### Summary

CAEN Productivity Engineering Gesellschaft fuer IC Design mbH

<a name='F-CSLibrary-Constants-EpcMDID-CAEN_Productivity_Engineering_Gesellschaft_fuer_IC_Design_mbH_with_xTid'></a>
### CAEN_Productivity_Engineering_Gesellschaft_fuer_IC_Design_mbH_with_xTid `constants`

##### Summary

CAEN Productivity Engineering Gesellschaft fuer IC Design mbH with xTid

<a name='F-CSLibrary-Constants-EpcMDID-CAEN_RFID_srl'></a>
### CAEN_RFID_srl `constants`

##### Summary

CAEN RFID srl

<a name='F-CSLibrary-Constants-EpcMDID-CAEN_RFID_srl_with_xTid'></a>
### CAEN_RFID_srl_with_xTid `constants`

##### Summary

CAEN RFID srl with xTid

<a name='F-CSLibrary-Constants-EpcMDID-EM_Microelectronics'></a>
### EM_Microelectronics `constants`

##### Summary

EM Microelectronics

<a name='F-CSLibrary-Constants-EpcMDID-EM_Microelectronics_with_xTid'></a>
### EM_Microelectronics_with_xTid `constants`

##### Summary

EM Microelectronics with xTid

<a name='F-CSLibrary-Constants-EpcMDID-EP_Microelectronics'></a>
### EP_Microelectronics `constants`

##### Summary

EP Microelectronics

<a name='F-CSLibrary-Constants-EpcMDID-EP_Microelectronics_with_xTid'></a>
### EP_Microelectronics_with_xTid `constants`

##### Summary

EP Microelectronics with xTid

<a name='F-CSLibrary-Constants-EpcMDID-Fujitsu'></a>
### Fujitsu `constants`

##### Summary

Fujitsu

<a name='F-CSLibrary-Constants-EpcMDID-Fujitsu_with_xTid'></a>
### Fujitsu_with_xTid `constants`

##### Summary

Fujitsu with xTid

<a name='F-CSLibrary-Constants-EpcMDID-Impinj'></a>
### Impinj `constants`

##### Summary

Impinj

<a name='F-CSLibrary-Constants-EpcMDID-Impinj_with_xTid'></a>
### Impinj_with_xTid `constants`

##### Summary

Impinj with xTid

<a name='F-CSLibrary-Constants-EpcMDID-Intelleflex'></a>
### Intelleflex `constants`

##### Summary

Intelleflex

<a name='F-CSLibrary-Constants-EpcMDID-Intelleflex_with_xTid'></a>
### Intelleflex_with_xTid `constants`

##### Summary

Intelleflex with xTid

<a name='F-CSLibrary-Constants-EpcMDID-LSIS'></a>
### LSIS `constants`

##### Summary

LSIS

<a name='F-CSLibrary-Constants-EpcMDID-LSIS_with_xTid'></a>
### LSIS_with_xTid `constants`

##### Summary

LSIS with xTid

<a name='F-CSLibrary-Constants-EpcMDID-Motorola'></a>
### Motorola `constants`

##### Summary

Motorola

<a name='F-CSLibrary-Constants-EpcMDID-Motorola_with_xTid'></a>
### Motorola_with_xTid `constants`

##### Summary

Motorola with xTid

<a name='F-CSLibrary-Constants-EpcMDID-Mstar'></a>
### Mstar `constants`

##### Summary

Mstar

<a name='F-CSLibrary-Constants-EpcMDID-Mstar_with_xTid'></a>
### Mstar_with_xTid `constants`

##### Summary

Mstar with xTid

<a name='F-CSLibrary-Constants-EpcMDID-NXP'></a>
### NXP `constants`

##### Summary

NXP

<a name='F-CSLibrary-Constants-EpcMDID-NXP_with_xTid'></a>
### NXP_with_xTid `constants`

##### Summary

NXP with xTid

<a name='F-CSLibrary-Constants-EpcMDID-Quanray_Electronics'></a>
### Quanray_Electronics `constants`

##### Summary

Quanray Electronics

<a name='F-CSLibrary-Constants-EpcMDID-Quanray_Electronics_with_xTid'></a>
### Quanray_Electronics_with_xTid `constants`

##### Summary

Quanray Electronics with xTid

<a name='F-CSLibrary-Constants-EpcMDID-Renesas_Technology_Corp'></a>
### Renesas_Technology_Corp `constants`

##### Summary

Renesas Technology Corp

<a name='F-CSLibrary-Constants-EpcMDID-Renesas_Technology_Corp_with_xTid'></a>
### Renesas_Technology_Corp_with_xTid `constants`

##### Summary

Renesas Technology Corp with xTid

<a name='F-CSLibrary-Constants-EpcMDID-ST_Microelectronics'></a>
### ST_Microelectronics `constants`

##### Summary

ST Microelectronics

<a name='F-CSLibrary-Constants-EpcMDID-ST_Microelectronics_with_xTid'></a>
### ST_Microelectronics_with_xTid `constants`

##### Summary

ST Microelectronics with xTid

<a name='F-CSLibrary-Constants-EpcMDID-Sentech_Snd_Bhd'></a>
### Sentech_Snd_Bhd `constants`

##### Summary

Sentech Snd Bhd

<a name='F-CSLibrary-Constants-EpcMDID-Sentech_Snd_Bhd_with_xTid'></a>
### Sentech_Snd_Bhd_with_xTid `constants`

##### Summary

Sentech Snd Bhd with xTid

<a name='F-CSLibrary-Constants-EpcMDID-Texas_Instruments'></a>
### Texas_Instruments `constants`

##### Summary

Texas Instruments

<a name='F-CSLibrary-Constants-EpcMDID-Texas_Instruments_with_xTid'></a>
### Texas_Instruments_with_xTid `constants`

##### Summary

Texas Instruments with xTid

<a name='F-CSLibrary-Constants-EpcMDID-Tyco_International'></a>
### Tyco_International `constants`

##### Summary

Tyco International

<a name='F-CSLibrary-Constants-EpcMDID-Tyco_International_with_xTid'></a>
### Tyco_International_with_xTid `constants`

##### Summary

Tyco International with xTid

<a name='F-CSLibrary-Constants-EpcMDID-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

UNKNOWN

<a name='T-CSLibrary-Structures-ErrorBit'></a>
## ErrorBit `type`

##### Namespace

CSLibrary.Structures

##### Summary

Pass / Fail

<a name='F-CSLibrary-Structures-ErrorBit-Error'></a>
### Error `constants`

##### Summary

Fail

<a name='F-CSLibrary-Structures-ErrorBit-OK'></a>
### OK `constants`

##### Summary

Pass

<a name='T-CSLibrary-Constants-ErrorCode'></a>
## ErrorCode `type`

##### Namespace

CSLibrary.Constants

##### Summary

Operation Error Code

<a name='F-CSLibrary-Constants-ErrorCode-CRC_INVALID'></a>
### CRC_INVALID `constants`

##### Summary

CRC Invalid

<a name='F-CSLibrary-Constants-ErrorCode-FUNC_RETURN_FAILED'></a>
### FUNC_RETURN_FAILED `constants`

##### Summary

function return failure

<a name='F-CSLibrary-Constants-ErrorCode-INVALID_TAG'></a>
### INVALID_TAG `constants`

##### Summary

Invalid tag found, ie not Gen2 class-1

<a name='F-CSLibrary-Constants-ErrorCode-MAC_ERROR'></a>
### MAC_ERROR `constants`

##### Summary

MacError Occurs

<a name='F-CSLibrary-Constants-ErrorCode-MAX_RETRY_OVER'></a>
### MAX_RETRY_OVER `constants`

##### Summary

Max retry is over

<a name='F-CSLibrary-Constants-ErrorCode-PARSE_PKT_ERROR'></a>
### PARSE_PKT_ERROR `constants`

##### Summary

fail to parse packet

<a name='F-CSLibrary-Constants-ErrorCode-SYSTEM_ERROR'></a>
### SYSTEM_ERROR `constants`

##### Summary

System.Exception catch

<a name='F-CSLibrary-Constants-ErrorCode-TAG_NOT_FOUND'></a>
### TAG_NOT_FOUND `constants`

##### Summary

can't find specific tag

<a name='F-CSLibrary-Constants-ErrorCode-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknow error

<a name='F-CSLibrary-Constants-ErrorCode-WRITTEN_DATA_INVALID'></a>
### WRITTEN_DATA_INVALID `constants`

##### Summary

Written data to target tag is invalid

<a name='T-CSLibrary-Constants-ErrorType'></a>
## ErrorType `type`

##### Namespace

CSLibrary.Constants

##### Summary

Error Type

<a name='F-CSLibrary-Constants-ErrorType-COMMON'></a>
### COMMON `constants`

##### Summary

General Error

<a name='F-CSLibrary-Constants-ErrorType-INVENTORY'></a>
### INVENTORY `constants`

##### Summary

Inventory or search error

<a name='F-CSLibrary-Constants-ErrorType-KILL'></a>
### KILL `constants`

##### Summary

Kill error
Notes : Kill always reports an error even  kill a tag successfully

<a name='F-CSLibrary-Constants-ErrorType-LOCK'></a>
### LOCK `constants`

##### Summary

Lock error

<a name='F-CSLibrary-Constants-ErrorType-MAC'></a>
### MAC `constants`

##### Summary

Mac Error

<a name='F-CSLibrary-Constants-ErrorType-READ'></a>
### READ `constants`

##### Summary

Read error

<a name='F-CSLibrary-Constants-ErrorType-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknow

<a name='F-CSLibrary-Constants-ErrorType-WRITE'></a>
### WRITE `constants`

##### Summary

Write error

<a name='T-CSLibrary-Structures-Ext1SensorType'></a>
## Ext1SensorType `type`

##### Namespace

CSLibrary.Structures

##### Summary

External sensor 1 type

<a name='F-CSLibrary-Structures-Ext1SensorType-ACExcitation'></a>
### ACExcitation `constants`

##### Summary

Capacitive or resistive sensor without DC (AC signal on EXC pin)

<a name='F-CSLibrary-Structures-Ext1SensorType-HighImpedanceInput'></a>
### HighImpedanceInput `constants`

##### Summary

High Impedance Input

<a name='F-CSLibrary-Structures-Ext1SensorType-LinerResistiveSensor'></a>
### LinerResistiveSensor `constants`

##### Summary

Liner Resistive Sensor

<a name='T-CSLibrary-Structures-Ext2SensorType'></a>
## Ext2SensorType `type`

##### Namespace

CSLibrary.Structures

##### Summary

External sensor 2 type

<a name='F-CSLibrary-Structures-Ext2SensorType-HighImpedanceInput'></a>
### HighImpedanceInput `constants`

##### Summary

High Impedance Input

<a name='F-CSLibrary-Structures-Ext2SensorType-LinerConductiveSensor'></a>
### LinerConductiveSensor `constants`

##### Summary

Liner Conductive Sensor

<a name='T-CSLibrary-Constants-ExtendedKillCommand'></a>
## ExtendedKillCommand `type`

##### Namespace

CSLibrary.Constants

##### Summary

Extended Kill command for UHF class 1 gen-2 version 1.2

<a name='F-CSLibrary-Constants-ExtendedKillCommand-DISABLE_PERMALOCK'></a>
### DISABLE_PERMALOCK `constants`

##### Summary

The Tag shall diable block permalocking and unlock any block of User memory that
were previously permalocked. The Tag shall disable support for the BlockPermalock
command. If the Tag did not implement block permalocking prior to recommissioning
then block permalocking shall remains disabled. The lock status of User memory shall
be determined solely by the lock bits.

<a name='F-CSLibrary-Constants-ExtendedKillCommand-DISABLE_USER_MEMORY'></a>
### DISABLE_USER_MEMORY `constants`

##### Summary

The Tag shall render its User memory inaccessible, causing the entire memory bank to
become unreadable, unwriteable, unselectable(ie. the Tag functions as though its User memory
bank no longer exits).

<a name='F-CSLibrary-Constants-ExtendedKillCommand-NORMAL'></a>
### NORMAL `constants`

##### Summary

Perform normall Tag Kill command

<a name='F-CSLibrary-Constants-ExtendedKillCommand-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown command

<a name='F-CSLibrary-Constants-ExtendedKillCommand-UNLOCK_ALL_BANKS'></a>
### UNLOCK_ALL_BANKS `constants`

##### Summary

The Tag shall unlock its EPC, TID, and User memory banks, regardless of whether these
banks were locked or permalocked. Portions of User memory that were block permalock shall
remain block permalocked, and vice versa, unless the DISABLE_PERMALOCK is also asserted, in which
case the Tag shall unlock its permalocked blocks. The Tag shall write-unlock its kill and
access passwords, and shall render the kill and access passwords permanently unreadable regardless
of the values of the Tag's lock bits. If an Interrogator subsequently attempts to read
the Tag's kill or access passwords the Tag shall backscatter an error code

<a name='T-CSLibrary-Structures-FIFOSubcommand'></a>
## FIFOSubcommand `type`

##### Namespace

CSLibrary.Structures

##### Summary

Access FIFO Subcommand

<a name='F-CSLibrary-Structures-FIFOSubcommand-ReadData'></a>
### ReadData `constants`

##### Summary

Read data from FIFO

<a name='F-CSLibrary-Structures-FIFOSubcommand-ReadStatus'></a>
### ReadStatus `constants`

##### Summary

Read status register

<a name='F-CSLibrary-Structures-FIFOSubcommand-WriteData'></a>
### WriteData `constants`

##### Summary

Write data to FIFO

<a name='T-CSLibrary-Structures-FeedbackResistor'></a>
## FeedbackResistor `type`

##### Namespace

CSLibrary.Structures

##### Summary

Feedback resistor value

<a name='F-CSLibrary-Structures-FeedbackResistor-R185K'></a>
### R185K `constants`

##### Summary

Resistor 185K

<a name='F-CSLibrary-Structures-FeedbackResistor-R1875K'></a>
### R1875K `constants`

##### Summary

Resistor 1875K

<a name='F-CSLibrary-Structures-FeedbackResistor-R3875K'></a>
### R3875K `constants`

##### Summary

Resistor 3875K

<a name='F-CSLibrary-Structures-FeedbackResistor-R400K'></a>
### R400K `constants`

##### Summary

Resistor 400K

<a name='F-CSLibrary-Structures-FeedbackResistor-R875K'></a>
### R875K `constants`

##### Summary

Resistor 875K

<a name='T-CSLibrary-Structures-FixedQParms'></a>
## FixedQParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

The  parameters  for  the  fixed-Q  algorithm,  MAC  singulation  algorithm  0,  (i.e., 
RFID_18K6C_SINGULATION_ALGORITHM_FIXEDQ)

<a name='M-CSLibrary-Structures-FixedQParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='M-CSLibrary-Structures-FixedQParms-#ctor-System-UInt32,System-UInt32,System-UInt32,System-UInt32-'></a>
### #ctor(qValue,retryCount,toggleTarget,repeatUntilNoTags) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| qValue | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| retryCount | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| toggleTarget | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| repeatUntilNoTags | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |

<a name='F-CSLibrary-Structures-FixedQParms-qValue'></a>
### qValue `constants`

##### Summary

The Q value to use.  Valid values are 0-15, inclusive.

<a name='F-CSLibrary-Structures-FixedQParms-repeatUntilNoTags'></a>
### repeatUntilNoTags `constants`

##### Summary

A flag that indicates whether or not the singulation 
algorithm should continue performing inventory rounds 
until no tags are singulated.  A non-zero value indicates 
that, for each execution of the singulation algorithm, 
inventory rounds should be performed until no tags are 
singulated.  A zero value indicates that a single 
inventory round should be performed for each 
execution of the singulation algorithm.

<a name='F-CSLibrary-Structures-FixedQParms-retryCount'></a>
### retryCount `constants`

##### Summary

Specifies the number of times to try another execution 
of the singulation algorithm for the specified 
session/target before either toggling the target (if 
toggleTarget is non-zero) or terminating the 
inventory/tag access operation.  Valid values are 0-
255, inclusive.

<a name='F-CSLibrary-Structures-FixedQParms-toggleTarget'></a>
### toggleTarget `constants`

##### Summary

A flag that indicates if, after performing the inventory cycle for 
the specified target (i.e., A or B), if the target should be toggled 
(i.e., A to B or B to A) and another inventory cycle run.  A non-
zero value indicates that the target should be toggled.  A zero 
value indicates that the target should not be toggled.  Note that 
if the target is toggled, retryCount and 
repeatUntilNoTags will also apply to the new target.

<a name='T-CSLibrary-Constants-FreqAgileMode'></a>
## FreqAgileMode `type`

##### Namespace

CSLibrary.Constants

##### Summary

Freq Agile Mode

<a name='F-CSLibrary-Constants-FreqAgileMode-DISABLE'></a>
### DISABLE `constants`

##### Summary

Disable Freq Agile

<a name='F-CSLibrary-Constants-FreqAgileMode-ENABLE'></a>
### ENABLE `constants`

##### Summary

Enable Freq Agile

<a name='T-CSLibrary-Structures-FrequencyBandParms'></a>
## FrequencyBandParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Frequency Band Parms

<a name='F-CSLibrary-Structures-FrequencyBandParms-AffinityBand'></a>
### AffinityBand `constants`

##### Summary

AffinityBand

<a name='F-CSLibrary-Structures-FrequencyBandParms-Band'></a>
### Band `constants`

##### Summary

Frequency Band

<a name='F-CSLibrary-Structures-FrequencyBandParms-DivideRatio'></a>
### DivideRatio `constants`

##### Summary

DivideRation

<a name='F-CSLibrary-Structures-FrequencyBandParms-Frequency'></a>
### Frequency `constants`

##### Summary

Frequency

<a name='F-CSLibrary-Structures-FrequencyBandParms-GuardBand'></a>
### GuardBand `constants`

##### Summary

GuardBand

<a name='F-CSLibrary-Structures-FrequencyBandParms-MaximumDACBand'></a>
### MaximumDACBand `constants`

##### Summary

MaximumDACBand

<a name='F-CSLibrary-Structures-FrequencyBandParms-MinimumDACBand'></a>
### MinimumDACBand `constants`

##### Summary

MinimumDACBand

<a name='F-CSLibrary-Structures-FrequencyBandParms-MultiplyRatio'></a>
### MultiplyRatio `constants`

##### Summary

MultiplyRatio

<a name='F-CSLibrary-Structures-FrequencyBandParms-State'></a>
### State `constants`

##### Summary

State

<a name='T-CSLibrary-Constants-FwUpdateFlags'></a>
## FwUpdateFlags `type`

##### Namespace

CSLibrary.Constants

##### Summary

Firmware Update flags

<a name='F-CSLibrary-Constants-FwUpdateFlags-NVMEM_UPDATE'></a>
### NVMEM_UPDATE `constants`

##### Summary

Update Firmware without test

<a name='F-CSLibrary-Constants-FwUpdateFlags-NVMEM_UPDATE_APP'></a>
### NVMEM_UPDATE_APP `constants`

##### Summary

Update Application without test

<a name='F-CSLibrary-Constants-FwUpdateFlags-NVMEM_UPDATE_APP_TEST'></a>
### NVMEM_UPDATE_APP_TEST `constants`

##### Summary

Update Application with test

<a name='F-CSLibrary-Constants-FwUpdateFlags-NVMEM_UPDATE_BL'></a>
### NVMEM_UPDATE_BL `constants`

##### Summary

Update Bootloader without test

<a name='F-CSLibrary-Constants-FwUpdateFlags-NVMEM_UPDATE_BL_TEST'></a>
### NVMEM_UPDATE_BL_TEST `constants`

##### Summary

Update Bootloader with test

<a name='F-CSLibrary-Constants-FwUpdateFlags-NVMEM_UPDATE_TEST'></a>
### NVMEM_UPDATE_TEST `constants`

##### Summary

Update Firmware with test

<a name='T-CSLibrary-Structures-G2ConfigParms'></a>
## G2ConfigParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

G2 Config Parameter

<a name='M-CSLibrary-Structures-G2ConfigParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-G2ConfigParms-DigitalOutput'></a>
### DigitalOutput `constants`

##### Summary

Digital Output

<a name='F-CSLibrary-Structures-G2ConfigParms-ExternalSupply'></a>
### ExternalSupply `constants`

##### Summary

External Supply Flag or Input Signal

<a name='F-CSLibrary-Structures-G2ConfigParms-InvertDigitalOutput'></a>
### InvertDigitalOutput `constants`

##### Summary

Invert Digital Output

<a name='F-CSLibrary-Structures-G2ConfigParms-MaxBackscatterStrength'></a>
### MaxBackscatterStrength `constants`

##### Summary

Max. Backscatter Strength

<a name='F-CSLibrary-Structures-G2ConfigParms-PSFAlarm'></a>
### PSFAlarm `constants`

##### Summary

PSF Alarm Flag

<a name='F-CSLibrary-Structures-G2ConfigParms-ReadProtectEPC'></a>
### ReadProtectEPC `constants`

##### Summary

Read Protect EPC Bank

<a name='F-CSLibrary-Structures-G2ConfigParms-ReadProtectTID'></a>
### ReadProtectTID `constants`

##### Summary

Read Protect TID

<a name='F-CSLibrary-Structures-G2ConfigParms-ReadRangeReduction'></a>
### ReadRangeReduction `constants`

##### Summary

Read Range Reduction On/Off

<a name='F-CSLibrary-Structures-G2ConfigParms-TempetrAlarm'></a>
### TempetrAlarm `constants`

##### Summary

Temper Alarm Flag

<a name='F-CSLibrary-Structures-G2ConfigParms-TransparentMode'></a>
### TransparentMode `constants`

##### Summary

Transparent Mode On/Off

<a name='F-CSLibrary-Structures-G2ConfigParms-TransparentModeData'></a>
### TransparentModeData `constants`

##### Summary

Transparent Mode Data/Raw

<a name='F-CSLibrary-Structures-G2ConfigParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

Kill/Access Password

<a name='T-CSLibrary-Constants-GPIOTrigger'></a>
## GPIOTrigger `type`

##### Namespace

CSLibrary.Constants

##### Summary

GPIO Trigger flags

<a name='F-CSLibrary-Constants-GPIOTrigger-ANY_TRIGGER'></a>
### ANY_TRIGGER `constants`

##### Summary

Raising edge and falling edge trigger

<a name='F-CSLibrary-Constants-GPIOTrigger-FALLING_EDGE'></a>
### FALLING_EDGE `constants`

##### Summary

Falling edge trigger

<a name='F-CSLibrary-Constants-GPIOTrigger-OFF'></a>
### OFF `constants`

##### Summary

Turn off trigger

<a name='F-CSLibrary-Constants-GPIOTrigger-RISING_EDGE'></a>
### RISING_EDGE `constants`

##### Summary

Raising edge trigger

<a name='T-CSLibrary-Structures-GPI_INTERRUPT_CALLBACK'></a>
## GPI_INTERRUPT_CALLBACK `type`

##### Namespace

CSLibrary.Structures

##### Summary

GPI Interrupt callback

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| ip | [T:CSLibrary.Structures.GPI_INTERRUPT_CALLBACK](#T-T-CSLibrary-Structures-GPI_INTERRUPT_CALLBACK 'T:CSLibrary.Structures.GPI_INTERRUPT_CALLBACK') | Source IP address |

<a name='T-CSLibrary-Tools-GUID'></a>
## GUID `type`

##### Namespace

CSLibrary.Tools

##### Summary

Autogen a guid

<a name='M-CSLibrary-Tools-GUID-Gen12BitUID'></a>
### Gen12BitUID() `method`

##### Summary

12 bit guid

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Tools-GUID-Gen24BitUID'></a>
### Gen24BitUID() `method`

##### Summary

24 bit guid

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Tools-GUID-Gen48BitUID'></a>
### Gen48BitUID() `method`

##### Summary

48 bit guid

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Tools-GUID-Gen96BitUID'></a>
### Gen96BitUID() `method`

##### Summary

96 bit guid

##### Returns



##### Parameters

This method has no parameters.

<a name='T-CSLibrary-Constants-GpioPin'></a>
## GpioPin `type`

##### Namespace

CSLibrary.Constants

<a name='F-CSLibrary-Constants-GpioPin-PIN_0'></a>
### PIN_0 `constants`

##### Summary

Pin 0

<a name='F-CSLibrary-Constants-GpioPin-PIN_1'></a>
### PIN_1 `constants`

##### Summary

Pin 1

<a name='F-CSLibrary-Constants-GpioPin-PIN_2'></a>
### PIN_2 `constants`

##### Summary

Pin 2

<a name='F-CSLibrary-Constants-GpioPin-PIN_3'></a>
### PIN_3 `constants`

##### Summary

Pin 3

<a name='T-CSLibrary-Structures-HST_INV_EPC_MATCH_CFG'></a>
## HST_INV_EPC_MATCH_CFG `type`

##### Namespace

CSLibrary.Structures

##### Summary

The host writes this register to enable matching of the EPC read during 
the underlying Query and inventory operations. Only matching EPCs will be returned to the host.

<a name='M-CSLibrary-Structures-HST_INV_EPC_MATCH_CFG-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='M-CSLibrary-Structures-HST_INV_EPC_MATCH_CFG-#ctor-System-UInt32-'></a>
### #ctor(data) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| data | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |

<a name='M-CSLibrary-Structures-HST_INV_EPC_MATCH_CFG-#ctor-System-Boolean,System-Boolean,System-UInt32,System-UInt32-'></a>
### #ctor(enable,match,offset,count) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| enable | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') | EPC matching enabled |
| match | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') | Determines if the associated tag-protocol operation will be 
applied to tags that match the mask or not.  A non-zero 
value indicates that the tag-protocol operation should be 
applied to tags that match the mask.  A value of zero 
indicates that the tag-protocol operation should be applied 
to tags that do not match the mask. |
| offset | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The offset in bits, from the start of the Electronic Product 
Code (EPC), of the first bit that will be matched against the 
mask.  If offset falls beyond the end of EPC, the tag is 
considered non-matching. |
| count | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The number of bits in the mask.  A length of zero will cause 
all tags to match.  If (offset+count) falls beyond the end 
of the EPC, the tag is considered non-matching.  Valid 
values are 0 to 496, inclusive. |

<a name='P-CSLibrary-Structures-HST_INV_EPC_MATCH_CFG-count'></a>
### count `property`

##### Summary

The number of bits in the mask.  A length of zero will cause 
all tags to match.  If (offset+count) falls beyond the end 
of the EPC, the tag is considered non-matching.  Valid 
values are 0 to 496, inclusive.

<a name='P-CSLibrary-Structures-HST_INV_EPC_MATCH_CFG-enable'></a>
### enable `property`

##### Summary

EPC matching enabled

<a name='P-CSLibrary-Structures-HST_INV_EPC_MATCH_CFG-match'></a>
### match `property`

##### Summary

Determines if the associated tag-protocol operation will be 
applied to tags that match the mask or not.  A non-zero 
value indicates that the tag-protocol operation should be 
applied to tags that match the mask.  A value of zero 
indicates that the tag-protocol operation should be applied 
to tags that do not match the mask.

<a name='P-CSLibrary-Structures-HST_INV_EPC_MATCH_CFG-offset'></a>
### offset `property`

##### Summary

The offset in bits, from the start of the Electronic Product 
Code (EPC), of the first bit that will be matched against the 
mask.  If offset falls beyond the end of EPC, the tag is 
considered non-matching.

<a name='P-CSLibrary-Structures-HST_INV_EPC_MATCH_CFG-value'></a>
### value `property`

##### Summary

Internal use

<a name='M-CSLibrary-Structures-HST_INV_EPC_MATCH_CFG-#cctor'></a>
### #cctor() `method`

##### Summary

Internal Constructor

##### Parameters

This method has no parameters.

<a name='T-CSLibrary-Text-Hex'></a>
## Hex `type`

##### Namespace

CSLibrary.Text

##### Summary

For Backward Compatibility

<a name='T-CSLibrary-Text-HexEncoding'></a>
## HexEncoding `type`

##### Namespace

CSLibrary.Text

##### Summary

Summary description for HexEncoding.

<a name='M-CSLibrary-Text-HexEncoding-Compare-System-String,System-String-'></a>
### Compare(source,target) `method`

##### Summary

Compare Hex String, ie, source = "11ffaa", target = "11FFaa", it will return true

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| source | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | Source Hex string |
| target | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | Target comparing Hex string |

<a name='M-CSLibrary-Text-HexEncoding-Compare-System-Byte[],System-Byte[]-'></a>
### Compare(source,target) `method`

##### Summary

Compare Hex

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| source | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | Source Hex |
| target | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | Target comparing Hex |

<a name='M-CSLibrary-Text-HexEncoding-Compare-System-Byte[],System-Byte[],System-Int32-'></a>
### Compare(source,target,size) `method`

##### Summary

Compare Hex

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| source | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | Source Hex |
| target | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | Target comparing Hex |
| size | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | Size to compare |

<a name='M-CSLibrary-Text-HexEncoding-Compare``1-``0[],``0[]-'></a>
### Compare\`\`1(a,b) `method`

##### Summary

Generic compare two array

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| a | [\`\`0[]](#T-``0[] '``0[]') |  |
| b | [\`\`0[]](#T-``0[] '``0[]') |  |

##### Generic Types

| Name | Description |
| ---- | ----------- |
| T | Type of array |

<a name='M-CSLibrary-Text-HexEncoding-Copy-System-Byte[],System-Byte[],System-Int32-'></a>
### Copy(src,dst,count) `method`

##### Summary

Copy One array to another array

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| src | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| dst | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| count | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |

<a name='M-CSLibrary-Text-HexEncoding-Copy-System-Byte[],System-Byte[],System-Int32,System-Int32-'></a>
### Copy(src,dst,dstIndex,count) `method`

##### Summary

Copy One array to another array

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| src | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| dst | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| dstIndex | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |
| count | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |

<a name='M-CSLibrary-Text-HexEncoding-Copy-System-Byte[],System-Int32,System-Byte[],System-Int32,System-Int32-'></a>
### Copy(src,srcIndex,dst,dstIndex,count) `method`

##### Summary

Copy One array to another array

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| src | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| srcIndex | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |
| dst | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| dstIndex | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |
| count | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |

<a name='M-CSLibrary-Text-HexEncoding-GenPostMatchMask-System-String-'></a>
### GenPostMatchMask(hexString) `method`

##### Summary

Creates a byte array from the hexadecimal string. Each two characters are combined
to create one byte. First two hexadecimal characters become first byte in returned array.
Non-hexadecimal characters are ignored.

##### Returns

byte array, in the same left-to-right order as the hexString

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| hexString | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | string to convert to byte array |

<a name='M-CSLibrary-Text-HexEncoding-GenSelectMask-System-String-'></a>
### GenSelectMask(hexString) `method`

##### Summary

Creates a byte array from the hexadecimal string. Each two characters are combined
to create one byte. First two hexadecimal characters become first byte in returned array.
Non-hexadecimal characters are ignored.

##### Returns

byte array, in the same left-to-right order as the hexString

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| hexString | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | string to convert to byte array |

<a name='M-CSLibrary-Text-HexEncoding-GetBitCount-System-String-'></a>
### GetBitCount(hexString) `method`

##### Summary

Get bit length from string

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| hexString | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |  |

<a name='M-CSLibrary-Text-HexEncoding-GetBitCount-System-Byte[]-'></a>
### GetBitCount(bytes) `method`

##### Summary

Get bit length from string

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| bytes | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |

<a name='M-CSLibrary-Text-HexEncoding-GetByteCount-System-String-'></a>
### GetByteCount(hexString) `method`

##### Summary

GetByteCount

##### Returns

Number of Byte Count

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| hexString | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | Input Hex String |

<a name='M-CSLibrary-Text-HexEncoding-GetWordCount-System-String-'></a>
### GetWordCount(hexString) `method`

##### Summary

Get Word length from string

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| hexString | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |  |

<a name='M-CSLibrary-Text-HexEncoding-HexToByte-System-String-'></a>
### HexToByte(hex) `method`

##### Summary

Converts 1 or 2 character string into equivalant byte value

##### Returns

byte

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| hex | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | 1 or 2 character string |

<a name='M-CSLibrary-Text-HexEncoding-IsHexFormat-System-String-'></a>
### IsHexFormat(hexString) `method`

##### Summary

Determines if given string is in proper hexadecimal string format

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| hexString | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |  |

<a name='M-CSLibrary-Text-HexEncoding-ToBinary-System-Byte[],System-UInt32,System-UInt32-'></a>
### ToBinary(source,offset,length) `method`

##### Summary

Convert to binary format

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| source | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| offset | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| length | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |

<a name='M-CSLibrary-Text-HexEncoding-ToByte-System-String-'></a>
### ToByte(hexString) `method`

##### Summary

return a byte from string

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| hexString | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |  |

<a name='M-CSLibrary-Text-HexEncoding-ToBytes-System-String-'></a>
### ToBytes(hexString) `method`

##### Summary

Creates a byte array from the hexadecimal string. Each two characters are combined
to create one byte. First two hexadecimal characters become first byte in returned array.
Non-hexadecimal characters are ignored.

##### Returns

byte array, in the same left-to-right order as the hexString

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| hexString | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | string to convert to byte array |

<a name='M-CSLibrary-Text-HexEncoding-ToBytes-System-UInt16[]-'></a>
### ToBytes(data) `method`

##### Summary

Convent ushort array to byte array

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| data | [System.UInt16[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16[] 'System.UInt16[]') |  |

<a name='M-CSLibrary-Text-HexEncoding-ToBytes-System-UInt16[],System-Int32-'></a>
### ToBytes(data,count) `method`

##### Summary

Convent ushort array to byte array

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| data | [System.UInt16[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16[] 'System.UInt16[]') |  |
| count | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |

<a name='M-CSLibrary-Text-HexEncoding-ToInt16-System-Byte[],System-Int32-'></a>
### ToInt16(buffer,offset) `method`

##### Summary

Convert 2 Bytes to one short

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| buffer | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| offset | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |

<a name='M-CSLibrary-Text-HexEncoding-ToShorts-System-Byte[]-'></a>
### ToShorts(Input) `method`

##### Summary

return short array from byte array

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| Input | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |

<a name='M-CSLibrary-Text-HexEncoding-ToString-System-Byte[]-'></a>
### ToString(bytes) `method`

##### Summary

Byte to String Conversion

##### Returns

Return a String

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| bytes | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | Input Byte Array |

<a name='M-CSLibrary-Text-HexEncoding-ToString-System-Byte[],System-Int32-'></a>
### ToString(bytes,length) `method`

##### Summary

Byte to String Conversion

##### Returns

Return a String

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| bytes | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | Input Byte Array |
| length | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | Input Byte length |

<a name='M-CSLibrary-Text-HexEncoding-ToString-System-Byte[],System-UInt32,System-UInt32-'></a>
### ToString(bytes,offset,count) `method`

##### Summary

Byte to String Conversion

##### Returns

Return a String

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| bytes | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | Input Byte Array |
| offset | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Start offset |
| count | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Number of Count to converse |

<a name='M-CSLibrary-Text-HexEncoding-ToString-System-UInt16[]-'></a>
### ToString(data) `method`

##### Summary

ushort to String Conversion

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| data | [System.UInt16[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16[] 'System.UInt16[]') |  |

<a name='M-CSLibrary-Text-HexEncoding-ToString-System-UInt16[],System-UInt32,System-UInt32-'></a>
### ToString(data,offset,count) `method`

##### Summary

ushort to String Conversion

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| data | [System.UInt16[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16[] 'System.UInt16[]') | source data |
| offset | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Start offset |
| count | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Number of Count to converse |

<a name='M-CSLibrary-Text-HexEncoding-ToUInt16-System-Byte[],System-Int32-'></a>
### ToUInt16(buffer,offset) `method`

##### Summary

Convert 2 Bytes to one short

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| buffer | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| offset | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |

<a name='M-CSLibrary-Text-HexEncoding-ToUInt32-System-Byte[],System-Int32-'></a>
### ToUInt32(buffer,offset) `method`

##### Summary

Convert 4 Bytes to one uint32

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| buffer | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| offset | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |

<a name='M-CSLibrary-Text-HexEncoding-ToUInt32-System-String-'></a>
### ToUInt32(hexString) `method`

##### Summary

Convert string to one uint32

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| hexString | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |  |

<a name='M-CSLibrary-Text-HexEncoding-ToUInt64-System-Byte[],System-Int32-'></a>
### ToUInt64(buffer,offset) `method`

##### Summary

Convert 4 bytes to long

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| buffer | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| offset | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |

<a name='M-CSLibrary-Text-HexEncoding-ToUshort-System-String-'></a>
### ToUshort(str) `method`

##### Summary

return ushort from byte string

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| str | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |  |

<a name='M-CSLibrary-Text-HexEncoding-ToUshorts-System-Byte[]-'></a>
### ToUshorts(Input) `method`

##### Summary

return ushort array from byte array

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| Input | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |

<a name='M-CSLibrary-Text-HexEncoding-ToUshorts-System-String-'></a>
### ToUshorts(Input) `method`

##### Summary

return ushort array from string input

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| Input | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |  |

<a name='T-CSLibrary-HighLevelInterface'></a>
## HighLevelInterface `type`

##### Namespace

CSLibrary

##### Summary

Reader HighLevelInterface

<a name='M-CSLibrary-HighLevelInterface-#ctor'></a>
### #ctor() `constructor`

##### Summary

Default Constructor without debugger

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-HighLevelInterface-AUSTableOfFreq'></a>
### AUSTableOfFreq `constants`

##### Summary

Australia Frequency Table

<a name='F-CSLibrary-HighLevelInterface-AUS_CHN_CNT'></a>
### AUS_CHN_CNT `constants`

##### Summary

Australia Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-BR1_CHN_CNT'></a>
### BR1_CHN_CNT `constants`

##### Summary

Brazil1 Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-BR2_CHN_CNT'></a>
### BR2_CHN_CNT `constants`

##### Summary

Brazil2 Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-BR3_CHN_CNT'></a>
### BR3_CHN_CNT `constants`

##### Summary

Brazil3 Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-BR4_CHN_CNT'></a>
### BR4_CHN_CNT `constants`

##### Summary

Brazil2 Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-BR5_CHN_CNT'></a>
### BR5_CHN_CNT `constants`

##### Summary

Brazil2 Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-CHN10TableOfFreq'></a>
### CHN10TableOfFreq `constants`

##### Summary

China Frequency Table

<a name='F-CSLibrary-HighLevelInterface-CHN11TableOfFreq'></a>
### CHN11TableOfFreq `constants`

##### Summary

China Frequency Table

<a name='F-CSLibrary-HighLevelInterface-CHN12TableOfFreq'></a>
### CHN12TableOfFreq `constants`

##### Summary

China Frequency Table

<a name='F-CSLibrary-HighLevelInterface-CHN1TableOfFreq'></a>
### CHN1TableOfFreq `constants`

##### Summary

China Frequency Table

<a name='F-CSLibrary-HighLevelInterface-CHN2TableOfFreq'></a>
### CHN2TableOfFreq `constants`

##### Summary

China Frequency Table

<a name='F-CSLibrary-HighLevelInterface-CHN3TableOfFreq'></a>
### CHN3TableOfFreq `constants`

##### Summary

China Frequency Table

<a name='F-CSLibrary-HighLevelInterface-CHN4TableOfFreq'></a>
### CHN4TableOfFreq `constants`

##### Summary

China Frequency Table

<a name='F-CSLibrary-HighLevelInterface-CHN5TableOfFreq'></a>
### CHN5TableOfFreq `constants`

##### Summary

China Frequency Table

<a name='F-CSLibrary-HighLevelInterface-CHN6TableOfFreq'></a>
### CHN6TableOfFreq `constants`

##### Summary

China Frequency Table

<a name='F-CSLibrary-HighLevelInterface-CHN7TableOfFreq'></a>
### CHN7TableOfFreq `constants`

##### Summary

China Frequency Table

<a name='F-CSLibrary-HighLevelInterface-CHN8TableOfFreq'></a>
### CHN8TableOfFreq `constants`

##### Summary

China Frequency Table

<a name='F-CSLibrary-HighLevelInterface-CHN9TableOfFreq'></a>
### CHN9TableOfFreq `constants`

##### Summary

China Frequency Table

<a name='F-CSLibrary-HighLevelInterface-CHNTableOfFreq'></a>
### CHNTableOfFreq `constants`

##### Summary

China Frequency Table

<a name='F-CSLibrary-HighLevelInterface-CN1_CHN_CNT'></a>
### CN1_CHN_CNT `constants`

##### Summary

China Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-CN9_CHN_CNT'></a>
### CN9_CHN_CNT `constants`

##### Summary

China Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-CN_CHN_CNT'></a>
### CN_CHN_CNT `constants`

##### Summary

China Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-CurrentPath'></a>
### CurrentPath `constants`

##### Summary

Current Path

<a name='F-CSLibrary-HighLevelInterface-ETSITableOfFreq'></a>
### ETSITableOfFreq `constants`

##### Summary

ETSI, G800 and India Frequency Table

<a name='F-CSLibrary-HighLevelInterface-ETSIUPPERBAND_CHN_CNT'></a>
### ETSIUPPERBAND_CHN_CNT `constants`

##### Summary

Brazil1 Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-ETSI_CHN_CNT'></a>
### ETSI_CHN_CNT `constants`

##### Summary

ETSI Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-FCCTableOfFreq'></a>
### FCCTableOfFreq `constants`

##### Summary

FCC Frequency Table

<a name='F-CSLibrary-HighLevelInterface-FCC_CHN_CNT'></a>
### FCC_CHN_CNT `constants`

##### Summary

FCC Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-HKTableOfFreq'></a>
### HKTableOfFreq `constants`

##### Summary

Hong Kong and Singapo Frequency Table

<a name='F-CSLibrary-HighLevelInterface-HK_CHN_CNT'></a>
### HK_CHN_CNT `constants`

##### Summary

Hong Kong Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-IDATableOfFreq'></a>
### IDATableOfFreq `constants`

##### Summary

India Frequency Table

<a name='F-CSLibrary-HighLevelInterface-IDA_CHN_CNT'></a>
### IDA_CHN_CNT `constants`

##### Summary

India Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-IDTableOfFreq'></a>
### IDTableOfFreq `constants`

##### Summary

Indonesia Frequency Table

<a name='F-CSLibrary-HighLevelInterface-ID_CHN_CNT'></a>
### ID_CHN_CNT `constants`

##### Summary

Indonesia Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-JE_CHN_CNT'></a>
### JE_CHN_CNT `constants`

##### Summary

Brazil1 Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-JPN2012TableOfFreq'></a>
### JPN2012TableOfFreq `constants`

##### Summary

Japan 2012 Frequency Table

<a name='F-CSLibrary-HighLevelInterface-JPN2012_CHN_CNT'></a>
### JPN2012_CHN_CNT `constants`

##### Summary

Japan Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-JPN2019TableOfFreq'></a>
### JPN2019TableOfFreq `constants`

##### Summary

Japan 2012 Frequency Table

<a name='F-CSLibrary-HighLevelInterface-JPN2019_CHN_CNT'></a>
### JPN2019_CHN_CNT `constants`

##### Summary

Japan Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-JPNTableOfFreq'></a>
### JPNTableOfFreq `constants`

##### Summary

Japan Frequency Table

<a name='F-CSLibrary-HighLevelInterface-JPNTableOfFreq29'></a>
### JPNTableOfFreq29 `constants`

##### Summary

Japan Frequency Table

<a name='F-CSLibrary-HighLevelInterface-JPN_CHN_CNT'></a>
### JPN_CHN_CNT `constants`

##### Summary

Japan Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-KRTableOfFreq'></a>
### KRTableOfFreq `constants`

##### Summary

Korea Frequency Table

<a name='F-CSLibrary-HighLevelInterface-KR_CHN_CNT'></a>
### KR_CHN_CNT `constants`

##### Summary

Korea Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-LH1_CHN_CNT'></a>
### LH1_CHN_CNT `constants`

##### Summary

Brazil1 Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-LH2_CHN_CNT'></a>
### LH2_CHN_CNT `constants`

##### Summary

Brazil1 Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-LH_CHN_CNT'></a>
### LH_CHN_CNT `constants`

##### Summary

Brazil1 Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-MYSTableOfFreq'></a>
### MYSTableOfFreq `constants`

##### Summary

Malaysia Frequency Table

<a name='F-CSLibrary-HighLevelInterface-MYS_CHN_CNT'></a>
### MYS_CHN_CNT `constants`

##### Summary

Malaysia Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-MacErrorCode'></a>
### MacErrorCode `constants`

##### Summary

current MacErrorCode

<a name='F-CSLibrary-HighLevelInterface-NZ_CHN_CNT'></a>
### NZ_CHN_CNT `constants`

##### Summary

Brazil1 Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-OFCATableOfFreq'></a>
### OFCATableOfFreq `constants`

##### Summary

Hong Kong and Singapo Frequency Table

<a name='F-CSLibrary-HighLevelInterface-OFCA_CHN_CNT'></a>
### OFCA_CHN_CNT `constants`

##### Summary

Hong Kong Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-PH_CHN_CNT'></a>
### PH_CHN_CNT `constants`

##### Summary

Brazil1 Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-SAHopping_CHN_CNT'></a>
### SAHopping_CHN_CNT `constants`

##### Summary

FCC Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-TW2_CHN_CNT'></a>
### TW2_CHN_CNT `constants`

##### Summary

Taiwan Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-TWTableOfFreq'></a>
### TWTableOfFreq `constants`

##### Summary

Taiwan Frequency Table

<a name='F-CSLibrary-HighLevelInterface-TW_CHN_CNT'></a>
### TW_CHN_CNT `constants`

##### Summary

Taiwan Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-UH1TableOfFreq'></a>
### UH1TableOfFreq `constants`

##### Summary

FCC UH Frequency Table 915-920

<a name='F-CSLibrary-HighLevelInterface-UH1_CHN_CNT'></a>
### UH1_CHN_CNT `constants`

##### Summary

FCC UH Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-UH2TableOfFreq'></a>
### UH2TableOfFreq `constants`

##### Summary

FCC UH Frequency Table 920-928

<a name='F-CSLibrary-HighLevelInterface-UH2_CHN_CNT'></a>
### UH2_CHN_CNT `constants`

##### Summary

FCC UH Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-VE_CHN_CNT'></a>
### VE_CHN_CNT `constants`

##### Summary

FCC Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-ZATableOfFreq'></a>
### ZATableOfFreq `constants`

##### Summary

South Africa Frequency Table

<a name='F-CSLibrary-HighLevelInterface-ZA_CHN_CNT'></a>
### ZA_CHN_CNT `constants`

##### Summary

FCC Frequency Channel number

<a name='F-CSLibrary-HighLevelInterface-_RegisterAccessLock'></a>
### _RegisterAccessLock `constants`

##### Summary

Read Register

<a name='F-CSLibrary-HighLevelInterface-m_oem_machine'></a>
### m_oem_machine `constants`

##### Summary

OEM value

<a name='P-CSLibrary-HighLevelInterface-AntennaPortSequence'></a>
### AntennaPortSequence `property`

##### Summary

Antenna list

<a name='P-CSLibrary-HighLevelInterface-AntennaSequenceSize'></a>
### AntennaSequenceSize `property`

##### Summary

Antenna sequence size for SEQUENCE MODE

<a name='P-CSLibrary-HighLevelInterface-CurrentFreqChannelIndex'></a>
### CurrentFreqChannelIndex `property`

##### Summary

Get Current Freq Channel Index

<a name='P-CSLibrary-HighLevelInterface-CurrentInterfaceType'></a>
### CurrentInterfaceType `property`

##### Summary

Get Communication Interface Type

<a name='P-CSLibrary-HighLevelInterface-DeviceNameOrIP'></a>
### DeviceNameOrIP `property`

##### Summary

Get Reader connection name

<a name='P-CSLibrary-HighLevelInterface-IPAddress'></a>
### IPAddress `property`

##### Summary

Get IP Address

<a name='P-CSLibrary-HighLevelInterface-IsFixedChannel'></a>
### IsFixedChannel `property`

##### Summary

Get Fixed frequency channel

<a name='P-CSLibrary-HighLevelInterface-IsFixedChannelOnly'></a>
### IsFixedChannelOnly `property`

##### Summary

If true, it can only set to fixed channel.
Otherwise, both fixed and hopping can be set.

<a name='P-CSLibrary-HighLevelInterface-IsHoppingChannelOnly'></a>
### IsHoppingChannelOnly `property`

##### Summary

If true, it can only set to hopping channel.

<a name='P-CSLibrary-HighLevelInterface-LBT_ON'></a>
### LBT_ON `property`

##### Summary

Get Current LBT status

<a name='P-CSLibrary-HighLevelInterface-LastErrorMessage'></a>
### LastErrorMessage `property`

##### Summary

get last function return error messsage

<a name='P-CSLibrary-HighLevelInterface-LastResultCode'></a>
### LastResultCode `property`

##### Summary

get last function return code

<a name='P-CSLibrary-HighLevelInterface-MacAddress'></a>
### MacAddress `property`

##### Summary

Get MAC Address

<a name='P-CSLibrary-HighLevelInterface-Name'></a>
### Name `property`

##### Summary

Get or Set Reader Name

<a name='P-CSLibrary-HighLevelInterface-Options'></a>
### Options `property`

##### Summary

CSLibrary Operation parameters
Notes : you must config this parameters before perform any operation

<a name='P-CSLibrary-HighLevelInterface-ReconnectTimeout'></a>
### ReconnectTimeout `property`

##### Summary

Reconnect Timeout

<a name='P-CSLibrary-HighLevelInterface-SelectedChannel'></a>
### SelectedChannel `property`

##### Summary

Get Current Selected Frequency Channel

<a name='P-CSLibrary-HighLevelInterface-SelectedFrequencyBand'></a>
### SelectedFrequencyBand `property`

##### Summary

Get current frequency

<a name='P-CSLibrary-HighLevelInterface-SelectedLinkProfile'></a>
### SelectedLinkProfile `property`

##### Summary

Current selected frequency

<a name='P-CSLibrary-HighLevelInterface-SelectedPowerLevel'></a>
### SelectedPowerLevel `property`

##### Summary

Get current power level

<a name='P-CSLibrary-HighLevelInterface-SelectedRegionCode'></a>
### SelectedRegionCode `property`

##### Summary

Get Region Profile

<a name='P-CSLibrary-HighLevelInterface-State'></a>
### State `property`

##### Summary

Current Operation State

<a name='M-CSLibrary-HighLevelInterface-COMM_AdapterCommand-CSLibrary-HighLevelInterface-READERCMD-'></a>
### COMM_AdapterCommand() `method`

##### Summary

Send Command to Reader

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-COMM_Disconnect'></a>
### COMM_Disconnect() `method`

##### Summary

Disconnect

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-COMM_READER_Recv-System-Byte[],System-Int32,System-Int32,System-UInt32-'></a>
### COMM_READER_Recv() `method`

##### Summary

Receive data from Reader

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-COMM_READER_Send-System-Byte[],System-Int32,System-Int32,System-Int32-'></a>
### COMM_READER_Send() `method`

##### Summary

Send data to Reader

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-COMM_Reboot'></a>
### COMM_Reboot(cmd) `method`

##### Summary

Reset device

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| cmd | [M:CSLibrary.HighLevelInterface.COMM_Reboot](#T-M-CSLibrary-HighLevelInterface-COMM_Reboot 'M:CSLibrary.HighLevelInterface.COMM_Reboot') |  |

<a name='M-CSLibrary-HighLevelInterface-CUST_18K6CTagBlockWrite-CSLibrary-Constants-MemoryBank,System-UInt32,System-UInt32,System-UInt16[],System-UInt32,System-UInt32,System-UInt32,CSLibrary-Constants-SelectFlags-'></a>
### CUST_18K6CTagBlockWrite(bank,offset,count,data,password,retry,flags) `method`

##### Summary



##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| bank | [CSLibrary.Constants.MemoryBank](#T-CSLibrary-Constants-MemoryBank 'CSLibrary.Constants.MemoryBank') |  |
| offset | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| count | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| data | [System.UInt16[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16[] 'System.UInt16[]') |  |
| password | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| retry | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| flags | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |

<a name='M-CSLibrary-HighLevelInterface-CUST_18K6CTagWrite-CSLibrary-Constants-MemoryBank,System-UInt32,System-UInt32,System-UInt16[],System-UInt32,System-UInt32,System-UInt32,CSLibrary-Constants-SelectFlags-'></a>
### CUST_18K6CTagWrite(bank,offset,count,data,password,retry,flags) `method`

##### Summary



##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| bank | [CSLibrary.Constants.MemoryBank](#T-CSLibrary-Constants-MemoryBank 'CSLibrary.Constants.MemoryBank') |  |
| offset | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| count | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| data | [System.UInt16[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16[] 'System.UInt16[]') |  |
| password | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| retry | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| flags | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |

<a name='M-CSLibrary-HighLevelInterface-CheckStatus-CSLibrary-Structures-DEVICE_STATUS@-'></a>
### CheckStatus() `method`

##### Summary

Check Status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-CheckStatus-System-String,System-String,CSLibrary-Structures-DEVICE_STATUS@-'></a>
### CheckStatus() `method`

##### Summary

Check Status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-CheckStatus-System-String,CSLibrary-Structures-DEVICE_STATUS@-'></a>
### CheckStatus() `method`

##### Summary

Check Status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-ColdChain_StartTemperatureLog-System-UInt32,System-UInt16,System-Byte-'></a>
### ColdChain_StartTemperatureLog(StartTime,Interval,Offset) `method`

##### Summary

only for ColdChain IC card

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| StartTime | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| Interval | [System.UInt16](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16 'System.UInt16') |  |
| Offset | [System.Byte](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte 'System.Byte') |  |

<a name='M-CSLibrary-HighLevelInterface-Connect'></a>
### Connect() `method`

##### Summary

Connect CS101 intenal reader and allocate resources
(only for CS101 internal reader)

##### Returns

Result

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-Connect-System-String,System-Int32,System-Boolean-'></a>
### Connect(ipAddress,timeout,libraryDebug) `method`

##### Summary

Face out command, please use Connect(string ipAddress, int timeout);

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| ipAddress | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |  |
| timeout | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |
| libraryDebug | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') |  |

<a name='M-CSLibrary-HighLevelInterface-CreateDynamicQParms-System-UInt32,System-UInt32,System-UInt32,System-UInt32,System-UInt32,System-UInt32-'></a>
### CreateDynamicQParms(startQValue,maxQValue,minQValue,retryCount,toggleTarget,thresholdMultiplier) `method`

##### Summary

Create DynamicQ parameter

##### Returns

DynamicQThresholdParms

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| startQValue | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The starting Q value to use.  Valid values are 0-15, inclusive.  
startQValue must be greater than or equal to minQValue and 
less than or equal to maxQValue. |
| maxQValue | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The maximum Q value to use.  Valid values are 0-15, inclusive.  
maxQValue must be greater than or equal to startQValue and 
minQValue. |
| minQValue | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The minimum Q value to use.  Valid values are 0-15, inclusive.  
minQValue must be less than or equal to startQValue and 
maxQValue. |
| retryCount | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Specifies the number of times to try another execution 
of the singulation algorithm for the specified 
session/target before either toggling the target (if 
toggleTarget is non-zero) or terminating the 
inventory/tag access operation.  Valid values are 0-255, 
inclusive. |
| toggleTarget | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | A flag that indicates if, after performing the inventory cycle for the 
specified target (i.e., A or B), if the target should be toggled (i.e., 
A to B or B to A) and another inventory cycle run.  A non-zero 
value indicates that the target should be toggled.  A zero value 
indicates that the target should not be toggled.  Note that if the 
target is toggled, retryCount and maxQueryRepCount will 
also apply to the new target. |
| thresholdMultiplier | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The multiplier, specified in units of fourths (i.e., 0.25), that will be 
applied to the Q-adjustment threshold as part of the dynamic-Q 
algorithm.  For example, a value of 7 represents a multiplier of 
1.75.  See [MAC-EDS] for specifics on how the Q-adjustment 
threshold is used in the dynamic Q algorithm.  Valid values are 0-
255, inclusive. |

<a name='M-CSLibrary-HighLevelInterface-CreateFixedQParms-System-UInt32,System-UInt32,System-UInt32,System-UInt32-'></a>
### CreateFixedQParms(qValue,retryCount,toggleTarget,repeatUntilNoTags) `method`

##### Summary

Create FixedQ parameter

##### Returns

FixedQParms

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| qValue | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The Q value to use. Valid values are 0-15, inclusive. |
| retryCount | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Specifies the number of times to try another execution 
of the singulation algorithm for the specified 
session/target before either toggling the target (if 
toggleTarget is non-zero) or terminating the 
inventory/tag access operation.  Valid values are 0-
255, inclusive. |
| toggleTarget | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | A flag that indicates if, after performing the inventory cycle for 
the specified target (i.e., A or B), if the target should be toggled 
(i.e., A to B or B to A) and another inventory cycle run.  A non-
zero value indicates that the target should be toggled.  A zero 
value indicates that the target should not be toggled.  Note that 
if the target is toggled, retryCount and 
repeatUntilNoTags will also apply to the new target. |
| repeatUntilNoTags | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | A flag that indicates whether or not the singulation 
algorithm should continue performing inventory rounds 
until no tags are singulated.  A non-zero value indicates 
that, for each execution of the singulation algorithm, 
inventory rounds should be performed until no tags are 
singulated.  A zero value indicates that a single 
inventory round should be performed for each 
execution of the singulation algorithm. |

<a name='M-CSLibrary-HighLevelInterface-CreatePostMatchCriteria-System-UInt32,System-UInt32,System-Boolean,System-Byte[]-'></a>
### CreatePostMatchCriteria(Offset,Count,match,bTarget) `method`

##### Summary

Create PostMatchCriteria parms

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| Offset | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The offset in bits, from the start of the Electronic Product 
Code (EPC), of the first bit that will be matched against the 
mask.  If offset falls beyond the end of EPC, the tag is 
considered non-matching. |
| Count | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The number of bits in the mask.  A length of zero will cause 
all tags to match.  If (offset+count) falls beyond the end 
of the EPC, the tag is considered non-matching.  Valid 
values are 0 to 496, inclusive. |
| match | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') | Determines if the associated tag-protocol operation will be 
applied to tags that match the mask or not.  A non-zero 
value indicates that the tag-protocol operation should be 
applied to tags that match the mask.  A value of zero 
indicates that the tag-protocol operation should be applied 
to tags that do not match the mask. |
| bTarget | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | A buffer that contains a left-justified bit array that represents 
that bit pattern to match – i.e., the most significant bit of the 
bit array appears in the most-significant bit (i.e., bit 7) of the 
first byte of the buffer (i.e., mask[0]).  All bits beyond count 
are ignored.  For example, if the application wished to find 
tags with the following 16 bits 1011.1111.1010.0101, 
starting at offset 20 in the Electronic Product Code, then the 
fields would be set as follows: 
offset  = 20 
count   = 16 
mask[0] = 0xBF (1011.1111) 
mask[1] = 0xA5 (1010.0101) |

<a name='M-CSLibrary-HighLevelInterface-CreateSelectCriteria-System-UInt32,System-UInt32,CSLibrary-Constants-MemoryBank,CSLibrary-Constants-Action,CSLibrary-Constants-Target,System-Boolean,System-Byte[]-'></a>
### CreateSelectCriteria(Offset,Count,bnk,action,target,enableTruncate,bTarget) `method`

##### Summary

Create SelectCriteria parms

##### Returns

SelectCriteria

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| Offset | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The offset, in bits, from the start of the memory bank, of the 
first bit that will be matched against the mask.  If offset falls 
beyond the end of the memory bank, the tag is considered 
non-matching. |
| Count | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The number of bits in the mask.  A length of zero will cause all 
tags to match.  If (offset+count) falls beyond the end of 
the memory bank, the tag is considered non-matching.  Valid 
values are 0 to 255, inclusive. |
| bnk | [CSLibrary.Constants.MemoryBank](#T-CSLibrary-Constants-MemoryBank 'CSLibrary.Constants.MemoryBank') | The memory bank that contains the bits that will be compared 
against the bit pattern specified in mask.  For a tag mask, 
RFID_18K6C_MEMORY_BANK_RESERVED is not a valid value. |
| action | [CSLibrary.Constants.Action](#T-CSLibrary-Constants-Action 'CSLibrary.Constants.Action') | Specifies the action that will be applied to the tag populations (i.e, the 
matching and non-matching tags). |
| target | [CSLibrary.Constants.Target](#T-CSLibrary-Constants-Target 'CSLibrary.Constants.Target') | Specifies what flag, selected (i.e., SL) or one of the four inventory 
flags (i.e., S0, S1, S2, or S3), will be modified by the action. |
| enableTruncate | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') | Specifies if, during singulation, a tag will respond to a subsequent 
inventory operation with its entire Electronic Product Code (EPC) or 
will only respond with the portion of the EPC that immediately follows 
the bit pattern (as long as the bit pattern falls within the EPC – if the 
bit pattern does not fall within the tag's EPC, the tag ignores the tag 
partitioning operation2).  If this parameter is non-zero: 
?     bank must be RFID_18K6C_MEMORY_BANK_EPC. 
?     target must be RFID_18K6C_TARGET_SELECTED_FLAG. 
This action must correspond to the last tag select operation issued 
before the inventory operation or access command. |
| bTarget | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | A buffer that contains a left-justified bit array that represents 
that bit pattern to match – i.e., the most significant bit of the bit 
array appears in the most-significant bit (i.e., bit 7) of the first 
byte of the buffer (i.e., mask[0]).  All bits beyond count are 
ignored. |

<a name='M-CSLibrary-HighLevelInterface-CreateTagGroup-CSLibrary-Constants-Selected,CSLibrary-Constants-Session,CSLibrary-Constants-SessionTarget-'></a>
### CreateTagGroup(select,session,target) `method`

##### Summary

Create TagGroup parameter

##### Returns

TagGroup

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| select | [CSLibrary.Constants.Selected](#T-CSLibrary-Constants-Selected 'CSLibrary.Constants.Selected') | Specifies the state of the selected (SL) flag for tags that will have 
the operation applied to them. |
| session | [CSLibrary.Constants.Session](#T-CSLibrary-Constants-Session 'CSLibrary.Constants.Session') | Specifies which inventory session flag (i.e., S0, S1, S2, or S3) 
will be matched against the inventory state specified by target. |
| target | [CSLibrary.Constants.SessionTarget](#T-CSLibrary-Constants-SessionTarget 'CSLibrary.Constants.SessionTarget') | Specifies the state of the inventory session flag (i.e., A or B), 
specified by session, for tags that will have the operation 
applied to them. |

<a name='M-CSLibrary-HighLevelInterface-DirectSearch-System-Net-IPAddress,CSLibrary-Net-DeviceInfomation@-'></a>
### DirectSearch(IP) `method`

##### Summary

Direct search reader and return mode status

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| IP | [System.Net.IPAddress](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Net.IPAddress 'System.Net.IPAddress') |  |

<a name='M-CSLibrary-HighLevelInterface-Disconnect'></a>
### Disconnect() `method`

##### Summary

Disconnect reader and free resources

##### Returns

Return OK if Success

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-Dispose'></a>
### Dispose() `method`

##### Summary

Destructor

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-EngBypassReadRegister-System-UInt16,System-UInt16@-'></a>
### EngBypassReadRegister(address,value) `method`

##### Summary

Reads directly from a radio-module hardware register.  The radio 
module's hardware registers may not be read while a radio module 
is executing a tag-protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| address | [System.UInt16](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16 'System.UInt16') | The 16-bit address of the radio-module hardware 
register to be read.  An address that is beyond the end 
of the radio module's register set Results in an invalid-
parameter return status. |
| value | [System.UInt16@](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16@ 'System.UInt16@') | A 16-bit value that will receive the value 
in the radio-module hardware register specified by 
address. |

<a name='M-CSLibrary-HighLevelInterface-EngBypassWriteRegister-System-UInt16,System-UInt16-'></a>
### EngBypassWriteRegister(address,value) `method`

##### Summary

Writes directly to a radio-module hardware register.  The radio 
module's hardware registers may not be written while a radio 
module is executing a tag-protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| address | [System.UInt16](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16 'System.UInt16') | The 16-bit address of the radio-module hardware 
register to be written.  An address that is beyond the 
end of the radio module's register set Results in an 
invalid-parameter return status. |
| value | [System.UInt16](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16 'System.UInt16') | The 16-bit value to write to the radio-module 
hardware register specified by address. |

<a name='M-CSLibrary-HighLevelInterface-EngGetReaderDataFormat-CSLibrary-Constants-ResponseMode@-'></a>
### EngGetReaderDataFormat(mode) `method`

##### Summary

Allows the application to retrieve the mode of data reporting for 
tag-access operations.  The data-reporting mode may not be 
retrieved while a radio module is executing a tag-protocol 
operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| mode | [CSLibrary.Constants.ResponseMode@](#T-CSLibrary-Constants-ResponseMode@ 'CSLibrary.Constants.ResponseMode@') | return will contain  
the operation-response data reporting 
mode for the data type specifed by 
responseType. |

<a name='M-CSLibrary-HighLevelInterface-EngModeEnable-System-String-'></a>
### EngModeEnable(Password) `method`

##### Summary

Enable Engineering Mode

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| Password | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |  |

<a name='M-CSLibrary-HighLevelInterface-EngReadOemData-System-UInt32,System-UInt32@-'></a>
### EngReadOemData(address,value) `method`

##### Summary

Reads one or more 32-bit values from the MAC's OEM 
configuration data area.  Note that the the 32-bit values read from 
the OEM configuration data area are in the R1000 Firmware-
processor endian format and it is the responsibility of the 
application to convert to the endian format of the host processor.  
The MAC's OEM configuration data area may not be read while a 
radio module is executing a tag-protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| address | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The address of the first 32-bit value to read from the 
MAC's OEM configuration data area.  Note that the 
address is a 32-bit word address, and not a byte 
address – i.e., address 1 is actually byte 4, address 2 
is actually byte 8, etc.  An address that is beyond the 
end of the OEM configuration data area Results in an 
invalid-parameter error. |
| value | [System.UInt32@](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32@ 'System.UInt32@') | Return  the data from MAC's OEM 
configuration data area.  The 32-bit values returned 
are in the MAC's native format (i.e., little endian). |

<a name='M-CSLibrary-HighLevelInterface-EngReadRegister-System-UInt16,System-UInt32@-'></a>
### EngReadRegister() `method`

##### Summary

Read Register

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-EngSetInterface-CSLibrary-HighLevelInterface-INTERFACETYPE-'></a>
### EngSetInterface(Mode) `method`

##### Summary

Set connection intergface

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| Mode | [CSLibrary.HighLevelInterface.INTERFACETYPE](#T-CSLibrary-HighLevelInterface-INTERFACETYPE 'CSLibrary.HighLevelInterface.INTERFACETYPE') |  |

<a name='M-CSLibrary-HighLevelInterface-EngSetReaderDataFormat-CSLibrary-Constants-ResponseMode-'></a>
### EngSetReaderDataFormat(mode) `method`

##### Summary

Allows the application to control the mode of data reporting for 
tag-access operations.  By default, when an application opens a 
radio, the RFID Reader Library sets the reporting mode to 
"normal".  The data-reporting mode will remain in effect until a 
subsequent call to RFID_RadioSetResponseDataMode, or the radio 
is closed and re-opened (at which point the data mode is set to 
normal).  The data-reporting mode may not be changed while a 
radio module is executing a tag-protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| mode | [CSLibrary.Constants.ResponseMode](#T-CSLibrary-Constants-ResponseMode 'CSLibrary.Constants.ResponseMode') | The requested data-reporting mode for 
the data type specified by 
responseType |

<a name='M-CSLibrary-HighLevelInterface-EngTest_TransmitRandomData-System-Boolean,System-Int32-'></a>
### EngTest_TransmitRandomData(enable,randomPattern) `method`

##### Summary

randomPattern = 0 : 4096 bit
    1 : 511 bit

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| enable | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') |  |
| randomPattern | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |

<a name='M-CSLibrary-HighLevelInterface-EngUpdateFirmware-System-UInt32,CSLibrary-Structures-NonVolatileMemoryBlock[],CSLibrary-Constants-FwUpdateFlags-'></a>
### EngUpdateFirmware(length,pImage,flags) `method`

##### Summary

Writes the specified data to the radio module's nonvolatile-
memory block(s).  After a successful update, the RFID radio 
module resets itself and the RFID Reader Library closes and 
invalidates the radio m_radioIndex so that it may no longer be used by 
the application.  To obtain control of the radio again, the 
application must re-enumerate, via 
RFID_RetrieveAttachedRadiosList, the radio modules in the 
system and request control of the radio again via 
RFID_RadioOpen. 
In the case of an unsuccessful update and depending upon the 
underlying cause for the returned failure status, the radio 
module's nonvolatile memory may be left in an undefined state, 
which means that the radio module may be in an unusable state.  
In this situation, the RFID Reader Library does not invalidate the 
radio m_radioIndex – i.e., it is the application's responsibility to close the 
m_radioIndex. 
Alternatively, an application can perform the update in "test" 
mode.  An application uses the "test" mode, by checking the 
returned status, to verify that the update would succeed before 
performing the destructive update of the radio module's 
nonvolatile memory.  When a "test" update has completed, either 
successfully or unsuccessfully, the MAC firmware returns to its 
normal idle state and the radio m_radioIndex remains valid (indicating 
that the application is still responsible for closing it). 
The radio module's nonvolatile memory may not be updated while 
a radio module is executing a tag-protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| length | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The number of nonvolatile memory blocks in 
the array pointed to by pBlocks.  This value 
must be greater than zero. |
| pImage | [CSLibrary.Structures.NonVolatileMemoryBlock[]](#T-CSLibrary-Structures-NonVolatileMemoryBlock[] 'CSLibrary.Structures.NonVolatileMemoryBlock[]') | An array of countBlocks nonvolatile 
memory block structures that are used to control the update 
of the radio module's nonvolatile memory.  This 
pointer must not be NULL. |
| flags | [CSLibrary.Constants.FwUpdateFlags](#T-CSLibrary-Constants-FwUpdateFlags 'CSLibrary.Constants.FwUpdateFlags') | Firmware update flags |

<a name='M-CSLibrary-HighLevelInterface-EngWriteOemData-System-UInt32,System-UInt32-'></a>
### EngWriteOemData(address,value) `method`

##### Summary

Writes one or more 32-bit values to the MAC's OEM configuration 
data area.  Note that it is the responsibility of the application 
programmer to ensure that the 32-bit values written to the OEM 
configuration data area areconverted from the host-processor 
endian format to the MAC-processor endian format before they are 
written.  The MAC's OEM configuration data area may not be 
written while a radio module is executing a tag-protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| address | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The 32-bit address into the MAC's OEM configuration 
data area where the first 32-bit data word is to be 
written.  Note that the address is a 32-bit address, and 
not a byte address – i.e., address 1 is actually byte 4, 
address 2 is actually byte 8, etc.  An address that is 
beyond the end of the OEM configuration data area 
Results in an invalid-parameter error. |
| value | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | A 32-bit unsigned integers 
that contains the data to be written into the MAC's 
OEM configuration data area.  The 32-bit values 
provided must be in the MAC's native format (i.e., 
little endian).  This parameter must not be NULL. |

<a name='M-CSLibrary-HighLevelInterface-EngWriteRegister-System-UInt16,System-UInt32-'></a>
### EngWriteRegister() `method`

##### Summary

Write Register

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-Finalize'></a>
### Finalize() `method`

##### Summary

Destructor

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-FireOnFirmwareUpgradeEvent-System-UInt64-'></a>
### FireOnFirmwareUpgradeEvent(Offset) `method`

##### Summary

if 0 = First time reboot, 0xffffffffffffffff = second time reboot, write offset address

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| Offset | [System.UInt64](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt64 'System.UInt64') |  |

<a name='M-CSLibrary-HighLevelInterface-ForceReset'></a>
### ForceReset() `method`

##### Summary

Force reset device

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-ForceReset-System-String,System-String-'></a>
### ForceReset() `method`

##### Summary

Force reset device

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-ForceReset-System-String-'></a>
### ForceReset() `method`

##### Summary

Force reset device

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetActiveLinkProfile-CSLibrary-Constants-RegionCode-'></a>
### GetActiveLinkProfile(region) `method`

##### Summary

Available Link Profile you can use on specific region

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| region | [CSLibrary.Constants.RegionCode](#T-CSLibrary-Constants-RegionCode 'CSLibrary.Constants.RegionCode') |  |

<a name='M-CSLibrary-HighLevelInterface-GetActiveLinkProfile'></a>
### GetActiveLinkProfile() `method`

##### Summary

Available Link Profile you can use on current region

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetActiveLinkProfileInfo'></a>
### GetActiveLinkProfileInfo() `method`

##### Summary

Get Current active LinkProfile information

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetActiveLinkProfileInfo-System-UInt32-'></a>
### GetActiveLinkProfileInfo() `method`

##### Summary

Get Current active LinkProfile information

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetActiveMaxPowerLevel-CSLibrary-Constants-RegionCode-'></a>
### GetActiveMaxPowerLevel() `method`

##### Summary

Available Maximum Power you can set on specific region

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetActiveMaxPowerLevel'></a>
### GetActiveMaxPowerLevel() `method`

##### Summary

Available Maximum Power you can set on current region

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetActiveRegionCode'></a>
### GetActiveRegionCode() `method`

##### Summary

Available region you can use

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetAntennaPortConfiguration-CSLibrary-Structures-AntennaPortConfig@-'></a>
### GetAntennaPortConfiguration(antenna) `method`

##### Summary

Allows an application to retrieve a single logical antenna port's 
configuration parameters  e.g., dwell time, power level, and 
number of inventory cycles.  Even if the logical antenna port is 
disabled, an application is allowed to retrieve these configuration 
parameters.  Retrieving configuration parameters does not cause a 
logical antenna port to be automatically enabled; the application 
must still enable the logical antenna port via 
RFID_AntennaPortSetState.  The antenna-port configuration 
cannot be retrieved while a radio module is executing a tag-
protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| antenna | [CSLibrary.Structures.AntennaPortConfig@](#T-CSLibrary-Structures-AntennaPortConfig@ 'CSLibrary.Structures.AntennaPortConfig@') | A structure that upon return will 
contain the antenna-port configuration 
parameters. |

<a name='M-CSLibrary-HighLevelInterface-GetAntennaPortConfiguration-System-UInt32,CSLibrary-Structures-AntennaPortConfig@-'></a>
### GetAntennaPortConfiguration(port,antenna) `method`

##### Summary

Allows an application to retrieve a single logical antenna port's 
configuration parameters  e.g., dwell time, power level, and 
number of inventory cycles.  Even if the logical antenna port is 
disabled, an application is allowed to retrieve these configuration 
parameters.  Retrieving configuration parameters does not cause a 
logical antenna port to be automatically enabled; the application 
must still enable the logical antenna port via 
RFID_AntennaPortSetState.  The antenna-port configuration 
cannot be retrieved while a radio module is executing a tag-
protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| port | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | antenna-port |
| antenna | [CSLibrary.Structures.AntennaPortConfig@](#T-CSLibrary-Structures-AntennaPortConfig@ 'CSLibrary.Structures.AntennaPortConfig@') | A structure that upon return will 
contain the antenna-port configuration 
parameters. |

<a name='M-CSLibrary-HighLevelInterface-GetAntennaPortStatus-CSLibrary-Structures-AntennaPortStatus-'></a>
### GetAntennaPortStatus(portStatus) `method`

##### Summary

Retrieves the status of the requested logical antenna port for a 
particular radio module.  The antenna-port status cannot be 
retrieved while a radio module is executing a tag-protocol 
operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| portStatus | [CSLibrary.Structures.AntennaPortStatus](#T-CSLibrary-Structures-AntennaPortStatus 'CSLibrary.Structures.AntennaPortStatus') |  |

<a name='M-CSLibrary-HighLevelInterface-GetAntennaPortStatus-System-UInt32,CSLibrary-Structures-AntennaPortStatus-'></a>
### GetAntennaPortStatus(port,portStatus) `method`

##### Summary

Retrieves the status of the requested logical antenna port for a 
particular radio module.  The antenna-port status cannot be 
retrieved while a radio module is executing a tag-protocol 
operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| port | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | antenna port |
| portStatus | [CSLibrary.Structures.AntennaPortStatus](#T-CSLibrary-Structures-AntennaPortStatus 'CSLibrary.Structures.AntennaPortStatus') |  |

<a name='M-CSLibrary-HighLevelInterface-GetAntennaSequence-System-Byte[]-'></a>
### GetAntennaSequence(sequence) `method`

##### Summary

GetAntennaSequence

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| sequence | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |

<a name='M-CSLibrary-HighLevelInterface-GetAntennaSequence-System-Byte[],System-UInt32@,CSLibrary-Constants-AntennaSequenceMode@-'></a>
### GetAntennaSequence(sequence,sequenceSize,mode) `method`

##### Summary

GetAntennaSequence

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| sequence | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | Antenna Sequence |
| sequenceSize | [System.UInt32@](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32@ 'System.UInt32@') | Antenna Sequence Size |
| mode | [CSLibrary.Constants.AntennaSequenceMode@](#T-CSLibrary-Constants-AntennaSequenceMode@ 'CSLibrary.Constants.AntennaSequenceMode@') | Antenna Sequence Mode |

<a name='M-CSLibrary-HighLevelInterface-GetAvailableFrequencyTable-CSLibrary-Constants-RegionCode-'></a>
### GetAvailableFrequencyTable(region) `method`

##### Summary

Get frequency table on specific region

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| region | [CSLibrary.Constants.RegionCode](#T-CSLibrary-Constants-RegionCode 'CSLibrary.Constants.RegionCode') | Region Code |

<a name='M-CSLibrary-HighLevelInterface-GetAvailableFrequencyTable'></a>
### GetAvailableFrequencyTable() `method`

##### Summary

Get frequency table on current region

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetBootLoaderVersion-CSLibrary-Structures-Version-'></a>
### GetBootLoaderVersion(version) `method`

##### Summary

Get Silicon Lab Bootloader Version

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| version | [CSLibrary.Structures.Version](#T-CSLibrary-Structures-Version 'CSLibrary.Structures.Version') | version |

<a name='M-CSLibrary-HighLevelInterface-GetC51AppVersion'></a>
### GetC51AppVersion() `method`

##### Summary

Get Silicon Lab Application Version
Notes:Not support in future version

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetC51BootLoaderVersion'></a>
### GetC51BootLoaderVersion() `method`

##### Summary

Get Silicon Lab Bootloader Version
Notes:Not support in future version

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetCSLibraryVersion'></a>
### GetCSLibraryVersion() `method`

##### Summary

Get RFID CSharp Library Version

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetCountryCode-System-UInt32@-'></a>
### GetCountryCode() `method`

##### Summary

GetCountryCode

##### Returns

Result

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetCurrentFrequencyTable'></a>
### GetCurrentFrequencyTable() `method`

##### Summary

Get frequency table on current region

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetCurrentLinkProfile-System-UInt32@-'></a>
### GetCurrentLinkProfile() `method`

##### Summary

Allows the application to retrieve the current link profile for the 
 radio module.  The current link profile cannot be retrieved while a 
 radio module is executing a tag-protocol operation.

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetCurrentSingulationAlgorithm-CSLibrary-Constants-SingulationAlgorithm@-'></a>
### GetCurrentSingulationAlgorithm(SingulationAlgorithm) `method`

##### Summary

Get Current Singulation Algorithm

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| SingulationAlgorithm | [CSLibrary.Constants.SingulationAlgorithm@](#T-CSLibrary-Constants-SingulationAlgorithm@ 'CSLibrary.Constants.SingulationAlgorithm@') |  |

<a name='M-CSLibrary-HighLevelInterface-GetCurrentTemperature-CSLibrary-Structures-TemperatureParms@-'></a>
### GetCurrentTemperature() `method`

##### Summary

Get Current System Temperature
Don't get temperature during operation starting

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetDriverVersion'></a>
### GetDriverVersion() `method`

##### Summary

Get RFID Library Version

Note: This function is for backward compatibility only and will be deprecated in future version
Please use GetHardwareVersion() instead

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetDynamicQParms-CSLibrary-Structures-DynamicQParms-'></a>
### GetDynamicQParms(parms) `method`

##### Summary

Get DynamicQ Singulation Algorithm

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| parms | [CSLibrary.Structures.DynamicQParms](#T-CSLibrary-Structures-DynamicQParms 'CSLibrary.Structures.DynamicQParms') |  |

<a name='M-CSLibrary-HighLevelInterface-GetFirmwareVersion'></a>
### GetFirmwareVersion() `method`

##### Summary

GetFirmwareVersion

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetFixedQParms-CSLibrary-Structures-FixedQParms-'></a>
### GetFixedQParms(fixedQ) `method`

##### Summary

Get FixedQ Singulation Algorithm

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| fixedQ | [CSLibrary.Structures.FixedQParms](#T-CSLibrary-Structures-FixedQParms 'CSLibrary.Structures.FixedQParms') |  |

<a name='M-CSLibrary-HighLevelInterface-GetForwardPowerLevel-System-UInt32@-'></a>
### GetForwardPowerLevel() `method`

##### Summary

Get measurement of the PA output power level measured in 0.1 dBm units.

##### Returns

Result

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetFrequencyBand-System-UInt32,CSLibrary-Structures-FrequencyBandParms@-'></a>
### GetFrequencyBand(m_radioIndex,frequencySelector,freq) `method`

##### Summary

Get Frequency band - Basic function

##### Returns

FrequencyBandParms

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| m_radioIndex | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Input radio index |
| frequencySelector | [CSLibrary.Structures.FrequencyBandParms@](#T-CSLibrary-Structures-FrequencyBandParms@ 'CSLibrary.Structures.FrequencyBandParms@') | frequencySelector |

<a name='M-CSLibrary-HighLevelInterface-GetFrequencyCompensation-System-UInt32@,System-UInt32@-'></a>
### GetFrequencyCompensation(coeff0,coeff1) `method`

##### Summary

GetFrequencyCompensation

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| coeff0 | [System.UInt32@](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32@ 'System.UInt32@') | Frequency compensation coeff0. freq_induced_error = (coeff1 * freq) + 
coeff0.

bit 31 – sign bit (0=pos, 1=neg)

bits 30:0 – coeff0, in units of 0.001dB |
| coeff1 | [System.UInt32@](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32@ 'System.UInt32@') | Frequency compensation coeff1. freq_induced_error =
(coeff1 * freq) + coeff0

bit 31 – sign bit (0=pos, 1=neg)

bits 30:0 – coeff1, in units of 0.000001dB/MHz |

<a name='M-CSLibrary-HighLevelInterface-GetGPI0-System-String,System-Int32@-'></a>
### GetGPI0(ip,HL) `method`

##### Summary

Get GPI0 status

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| ip | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | Target IP |
| HL | [System.Int32@](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32@ 'System.Int32@') |  |

<a name='M-CSLibrary-HighLevelInterface-GetGPI0Status-System-String,System-Boolean@-'></a>
### GetGPI0Status() `method`

##### Summary

Check GPI0 port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetGPI0Status-System-Boolean@-'></a>
### GetGPI0Status() `method`

##### Summary

Check GPI0 port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetGPI1Status-System-String,System-Boolean@-'></a>
### GetGPI1Status() `method`

##### Summary

Check GPI1 port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetGPI1Status-System-Boolean@-'></a>
### GetGPI1Status() `method`

##### Summary

Check GPI1 port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetGPI2Status-System-String,System-Boolean@-'></a>
### GetGPI2Status() `method`

##### Summary

Check GPI0 port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetGPI2Status-System-Boolean@-'></a>
### GetGPI2Status() `method`

##### Summary

Check GPI0 port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetGPI3Status-System-String,System-Boolean@-'></a>
### GetGPI3Status() `method`

##### Summary

Check GPI1 port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetGPI3Status-System-Boolean@-'></a>
### GetGPI3Status() `method`

##### Summary

Check GPI1 port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetGPIInterrupt-System-String,CSLibrary-Constants-GPIOTrigger@,CSLibrary-Constants-GPIOTrigger@-'></a>
### GetGPIInterrupt() `method`

##### Summary

Get GPI0 trigger status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetGPIInterrupt-CSLibrary-Constants-GPIOTrigger@,CSLibrary-Constants-GPIOTrigger@-'></a>
### GetGPIInterrupt() `method`

##### Summary

Get GPI0 trigger status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetGPIStatus-System-String,System-Boolean@,System-Boolean@,System-Boolean@,System-Boolean@-'></a>
### GetGPIStatus() `method`

##### Summary

Check GPI port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetGPIStatus-System-String,System-Boolean@,System-Boolean@-'></a>
### GetGPIStatus() `method`

##### Summary

Check GPI port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetGPIStatus-System-Boolean@,System-Boolean@,System-Boolean@,System-Boolean@-'></a>
### GetGPIStatus() `method`

##### Summary

Check GPI port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetGPIStatus-System-Boolean@,System-Boolean@-'></a>
### GetGPIStatus() `method`

##### Summary

Check GPI port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetGPO0Status-System-String,System-Boolean@-'></a>
### GetGPO0Status() `method`

##### Summary

Check GPO0 port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetGPO0Status-System-Boolean@-'></a>
### GetGPO0Status() `method`

##### Summary

Check GPO0 port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetGPO1Status-System-String,System-Boolean@-'></a>
### GetGPO1Status() `method`

##### Summary

Check GPO1 port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetGPO1Status-System-Boolean@-'></a>
### GetGPO1Status() `method`

##### Summary

Check GPO1 port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetGPO2Status-System-String,System-Boolean@-'></a>
### GetGPO2Status() `method`

##### Summary

Check GPO0 port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetGPO2Status-System-Boolean@-'></a>
### GetGPO2Status() `method`

##### Summary

Check GPO0 port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetGPO3Status-System-String,System-Boolean@-'></a>
### GetGPO3Status() `method`

##### Summary

Check GPO1 port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetGPO3Status-System-Boolean@-'></a>
### GetGPO3Status() `method`

##### Summary

Check GPO1 port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetGPOStatus-System-String,System-Boolean@,System-Boolean@,System-Boolean@,System-Boolean@-'></a>
### GetGPOStatus() `method`

##### Summary

Check GPO port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetGPOStatus-System-String,System-Boolean@,System-Boolean@-'></a>
### GetGPOStatus() `method`

##### Summary

Check GPO port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetGPOStatus-System-Boolean@,System-Boolean@,System-Boolean@,System-Boolean@-'></a>
### GetGPOStatus() `method`

##### Summary

Check GPO port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetGPOStatus-System-Boolean@,System-Boolean@-'></a>
### GetGPOStatus() `method`

##### Summary

Check GPO port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetHardwareVersion'></a>
### GetHardwareVersion() `method`

##### Summary

hardware rev # is actually the r1000 CHIP info

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetImageVersion'></a>
### GetImageVersion() `method`

##### Summary

Get Silicon Lab Application Version

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetImageVersion-CSLibrary-Structures-Version-'></a>
### GetImageVersion(version) `method`

##### Summary

Get Silicon Lab Application Version

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| version | [CSLibrary.Structures.Version](#T-CSLibrary-Structures-Version 'CSLibrary.Structures.Version') | version |

<a name='M-CSLibrary-HighLevelInterface-GetInventoryCount-System-UInt32@-'></a>
### GetInventoryCount(count) `method`

##### Summary

Get the maximum number of inventory cycles to 
attempt on the antenna port during a tag-protocol-
operation cycle before switching to the next enabled 
antenna port.  An inventory cycle consists of one or more 
executions of the singulation algorithm for a particular 
inventory-session target (i.e., A or B).  If the singulation 
algorithm [SING-ALG] is configured to toggle the 
inventory-session, executing the singulation algorithm for 
inventory session A and inventory session B counts as 
two inventory cycles.  A value of zero indicates that there 
is no maximum number of inventory cycles for this 
antenna port.  If this parameter is zero, then dwellTime 
may not be zero. 
See  for the effect of antenna-port dwell time and number 
of inventory cycles on the amount of time spent on an 
antenna port during a single tag-protocol-operation cycle. 
NOTE:  when performing any non-inventory ISO 18000-
6C tag access operation (i.e., read, write, kill, or lock), the 
radio module ignores the number of inventory cycles for 
the antenna port which is used for the tag-protocol 
operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| count | [System.UInt32@](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32@ 'System.UInt32@') |  |

<a name='M-CSLibrary-HighLevelInterface-GetInventoryCount-System-UInt32,System-UInt32@-'></a>
### GetInventoryCount(antennaPort,count) `method`

##### Summary

Get the maximum number of inventory cycles to 
attempt on the antenna port during a tag-protocol-
operation cycle before switching to the next enabled 
antenna port.  An inventory cycle consists of one or more 
executions of the singulation algorithm for a particular 
inventory-session target (i.e., A or B).  If the singulation 
algorithm [SING-ALG] is configured to toggle the 
inventory-session, executing the singulation algorithm for 
inventory session A and inventory session B counts as 
two inventory cycles.  A value of zero indicates that there 
is no maximum number of inventory cycles for this 
antenna port.  If this parameter is zero, then dwellTime 
may not be zero. 
See  for the effect of antenna-port dwell time and number 
of inventory cycles on the amount of time spent on an 
antenna port during a single tag-protocol-operation cycle. 
NOTE:  when performing any non-inventory ISO 18000-
6C tag access operation (i.e., read, write, kill, or lock), the 
radio module ignores the number of inventory cycles for 
the antenna port which is used for the tag-protocol 
operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| antennaPort | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Antenna Port number |
| count | [System.UInt32@](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32@ 'System.UInt32@') |  |

<a name='M-CSLibrary-HighLevelInterface-GetInventoryDuration-System-UInt32@-'></a>
### GetInventoryDuration(duration) `method`

##### Summary

This is used to get inventory duration

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| duration | [System.UInt32@](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32@ 'System.UInt32@') |  |

<a name='M-CSLibrary-HighLevelInterface-GetInventoryDuration-System-UInt32,System-UInt32@-'></a>
### GetInventoryDuration(antennaPort,duration) `method`

##### Summary

This is used to get inventory duration

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| antennaPort | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| duration | [System.UInt32@](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32@ 'System.UInt32@') |  |

<a name='M-CSLibrary-HighLevelInterface-GetMacErrorCode-System-UInt32@-'></a>
### GetMacErrorCode() `method`

##### Summary

Get Mac Error Code

##### Returns

Error Code

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetManufactureDate'></a>
### GetManufactureDate() `method`

##### Summary

Get Manufacture Date

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetMaxForwardPowerLevel-System-UInt32@-'></a>
### GetMaxForwardPowerLevel(MaxPowerLevel) `method`

##### Summary

Get the maximum PA output power level measured in 0.1 dBm units.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| MaxPowerLevel | [System.UInt32@](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32@ 'System.UInt32@') |  |

<a name='M-CSLibrary-HighLevelInterface-GetOperationMode-System-UInt16@,CSLibrary-Constants-AntennaSequenceMode@,System-UInt32@-'></a>
### GetOperationMode(cycles,mode,sequenceSize) `method`

##### Summary

Retrieves the operation mode for the RFID radio module.  The 
operation mode cannot be retrieved while a radio module is 
executing a tag-protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| cycles | [System.UInt16@](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16@ 'System.UInt16@') | The number of antenna cycles to be completed for command execution.

0x0001 = once cycle through

0xFFFF = cycle forever until a CANCEL is received. |
| mode | [CSLibrary.Constants.AntennaSequenceMode@](#T-CSLibrary-Constants-AntennaSequenceMode@ 'CSLibrary.Constants.AntennaSequenceMode@') | Antenna Sequence mode. |
| sequenceSize | [System.UInt32@](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32@ 'System.UInt32@') | Sequence size. Maximum value is 48 |

<a name='M-CSLibrary-HighLevelInterface-GetOperationMode-CSLibrary-Constants-RadioOperationMode@-'></a>
### GetOperationMode(mode) `method`

##### Summary

Retrieves the operation mode for the RFID radio module.  The 
operation mode cannot be retrieved while a radio module is 
executing a tag-protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| mode | [CSLibrary.Constants.RadioOperationMode@](#T-CSLibrary-Constants-RadioOperationMode@ 'CSLibrary.Constants.RadioOperationMode@') | return will receive the current operation mode. |

<a name='M-CSLibrary-HighLevelInterface-GetPCBAssemblyCode'></a>
### GetPCBAssemblyCode() `method`

##### Summary

Get PCBA number

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetPowerLevel-System-UInt32@-'></a>
### GetPowerLevel() `method`

##### Summary

GetPowerLevel

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetPowerLevel-System-UInt32,System-UInt32@-'></a>
### GetPowerLevel() `method`

##### Summary

GetPowerLevel

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetPowerState-CSLibrary-Constants-RadioPowerState@-'></a>
### GetPowerState(state) `method`

##### Summary

Allows the application to retrieve the current power state of the 
radio module.  The radio power state cannot be retrieved while a 
radio module is executing a tag-protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| state | [CSLibrary.Constants.RadioPowerState@](#T-CSLibrary-Constants-RadioPowerState@ 'CSLibrary.Constants.RadioPowerState@') | return will contain the current power state of the radio module. |

<a name='M-CSLibrary-HighLevelInterface-GetRadioResponseDataMode-CSLibrary-Constants-ResponseMode@-'></a>
### GetRadioResponseDataMode() `method`

##### Summary

Allows the application to retrieve the mode of data reporting for 
tag-access operations.  The data-reporting mode may not be 
retrieved while a radio module is executing a tag-protocol 
operation.

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetReadTagIndStatus-System-Byte@-'></a>
### GetReadTagIndStatus(mode) `method`

##### Summary

Get tag read GPO indication status

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| mode | [System.Byte@](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte@ 'System.Byte@') | 0 = OFF, 1 = GPO0, 2 = GPO1 |

<a name='M-CSLibrary-HighLevelInterface-GetReversedPowerLevel-System-Int32@-'></a>
### GetReversedPowerLevel() `method`

##### Summary

Get measurement of the reflected RF power measured in 0.1 dBm units.

##### Returns

Result

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetRfidCompensation-System-Boolean@-'></a>
### GetRfidCompensation() `method`

##### Summary

Get Compensate status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetRfidLibraryVersion'></a>
### GetRfidLibraryVersion() `method`

##### Summary

face out command

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetSelectCriteria-CSLibrary-Structures-SelectCriteria@-'></a>
### GetSelectCriteria(pCrit) `method`

##### Summary

Get Current Criteria Settings

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| pCrit | [CSLibrary.Structures.SelectCriteria@](#T-CSLibrary-Structures-SelectCriteria@ 'CSLibrary.Structures.SelectCriteria@') |  |

<a name='M-CSLibrary-HighLevelInterface-GetSiliconVersion'></a>
### GetSiliconVersion() `method`

##### Summary

Get Silicon Version

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetSingulationAlgorithmParms-CSLibrary-Constants-SingulationAlgorithm,CSLibrary-Structures-SingulationAlgorithmParms-'></a>
### GetSingulationAlgorithmParms(alg,parms) `method`

##### Summary

GetSingulationAlgorithmParms

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| alg | [CSLibrary.Constants.SingulationAlgorithm](#T-CSLibrary-Constants-SingulationAlgorithm 'CSLibrary.Constants.SingulationAlgorithm') |  |
| parms | [CSLibrary.Structures.SingulationAlgorithmParms](#T-CSLibrary-Structures-SingulationAlgorithmParms 'CSLibrary.Structures.SingulationAlgorithmParms') |  |

<a name='M-CSLibrary-HighLevelInterface-GetSoftwareMaxPowerLevel-CSLibrary-Constants-RegionCode-'></a>
### GetSoftwareMaxPowerLevel() `method`

##### Summary

Available Maximum Power you can set on specific region

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-GetTagGroup-CSLibrary-Structures-TagGroup-'></a>
### GetTagGroup(tagGroup) `method`

##### Summary

Get Tag Group

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| tagGroup | [CSLibrary.Structures.TagGroup](#T-CSLibrary-Structures-TagGroup 'CSLibrary.Structures.TagGroup') |  |

<a name='M-CSLibrary-HighLevelInterface-GetTemperatureCompensation-System-UInt32@,System-UInt32@-'></a>
### GetTemperatureCompensation(coeff0,coeff1) `method`

##### Summary

GetTemperatureCompensation

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| coeff0 | [System.UInt32@](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32@ 'System.UInt32@') | Temperature compensation coeff0. temperature_error = (coeff1 * temp) + 
coeff0.

bit 31 – sign bit (0=pos, 1=neg)

bits 30:0 – coeff0, in units of 0.001dB |
| coeff1 | [System.UInt32@](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32@ 'System.UInt32@') | Temperature compensation coeff1. temp_induced_error =
(coeff1 * temperature) + coeff0

bit 31 – sign bit (0=pos, 1=neg)

bits 30:0 – coeff1, in units of 0.001dB/°C |

<a name='M-CSLibrary-HighLevelInterface-GetThresholdTemperature-CSLibrary-Structures-ThresholdTemperatureParms@-'></a>
### GetThresholdTemperature() `method`

##### Summary

GetThresholdTemperature

##### Returns

Result

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-MacBypassReadRegister-System-UInt16,System-UInt16@-'></a>
### MacBypassReadRegister(address,value) `method`

##### Summary

Reads directly from a radio-module hardware register.  The radio 
module's hardware registers may not be read while a radio module 
is executing a tag-protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| address | [System.UInt16](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16 'System.UInt16') | The 16-bit address of the radio-module hardware 
register to be read.  An address that is beyond the end 
of the radio module's register set Results in an invalid-
parameter return status. |
| value | [System.UInt16@](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16@ 'System.UInt16@') | A 16-bit value that will receive the value 
in the radio-module hardware register specified by 
address. |

<a name='M-CSLibrary-HighLevelInterface-MacBypassWriteRegister-System-UInt16,System-UInt16-'></a>
### MacBypassWriteRegister(address,value) `method`

##### Summary

Writes directly to a radio-module hardware register.  The radio 
module's hardware registers may not be written while a radio 
module is executing a tag-protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| address | [System.UInt16](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16 'System.UInt16') | The 16-bit address of the radio-module hardware 
register to be written.  An address that is beyond the 
end of the radio module's register set Results in an 
invalid-parameter return status. |
| value | [System.UInt16](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16 'System.UInt16') | The 16-bit value to write to the radio-module 
hardware register specified by address. |

<a name='M-CSLibrary-HighLevelInterface-MacClearError'></a>
### MacClearError() `method`

##### Summary

Attempts to clear the error state for the radio module's MAC 
 firmware.  The MAC's error state may not be cleared while a radio 
 module is executing a tag-protocol operation.

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-MacErrorIsFatal-System-UInt32-'></a>
### MacErrorIsFatal(macErrCode) `method`

##### Summary

Mac Error Is Fatal Error

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| macErrCode | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Mac Error Code |

<a name='M-CSLibrary-HighLevelInterface-MacErrorIsNegligible-System-UInt32-'></a>
### MacErrorIsNegligible(macErrCode) `method`

##### Summary

Mac Error Is Negligible

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| macErrCode | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Mac Error Code |

<a name='M-CSLibrary-HighLevelInterface-MacErrorIsOverheat-System-UInt32-'></a>
### MacErrorIsOverheat(macErrCode) `method`

##### Summary

Check Mac error code

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| macErrCode | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Mac Error Code |

<a name='M-CSLibrary-HighLevelInterface-MacReadOemData-System-UInt32,System-UInt32[]-'></a>
### MacReadOemData(address,data) `method`

##### Summary

Reads one or more 32-bit words from the MAC's OEM configuration data
area.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| address | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The address of the first 32-bit value to read from the MAC's OEM configuration data area.
Note that the address is a 32-bit word address, and not a byte address |
| data | [System.UInt32[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32[] 'System.UInt32[]') | An array of count 32-bit unsigned integers that will receive the data from MAC's OEM 
configuration data area. The 32-bit values returned are in the MAC's native format (i.e., little endian). 
This parameter must not be NULL. |

<a name='M-CSLibrary-HighLevelInterface-MacWriteOemData-System-UInt32,System-UInt32[]-'></a>
### MacWriteOemData(address,data) `method`

##### Summary

Writes one or more 32-bit words to the MAC's OEM configuration data
area.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| address | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The 32-bit address into the MAC’s OEM configuration data 
area where the first 32-bit data word is to be written. Note that the address is
a 32-bit address, and not a byte address |
| data | [System.UInt32[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32[] 'System.UInt32[]') | An array of count 32-bit unsigned integers that 
contains the data to be written into the MAC’s OEM configuration data area.
The 32-bit values provided must be in the MAC’s native format (i.e., little endian). 
This parameter must not be NULL. |

<a name='M-CSLibrary-HighLevelInterface-R2000RSSINB-System-Byte-'></a>
### R2000RSSINB(cmd) `method`

##### Summary

Execute Host Command

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| cmd | [System.Byte](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte 'System.Byte') |  |

<a name='M-CSLibrary-HighLevelInterface-Reconnect-System-Int32-'></a>
### Reconnect(FailureRetries) `method`

##### Summary

Start reconnect by using previously configured setting until success,
You can call StopReconnect to stop it.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| FailureRetries | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | Reconnect retries |

<a name='M-CSLibrary-HighLevelInterface-SERIAL_Recv-System-Byte[],System-Int32,System-Int32,System-UInt32-'></a>
### SERIAL_Recv(buffer,offset,size,timeout) `method`

##### Summary

Receive data from reader

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| buffer | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| offset | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |
| size | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |
| timeout | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |

<a name='M-CSLibrary-HighLevelInterface-SERIAL_Recv-System-IO-Ports-SerialPort,System-Byte[],System-Int32,System-Int32,System-UInt32-'></a>
### SERIAL_Recv(buffer,offset,size,timeout) `method`

##### Summary

Receive data from reader

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| buffer | [System.IO.Ports.SerialPort](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.IO.Ports.SerialPort 'System.IO.Ports.SerialPort') |  |
| offset | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| size | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |
| timeout | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |

<a name='M-CSLibrary-HighLevelInterface-Set5VPowerOut-System-Boolean-'></a>
### Set5VPowerOut(onoff) `method`

##### Summary

Set GPIO 5V Power ON/OFF

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| onoff | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') | true = on, false = off |

<a name='M-CSLibrary-HighLevelInterface-SetAgileChannels-CSLibrary-Constants-RegionCode-'></a>
### SetAgileChannels(prof) `method`

##### Summary

Set to frequency agile mode

##### Returns

Result

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| prof | [CSLibrary.Constants.RegionCode](#T-CSLibrary-Constants-RegionCode 'CSLibrary.Constants.RegionCode') | Country Profile |

<a name='M-CSLibrary-HighLevelInterface-SetAntennaPortConfiguration-CSLibrary-Structures-AntennaPortConfig-'></a>
### SetAntennaPortConfiguration(antenna) `method`

##### Summary

Allows an application to configure several parameters for a single 
logical antenna port e.g.,  dwell time, power level, and number 
of inventory cycles.  Even if the logical antenna port is disabled, 
an application is allowed to set these configuration parameters.  
Setting configuration parameters does not cause a logical antenna 
port to be automatically enabled; the application must still enable 
the logical antenna port via RFID_AntennaPortSetState.  The 
antenna-port configuration cannot be set while a radio module is 
executing a tag-protocol operation. 
NOTE:  Since RFID_AntennaPortSetConfiguration sets all of the 
configuration parameters that are present in the 
RFID_ANTENNA_PORT_CONFIG structure, if an application wishes to 
leave some parameters unchanged, the application should first call 
RFID_AntennaPortGetConfiguration to retrieve the current 
settings, update the values in the structure that are to be 
changed, and then call RFID_AntennaPortSetConfiguration.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| antenna | [CSLibrary.Structures.AntennaPortConfig](#T-CSLibrary-Structures-AntennaPortConfig 'CSLibrary.Structures.AntennaPortConfig') | A structure that contains the 
antenna-port configuration parameters.  This 
parameter must not be NULL.  In version 1.1, 
the physicalRxPort and physicalTxPort 
fields must be the same. |

<a name='M-CSLibrary-HighLevelInterface-SetAntennaPortConfiguration-System-UInt32,CSLibrary-Structures-AntennaPortConfig-'></a>
### SetAntennaPortConfiguration(port,antenna) `method`

##### Summary

Allows an application to configure several parameters for a single 
logical antenna port e.g.,  dwell time, power level, and number 
of inventory cycles.  Even if the logical antenna port is disabled, 
an application is allowed to set these configuration parameters.  
Setting configuration parameters does not cause a logical antenna 
port to be automatically enabled; the application must still enable 
the logical antenna port via RFID_AntennaPortSetState.  The 
antenna-port configuration cannot be set while a radio module is 
executing a tag-protocol operation. 
NOTE:  Since RFID_AntennaPortSetConfiguration sets all of the 
configuration parameters that are present in the 
RFID_ANTENNA_PORT_CONFIG structure, if an application wishes to 
leave some parameters unchanged, the application should first call 
RFID_AntennaPortGetConfiguration to retrieve the current 
settings, update the values in the structure that are to be 
changed, and then call RFID_AntennaPortSetConfiguration.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| port | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | antenna-port |
| antenna | [CSLibrary.Structures.AntennaPortConfig](#T-CSLibrary-Structures-AntennaPortConfig 'CSLibrary.Structures.AntennaPortConfig') | A structure that contains the 
antenna-port configuration parameters.  This 
parameter must not be NULL.  In version 1.1, 
the physicalRxPort and physicalTxPort 
fields must be the same. |

<a name='M-CSLibrary-HighLevelInterface-SetAntennaPortState-CSLibrary-Constants-AntennaPortState-'></a>
### SetAntennaPortState(portState) `method`

##### Summary

Allows an application to specify whether or not a radio module's 
logical antenna port is enabled for subsequent tag operations.  The 
antenna-port state cannot be set while a radio module is executing 
a tag-protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| portState | [CSLibrary.Constants.AntennaPortState](#T-CSLibrary-Constants-AntennaPortState 'CSLibrary.Constants.AntennaPortState') | The new state of the logical antenna port. |

<a name='M-CSLibrary-HighLevelInterface-SetAntennaPortState-System-UInt32,CSLibrary-Constants-AntennaPortState-'></a>
### SetAntennaPortState(port,portState) `method`

##### Summary

Allows an application to specify whether or not a radio module's 
logical antenna port is enabled for subsequent tag operations.  The 
antenna-port state cannot be set while a radio module is executing 
a tag-protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| port | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | antenna port |
| portState | [CSLibrary.Constants.AntennaPortState](#T-CSLibrary-Constants-AntennaPortState 'CSLibrary.Constants.AntennaPortState') | The new state of the logical antenna port. |

<a name='M-CSLibrary-HighLevelInterface-SetAntennaPortStatus-CSLibrary-Structures-AntennaPortStatus-'></a>
### SetAntennaPortStatus(portStatus) `method`

##### Summary

Retrieves the status of the requested logical antenna port for a 
particular radio module.  The antenna-port status cannot be 
retrieved while a radio module is executing a tag-protocol 
operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| portStatus | [CSLibrary.Structures.AntennaPortStatus](#T-CSLibrary-Structures-AntennaPortStatus 'CSLibrary.Structures.AntennaPortStatus') |  |

<a name='M-CSLibrary-HighLevelInterface-SetAntennaPortStatus-System-UInt32,CSLibrary-Structures-AntennaPortStatus-'></a>
### SetAntennaPortStatus(port,portStatus) `method`

##### Summary

Retrieves the status of the requested logical antenna port for a 
particular radio module.  The antenna-port status cannot be 
retrieved while a radio module is executing a tag-protocol 
operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| port | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | antenna port |
| portStatus | [CSLibrary.Structures.AntennaPortStatus](#T-CSLibrary-Structures-AntennaPortStatus 'CSLibrary.Structures.AntennaPortStatus') |  |

<a name='M-CSLibrary-HighLevelInterface-SetAntennaSequence-System-Int32-'></a>
### SetAntennaSequence(sequenceSize) `method`

##### Summary

Set Antenna Sequence Size

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| sequenceSize | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | Size of the antenna sequence. This value must not greater than 48. |

<a name='M-CSLibrary-HighLevelInterface-SetAntennaSequence-System-Byte[]-'></a>
### SetAntennaSequence(sequence) `method`

##### Summary

SetAntennaSequence

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| sequence | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | Antenna number list, value must be within 0-15 |

<a name='M-CSLibrary-HighLevelInterface-SetAntennaSequence-System-Byte[],System-UInt32,CSLibrary-Constants-AntennaSequenceMode-'></a>
### SetAntennaSequence(sequence,sequenceSize,sequenceMode) `method`

##### Summary

SetAntennaSequenceonnect

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| sequence | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | Antenna Sequence |
| sequenceSize | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Antenna Sequence Size, it must be within 1-48 |
| sequenceMode | [CSLibrary.Constants.AntennaSequenceMode](#T-CSLibrary-Constants-AntennaSequenceMode 'CSLibrary.Constants.AntennaSequenceMode') | Antenna Sequence Mode |

<a name='M-CSLibrary-HighLevelInterface-SetAntennaSequence-CSLibrary-Constants-AntennaSequenceMode,System-Int32,CSLibrary-Structures-AntennaPortCollections-'></a>
### SetAntennaSequence(sequenceMode,sequenceSize,sequence) `method`

##### Summary

SetAntennaSequence

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| sequenceMode | [CSLibrary.Constants.AntennaSequenceMode](#T-CSLibrary-Constants-AntennaSequenceMode 'CSLibrary.Constants.AntennaSequenceMode') | Sequence mode. |
| sequenceSize | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | Size of the antenna sequence. This value must not greater than 48. |
| sequence | [CSLibrary.Structures.AntennaPortCollections](#T-CSLibrary-Structures-AntennaPortCollections 'CSLibrary.Structures.AntennaPortCollections') | Antenna number list, value must be within 0-15 and only 48 sequences can be used. |

<a name='M-CSLibrary-HighLevelInterface-SetCurrentLinkProfile-System-UInt32-'></a>
### SetCurrentLinkProfile(profile) `method`

##### Summary

Allows the application to set the current link profile for the radio 
module.  A link profile will remain in effect until changed by a 
subsequent call to RFID_RadioSetCurrentLinkProfile.  The 
current link profile cannot be set while a radio module is executing 
a tag-protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| profile | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The link profile to make the current link profile.  If this 
parameter does not represent a valid link profile, 
RFID_ERROR_INVALID_PARAMETER is returned. |

<a name='M-CSLibrary-HighLevelInterface-SetCurrentLinkProfile-System-UInt32,System-Boolean-'></a>
### SetCurrentLinkProfile(profile,extenLO) `method`

##### Summary

Allows the application to set the current link profile for the radio 
module.  A link profile will remain in effect until changed by a 
subsequent call to RFID_RadioSetCurrentLinkProfile.  The 
current link profile cannot be set while a radio module is executing 
a tag-protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| profile | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The link profile to make the current link profile.  If this 
parameter does not represent a valid link profile, 
RFID_ERROR_INVALID_PARAMETER is returned. |
| extenLO | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') | config enable and disable external LO |

<a name='M-CSLibrary-HighLevelInterface-SetCurrentSingulationAlgorithm-CSLibrary-Constants-SingulationAlgorithm-'></a>
### SetCurrentSingulationAlgorithm(SingulationAlgorithm) `method`

##### Summary

Allows the application to set the currently-active singulation 
algorithm (i.e., the one that is used when performing a tag-
protocol operation (e.g., inventory, tag read, etc.)).  The 
currently-active singulation algorithm may not be changed while a 
radio module is executing a tag-protocol operation.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| SingulationAlgorithm | [CSLibrary.Constants.SingulationAlgorithm](#T-CSLibrary-Constants-SingulationAlgorithm 'CSLibrary.Constants.SingulationAlgorithm') | The singulation algorithm that is to be used for 
subsequent tag-access operations.  If this 
parameter does not represent a valid 
singulation algorithm, 
RFID_ERROR_INVALID_PARAMETER is returned. |

<a name='M-CSLibrary-HighLevelInterface-SetDefaultAntennaList'></a>
### SetDefaultAntennaList() `method`

##### Summary

Set Antenna List to factory default value.

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-SetDynamicQParms-System-UInt32,System-UInt32,System-UInt32,System-UInt32,System-UInt32,System-UInt32-'></a>
### SetDynamicQParms(StartQValue,MinQValue,MaxQValue,RetryCount,ThresholdMultiplier,ToggleTarget) `method`

##### Summary

The parameters for the dynamic-Q algorithm with application-controlled Q-adjustment-threshold, MAC singulation algorithm 3

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| StartQValue | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The starting Q value to use.  Valid values are 0-15, inclusive.  
startQValue must be greater than or equal to minQValue and 
less than or equal to maxQValue. |
| MinQValue | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The minimum Q value to use.  Valid values are 0-15, inclusive.  
minQValue must be less than or equal to startQValue and 
maxQValue. |
| MaxQValue | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The maximum Q value to use.  Valid values are 0-15, inclusive.  
maxQValue must be greater than or equal to startQValue and 
minQValue. |
| RetryCount | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Specifies the number of times to try another execution of 
the singulation algorithm for the specified session/target 
before either toggling the target (if toggleTarget is non-
zero) or terminating the inventory/tag access operation.  
Valid values are 0-255, inclusive. |
| ThresholdMultiplier | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The multiplier, specified in units of fourths (i.e., 0.25), that will be 
applied to the Q-adjustment threshold as part of the dynamic-Q 
algorithm.  For example, a value of 7 represents a multiplier of 
1.75.  See [MAC-EDS] for specifics on how the Q-adjustment 
threshold is used in the dynamic Q algorithm.  Valid values are 0-
255, inclusive. |
| ToggleTarget | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | A flag that indicates if, after performing the inventory cycle for the 
specified target (i.e., A or B), if the target should be toggled (i.e., 
A to B or B to A) and another inventory cycle run.  A non-zero 
value indicates that the target should be toggled.  A zero value 
indicates that the target should not be toggled.  Note that if the 
target is toggled, retryCount and maxQueryRepCount will 
also apply to the new target. |

<a name='M-CSLibrary-HighLevelInterface-SetDynamicQParms-CSLibrary-Structures-DynamicQParms-'></a>
### SetDynamicQParms() `method`

##### Summary

The parameters for the dynamic-Q algorithm with application-controlled Q-adjustment-threshold, MAC singulation algorithm 3

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-SetDynamicQParms'></a>
### SetDynamicQParms() `method`

##### Summary

The parameters for the dynamic-Q algorithm with application-controlled Q-adjustment-threshold, MAC singulation algorithm 3

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-SetFixedChannel-CSLibrary-Constants-RegionCode,System-UInt32,CSLibrary-Constants-LBT-'></a>
### SetFixedChannel(prof,channel,LBTcfg) `method`

##### Summary

Set 1 Frequency Channel
All region can be used to set a fixed channel

##### Returns

Result

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| prof | [CSLibrary.Constants.RegionCode](#T-CSLibrary-Constants-RegionCode 'CSLibrary.Constants.RegionCode') | Region Code |
| channel | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Channel number start from zero, you can get the available channels 
from CSLibrary.HighLevelInterface.AvailableFrequencyTable(CSLibrary.Constants.RegionCode) |
| LBTcfg | [CSLibrary.Constants.LBT](#T-CSLibrary-Constants-LBT 'CSLibrary.Constants.LBT') | This is only used when JPN is set |

<a name='M-CSLibrary-HighLevelInterface-SetFixedChannel-System-UInt32,CSLibrary-Constants-LBT-'></a>
### SetFixedChannel(channel,LBTcfg) `method`

##### Summary

Set Fixed Frequency Channel on current region

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| channel | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | frequency channel number |
| LBTcfg | [CSLibrary.Constants.LBT](#T-CSLibrary-Constants-LBT 'CSLibrary.Constants.LBT') | LBT options |

<a name='M-CSLibrary-HighLevelInterface-SetFixedChannel-System-UInt32-'></a>
### SetFixedChannel(channel) `method`

##### Summary

Set Fixed Frequency Channel on current region

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| channel | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | frequency channel number |

<a name='M-CSLibrary-HighLevelInterface-SetFixedChannel'></a>
### SetFixedChannel() `method`

##### Summary

Reset Fixed Frequency Channel on current region

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-SetFixedQParms-System-UInt32,System-UInt32,System-UInt32,System-UInt32-'></a>
### SetFixedQParms(QValue,RetryCount,ToggleTarget,RepeatUnitNoTags) `method`

##### Summary

The  parameters  for  the  fixed-Q  algorithm,  MAC  singulation  algorithm  0
If running a same operation, it only need to config once times

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| QValue | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The Q value to use.  Valid values are 0-15, inclusive. |
| RetryCount | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Specifies the number of times to try another execution 
of the singulation algorithm for the specified 
session/target before either toggling the target (if 
toggleTarget is non-zero) or terminating the 
inventory/tag access operation.  Valid values are 0-
255, inclusive. Valid values are 0-255, inclusive. |
| ToggleTarget | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | A non-zero value indicates that the target should
be toggled.A zero value indicates that the target should not be toggled.
Note that if the target is toggled, retryCount and repeatUntilNoTags will also apply
to the new target. |
| RepeatUnitNoTags | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | A flag that indicates whether or not the singulation 
algorithm should continue performing inventory rounds 
until no tags are singulated.  A non-zero value indicates 
that, for each execution of the singulation algorithm, 
inventory rounds should be performed until no tags are 
singulated.  A zero value indicates that a single 
inventory round should be performed for each 
execution of the singulation algorithm. |

<a name='M-CSLibrary-HighLevelInterface-SetFixedQParms-CSLibrary-Structures-FixedQParms-'></a>
### SetFixedQParms() `method`

##### Summary

The  parameters  for  the  fixed-Q  algorithm,  MAC  singulation  algorithm  0
If running a same operation, it only need to config once times

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-SetFixedQParms'></a>
### SetFixedQParms() `method`

##### Summary

The  parameters  for  the  fixed-Q  algorithm,  MAC  singulation  algorithm  0
If running a same operation, it only need to config once times

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-SetFrequencyBand-System-UInt32,CSLibrary-Constants-BandState,System-UInt32,System-UInt32-'></a>
### SetFrequencyBand(m_radioIndex,frequencySelector,config,multdiv,pllcc) `method`

##### Summary

Set Frequency Band - Basic Function

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| m_radioIndex | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| frequencySelector | [CSLibrary.Constants.BandState](#T-CSLibrary-Constants-BandState 'CSLibrary.Constants.BandState') |  |
| config | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| multdiv | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |

<a name='M-CSLibrary-HighLevelInterface-SetFrequencyCompensation-System-UInt32,System-UInt32-'></a>
### SetFrequencyCompensation(coeff0,coeff1) `method`

##### Summary

SetFrequencyCompensation

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| coeff0 | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Frequency compensation coeff0. freq_induced_error = (coeff1 * freq) + 
coeff0.

bit 31 – sign bit (0=pos, 1=neg)

bits 30:0 – coeff0, in units of 0.001dB |
| coeff1 | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Frequency compensation coeff1. freq_induced_error =
(coeff1 * freq) + coeff0

bit 31 – sign bit (0=pos, 1=neg)

bits 30:0 – coeff1, in units of 0.000001dB/MHz |

<a name='M-CSLibrary-HighLevelInterface-SetGPI0Interrupt-System-String,CSLibrary-Constants-GPIOTrigger-'></a>
### SetGPI0Interrupt() `method`

##### Summary

Set GPI0 trigger status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-SetGPI0Interrupt-CSLibrary-Constants-GPIOTrigger-'></a>
### SetGPI0Interrupt() `method`

##### Summary

Set GPI0 trigger status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-SetGPI1Interrupt-System-String,CSLibrary-Constants-GPIOTrigger-'></a>
### SetGPI1Interrupt() `method`

##### Summary

Set GPI1 trigger status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-SetGPI1Interrupt-CSLibrary-Constants-GPIOTrigger-'></a>
### SetGPI1Interrupt() `method`

##### Summary

Set GPI1 trigger status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-SetGPO0Status-System-Boolean-'></a>
### SetGPO0Status() `method`

##### Summary

Set GPO0 port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-SetGPO0Status-System-String,System-Boolean-'></a>
### SetGPO0Status() `method`

##### Summary

Set GPO0 port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-SetGPO1Status-System-Boolean-'></a>
### SetGPO1Status() `method`

##### Summary

Set GPO1 port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-SetGPO1Status-System-String,System-Boolean-'></a>
### SetGPO1Status() `method`

##### Summary

Set GPO1 port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-SetGPO2Status-System-Boolean-'></a>
### SetGPO2Status() `method`

##### Summary

Set GPO0 port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-SetGPO2Status-System-String,System-Boolean-'></a>
### SetGPO2Status() `method`

##### Summary

Set GPO0 port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-SetGPO3Status-System-Boolean-'></a>
### SetGPO3Status() `method`

##### Summary

Set GPO1 port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-SetGPO3Status-System-String,System-Boolean-'></a>
### SetGPO3Status() `method`

##### Summary

Set GPO1 port status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-SetHoppingChannels-CSLibrary-Constants-RegionCode-'></a>
### SetHoppingChannels(prof) `method`

##### Summary

Set to the specific frequency profile

##### Returns

Result

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| prof | [CSLibrary.Constants.RegionCode](#T-CSLibrary-Constants-RegionCode 'CSLibrary.Constants.RegionCode') | Country Profile |

<a name='M-CSLibrary-HighLevelInterface-SetHoppingChannels'></a>
### SetHoppingChannels() `method`

##### Summary

Reset current frequency profile

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-SetInterface-CSLibrary-HighLevelInterface-INTERFACETYPE-'></a>
### SetInterface(Mode) `method`

##### Summary

Set connection intergface

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| Mode | [CSLibrary.HighLevelInterface.INTERFACETYPE](#T-CSLibrary-HighLevelInterface-INTERFACETYPE 'CSLibrary.HighLevelInterface.INTERFACETYPE') |  |

<a name='M-CSLibrary-HighLevelInterface-SetInventoryCycle-System-UInt32-'></a>
### SetInventoryCycle(cycle) `method`

##### Summary

Specifies the maximum number of inventory cycles to 
attempt on the antenna port during a tag-protocol-
operation cycle before switching to the next enabled 
antenna port.  An inventory cycle consists of one or more 
executions of the singulation algorithm for a particular 
inventory-session target (i.e., A or B).  If the singulation 
algorithm [SING-ALG] is configured to toggle the 
inventory-session, executing the singulation algorithm for 
inventory session A and inventory session B counts as 
two inventory cycles.  A value of zero indicates that there 
is no maximum number of inventory cycles for this 
antenna port.  If this parameter is zero, then dwellTime 
may not be zero. 
See  for the effect of antenna-port dwell time and number 
of inventory cycles on the amount of time spent on an 
antenna port during a single tag-protocol-operation cycle. 
NOTE:  when performing any non-inventory ISO 18000-
6C tag access operation (i.e., read, write, kill, or lock), the 
radio module ignores the number of inventory cycles for 
the antenna port which is used for the tag-protocol 
operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| cycle | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Inventory Cycle count, if this is zero, InventoryDuration can't set to zero. |

<a name='M-CSLibrary-HighLevelInterface-SetInventoryCycle-System-UInt32,System-UInt32-'></a>
### SetInventoryCycle(antennaPort,cycle) `method`

##### Summary

Specifies the maximum number of inventory cycles to 
attempt on the antenna port during a tag-protocol-
operation cycle before switching to the next enabled 
antenna port.  An inventory cycle consists of one or more 
executions of the singulation algorithm for a particular 
inventory-session target (i.e., A or B).  If the singulation 
algorithm [SING-ALG] is configured to toggle the 
inventory-session, executing the singulation algorithm for 
inventory session A and inventory session B counts as 
two inventory cycles.  A value of zero indicates that there 
is no maximum number of inventory cycles for this 
antenna port.  If this parameter is zero, then dwellTime 
may not be zero. 
See  for the effect of antenna-port dwell time and number 
of inventory cycles on the amount of time spent on an 
antenna port during a single tag-protocol-operation cycle. 
NOTE:  when performing any non-inventory ISO 18000-
6C tag access operation (i.e., read, write, kill, or lock), the 
radio module ignores the number of inventory cycles for 
the antenna port which is used for the tag-protocol 
operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| antennaPort | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Antenna Port number |
| cycle | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Inventory Cycle count, if this is zero, InventoryDuration can't set to zero. |

<a name='M-CSLibrary-HighLevelInterface-SetInventoryDuration-System-UInt32-'></a>
### SetInventoryDuration(duration) `method`

##### Summary

This is used to set inventory duration

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| duration | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |

<a name='M-CSLibrary-HighLevelInterface-SetInventoryDuration-System-UInt32,System-UInt32-'></a>
### SetInventoryDuration(antennaPort,duration) `method`

##### Summary

This is used to set inventory duration

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| antennaPort | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Antenna Port number |
| duration | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |

<a name='M-CSLibrary-HighLevelInterface-SetLNA-System-Int32,System-Int32,System-Int32,System-Int32-'></a>
### SetLNA(rflna_high_comp_norm,rflna_gain_norm,iflna_gain_norm,ifagc_gain_norm,ifagc_gain_norm) `method`

##### Summary

RF LNA compression mode = 0, 1
RF LNA Gain = 1, 7, 13
IF LNA Gain = 6, 12, 18, 24
AGC Gain = -12, -6, 0, 6

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| rflna_high_comp_norm | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |
| rflna_gain_norm | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |
| iflna_gain_norm | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |
| ifagc_gain_norm | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |

<a name='M-CSLibrary-HighLevelInterface-SetMaxForwardPowerLevel-System-UInt32-'></a>
### SetMaxForwardPowerLevel(MaxPowerLevel) `method`

##### Summary

Set the maximum PA output power level measured in 0.1 dBm units.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| MaxPowerLevel | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |

<a name='M-CSLibrary-HighLevelInterface-SetOperationMode-System-UInt16,CSLibrary-Constants-AntennaSequenceMode,System-UInt32-'></a>
### SetOperationMode(cycles,mode,sequenceSize) `method`

##### Summary

Sets the operation mode of RFID radio module.  By default, when 
an application opens a radio, the RFID Reader Library sets the 
reporting mode to non-continuous.  An RFID radio module's 
operation mode will remain in effect until it is explicitly changed 
via RFID_RadioSetOperationMode, or the radio is closed and re-
opened (at which point it will be set to non-continuous mode).  
The operation mode may not be changed while a radio module is 
executing a tag-protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| cycles | [System.UInt16](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16 'System.UInt16') | The number of antenna cycles to be completed for command execution.

0x0001 = once cycle through

0xFFFF = cycle forever until a CANCEL is received. |
| mode | [CSLibrary.Constants.AntennaSequenceMode](#T-CSLibrary-Constants-AntennaSequenceMode 'CSLibrary.Constants.AntennaSequenceMode') | Antenna Sequence mode. |
| sequenceSize | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Sequence size. Maximum value is 48 |

<a name='M-CSLibrary-HighLevelInterface-SetOperationMode-CSLibrary-Constants-RadioOperationMode-'></a>
### SetOperationMode(mode) `method`

##### Summary

Sets the operation mode of RFID radio module.  By default, when 
an application opens a radio, the RFID Reader Library sets the 
reporting mode to non-continuous.  An RFID radio module's 
operation mode will remain in effect until it is explicitly changed 
via RFID_RadioSetOperationMode, or the radio is closed and re-
opened (at which point it will be set to non-continuous mode).  
The operation mode may not be changed while a radio module is 
executing a tag-protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| mode | [CSLibrary.Constants.RadioOperationMode](#T-CSLibrary-Constants-RadioOperationMode 'CSLibrary.Constants.RadioOperationMode') | The operation mode for the radio module. |

<a name='M-CSLibrary-HighLevelInterface-SetOperationMode-CSLibrary-Constants-RadioOperationMode,CSLibrary-Constants-AntennaSequenceMode,System-Int32-'></a>
### SetOperationMode(operationMode,sequenceMode,sequenceSize) `method`

##### Summary

Sets the radio's operation mode.  An RFID radio module operation mode
will remain in effect until it is explicitly changed via RadioSetOperationMode

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| operationMode | [CSLibrary.Constants.RadioOperationMode](#T-CSLibrary-Constants-RadioOperationMode 'CSLibrary.Constants.RadioOperationMode') | The operation mode for the radio module. |
| sequenceMode | [CSLibrary.Constants.AntennaSequenceMode](#T-CSLibrary-Constants-AntennaSequenceMode 'CSLibrary.Constants.AntennaSequenceMode') | The antenna sequence mode for the radio module. |
| sequenceSize | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | The antenna sequence size for the radio module. This must be between 0 to 48. |

<a name='M-CSLibrary-HighLevelInterface-SetPostMatchCriteria-CSLibrary-Structures-SingulationCriterion[]-'></a>
### SetPostMatchCriteria(postmatch) `method`

##### Summary

Configures the post-singulation match criteria to be used by the 
RFID radio module.  The supplied post-singulation match criteria 
will be used for any tag-protocol operations (i.e., 
Inventory, etc.) in which the application specifies 
that a post-singulation match should be performed on the tags 
that are singulated by the tag-protocol operation (i.e., the 
SelectFlags.POST_MATCH flag is provided to the 
appropriate RFID_18K6CTag* function).  The post-singulation 
match criteria will stay in effect until the next call to 
SetPostMatchCriteria.  Post-singulation match 
criteria may not be changed while a radio module is executing a 
tag-protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| postmatch | [CSLibrary.Structures.SingulationCriterion[]](#T-CSLibrary-Structures-SingulationCriterion[] 'CSLibrary.Structures.SingulationCriterion[]') | An array that specifies the post-
singulation match criteria that are to be 
applied to the tag's Electronic Product Code 
after it is singulated to determine if it is to 
have the tag-protocol operation applied to it.  
If the countCriteria field is zero, all post-
singulation criteria will be disabled.  This 
parameter must not be NULL. |

<a name='M-CSLibrary-HighLevelInterface-SetPowerLevel-System-UInt32-'></a>
### SetPowerLevel(pwrlevel) `method`

##### Summary

Set Power Level(Max 300)...

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| pwrlevel | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Power Level Max. 300 |

<a name='M-CSLibrary-HighLevelInterface-SetPowerLevel-System-UInt32,System-UInt32-'></a>
### SetPowerLevel(antennaPort,pwrlevel) `method`

##### Summary

Set Power Level...

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| antennaPort | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Antenna Port number |
| pwrlevel | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Power Level |

<a name='M-CSLibrary-HighLevelInterface-SetPowerState-CSLibrary-Constants-RadioPowerState-'></a>
### SetPowerState(powerState) `method`

##### Summary

Allows the application to set the power state of the radio module.  
The radio power state cannot be set while a radio module is 
executing a tag-protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| powerState | [CSLibrary.Constants.RadioPowerState](#T-CSLibrary-Constants-RadioPowerState 'CSLibrary.Constants.RadioPowerState') | The new power state for the RFID radio module. |

<a name='M-CSLibrary-HighLevelInterface-SetRadioResponseDataMode-CSLibrary-Constants-ResponseMode-'></a>
### SetRadioResponseDataMode(mode) `method`

##### Summary

Allows the application to control the mode of data reporting for 
tag-access operations.  By default, when an application opens a 
radio, the RFID Reader Library sets the reporting mode to 
"Compact".  The data-reporting mode will remain in effect until a 
subsequent call to RFID_RadioSetResponseDataMode, or the radio 
is closed and re-opened (at which point the data mode is set to 
normal).  The data-reporting mode may not be changed while a 
radio module is executing a tag-protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| mode | [CSLibrary.Constants.ResponseMode](#T-CSLibrary-Constants-ResponseMode 'CSLibrary.Constants.ResponseMode') | The requested data-reporting mode for 
the data type specified by |

<a name='M-CSLibrary-HighLevelInterface-SetReadTagInd-System-Byte-'></a>
### SetReadTagInd(mode) `method`

##### Summary

Set tag read GPO indication

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| mode | [System.Byte](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte 'System.Byte') | 0 = OFF, 1 = GPO0, 2 = GPO1 |

<a name='M-CSLibrary-HighLevelInterface-SetRfidCompensation-System-Boolean-'></a>
### SetRfidCompensation() `method`

##### Summary

Turn on/off compensate for temperature and frequency

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-SetSelectCriteria-CSLibrary-Structures-SelectCriterion[]-'></a>
### SetSelectCriteria(critlist) `method`

##### Summary

Configures the tag-selection criteria for the ISO 18000-6C select 
 command.  The supplied tag-selection criteria will be used for any 
 tag-protocol operations (i.e., Inventory, etc.) in 
 which the application specifies that an ISO 18000-6C select 
 command should be issued prior to executing the tag-protocol 
 operation (i.e., the SelectFlags.SELECT flag is provided to 
 the appropriate RFID_18K6CTag* function).  The tag-selection 
 criteria will stay in effect until the next call to 
 SetSelectCriteria.  Tag-selection criteria may not 
 be changed while a radio module is executing a tag-protocol 
 operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| critlist | [CSLibrary.Structures.SelectCriterion[]](#T-CSLibrary-Structures-SelectCriterion[] 'CSLibrary.Structures.SelectCriterion[]') | SelectCriteria array, containing countCriteria entries, of selection 
 criterion structures that are to be applied sequentially, beginning with 
 pCriteria[0], to the tag population.  If this field is NULL, 
 countCriteria must be zero. |

<a name='M-CSLibrary-HighLevelInterface-SetSingulationAlgorithmParms-CSLibrary-Constants-SingulationAlgorithm,CSLibrary-Structures-SingulationAlgorithmParms-'></a>
### SetSingulationAlgorithmParms(alg,parms) `method`

##### Summary

SetSingulationAlgorithmParms

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| alg | [CSLibrary.Constants.SingulationAlgorithm](#T-CSLibrary-Constants-SingulationAlgorithm 'CSLibrary.Constants.SingulationAlgorithm') |  |
| parms | [CSLibrary.Structures.SingulationAlgorithmParms](#T-CSLibrary-Structures-SingulationAlgorithmParms 'CSLibrary.Structures.SingulationAlgorithmParms') |  |

<a name='M-CSLibrary-HighLevelInterface-SetTagGroup-CSLibrary-Constants-Selected-'></a>
### SetTagGroup(gpSelect) `method`

##### Summary

Get Tag Group

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| gpSelect | [CSLibrary.Constants.Selected](#T-CSLibrary-Constants-Selected 'CSLibrary.Constants.Selected') |  |

<a name='M-CSLibrary-HighLevelInterface-SetTagGroup-CSLibrary-Constants-Selected,CSLibrary-Constants-Session,CSLibrary-Constants-SessionTarget-'></a>
### SetTagGroup(gpSelect,gpSession,gpSessionTarget) `method`

##### Summary

Once the tag population has been partitioned into disjoint groups, a subsequent 
tag-protocol operation (i.e., an inventory operation or access command) is then 
applied to one of the tag groups.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| gpSelect | [CSLibrary.Constants.Selected](#T-CSLibrary-Constants-Selected 'CSLibrary.Constants.Selected') | Specifies the state of the selected (SL) flag for tags that will have 
the operation applied to them. |
| gpSession | [CSLibrary.Constants.Session](#T-CSLibrary-Constants-Session 'CSLibrary.Constants.Session') | Specifies which inventory session flag (i.e., S0, S1, S2, or S3) 
will be matched against the inventory state specified by target. |
| gpSessionTarget | [CSLibrary.Constants.SessionTarget](#T-CSLibrary-Constants-SessionTarget 'CSLibrary.Constants.SessionTarget') | Specifies the state of the inventory session flag (i.e., A or B),
specified by session, for tags that will have the operation 
applied to them. |

<a name='M-CSLibrary-HighLevelInterface-SetTagGroup-CSLibrary-Structures-TagGroup-'></a>
### SetTagGroup(tagGroup) `method`

##### Summary

Once the tag population has been partitioned into disjoint groups, a subsequent 
tag-protocol operation (i.e., an inventory operation or access command) is then 
applied to one of the tag groups.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| tagGroup | [CSLibrary.Structures.TagGroup](#T-CSLibrary-Structures-TagGroup 'CSLibrary.Structures.TagGroup') | [TagGroup](#T-CSLibrary-Structures-TagGroup 'CSLibrary.Structures.TagGroup') |

<a name='M-CSLibrary-HighLevelInterface-SetTemperatureCompensation-System-UInt32,System-UInt32-'></a>
### SetTemperatureCompensation(coeff0,coeff1) `method`

##### Summary

SetTemperatureCompensation

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| coeff0 | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Temperature compensation coeff0. temperature_error = (coeff1 * temp) + 
coeff0.

bit 31 – sign bit (0=pos, 1=neg)

bits 30:0 – coeff0, in units of 0.001dB |
| coeff1 | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Temperature compensation coeff1. temp_induced_error =
(coeff1 * temperature) + coeff0

bit 31 – sign bit (0=pos, 1=neg)

bits 30:0 – coeff1, in units of 0.001dB/°C |

<a name='M-CSLibrary-HighLevelInterface-SetThresholdTemperature-System-UInt32,System-UInt32,System-UInt32,System-UInt32-'></a>
### SetThresholdTemperature(ambient,xcver,patemp,padeta) `method`

##### Summary

No Use, use system default value instead
SetThresholdTemperature

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| ambient | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| xcver | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| patemp | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| padeta | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |

<a name='M-CSLibrary-HighLevelInterface-Setup18K6CBlockWriteRegisters-CSLibrary-Constants-MemoryBank,System-UInt32,System-UInt32,System-UInt16[],System-UInt32-'></a>
### Setup18K6CBlockWriteRegisters(WriteBank,WriteOffset,WriteSize,WriteBuf,BufOffset) `method`

##### Summary

WriteSize = word count max 256

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| WriteBank | [CSLibrary.Constants.MemoryBank](#T-CSLibrary-Constants-MemoryBank 'CSLibrary.Constants.MemoryBank') |  |
| WriteOffset | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| WriteSize | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| WriteBuf | [System.UInt16[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16[] 'System.UInt16[]') |  |
| BufOffset | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |

<a name='M-CSLibrary-HighLevelInterface-StartOperation-CSLibrary-Constants-Operation,System-Boolean-'></a>
### StartOperation(opertion,bWait) `method`

##### Summary

Start operation

##### Returns

[Result](#T-CSLibrary-Constants-Result 'CSLibrary.Constants.Result')

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| opertion | [CSLibrary.Constants.Operation](#T-CSLibrary-Constants-Operation 'CSLibrary.Constants.Operation') | operation type |
| bWait | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') | blocking and waiting until user cancel or operation done |

<a name='M-CSLibrary-HighLevelInterface-StartPollGPIStatus-CSLibrary-Structures-GPI_INTERRUPT_CALLBACK-'></a>
### StartPollGPIStatus() `method`

##### Summary

Start to poll GPI status

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-StartUdpPollGPIStatus-CSLibrary-Structures-GPI_INTERRUPT_CALLBACK-'></a>
### StartUdpPollGPIStatus(func) `method`

##### Summary

StartPollGPIStatus

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| func | [CSLibrary.Structures.GPI_INTERRUPT_CALLBACK](#T-CSLibrary-Structures-GPI_INTERRUPT_CALLBACK 'CSLibrary.Structures.GPI_INTERRUPT_CALLBACK') |  |

<a name='M-CSLibrary-HighLevelInterface-StopPollGPIStatus'></a>
### StopPollGPIStatus() `method`

##### Summary

StopPollGPIStatus

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-SyncInventory-System-Byte,CSLibrary-Structures-InventoryCallbackDelegate,CSLibrary-Constants-SelectFlags-'></a>
### SyncInventory(tagStopCount,callback,flags) `method`

##### Summary

Executes a tag inventory for the tags of interest.  If the
SelectFlags.SELECT flag is specified, the tag population is
partitioned (i.e., ISO 18000-6C select) prior to the inventory operation.
If the RFID_FLAG_PERFORM_POST_MATCH flag is specified, the post-singulation
match mask is applied to a singulated tag's EPC to determine if the tag
will be returned to the application.  The operation-response packets
will be returned to the application via the application-supplied callback
function.  An application may prematurely stop an inventory operation by
calling RFID_Radio{Cancel|Abort}Operation on another thread or by returning
a non-zero value from the callback function.  A tag inventory may not be
issued while a radio module is executing a tag-protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| tagStopCount | [System.Byte](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte 'System.Byte') | The maximum number of tags to which the tag-protocol operation 
will be applied.  If this number is zero, then the operation is applied 
to all tags that match the selection, and optionally post-singulation, 
match criteria (within the constraints of the antenna-port dwell time 
and inventory cycle count – see ).  If this number is non-zero, the 
antenna-port dwell-time and inventory-cycle-count constraints still 
apply, however the operation will be prematurely terminated if the 
maximum number of tags have the tag-protocol operation applied to 
them.  For version 1.3, this field may have a maximum value 255. |
| callback | [CSLibrary.Structures.InventoryCallbackDelegate](#T-CSLibrary-Structures-InventoryCallbackDelegate 'CSLibrary.Structures.InventoryCallbackDelegate') | callback function |
| flags | [CSLibrary.Constants.SelectFlags](#T-CSLibrary-Constants-SelectFlags 'CSLibrary.Constants.SelectFlags') | read flags.  May be zero or a combination of the following:
SelectFlags.SELECT - perform one or more selects before performing
  the read.
SelectFlags.POST_MATCH - perform post-singulation mask match on
  singulated tags. |

<a name='M-CSLibrary-HighLevelInterface-SyncKill-System-UInt32,CSLibrary-Constants-ExtendedKillCommand,System-Byte,CSLibrary-Structures-TagAccessCallbackDelegate,CSLibrary-Constants-SelectFlags-'></a>
### SyncKill(killPassword,killCmd,tagStopCount,callback,flags) `method`

##### Summary

Executes a tag kill for the tags of interest.  If the
SelectFlags.SELECT flag is specified, the tag population is
partitioned (i.e., ISO 18000-6C select) prior to the tag-kill operation.
If the RFID_FLAG_PERFORM_POST_MATCH flag is specified, the post-singulation
match mask is applied to a singulated tag's EPC to determine if the tag
will be killed.  The operation-response packets will be returned to the
application via the application-supplied callback function.  Each tag-kill
record is grouped with its corresponding tag-inventory record.  An
application may prematurely stop a kill operation by calling
RFID_Radio{Cancel|Abort}Operation on another thread or by returning a non-
zerovalue from the callback function.  A tag kill may not be
issued while a radio module is executing a tag-protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| killPassword | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The kill password for the tags. |
| killCmd | [CSLibrary.Constants.ExtendedKillCommand](#T-CSLibrary-Constants-ExtendedKillCommand 'CSLibrary.Constants.ExtendedKillCommand') | Extended Kill command for UHF class 1 gen-2 version 1.2 |
| tagStopCount | [System.Byte](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte 'System.Byte') | `Please use 1 for tag kill.`

The maximum number of tags to which the tag-protocol operation 
will be applied.  If this number is zero, then the operation is applied 
to all tags that match the selection, and optionally post-singulation, 
match criteria (within the constraints of the antenna-port dwell time 
and inventory cycle count – see ).  If this number is non-zero, the 
antenna-port dwell-time and inventory-cycle-count constraints still 
apply, however the operation will be prematurely terminated if the 
maximum number of tags have the tag-protocol operation applied to 
them.  For version 1.3, this field may have a maximum value 255. |
| callback | [CSLibrary.Structures.TagAccessCallbackDelegate](#T-CSLibrary-Structures-TagAccessCallbackDelegate 'CSLibrary.Structures.TagAccessCallbackDelegate') | callback function |
| flags | [CSLibrary.Constants.SelectFlags](#T-CSLibrary-Constants-SelectFlags 'CSLibrary.Constants.SelectFlags') | read flags.  May be zero or a combination of the following:
SelectFlags.SELECT - perform one or more selects before performing
  the read.
SelectFlags.POST_MATCH - perform post-singulation mask match on
  singulated tags. |

<a name='M-CSLibrary-HighLevelInterface-SyncLock-System-UInt32,CSLibrary-Constants-Permission,CSLibrary-Constants-Permission,CSLibrary-Constants-Permission,CSLibrary-Constants-Permission,CSLibrary-Constants-Permission,System-Byte,CSLibrary-Structures-TagAccessCallbackDelegate,CSLibrary-Constants-SelectFlags-'></a>
### SyncLock(password,kilMemoryBank,accMemoryBank,epcMemoryBank,tidMemoryBank,usrMemoryBank,tagStopCount,callback,flags) `method`

##### Summary

Executes a tag lock for the tags of interest.  If the
SelectFlags.SELECT flag is specified, the tag population is
partitioned (i.e., ISO 18000-6C select) prior to the tag-lock operation.
If the SelectFlags.POST_MATCH flag is specified, the post-singulation
match mask is applied to a singulated tag's EPC to determine if the tag
will be locked.  The operation-response packets will be returned to the
application via the application-supplied callback function.  Each tag-lock
record is grouped with its corresponding tag-inventory record.  An
application may prematurely stop a lock operation by calling
RFID_Radio{Cancel|Abort}Operation on another thread or by returning a non-
zero value from the callback function.  A tag lock may not be
issued while a radio module is executing a tag-protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| password | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The access password for the tags.  A value of zero indicates no 
access password. |
| kilMemoryBank | [CSLibrary.Constants.Permission](#T-CSLibrary-Constants-Permission 'CSLibrary.Constants.Permission') | The access permissions for the tag's kill password. |
| accMemoryBank | [CSLibrary.Constants.Permission](#T-CSLibrary-Constants-Permission 'CSLibrary.Constants.Permission') | The access permissions for the tag's access password. |
| epcMemoryBank | [CSLibrary.Constants.Permission](#T-CSLibrary-Constants-Permission 'CSLibrary.Constants.Permission') | The access permissions for the tag's EPC memory bank. |
| tidMemoryBank | [CSLibrary.Constants.Permission](#T-CSLibrary-Constants-Permission 'CSLibrary.Constants.Permission') | The access permissions for the tag's TID memory bank. |
| usrMemoryBank | [CSLibrary.Constants.Permission](#T-CSLibrary-Constants-Permission 'CSLibrary.Constants.Permission') | The access permissions for the tag's user memory bank. |
| tagStopCount | [System.Byte](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte 'System.Byte') | The maximum number of tags to which the tag-protocol operation 
will be applied.  If this number is zero, then the operation is applied 
to all tags that match the selection, and optionally post-singulation, 
match criteria (within the constraints of the antenna-port dwell time 
and inventory cycle count – see ).  If this number is non-zero, the 
antenna-port dwell-time and inventory-cycle-count constraints still 
apply, however the operation will be prematurely terminated if the 
maximum number of tags have the tag-protocol operation applied to 
them.  For version 1.3, this field may have a maximum value 255. |
| callback | [CSLibrary.Structures.TagAccessCallbackDelegate](#T-CSLibrary-Structures-TagAccessCallbackDelegate 'CSLibrary.Structures.TagAccessCallbackDelegate') | callback function |
| flags | [CSLibrary.Constants.SelectFlags](#T-CSLibrary-Constants-SelectFlags 'CSLibrary.Constants.SelectFlags') | read flags.  May be zero or a combination of the following:
SelectFlags.SELECT - perform one or more selects before performing
  the read.
SelectFlags.POST_MATCH - perform post-singulation mask match on
  singulated tags. |

<a name='M-CSLibrary-HighLevelInterface-SyncMatch-System-UInt16,System-UInt16,CSLibrary-Constants-MemoryBank,CSLibrary-Constants-Target,CSLibrary-Constants-Action,System-Boolean,CSLibrary-Structures-S_MASK-'></a>
### SyncMatch(offset,count,bank,target,action,enableTruncate,mask) `method`

##### Summary

An application may require that the tag population be logically partitioned into 
disjoint groups prior to issuing an inventory operation or access command.  After 
the tags are partitioned, the specified operation may then be applied to one of 
the groups.  Two pieces of information are used to partition a tag population into 
disjoint groups and control to which tags an operation is applied.  These pieces 
of information, which are explained in subsequent sections, are:  a tag mask
and the action that is to be performed on partitioned tag populations

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| offset | [System.UInt16](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16 'System.UInt16') | The offset, in bits, from the start of the memory bank, of the 
first bit that will be matched against the mask.  If offset falls 
beyond the end of the memory bank, the tag is considered 
non-matching. |
| count | [System.UInt16](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16 'System.UInt16') | The number of bits in the mask.  A length of zero will cause all 
tags to match.  If (offset+count) falls beyond the end of 
the memory bank, the tag is considered non-matching.  Valid 
values are 0 to 255, inclusive. |
| bank | [CSLibrary.Constants.MemoryBank](#T-CSLibrary-Constants-MemoryBank 'CSLibrary.Constants.MemoryBank') | The memory bank that contains the bits that will be compared 
against the bit pattern specified in mask.  For a tag mask, 
[RESERVED](#F-CSLibrary-Constants-MemoryBank-RESERVED 'CSLibrary.Constants.MemoryBank.RESERVED') is not a valid value. |
| target | [CSLibrary.Constants.Target](#T-CSLibrary-Constants-Target 'CSLibrary.Constants.Target') | Specifies what flag, selected (i.e., SL) or one of the four inventory 
flags (i.e., S0, S1, S2, or S3), will be modified by the action. |
| action | [CSLibrary.Constants.Action](#T-CSLibrary-Constants-Action 'CSLibrary.Constants.Action') | Specifies the action that will be applied to the tag populations (i.e, the 
matching and non-matching tags). |
| enableTruncate | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') | Specifies if, during singulation, a tag will respond to a subsequent 
inventory operation with its entire Electronic Product Code (EPC) or 
will only respond with the portion of the EPC that immediately follows 
the bit pattern (as long as the bit pattern falls within the EPC – if the 
bit pattern does not fall within the tag’s EPC, the tag ignores the tag 
partitioning operation2).  If this parameter is true:

bank must be [EPC](#F-CSLibrary-Constants-MemoryBank-EPC 'CSLibrary.Constants.MemoryBank.EPC').

target must be [SELECTED](#F-CSLibrary-Constants-Target-SELECTED 'CSLibrary.Constants.Target.SELECTED').

This action must correspond to the last tag select operation issued 
before the inventory operation or access command. |
| mask | [CSLibrary.Structures.S_MASK](#T-CSLibrary-Structures-S_MASK 'CSLibrary.Structures.S_MASK') | A mask that contains a left-justified bit array that represents 
that bit pattern to match |

<a name='M-CSLibrary-HighLevelInterface-SyncRead-System-UInt16,System-UInt16,CSLibrary-Constants-MemoryBank,System-UInt32,System-Byte,CSLibrary-Structures-TagAccessCallbackDelegate,CSLibrary-Constants-SelectFlags-'></a>
### SyncRead(offset,count,bank,password,tagStopCount,callback,flags) `method`

##### Summary

Executes a tag read for the tags of interest.  If the
SelectFlags.SELECT flag is specified, the tag population is
partitioned (i.e., ISO 18000-6C select) prior to the tag-read operation.
If the RFID_FLAG_PERFORM_POST_MATCH flag is specified, the post-singulation
match mask is applied to a singulated tag's EPC to determine if the tag
will be read from.  Reads may only be performed on 16-bit word boundaries
and for multiples of 16-bit words.  If one or more of the memory words
specified by the offset/count combination do not exist or are read-locked,
the read from the tag will fail and this failure will be reported through
the operation response packet.    The operation-response packets will
be returned to the application via the application-supplied callback
function.  Each tag-read record is grouped with its corresponding tag-
inventory record.  An application may prematurely stop a read operation by
calling RFID_Radio{Cancel|Abort}Operation on another thread or by returning
a non-zero value from the callback function.  A tag read may not be
issued while a radio module is executing a tag-protocol operation.

Note that read should not be confused with inventory.  A read allows for
reading a sequence of one or more 16-bit words starting from an arbitrary
16-bit location in any of the tag's memory banks.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| offset | [System.UInt16](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16 'System.UInt16') | The offset of the first 16-bit word, where zero is the first 16-bit 
word in the memory bank, to read from the specified memory 
bank. |
| count | [System.UInt16](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16 'System.UInt16') | The number of 16-bit words to read.  If this value is zero and 
bank is MemoryBank.EPC, the read will return the 
contents of the tag's EPC memory starting at the 16-bit word 
specified by offset through the end of the EPC.  If this value is 
zero and bank is not MemoryBank.EPC, the read 
will return, for the tag's chosen memory bank, data starting from 
the 16-bit word specified by offset to the end of the memory 
bank.  If this value is non-zero, it must be in the range 1 to 255, 
inclusive. |
| bank | [CSLibrary.Constants.MemoryBank](#T-CSLibrary-Constants-MemoryBank 'CSLibrary.Constants.MemoryBank') | The memory bank from which to read.  Valid values are:

MemoryBank.RESERVED

MemoryBank.EPC

MemoryBank.TID

MemoryBank.USER |
| password | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The access password for the tags.  A value of zero indicates no 
access password. |
| tagStopCount | [System.Byte](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte 'System.Byte') | The maximum number of tags to which the tag-protocol operation 
will be applied.  If this number is zero, then the operation is applied 
to all tags that match the selection, and optionally post-singulation, 
match criteria (within the constraints of the antenna-port dwell time 
and inventory cycle count – see ).  If this number is non-zero, the 
antenna-port dwell-time and inventory-cycle-count constraints still 
apply, however the operation will be prematurely terminated if the 
maximum number of tags have the tag-protocol operation applied to 
them.  For version 1.3, this field may have a maximum value 255. |
| callback | [CSLibrary.Structures.TagAccessCallbackDelegate](#T-CSLibrary-Structures-TagAccessCallbackDelegate 'CSLibrary.Structures.TagAccessCallbackDelegate') | callback function |
| flags | [CSLibrary.Constants.SelectFlags](#T-CSLibrary-Constants-SelectFlags 'CSLibrary.Constants.SelectFlags') | read flags.  May be zero or a combination of the following:
SelectFlags.SELECT - perform one or more selects before performing
  the read.
SelectFlags.POST_MATCH - perform post-singulation mask match on
  singulated tags. |

<a name='M-CSLibrary-HighLevelInterface-SyncWrite-System-UInt16,System-UInt16,CSLibrary-Constants-MemoryBank,System-UInt32,System-Byte,System-UInt16[],CSLibrary-Structures-TagAccessCallbackDelegate,CSLibrary-Constants-SelectFlags-'></a>
### SyncWrite(offset,count,bank,password,tagStopCount,data,callback,flags) `method`

##### Summary

Executes a tag write for the tags of interest.  If the
SelectFlags.SELECT flag is specified, the tag population is
partitioned (i.e., ISO 18000-6C select) prior to the tag-write operation.
If the RFID_FLAG_PERFORM_POST_MATCH flag is specified, the post-singulation
match mask is applied to a singulated tag's EPC to determine if the tag
will be written to.  Writes may only be performed on 16-bit word boundaries
and for multiples of 16-bit words.  If one or more of the specified memory
words do not exist or are write-locked, the write to the tag will fail and
this failure will be reported through the operation-response packet.  The
operation-response packets will be returned to the application via
the application-supplied callback function.  Each tag-write record is
grouped with its corresponding tag-inventory record.  An application may
prematurely stop a write operation by calling
RFID_Radio{Cancel|Abort}Operation on another thread or by returning a non-
zero value from the callback function.  A tag write may not be
issued while a radio module is executing a tag-protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| offset | [System.UInt16](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16 'System.UInt16') | The offset of the first 16-bit word, where zero is the first 16-bit 
word in the memory bank, to write in the specified memory bank. |
| count | [System.UInt16](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16 'System.UInt16') | The number of 16-bit words to be written to the tag's specified 
memory bank.  For version 1.1 of the RFID Reader Library, this 
parameter must contain a value between 1 and 8, inclusive. |
| bank | [CSLibrary.Constants.MemoryBank](#T-CSLibrary-Constants-MemoryBank 'CSLibrary.Constants.MemoryBank') | The memory bank from which to read.  Valid values are:

MemoryBank.RESERVED

MemoryBank.EPC

MemoryBank.TID

MemoryBank.USER |
| password | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The access password for the tags.  A value of zero indicates no 
access password. |
| tagStopCount | [System.Byte](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte 'System.Byte') | The maximum number of tags to which the tag-protocol operation 
will be applied.  If this number is zero, then the operation is applied 
to all tags that match the selection, and optionally post-singulation, 
match criteria (within the constraints of the antenna-port dwell time 
and inventory cycle count – see ).  If this number is non-zero, the 
antenna-port dwell-time and inventory-cycle-count constraints still 
apply, however the operation will be prematurely terminated if the 
maximum number of tags have the tag-protocol operation applied to 
them.  For version 1.3, this field may have a maximum value 255. |
| data | [System.UInt16[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16[] 'System.UInt16[]') | A buffer of count 16-bit values to be written 
sequentially to the tag's specified memory bank.  The high-order 
byte of pData[n] will be written to the tag's memory-bank byte at 
16-bit offset (offset+n).  The low-order byte will be written to the 
next byte.  For example, if offset is 2 and pData[0] is 0x1122, 
then the tag-memory byte at 16-bit offset 2 (byte offset 4) will have 
0x11 written to it and the next byte (byte offset 5) will have 0x22 
written to it.  This field must not be NULL. |
| callback | [CSLibrary.Structures.TagAccessCallbackDelegate](#T-CSLibrary-Structures-TagAccessCallbackDelegate 'CSLibrary.Structures.TagAccessCallbackDelegate') | callback function |
| flags | [CSLibrary.Constants.SelectFlags](#T-CSLibrary-Constants-SelectFlags 'CSLibrary.Constants.SelectFlags') | read flags.  May be zero or a combination of the following:
SelectFlags.SELECT - perform one or more selects before performing
  the read.
SelectFlags.POST_MATCH - perform post-singulation mask match on
  singulated tags. |

<a name='M-CSLibrary-HighLevelInterface-SyncWrite-System-UInt16[],System-UInt16,CSLibrary-Constants-MemoryBank,System-UInt32,System-Byte,System-UInt16[],CSLibrary-Structures-TagAccessCallbackDelegate,CSLibrary-Constants-SelectFlags-'></a>
### SyncWrite(offset,count,bank,password,tagStopCount,data,callback,flags) `method`

##### Summary

Executes a tag write for the tags of interest.  If the
SelectFlags.SELECT flag is specified, the tag population is
partitioned (i.e., ISO 18000-6C select) prior to the tag-write operation.
If the RFID_FLAG_PERFORM_POST_MATCH flag is specified, the post-singulation
match mask is applied to a singulated tag's EPC to determine if the tag
will be written to.  Writes may only be performed on 16-bit word boundaries
and for multiples of 16-bit words.  If one or more of the specified memory
words do not exist or are write-locked, the write to the tag will fail and
this failure will be reported through the operation-response packet.  The
operation-response packets will be returned to the application via
the application-supplied callback function.  Each tag-write record is
grouped with its corresponding tag-inventory record.  An application may
prematurely stop a write operation by calling
RFID_Radio{Cancel|Abort}Operation on another thread or by returning a non-
zero value from the callback function.  A tag write may not be
issued while a radio module is executing a tag-protocol operation.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| offset | [System.UInt16[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16[] 'System.UInt16[]') | An array of count 16-bit values that specify 16-bit tag-
memory-bank offsets, with zero being the first 16-bit word in the 
memory bank, where the corresponding 16-bit words in the pData 
array will be written.  i.e., the 16-bit word in pData[n] will be written to 
the 16-bit tag-memory-bank offset contained in pOffset[n].  This 
field must not be NULL. |
| count | [System.UInt16](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16 'System.UInt16') | The number of 16-bit words to be written to the tag's specified 
memory bank.  For version 1.1 of the RFID Reader Library, this 
parameter must contain a value between 1 and 8, inclusive. |
| bank | [CSLibrary.Constants.MemoryBank](#T-CSLibrary-Constants-MemoryBank 'CSLibrary.Constants.MemoryBank') | The memory bank from which to read.  Valid values are:

MemoryBank.RESERVED

MemoryBank.EPC

MemoryBank.TID

MemoryBank.USER |
| password | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | The access password for the tags.  A value of zero indicates no 
access password. |
| tagStopCount | [System.Byte](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte 'System.Byte') | The maximum number of tags to which the tag-protocol operation 
will be applied.  If this number is zero, then the operation is applied 
to all tags that match the selection, and optionally post-singulation, 
match criteria (within the constraints of the antenna-port dwell time 
and inventory cycle count – see ).  If this number is non-zero, the 
antenna-port dwell-time and inventory-cycle-count constraints still 
apply, however the operation will be prematurely terminated if the 
maximum number of tags have the tag-protocol operation applied to 
them.  For version 1.3, this field may have a maximum value 255. |
| data | [System.UInt16[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16[] 'System.UInt16[]') | A buffer of count 16-bit values to be written 
sequentially to the tag's specified memory bank.  The high-order 
byte of pData[n] will be written to the tag's memory-bank byte at 
16-bit offset (offset+n).  The low-order byte will be written to the 
next byte.  For example, if offset is 2 and pData[0] is 0x1122, 
then the tag-memory byte at 16-bit offset 2 (byte offset 4) will have 
0x11 written to it and the next byte (byte offset 5) will have 0x22 
written to it.  This field must not be NULL. |
| callback | [CSLibrary.Structures.TagAccessCallbackDelegate](#T-CSLibrary-Structures-TagAccessCallbackDelegate 'CSLibrary.Structures.TagAccessCallbackDelegate') | callback function |
| flags | [CSLibrary.Constants.SelectFlags](#T-CSLibrary-Constants-SelectFlags 'CSLibrary.Constants.SelectFlags') | read flags.  May be zero or a combination of the following:
SelectFlags.SELECT - perform one or more selects before performing
  the read.
SelectFlags.POST_MATCH - perform post-singulation mask match on
  singulated tags. |

<a name='M-CSLibrary-HighLevelInterface-TurnCarrierWaveOff'></a>
### TurnCarrierWaveOff() `method`

##### Summary

Turn off Carrier Wave

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-TurnCarrierWaveOn-System-Boolean-'></a>
### TurnCarrierWaveOn() `method`

##### Summary

Turn on Carrier Wave

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-UDPKeepAliveOff'></a>
### UDPKeepAliveOff() `method`

##### Summary

TurnOff UDP Keep-Alive

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-UDPKeepAliveOff-System-String-'></a>
### UDPKeepAliveOff() `method`

##### Summary

TurnOff UDP Keep-Alive

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-UDPKeepAliveOn'></a>
### UDPKeepAliveOn() `method`

##### Summary

TurnOn UDP Keep-Alive

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-HighLevelInterface-UDPKeepAliveOn-System-String-'></a>
### UDPKeepAliveOn() `method`

##### Summary

TurnOn UDP Keep-Alive

##### Returns



##### Parameters

This method has no parameters.

<a name='T-CSLibrary-Structures-IBANK'></a>
## IBANK `type`

##### Namespace

CSLibrary.Structures

##### Summary



<a name='M-CSLibrary-Structures-IBANK-GetLength'></a>
### GetLength() `method`

##### Summary

Get Data Length, Data in Ushort format

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-IBANK-ToBytes'></a>
### ToBytes() `method`

##### Summary

Convert Value to Byte array

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-IBANK-ToShorts'></a>
### ToShorts() `method`

##### Summary

Convert Value to short array

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-IBANK-ToString'></a>
### ToString() `method`

##### Summary

Convert Data to Hex String

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-IBANK-ToUshorts'></a>
### ToUshorts() `method`

##### Summary

Convert Value to ushort array

##### Parameters

This method has no parameters.

<a name='T-CSLibrary-HighLevelInterface-INTERFACETYPE'></a>
## INTERFACETYPE `type`

##### Namespace

CSLibrary.HighLevelInterface

##### Summary

Communication interface

<a name='F-CSLibrary-HighLevelInterface-INTERFACETYPE-IPV4'></a>
### IPV4 `constants`

##### Summary

IPv4 (Enther Net)

<a name='F-CSLibrary-HighLevelInterface-INTERFACETYPE-SERIAL'></a>
### SERIAL `constants`

##### Summary

Serial Port

<a name='F-CSLibrary-HighLevelInterface-INTERFACETYPE-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown

<a name='F-CSLibrary-HighLevelInterface-INTERFACETYPE-USB'></a>
### USB `constants`

##### Summary

USB

<a name='T-CSLibrary-Structures-INVENTORY_PKT'></a>
## INVENTORY_PKT `type`

##### Namespace

CSLibrary.Structures

##### Summary

Tag Access Packet

<a name='M-CSLibrary-Structures-INVENTORY_PKT-#ctor-System-Byte,System-UInt32,System-Single,System-UInt16,System-UInt16,System-Boolean,System-String,System-String-'></a>
### #ctor(flags,ms,rssi,ana_ctrl,ana_port,isTruncate,pc,epc) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| flags | [System.Byte](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte 'System.Byte') | error flags |
| ms | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | error flags |
| rssi | [System.Single](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Single 'System.Single') | access command |
| ana_ctrl | [System.UInt16](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16 'System.UInt16') | The value of the R1000’s ANA_CTRL1 register at time the RSSI

measurement was taken - contains the IF LNA’s gain info for RSSI.

Bits 15:6: reserved for future use

Bits 5:4: IF LNA gain. 0=24dB, 1=18dB, 3=12dB

Bits 3:0: reserved for future use |
| ana_port | [System.UInt16](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16 'System.UInt16') | ana_port |
| isTruncate | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') | isTruncate |
| pc | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | data |
| epc | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | data |

<a name='F-CSLibrary-Structures-INVENTORY_PKT-ana_ctrl'></a>
### ana_ctrl `constants`

##### Summary

The value of the R1000’s ANA_CTRL1 register at time the RSSI

measurement was taken - contains the IF LNA’s gain info for RSSI.

Bits 15:6: reserved for future use

Bits 5:4: IF LNA gain. 0=24dB, 1=18dB, 3=12dB

Bits 3:0: reserved for future use

<a name='F-CSLibrary-Structures-INVENTORY_PKT-ana_port'></a>
### ana_port `constants`

##### Summary

Antenna port number currently using.

<a name='F-CSLibrary-Structures-INVENTORY_PKT-epc'></a>
### epc `constants`

##### Summary

Electronic Product Code

<a name='F-CSLibrary-Structures-INVENTORY_PKT-isTruncate'></a>
### isTruncate `constants`

##### Summary

EPC is truncated.

<a name='F-CSLibrary-Structures-INVENTORY_PKT-ms_ctr'></a>
### ms_ctr `constants`

##### Summary

Current millisecond timer/counter

<a name='F-CSLibrary-Structures-INVENTORY_PKT-pc'></a>
### pc `constants`

##### Summary

Protocol Control

<a name='F-CSLibrary-Structures-INVENTORY_PKT-rssi'></a>
### rssi `constants`

##### Summary

The Receive Signal Strength Indicator (RSSI).

<a name='P-CSLibrary-Structures-INVENTORY_PKT-IsCRCInvalid'></a>
### IsCRCInvalid `property`

##### Summary

CRC invalid flag:

false = CRC was valid

true  = CRC was invalid

<a name='T-CSLibrary-Net-IP'></a>
## IP `type`

##### Namespace

CSLibrary.Net

##### Summary

IP Structure

<a name='F-CSLibrary-Net-IP-Address'></a>
### Address `constants`

##### Summary

IP Address in 4 bytes format

<a name='M-CSLibrary-Net-IP-ToString'></a>
### ToString() `method`

##### Summary

IP Address in String format, i.e. 127.0.0.1

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Net-IP-op_Implicit-CSLibrary-Net-IP-~System-String'></a>
### op_Implicit(ip) `method`

##### Summary

Convert to string

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| ip | [CSLibrary.Net.IP)~System.String](#T-CSLibrary-Net-IP-~System-String 'CSLibrary.Net.IP)~System.String') |  |

<a name='M-CSLibrary-Net-IP-op_Implicit-CSLibrary-Net-IP-~System-Int64'></a>
### op_Implicit(ip) `method`

##### Summary

Convert to string

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| ip | [CSLibrary.Net.IP)~System.Int64](#T-CSLibrary-Net-IP-~System-Int64 'CSLibrary.Net.IP)~System.Int64') |  |

<a name='T-CSLibrary-Structures-InternalCustCmdEASParms'></a>
## InternalCustCmdEASParms `type`

##### Namespace

CSLibrary.Structures

<a name='M-CSLibrary-Structures-InternalCustCmdEASParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-InternalCustCmdEASParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no access 
password.

<a name='F-CSLibrary-Structures-InternalCustCmdEASParms-enable'></a>
### enable `constants`

##### Summary

Enable EAS

<a name='F-CSLibrary-Structures-InternalCustCmdEASParms-length'></a>
### length `constants`

##### Summary

Structure size

<a name='F-CSLibrary-Structures-InternalCustCmdEASParms-retry'></a>
### retry `constants`

##### Summary

Retry count

<a name='T-CSLibrary-Structures-InternalCustCmdTagReadProtectParms'></a>
## InternalCustCmdTagReadProtectParms `type`

##### Namespace

CSLibrary.Structures

<a name='M-CSLibrary-Structures-InternalCustCmdTagReadProtectParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-InternalCustCmdTagReadProtectParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no access 
password.

<a name='F-CSLibrary-Structures-InternalCustCmdTagReadProtectParms-length_'></a>
### length_ `constants`

##### Summary

Structure size

<a name='F-CSLibrary-Structures-InternalCustCmdTagReadProtectParms-retry'></a>
### retry `constants`

##### Summary

Retry count

<a name='T-CSLibrary-Structures-InternalTagInventoryParms'></a>
## InternalTagInventoryParms `type`

##### Namespace

CSLibrary.Structures

<a name='M-CSLibrary-Structures-InternalTagInventoryParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-InternalTagInventoryParms-flags'></a>
### flags `constants`

##### Summary

Flag - Zero or combination of  Select or Post-Match

<a name='F-CSLibrary-Structures-InternalTagInventoryParms-tagStopCount'></a>
### tagStopCount `constants`

##### Summary

The maximum number of tags to which the tag-protocol operation will be

applied.  If this number is zero, then the operation is applied to all

tags that match the selection, and optionally post-singulation, match

criteria.  If this number is non-zero, the antenna-port dwell-time and

inventory-round-count constraints still apply, however the operation

will be prematurely terminated if the maximum number of tags have the

tag-protocol operation applied to them.

<a name='T-CSLibrary-Structures-InternalTagRangingParms'></a>
## InternalTagRangingParms `type`

##### Namespace

CSLibrary.Structures

##### Summary



<a name='M-CSLibrary-Structures-InternalTagRangingParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-InternalTagRangingParms-flags'></a>
### flags `constants`

##### Summary

Flag - Zero or combination of  Select or Post-Match

<a name='F-CSLibrary-Structures-InternalTagRangingParms-length'></a>
### length `constants`

##### Summary

Structure size

<a name='F-CSLibrary-Structures-InternalTagRangingParms-tagStopCount'></a>
### tagStopCount `constants`

##### Summary

The maximum number of tags to which the tag-protocol operation will be

applied.  If this number is zero, then the operation is applied to all

tags that match the selection, and optionally post-singulation, match

criteria.  If this number is non-zero, the antenna-port dwell-time and

inventory-round-count constraints still apply, however the operation

will be prematurely terminated if the maximum number of tags have the

tag-protocol operation applied to them.

<a name='T-CSLibrary-Structures-InternalTagReadProtectParms'></a>
## InternalTagReadProtectParms `type`

##### Namespace

CSLibrary.Structures

<a name='M-CSLibrary-Structures-InternalTagReadProtectParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-InternalTagReadProtectParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no access 
password.

<a name='F-CSLibrary-Structures-InternalTagReadProtectParms-common'></a>
### common `constants`

##### Summary

The common tag-protocol operation parameters.

<a name='F-CSLibrary-Structures-InternalTagReadProtectParms-length_'></a>
### length_ `constants`

##### Summary

Structure size

<a name='T-CSLibrary-Structures-InternalTagSearchOneParms'></a>
## InternalTagSearchOneParms `type`

##### Namespace

CSLibrary.Structures

<a name='M-CSLibrary-Structures-InternalTagSearchOneParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-InternalTagSearchOneParms-avgRssi'></a>
### avgRssi `constants`

##### Summary



<a name='F-CSLibrary-Structures-InternalTagSearchOneParms-length'></a>
### length `constants`

##### Summary

Structure size

<a name='T-CSLibrary-Structures-InventoryCallbackDelegate'></a>
## InventoryCallbackDelegate `type`

##### Namespace

CSLibrary.Structures

##### Summary

Tag access callback

##### Returns

return false will abort operation

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| pkt | [T:CSLibrary.Structures.InventoryCallbackDelegate](#T-T-CSLibrary-Structures-InventoryCallbackDelegate 'T:CSLibrary.Structures.InventoryCallbackDelegate') | packet data |

<a name='T-CSLibrary-Structures-InventoryParms'></a>
## InventoryParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

An inventory operation allows the application to gather the EPCs (or part of the 
EPCs if the tag-select action specified to truncate the response) for all tags of 
interest.  The data returned from the inventory operation will adhere to the format 
specified in [REC].

<a name='M-CSLibrary-Structures-InventoryParms-#ctor-System-Boolean-'></a>
### #ctor(initial) `constructor`

##### Summary

Initial Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| initial | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') |  |

<a name='F-CSLibrary-Structures-InventoryParms-common'></a>
### common `constants`

##### Summary

The common tag-protocol operation parameters.

<a name='T-CSLibrary-Constants-IsoMDID'></a>
## IsoMDID `type`

##### Namespace

CSLibrary.Constants

##### Summary

ISO/IEC 7816-6 registration authority

<a name='F-CSLibrary-Constants-IsoMDID-AMIC'></a>
### AMIC `constants`

##### Summary

AMIC Technology Corp

<a name='F-CSLibrary-Constants-IsoMDID-ASK'></a>
### ASK `constants`

##### Summary

ASK

<a name='F-CSLibrary-Constants-IsoMDID-ATMEL'></a>
### ATMEL `constants`

##### Summary

ATMEL

<a name='F-CSLibrary-Constants-IsoMDID-Alliance'></a>
### Alliance `constants`

##### Summary

RightPlug Alliance

<a name='F-CSLibrary-Constants-IsoMDID-Belling'></a>
### Belling `constants`

##### Summary

Shanghai Belling Corp., Ltd.

<a name='F-CSLibrary-Constants-IsoMDID-Broadcom'></a>
### Broadcom `constants`

##### Summary

Broadcom Corporation

<a name='F-CSLibrary-Constants-IsoMDID-Cylink'></a>
### Cylink `constants`

##### Summary

Cylink

<a name='F-CSLibrary-Constants-IsoMDID-Cypak'></a>
### Cypak `constants`

##### Summary

Cypak AB

<a name='F-CSLibrary-Constants-IsoMDID-Dallas'></a>
### Dallas `constants`

##### Summary

Dallas Semiconductor/Maxim

<a name='F-CSLibrary-Constants-IsoMDID-EM'></a>
### EM `constants`

##### Summary

EM Microelectronic-Marin SA

<a name='F-CSLibrary-Constants-IsoMDID-Emosyn'></a>
### Emosyn `constants`

##### Summary

Emosyn

<a name='F-CSLibrary-Constants-IsoMDID-EmosynEM'></a>
### EmosynEM `constants`

##### Summary

Emosyn-EM Microelectronics

<a name='F-CSLibrary-Constants-IsoMDID-Fudan'></a>
### Fudan `constants`

##### Summary

Shanghai Fudan Microelectronics Co. Ltd.

<a name='F-CSLibrary-Constants-IsoMDID-Fujitsu'></a>
### Fujitsu `constants`

##### Summary

Fujitsu Limited

<a name='F-CSLibrary-Constants-IsoMDID-Hitachi'></a>
### Hitachi `constants`

##### Summary

Hitachi, Ltd

<a name='F-CSLibrary-Constants-IsoMDID-HitachiULSI'></a>
### HitachiULSI `constants`

##### Summary

Hitachi ULSI Systems Co., Ltd.

<a name='F-CSLibrary-Constants-IsoMDID-Hynix'></a>
### Hynix `constants`

##### Summary

Hynix

<a name='F-CSLibrary-Constants-IsoMDID-INSIDE'></a>
### INSIDE `constants`

##### Summary

INSIDE Technology

<a name='F-CSLibrary-Constants-IsoMDID-Impinj'></a>
### Impinj `constants`

##### Summary

Impinj, Inc.

<a name='F-CSLibrary-Constants-IsoMDID-Infineon'></a>
### Infineon `constants`

##### Summary

Infineon Technologies AG

<a name='F-CSLibrary-Constants-IsoMDID-Innovision'></a>
### Innovision `constants`

##### Summary

Innovision Research and Techology Plc

<a name='F-CSLibrary-Constants-IsoMDID-KSW'></a>
### KSW `constants`

##### Summary

KSW Microtec GmbH

<a name='F-CSLibrary-Constants-IsoMDID-LG'></a>
### LG `constants`

##### Summary

LG-Semiconductors Co. Ltd

<a name='F-CSLibrary-Constants-IsoMDID-MStar'></a>
### MStar `constants`

##### Summary

MStar Semiconductor, Inc

<a name='F-CSLibrary-Constants-IsoMDID-Magellan'></a>
### Magellan `constants`

##### Summary

Magellan Technology Pty Limited

<a name='F-CSLibrary-Constants-IsoMDID-Malaysia'></a>
### Malaysia `constants`

##### Summary

Malaysia Microelectronic Solutions Sdn. Bhd

<a name='F-CSLibrary-Constants-IsoMDID-Masktech'></a>
### Masktech `constants`

##### Summary

Masktech Germany Gmbh

<a name='F-CSLibrary-Constants-IsoMDID-Matsushita'></a>
### Matsushita `constants`

##### Summary

Matsushita Electronics Corporation, Semiconductor Co.

<a name='F-CSLibrary-Constants-IsoMDID-Melexis'></a>
### Melexis `constants`

##### Summary

Melexis NV BO

<a name='F-CSLibrary-Constants-IsoMDID-Mitsubishi'></a>
### Mitsubishi `constants`

##### Summary

Mitsubishi Electric Corp.

<a name='F-CSLibrary-Constants-IsoMDID-Motorola'></a>
### Motorola `constants`

##### Summary

Motorola

<a name='F-CSLibrary-Constants-IsoMDID-NEC'></a>
### NEC `constants`

##### Summary

NEC

<a name='F-CSLibrary-Constants-IsoMDID-ORGA'></a>
### ORGA `constants`

##### Summary

ORGA Kartensysteme GmbH

<a name='F-CSLibrary-Constants-IsoMDID-Oki'></a>
### Oki `constants`

##### Summary

Oki Electric Industry Co. Ltd

<a name='F-CSLibrary-Constants-IsoMDID-Philips'></a>
### Philips `constants`

##### Summary

Philips Semiconductors

<a name='F-CSLibrary-Constants-IsoMDID-RFIDsec'></a>
### RFIDsec `constants`

##### Summary

RFIDsec

<a name='F-CSLibrary-Constants-IsoMDID-Renesas'></a>
### Renesas `constants`

##### Summary

Renesas Technology Corp.

<a name='F-CSLibrary-Constants-IsoMDID-Ricoh'></a>
### Ricoh `constants`

##### Summary

Ricoh

<a name='F-CSLibrary-Constants-IsoMDID-SHARP'></a>
### SHARP `constants`

##### Summary

SHARP Corporation

<a name='F-CSLibrary-Constants-IsoMDID-STM'></a>
### STM `constants`

##### Summary

STMicroelectronics SA

<a name='F-CSLibrary-Constants-IsoMDID-Samsung'></a>
### Samsung `constants`

##### Summary

Samsung Electronics Co. Ltd

<a name='F-CSLibrary-Constants-IsoMDID-Schweizer'></a>
### Schweizer `constants`

##### Summary

Schweizer Electronic AG

<a name='F-CSLibrary-Constants-IsoMDID-Sony'></a>
### Sony `constants`

##### Summary

Sony Corporation

<a name='F-CSLibrary-Constants-IsoMDID-TAGSYS'></a>
### TAGSYS `constants`

##### Summary

TAGSYS

<a name='F-CSLibrary-Constants-IsoMDID-Texas'></a>
### Texas `constants`

##### Summary

Texas Instrument

<a name='F-CSLibrary-Constants-IsoMDID-Toshiba'></a>
### Toshiba `constants`

##### Summary

Toshiba Corp.

<a name='F-CSLibrary-Constants-IsoMDID-Transcore'></a>
### Transcore `constants`

##### Summary

Transcore

<a name='F-CSLibrary-Constants-IsoMDID-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown company

<a name='F-CSLibrary-Constants-IsoMDID-Unicore'></a>
### Unicore `constants`

##### Summary

Unicore Microsystems, LLC

<a name='F-CSLibrary-Constants-IsoMDID-XICOR'></a>
### XICOR `constants`

##### Summary

XICOR, Inc.

<a name='F-CSLibrary-Constants-IsoMDID-ZMD'></a>
### ZMD `constants`

##### Summary

ZMD AG

<a name='F-CSLibrary-Constants-IsoMDID-eeDar'></a>
### eeDar `constants`

##### Summary

eeDar Technology Inc.

<a name='T-CSLibrary-Structures-KillCmdParms'></a>
## KillCmdParms `type`

##### Namespace

CSLibrary.Structures

<a name='M-CSLibrary-Structures-KillCmdParms-#ctor-System-Boolean-'></a>
### #ctor(initial) `constructor`

##### Summary

Initial Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| initial | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') |  |

<a name='F-CSLibrary-Structures-KillCmdParms-killPassword'></a>
### killPassword `constants`

##### Summary

The kill password for the tags.

<a name='T-CSLibrary-Structures-KillParms'></a>
## KillParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

A tag-kill command allows an application to kill (i.e., render inoperable) a set of 
tags of interest.  The data returned from the tag kill will adhere to the format 
specified in [REC].

<a name='M-CSLibrary-Structures-KillParms-#ctor-System-Boolean-'></a>
### #ctor(initial) `constructor`

##### Summary

Initial Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| initial | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') |  |

<a name='F-CSLibrary-Structures-KillParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no access 
password.

<a name='F-CSLibrary-Structures-KillParms-common'></a>
### common `constants`

##### Summary

The common tag-protocol operation parameters.

<a name='F-CSLibrary-Structures-KillParms-killCmdParms'></a>
### killCmdParms `constants`

##### Summary

The ISO 18000-6C tag-kill specific command parameters

<a name='F-CSLibrary-Structures-KillParms-length'></a>
### length `constants`

##### Summary

Structure size

<a name='T-CSLibrary-Constants-LBT'></a>
## LBT `type`

##### Namespace

CSLibrary.Constants

##### Summary

LBT Config

<a name='F-CSLibrary-Constants-LBT-OFF'></a>
### OFF `constants`

##### Summary

LBT OFF

<a name='F-CSLibrary-Constants-LBT-ON'></a>
### ON `constants`

##### Summary

LBT ON

<a name='F-CSLibrary-Constants-LBT-SCAN'></a>
### SCAN `constants`

##### Summary

LBT SCAN MODE

<a name='T-CSLibrary-Structures-LibraryVersion'></a>
## LibraryVersion `type`

##### Namespace

CSLibrary.Structures

##### Summary

Library Version Structure

<a name='M-CSLibrary-Structures-LibraryVersion-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='T-CSLibrary-LinkProfileInfo'></a>
## LinkProfileInfo `type`

##### Namespace

CSLibrary

##### Summary

LinkProfile Information

<a name='M-CSLibrary-LinkProfileInfo-#ctor-CSLibrary-Structures-RadioLinkProfile-'></a>
### #ctor(linkProfile) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| linkProfile | [CSLibrary.Structures.RadioLinkProfile](#T-CSLibrary-Structures-RadioLinkProfile 'CSLibrary.Structures.RadioLinkProfile') |  |

<a name='P-CSLibrary-LinkProfileInfo-DenseReaderMode'></a>
### DenseReaderMode `property`

##### Summary

Dense Reader Mode enable

<a name='P-CSLibrary-LinkProfileInfo-Description'></a>
### Description `property`

##### Summary

Profile Description

<a name='P-CSLibrary-LinkProfileInfo-Enabled'></a>
### Enabled `property`

##### Summary

Enable current profile

<a name='P-CSLibrary-LinkProfileInfo-LinkProfileConfig'></a>
### LinkProfileConfig `property`

##### Summary



<a name='P-CSLibrary-LinkProfileInfo-Name'></a>
### Name `property`

##### Summary

Profile Name

<a name='P-CSLibrary-LinkProfileInfo-NarrowbandRssiSamples'></a>
### NarrowbandRssiSamples `property`

##### Summary

Narrowband Rssi Samples

<a name='P-CSLibrary-LinkProfileInfo-ProfileId'></a>
### ProfileId `property`

##### Summary

LinkProfile ID

<a name='P-CSLibrary-LinkProfileInfo-ProfileProtocol'></a>
### ProfileProtocol `property`

##### Summary

LinkPrile Protocol

<a name='P-CSLibrary-LinkProfileInfo-ProfileUniqueId'></a>
### ProfileUniqueId `property`

##### Summary

LinkProfile UID

<a name='P-CSLibrary-LinkProfileInfo-ProfileVersion'></a>
### ProfileVersion `property`

##### Summary

LinkProfile Version

<a name='P-CSLibrary-LinkProfileInfo-RealtimeNarrowbandRssiSamples'></a>
### RealtimeNarrowbandRssiSamples `property`

##### Summary

Realtime Narrowband Rssi Samples

<a name='P-CSLibrary-LinkProfileInfo-RealtimeRssiEnabled'></a>
### RealtimeRssiEnabled `property`

##### Summary

Realtime Rssi Enabled

<a name='P-CSLibrary-LinkProfileInfo-RealtimeWidebandRssiSamples'></a>
### RealtimeWidebandRssiSamples `property`

##### Summary

Realtime Wideband Rssi Samples

<a name='P-CSLibrary-LinkProfileInfo-WidebandRssiSamples'></a>
### WidebandRssiSamples `property`

##### Summary

Wideband Rssi Samples

<a name='M-CSLibrary-LinkProfileInfo-ToString'></a>
### ToString() `method`

##### Summary



##### Returns



##### Parameters

This method has no parameters.

<a name='T-CSLibrary-Structures-LockCmdParms'></a>
## LockCmdParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

The ISO 18000-6C tag-lock operation lock specific command parameters.

<a name='F-CSLibrary-Structures-LockCmdParms-length'></a>
### length `constants`

##### Summary

Structure size

<a name='F-CSLibrary-Structures-LockCmdParms-permissions'></a>
### permissions `constants`

##### Summary

A structure that contains the access permissions to be set for the tag.

<a name='T-CSLibrary-Structures-LockParms'></a>
## LockParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

A  tag-permission  command  (aka,  tag  lock)  allows  the  application  to  set  the 
access permissions of a tag.

<a name='F-CSLibrary-Structures-LockParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no access 
password.

<a name='F-CSLibrary-Structures-LockParms-common'></a>
### common `constants`

##### Summary

The common tag-protocol operation parameters.

<a name='F-CSLibrary-Structures-LockParms-length'></a>
### length `constants`

##### Summary

Structure size

<a name='F-CSLibrary-Structures-LockParms-lockCmdParms'></a>
### lockCmdParms `constants`

##### Summary

The ISO 18000-6C tag-lock operation lock specific command parameters.

<a name='T-CSLibrary-Structures-LoggingForm'></a>
## LoggingForm `type`

##### Namespace

CSLibrary.Structures

##### Summary

Logging Form

<a name='T-CSLibrary-Net-MAC'></a>
## MAC `type`

##### Namespace

CSLibrary.Net

##### Summary

MAC Structure

<a name='F-CSLibrary-Net-MAC-Address'></a>
### Address `constants`

##### Summary

Mac Address in 6 bytes format

<a name='M-CSLibrary-Net-MAC-Equals-System-Object-'></a>
### Equals(obj) `method`

##### Summary

Check equal

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| obj | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') |  |

<a name='M-CSLibrary-Net-MAC-Parse-System-String-'></a>
### Parse(address) `method`

##### Summary

Parse String to Byte array format

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| address | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |  |

<a name='M-CSLibrary-Net-MAC-ToString'></a>
### ToString() `method`

##### Summary

MAC Address in String format, i.e. 00:19:BB:44:7C:AA

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Net-MAC-op_Implicit-CSLibrary-Net-MAC-~System-String'></a>
### op_Implicit(mac) `method`

##### Summary

Convert to string

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| mac | [CSLibrary.Net.MAC)~System.String](#T-CSLibrary-Net-MAC-~System-String 'CSLibrary.Net.MAC)~System.String') |  |

<a name='T-CSLibrary-HighLevelInterface-MacRegister'></a>
## MacRegister `type`

##### Namespace

CSLibrary.HighLevelInterface

##### Summary

REGISTER NAME/ADDRESS CONSTANTS

<a name='T-CSLibrary-Constants-MacResetType'></a>
## MacResetType `type`

##### Namespace

CSLibrary.Constants

##### Summary

The type of reset that the MAC should perform.

<a name='F-CSLibrary-Constants-MacResetType-SOFT'></a>
### SOFT `constants`

##### Summary

Soft reset

<a name='F-CSLibrary-Constants-MacResetType-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown action

<a name='T-CSLibrary-Structures-MacVersion'></a>
## MacVersion `type`

##### Namespace

CSLibrary.Structures

##### Summary

Mac Version Structure

<a name='M-CSLibrary-Structures-MacVersion-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='M-CSLibrary-Structures-MacVersion-#ctor-System-UInt32,System-UInt32,System-UInt32-'></a>
### #ctor(major,minor,patch) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| major | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| minor | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| patch | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |

<a name='T-CSLibrary-Constants-Machine'></a>
## Machine `type`

##### Namespace

CSLibrary.Constants

##### Summary

Machine Type

<a name='T-CSLibrary-Constants-MemoryBank'></a>
## MemoryBank `type`

##### Namespace

CSLibrary.Constants

##### Summary

Tag's memory bank

<a name='F-CSLibrary-Constants-MemoryBank-BANK0'></a>
### BANK0 `constants`

##### Summary

Bank 0

<a name='F-CSLibrary-Constants-MemoryBank-BANK1'></a>
### BANK1 `constants`

##### Summary

Bank 1

<a name='F-CSLibrary-Constants-MemoryBank-BANK2'></a>
### BANK2 `constants`

##### Summary

Bank 2

<a name='F-CSLibrary-Constants-MemoryBank-BANK3'></a>
### BANK3 `constants`

##### Summary

Bank 3

<a name='F-CSLibrary-Constants-MemoryBank-EPC'></a>
### EPC `constants`

##### Summary

PC and EPC memory bank

<a name='F-CSLibrary-Constants-MemoryBank-RESERVED'></a>
### RESERVED `constants`

##### Summary

Acesss and Kill password bank

<a name='F-CSLibrary-Constants-MemoryBank-TID'></a>
### TID `constants`

##### Summary

TID bank

<a name='F-CSLibrary-Constants-MemoryBank-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown

<a name='F-CSLibrary-Constants-MemoryBank-USER'></a>
### USER `constants`

##### Summary

User memory bank

<a name='T-CSLibrary-Constants-MillerNumber'></a>
## MillerNumber `type`

##### Namespace

CSLibrary.Constants

##### Summary

The miller number (i.e., cycles per symbol) that is sent as 
part of the Query command.

<a name='F-CSLibrary-Constants-MillerNumber-NUMBER_2'></a>
### NUMBER_2 `constants`

##### Summary

The FM0 signal is multiplied by a square wave with either 2 periods for each FM0 symbol.

<a name='F-CSLibrary-Constants-MillerNumber-NUMBER_4'></a>
### NUMBER_4 `constants`

##### Summary

The FM0 signal is multiplied by a square wave with either 4 periods for each FM0 symbol.

<a name='F-CSLibrary-Constants-MillerNumber-NUMBER_8'></a>
### NUMBER_8 `constants`

##### Summary

The FM0 signal is multiplied by a square wave with either 8 periods for each FM0 symbol.

<a name='F-CSLibrary-Constants-MillerNumber-NUMBER_FM0'></a>
### NUMBER_FM0 `constants`

##### Summary

A binary '0' has a transition in the middle of a symbol, whereas a binary '1' does not.

<a name='F-CSLibrary-Constants-MillerNumber-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown

<a name='T-CSLibrary-Net-Mode'></a>
## Mode `type`

##### Namespace

CSLibrary.Net

##### Summary

Netfinder Mode

<a name='F-CSLibrary-Net-Mode-Bootloader'></a>
### Bootloader `constants`

##### Summary

Bootloader mode (Network device)

<a name='F-CSLibrary-Net-Mode-Normal'></a>
### Normal `constants`

##### Summary

Application mode (Network device)

<a name='F-CSLibrary-Net-Mode-NormalSerial'></a>
### NormalSerial `constants`

##### Summary

Application mode (Serial Device)

<a name='F-CSLibrary-Net-Mode-NormalUsb'></a>
### NormalUsb `constants`

##### Summary

Application mode (USB Device)

<a name='F-CSLibrary-Net-Mode-Unknown'></a>
### Unknown `constants`

##### Summary

Unknown

<a name='T-CSLibrary-Net-Modes'></a>
## Modes `type`

##### Namespace

CSLibrary.Net

##### Summary

TFTP modes

<a name='T-CSLibrary-Constants-ModulationType'></a>
## ModulationType `type`

##### Namespace

CSLibrary.Constants

##### Summary

The modulation type that is used by the profile.

<a name='F-CSLibrary-Constants-ModulationType-DSB_ASK'></a>
### DSB_ASK `constants`

##### Summary

DSB_ASK Modulation

<a name='F-CSLibrary-Constants-ModulationType-PR_ASK'></a>
### PR_ASK `constants`

##### Summary

PR_ASK Modulation

<a name='F-CSLibrary-Constants-ModulationType-SSB_ASK'></a>
### SSB_ASK `constants`

##### Summary

SSB_ASK Modulation

<a name='F-CSLibrary-Constants-ModulationType-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown

<a name='T-CSLibrary-Net-NetFinder'></a>
## NetFinder `type`

##### Namespace

CSLibrary.Net

##### Summary

Search device on ethernet

<a name='M-CSLibrary-Net-NetFinder-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='P-CSLibrary-Net-NetFinder-LastError'></a>
### LastError `property`

##### Summary

Get last error message

<a name='P-CSLibrary-Net-NetFinder-Operation'></a>
### Operation `property`

##### Summary

Get current recevice mode operation

<a name='P-CSLibrary-Net-NetFinder-Radios'></a>
### Radios `property`

##### Summary

Get Radios list in the same network

<a name='M-CSLibrary-Net-NetFinder-AssignDevice-System-Byte[],System-Byte[],System-Byte[],System-Boolean-'></a>
### AssignDevice(targetMacAddress,ipAddressTo,trustedServerAddress,trustedServerEnabled) `method`

##### Summary

Change Target device IP, trusted server address

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| targetMacAddress | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| ipAddressTo | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| trustedServerAddress | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| trustedServerEnabled | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') |  |

##### Remarks

You must call SearchDevice() before call this function.

<a name='M-CSLibrary-Net-NetFinder-AssignDevice-System-Byte[],System-Byte[],System-Byte,System-Boolean-'></a>
### AssignDevice(targetMacAddress,ipAddressTo,DHCPRetry,DHCPEnabled) `method`

##### Summary

Assign target device information

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| targetMacAddress | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| ipAddressTo | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| DHCPRetry | [System.Byte](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte 'System.Byte') |  |
| DHCPEnabled | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') |  |

##### Remarks

You must call SearchDevice() before call this function.

<a name='M-CSLibrary-Net-NetFinder-AssignDevice-System-Byte[],System-Byte[],System-String,System-Byte,System-Boolean-'></a>
### AssignDevice(targetMacAddress,ipAddressTo,deviceName,DHCPRetry,DHCPEnabled) `method`

##### Summary

Assign target device information

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| targetMacAddress | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| ipAddressTo | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| deviceName | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |  |
| DHCPRetry | [System.Byte](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte 'System.Byte') |  |
| DHCPEnabled | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') |  |

##### Remarks

You must call SearchDevice() before call this function.

<a name='M-CSLibrary-Net-NetFinder-AssignDevice-System-Byte[],System-Byte[],System-String,System-Byte,System-Boolean,System-Byte[],System-Boolean,System-Byte[],System-Byte[],System-Int32-'></a>
### AssignDevice(targetMacAddress,ipAddressTo,deviceName,DHCPRetry,DHCPEnabled,trustedServerAddress,trustedServerEnabled,subnet,gateway) `method`

##### Summary

Assign target device information

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| targetMacAddress | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | Target device address(You must call SearchDevice() to discovery all device first) |
| ipAddressTo | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | Changable IP only use if DHCPEnabled is `False` |
| deviceName | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | target device name |
| DHCPRetry | [System.Byte](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte 'System.Byte') | DHCP retry count |
| DHCPEnabled | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') | If set to True, DHCP will assign dynamic IP. |
| trustedServerAddress | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | Trusted Server Address |
| trustedServerEnabled | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') | If set to True, target device can only connect to trusted server |
| subnet | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | Subnet Mask |
| gateway | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | Gateway |

<a name='M-CSLibrary-Net-NetFinder-AsyncUpdateEboot-System-String,System-String-'></a>
### AsyncUpdateEboot(IP,ebootfile) `method`

##### Summary

Async update Eboot

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| IP | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |  |
| ebootfile | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |  |

<a name='M-CSLibrary-Net-NetFinder-AsyncUpdateImage-System-String,System-String-'></a>
### AsyncUpdateImage(IP,imagefile) `method`

##### Summary

Async update image

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| IP | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |  |
| imagefile | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |  |

<a name='M-CSLibrary-Net-NetFinder-ClearDeviceList'></a>
### ClearDeviceList() `method`

##### Summary

Clear all device list

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Net-NetFinder-CreateAckPacket-System-Int32-'></a>
### CreateAckPacket(blockNr) `method`

##### Summary

Creates the ack packet.

##### Returns

the ack packet

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| blockNr | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | The block nr. |

<a name='M-CSLibrary-Net-NetFinder-CreateDataPacket-System-Int32,System-Byte[]-'></a>
### CreateDataPacket(blockNr,data) `method`

##### Summary

Creates the data packet.

##### Returns

the data packet

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| blockNr | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | The packet nr. |
| data | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | The data. |

<a name='M-CSLibrary-Net-NetFinder-CreateRequestPacket-CSLibrary-Net-Opcodes,System-String,CSLibrary-Net-Modes-'></a>
### CreateRequestPacket(opCode,remoteFile,tftpMode) `method`

##### Summary

Creates the request packet.

##### Returns

the ack packet

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| opCode | [CSLibrary.Net.Opcodes](#T-CSLibrary-Net-Opcodes 'CSLibrary.Net.Opcodes') | The op code. |
| remoteFile | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The remote file. |
| tftpMode | [CSLibrary.Net.Modes](#T-CSLibrary-Net-Modes 'CSLibrary.Net.Modes') | The TFTP mode. |

<a name='M-CSLibrary-Net-NetFinder-Dispose'></a>
### Dispose() `method`

##### Summary

Dispose resource

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Net-NetFinder-GetApiMode-System-String-'></a>
### GetApiMode() `method`

##### Summary

Get API Mode

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Net-NetFinder-GetPoeInfo-System-String,System-Byte@,System-UInt16@,System-UInt16@-'></a>
### GetPoeInfo() `method`

##### Summary

Get POE Information

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Net-NetFinder-GetTagIndicationMode-System-String-'></a>
### GetTagIndicationMode() `method`

##### Summary

Get Read Tag GPO Indication Status

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Net-NetFinder-ResearchDevice'></a>
### ResearchDevice() `method`

##### Summary

Start to re-search device on ethernet continuously until Stop function called.

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Net-NetFinder-SearchDevice'></a>
### SearchDevice() `method`

##### Summary

Start to search USB device first and search on ethernet continuously until Stop function called.

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Net-NetFinder-SearchDevice-System-Net-IPAddress-'></a>
### SearchDevice() `method`

##### Summary

Start to search device on ethernet continuously until Stop function called.

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Net-NetFinder-SearchSerialDeivce'></a>
### SearchSerialDeivce() `method`

##### Summary

Start to search device on Serial Ports.

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Net-NetFinder-SearchUsbDevice'></a>
### SearchUsbDevice() `method`

##### Summary

Start to search device on USB.

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Net-NetFinder-SetApiMode-System-String,CSLibrary-Net-ApiMode-'></a>
### SetApiMode() `method`

##### Summary

Set Device Mode (mode 0 = high, 1 = low)

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Net-NetFinder-SetPoePower-System-String,System-UInt16-'></a>
### SetPoePower() `method`

##### Summary

Set POE Request Power 0.1w pre step

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Net-NetFinder-SetTagIndicationMode-System-String,System-Byte-'></a>
### SetTagIndicationMode() `method`

##### Summary

Set Read Tag GPO Indication Status

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Net-NetFinder-Stop'></a>
### Stop() `method`

##### Summary

Stop to search

##### Parameters

This method has no parameters.

<a name='T-CSLibrary-Structures-NonVolatileMemoryBlock'></a>
## NonVolatileMemoryBlock `type`

##### Namespace

CSLibrary.Structures

##### Summary

NonVolatileMemoryBlock - for future use

<a name='M-CSLibrary-Structures-NonVolatileMemoryBlock-#ctor'></a>
### #ctor() `constructor`

##### Summary



##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-NonVolatileMemoryBlock-address'></a>
### address `constants`

##### Summary



<a name='F-CSLibrary-Structures-NonVolatileMemoryBlock-flags'></a>
### flags `constants`

##### Summary



<a name='F-CSLibrary-Structures-NonVolatileMemoryBlock-length'></a>
### length `constants`

##### Summary



<a name='F-CSLibrary-Structures-NonVolatileMemoryBlock-pData'></a>
### pData `constants`

##### Summary



<a name='T-CSLibrary-Events-OnAccessCompletedEventArgs'></a>
## OnAccessCompletedEventArgs `type`

##### Namespace

CSLibrary.Events

##### Summary

Tag Access Completed Argument

<a name='M-CSLibrary-Events-OnAccessCompletedEventArgs-#ctor-System-Boolean,CSLibrary-Constants-Bank,CSLibrary-Constants-TagAccess,CSLibrary-Structures-IBANK-'></a>
### #ctor(success,bank,access,data) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| success | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') | Access Result |
| bank | [CSLibrary.Constants.Bank](#T-CSLibrary-Constants-Bank 'CSLibrary.Constants.Bank') | Access bank |
| access | [CSLibrary.Constants.TagAccess](#T-CSLibrary-Constants-TagAccess 'CSLibrary.Constants.TagAccess') | Access type |
| data | [CSLibrary.Structures.IBANK](#T-CSLibrary-Structures-IBANK 'CSLibrary.Structures.IBANK') | Access Data only use for Tag Read operation |

<a name='F-CSLibrary-Events-OnAccessCompletedEventArgs-access'></a>
### access `constants`

##### Summary

Access Type

<a name='F-CSLibrary-Events-OnAccessCompletedEventArgs-bank'></a>
### bank `constants`

##### Summary

Access bank

<a name='F-CSLibrary-Events-OnAccessCompletedEventArgs-data'></a>
### data `constants`

##### Summary

Access Data only use for Tag Read operation

<a name='F-CSLibrary-Events-OnAccessCompletedEventArgs-success'></a>
### success `constants`

##### Summary

Access Result

<a name='T-CSLibrary-Events-OnAsyncCallbackEventArgs'></a>
## OnAsyncCallbackEventArgs `type`

##### Namespace

CSLibrary.Events

##### Summary

Inventory or tag search callback event argument

<a name='M-CSLibrary-Events-OnAsyncCallbackEventArgs-#ctor-CSLibrary-Structures-TagCallbackInfo,CSLibrary-Constants-CallbackType-'></a>
### #ctor(info,type) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| info | [CSLibrary.Structures.TagCallbackInfo](#T-CSLibrary-Structures-TagCallbackInfo 'CSLibrary.Structures.TagCallbackInfo') | Tag Information |
| type | [CSLibrary.Constants.CallbackType](#T-CSLibrary-Constants-CallbackType 'CSLibrary.Constants.CallbackType') | Callback Type |

<a name='F-CSLibrary-Events-OnAsyncCallbackEventArgs-Cancel'></a>
### Cancel `constants`

##### Summary

Cancel async callback.

<a name='F-CSLibrary-Events-OnAsyncCallbackEventArgs-info'></a>
### info `constants`

##### Summary

Callback Tag Information

<a name='F-CSLibrary-Events-OnAsyncCallbackEventArgs-type'></a>
### type `constants`

##### Summary

Async callback data type

<a name='T-CSLibrary-Events-OnFirmwareUpgradeEventArgs'></a>
## OnFirmwareUpgradeEventArgs `type`

##### Namespace

CSLibrary.Events

##### Summary

Current position of updating

<a name='M-CSLibrary-Events-OnFirmwareUpgradeEventArgs-#ctor-System-UInt64-'></a>
### #ctor(state) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| state | [System.UInt64](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt64 'System.UInt64') |  |

<a name='F-CSLibrary-Events-OnFirmwareUpgradeEventArgs-CurrentUpdateOffset'></a>
### CurrentUpdateOffset `constants`

##### Summary

Current operation state

<a name='T-CSLibrary-Events-OnStateChangedEventArgs'></a>
## OnStateChangedEventArgs `type`

##### Namespace

CSLibrary.Events

##### Summary

Reader Operation changed EventArgs

<a name='M-CSLibrary-Events-OnStateChangedEventArgs-#ctor-CSLibrary-Constants-RFState-'></a>
### #ctor(state) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| state | [CSLibrary.Constants.RFState](#T-CSLibrary-Constants-RFState 'CSLibrary.Constants.RFState') |  |

<a name='F-CSLibrary-Events-OnStateChangedEventArgs-state'></a>
### state `constants`

##### Summary

Current operation state

<a name='T-CSLibrary-Net-Opcodes'></a>
## Opcodes `type`

##### Namespace

CSLibrary.Net

##### Summary

TFTP opcodes

<a name='T-CSLibrary-Constants-Operation'></a>
## Operation `type`

##### Namespace

CSLibrary.Constants

##### Summary

RFID Operation Mode

<a name='F-CSLibrary-Constants-Operation-CL_ACCESS_FIFO'></a>
### CL_ACCESS_FIFO `constants`

##### Summary

Set access FIFO

<a name='F-CSLibrary-Constants-Operation-CL_END_LOG'></a>
### CL_END_LOG `constants`

##### Summary

End log

<a name='F-CSLibrary-Constants-Operation-CL_GET_BAT_LV'></a>
### CL_GET_BAT_LV `constants`

##### Summary

Get battery level

<a name='F-CSLibrary-Constants-Operation-CL_GET_CAL_DATA'></a>
### CL_GET_CAL_DATA `constants`

##### Summary

Get cal data

<a name='F-CSLibrary-Constants-Operation-CL_GET_LOG_STATE'></a>
### CL_GET_LOG_STATE `constants`

##### Summary

get log state

<a name='F-CSLibrary-Constants-Operation-CL_GET_MEASUREMENT_SETUP'></a>
### CL_GET_MEASUREMENT_SETUP `constants`

##### Summary

Get measurement setup

<a name='F-CSLibrary-Constants-Operation-CL_GET_SENSOR_VALUE'></a>
### CL_GET_SENSOR_VALUE `constants`

##### Summary

Get sensor value

<a name='F-CSLibrary-Constants-Operation-CL_INIT'></a>
### CL_INIT `constants`

##### Summary

Init

<a name='F-CSLibrary-Constants-Operation-CL_OPEN_AREA'></a>
### CL_OPEN_AREA `constants`

##### Summary

Open area

<a name='F-CSLibrary-Constants-Operation-CL_SET_CAL_DATA'></a>
### CL_SET_CAL_DATA `constants`

##### Summary

Set cal data

<a name='F-CSLibrary-Constants-Operation-CL_SET_LOG_LIMITS'></a>
### CL_SET_LOG_LIMITS `constants`

##### Summary

Set log limits

<a name='F-CSLibrary-Constants-Operation-CL_SET_LOG_MODE'></a>
### CL_SET_LOG_MODE `constants`

##### Summary

Set log mode

<a name='F-CSLibrary-Constants-Operation-CL_SET_PASSWORD'></a>
### CL_SET_PASSWORD `constants`

##### Summary

Set password

<a name='F-CSLibrary-Constants-Operation-CL_SET_SFE_PARA'></a>
### CL_SET_SFE_PARA `constants`

##### Summary

Set DFE parameter

<a name='F-CSLibrary-Constants-Operation-CL_SET_SHELF_LIFE'></a>
### CL_SET_SHELF_LIFE `constants`

##### Summary

Set shelf life

<a name='F-CSLibrary-Constants-Operation-CL_START_LOG'></a>
### CL_START_LOG `constants`

##### Summary

Start log

<a name='F-CSLibrary-Constants-Operation-EAS_ALARM'></a>
### EAS_ALARM `constants`

##### Summary

EAS Alarm

<a name='F-CSLibrary-Constants-Operation-EAS_CONFIG'></a>
### EAS_CONFIG `constants`

##### Summary

configure EAS

<a name='F-CSLibrary-Constants-Operation-EM4324_GetUid'></a>
### EM4324_GetUid `constants`

##### Summary

Custom EM Get Sensor Data

<a name='F-CSLibrary-Constants-Operation-EM4325_GetUid'></a>
### EM4325_GetUid `constants`

##### Summary

Custom EM Get Sensor Data

<a name='F-CSLibrary-Constants-Operation-EM_GetSensorData'></a>
### EM_GetSensorData `constants`

##### Summary

Custom EM Get Sensor Data

<a name='F-CSLibrary-Constants-Operation-EM_ResetAlarms'></a>
### EM_ResetAlarms `constants`

##### Summary

Custom EM Get Sensor Data

<a name='F-CSLibrary-Constants-Operation-EM_SPI'></a>
### EM_SPI `constants`

##### Summary

SPI Command

<a name='F-CSLibrary-Constants-Operation-EM_SPIAlarm'></a>
### EM_SPIAlarm `constants`

##### Summary

EM4325 Command

<a name='F-CSLibrary-Constants-Operation-EM_SPIBoot'></a>
### EM_SPIBoot `constants`

##### Summary

EM4325 Command

<a name='F-CSLibrary-Constants-Operation-EM_SPIGetSensorData'></a>
### EM_SPIGetSensorData `constants`

##### Summary

EM4325 Command

<a name='F-CSLibrary-Constants-Operation-EM_SPIReadPage'></a>
### EM_SPIReadPage `constants`

##### Summary

EM4325 Command

<a name='F-CSLibrary-Constants-Operation-EM_SPIReadRegisterFileWord'></a>
### EM_SPIReadRegisterFileWord `constants`

##### Summary

EM4325 Command

<a name='F-CSLibrary-Constants-Operation-EM_SPIReadWord'></a>
### EM_SPIReadWord `constants`

##### Summary

EM4325 Command

<a name='F-CSLibrary-Constants-Operation-EM_SPIReqRN'></a>
### EM_SPIReqRN `constants`

##### Summary

EM4325 Command

<a name='F-CSLibrary-Constants-Operation-EM_SPIRequestStatus'></a>
### EM_SPIRequestStatus `constants`

##### Summary

SPI Command

<a name='F-CSLibrary-Constants-Operation-EM_SPISetClock'></a>
### EM_SPISetClock `constants`

##### Summary

EM4325 Command

<a name='F-CSLibrary-Constants-Operation-EM_SPISetFlags'></a>
### EM_SPISetFlags `constants`

##### Summary

EM4325 Command

<a name='F-CSLibrary-Constants-Operation-EM_SPITransponder'></a>
### EM_SPITransponder `constants`

##### Summary

EM4325 Command

<a name='F-CSLibrary-Constants-Operation-EM_SPIWritePage'></a>
### EM_SPIWritePage `constants`

##### Summary

EM4325 Command

<a name='F-CSLibrary-Constants-Operation-EM_SPIWriteRegisterFileWord'></a>
### EM_SPIWriteRegisterFileWord `constants`

##### Summary

EM4325 Command

<a name='F-CSLibrary-Constants-Operation-EM_SPIWriteWord'></a>
### EM_SPIWriteWord `constants`

##### Summary

EM4325 Command

<a name='F-CSLibrary-Constants-Operation-G2_CHANGE_CONFIG'></a>
### G2_CHANGE_CONFIG `constants`

##### Summary

G2iL Change Config

<a name='F-CSLibrary-Constants-Operation-G2_CHANGE_EAS'></a>
### G2_CHANGE_EAS `constants`

##### Summary

G2X ChangeEAS

<a name='F-CSLibrary-Constants-Operation-G2_EAS_ALARM'></a>
### G2_EAS_ALARM `constants`

##### Summary

G2X EAS Alarm

<a name='F-CSLibrary-Constants-Operation-G2_READ_PROTECT'></a>
### G2_READ_PROTECT `constants`

##### Summary

G2X ReadProtect

<a name='F-CSLibrary-Constants-Operation-G2_RESET_READ_PROTECT'></a>
### G2_RESET_READ_PROTECT `constants`

##### Summary

G2X Reset ReadProtect

<a name='F-CSLibrary-Constants-Operation-QT_COMMAND'></a>
### QT_COMMAND `constants`

##### Summary

QT Command

<a name='F-CSLibrary-Constants-Operation-TAG_BLOCK_PERMALOCK'></a>
### TAG_BLOCK_PERMALOCK `constants`

##### Summary

perform 18K6C BlockPermalock to target tag

<a name='F-CSLibrary-Constants-Operation-TAG_BLOCK_WRITE'></a>
### TAG_BLOCK_WRITE `constants`

##### Summary

perform 18K6C block write to target tag

<a name='F-CSLibrary-Constants-Operation-TAG_INVENTORY'></a>
### TAG_INVENTORY `constants`

##### Summary

perform inventory on any tags

<a name='F-CSLibrary-Constants-Operation-TAG_KILL'></a>
### TAG_KILL `constants`

##### Summary

perform 18K6C tag kill to target tag

<a name='F-CSLibrary-Constants-Operation-TAG_LOCK'></a>
### TAG_LOCK `constants`

##### Summary

perform 18K6C tag lock to target tag

<a name='F-CSLibrary-Constants-Operation-TAG_PREFILTER'></a>
### TAG_PREFILTER `constants`

##### Summary

PreFilter

<a name='F-CSLibrary-Constants-Operation-TAG_RANGING'></a>
### TAG_RANGING `constants`

##### Summary

perform custom ranging on any tags

<a name='F-CSLibrary-Constants-Operation-TAG_READ'></a>
### TAG_READ `constants`

##### Summary

perform 18K6C tag read to target tag

<a name='F-CSLibrary-Constants-Operation-TAG_READ_ACC_PWD'></a>
### TAG_READ_ACC_PWD `constants`

##### Summary

perform custom read on access password

<a name='F-CSLibrary-Constants-Operation-TAG_READ_EPC'></a>
### TAG_READ_EPC `constants`

##### Summary

perform custom read on epc

<a name='F-CSLibrary-Constants-Operation-TAG_READ_KILL_PWD'></a>
### TAG_READ_KILL_PWD `constants`

##### Summary

perform custom read on kill password

<a name='F-CSLibrary-Constants-Operation-TAG_READ_PC'></a>
### TAG_READ_PC `constants`

##### Summary

perform custom read on pc

<a name='F-CSLibrary-Constants-Operation-TAG_READ_PROTECT'></a>
### TAG_READ_PROTECT `constants`

##### Summary

perform read protect custom command on specific tags

<a name='F-CSLibrary-Constants-Operation-TAG_READ_TID'></a>
### TAG_READ_TID `constants`

##### Summary

perform custom read on tid

<a name='F-CSLibrary-Constants-Operation-TAG_READ_USER'></a>
### TAG_READ_USER `constants`

##### Summary

perform custom read on user bank

<a name='F-CSLibrary-Constants-Operation-TAG_RESET_READ_PROTECT'></a>
### TAG_RESET_READ_PROTECT `constants`

##### Summary

perform reset read protect custom search on specific tags

<a name='F-CSLibrary-Constants-Operation-TAG_SEARCHING'></a>
### TAG_SEARCHING `constants`

##### Summary

perform custom search specific tags

<a name='F-CSLibrary-Constants-Operation-TAG_SELECTED'></a>
### TAG_SELECTED `constants`

##### Summary

Select a tag for operation

<a name='F-CSLibrary-Constants-Operation-TAG_WRITE'></a>
### TAG_WRITE `constants`

##### Summary

perform 18K6C tag write to target tag

<a name='F-CSLibrary-Constants-Operation-TAG_WRITE_ACC_PWD'></a>
### TAG_WRITE_ACC_PWD `constants`

##### Summary

perform custom write on access password

<a name='F-CSLibrary-Constants-Operation-TAG_WRITE_EPC'></a>
### TAG_WRITE_EPC `constants`

##### Summary

perform custom write on epc

<a name='F-CSLibrary-Constants-Operation-TAG_WRITE_KILL_PWD'></a>
### TAG_WRITE_KILL_PWD `constants`

##### Summary

perform custom write on kill password

<a name='F-CSLibrary-Constants-Operation-TAG_WRITE_PC'></a>
### TAG_WRITE_PC `constants`

##### Summary

perform custom write on pc

<a name='F-CSLibrary-Constants-Operation-TAG_WRITE_USER'></a>
### TAG_WRITE_USER `constants`

##### Summary

perform custom write on user bank

<a name='F-CSLibrary-Constants-Operation-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknow operation

<a name='T-CSLibrary-Constants-OptType'></a>
## OptType `type`

##### Namespace

CSLibrary.Constants

<a name='T-CSLibrary-Constants-PacketBitMap'></a>
## PacketBitMap `type`

##### Namespace

CSLibrary.Constants

<a name='F-CSLibrary-Constants-PacketBitMap-accessErrorFlag'></a>
### accessErrorFlag `constants`

<a name='F-CSLibrary-Constants-PacketBitMap-crcResult'></a>
### crcResult `constants`

<a name='T-CSLibrary-Structures-PasswordLevel'></a>
## PasswordLevel `type`

##### Namespace

CSLibrary.Structures

##### Summary

Password Level

<a name='F-CSLibrary-Structures-PasswordLevel-Application'></a>
### Application `constants`

##### Summary

Application Password

<a name='F-CSLibrary-Structures-PasswordLevel-Measurement'></a>
### Measurement `constants`

##### Summary

Measurement Password

<a name='F-CSLibrary-Structures-PasswordLevel-System'></a>
### System `constants`

##### Summary

System Password

<a name='T-CSLibrary-Structures-PermalockCmdParms'></a>
## PermalockCmdParms `type`

##### Namespace

CSLibrary.Structures

<a name='M-CSLibrary-Structures-PermalockCmdParms-#ctor-CSLibrary-Constants-PermalockFlags,System-UInt16,System-UInt16,System-UInt16[]-'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-PermalockCmdParms-count'></a>
### count `constants`

##### Summary

The number of 16-bit words to be written to the tag's specified memory 
bank.  For version 1.2 of the RFID Reader Library, this parameter must 
contain a value between 1 and 255, inclusive.

<a name='F-CSLibrary-Structures-PermalockCmdParms-flags'></a>
### flags `constants`

##### Summary

Permalock access flags

<a name='F-CSLibrary-Structures-PermalockCmdParms-offset'></a>
### offset `constants`

##### Summary

The number of 16-bit words that will be written.  This field must be 
between 1 and 32, inclusive.

<a name='F-CSLibrary-Structures-PermalockCmdParms-pData'></a>
### pData `constants`

##### Summary

A buffer of count 16-bit values to be written 
sequentially to the tag's specified memory bank.  The high-order 
byte of pData[n] will be written to the tag's memory-bank byte at 
16-bit offset (offset+n).  The low-order byte will be written to the 
next byte.  For example, if offset is 2 and pData[0] is 0x1122, 
then the tag-memory byte at 16-bit offset 2 (byte offset 4) will have 
0x11 written to it and the next byte (byte offset 5) will have 0x22 
written to it.  This field must not be NULL.

<a name='M-CSLibrary-Structures-PermalockCmdParms-Dispose'></a>
### Dispose() `method`

##### Summary

Release all resources

##### Parameters

This method has no parameters.

<a name='T-CSLibrary-Constants-PermalockFlags'></a>
## PermalockFlags `type`

##### Namespace

CSLibrary.Constants

##### Summary

Permalock access flags

<a name='F-CSLibrary-Constants-PermalockFlags-GET_VALUE'></a>
### GET_VALUE `constants`

##### Summary

Get permalock status

<a name='F-CSLibrary-Constants-PermalockFlags-SET_VALUE'></a>
### SET_VALUE `constants`

##### Summary

Set permalock status

<a name='T-CSLibrary-Structures-PermalockParms'></a>
## PermalockParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

A tag block-write command allows an application to write one or more 16-bit 
words to the specified memory bank of the ISO 18000-6C tags of interest.  The 
data returned from the block write will adhere to the format specified in [REC].  A 
Write can be performed on a contiguous set of one or more 16-bit words to one 
of the tag's memory banks.

<a name='F-CSLibrary-Structures-PermalockParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no access 
password.

<a name='F-CSLibrary-Structures-PermalockParms-common'></a>
### common `constants`

##### Summary

The common tag-protocol operation parameters.

<a name='F-CSLibrary-Structures-PermalockParms-length'></a>
### length `constants`

##### Summary

Structure size

<a name='F-CSLibrary-Structures-PermalockParms-permalockCmdParms'></a>
### permalockCmdParms `constants`

##### Summary

Permalock command parms

<a name='T-CSLibrary-Constants-Permission'></a>
## Permission `type`

##### Namespace

CSLibrary.Constants

##### Summary

A  tag-permission  command  (aka,  tag  lock)  allows  the  application  to  set  the 
access permissions of a tag.  These include the following: 
•    Set whether or not an access password is required to write to the EPC, 
TID, or user memory banks.  
•    Set  whether  or  not  the  above  memory-write  permission  is  permanently 
set.    Once  the  memory-write  permission  has  been  permanently  set, 
attempts to change the permission or turn off the permanent setting will 
fail. 
•    Set a memory bank to be read-only. 
•    Set whether or not the individual passwords (i.e., access and kill) may be 
accessed (i.e., read and written) and, if they are accessible, whether or 
not an access password is required to read the individual passwords (i.e., 
access and kill). 
•    Set whether or not the above password-access permission is 
permanently set.  Once the password-access permission has been 
permanently set, attempts to change the permission or turn off the 
permanent setting will fail. 
•    Set the individual passwords to be inaccessible (i.e., unable to be read or 
written).

<a name='F-CSLibrary-Constants-Permission-LOCK'></a>
### LOCK `constants`

##### Summary

This bank can not be accessible unless access password is provided

<a name='F-CSLibrary-Constants-Permission-P_LOCK'></a>
### P_LOCK `constants`

##### Summary

This bank can not be accessible unless access password is provided.
Note : The security of this bank can not be changed

<a name='F-CSLibrary-Constants-Permission-P_UNLOCK'></a>
### P_UNLOCK `constants`

##### Summary

This bank can be read and written permanently.
Note : The security of this bank can not be changed

<a name='F-CSLibrary-Constants-Permission-UNCHANGED'></a>
### UNCHANGED `constants`

##### Summary

The permission should remain unchanged.

<a name='F-CSLibrary-Constants-Permission-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown permission

<a name='F-CSLibrary-Constants-Permission-UNLOCK'></a>
### UNLOCK `constants`

##### Summary

This bank can be read and written

<a name='T-CSLibrary-Structures-ProfileConfig'></a>
## ProfileConfig `type`

##### Namespace

CSLibrary.Structures

##### Summary

Link Profile Configuration Structure

<a name='M-CSLibrary-Structures-ProfileConfig-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-ProfileConfig-length_'></a>
### length_ `constants`

##### Summary

Structure size

<a name='P-CSLibrary-Structures-ProfileConfig-length'></a>
### length `property`

##### Summary

Structure size

<a name='T-CSLibrary-Structures-QTCommandParms'></a>
## QTCommandParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

QT Command Parameter

<a name='M-CSLibrary-Structures-QTCommandParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-QTCommandParms-MEM'></a>
### MEM `constants`

##### Summary

0: Tag uses Reveal Memory Map (Private Mode)
1: Tag uses Conceal Memory Map (Public Mode)

<a name='F-CSLibrary-Structures-QTCommandParms-RW'></a>
### RW `constants`

##### Summary

Read / Write, 
0: read the QT control bits in cache
1: write the QT control bits

<a name='F-CSLibrary-Structures-QTCommandParms-SR'></a>
### SR `constants`

##### Summary

Reduces Range if in or about to be in OPEN or SECURED state
0: Tag does not reduce range
1: Tag reduces range if in or about to be in OPEN or SECURED state

<a name='F-CSLibrary-Structures-QTCommandParms-TP'></a>
### TP `constants`

##### Summary

written to nonvolatile (NVM) or volatile (DFF) memory
0: write to DFF memory
1: write to NVM memory

<a name='F-CSLibrary-Structures-QTCommandParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

Kill/Access Password

<a name='T-CSLibrary-Constants-QTCtrlType'></a>
## QTCtrlType `type`

##### Namespace

CSLibrary.Constants

<a name='T-CSLibrary-Constants-QTMemMapType'></a>
## QTMemMapType `type`

##### Namespace

CSLibrary.Constants

<a name='T-CSLibrary-Structures-QTMode'></a>
## QTMode `type`

##### Namespace

CSLibrary.Structures

##### Summary

QT Mode

<a name='F-CSLibrary-Structures-QTMode-PermPrivate'></a>
### PermPrivate `constants`

##### Summary

Permanent Private

<a name='F-CSLibrary-Structures-QTMode-PermPublic'></a>
### PermPublic `constants`

##### Summary

Permanent Public

<a name='F-CSLibrary-Structures-QTMode-TempPrivate'></a>
### TempPrivate `constants`

##### Summary

Temporary Private

<a name='F-CSLibrary-Structures-QTMode-TempPublic'></a>
### TempPublic `constants`

##### Summary

Temporary Public

<a name='T-CSLibrary-Constants-QTPersistenceType'></a>
## QTPersistenceType `type`

##### Namespace

CSLibrary.Constants

<a name='T-CSLibrary-Constants-QTShortRangeType'></a>
## QTShortRangeType `type`

##### Namespace

CSLibrary.Constants

<a name='T-CSLibrary-Structures-QueryParms'></a>
## QueryParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Once the tag population has been partitioned into disjoint groups, a subsequent 
tag-protocol operation (i.e., an inventory operation or access command) is then 
applied to one of the tag groups.  A tag group is specified using the following:

<a name='M-CSLibrary-Structures-QueryParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-QueryParms-singulationParms'></a>
### singulationParms `constants`

##### Summary

Based upon usage scenarios, different singulation algorithms (i.e., Q-adjustment, 
etc.) may be desired.  This document simply documents the mechanisms by 
which an application can choose and configure singulation algorithms.

<a name='F-CSLibrary-Structures-QueryParms-tagGroup'></a>
### tagGroup `constants`

##### Summary

Once the tag population has been partitioned into disjoint groups, a subsequent 
tag-protocol operation (i.e., an inventory operation or access command) is then 
applied to one of the tag groups.  A tag group is specified using the following:

<a name='T-CSLibrary-Constants-RFID_18K6C'></a>
## RFID_18K6C `type`

##### Namespace

CSLibrary.Constants

##### Summary

The values that can be found in the command field for tag access packets

<a name='F-CSLibrary-Constants-RFID_18K6C-ACCESS'></a>
### ACCESS `constants`

##### Summary

ISO 18000-6C Access

<a name='F-CSLibrary-Constants-RFID_18K6C-ACK'></a>
### ACK `constants`

##### Summary

ISO 18000-6C ACK

<a name='F-CSLibrary-Constants-RFID_18K6C-BLOCKERASE'></a>
### BLOCKERASE `constants`

##### Summary

ISO 18000-6C Block erase

<a name='F-CSLibrary-Constants-RFID_18K6C-BLOCKWRITE'></a>
### BLOCKWRITE `constants`

##### Summary

ISO 18000-6C Block write

<a name='F-CSLibrary-Constants-RFID_18K6C-KILL'></a>
### KILL `constants`

##### Summary

ISO 18000-6C Kill

<a name='F-CSLibrary-Constants-RFID_18K6C-LOCK'></a>
### LOCK `constants`

##### Summary

ISO 18000-6C Lock

<a name='F-CSLibrary-Constants-RFID_18K6C-NAK'></a>
### NAK `constants`

##### Summary

ISO 18000-6C Nak

<a name='F-CSLibrary-Constants-RFID_18K6C-QT'></a>
### QT `constants`

##### Summary

ISO 18000-6C QT command

<a name='F-CSLibrary-Constants-RFID_18K6C-QUERY'></a>
### QUERY `constants`

##### Summary

ISO 18000-6C Query

<a name='F-CSLibrary-Constants-RFID_18K6C-QUERYADJ'></a>
### QUERYADJ `constants`

##### Summary

ISO 18000-6C Query adj

<a name='F-CSLibrary-Constants-RFID_18K6C-QUERYREP'></a>
### QUERYREP `constants`

##### Summary

ISO 18000-6C query response

<a name='F-CSLibrary-Constants-RFID_18K6C-READ'></a>
### READ `constants`

##### Summary

ISO 18000-6C Read

<a name='F-CSLibrary-Constants-RFID_18K6C-REQRN'></a>
### REQRN `constants`

##### Summary

ISO 18000-6C request RN

<a name='F-CSLibrary-Constants-RFID_18K6C-SELECT'></a>
### SELECT `constants`

##### Summary

ISO 18000-6C Select

<a name='F-CSLibrary-Constants-RFID_18K6C-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown

<a name='F-CSLibrary-Constants-RFID_18K6C-WRITE'></a>
### WRITE `constants`

##### Summary

ISO 18000-6C Write

<a name='T-CSLibrary-Constants-RFID_ACCESS'></a>
## RFID_ACCESS `type`

##### Namespace

CSLibrary.Constants

##### Summary

Tag access enum Result

<a name='F-CSLibrary-Constants-RFID_ACCESS-ACK_TIMEOUT'></a>
### ACK_TIMEOUT `constants`

##### Summary

Tag failed to respond within timeout.

<a name='F-CSLibrary-Constants-RFID_ACCESS-CRC_INVALID'></a>
### CRC_INVALID `constants`

##### Summary

CRC was invalid

<a name='F-CSLibrary-Constants-RFID_ACCESS-CRC_INVALID_ON_KILL'></a>
### CRC_INVALID_ON_KILL `constants`

##### Summary

CRC error on tag response to a kill.

<a name='F-CSLibrary-Constants-RFID_ACCESS-CRC_INVALID_ON_READ'></a>
### CRC_INVALID_ON_READ `constants`

##### Summary

CRC error on the read packet when verifying the write.

<a name='F-CSLibrary-Constants-RFID_ACCESS-CRC_INVALID_ON_WRITE'></a>
### CRC_INVALID_ON_WRITE `constants`

##### Summary

CRC error on tag response to a write.

<a name='F-CSLibrary-Constants-RFID_ACCESS-GENERAL_ERR'></a>
### GENERAL_ERR `constants`

##### Summary

general error (catch-all for errors not covered by codes)

<a name='F-CSLibrary-Constants-RFID_ACCESS-INSUFFICIENT_POWER_TO_WRITE'></a>
### INSUFFICIENT_POWER_TO_WRITE `constants`

##### Summary

tag has insufficient power to perform the memory write

<a name='F-CSLibrary-Constants-RFID_ACCESS-INVALID_HANDLE_ON_KILL_CMD'></a>
### INVALID_HANDLE_ON_KILL_CMD `constants`

##### Summary

Tag responded with an invalid handle on first kill command.

<a name='F-CSLibrary-Constants-RFID_ACCESS-MEMORY_LOCATION_NOT_EXIST'></a>
### MEMORY_LOCATION_NOT_EXIST `constants`

##### Summary

specified memory location does not exist of the PC value is not supported by the tag

<a name='F-CSLibrary-Constants-RFID_ACCESS-NOT_SUPPORTED'></a>
### NOT_SUPPORTED `constants`

##### Summary

tag does not support error-specific codes

<a name='F-CSLibrary-Constants-RFID_ACCESS-PERMISSION_DENIED'></a>
### PERMISSION_DENIED `constants`

##### Summary

specified memory location is locked and/or permalocked and is not writeable

<a name='F-CSLibrary-Constants-RFID_ACCESS-PROBLEM_TRANSMITTING_KILL_CMD'></a>
### PROBLEM_TRANSMITTING_KILL_CMD `constants`

##### Summary

Problem transmitting 2nd half of tag kill.

<a name='F-CSLibrary-Constants-RFID_ACCESS-PROBLEM_TRANSMITTING_TAG_CMD'></a>
### PROBLEM_TRANSMITTING_TAG_CMD `constants`

##### Summary

Problem transmitting tag command.

<a name='F-CSLibrary-Constants-RFID_ACCESS-READ_TIMEOUT'></a>
### READ_TIMEOUT `constants`

##### Summary

Failed waiting for read data from tag, possible timeout.

<a name='F-CSLibrary-Constants-RFID_ACCESS-REQ_TAG_HANDLE_FAILED'></a>
### REQ_TAG_HANDLE_FAILED `constants`

##### Summary

Failure requesting a new tag handle.

<a name='F-CSLibrary-Constants-RFID_ACCESS-RESP_TIMEOUT'></a>
### RESP_TIMEOUT `constants`

##### Summary

Error waiting for tag response, possible timeout.

<a name='F-CSLibrary-Constants-RFID_ACCESS-SUCCESS'></a>
### SUCCESS `constants`

##### Summary

access success

<a name='F-CSLibrary-Constants-RFID_ACCESS-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

can't determine error type

<a name='F-CSLibrary-Constants-RFID_ACCESS-WRITE_RETRY_EXCEEDED'></a>
### WRITE_RETRY_EXCEEDED `constants`

##### Summary

Maximum retry's on the write exceeded.

<a name='F-CSLibrary-Constants-RFID_ACCESS-WRITE_VERIFY_FAILED'></a>
### WRITE_VERIFY_FAILED `constants`

##### Summary

Read after write verify failed.

<a name='T-CSLibrary-Constants-RFID_COMMAND_TYPE_18K6C'></a>
## RFID_COMMAND_TYPE_18K6C `type`

##### Namespace

CSLibrary.Constants

##### Summary

Constants for the command begin's cmd field

<a name='F-CSLibrary-Constants-RFID_COMMAND_TYPE_18K6C-INVENTORY'></a>
### INVENTORY `constants`

##### Summary

ISO 18000-6C Inventory

<a name='F-CSLibrary-Constants-RFID_COMMAND_TYPE_18K6C-KILL'></a>
### KILL `constants`

##### Summary

ISO 18000-6C Kill

<a name='F-CSLibrary-Constants-RFID_COMMAND_TYPE_18K6C-LOCK'></a>
### LOCK `constants`

##### Summary

ISO 18000-6C Lock

<a name='F-CSLibrary-Constants-RFID_COMMAND_TYPE_18K6C-READ'></a>
### READ `constants`

##### Summary

ISO 18000-6C Read

<a name='F-CSLibrary-Constants-RFID_COMMAND_TYPE_18K6C-WRITE'></a>
### WRITE `constants`

##### Summary

ISO 18000-6C Write

<a name='T-CSLibrary-Structures-RFID_PACKET_COMMAND_END'></a>
## RFID_PACKET_COMMAND_END `type`

##### Namespace

CSLibrary.Structures

<a name='F-CSLibrary-Structures-RFID_PACKET_COMMAND_END-cmn'></a>
### cmn `constants`

<a name='T-CSLibrary-Structures-RFID_PACKET_COMMON'></a>
## RFID_PACKET_COMMON `type`

##### Namespace

CSLibrary.Structures

##### Summary

The common packet preamble that contains fields that are common to all packets.

<a name='F-CSLibrary-Structures-RFID_PACKET_COMMON-flags'></a>
### flags `constants`

##### Summary

Packet specific flags

<a name='F-CSLibrary-Structures-RFID_PACKET_COMMON-pkt_len'></a>
### pkt_len `constants`

##### Summary

Packet length indicator - number of 32-bit words that follow the common

packet preamble (i.e., this struct)

<a name='F-CSLibrary-Structures-RFID_PACKET_COMMON-pkt_type'></a>
### pkt_type `constants`

##### Summary

Packet type identifier

<a name='F-CSLibrary-Structures-RFID_PACKET_COMMON-pkt_ver'></a>
### pkt_ver `constants`

##### Summary

Packet specific version number

<a name='F-CSLibrary-Structures-RFID_PACKET_COMMON-res0'></a>
### res0 `constants`

##### Summary

Reserved for future use

<a name='T-CSLibrary-Constants-RFID_PACKET_TYPE'></a>
## RFID_PACKET_TYPE `type`

##### Namespace

CSLibrary.Constants

##### Summary

The 16-bit packet types that will be found in the common packet header     
pkt_type field.
  
When adding a new packet type to a class, simply append it to end of the   
appropriate type's enumeration list.   
  
NOTE: These packet type constants are in the endian format for the system  
upon which the compile is being performed.  Before comparing them against  
the packet type field from the packet, ensure that, if necessary, the      
packet type field is converted from little endian (i.e., MAC format) to    
the endian format for the system running the application.

<a name='F-CSLibrary-Constants-RFID_PACKET_TYPE-ANTENNA_BEGIN'></a>
### ANTENNA_BEGIN `constants`

##### Summary

The antenna-begin packet indicates the radio has begun using a particular antenna for 
the current cycle.

<a name='F-CSLibrary-Constants-RFID_PACKET_TYPE-ANTENNA_CYCLE_BEGIN'></a>
### ANTENNA_CYCLE_BEGIN `constants`

##### Summary

The antenna-cycle-begin packet indicates the start of one iteration through all 
enabled, functional antennas.

<a name='F-CSLibrary-Constants-RFID_PACKET_TYPE-ANTENNA_CYCLE_END'></a>
### ANTENNA_CYCLE_END `constants`

##### Summary

The antenna-cycle-end packet indicates the end of one iteration through all enabled, 
functional antennas.

<a name='F-CSLibrary-Constants-RFID_PACKET_TYPE-ANTENNA_END'></a>
### ANTENNA_END `constants`

##### Summary

The antenna-end packet indicates that the radio has stopped using a particular 
antenna for the current cycle.

<a name='F-CSLibrary-Constants-RFID_PACKET_TYPE-CARRIER_INFO'></a>
### CARRIER_INFO `constants`

##### Summary

The Carrier info packet is sent by the Intel® R1000 Firmware whenever Transmit CW 
is turned on and whenever it is turned off. The purpose is to provide timing 
information frequency channel use information to the host application.

<a name='F-CSLibrary-Constants-RFID_PACKET_TYPE-COMMAND_BEGIN'></a>
### COMMAND_BEGIN `constants`

##### Summary

The command-begin packet indicates the start of a sequence of packets for an ISO 
18000-6C tag-protocol operation (i.e. inventory, read, etc.). The type of command 
executed by the RFID radio module determines which data packets appear, and in 
what order they appear, between the command-begin/end packet pair.

<a name='F-CSLibrary-Constants-RFID_PACKET_TYPE-COMMAND_END'></a>
### COMMAND_END `constants`

##### Summary

The command-end packet indicates the end of sequence of packets for an ISO 18000-
6C tag-protocol operation. A command-end packet is always used to terminate a 
packet sequence regardless of the fact that a tag-access operation is completed 
successfully or not.

<a name='F-CSLibrary-Constants-RFID_PACKET_TYPE-CYCCFG_EVT'></a>
### CYCCFG_EVT `constants`

##### Summary

The Cycle configuration event packet is sent when the Intel® R1000 Firmware 
performs a cycle granular configuration adjustment.

<a name='F-CSLibrary-Constants-RFID_PACKET_TYPE-INVENTORY_CYCLE_BEGIN'></a>
### INVENTORY_CYCLE_BEGIN `constants`

##### Summary

The inventory-cycle-begin packet indicates that an inventory round has begun on an 
antenna.

<a name='F-CSLibrary-Constants-RFID_PACKET_TYPE-INVENTORY_CYCLE_END'></a>
### INVENTORY_CYCLE_END `constants`

##### Summary

The inventory-cycle-end packet indicates that an inventory round has ended on an 
antenna.

<a name='F-CSLibrary-Constants-RFID_PACKET_TYPE-INVENTORY_CYCLE_END_DIAGS'></a>
### INVENTORY_CYCLE_END_DIAGS `constants`

##### Summary

The inventory-cycle-end-diagnostics packet appears at the end of an inventory round 
and contains diagnostics information related to the inventory round that has just 
completed.

<a name='F-CSLibrary-Constants-RFID_PACKET_TYPE-ISO18K6C_INVENTORY'></a>
### ISO18K6C_INVENTORY `constants`

##### Summary

The ISO 18000-6C inventory-response packet contains the data a tag backscatters 
during the tag-singulation phase. This data is generated for tag inventories as well as 
ISO 18000-6C tag-access operations (i.e. read, write, etc.). Assuming a valid CRC, 
the data contains the PC+EPC+CRC16 received during the singulation of a tag.

<a name='F-CSLibrary-Constants-RFID_PACKET_TYPE-ISO18K6C_INVENTORY_DIAGS'></a>
### ISO18K6C_INVENTORY_DIAGS `constants`

##### Summary

The ISO 18000-6C inventory-response diagnostics packet is used to convey 
diagnostics information for the tag during the ISO 18000-6C inventory.

<a name='F-CSLibrary-Constants-RFID_PACKET_TYPE-ISO18K6C_INVENTORY_ROUND_BEGIN'></a>
### ISO18K6C_INVENTORY_ROUND_BEGIN `constants`

##### Summary

The ISO 18000-6C inventory-round-begin packet indicates that an ISO 18000-6C 
inventory round has begun on an antenna.

<a name='F-CSLibrary-Constants-RFID_PACKET_TYPE-ISO18K6C_INVENTORY_ROUND_BEGIN_DIAGS'></a>
### ISO18K6C_INVENTORY_ROUND_BEGIN_DIAGS `constants`

##### Summary

The ISO 18000-6C inventory-round-begin-diagnostics packet appears at the beginning 
of an ISO 18000-6C inventory round and contains diagnostics information related to 
the inventory round that is about to commence.

<a name='F-CSLibrary-Constants-RFID_PACKET_TYPE-ISO18K6C_INVENTORY_ROUND_END'></a>
### ISO18K6C_INVENTORY_ROUND_END `constants`

##### Summary

The ISO 18000-6C inventory-round-end packet indicates that an ISO 18000-6C 
inventory round has ended on an antenna.

<a name='F-CSLibrary-Constants-RFID_PACKET_TYPE-ISO18K6C_INVENTORY_ROUND_END_DIAGS'></a>
### ISO18K6C_INVENTORY_ROUND_END_DIAGS `constants`

##### Summary

The ISO 18000-6C inventory-round-end-diagnostics packet appears at the end of an 
ISO 18000-6C inventory round and contains diagnostics information related to the 
inventory round that has just completed.

<a name='F-CSLibrary-Constants-RFID_PACKET_TYPE-ISO18K6C_TAG_ACCESS'></a>
### ISO18K6C_TAG_ACCESS `constants`

##### Summary

The ISO 18000-6C tag-access packet indicates the Result of the tag-access command 
upon the ISO 18000-6C tag. Valid tag access commands are as follows: 
Read, Write, Kill, Lock, Erase

<a name='F-CSLibrary-Constants-RFID_PACKET_TYPE-NONCRITICAL_FAULT'></a>
### NONCRITICAL_FAULT `constants`

##### Summary

The packet types for the status packets.

<a name='F-CSLibrary-Constants-RFID_PACKET_TYPE-RES0'></a>
### RES0 `constants`

##### Summary

Reserved

<a name='F-CSLibrary-Constants-RFID_PACKET_TYPE-RES1'></a>
### RES1 `constants`

##### Summary

Reserved

<a name='F-CSLibrary-Constants-RFID_PACKET_TYPE-RES2'></a>
### RES2 `constants`

##### Summary

Reserved

<a name='F-CSLibrary-Constants-RFID_PACKET_TYPE-RES3'></a>
### RES3 `constants`

##### Summary

Reserved

<a name='F-CSLibrary-Constants-RFID_PACKET_TYPE-RES4'></a>
### RES4 `constants`

##### Summary

Reserved

<a name='T-CSLibrary-Constants-RFState'></a>
## RFState `type`

##### Namespace

CSLibrary.Constants

##### Summary

Reader Operation State

<a name='F-CSLibrary-Constants-RFState-ABORT'></a>
### ABORT `constants`

##### Summary

Operation is stopping, please wait until back to Idle mode.

<a name='F-CSLibrary-Constants-RFState-ANT_CYCLE_END'></a>
### ANT_CYCLE_END `constants`

##### Summary

Anntenna Cycle End Notification.

<a name='F-CSLibrary-Constants-RFState-BUFFER_FULL'></a>
### BUFFER_FULL `constants`

##### Summary

Receive Buffer Full

<a name='F-CSLibrary-Constants-RFState-BUSY'></a>
### BUSY `constants`

##### Summary

Operation is running, please stop it before do any other operation.

<a name='F-CSLibrary-Constants-RFState-CARRIER_INFO'></a>
### CARRIER_INFO `constants`

##### Summary

Received Carrier Info

<a name='F-CSLibrary-Constants-RFState-CH_BUSY'></a>
### CH_BUSY `constants`

##### Summary

Channel hit

<a name='F-CSLibrary-Constants-RFState-CH_CLEAR'></a>
### CH_CLEAR `constants`

##### Summary

Channel clear

<a name='F-CSLibrary-Constants-RFState-DISCONNECTED'></a>
### DISCONNECTED `constants`

##### Summary

Reader is disconnected in idle mode.

<a name='F-CSLibrary-Constants-RFState-EAS_ALARM'></a>
### EAS_ALARM `constants`

##### Summary

EAS Alert

<a name='F-CSLibrary-Constants-RFState-ENGTESTRESULT'></a>
### ENGTESTRESULT `constants`

<a name='F-CSLibrary-Constants-RFState-ERROR'></a>
### ERROR `constants`

##### Summary

Reader is in error stage, please restart reader.

<a name='F-CSLibrary-Constants-RFState-IDLE'></a>
### IDLE `constants`

##### Summary

Idle mode, ready for any operation.

<a name='F-CSLibrary-Constants-RFState-INVENTORY_CYCLE_BEGIN'></a>
### INVENTORY_CYCLE_BEGIN `constants`

##### Summary

Inventory Cycle Begin

<a name='F-CSLibrary-Constants-RFState-INVENTORY_CYCLE_END_DIAGNOSTICS'></a>
### INVENTORY_CYCLE_END_DIAGNOSTICS `constants`

##### Summary

Inventory cycle end diagnostics

<a name='F-CSLibrary-Constants-RFState-INVENTORY_MAC_ERROR'></a>
### INVENTORY_MAC_ERROR `constants`

##### Summary

Inventory MAC Error

<a name='F-CSLibrary-Constants-RFState-INVENTORY_ROUND_BEGIN'></a>
### INVENTORY_ROUND_BEGIN `constants`

##### Summary

Inventory round begin

<a name='F-CSLibrary-Constants-RFState-INVENTORY_ROUND_BEGIN_DIAGNOSTICS'></a>
### INVENTORY_ROUND_BEGIN_DIAGNOSTICS `constants`

##### Summary

Inventory round begin diagnostics

<a name='F-CSLibrary-Constants-RFState-INVENTORY_ROUND_END'></a>
### INVENTORY_ROUND_END `constants`

##### Summary

Inventory round end

<a name='F-CSLibrary-Constants-RFState-INVENTORY_ROUND_END_DIAGNOSTICS'></a>
### INVENTORY_ROUND_END_DIAGNOSTICS `constants`

##### Summary

Inventory round end diagnostics

<a name='F-CSLibrary-Constants-RFState-RESET'></a>
### RESET `constants`

##### Summary

Reader is required to reset in inventory mode.

<a name='F-CSLibrary-Constants-RFState-SHUTDOWN'></a>
### SHUTDOWN `constants`

##### Summary

buffer full

<a name='F-CSLibrary-Constants-RFState-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown operation

<a name='T-CSLibrary-Structures-RadioInformation'></a>
## RadioInformation `type`

##### Namespace

CSLibrary.Structures

##### Summary

When  detecting  the  attached  RFID  radio  modules,  the  structures  for  retrieving 
the information for the attached RFID radio modules are as follows:

<a name='M-CSLibrary-Structures-RadioInformation-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-RadioInformation-cookie'></a>
### cookie `constants`

##### Summary

A unique cookie for the particular radio.  This cookie 
will be provided to the RFID_RadioOpen function 
when the application wishes to take control of the 
radio.  Note that cookies are guaranteed to only be 
valid for as long as (1) the corresponding RFID radio 
module is attached to the host system, (2) the 
corresponding RFID radio module is not power cycled, 
(3) the corresponding RFID radio module's MAC 
firmware is not reset, and (4) the RFID Reader Library 
is not shut down.

<a name='F-CSLibrary-Structures-RadioInformation-driverVersion'></a>
### driverVersion `constants`

##### Summary

The version information for the bus driver that is used 
to communicate with the radio module.

<a name='F-CSLibrary-Structures-RadioInformation-idLength'></a>
### idLength `constants`

##### Summary

The length, in bytes, of the radio's unique ID (aka, 
serial number) including the null terminator.

<a name='F-CSLibrary-Structures-RadioInformation-length'></a>
### length `constants`

##### Summary

Structure size

<a name='F-CSLibrary-Structures-RadioInformation-uniqueId'></a>
### uniqueId `constants`

##### Summary

A pointer to an array of bytes that contains the unique 
ID (aka, serial number) for the radio represented as a 
null terminated ASCII character string.

<a name='T-CSLibrary-Structures-RadioLinkProfile'></a>
## RadioLinkProfile `type`

##### Namespace

CSLibrary.Structures

##### Summary

RadioLinkProfile Structure

<a name='M-CSLibrary-Structures-RadioLinkProfile-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-RadioLinkProfile-denseReaderMode'></a>
### denseReaderMode `constants`

##### Summary

Indicates if this is a dense-reader-mode (DRM) profile.  
A non-zero value indicates that the profile is a DRM 
profile.  A zero value indicates that the profile is not a 
DRM profile.

<a name='F-CSLibrary-Structures-RadioLinkProfile-enabled'></a>
### enabled `constants`

##### Summary

Indicates if the profile is the active one.  A non-zero 
value indicates that the profile is active.  A zero value 
indicates that the profile is inactive.

<a name='F-CSLibrary-Structures-RadioLinkProfile-length_'></a>
### length_ `constants`

##### Summary

Structure size

<a name='F-CSLibrary-Structures-RadioLinkProfile-narrowbandRssiSamples'></a>
### narrowbandRssiSamples `constants`

##### Summary

Number of samples over which the narrow band RSSI 
will be averaged.

<a name='F-CSLibrary-Structures-RadioLinkProfile-profileConfig_'></a>
### profileConfig_ `constants`

##### Summary

The link profile configuration information.  This is a 
discriminated union, with profileProtocol as the 
discriminator (i.e., determines which structure within 
the union is used).  For example, if 
profileProtocol is 
RFID_RADIO_PROTOCOL_ISO18K6C, the iso18K6C 
field is used.

<a name='F-CSLibrary-Structures-RadioLinkProfile-profileId'></a>
### profileId `constants`

##### Summary

The identifier used for the link profile.  This field 
combined with profileVersion provides a unique 
identifier for the link profile.

<a name='F-CSLibrary-Structures-RadioLinkProfile-profileProtocol_'></a>
### profileProtocol_ `constants`

##### Summary

The tag protocol for which this link profile has been 
configured.  The value of this field determines which of 
the structures within the profileConfig contains the 
link profile configuration information.

<a name='F-CSLibrary-Structures-RadioLinkProfile-profileVersion'></a>
### profileVersion `constants`

##### Summary

The version of the link profile.  This field combined with 
profileId provides a unique identifier for the link 
profile.

<a name='F-CSLibrary-Structures-RadioLinkProfile-realtimeNarrowbandRssiSamples'></a>
### realtimeNarrowbandRssiSamples `constants`

##### Summary

Reserved for future use.

<a name='F-CSLibrary-Structures-RadioLinkProfile-realtimeRssiEnabled'></a>
### realtimeRssiEnabled `constants`

##### Summary

Reserved for future use.

<a name='F-CSLibrary-Structures-RadioLinkProfile-realtimeWidebandRssiSamples'></a>
### realtimeWidebandRssiSamples `constants`

##### Summary

Reserved for future use.

<a name='F-CSLibrary-Structures-RadioLinkProfile-widebandRssiSamples'></a>
### widebandRssiSamples `constants`

##### Summary

Number of samples over which the wide band Receive 
Signal Strength Indication (RSSI) will be averaged.

<a name='P-CSLibrary-Structures-RadioLinkProfile-length'></a>
### length `property`

##### Summary

Structure size

<a name='P-CSLibrary-Structures-RadioLinkProfile-profileConfig'></a>
### profileConfig `property`

##### Summary

The link profile configuration information.  This is a 
discriminated union, with profileProtocol as the 
discriminator (i.e., determines which structure within 
the union is used).  For example, if 
profileProtocol is 
RFID_RADIO_PROTOCOL_ISO18K6C, the iso18K6C 
field is used.///

<a name='P-CSLibrary-Structures-RadioLinkProfile-profileProtocol'></a>
### profileProtocol `property`

##### Summary

The tag protocol for which this link profile has been 
configured.  The value of this field determines which of 
the structures within the profileConfig contains the 
link profile configuration information.

<a name='T-CSLibrary-Structures-RadioLinkProfileConfig'></a>
## RadioLinkProfileConfig `type`

##### Namespace

CSLibrary.Structures

##### Summary



<a name='M-CSLibrary-Structures-RadioLinkProfileConfig-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-RadioLinkProfileConfig-data01Difference'></a>
### data01Difference `constants`

##### Summary

The difference, in Tari, between an data zero and a data one.

<a name='F-CSLibrary-Structures-RadioLinkProfileConfig-divideRatio'></a>
### divideRatio `constants`

##### Summary

The tag-to-interrogator divide ratio that is sent as part of the 
Query command.

<a name='F-CSLibrary-Structures-RadioLinkProfileConfig-millerNumber'></a>
### millerNumber `constants`

##### Summary

The miller number (i.e., cycles per symbol) that is sent as 
part of the Query command.

<a name='F-CSLibrary-Structures-RadioLinkProfileConfig-minT2Delay'></a>
### minT2Delay `constants`

##### Summary

The minimum ISO 18000-6C T2 time, in 
microseconds, after receiving tag responses 
before a radio may transmit again.

<a name='F-CSLibrary-Structures-RadioLinkProfileConfig-modulationType'></a>
### modulationType `constants`

##### Summary

The modulation type that is used by the profile.

<a name='F-CSLibrary-Structures-RadioLinkProfileConfig-pulseWidth'></a>
### pulseWidth `constants`

##### Summary

The duration of the low-going portion of the interrogator-to-
tag PIE symbol (i.e., pulse width) in nanoseconds.

<a name='F-CSLibrary-Structures-RadioLinkProfileConfig-rtCalibration'></a>
### rtCalibration `constants`

##### Summary

The width of the interrogator (i.e., radio) to tag calibration 
(i.e., RTCal) in nanoseconds.

<a name='F-CSLibrary-Structures-RadioLinkProfileConfig-rxDelay'></a>
### rxDelay `constants`

##### Summary

The amount of time, measured in 48MHz clock 
cycles, after transmitting that the radio module 
will wait before attempting to receive 
backscattered signals from tags.

<a name='F-CSLibrary-Structures-RadioLinkProfileConfig-tari'></a>
### tari `constants`

##### Summary

The duration of the Tari in nanoseconds.

<a name='F-CSLibrary-Structures-RadioLinkProfileConfig-trCalibration'></a>
### trCalibration `constants`

##### Summary

The width of the tag to interrogator calibration (i.e., TRCal) in 
nanoseconds.

<a name='F-CSLibrary-Structures-RadioLinkProfileConfig-trLinkFrequency'></a>
### trLinkFrequency `constants`

##### Summary

The tag-to-interrogator link frequency in Hz.  Note that this is 
not the link data-rate.  The link data rate can be computed by 
dividing this value by 2millerNumber.

<a name='F-CSLibrary-Structures-RadioLinkProfileConfig-txPropagationDelay'></a>
### txPropagationDelay `constants`

##### Summary

The number of microseconds it takes for a 
signal to propagate through the radio's transmit 
chain.

<a name='F-CSLibrary-Structures-RadioLinkProfileConfig-varT2Delay'></a>
### varT2Delay `constants`

##### Summary

The delay, in microseconds, that is inserted to ensure 
meeting the minimum ISO 18000-6C T2 timing.

<a name='T-CSLibrary-Constants-RadioOperationMode'></a>
## RadioOperationMode `type`

##### Namespace

CSLibrary.Constants

##### Summary

A radio module may operate either in continuous or non-continuous mode.  In 
continuous mode, when a tag-protocol-operation cycle (i.e., one iteration through 
all enabled antenna ports) has completed, the radio module will begin a new tag-
protocol-operation cycle with the first enabled antenna port and will continue to 
do so until the operation is explicitly cancelled by the application.  In non-
continuous mode, only a single tag-protocol-operation cycle is executed upon the 
radio module.

<a name='F-CSLibrary-Constants-RadioOperationMode-CONTINUOUS'></a>
### CONTINUOUS `constants`

##### Summary

Continuous operation

<a name='F-CSLibrary-Constants-RadioOperationMode-NONCONTINUOUS'></a>
### NONCONTINUOUS `constants`

##### Summary

Non-continuous

<a name='F-CSLibrary-Constants-RadioOperationMode-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown

<a name='T-CSLibrary-Constants-RadioPowerState'></a>
## RadioPowerState `type`

##### Namespace

CSLibrary.Constants

##### Summary

Based upon the usage scenario, an application is given the flexibility to place the 
radio module into specific power states.  A radio module that is in the low-power 
state will remain so until either a tag-protocol operation (e.g., 
TagInventory, etc.) is executed on the radio module or until it is 
explicitly instructed to leave low-power state.  Note that if an RFID radio module 
is brought out of low-power state by the execution of a tag-protocol operation, it 
will not automatically return to low-power state. 
Note  that  the  radio-module  power  state  should  not  be  confused  with  the  per-
antenna RF power-level

<a name='F-CSLibrary-Constants-RadioPowerState-FULL'></a>
### FULL `constants`

##### Summary

Full power mode

<a name='F-CSLibrary-Constants-RadioPowerState-STANDBY'></a>
### STANDBY `constants`

##### Summary

Standby mode

<a name='F-CSLibrary-Constants-RadioPowerState-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown

<a name='T-CSLibrary-Constants-RadioProtocol'></a>
## RadioProtocol `type`

##### Namespace

CSLibrary.Constants

##### Summary

The tag protocol for which this link profile has been 
configured.  The value of this field determines which of 
the structures within the profileConfig contains the 
link profile configuration information.

<a name='F-CSLibrary-Constants-RadioProtocol-ISO18K6C'></a>
### ISO18K6C `constants`

##### Summary

ISO 18000-6C

<a name='F-CSLibrary-Constants-RadioProtocol-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown

<a name='T-CSLibrary-Structures-Read2BandsCmdParms'></a>
## Read2BandsCmdParms `type`

##### Namespace

CSLibrary.Structures

<a name='M-CSLibrary-Structures-Read2BandsCmdParms-#ctor-System-Boolean-'></a>
### #ctor(initial) `constructor`

##### Summary

Initial Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| initial | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') |  |

<a name='F-CSLibrary-Structures-Read2BandsCmdParms-bank1'></a>
### bank1 `constants`

##### Summary

The memory bank from which to read.  Valid values are: 
MemoryBank.RESERVED 
MemoryBank.EPC  
MemoryBank.TID 
MemoryBank.USER

<a name='F-CSLibrary-Structures-Read2BandsCmdParms-bank2'></a>
### bank2 `constants`

##### Summary

The memory bank from which to read.  Valid values are: 
MemoryBank.RESERVED 
MemoryBank.EPC  
MemoryBank.TID 
MemoryBank.USER

<a name='F-CSLibrary-Structures-Read2BandsCmdParms-count1'></a>
### count1 `constants`

##### Summary

The number of 16-bit words to read.  If this value is zero and 
bank is MemoryBank.EPC, the read will return the 
contents of the tag's EPC memory starting at the 16-bit word 
specified by offset through the end of the EPC.  If this value is 
zero and bank is not MemoryBank.EPC, the read 
will return, for the tag's chosen memory bank, data starting from 
the 16-bit word specified by offset to the end of the memory 
bank.  If this value is non-zero, it must be in the range 1 to 255, 
inclusive.

<a name='F-CSLibrary-Structures-Read2BandsCmdParms-count2'></a>
### count2 `constants`

##### Summary

The number of 16-bit words to read.  If this value is zero and 
bank is MemoryBank.EPC, the read will return the 
contents of the tag's EPC memory starting at the 16-bit word 
specified by offset through the end of the EPC.  If this value is 
zero and bank is not MemoryBank.EPC, the read 
will return, for the tag's chosen memory bank, data starting from 
the 16-bit word specified by offset to the end of the memory 
bank.  If this value is non-zero, it must be in the range 1 to 255, 
inclusive.

<a name='F-CSLibrary-Structures-Read2BandsCmdParms-length'></a>
### length `constants`

##### Summary

The length of this structure.

<a name='F-CSLibrary-Structures-Read2BandsCmdParms-offset1'></a>
### offset1 `constants`

##### Summary

The offset of the first 16-bit word, where zero is the first 16-bit 
word in the memory bank, to read from the specified memory 
bank.

<a name='F-CSLibrary-Structures-Read2BandsCmdParms-offset2'></a>
### offset2 `constants`

##### Summary

The offset of the first 16-bit word, where zero is the first 16-bit 
word in the memory bank, to read from the specified memory 
bank.

<a name='T-CSLibrary-Structures-ReadCmdParms'></a>
## ReadCmdParms `type`

##### Namespace

CSLibrary.Structures

<a name='M-CSLibrary-Structures-ReadCmdParms-#ctor-System-Boolean-'></a>
### #ctor(initial) `constructor`

##### Summary

Initial Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| initial | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') |  |

<a name='F-CSLibrary-Structures-ReadCmdParms-bank'></a>
### bank `constants`

##### Summary

The memory bank from which to read.  Valid values are: 
MemoryBank.RESERVED 
MemoryBank.EPC  
MemoryBank.TID 
MemoryBank.USER

<a name='F-CSLibrary-Structures-ReadCmdParms-count'></a>
### count `constants`

##### Summary

The number of 16-bit words to read.  If this value is zero and 
bank is MemoryBank.EPC, the read will return the 
contents of the tag's EPC memory starting at the 16-bit word 
specified by offset through the end of the EPC.  If this value is 
zero and bank is not MemoryBank.EPC, the read 
will return, for the tag's chosen memory bank, data starting from 
the 16-bit word specified by offset to the end of the memory 
bank.  If this value is non-zero, it must be in the range 1 to 255, 
inclusive.

<a name='F-CSLibrary-Structures-ReadCmdParms-length'></a>
### length `constants`

##### Summary

The length of this structure.

<a name='F-CSLibrary-Structures-ReadCmdParms-offset'></a>
### offset `constants`

##### Summary

The offset of the first 16-bit word, where zero is the first 16-bit 
word in the memory bank, to read from the specified memory 
bank.

<a name='T-CSLibrary-Structures-ReadParms'></a>
## ReadParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Reading tag data should not be confused with performing an inventory.  
Whereas an inventory is restricted to returning all or part of the tag's EPC data, a 
read operation can be used to read one or more 16-bit words from any of a tag's 
memory banks.  While a read may be used to retrieve a set of tag EPC data, if 
the EPC is the only desired data, then at the low-level tag access, performing an 
inventory operation is more efficient.  The data returned from the tag read will 
adhere to the format specified in [REC].

<a name='M-CSLibrary-Structures-ReadParms-#ctor-System-Boolean-'></a>
### #ctor(initial) `constructor`

##### Summary

Initial Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| initial | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') |  |

<a name='F-CSLibrary-Structures-ReadParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no 
access password.

<a name='F-CSLibrary-Structures-ReadParms-common'></a>
### common `constants`

##### Summary

The common tag-protocol operation parameters.

<a name='F-CSLibrary-Structures-ReadParms-length'></a>
### length `constants`

##### Summary

ReadParms length

<a name='F-CSLibrary-Structures-ReadParms-readCmdParms'></a>
### readCmdParms `constants`

##### Summary



<a name='T-CSLibrary-Structures-ReadProtectParms'></a>
## ReadProtectParms `type`

##### Namespace

CSLibrary.Structures

<a name='F-CSLibrary-Structures-ReadProtectParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no access 
password.

<a name='F-CSLibrary-Structures-ReadProtectParms-common'></a>
### common `constants`

##### Summary

The common tag-protocol operation parameters.

<a name='F-CSLibrary-Structures-ReadProtectParms-length'></a>
### length `constants`

##### Summary

Structure size

<a name='T-CSLibrary-Net-RecvOperation'></a>
## RecvOperation `type`

##### Namespace

CSLibrary.Net

##### Summary

Current Packet Recevice mode

<a name='F-CSLibrary-Net-RecvOperation-ASSIGN'></a>
### ASSIGN `constants`

##### Summary

Assigment operation

<a name='F-CSLibrary-Net-RecvOperation-CLOSED'></a>
### CLOSED `constants`

##### Summary



<a name='F-CSLibrary-Net-RecvOperation-IDLE'></a>
### IDLE `constants`

##### Summary

Idle

<a name='F-CSLibrary-Net-RecvOperation-SEARCH'></a>
### SEARCH `constants`

##### Summary

Searching device

<a name='F-CSLibrary-Net-RecvOperation-UPDATE'></a>
### UPDATE `constants`

##### Summary

Update in progress

<a name='T-CSLibrary-Constants-RegionCode'></a>
## RegionCode `type`

##### Namespace

CSLibrary.Constants

##### Summary

Region Profile

<a name='F-CSLibrary-Constants-RegionCode-AR'></a>
### AR `constants`

##### Summary

Argentina

<a name='F-CSLibrary-Constants-RegionCode-AU'></a>
### AU `constants`

##### Summary

Australia

<a name='F-CSLibrary-Constants-RegionCode-BR1'></a>
### BR1 `constants`

##### Summary

Brazil

<a name='F-CSLibrary-Constants-RegionCode-BR2'></a>
### BR2 `constants`

##### Summary

Brazil

<a name='F-CSLibrary-Constants-RegionCode-BR3'></a>
### BR3 `constants`

##### Summary

Brazil

<a name='F-CSLibrary-Constants-RegionCode-BR4'></a>
### BR4 `constants`

##### Summary

Brazil

<a name='F-CSLibrary-Constants-RegionCode-BR5'></a>
### BR5 `constants`

##### Summary

Brazil

<a name='F-CSLibrary-Constants-RegionCode-CL'></a>
### CL `constants`

<a name='F-CSLibrary-Constants-RegionCode-CN'></a>
### CN `constants`

##### Summary

China all frequency

<a name='F-CSLibrary-Constants-RegionCode-CO'></a>
### CO `constants`

##### Summary

Colombia

<a name='F-CSLibrary-Constants-RegionCode-CR'></a>
### CR `constants`

##### Summary

Costa Rica??? ????????

<a name='F-CSLibrary-Constants-RegionCode-CURRENT'></a>
### CURRENT `constants`

##### Summary

Current Country

<a name='F-CSLibrary-Constants-RegionCode-DO'></a>
### DO `constants`

##### Summary

Dominican Republic

<a name='F-CSLibrary-Constants-RegionCode-ETSI'></a>
### ETSI `constants`

##### Summary

Europe

<a name='F-CSLibrary-Constants-RegionCode-ETSIUPPERBAND'></a>
### ETSIUPPERBAND `constants`

##### Summary

ETSI Upper Band

<a name='F-CSLibrary-Constants-RegionCode-FCC'></a>
### FCC `constants`

##### Summary

USA

<a name='F-CSLibrary-Constants-RegionCode-G800'></a>
### G800 `constants`

##### Summary

G800 same as India

<a name='F-CSLibrary-Constants-RegionCode-HK'></a>
### HK `constants`

##### Summary

Hong Kong

<a name='F-CSLibrary-Constants-RegionCode-HK50'></a>
### HK50 `constants`

##### Summary

Hong Kong (50 Channels)

<a name='F-CSLibrary-Constants-RegionCode-HK8'></a>
### HK8 `constants`

##### Summary

Hong Kong (8 Channels)

<a name='F-CSLibrary-Constants-RegionCode-ID'></a>
### ID `constants`

##### Summary

Indonesia

<a name='F-CSLibrary-Constants-RegionCode-IN'></a>
### IN `constants`

##### Summary

India

<a name='F-CSLibrary-Constants-RegionCode-JE'></a>
### JE `constants`

##### Summary

Israel

<a name='F-CSLibrary-Constants-RegionCode-JP'></a>
### JP `constants`

##### Summary

Japan

<a name='F-CSLibrary-Constants-RegionCode-KR'></a>
### KR `constants`

##### Summary

Korea

<a name='F-CSLibrary-Constants-RegionCode-LH'></a>
### LH `constants`

##### Summary

LH

<a name='F-CSLibrary-Constants-RegionCode-LH1'></a>
### LH1 `constants`

##### Summary

LH

<a name='F-CSLibrary-Constants-RegionCode-LH2'></a>
### LH2 `constants`

##### Summary

LH

<a name='F-CSLibrary-Constants-RegionCode-MX'></a>
### MX `constants`

##### Summary

Mexico

<a name='F-CSLibrary-Constants-RegionCode-MY'></a>
### MY `constants`

##### Summary

Malaysia

<a name='F-CSLibrary-Constants-RegionCode-NZ'></a>
### NZ `constants`

##### Summary

New Zealand

<a name='F-CSLibrary-Constants-RegionCode-PA'></a>
### PA `constants`

##### Summary

Panama

<a name='F-CSLibrary-Constants-RegionCode-PE'></a>
### PE `constants`

##### Summary

Peru

<a name='F-CSLibrary-Constants-RegionCode-PH'></a>
### PH `constants`

##### Summary

Philippine

<a name='F-CSLibrary-Constants-RegionCode-SAHOPPING'></a>
### SAHOPPING `constants`

##### Summary

SA Hopping

<a name='F-CSLibrary-Constants-RegionCode-SG'></a>
### SG `constants`

##### Summary

Singapore

<a name='F-CSLibrary-Constants-RegionCode-TH'></a>
### TH `constants`

##### Summary

Thailand

<a name='F-CSLibrary-Constants-RegionCode-TW'></a>
### TW `constants`

##### Summary

Taiwan

<a name='F-CSLibrary-Constants-RegionCode-UH1'></a>
### UH1 `constants`

##### Summary

UH1

<a name='F-CSLibrary-Constants-RegionCode-UH2'></a>
### UH2 `constants`

##### Summary

UH2

<a name='F-CSLibrary-Constants-RegionCode-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknow Country

<a name='F-CSLibrary-Constants-RegionCode-UY'></a>
### UY `constants`

##### Summary

Uruguay

<a name='F-CSLibrary-Constants-RegionCode-VE'></a>
### VE `constants`

##### Summary

Venezuela

<a name='F-CSLibrary-Constants-RegionCode-VI'></a>
### VI `constants`

##### Summary

Vietnam

<a name='F-CSLibrary-Constants-RegionCode-ZA'></a>
### ZA `constants`

##### Summary

South Africa

<a name='T-CSLibrary-Constants-ResponseMode'></a>
## ResponseMode `type`

##### Namespace

CSLibrary.Constants

##### Summary

The requested data-reporting mode for 
the data type specified by 
responseType.

<a name='F-CSLibrary-Constants-ResponseMode-COMPACT'></a>
### COMPACT `constants`

##### Summary

The response data is limited to provide the application with the 
pertinent tag-access operation data, but minimize the amount of MAC-to-
host communication overhead.

<a name='F-CSLibrary-Constants-ResponseMode-EXTENDED'></a>
### EXTENDED `constants`

##### Summary

The response data builds on the normal mode by providing 
additional diagnostics and statistical information.

<a name='F-CSLibrary-Constants-ResponseMode-NORMAL'></a>
### NORMAL `constants`

##### Summary

The response data builds on the compact mode to provide the 
 application with status and contextual information to give additional finer-
grained feedback such as the beginning of inventory cycles, etc.

<a name='F-CSLibrary-Constants-ResponseMode-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown Mode

<a name='T-CSLibrary-Constants-ResponseType'></a>
## ResponseType `type`

##### Namespace

CSLibrary.Constants

##### Summary

The type of data that will have its 
mode set to the mode specified by 
responseMode.  For version 1.1 of the 
RFID Reader Library, the only valid 
value is RFID_RESPONSE_TYPE_DATA.

<a name='F-CSLibrary-Constants-ResponseType-DATA'></a>
### DATA `constants`

##### Summary

an application can control the mode of data reporting in response to 
a tag-access operation (i.e., inventory, read, etc.).

<a name='F-CSLibrary-Constants-ResponseType-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown mode

<a name='T-CSLibrary-Constants-Result'></a>
## Result `type`

##### Namespace

CSLibrary.Constants

##### Summary

function Result value definitions

<a name='T-CSLibrary-Net-Result'></a>
## Result `type`

##### Namespace

CSLibrary.Net

##### Summary

Assignment Result

<a name='F-CSLibrary-Constants-Result-ALREADY_OPEN'></a>
### ALREADY_OPEN `constants`

##### Summary

Attempted to open a radio that is already open

<a name='F-CSLibrary-Constants-Result-BUFFER_TOO_SMALL'></a>
### BUFFER_TOO_SMALL `constants`

##### Summary

Buffer supplied is too small

<a name='F-CSLibrary-Constants-Result-CHECK_STATUS_FAIL'></a>
### CHECK_STATUS_FAIL `constants`

##### Summary

Check Status fail

<a name='F-CSLibrary-Constants-Result-CURRENTLY_NOT_ALLOWED'></a>
### CURRENTLY_NOT_ALLOWED `constants`

##### Summary

The RFID library function is not allowed at this time.

<a name='F-CSLibrary-Constants-Result-DEVICE_CONNECTED'></a>
### DEVICE_CONNECTED `constants`

##### Summary

Device Connected

<a name='F-CSLibrary-Constants-Result-DEVICE_NOT_SUPPORT'></a>
### DEVICE_NOT_SUPPORT `constants`

##### Summary

Device not support

<a name='F-CSLibrary-Constants-Result-DRIVER_LOAD'></a>
### DRIVER_LOAD `constants`

##### Summary

Failed to load radio bus driver

<a name='F-CSLibrary-Constants-Result-DRIVER_MISMATCH'></a>
### DRIVER_MISMATCH `constants`

##### Summary

Library cannot use version of radio bus driver present on system

<a name='F-CSLibrary-Constants-Result-EMULATION_MODE'></a>
### EMULATION_MODE `constants`

##### Summary

Operation cannot be performed while library is in emulation mode

<a name='F-CSLibrary-Constants-Result-FAILURE'></a>
### FAILURE `constants`

##### Summary

General failure

<a name='F-CSLibrary-Constants-Result-FIRMWARE_TOO_OLD'></a>
### FIRMWARE_TOO_OLD `constants`

##### Summary

Network processor firmware too old.

<a name='F-CSLibrary-Constants-Result-INVALID_ANTENNA'></a>
### INVALID_ANTENNA `constants`

##### Summary

Antenna number is invalid

<a name='F-CSLibrary-Constants-Result-INVALID_HANDLE'></a>
### INVALID_HANDLE `constants`

##### Summary

Radio handle provided is invalid

<a name='F-CSLibrary-Constants-Result-INVALID_OEM_COUNTRY_CODE'></a>
### INVALID_OEM_COUNTRY_CODE `constants`

##### Summary

OEM Country code invalid

<a name='F-CSLibrary-Constants-Result-INVALID_PARAMETER'></a>
### INVALID_PARAMETER `constants`

##### Summary

One of the parameters to the function is invalid

<a name='F-CSLibrary-Constants-Result-MAC_ERROR'></a>
### MAC_ERROR `constants`

##### Summary

MAC ERROR

<a name='F-CSLibrary-Constants-Result-MAX_RETRY_EXIT'></a>
### MAX_RETRY_EXIT `constants`

##### Summary

Tag access maximum retry error

<a name='F-CSLibrary-Constants-Result-NETWORK_LOST'></a>
### NETWORK_LOST `constants`

##### Summary

Network lost

<a name='F-CSLibrary-Constants-Result-NETWORK_RESET'></a>
### NETWORK_RESET `constants`

##### Summary

Network reset

<a name='F-CSLibrary-Constants-Result-NONVOLATILE_INIT_FAILED'></a>
### NONVOLATILE_INIT_FAILED `constants`

##### Summary

The MAC firmware encountered an error while initiating the nonvolatile
memory update.  The MAC firmware will return to its normal idle state
without resetting the radio module.

<a name='F-CSLibrary-Constants-Result-NONVOLATILE_OUT_OF_BOUNDS'></a>
### NONVOLATILE_OUT_OF_BOUNDS `constants`

##### Summary

An attempt was made to write data to an address that is not in the
valid range of radio module nonvolatile memory addresses.

<a name='F-CSLibrary-Constants-Result-NONVOLATILE_WRITE_FAILED'></a>
### NONVOLATILE_WRITE_FAILED `constants`

##### Summary

The MAC firmware encountered an error while trying to write to the
radio module's nonvolatile memory region.

<a name='F-CSLibrary-Constants-Result-NOT_INITIALIZED'></a>
### NOT_INITIALIZED `constants`

##### Summary

Library has not been successfully initialized

<a name='F-CSLibrary-Constants-Result-NOT_SUPPORTED'></a>
### NOT_SUPPORTED `constants`

##### Summary

Function not supported

<a name='F-CSLibrary-Constants-Result-NO_SUCH_RADIO'></a>
### NO_SUCH_RADIO `constants`

##### Summary

Attempted to open a non-existent radio

<a name='F-CSLibrary-Constants-Result-NO_TAG_FOUND'></a>
### NO_TAG_FOUND `constants`

##### Summary

No Tag Found

<a name='F-CSLibrary-Constants-Result-OK'></a>
### OK `constants`

##### Summary

Success

<a name='F-CSLibrary-Constants-Result-OPERATION_CANCELLED'></a>
### OPERATION_CANCELLED `constants`

##### Summary

Op cancelled by cancel op func, close radio, or library shutdown

<a name='F-CSLibrary-Constants-Result-OUT_OF_MEMORY'></a>
### OUT_OF_MEMORY `constants`

##### Summary

Library encountered an error allocating memory

<a name='F-CSLibrary-Constants-Result-POWER_DOWN_FAIL'></a>
### POWER_DOWN_FAIL `constants`

##### Summary

RFID Power down failed

<a name='F-CSLibrary-Constants-Result-POWER_UP_FAIL'></a>
### POWER_UP_FAIL `constants`

##### Summary

RFID Power up failed

<a name='F-CSLibrary-Constants-Result-PREALLOCATED_BUFFER_FULL'></a>
### PREALLOCATED_BUFFER_FULL `constants`

##### Summary

Pre-allocated buffer is full

<a name='F-CSLibrary-Constants-Result-RADIO_BUSY'></a>
### RADIO_BUSY `constants`

##### Summary

The operation cannot be performed because the radio is currently busy

<a name='F-CSLibrary-Constants-Result-RADIO_FAILURE'></a>
### RADIO_FAILURE `constants`

##### Summary

The underlying radio module encountered an error

<a name='F-CSLibrary-Constants-Result-RADIO_NOT_PRESENT'></a>
### RADIO_NOT_PRESENT `constants`

##### Summary

The radio has been detached from the system

<a name='F-CSLibrary-Constants-Result-RADIO_NOT_RESPONDING'></a>
### RADIO_NOT_RESPONDING `constants`

##### Summary

The radio module's MAC firmware is not responding to requests.

<a name='F-CSLibrary-Constants-Result-RECEIVE_OVERFLOW'></a>
### RECEIVE_OVERFLOW `constants`

##### Summary

The underlying transport layer detected that there was an overflow
error Resulting in one or more bytes of the incoming data being   
dropped.  The operation was aborted and all data in the pipeline was
flushed.

<a name='F-CSLibrary-Constants-Result-SYSTEM_CATCH_EXCEPTION'></a>
### SYSTEM_CATCH_EXCEPTION `constants`

##### Summary

System catch exception

<a name='F-CSLibrary-Constants-Result-THREAD_ERROR'></a>
### THREAD_ERROR `constants`

<a name='F-CSLibrary-Constants-Result-UNDER_CONSTRUCTION'></a>
### UNDER_CONSTRUCTION `constants`

##### Summary

Inventory packet header error.

<a name='F-CSLibrary-Constants-Result-UNKNOWN_OPERATION'></a>
### UNKNOWN_OPERATION `constants`

##### Summary

Unknown Operation

<a name='F-CSLibrary-Net-Result-BUILD_ASSIGN_BUFFER_FAIL'></a>
### BUILD_ASSIGN_BUFFER_FAIL `constants`

##### Summary

fail to build assign buffer internallay.

<a name='F-CSLibrary-Net-Result-DATA_NOT_FOUND'></a>
### DATA_NOT_FOUND `constants`

##### Summary

target MAC address not found in current search list, 
please try SearchDevice() first or check you network connection carefully.

<a name='F-CSLibrary-Net-Result-FAIL'></a>
### FAIL `constants`

##### Summary

Gernal fail.

<a name='F-CSLibrary-Net-Result-INVALID_PARAMETER'></a>
### INVALID_PARAMETER `constants`

##### Summary

Invalid parameter.

<a name='F-CSLibrary-Net-Result-NO_CHANGED'></a>
### NO_CHANGED `constants`

##### Summary

Assign configure is same as current configure.

<a name='F-CSLibrary-Net-Result-OK'></a>
### OK `constants`

##### Summary

No error.

<a name='F-CSLibrary-Net-Result-OPERATION_BUSY'></a>
### OPERATION_BUSY `constants`

##### Summary

Operation already in progress. Please stop operation and retry again.

<a name='F-CSLibrary-Net-Result-SEND_ASSIGN_FAIL'></a>
### SEND_ASSIGN_FAIL `constants`

##### Summary

fail to send assignment packet.

<a name='F-CSLibrary-Net-Result-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown error.

<a name='T-CSLibrary-Net-ResultArgs'></a>
## ResultArgs `type`

##### Namespace

CSLibrary.Net

##### Summary

Result Argument

<a name='M-CSLibrary-Net-ResultArgs-#ctor-CSLibrary-Net-AssignResult-'></a>
### #ctor(Result) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| Result | [CSLibrary.Net.AssignResult](#T-CSLibrary-Net-AssignResult 'CSLibrary.Net.AssignResult') |  |

<a name='P-CSLibrary-Net-ResultArgs-Result'></a>
### Result `property`

##### Summary

Result

<a name='T-CSLibrary-Structures-S_DATA'></a>
## S_DATA `type`

##### Namespace

CSLibrary.Structures

##### Summary

Custom Data Structure

<a name='M-CSLibrary-Structures-S_DATA-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='M-CSLibrary-Structures-S_DATA-#ctor-System-String-'></a>
### #ctor(src) `constructor`

##### Summary

Custom constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| src | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | data in string format |

<a name='M-CSLibrary-Structures-S_DATA-#ctor-System-Byte[]-'></a>
### #ctor(src) `constructor`

##### Summary

Custom constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| src | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | data in byte array format |

<a name='M-CSLibrary-Structures-S_DATA-#ctor-System-UInt16[]-'></a>
### #ctor(src) `constructor`

##### Summary

Custom constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| src | [System.UInt16[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16[] 'System.UInt16[]') | data in ushort array format |

<a name='M-CSLibrary-Structures-S_DATA-CompareTo-System-Object-'></a>
### CompareTo(item) `method`

##### Summary

Compare Data
if equal return 0

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| item | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') |  |

<a name='M-CSLibrary-Structures-S_DATA-GetLength'></a>
### GetLength() `method`

##### Summary

Get Byte Data Length.

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_DATA-ToBytes'></a>
### ToBytes() `method`

##### Summary

Convert to byte array

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_DATA-ToShorts'></a>
### ToShorts() `method`

##### Summary

Convert to short array

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_DATA-ToString'></a>
### ToString() `method`

##### Summary

Convert to HexString

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_DATA-ToUshorts'></a>
### ToUshorts() `method`

##### Summary

Convert to ushort array

##### Returns



##### Parameters

This method has no parameters.

<a name='T-CSLibrary-Structures-S_EPC'></a>
## S_EPC `type`

##### Namespace

CSLibrary.Structures

##### Summary

Electronic Product Code

<a name='M-CSLibrary-Structures-S_EPC-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='M-CSLibrary-Structures-S_EPC-#ctor-System-String-'></a>
### #ctor(epc) `constructor`

##### Summary

Custom constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| epc | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | epc in string format, must be smaller than or equal to 62 hex numbers |

<a name='M-CSLibrary-Structures-S_EPC-#ctor-System-UInt16[]-'></a>
### #ctor(epc) `constructor`

##### Summary

Custom constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| epc | [System.UInt16[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16[] 'System.UInt16[]') | epc in ushort array format, must be smaller than or equal to 31 |

<a name='M-CSLibrary-Structures-S_EPC-#ctor-System-UInt16[],System-Int32-'></a>
### #ctor(epc,count) `constructor`

##### Summary

Custom constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| epc | [System.UInt16[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16[] 'System.UInt16[]') | epc in ushort array format, must be smaller than or equal to 31 |
| count | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | number of ushort copy to local |

<a name='M-CSLibrary-Structures-S_EPC-#ctor-System-Byte[]-'></a>
### #ctor(epc) `constructor`

##### Summary

Custom constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| epc | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | epc in byte array format, must be smaller than or equal to 62 bytes |

<a name='M-CSLibrary-Structures-S_EPC-CompareTo-System-Object-'></a>
### CompareTo(item) `method`

##### Summary

Compare Data
if equal return 0

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| item | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') |  |

<a name='M-CSLibrary-Structures-S_EPC-GetLength'></a>
### GetLength() `method`

##### Summary

Get Data Length, Data in word format

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_EPC-ToBytes'></a>
### ToBytes() `method`

##### Summary

Convert to byte array

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_EPC-ToShorts'></a>
### ToShorts() `method`

##### Summary

Convert to short array

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_EPC-ToString'></a>
### ToString() `method`

##### Summary

Convert to HexString

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_EPC-ToUshorts'></a>
### ToUshorts() `method`

##### Summary

Convert to ushort array

##### Returns



##### Parameters

This method has no parameters.

<a name='T-CSLibrary-Structures-S_MASK'></a>
## S_MASK `type`

##### Namespace

CSLibrary.Structures

##### Summary

Custom Data Structure

<a name='M-CSLibrary-Structures-S_MASK-#ctor-System-String-'></a>
### #ctor(mask) `constructor`

##### Summary

Custom constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| mask | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | mask in string format |

<a name='M-CSLibrary-Structures-S_MASK-#ctor-System-Byte[]-'></a>
### #ctor(mask) `constructor`

##### Summary

Custom constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| mask | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | mask in byte array format |

<a name='M-CSLibrary-Structures-S_MASK-#ctor-System-UInt16[]-'></a>
### #ctor(mask) `constructor`

##### Summary

Custom constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| mask | [System.UInt16[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16[] 'System.UInt16[]') | mask in byte array format |

<a name='M-CSLibrary-Structures-S_MASK-#ctor-System-Byte[],System-UInt32-'></a>
### #ctor(mask,count) `constructor`

##### Summary

Custom constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| mask | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | mask in byte array format |
| count | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | total byte length to copy |

<a name='F-CSLibrary-Structures-S_MASK-m_mask'></a>
### m_mask `constants`

##### Summary

Protocol Control Value

<a name='P-CSLibrary-Structures-S_MASK-Length'></a>
### Length `property`

##### Summary

total byte length of mask

<a name='M-CSLibrary-Structures-S_MASK-CompareTo-System-Object-'></a>
### CompareTo(item) `method`

##### Summary

Compare Data
if equal return 0

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| item | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') |  |

<a name='M-CSLibrary-Structures-S_MASK-GetLength'></a>
### GetLength() `method`

##### Summary

Get Data Length, Data in word format

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_MASK-ToBytes'></a>
### ToBytes() `method`

##### Summary

Convert to byte array

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_MASK-ToShorts'></a>
### ToShorts() `method`

##### Summary

Convert to short array

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_MASK-ToString'></a>
### ToString() `method`

##### Summary

Convert to HexString

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_MASK-ToUshorts'></a>
### ToUshorts() `method`

##### Summary

Convert to ushort array

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_MASK-op_Implicit-CSLibrary-Structures-S_MASK-~System-String'></a>
### op_Implicit() `method`

##### Summary

Convert to string

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_MASK-op_Implicit-CSLibrary-Structures-S_MASK-~System-UInt16[]'></a>
### op_Implicit() `method`

##### Summary

Convert mask to ushort[]

##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_MASK-op_Implicit-System-UInt16[]-~CSLibrary-Structures-S_MASK'></a>
### op_Implicit() `method`

##### Summary

Convert ushort[] to mask

##### Parameters

This method has no parameters.

<a name='T-CSLibrary-Structures-S_PC'></a>
## S_PC `type`

##### Namespace

CSLibrary.Structures

##### Summary

Protocol Control(must be 2 Bytes)

<a name='M-CSLibrary-Structures-S_PC-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='M-CSLibrary-Structures-S_PC-#ctor-System-String-'></a>
### #ctor(pc) `constructor`

##### Summary

Custom constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| pc | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | pc in string format, must be 4 hex numbers |

<a name='M-CSLibrary-Structures-S_PC-#ctor-System-UInt16-'></a>
### #ctor(pc) `constructor`

##### Summary

Custom constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| pc | [System.UInt16](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16 'System.UInt16') | pc in ushort format |

<a name='P-CSLibrary-Structures-S_PC-EPCLength'></a>
### EPCLength `property`

##### Summary

Get EPC Word(16bit) Length from current PC value

<a name='P-CSLibrary-Structures-S_PC-UMI'></a>
### UMI `property`

##### Summary

User Memory Indicator, true if user memory contains data.
Notes: Not all tags support this function

<a name='P-CSLibrary-Structures-S_PC-XI'></a>
### XI `property`

##### Summary

An XPC_W1 Indicator, true if XPC_W1 is non-zero value
Notes: Not all tags support this function

<a name='M-CSLibrary-Structures-S_PC-CompareTo-System-Object-'></a>
### CompareTo(item) `method`

##### Summary

Compare Data
if equal return 0

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| item | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') |  |

<a name='M-CSLibrary-Structures-S_PC-GetLength'></a>
### GetLength() `method`

##### Summary

Get Data Length, Data in word format

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_PC-ToBytes'></a>
### ToBytes() `method`

##### Summary

Convert to byte array

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_PC-ToShorts'></a>
### ToShorts() `method`

##### Summary

Convert to short array

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_PC-ToString'></a>
### ToString() `method`

##### Summary

Convert to HexString

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_PC-ToUshorts'></a>
### ToUshorts() `method`

##### Summary

Convert to ushort array

##### Returns



##### Parameters

This method has no parameters.

<a name='T-CSLibrary-Structures-S_PWD'></a>
## S_PWD `type`

##### Namespace

CSLibrary.Structures

##### Summary

Custom Password Structure

<a name='M-CSLibrary-Structures-S_PWD-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='M-CSLibrary-Structures-S_PWD-#ctor-System-String-'></a>
### #ctor(data) `constructor`

##### Summary

Custom constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| data | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | pc in string format, must be 8 hex numbers |

<a name='M-CSLibrary-Structures-S_PWD-#ctor-System-UInt32-'></a>
### #ctor(pwd) `constructor`

##### Summary

Custom constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| pwd | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | password in Uint32 format |

<a name='P-CSLibrary-Structures-S_PWD-m_pwd'></a>
### m_pwd `property`

##### Summary

Password

<a name='M-CSLibrary-Structures-S_PWD-CompareTo-System-Object-'></a>
### CompareTo(item) `method`

##### Summary

Compare Data
if equal return 0

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| item | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') |  |

<a name='M-CSLibrary-Structures-S_PWD-GetLength'></a>
### GetLength() `method`

##### Summary

Get Data Length, Data in word format

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_PWD-ToBytes'></a>
### ToBytes() `method`

##### Summary

Convert to byte array

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_PWD-ToShorts'></a>
### ToShorts() `method`

##### Summary

Convert to short array

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_PWD-ToString'></a>
### ToString() `method`

##### Summary

Convert to HexString

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_PWD-ToUshorts'></a>
### ToUshorts() `method`

##### Summary

Convert to ushort array

##### Returns



##### Parameters

This method has no parameters.

<a name='T-CSLibrary-Structures-S_TID'></a>
## S_TID `type`

##### Namespace

CSLibrary.Structures

##### Summary

TID

<a name='M-CSLibrary-Structures-S_TID-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='M-CSLibrary-Structures-S_TID-#ctor-System-String-'></a>
### #ctor(tid) `constructor`

##### Summary

Custom constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| tid | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | pc in string format, must be 4 hex numbers |

<a name='M-CSLibrary-Structures-S_TID-#ctor-System-UInt16[]-'></a>
### #ctor(tid) `constructor`

##### Summary

Custom constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| tid | [System.UInt16[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16[] 'System.UInt16[]') | Tid in byte array format |

<a name='M-CSLibrary-Structures-S_TID-#ctor-System-UInt16[],System-Int32-'></a>
### #ctor(tid,count) `constructor`

##### Summary

Custom constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| tid | [System.UInt16[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16[] 'System.UInt16[]') | Tid in byte array format |
| count | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | number of ushort copy to local |

<a name='P-CSLibrary-Structures-S_TID-GetACID'></a>
### GetACID `property`

##### Summary

Get Allocation Class ID

<a name='P-CSLibrary-Structures-S_TID-GetEpcID'></a>
### GetEpcID `property`

##### Summary

Get EPC Mask Designer ID

<a name='P-CSLibrary-Structures-S_TID-GetIsoID'></a>
### GetIsoID `property`

##### Summary

Get ISO Mask Designer ID

<a name='M-CSLibrary-Structures-S_TID-CompareTo-System-Object-'></a>
### CompareTo(item) `method`

##### Summary

Compare Data
if equal return 0

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| item | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') |  |

<a name='M-CSLibrary-Structures-S_TID-GetLength'></a>
### GetLength() `method`

##### Summary

Get Data Length, Data in word format

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_TID-ToBytes'></a>
### ToBytes() `method`

##### Summary

Convert to byte array

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_TID-ToShorts'></a>
### ToShorts() `method`

##### Summary

Convert to short array

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_TID-ToString'></a>
### ToString() `method`

##### Summary

Convert to HexString

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_TID-ToUshorts'></a>
### ToUshorts() `method`

##### Summary

Convert to ushort array

##### Returns



##### Parameters

This method has no parameters.

<a name='T-CSLibrary-Structures-S_XPC_W1'></a>
## S_XPC_W1 `type`

##### Namespace

CSLibrary.Structures

##### Summary

X Protocol Control W1 (must be 2 Bytes)

<a name='M-CSLibrary-Structures-S_XPC_W1-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='M-CSLibrary-Structures-S_XPC_W1-#ctor-System-String-'></a>
### #ctor(pc) `constructor`

##### Summary

Custom constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| pc | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | pc in string format, must be 4 hex numbers |

<a name='M-CSLibrary-Structures-S_XPC_W1-#ctor-System-UInt16-'></a>
### #ctor(pc) `constructor`

##### Summary

Custom constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| pc | [System.UInt16](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16 'System.UInt16') | pc in ushort format |

<a name='P-CSLibrary-Structures-S_XPC_W1-XEB'></a>
### XEB `property`

##### Summary

An XPC_W2 Indicator, true if XPC_W2 is non-zero value
Notes: Not all tags support this function

<a name='M-CSLibrary-Structures-S_XPC_W1-CompareTo-System-Object-'></a>
### CompareTo(item) `method`

##### Summary

Compare Data
if equal return 0

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| item | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') |  |

<a name='M-CSLibrary-Structures-S_XPC_W1-GetLength'></a>
### GetLength() `method`

##### Summary

Get Data Length, Data in word format

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_XPC_W1-ToBytes'></a>
### ToBytes() `method`

##### Summary

Convert to byte array

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_XPC_W1-ToShorts'></a>
### ToShorts() `method`

##### Summary

Convert to short array

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_XPC_W1-ToString'></a>
### ToString() `method`

##### Summary

Convert to HexString

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_XPC_W1-ToUshorts'></a>
### ToUshorts() `method`

##### Summary

Convert to ushort array

##### Returns



##### Parameters

This method has no parameters.

<a name='T-CSLibrary-Structures-S_XPC_W2'></a>
## S_XPC_W2 `type`

##### Namespace

CSLibrary.Structures

##### Summary

X Protocol Control W2 (must be 2 Bytes)

<a name='M-CSLibrary-Structures-S_XPC_W2-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='M-CSLibrary-Structures-S_XPC_W2-#ctor-System-String-'></a>
### #ctor(pc) `constructor`

##### Summary

Custom constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| pc | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | pc in string format, must be 4 hex numbers |

<a name='M-CSLibrary-Structures-S_XPC_W2-#ctor-System-UInt16-'></a>
### #ctor(pc) `constructor`

##### Summary

Custom constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| pc | [System.UInt16](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16 'System.UInt16') | pc in ushort format |

<a name='M-CSLibrary-Structures-S_XPC_W2-CompareTo-System-Object-'></a>
### CompareTo(item) `method`

##### Summary

Compare Data
if equal return 0

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| item | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') |  |

<a name='M-CSLibrary-Structures-S_XPC_W2-GetLength'></a>
### GetLength() `method`

##### Summary

Get Data Length, Data in word format

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_XPC_W2-ToBytes'></a>
### ToBytes() `method`

##### Summary

Convert to byte array

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_XPC_W2-ToShorts'></a>
### ToShorts() `method`

##### Summary

Convert to short array

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_XPC_W2-ToString'></a>
### ToString() `method`

##### Summary

Convert to HexString

##### Returns



##### Parameters

This method has no parameters.

<a name='M-CSLibrary-Structures-S_XPC_W2-ToUshorts'></a>
### ToUshorts() `method`

##### Summary

Convert to ushort array

##### Returns



##### Parameters

This method has no parameters.

<a name='T-CSLibrary-Structures-SelectAction'></a>
## SelectAction `type`

##### Namespace

CSLibrary.Structures

##### Summary

The partitioning of tags into disjoint groups is accomplished by applying actions 
to the tags that match and/or do not match the specified mask.

<a name='M-CSLibrary-Structures-SelectAction-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='M-CSLibrary-Structures-SelectAction-#ctor-CSLibrary-Constants-Target,CSLibrary-Constants-Action,System-Int32-'></a>
### #ctor(target,action,enableTruncate) `constructor`

##### Summary

Custom constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| target | [CSLibrary.Constants.Target](#T-CSLibrary-Constants-Target 'CSLibrary.Constants.Target') | [Target](#T-CSLibrary-Constants-Target 'CSLibrary.Constants.Target') |
| action | [CSLibrary.Constants.Action](#T-CSLibrary-Constants-Action 'CSLibrary.Constants.Action') | [Action](#T-CSLibrary-Constants-Action 'CSLibrary.Constants.Action') |
| enableTruncate | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |

<a name='F-CSLibrary-Structures-SelectAction-action'></a>
### action `constants`

##### Summary

Specifies the action that will be applied to the tag populations (i.e, the 
matching and non-matching tags).

<a name='F-CSLibrary-Structures-SelectAction-enableTruncate'></a>
### enableTruncate `constants`

##### Summary

Specifies if, during singulation, a tag will respond to a subsequent 
inventory operation with its entire Electronic Product Code (EPC) or 
will only respond with the portion of the EPC that immediately follows 
the bit pattern (as long as the bit pattern falls within the EPC – if the 
bit pattern does not fall within the tag’s EPC, the tag ignores the tag 
partitioning operation2).  If this parameter is non-zero:

bank must be [EPC](#F-CSLibrary-Constants-MemoryBank-EPC 'CSLibrary.Constants.MemoryBank.EPC').

target must be [SELECTED](#F-CSLibrary-Constants-Target-SELECTED 'CSLibrary.Constants.Target.SELECTED').

This action must correspond to the last tag select operation issued 
before the inventory operation or access command.

<a name='F-CSLibrary-Structures-SelectAction-target'></a>
### target `constants`

##### Summary

Specifies what flag, selected (i.e., SL) or one of the four inventory 
flags (i.e., S0, S1, S2, or S3), will be modified by the action.

<a name='T-CSLibrary-Structures-SelectCriteria'></a>
## SelectCriteria `type`

##### Namespace

CSLibrary.Structures

##### Summary

Tag-selection criteria

<a name='M-CSLibrary-Structures-SelectCriteria-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-SelectCriteria-countCriteria'></a>
### countCriteria `constants`

##### Summary

The number of selection criteria in the array pointed to by the pCriteria 
field.  This field must be greater than or equal to zero and less than or 
equal to the maximum number of selection criteria as specified in [MAC-
EDS].  Calling RFID_18K6CSetSelectCriteria with this field set to 
zero Results in disabling all selection criteria (i.e., even if the 
[SELECT](#F-CSLibrary-Constants-SelectFlags-SELECT 'CSLibrary.Constants.SelectFlags.SELECT') flag is provided to the appropriate 
RFID_18K6CTag* function, no selects will be issued).  If this field is zero, 
pCriteria may be NULL.

<a name='F-CSLibrary-Structures-SelectCriteria-pCriteria'></a>
### pCriteria `constants`

##### Summary

A pointer to an array, containing countCriteria entries, of selection 
criterion structures that are to be applied sequentially, beginning with 
pCriteria[0], to the tag population.  If this field is NULL, 
countCriteria must be zero.

<a name='T-CSLibrary-Structures-SelectCriterion'></a>
## SelectCriterion `type`

##### Namespace

CSLibrary.Structures

##### Summary

Together, the selection mask and selection action form a single selection 
criterion.

<a name='M-CSLibrary-Structures-SelectCriterion-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-SelectCriterion-action'></a>
### action `constants`

##### Summary

The action that is to be applied to matching and/or non-matching tags (as 
defined by the mask field).

<a name='F-CSLibrary-Structures-SelectCriterion-mask'></a>
### mask `constants`

##### Summary

The mask that will be applied to a tag to determine if it is matching or non-
matching.

<a name='T-CSLibrary-Constants-SelectFlags'></a>
## SelectFlags `type`

##### Namespace

CSLibrary.Constants

##### Summary

Select Flags

<a name='F-CSLibrary-Constants-SelectFlags-DISABLE_INVENTORY'></a>
### DISABLE_INVENTORY `constants`

##### Summary

Disable Inventory

<a name='F-CSLibrary-Constants-SelectFlags-POSTMATCH'></a>
### POSTMATCH `constants`

##### Summary

Use Post-Match Criteria

<a name='F-CSLibrary-Constants-SelectFlags-POST_MATCH'></a>
### POST_MATCH `constants`

##### Summary

Using Post-Match Criterion

<a name='F-CSLibrary-Constants-SelectFlags-READ1BANK'></a>
### READ1BANK `constants`

##### Summary

Read 1 bank after Inventory

<a name='F-CSLibrary-Constants-SelectFlags-READ2BANK'></a>
### READ2BANK `constants`

##### Summary

Read 2 bank after Inventory

<a name='F-CSLibrary-Constants-SelectFlags-SELECT'></a>
### SELECT `constants`

##### Summary

Use Select Criteria

<a name='F-CSLibrary-Constants-SelectFlags-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown

<a name='F-CSLibrary-Constants-SelectFlags-ZERO'></a>
### ZERO `constants`

##### Summary

Normal Inventory

<a name='T-CSLibrary-Structures-SelectMask'></a>
## SelectMask `type`

##### Namespace

CSLibrary.Structures

##### Summary

The tag mask is used to specify a bit pattern that is used to match against one of 
a tag's memory banks to determine if it is matching or non-matching.  A mask is 
a combination of a memory bank and a sequence of bits that will be matched at 
the specified offset within the chosen memory bank.

<a name='M-CSLibrary-Structures-SelectMask-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='M-CSLibrary-Structures-SelectMask-#ctor-CSLibrary-Constants-MemoryBank,System-UInt32,System-UInt32,System-Byte[]-'></a>
### #ctor(bank,offset,count,epc) `constructor`

##### Summary

Custom constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| bank | [CSLibrary.Constants.MemoryBank](#T-CSLibrary-Constants-MemoryBank 'CSLibrary.Constants.MemoryBank') | Memory bank |
| offset | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | offset in bit |
| count | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | count in bit |
| epc | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | epc mask |

<a name='F-CSLibrary-Structures-SelectMask-bank'></a>
### bank `constants`

##### Summary

The memory bank that contains the bits that will be compared 
against the bit pattern specified in mask.  For a tag mask, 
[RESERVED](#F-CSLibrary-Constants-MemoryBank-RESERVED 'CSLibrary.Constants.MemoryBank.RESERVED') is not a valid value.

<a name='F-CSLibrary-Structures-SelectMask-count'></a>
### count `constants`

##### Summary

The number of bits in the mask.  A length of zero will cause all 
tags to match.  If (offset+count) falls beyond the end of 
the memory bank, the tag is considered non-matching.  Valid 
values are 0 to 255, inclusive.

<a name='F-CSLibrary-Structures-SelectMask-m_mask'></a>
### m_mask `constants`

##### Summary

A buffer that contains a left-justified bit array that represents 
that bit pattern to match

<a name='F-CSLibrary-Structures-SelectMask-offset'></a>
### offset `constants`

##### Summary

The offset, in bits, from the start of the memory bank, of the 
first bit that will be matched against the mask.  If offset falls 
beyond the end of the memory bank, the tag is considered 
non-matching.

<a name='P-CSLibrary-Structures-SelectMask-mask'></a>
### mask `property`

##### Summary

A buffer that contains a left-justified bit array that represents 
that bit pattern to match – i.e., the most significant bit of the bit 
array appears in the most-significant bit (i.e., bit 7) of the first 
byte of the buffer (i.e., mask[0]).  All bits beyond count are 
ignored.  For example, if the application wished to find tags 
with the following 12 bits 1000.1100.1101, starting at offset 
16 in the EPC memory bank, then the fields would be set as 
follows: 
bank    = RFID_18K6C_MEMORY_BANK_EPC 
offset  = 16 
count   = 12 
mask[0] = 0x8C (1000.1100) 
mask[1] = 0xD? (1101.????)

<a name='T-CSLibrary-Constants-SelectMaskFlags'></a>
## SelectMaskFlags `type`

##### Namespace

CSLibrary.Constants

##### Summary

Tag Parameters Selected flags

<a name='F-CSLibrary-Constants-SelectMaskFlags-DISABLE_ALL'></a>
### DISABLE_ALL `constants`

##### Summary

a flag that enable all disable

<a name='F-CSLibrary-Constants-SelectMaskFlags-ENABLE_ALL'></a>
### ENABLE_ALL `constants`

##### Summary

a flag that enable all items

<a name='F-CSLibrary-Constants-SelectMaskFlags-ENABLE_NON_MATCH'></a>
### ENABLE_NON_MATCH `constants`

##### Summary

A flag that select a tag if the tag is not matching to you selected criteria.

<a name='F-CSLibrary-Constants-SelectMaskFlags-ENABLE_PC_MASK'></a>
### ENABLE_PC_MASK `constants`

##### Summary

A flag that enable using PC mask to select a tag.

<a name='F-CSLibrary-Constants-SelectMaskFlags-ENABLE_TOGGLE'></a>
### ENABLE_TOGGLE `constants`

##### Summary

A flag that indicates if, after performing the inventory cycle for 
the specified target (i.e., A or B), if the target should be toggled 
(i.e., A to B or B to A) and another inventory cycle run.  A non-
zero value indicates that the target should be toggled.  A zero 
value indicates that the target should not be toggled.

<a name='T-CSLibrary-Constants-Selected'></a>
## Selected `type`

##### Namespace

CSLibrary.Constants

##### Summary

Specifies the state of the selected (SL) flag for tags that will have 
the operation applied to them.

<a name='F-CSLibrary-Constants-Selected-ALL'></a>
### ALL `constants`

##### Summary

Select all

<a name='F-CSLibrary-Constants-Selected-ASSERTED'></a>
### ASSERTED `constants`

##### Summary

Select on

<a name='F-CSLibrary-Constants-Selected-DEASSERTED'></a>
### DEASSERTED `constants`

##### Summary

Select off

<a name='F-CSLibrary-Constants-Selected-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown

<a name='T-CSLibrary-Structures-Sensor'></a>
## Sensor `type`

##### Namespace

CSLibrary.Structures

##### Summary

Sensor Type

<a name='T-CSLibrary-Constants-Session'></a>
## Session `type`

##### Namespace

CSLibrary.Constants

##### Summary

Specifies which inventory session flag (i.e., S0, S1, S2, or S3) 
will be matched against the inventory state specified by target.

<a name='F-CSLibrary-Constants-Session-S0'></a>
### S0 `constants`

##### Summary

Tag energized : Indefinite

Tag not energized : None

<a name='F-CSLibrary-Constants-Session-S1'></a>
### S1 `constants`

##### Summary

Tag energized :

Norminal temperature range : 5s > persistence > 500ms

Exttended temperature range : Not specified

Tag not energized :

Norminal temperature range : 5s > persistence > 500ms

Exttended temperature range : Not specified

<a name='F-CSLibrary-Constants-Session-S2'></a>
### S2 `constants`

##### Summary

Tag energized : Indefinite

Tag not energized :

Norminal temperature range : persistence > 2s

Exttended temperature range : Not specified

<a name='F-CSLibrary-Constants-Session-S3'></a>
### S3 `constants`

##### Summary

Tag energized : Indefinite

Tag not energized :

Norminal temperature range : persistence > 2s

Exttended temperature range : Not specified

<a name='F-CSLibrary-Constants-Session-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown

<a name='T-CSLibrary-Constants-SessionTarget'></a>
## SessionTarget `type`

##### Namespace

CSLibrary.Constants

##### Summary

Specifies the state of the inventory session flag (i.e., A or B), 
specified by session, for tags that will have the operation 
applied to them.

<a name='F-CSLibrary-Constants-SessionTarget-A'></a>
### A `constants`

##### Summary

Session A

<a name='F-CSLibrary-Constants-SessionTarget-B'></a>
### B `constants`

##### Summary

Session B

<a name='F-CSLibrary-Constants-SessionTarget-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown

<a name='T-CSLibrary-Constants-SingulationAlgorithm'></a>
## SingulationAlgorithm `type`

##### Namespace

CSLibrary.Constants

##### Summary

Based upon usage scenarios, different singulation algorithms (i.e., Q-adjustment, 
etc.) may be desired.  This document simply documents the mechanisms by 
which an application can choose and configure singulation algorithms.  This 
document does not provide specific information about the singulation algorithms.

<a name='F-CSLibrary-Constants-SingulationAlgorithm-DYNAMICQ'></a>
### DYNAMICQ `constants`

##### Summary

Adjusts the Q value based on the presence
or absence of tags.  This is the MAC's 
singulation algorithm 3 (see [MAC-EDS]).

<a name='F-CSLibrary-Constants-SingulationAlgorithm-FIXEDQ'></a>
### FIXEDQ `constants`

##### Summary

Fixed Q value.  This is the MAC's 
singulation algorithm 0 (see [MAC-EDS]). 
NOTE:  when performing non-inventory 
tag-access operations (i.e., read, write, 
kill, or lock), the MAC always uses this 
singulation algorithm.

<a name='F-CSLibrary-Constants-SingulationAlgorithm-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown

<a name='T-CSLibrary-Structures-SingulationAlgorithmParms'></a>
## SingulationAlgorithmParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

SingulationAlgorithmParms

<a name='M-CSLibrary-Structures-SingulationAlgorithmParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-SingulationAlgorithmParms-length_'></a>
### length_ `constants`

##### Summary

Structure size

<a name='P-CSLibrary-Structures-SingulationAlgorithmParms-length'></a>
### length `property`

##### Summary

Structure size

<a name='T-CSLibrary-Structures-SingulationCriteria'></a>
## SingulationCriteria `type`

##### Namespace

CSLibrary.Structures

##### Summary

Post-singulation match criteria can be grouped together using the following:

<a name='M-CSLibrary-Structures-SingulationCriteria-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-SingulationCriteria-countCriteria'></a>
### countCriteria `constants`

##### Summary

The number of singulation criteria in the array pointed to by the 
pCriteria field.  This field must be greater than or equal to zero and 
less than or equal to the maximum number of post-singulation criteria as 
specified in [MAC-EDS].  Calling 
[SetPostMatchCriteria](#M-CSLibrary-HighLevelInterface-SetPostMatchCriteria-CSLibrary-Structures-SingulationCriterion[]- 'CSLibrary.HighLevelInterface.SetPostMatchCriteria(CSLibrary.Structures.SingulationCriterion[])') with this field set to zero Results 
in disabling all post-singulation criteria (i.e., even if the 
[POST_MATCH](#F-CSLibrary-Constants-SelectFlags-POST_MATCH 'CSLibrary.Constants.SelectFlags.POST_MATCH') flag is provided to the appropriate 
RFID_18K6CTag* function, no post-singulation matching will be 
performed – the Result is that all tags are considered matching).  If this 
field is zero, pCriteria may be NULL.

<a name='F-CSLibrary-Structures-SingulationCriteria-pCriteria'></a>
### pCriteria `constants`

##### Summary

A pointer to an array, containing countCriteria entries, of post-
 singulation criterion structures that are to be applied sequentially, 
 beginning with pCriteria[0], to singulated tags.  This must not be 
 NULL.  If this field is NULL, countCriteria must be zero.

<a name='T-CSLibrary-Structures-SingulationCriterion'></a>
## SingulationCriterion `type`

##### Namespace

CSLibrary.Structures

##### Summary

Together, the selection mask and an indication if the application is interested in 
matching or non-matching tags form a single post-singulation match criterion.

<a name='M-CSLibrary-Structures-SingulationCriterion-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-SingulationCriterion-mask'></a>
### mask `constants`

##### Summary

The mask that will be applied to the tag’s Electronic Product 
Code to determine if it is matching or non-matching.

<a name='F-CSLibrary-Structures-SingulationCriterion-match'></a>
### match `constants`

##### Summary

Determines if the associated tag-protocol operation will be 
applied to tags that match the mask or not.  A non-zero 
value indicates that the tag-protocol operation should be 
applied to tags that match the mask.  A value of zero 
indicates that the tag-protocol operation should be applied 
to tags that do not match the mask.

<a name='T-CSLibrary-Structures-SingulationMask'></a>
## SingulationMask `type`

##### Namespace

CSLibrary.Structures

##### Summary

The post-singulation match mask is used to specify a bit pattern of up to 496 bits 
that is used to match against the EPC backscattered by a tag during singulation 
to determine if a tag is matching or non-matching.

<a name='M-CSLibrary-Structures-SingulationMask-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='M-CSLibrary-Structures-SingulationMask-#ctor-System-UInt32,System-UInt32,System-Byte[]-'></a>
### #ctor(offset,count,mask) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| offset | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| count | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| mask | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |

<a name='F-CSLibrary-Structures-SingulationMask-count'></a>
### count `constants`

##### Summary

The number of bits in the mask.  A length of zero will cause 
all tags to match.  If (offset+count) falls beyond the end 
of the EPC, the tag is considered non-matching.  Valid 
values are 0 to 496, inclusive.

<a name='F-CSLibrary-Structures-SingulationMask-m_mask'></a>
### m_mask `constants`

##### Summary



<a name='F-CSLibrary-Structures-SingulationMask-offset'></a>
### offset `constants`

##### Summary

The offset in bits, from the start of the Electronic Product 
Code (EPC), of the first bit that will be matched against the 
mask.  If offset falls beyond the end of EPC, the tag is 
considered non-matching.

<a name='P-CSLibrary-Structures-SingulationMask-mask'></a>
### mask `property`

##### Summary

A buffer that contains a left-justified bit array that represents 
that bit pattern to match – i.e., the most significant bit of the 
bit array appears in the most-significant bit (i.e., bit 7) of the 
first byte of the buffer (i.e., mask[0]).  All bits beyond count 
are ignored.  For example, if the application wished to find 
tags with the following 16 bits 1011.1111.1010.0101, 
starting at offset 20 in the Electronic Product Code, then the 
fields would be set as follows: 
offset  = 20 
count   = 16 
mask[0] = 0xBF (1011.1111) 
mask[1] = 0xA5 (1010.0101)

<a name='T-CSLibrary-Tools-Sound'></a>
## Sound `type`

##### Namespace

CSLibrary.Tools

##### Summary

PC Sound

<a name='M-CSLibrary-Tools-Sound-Beep-System-UInt32,System-UInt32-'></a>
### Beep(frequency,duration) `method`

##### Summary

Sound Beep

##### Returns

BOOL

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| frequency | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Frequency |
| duration | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Duration |

<a name='T-CSLibrary-Structures-StorageRule'></a>
## StorageRule `type`

##### Namespace

CSLibrary.Structures

##### Summary

Store Rule

<a name='F-CSLibrary-Structures-StorageRule-Normal'></a>
### Normal `constants`

##### Summary

Not save new data

<a name='F-CSLibrary-Structures-StorageRule-Rolling'></a>
### Rolling `constants`

##### Summary

Save new data

<a name='T-CSLibrary-Structures-TAG_ACCESS_PKT'></a>
## TAG_ACCESS_PKT `type`

##### Namespace

CSLibrary.Structures

##### Summary

Tag Access Packet

<a name='M-CSLibrary-Structures-TAG_ACCESS_PKT-#ctor-System-Byte,CSLibrary-Constants-RFID_18K6C,System-UInt32,CSLibrary-Constants-TAG_BACKSCATTERED_ERROR,System-Byte[]-'></a>
### #ctor(flags,cmd,ms,errorCode,data) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| flags | [System.Byte](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte 'System.Byte') | error flags |
| cmd | [CSLibrary.Constants.RFID_18K6C](#T-CSLibrary-Constants-RFID_18K6C 'CSLibrary.Constants.RFID_18K6C') | access command |
| ms | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | timer |
| errorCode | [CSLibrary.Constants.TAG_BACKSCATTERED_ERROR](#T-CSLibrary-Constants-TAG_BACKSCATTERED_ERROR 'CSLibrary.Constants.TAG_BACKSCATTERED_ERROR') | error code |
| data | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | data |

<a name='F-CSLibrary-Structures-TAG_ACCESS_PKT-cmd'></a>
### cmd `constants`

##### Summary

ISO 18000-6C access command

<a name='F-CSLibrary-Structures-TAG_ACCESS_PKT-data'></a>
### data `constants`

##### Summary

Tag Access data

<a name='F-CSLibrary-Structures-TAG_ACCESS_PKT-errorCode'></a>
### errorCode `constants`

##### Summary

Please check success flags first

If the tag backscattered an error (i.e. the tag backscatter error

flag is set), this value is the error code that the tag

backscattered. Values are:

– general error (catch-all for errors not covered by codes)

– specified memory location does not exist of the PC value

is not supported by the tag

– specified memory location is locked and/or permalocked

and is not writeable

– tag has insufficient power to perform the memory write

– tag does not support error-specific codes

<a name='F-CSLibrary-Structures-TAG_ACCESS_PKT-ms_ctr'></a>
### ms_ctr `constants`

##### Summary

Current millisecond timer/counter

<a name='P-CSLibrary-Structures-TAG_ACCESS_PKT-IsAckTimeout'></a>
### IsAckTimeout `property`

##### Summary

ACK timeout flag:

false = Tag responded within timeout.

true  = Tag failed to respond within timeout.

<a name='P-CSLibrary-Structures-TAG_ACCESS_PKT-IsBackscatterError'></a>
### IsBackscatterError `property`

##### Summary

Tag backscatter error flag:

false = Tag did not backscatter an error.

true  = Tag backscattered an error.  See 
`error_code` field.

<a name='P-CSLibrary-Structures-TAG_ACCESS_PKT-IsCRCInvalid'></a>
### IsCRCInvalid `property`

##### Summary

CRC invalid flag:

false = CRC was valid

true  = CRC was invalid

<a name='P-CSLibrary-Structures-TAG_ACCESS_PKT-IsError'></a>
### IsError `property`

##### Summary

false = Access operation succeeded

true  = An error occurred.  If one of the following 
error-specific bit fields does not indicate an 
error, the error code appears in the data
field.

<a name='T-CSLibrary-Constants-TAG_BACKSCATTERED_ERROR'></a>
## TAG_BACKSCATTERED_ERROR `type`

##### Namespace

CSLibrary.Constants

##### Summary

If a Tag encounters an error when executing an access command that reads from or writes to memory,
and if the command is a handle-based command(i.e. Read, Write, Kill, Lock, BlockWrite, BlockErase,
or BlockPermalock), then the Tag shall backscatter an error code.

<a name='F-CSLibrary-Constants-TAG_BACKSCATTERED_ERROR-INSUFFICIENT_POWER'></a>
### INSUFFICIENT_POWER `constants`

##### Summary

The Tag has insufficient power to perform the memory-write operation.

<a name='F-CSLibrary-Constants-TAG_BACKSCATTERED_ERROR-MEMORY_LOCKED'></a>
### MEMORY_LOCKED `constants`

##### Summary

The specified memory location is locked and/or permalocked and is either not writeable or not readable.

<a name='F-CSLibrary-Constants-TAG_BACKSCATTERED_ERROR-MEMORY_OVERRUN'></a>
### MEMORY_OVERRUN `constants`

##### Summary

The specified memory location does not exist or the EPC length field is not

<a name='F-CSLibrary-Constants-TAG_BACKSCATTERED_ERROR-NON_SPECIFIC_ERROR'></a>
### NON_SPECIFIC_ERROR `constants`

##### Summary

The Tag does not support error-specific codes.

<a name='F-CSLibrary-Constants-TAG_BACKSCATTERED_ERROR-OTHER_ERROR'></a>
### OTHER_ERROR `constants`

##### Summary

Catch-all for errors not covered by other codes

<a name='T-CSLibrary-Structures-TAG_BLOCK_WRITE_PARMS'></a>
## TAG_BLOCK_WRITE_PARMS `type`

##### Namespace

CSLibrary.Structures

##### Summary

The ISO 18000-6C tag-block write operation parameters

<a name='F-CSLibrary-Structures-TAG_BLOCK_WRITE_PARMS-accessPassword'></a>
### accessPassword `constants`

##### Summary

Target Access Password

<a name='F-CSLibrary-Structures-TAG_BLOCK_WRITE_PARMS-bank'></a>
### bank `constants`

##### Summary

Target Memory Bank

<a name='F-CSLibrary-Structures-TAG_BLOCK_WRITE_PARMS-count'></a>
### count `constants`

##### Summary

Total number of words written to user memory

<a name='F-CSLibrary-Structures-TAG_BLOCK_WRITE_PARMS-flags'></a>
### flags `constants`

##### Summary

Flag - Zero or combination of  Select or Post-Match

<a name='F-CSLibrary-Structures-TAG_BLOCK_WRITE_PARMS-offset'></a>
### offset `constants`

##### Summary

Starting offset

<a name='F-CSLibrary-Structures-TAG_BLOCK_WRITE_PARMS-pData'></a>
### pData `constants`

##### Summary

Write Buffer data to target tag

<a name='F-CSLibrary-Structures-TAG_BLOCK_WRITE_PARMS-retryCount'></a>
### retryCount `constants`

##### Summary

The maximum number of times the write should be retried in the event 
of write-verify failure(s).  In the event of write-verify failure(s), the write 
will be retried either for the specified number of retries or until the data 
written is successfully verified.  If the specified number of retries are 
performed without successfully verifying the written data, the write 
operation is considered to have failed and the tag-access operation-
response packet will indicate the error.  This value must be between 0 
and 31, inclusive. 
If verify is non-zero, this parameter is ignored.

<a name='T-CSLibrary-Net-TFTPException'></a>
## TFTPException `type`

##### Namespace

CSLibrary.Net

##### Summary

A TFTP Exception

<a name='M-CSLibrary-Net-TFTPException-#ctor-System-Int32,System-String-'></a>
### #ctor(errCode,errMsg) `constructor`

##### Summary

Initializes a new instance of the [TFTPException](#T-CSLibrary-Net-TFTPException 'CSLibrary.Net.TFTPException') class.

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| errCode | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | The err code. |
| errMsg | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The err MSG. |

<a name='F-CSLibrary-Net-TFTPException-ErrorCode'></a>
### ErrorCode `constants`

##### Summary

Error code

<a name='F-CSLibrary-Net-TFTPException-ErrorMessage'></a>
### ErrorMessage `constants`

##### Summary

Error Message

<a name='M-CSLibrary-Net-TFTPException-ToString'></a>
### ToString() `method`

##### Summary

Creates and returns a string representation of the current exception.

##### Returns

A string representation of the current exception.

##### Parameters

This method has no parameters.

<a name='T-CSLibrary-Constants-TagAccess'></a>
## TagAccess `type`

##### Namespace

CSLibrary.Constants

##### Summary

The values that can be found in the command field for tag access packets

<a name='F-CSLibrary-Constants-TagAccess-BLOCKWRITE'></a>
### BLOCKWRITE `constants`

##### Summary

ISO 18000-6C Block Write

<a name='F-CSLibrary-Constants-TagAccess-CHANGEEAS'></a>
### CHANGEEAS `constants`

##### Summary

(Custome) Change EAS

<a name='F-CSLibrary-Constants-TagAccess-ERASE'></a>
### ERASE `constants`

##### Summary

ISO 18000-6C Erase

<a name='F-CSLibrary-Constants-TagAccess-KILL'></a>
### KILL `constants`

##### Summary

ISO 18000-6C Kill

<a name='F-CSLibrary-Constants-TagAccess-LOCK'></a>
### LOCK `constants`

##### Summary

ISO 18000-6C Lock

<a name='F-CSLibrary-Constants-TagAccess-READ'></a>
### READ `constants`

##### Summary

ISO 18000-6C Read

<a name='F-CSLibrary-Constants-TagAccess-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown

<a name='F-CSLibrary-Constants-TagAccess-WRITE'></a>
### WRITE `constants`

##### Summary

ISO 18000-6C Write

<a name='T-CSLibrary-Structures-TagAccessCallbackDelegate'></a>
## TagAccessCallbackDelegate `type`

##### Namespace

CSLibrary.Structures

##### Summary

Tag access callback

##### Returns

return false will abort operation

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| pkt | [T:CSLibrary.Structures.TagAccessCallbackDelegate](#T-T-CSLibrary-Structures-TagAccessCallbackDelegate 'T:CSLibrary.Structures.TagAccessCallbackDelegate') | packet data |

<a name='T-CSLibrary-Structures-TagBlockPermalockParms'></a>
## TagBlockPermalockParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

block lock structure, configure this before do block lock

<a name='M-CSLibrary-Structures-TagBlockPermalockParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-TagBlockPermalockParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no 
access password.

<a name='F-CSLibrary-Structures-TagBlockPermalockParms-count'></a>
### count `constants`

##### Summary



<a name='F-CSLibrary-Structures-TagBlockPermalockParms-flags'></a>
### flags `constants`

##### Summary

Flag - Zero or combination of  Select or Post-Match

<a name='F-CSLibrary-Structures-TagBlockPermalockParms-length'></a>
### length `constants`

##### Summary

Structure size

<a name='F-CSLibrary-Structures-TagBlockPermalockParms-mask'></a>
### mask `constants`

##### Summary



<a name='F-CSLibrary-Structures-TagBlockPermalockParms-offset'></a>
### offset `constants`

##### Summary



<a name='F-CSLibrary-Structures-TagBlockPermalockParms-retryCount'></a>
### retryCount `constants`

##### Summary

Number of retries attemp to read. This field must be between 0 and 15, inclusive.

<a name='F-CSLibrary-Structures-TagBlockPermalockParms-setPermalock'></a>
### setPermalock `constants`

##### Summary

True to set permalock, otherwise read it state

<a name='T-CSLibrary-Structures-TagCallbackInfo'></a>
## TagCallbackInfo `type`

##### Namespace

CSLibrary.Structures

##### Summary

Tag Callback Information

<a name='M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Int32,System-Single,System-UInt32,System-UInt32,System-Byte,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-UInt32,System-String-'></a>
### #ctor(index,rssi,count,antennaPort,pc,epc,ms_ctr,name) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| index | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |
| rssi | [System.Single](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Single 'System.Single') |  |
| count | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| antennaPort | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| pc | [System.Byte](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte 'System.Byte') |  |
| epc | [CSLibrary.Structures.S_PC](#T-CSLibrary-Structures-S_PC 'CSLibrary.Structures.S_PC') |  |
| ms_ctr | [CSLibrary.Structures.S_EPC](#T-CSLibrary-Structures-S_EPC 'CSLibrary.Structures.S_EPC') |  |
| name | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |

<a name='M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Int32,System-Single,System-UInt32,System-Byte,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-UInt16[],System-UInt16[],System-UInt32,System-UInt16,System-String-'></a>
### #ctor(index,rssi,count,antennaPort,freqChannel,pc,epc,ms_ctr,name) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| index | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |
| rssi | [System.Single](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Single 'System.Single') |  |
| count | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| antennaPort | [System.Byte](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte 'System.Byte') |  |
| freqChannel | [CSLibrary.Structures.S_PC](#T-CSLibrary-Structures-S_PC 'CSLibrary.Structures.S_PC') |  |
| pc | [CSLibrary.Structures.S_EPC](#T-CSLibrary-Structures-S_EPC 'CSLibrary.Structures.S_EPC') |  |
| epc | [System.UInt16[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16[] 'System.UInt16[]') |  |
| ms_ctr | [System.UInt16[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16[] 'System.UInt16[]') |  |
| name | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |

<a name='M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Int32,System-Single,System-UInt32,System-Byte,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_XPC_W1,CSLibrary-Structures-S_XPC_W2,CSLibrary-Structures-S_EPC,System-UInt16[],System-UInt16[],System-UInt32,System-UInt16,System-String-'></a>
### #ctor(index,rssi,count,antennaPort,freqChannel,pc,epc,ms_ctr,name) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| index | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |
| rssi | [System.Single](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Single 'System.Single') |  |
| count | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| antennaPort | [System.Byte](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte 'System.Byte') |  |
| freqChannel | [CSLibrary.Structures.S_PC](#T-CSLibrary-Structures-S_PC 'CSLibrary.Structures.S_PC') |  |
| pc | [CSLibrary.Structures.S_XPC_W1](#T-CSLibrary-Structures-S_XPC_W1 'CSLibrary.Structures.S_XPC_W1') |  |
| epc | [CSLibrary.Structures.S_XPC_W2](#T-CSLibrary-Structures-S_XPC_W2 'CSLibrary.Structures.S_XPC_W2') |  |
| ms_ctr | [CSLibrary.Structures.S_EPC](#T-CSLibrary-Structures-S_EPC 'CSLibrary.Structures.S_EPC') |  |
| name | [System.UInt16[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16[] 'System.UInt16[]') |  |

<a name='M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Int32,System-Single,System-UInt32,System-UInt32,System-Byte,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-String-'></a>
### #ctor(index,rssi,count,antennaPort,pc,epc,name) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| index | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |
| rssi | [System.Single](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Single 'System.Single') |  |
| count | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| antennaPort | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| pc | [System.Byte](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte 'System.Byte') |  |
| epc | [CSLibrary.Structures.S_PC](#T-CSLibrary-Structures-S_PC 'CSLibrary.Structures.S_PC') |  |
| name | [CSLibrary.Structures.S_EPC](#T-CSLibrary-Structures-S_EPC 'CSLibrary.Structures.S_EPC') |  |

<a name='M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Single,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-String-'></a>
### #ctor(rssi,pc,epc,name) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| rssi | [System.Single](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Single 'System.Single') |  |
| pc | [CSLibrary.Structures.S_PC](#T-CSLibrary-Structures-S_PC 'CSLibrary.Structures.S_PC') |  |
| epc | [CSLibrary.Structures.S_EPC](#T-CSLibrary-Structures-S_EPC 'CSLibrary.Structures.S_EPC') |  |
| name | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |  |

<a name='M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Int32,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-String-'></a>
### #ctor(index,pc,epc,name) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| index | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |
| pc | [CSLibrary.Structures.S_PC](#T-CSLibrary-Structures-S_PC 'CSLibrary.Structures.S_PC') |  |
| epc | [CSLibrary.Structures.S_EPC](#T-CSLibrary-Structures-S_EPC 'CSLibrary.Structures.S_EPC') |  |
| name | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |  |

<a name='M-CSLibrary-Structures-TagCallbackInfo-#ctor-CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-String-'></a>
### #ctor(pc,epc,name) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| pc | [CSLibrary.Structures.S_PC](#T-CSLibrary-Structures-S_PC 'CSLibrary.Structures.S_PC') |  |
| epc | [CSLibrary.Structures.S_EPC](#T-CSLibrary-Structures-S_EPC 'CSLibrary.Structures.S_EPC') |  |
| name | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |  |

<a name='M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Int32,System-Single,System-UInt32,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_XPC_W1,CSLibrary-Structures-S_XPC_W2,CSLibrary-Structures-S_EPC,System-UInt32-'></a>
### #ctor(index,rssi,count,pc,xpc_w1,xpc_w2,epc,ms_ctr) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| index | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |
| rssi | [System.Single](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Single 'System.Single') |  |
| count | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| pc | [CSLibrary.Structures.S_PC](#T-CSLibrary-Structures-S_PC 'CSLibrary.Structures.S_PC') |  |
| xpc_w1 | [CSLibrary.Structures.S_XPC_W1](#T-CSLibrary-Structures-S_XPC_W1 'CSLibrary.Structures.S_XPC_W1') |  |
| xpc_w2 | [CSLibrary.Structures.S_XPC_W2](#T-CSLibrary-Structures-S_XPC_W2 'CSLibrary.Structures.S_XPC_W2') |  |
| epc | [CSLibrary.Structures.S_EPC](#T-CSLibrary-Structures-S_EPC 'CSLibrary.Structures.S_EPC') |  |
| ms_ctr | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |

<a name='M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Int32,System-Single,System-UInt32,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-UInt32-'></a>
### #ctor(index,rssi,count,pc,epc,ms_ctr) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| index | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |
| rssi | [System.Single](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Single 'System.Single') |  |
| count | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| pc | [CSLibrary.Structures.S_PC](#T-CSLibrary-Structures-S_PC 'CSLibrary.Structures.S_PC') |  |
| epc | [CSLibrary.Structures.S_EPC](#T-CSLibrary-Structures-S_EPC 'CSLibrary.Structures.S_EPC') |  |
| ms_ctr | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |

<a name='M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Int32,System-Single,System-UInt32,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC-'></a>
### #ctor(index,rssi,count,pc,epc) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| index | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |
| rssi | [System.Single](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Single 'System.Single') |  |
| count | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| pc | [CSLibrary.Structures.S_PC](#T-CSLibrary-Structures-S_PC 'CSLibrary.Structures.S_PC') |  |
| epc | [CSLibrary.Structures.S_EPC](#T-CSLibrary-Structures-S_EPC 'CSLibrary.Structures.S_EPC') |  |

<a name='M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Int32,System-Single,System-UInt32,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-UInt16-'></a>
### #ctor(index,rssi,count,pc,epc) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| index | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |
| rssi | [System.Single](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Single 'System.Single') |  |
| count | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| pc | [CSLibrary.Structures.S_PC](#T-CSLibrary-Structures-S_PC 'CSLibrary.Structures.S_PC') |  |
| epc | [CSLibrary.Structures.S_EPC](#T-CSLibrary-Structures-S_EPC 'CSLibrary.Structures.S_EPC') |  |

<a name='M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Single,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-UInt32-'></a>
### #ctor(rssi,pc,epc) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| rssi | [System.Single](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Single 'System.Single') |  |
| pc | [CSLibrary.Structures.S_PC](#T-CSLibrary-Structures-S_PC 'CSLibrary.Structures.S_PC') |  |
| epc | [CSLibrary.Structures.S_EPC](#T-CSLibrary-Structures-S_EPC 'CSLibrary.Structures.S_EPC') |  |

<a name='M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Single,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-UInt32,System-UInt16-'></a>
### #ctor(rssi,pc,epc) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| rssi | [System.Single](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Single 'System.Single') |  |
| pc | [CSLibrary.Structures.S_PC](#T-CSLibrary-Structures-S_PC 'CSLibrary.Structures.S_PC') |  |
| epc | [CSLibrary.Structures.S_EPC](#T-CSLibrary-Structures-S_EPC 'CSLibrary.Structures.S_EPC') |  |

<a name='M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Single,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC-'></a>
### #ctor(rssi,pc,epc) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| rssi | [System.Single](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Single 'System.Single') |  |
| pc | [CSLibrary.Structures.S_PC](#T-CSLibrary-Structures-S_PC 'CSLibrary.Structures.S_PC') |  |
| epc | [CSLibrary.Structures.S_EPC](#T-CSLibrary-Structures-S_EPC 'CSLibrary.Structures.S_EPC') |  |

<a name='M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Boolean,System-Single,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-String-'></a>
### #ctor(crcInvalid,rssi,pc,epc,readerName) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| crcInvalid | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') |  |
| rssi | [System.Single](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Single 'System.Single') |  |
| pc | [CSLibrary.Structures.S_PC](#T-CSLibrary-Structures-S_PC 'CSLibrary.Structures.S_PC') |  |
| epc | [CSLibrary.Structures.S_EPC](#T-CSLibrary-Structures-S_EPC 'CSLibrary.Structures.S_EPC') |  |
| readerName | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |  |

<a name='M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Boolean,System-Single,System-UInt32,System-Byte,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-UInt32,System-UInt16,System-String-'></a>
### #ctor(crcInvalid,rssi,antennaPort,pc,epc,ms_ctr,readerName) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| crcInvalid | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') |  |
| rssi | [System.Single](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Single 'System.Single') |  |
| antennaPort | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| pc | [System.Byte](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte 'System.Byte') |  |
| epc | [CSLibrary.Structures.S_PC](#T-CSLibrary-Structures-S_PC 'CSLibrary.Structures.S_PC') |  |
| ms_ctr | [CSLibrary.Structures.S_EPC](#T-CSLibrary-Structures-S_EPC 'CSLibrary.Structures.S_EPC') |  |
| readerName | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |

<a name='M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Boolean,System-Single,System-UInt32,System-Byte,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-UInt32,System-String-'></a>
### #ctor(crcInvalid,rssi,antennaPort,pc,epc,ms_ctr,readerName) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| crcInvalid | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') |  |
| rssi | [System.Single](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Single 'System.Single') |  |
| antennaPort | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| pc | [System.Byte](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte 'System.Byte') |  |
| epc | [CSLibrary.Structures.S_PC](#T-CSLibrary-Structures-S_PC 'CSLibrary.Structures.S_PC') |  |
| ms_ctr | [CSLibrary.Structures.S_EPC](#T-CSLibrary-Structures-S_EPC 'CSLibrary.Structures.S_EPC') |  |
| readerName | [CSLibrary.Structures.S_PC](#T-CSLibrary-Structures-S_PC 'CSLibrary.Structures.S_PC') |  |

<a name='M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Boolean,System-Single,System-UInt32,System-Byte,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC,System-String-'></a>
### #ctor(crcInvalid,rssi,antennaPort,pc,epc,readerName) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| crcInvalid | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') |  |
| rssi | [System.Single](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Single 'System.Single') |  |
| antennaPort | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| pc | [System.Byte](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte 'System.Byte') |  |
| epc | [CSLibrary.Structures.S_PC](#T-CSLibrary-Structures-S_PC 'CSLibrary.Structures.S_PC') |  |
| readerName | [CSLibrary.Structures.S_EPC](#T-CSLibrary-Structures-S_EPC 'CSLibrary.Structures.S_EPC') |  |

<a name='M-CSLibrary-Structures-TagCallbackInfo-#ctor-System-Int32,CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC-'></a>
### #ctor(index,pc,epc) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| index | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |
| pc | [CSLibrary.Structures.S_PC](#T-CSLibrary-Structures-S_PC 'CSLibrary.Structures.S_PC') |  |
| epc | [CSLibrary.Structures.S_EPC](#T-CSLibrary-Structures-S_EPC 'CSLibrary.Structures.S_EPC') |  |

<a name='M-CSLibrary-Structures-TagCallbackInfo-#ctor-CSLibrary-Structures-S_PC,CSLibrary-Structures-S_EPC-'></a>
### #ctor(pc,epc) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| pc | [CSLibrary.Structures.S_PC](#T-CSLibrary-Structures-S_PC 'CSLibrary.Structures.S_PC') |  |
| epc | [CSLibrary.Structures.S_EPC](#T-CSLibrary-Structures-S_EPC 'CSLibrary.Structures.S_EPC') |  |

<a name='M-CSLibrary-Structures-TagCallbackInfo-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-TagCallbackInfo-Bank1Data'></a>
### Bank1Data `constants`

##### Summary

Bank 1 data

<a name='F-CSLibrary-Structures-TagCallbackInfo-Bank2Data'></a>
### Bank2Data `constants`

##### Summary

Bank 2 data

<a name='F-CSLibrary-Structures-TagCallbackInfo-antennaPort'></a>
### antennaPort `constants`

##### Summary

Current antenna port using.

<a name='F-CSLibrary-Structures-TagCallbackInfo-count'></a>
### count `constants`

##### Summary

total count

<a name='F-CSLibrary-Structures-TagCallbackInfo-crc16'></a>
### crc16 `constants`

##### Summary

crc16

<a name='F-CSLibrary-Structures-TagCallbackInfo-crcInvalid'></a>
### crcInvalid `constants`

##### Summary

Crc error flag

<a name='F-CSLibrary-Structures-TagCallbackInfo-epc'></a>
### epc `constants`

##### Summary

EPC Data (QT Private EPC)

<a name='F-CSLibrary-Structures-TagCallbackInfo-epcpublic'></a>
### epcpublic `constants`

##### Summary

QT Publuc EPC Data

<a name='F-CSLibrary-Structures-TagCallbackInfo-epcpublicstrlen'></a>
### epcpublicstrlen `constants`

##### Summary

QT Public EPC String Length

<a name='F-CSLibrary-Structures-TagCallbackInfo-epcstrlen'></a>
### epcstrlen `constants`

##### Summary

EPC String Length (QT Private EPC Length)

<a name='F-CSLibrary-Structures-TagCallbackInfo-freqChannel'></a>
### freqChannel `constants`

##### Summary

Tag deteched frequency

<a name='F-CSLibrary-Structures-TagCallbackInfo-index'></a>
### index `constants`

##### Summary

Index number, First come with small number.

<a name='F-CSLibrary-Structures-TagCallbackInfo-ms_ctr'></a>
### ms_ctr `constants`

##### Summary

ms_ctr

<a name='F-CSLibrary-Structures-TagCallbackInfo-name'></a>
### name `constants`

##### Summary

RFID Device name

<a name='F-CSLibrary-Structures-TagCallbackInfo-pc'></a>
### pc `constants`

##### Summary

PC Data (QT Private PC)

<a name='F-CSLibrary-Structures-TagCallbackInfo-pcpublic'></a>
### pcpublic `constants`

##### Summary

QT Public PC

<a name='F-CSLibrary-Structures-TagCallbackInfo-receiveTime'></a>
### receiveTime `constants`

##### Summary

Receive Time

<a name='F-CSLibrary-Structures-TagCallbackInfo-rssi'></a>
### rssi `constants`

##### Summary

The Receive Signal Strength Indicator (RSSI).

<a name='F-CSLibrary-Structures-TagCallbackInfo-xpc_w1'></a>
### xpc_w1 `constants`

##### Summary

XPC W1 Data (QT Private XPC W1)

<a name='F-CSLibrary-Structures-TagCallbackInfo-xpc_w2'></a>
### xpc_w2 `constants`

##### Summary

XPC W2 Data (QT Private XPC W2)

<a name='T-CSLibrary-Structures-TagGeneralSelectedParms'></a>
## TagGeneralSelectedParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Selected tag parameters, configure this before any specific tag operation

<a name='M-CSLibrary-Structures-TagGeneralSelectedParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-TagGeneralSelectedParms-Mask'></a>
### Mask `constants`

##### Summary

A buffer that contains a left-justified bit array that represents 
that bit pattern to match (use epcMask, if you select EPC)

<a name='F-CSLibrary-Structures-TagGeneralSelectedParms-MaskLength'></a>
### MaskLength `constants`

##### Summary

epc mask length in bit (use epcMaskLength, if you select EPC)

<a name='F-CSLibrary-Structures-TagGeneralSelectedParms-MaskOffset'></a>
### MaskOffset `constants`

##### Summary

epc mask offset in bit (use epcMaskOffset, if you select EPC)

<a name='F-CSLibrary-Structures-TagGeneralSelectedParms-ParallelEncoding'></a>
### ParallelEncoding `constants`

##### Summary

UCODE 7 Parallel Encoding

<a name='F-CSLibrary-Structures-TagGeneralSelectedParms-bank'></a>
### bank `constants`

##### Summary

memory bank

<a name='F-CSLibrary-Structures-TagGeneralSelectedParms-epcMask'></a>
### epcMask `constants`

##### Summary

A buffer that contains a left-justified bit array that represents 
that bit pattern to match – i.e., the most significant bit of the 
bit array appears in the most-significant bit (i.e., bit 7) of the 
first byte of the buffer (i.e., mask[0]).  All bits beyond count 
are ignored.  For example, if the application wished to find 
tags with the following 16 bits 1011.1111.1010.0101, 
starting at offset 20 in the Electronic Product Code, then the 
fields would be set as follows: 
offset  = 20 
count   = 16 
mask[0] = 0xBF (1011.1111) 
mask[1] = 0xA5 (1010.0101)

<a name='F-CSLibrary-Structures-TagGeneralSelectedParms-epcMaskLength'></a>
### epcMaskLength `constants`

##### Summary

epc mask length in bit, e.g. epc = 0x3000, length = 4 * 8 = 32 bits, epc = 0x300, length = 3 * 8 = 24 bits

<a name='F-CSLibrary-Structures-TagGeneralSelectedParms-epcMaskOffset'></a>
### epcMaskOffset `constants`

##### Summary

epc mask offset in bit, note : if enable PC mask, this parameter is ignored.

<a name='F-CSLibrary-Structures-TagGeneralSelectedParms-flags'></a>
### flags `constants`

##### Summary

A mask that indicates current parameters enalbe or not.

<a name='T-CSLibrary-Structures-TagGroup'></a>
## TagGroup `type`

##### Namespace

CSLibrary.Structures

##### Summary

A class that specifies the tag group that will 
have a subsequent tag-protocol operation applied 
to it.  This parameter must not be NULL.

<a name='M-CSLibrary-Structures-TagGroup-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='M-CSLibrary-Structures-TagGroup-#ctor-CSLibrary-Constants-Selected,CSLibrary-Constants-Session,CSLibrary-Constants-SessionTarget-'></a>
### #ctor(selected,session,target) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| selected | [CSLibrary.Constants.Selected](#T-CSLibrary-Constants-Selected 'CSLibrary.Constants.Selected') |  |
| session | [CSLibrary.Constants.Session](#T-CSLibrary-Constants-Session 'CSLibrary.Constants.Session') |  |
| target | [CSLibrary.Constants.SessionTarget](#T-CSLibrary-Constants-SessionTarget 'CSLibrary.Constants.SessionTarget') |  |

<a name='F-CSLibrary-Structures-TagGroup-selected'></a>
### selected `constants`

##### Summary

Specifies the state of the selected (SL) flag for tags that will have 
the operation applied to them.

<a name='F-CSLibrary-Structures-TagGroup-session'></a>
### session `constants`

##### Summary

Specifies which inventory session flag (i.e., S0, S1, S2, or S3) 
will be matched against the inventory state specified by target.

<a name='F-CSLibrary-Structures-TagGroup-target'></a>
### target `constants`

##### Summary

Specifies the state of the inventory session flag (i.e., A or B), 
specified by session, for tags that will have the operation 
applied to them.

<a name='T-CSLibrary-Structures-TagInventoryParms'></a>
## TagInventoryParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

The ISO 18000-6C tag-inventory operation parameters

<a name='F-CSLibrary-Structures-TagInventoryParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no 
access password.

<a name='F-CSLibrary-Structures-TagInventoryParms-bank1'></a>
### bank1 `constants`

##### Summary

Memory bank 1

<a name='F-CSLibrary-Structures-TagInventoryParms-bank2'></a>
### bank2 `constants`

##### Summary

Memory bank 2

<a name='F-CSLibrary-Structures-TagInventoryParms-count1'></a>
### count1 `constants`

##### Summary

The number of 16-bit words that will be read. This field must be
between 1 and 31, inclusive.

<a name='F-CSLibrary-Structures-TagInventoryParms-count2'></a>
### count2 `constants`

##### Summary

The number of 16-bit words that will be read. This field must be
between 1 and 31, inclusive.

<a name='F-CSLibrary-Structures-TagInventoryParms-flags'></a>
### flags `constants`

##### Summary

Flag - Zero or combination of  Select or Post-Match

<a name='F-CSLibrary-Structures-TagInventoryParms-multibanks'></a>
### multibanks `constants`

##### Summary

number of bank to read after inventory

<a name='F-CSLibrary-Structures-TagInventoryParms-offset1'></a>
### offset1 `constants`

##### Summary

The offset, in the memory bank, of the first 16-bit word to read.

<a name='F-CSLibrary-Structures-TagInventoryParms-offset2'></a>
### offset2 `constants`

##### Summary

The offset, in the memory bank, of the first 16-bit word to read.

<a name='F-CSLibrary-Structures-TagInventoryParms-tagStopCount'></a>
### tagStopCount `constants`

##### Summary

The maximum number of tags to which the tag-protocol operation will be

applied.  If this number is zero, then the operation is applied to all

tags that match the selection, and optionally post-singulation, match

criteria.  If this number is non-zero, the antenna-port dwell-time and

inventory-round-count constraints still apply, however the operation

will be prematurely terminated if the maximum number of tags have the

tag-protocol operation applied to them.

<a name='T-CSLibrary-Structures-TagKillParms'></a>
## TagKillParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Tag Kill structure, configure this before do tag kill

<a name='M-CSLibrary-Structures-TagKillParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-TagKillParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no 
access password.

<a name='F-CSLibrary-Structures-TagKillParms-extCommand'></a>
### extCommand `constants`

##### Summary

Extended Kill command

<a name='F-CSLibrary-Structures-TagKillParms-flags'></a>
### flags `constants`

##### Summary

Flag - Zero or combination of  Select or Post-Match

<a name='F-CSLibrary-Structures-TagKillParms-killPassword'></a>
### killPassword `constants`

##### Summary

The kill password for the tags.  A value of zero indicates no 
kill password.

<a name='F-CSLibrary-Structures-TagKillParms-retryCount'></a>
### retryCount `constants`

##### Summary

Number of retries attemp to read. This field must be between 0 and 15, inclusive.

<a name='T-CSLibrary-Structures-TagLockParms'></a>
## TagLockParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Tag lock structure, configure this before do tag lock

<a name='M-CSLibrary-Structures-TagLockParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-TagLockParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no 
access password.

<a name='F-CSLibrary-Structures-TagLockParms-accessPasswordPermissions'></a>
### accessPasswordPermissions `constants`

##### Summary

The access permissions for the tag's access password.

<a name='F-CSLibrary-Structures-TagLockParms-epcMemoryBankPermissions'></a>
### epcMemoryBankPermissions `constants`

##### Summary

The access permissions for the tag's EPC memory bank.

<a name='F-CSLibrary-Structures-TagLockParms-flags'></a>
### flags `constants`

##### Summary

Flag - Zero or combination of  Select or Post-Match

<a name='F-CSLibrary-Structures-TagLockParms-killPasswordPermissions'></a>
### killPasswordPermissions `constants`

##### Summary

The access permissions for the tag's kill password.

<a name='F-CSLibrary-Structures-TagLockParms-length'></a>
### length `constants`

##### Summary

Structure size

<a name='F-CSLibrary-Structures-TagLockParms-retryCount'></a>
### retryCount `constants`

##### Summary

Number of retries attemp to read. This field must be between 0 and 15, inclusive.

<a name='F-CSLibrary-Structures-TagLockParms-tidMemoryBankPermissions'></a>
### tidMemoryBankPermissions `constants`

##### Summary

The access permissions for the tag's TID memory bank.

<a name='F-CSLibrary-Structures-TagLockParms-userMemoryBankPermissions'></a>
### userMemoryBankPermissions `constants`

##### Summary

The access permissions for the tag's user memory bank.

<a name='T-CSLibrary-Structures-TagPerm'></a>
## TagPerm `type`

##### Namespace

CSLibrary.Structures

##### Summary

A structure that contains the access permissions to be set for the tag.

<a name='F-CSLibrary-Structures-TagPerm-accessPasswordPermissions'></a>
### accessPasswordPermissions `constants`

##### Summary

The access permissions for the tag's access password.

<a name='F-CSLibrary-Structures-TagPerm-epcMemoryBankPermissions'></a>
### epcMemoryBankPermissions `constants`

##### Summary

The access permissions for the tag's EPC memory bank.

<a name='F-CSLibrary-Structures-TagPerm-killPasswordPermissions'></a>
### killPasswordPermissions `constants`

##### Summary

The access permissions for the tag's kill password.

<a name='F-CSLibrary-Structures-TagPerm-tidMemoryBankPermissions'></a>
### tidMemoryBankPermissions `constants`

##### Summary

The access permissions for the tag's TID memory bank.

<a name='F-CSLibrary-Structures-TagPerm-userMemoryBankPermissions'></a>
### userMemoryBankPermissions `constants`

##### Summary

The access permissions for the tag's user memory bank.

<a name='T-CSLibrary-Structures-TagPostMachParms'></a>
## TagPostMachParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Post match tag parameters, configure this before any specific tag operation

<a name='M-CSLibrary-Structures-TagPostMachParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-TagPostMachParms-count'></a>
### count `constants`

##### Summary

The number of bits in the mask.  A length of zero will cause 
all tags to match.  If (offset+count) falls beyond the end 
of the EPC, the tag is considered non-matching.  Valid 
values are 0 to 496, inclusive.

<a name='F-CSLibrary-Structures-TagPostMachParms-mask'></a>
### mask `constants`

##### Summary

A buffer that contains a left-justified bit array that represents 
that bit pattern to match – i.e., the most significant bit of the 
bit array appears in the most-significant bit (i.e., bit 7) of the 
first byte of the buffer (i.e., mask[0]).  All bits beyond count 
are ignored.  For example, if the application wished to find 
tags with the following 16 bits 1011.1111.1010.0101, 
starting at offset 20 in the Electronic Product Code, then the 
fields would be set as follows: 
offset  = 20 
count   = 16 
mask[0] = 0xBF (1011.1111) 
mask[1] = 0xA5 (1010.0101)

<a name='F-CSLibrary-Structures-TagPostMachParms-offset'></a>
### offset `constants`

##### Summary

The offset in bits, from the start of the Electronic Product 
Code (EPC), of the first bit that will be matched against the 
mask.  If offset falls beyond the end of EPC, the tag is 
considered non-matching.

<a name='F-CSLibrary-Structures-TagPostMachParms-toggleTarget'></a>
### toggleTarget `constants`

##### Summary

A flag that indicates if, after performing the inventory cycle for 
the specified target (i.e., A or B), if the target should be toggled 
(i.e., A to B or B to A) and another inventory cycle run.  A non-
zero value indicates that the target should be toggled.  A zero 
value indicates that the target should not be toggled.

<a name='T-CSLibrary-Structures-TagRangingParms'></a>
## TagRangingParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

this parms is same as inventory parms

<a name='F-CSLibrary-Structures-TagRangingParms-QTMode'></a>
### QTMode `constants`

##### Summary

Inventory Tag on QT Mode

<a name='F-CSLibrary-Structures-TagRangingParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no 
access password.

<a name='F-CSLibrary-Structures-TagRangingParms-bank1'></a>
### bank1 `constants`

##### Summary

Memory bank 1

<a name='F-CSLibrary-Structures-TagRangingParms-bank2'></a>
### bank2 `constants`

##### Summary

Memory bank 2

<a name='F-CSLibrary-Structures-TagRangingParms-count1'></a>
### count1 `constants`

##### Summary

The number of 16-bit words that will be read. This field must be
between 1 and 31, inclusive.

<a name='F-CSLibrary-Structures-TagRangingParms-count2'></a>
### count2 `constants`

##### Summary

The number of 16-bit words that will be read. This field must be
between 1 and 31, inclusive.

<a name='F-CSLibrary-Structures-TagRangingParms-fastid'></a>
### fastid `constants`

##### Summary

fast id mode.

<a name='F-CSLibrary-Structures-TagRangingParms-flags'></a>
### flags `constants`

##### Summary

Flag - Zero or combination of  Select or Post-Match

<a name='F-CSLibrary-Structures-TagRangingParms-focus'></a>
### focus `constants`

##### Summary

focus mode.

<a name='F-CSLibrary-Structures-TagRangingParms-multibanks'></a>
### multibanks `constants`

##### Summary

number of bank to read after inventory

<a name='F-CSLibrary-Structures-TagRangingParms-offset1'></a>
### offset1 `constants`

##### Summary

The offset, in the memory bank, of the first 16-bit word to read.

<a name='F-CSLibrary-Structures-TagRangingParms-offset2'></a>
### offset2 `constants`

##### Summary

The offset, in the memory bank, of the first 16-bit word to read.

<a name='F-CSLibrary-Structures-TagRangingParms-retry'></a>
### retry `constants`

##### Summary

Inventory Tag on QT Mode

<a name='F-CSLibrary-Structures-TagRangingParms-tagStopCount'></a>
### tagStopCount `constants`

##### Summary

The maximum number of tags to which the tag-protocol operation will be

applied.  If this number is zero, then the operation is applied to all

tags that match the selection, and optionally post-singulation, match

criteria.  If this number is non-zero, the antenna-port dwell-time and

inventory-round-count constraints still apply, however the operation

will be prematurely terminated if the maximum number of tags have the

tag-protocol operation applied to them.

<a name='T-CSLibrary-Structures-TagReadEpcParms'></a>
## TagReadEpcParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Read EPC structures, configure this before read current EPC

<a name='M-CSLibrary-Structures-TagReadEpcParms-#ctor'></a>
### #ctor() `constructor`

##### Summary



##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-TagReadEpcParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no 
access password.

<a name='F-CSLibrary-Structures-TagReadEpcParms-count'></a>
### count `constants`

##### Summary

The number of 16-bit words that will be read. This field must be
between 1 and 31, inclusive.

<a name='F-CSLibrary-Structures-TagReadEpcParms-m_epc'></a>
### m_epc `constants`

##### Summary

An EPC to the 16-bit values to write to the tag's memory bank.

<a name='F-CSLibrary-Structures-TagReadEpcParms-offset'></a>
### offset `constants`

##### Summary

The offset, in the memory bank, of the first 16-bit word to read.

<a name='F-CSLibrary-Structures-TagReadEpcParms-retryCount'></a>
### retryCount `constants`

##### Summary

Number of retrial will retry if write failure

<a name='P-CSLibrary-Structures-TagReadEpcParms-epc'></a>
### epc `property`

##### Summary

An EPC to the 16-bit values to write to the tag's memory bank.

<a name='T-CSLibrary-Structures-TagReadParms'></a>
## TagReadParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Read memory structures, configure this before read

<a name='M-CSLibrary-Structures-TagReadParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-TagReadParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no 
access password.

<a name='F-CSLibrary-Structures-TagReadParms-count'></a>
### count `constants`

##### Summary

The number of 16-bit words that will be read.

<a name='F-CSLibrary-Structures-TagReadParms-m_pData'></a>
### m_pData `constants`

##### Summary

An array to the 16-bit values to read from the tag's memory bank.

<a name='F-CSLibrary-Structures-TagReadParms-offset'></a>
### offset `constants`

##### Summary

The offset, in the memory bank, of the first 16-bit word to read.

<a name='F-CSLibrary-Structures-TagReadParms-retryCount'></a>
### retryCount `constants`

##### Summary

Number of retrial will retry if read failure

<a name='P-CSLibrary-Structures-TagReadParms-pData'></a>
### pData `property`

##### Summary

An array to the 16-bit values to read from the tag's memory bank.

<a name='T-CSLibrary-Structures-TagReadPcParms'></a>
## TagReadPcParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Read PC structures, configure this before read current PC

<a name='M-CSLibrary-Structures-TagReadPcParms-#ctor'></a>
### #ctor() `constructor`

##### Summary



##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-TagReadPcParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no 
access password.

<a name='F-CSLibrary-Structures-TagReadPcParms-m_pc'></a>
### m_pc `constants`

##### Summary

A PC to the 16-bit values to read from the tag's memory bank.

<a name='F-CSLibrary-Structures-TagReadPcParms-retryCount'></a>
### retryCount `constants`

##### Summary

Number of retrial will retry if read failure

<a name='P-CSLibrary-Structures-TagReadPcParms-pc'></a>
### pc `property`

##### Summary

A PC to the 16-bit values to read from the tag's memory bank.

<a name='T-CSLibrary-Structures-TagReadProtectParms'></a>
## TagReadProtectParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

TagReadProtectParms

<a name='F-CSLibrary-Structures-TagReadProtectParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no 
access password.

<a name='F-CSLibrary-Structures-TagReadProtectParms-flags'></a>
### flags `constants`

##### Summary

Flag - Zero or combination of  Select or Post-Match

<a name='F-CSLibrary-Structures-TagReadProtectParms-retryCount'></a>
### retryCount `constants`

##### Summary

Max retry count can't excess 15

<a name='T-CSLibrary-Structures-TagReadPwdParms'></a>
## TagReadPwdParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Read password structures, configure this before read current password

<a name='M-CSLibrary-Structures-TagReadPwdParms-#ctor'></a>
### #ctor() `constructor`

##### Summary



##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-TagReadPwdParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no 
access password.

<a name='F-CSLibrary-Structures-TagReadPwdParms-m_password'></a>
### m_password `constants`

##### Summary

A password to the 32-bit values to read from the tag's memory bank.

<a name='F-CSLibrary-Structures-TagReadPwdParms-retryCount'></a>
### retryCount `constants`

##### Summary

Number of retrial will retry if read failure

<a name='P-CSLibrary-Structures-TagReadPwdParms-password'></a>
### password `property`

##### Summary

A password to the 32-bit values to read from the tag's memory bank.

<a name='T-CSLibrary-Structures-TagReadTidParms'></a>
## TagReadTidParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Read TID structures, configure this before read current TID

<a name='M-CSLibrary-Structures-TagReadTidParms-#ctor'></a>
### #ctor() `constructor`

##### Summary



##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-TagReadTidParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no 
access password.

<a name='F-CSLibrary-Structures-TagReadTidParms-count'></a>
### count `constants`

##### Summary

The number of 16-bit words that will be read. This field must be
between 1 and 31, inclusive.

<a name='F-CSLibrary-Structures-TagReadTidParms-offset'></a>
### offset `constants`

##### Summary

The offset, in the memory bank, of the first 16-bit word to read.

<a name='F-CSLibrary-Structures-TagReadTidParms-pData'></a>
### pData `constants`

##### Summary

A pointer to the 16-bit values to read from the tag's memory bank.

<a name='F-CSLibrary-Structures-TagReadTidParms-retryCount'></a>
### retryCount `constants`

##### Summary

Number of retrial will retry if read failure

<a name='P-CSLibrary-Structures-TagReadTidParms-tid'></a>
### tid `property`

##### Summary

An array to the 16-bit values to read from tag's memory bank.

<a name='T-CSLibrary-Structures-TagReadUserParms'></a>
## TagReadUserParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Read User memory structures, configure this before read current User memory

<a name='M-CSLibrary-Structures-TagReadUserParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-TagReadUserParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no 
access password.

<a name='F-CSLibrary-Structures-TagReadUserParms-count'></a>
### count `constants`

##### Summary

The number of 16-bit words that will be read.

<a name='F-CSLibrary-Structures-TagReadUserParms-m_pData'></a>
### m_pData `constants`

##### Summary

An array to the 16-bit values to read from the tag's memory bank.

<a name='F-CSLibrary-Structures-TagReadUserParms-offset'></a>
### offset `constants`

##### Summary

The offset, in the memory bank, of the first 16-bit word to read.

<a name='F-CSLibrary-Structures-TagReadUserParms-retryCount'></a>
### retryCount `constants`

##### Summary

Number of retrial will retry if read failure

<a name='P-CSLibrary-Structures-TagReadUserParms-pData'></a>
### pData `property`

##### Summary

An array to the 16-bit values to read from the tag's memory bank.

<a name='T-CSLibrary-Structures-TagSearchingParms'></a>
## TagSearchingParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

search one tag parms

<a name='F-CSLibrary-Structures-TagSearchingParms-avgRssi'></a>
### avgRssi `constants`

##### Summary

averaging the RSSI value during search

<a name='T-CSLibrary-Structures-TagSelectedParms'></a>
## TagSelectedParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Selected tag parameters, configure this before any specific tag operation

<a name='M-CSLibrary-Structures-TagSelectedParms-#ctor'></a>
### #ctor() `constructor`

##### Summary

constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-TagSelectedParms-Mask'></a>
### Mask `constants`

##### Summary

A buffer that contains a left-justified bit array that represents 
that bit pattern to match (use epcMask, if you select EPC)

<a name='F-CSLibrary-Structures-TagSelectedParms-MaskLength'></a>
### MaskLength `constants`

##### Summary

epc mask length in bit (use epcMaskLength, if you select EPC)

<a name='F-CSLibrary-Structures-TagSelectedParms-MaskOffset'></a>
### MaskOffset `constants`

##### Summary

epc mask offset in bit (use epcMaskOffset, if you select EPC)

<a name='F-CSLibrary-Structures-TagSelectedParms-ParallelEncoding'></a>
### ParallelEncoding `constants`

##### Summary

UCODE 7 Parallel Encoding

<a name='F-CSLibrary-Structures-TagSelectedParms-Qvalue'></a>
### Qvalue `constants`

##### Summary

Qvalue

<a name='F-CSLibrary-Structures-TagSelectedParms-bank'></a>
### bank `constants`

##### Summary

memory bank

<a name='F-CSLibrary-Structures-TagSelectedParms-epcMask'></a>
### epcMask `constants`

##### Summary

A buffer that contains a left-justified bit array that represents 
that bit pattern to match – i.e., the most significant bit of the 
bit array appears in the most-significant bit (i.e., bit 7) of the 
first byte of the buffer (i.e., mask[0]).  All bits beyond count 
are ignored.  For example, if the application wished to find 
tags with the following 16 bits 1011.1111.1010.0101, 
starting at offset 20 in the Electronic Product Code, then the 
fields would be set as follows: 
offset  = 20 
count   = 16 
mask[0] = 0xBF (1011.1111) 
mask[1] = 0xA5 (1010.0101)

<a name='F-CSLibrary-Structures-TagSelectedParms-epcMaskLength'></a>
### epcMaskLength `constants`

##### Summary

epc mask length in bit, e.g. epc = 0x3000, length = 4 * 8 = 32 bits, epc = 0x300, length = 3 * 8 = 24 bits

<a name='F-CSLibrary-Structures-TagSelectedParms-epcMaskOffset'></a>
### epcMaskOffset `constants`

##### Summary

epc mask offset in bit, note : if enable PC mask, this parameter is ignored.

<a name='F-CSLibrary-Structures-TagSelectedParms-flags'></a>
### flags `constants`

##### Summary

A mask that indicates current parameters enalbe or not.

<a name='T-CSLibrary-Structures-TagWriteEpcParms'></a>
## TagWriteEpcParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Write EPC structures, configure this before write new EPC value

<a name='M-CSLibrary-Structures-TagWriteEpcParms-#ctor'></a>
### #ctor() `constructor`

##### Summary



##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-TagWriteEpcParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no 
access password.

<a name='F-CSLibrary-Structures-TagWriteEpcParms-count'></a>
### count `constants`

##### Summary

The number of 16-bit words that will be written.  This field must be
between 1 and 31, inclusive.

<a name='F-CSLibrary-Structures-TagWriteEpcParms-epc'></a>
### epc `constants`

##### Summary

A new epc to the 16-bit values to write to the tag's memory bank.

<a name='F-CSLibrary-Structures-TagWriteEpcParms-offset'></a>
### offset `constants`

##### Summary

The offset, in the memory bank, of the first 16-bit word to write.

<a name='F-CSLibrary-Structures-TagWriteEpcParms-retryCount'></a>
### retryCount `constants`

##### Summary

Number of retrial will retry if write failure (Process Retry / Library Retry)

<a name='F-CSLibrary-Structures-TagWriteEpcParms-writeRetryCount'></a>
### writeRetryCount `constants`

##### Summary

Number of retrial will retry if write failure (Write Retry / Firmware Retry)

<a name='T-CSLibrary-Structures-TagWriteParms'></a>
## TagWriteParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Write structures, configure this before write

<a name='F-CSLibrary-Structures-TagWriteParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no 
access password.

<a name='F-CSLibrary-Structures-TagWriteParms-count'></a>
### count `constants`

##### Summary

The number of 16-bit words that will be written.

<a name='F-CSLibrary-Structures-TagWriteParms-flags'></a>
### flags `constants`

##### Summary

Flag - Normal or combination of  Select or Post-Match

<a name='F-CSLibrary-Structures-TagWriteParms-offset'></a>
### offset `constants`

##### Summary

The offset, in the memory bank, of the first 16-bit word to write.

<a name='F-CSLibrary-Structures-TagWriteParms-pData'></a>
### pData `constants`

##### Summary

A array to the 16-bit values to write to the tag's memory bank.

<a name='F-CSLibrary-Structures-TagWriteParms-retryCount'></a>
### retryCount `constants`

##### Summary

Number of retrial will retry if write failure (Process Retry / Library Retry)

<a name='F-CSLibrary-Structures-TagWriteParms-writeRetryCount'></a>
### writeRetryCount `constants`

##### Summary

Number of retrial will retry if write failure (Write Retry / Firmware Retry)

<a name='T-CSLibrary-Structures-TagWritePcParms'></a>
## TagWritePcParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Write PC structures, configure this before write new PC value

<a name='F-CSLibrary-Structures-TagWritePcParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no 
access password.

<a name='F-CSLibrary-Structures-TagWritePcParms-flags'></a>
### flags `constants`

##### Summary

Flag - Normal or combination of  Select or Post-Match

<a name='F-CSLibrary-Structures-TagWritePcParms-pc'></a>
### pc `constants`

##### Summary

A new pc to the 16-bit values to write to the tag's memory bank.

<a name='F-CSLibrary-Structures-TagWritePcParms-retryCount'></a>
### retryCount `constants`

##### Summary

Number of retrial will retry if write failure (Process Retry / Library Retry)

<a name='F-CSLibrary-Structures-TagWritePcParms-writeRetryCount'></a>
### writeRetryCount `constants`

##### Summary

Number of retrial will retry if write failure (Write Retry / Firmware Retry)

<a name='T-CSLibrary-Structures-TagWritePwdParms'></a>
## TagWritePwdParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Write password structures, configure this before write new password value

<a name='F-CSLibrary-Structures-TagWritePwdParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no 
access password.

<a name='F-CSLibrary-Structures-TagWritePwdParms-flags'></a>
### flags `constants`

##### Summary

Flag - Normal or combination of  Select or Post-Match

<a name='F-CSLibrary-Structures-TagWritePwdParms-password'></a>
### password `constants`

##### Summary

A new password to the 32-bit values to write to the tag's memory bank.

<a name='F-CSLibrary-Structures-TagWritePwdParms-retryCount'></a>
### retryCount `constants`

##### Summary

Number of retrial will retry if write failure (Process Retry / Library Retry)

<a name='F-CSLibrary-Structures-TagWritePwdParms-writeRetryCount'></a>
### writeRetryCount `constants`

##### Summary

Number of retrial will retry if write failure (Write Retry / Firmware Retry)

<a name='T-CSLibrary-Structures-TagWriteUserParms'></a>
## TagWriteUserParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Write User structures, configure this before write new user data

<a name='F-CSLibrary-Structures-TagWriteUserParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no 
access password.

<a name='F-CSLibrary-Structures-TagWriteUserParms-count'></a>
### count `constants`

##### Summary

The number of 16-bit words that will be written.

<a name='F-CSLibrary-Structures-TagWriteUserParms-flags'></a>
### flags `constants`

##### Summary

Flag - Normal or combination of  Select or Post-Match

<a name='F-CSLibrary-Structures-TagWriteUserParms-offset'></a>
### offset `constants`

##### Summary

The offset, in the memory bank, of the first 16-bit word to write.

<a name='F-CSLibrary-Structures-TagWriteUserParms-pData'></a>
### pData `constants`

##### Summary

A array to the 16-bit values to write to the tag's memory bank.

<a name='F-CSLibrary-Structures-TagWriteUserParms-retryCount'></a>
### retryCount `constants`

##### Summary

Number of retrial will retry if write failure (Process Retry / Library Retry)

<a name='F-CSLibrary-Structures-TagWriteUserParms-writeRetryCount'></a>
### writeRetryCount `constants`

##### Summary

Number of retrial will retry if write failure (Write Retry / Firmware Retry)

<a name='T-CSLibrary-Constants-Target'></a>
## Target `type`

##### Namespace

CSLibrary.Constants

##### Summary

Specifies what flag, selected (i.e., SL) or one of the four inventory 
flags (i.e., S0, S1, S2, or S3), will be modified by the action.

<a name='F-CSLibrary-Constants-Target-S0'></a>
### S0 `constants`

##### Summary

Tag energized : Indefinite
Tag not energized : None

<a name='F-CSLibrary-Constants-Target-S1'></a>
### S1 `constants`

##### Summary

Tag energized :
    Norminal temperature range : 5s > persistence > 500ms
    Exttended temperature range : Not specified
Tag not energized :
    Norminal temperature range : 5s > persistence > 500ms
    Exttended temperature range : Not specified

<a name='F-CSLibrary-Constants-Target-S2'></a>
### S2 `constants`

##### Summary

Tag energized : Indefinite
Tag not energized :
    Norminal temperature range : persistence > 2s
    Exttended temperature range : Not specified

<a name='F-CSLibrary-Constants-Target-S3'></a>
### S3 `constants`

##### Summary

Tag energized : Indefinite
Tag not energized :
    Norminal temperature range : persistence > 2s
    Exttended temperature range : Not specified

<a name='F-CSLibrary-Constants-Target-SELECTED'></a>
### SELECTED `constants`

##### Summary

Tag energized : Indefinite
Tag not energized :
    Norminal temperature range : persistence > 2s
    Exttended temperature range : Not specified

<a name='F-CSLibrary-Constants-Target-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary



<a name='T-CSLibrary-Structures-TemperatureParms'></a>
## TemperatureParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Temperature Parms

<a name='F-CSLibrary-Structures-TemperatureParms-amb'></a>
### amb `constants`

##### Summary

Ambient Temperature

<a name='F-CSLibrary-Structures-TemperatureParms-pwramp'></a>
### pwramp `constants`

##### Summary

Power Amp Temperature

<a name='F-CSLibrary-Structures-TemperatureParms-xcvr'></a>
### xcvr `constants`

##### Summary

Transciever Temperature

<a name='T-CSLibrary-Structures-ThresholdTemperatureParms'></a>
## ThresholdTemperatureParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

ThresholdTemperatureParms

<a name='F-CSLibrary-Structures-ThresholdTemperatureParms-amb'></a>
### amb `constants`

##### Summary

Ambient Temperature

<a name='F-CSLibrary-Structures-ThresholdTemperatureParms-delta'></a>
### delta `constants`

##### Summary

pa-delta

<a name='F-CSLibrary-Structures-ThresholdTemperatureParms-pwramp'></a>
### pwramp `constants`

##### Summary

Power Amp Temperature

<a name='F-CSLibrary-Structures-ThresholdTemperatureParms-xcvr'></a>
### xcvr `constants`

##### Summary

Transciever Temperature

<a name='T-CSLibrary-Net-TimeEvent'></a>
## TimeEvent `type`

##### Namespace

CSLibrary.Net

##### Summary

Time Event

<a name='F-CSLibrary-Net-TimeEvent-days'></a>
### days `constants`

##### Summary

Days

<a name='F-CSLibrary-Net-TimeEvent-hours'></a>
### hours `constants`

##### Summary

Hours

<a name='F-CSLibrary-Net-TimeEvent-minutes'></a>
### minutes `constants`

##### Summary

Minutes

<a name='F-CSLibrary-Net-TimeEvent-name'></a>
### name `constants`

##### Summary

Event name

<a name='F-CSLibrary-Net-TimeEvent-seconds'></a>
### seconds `constants`

##### Summary

Seconds

<a name='T-CSLibrary-Net-UpdatePercentArgs'></a>
## UpdatePercentArgs `type`

##### Namespace

CSLibrary.Net

##### Summary

UpdatePercentArgs

<a name='M-CSLibrary-Net-UpdatePercentArgs-#ctor-System-Int32-'></a>
### #ctor(percent) `constructor`

##### Summary

Constrcutor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| percent | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |

<a name='P-CSLibrary-Net-UpdatePercentArgs-Percent'></a>
### Percent `property`

##### Summary

Total update Percent

<a name='T-CSLibrary-Net-UpdateResult'></a>
## UpdateResult `type`

##### Namespace

CSLibrary.Net

##### Summary

Update Result

<a name='F-CSLibrary-Net-UpdateResult-FAIL'></a>
### FAIL `constants`

##### Summary

Update fail

<a name='F-CSLibrary-Net-UpdateResult-SUCCESS'></a>
### SUCCESS `constants`

##### Summary

Update success

<a name='T-CSLibrary-Net-UpdateResultArgs'></a>
## UpdateResultArgs `type`

##### Namespace

CSLibrary.Net

##### Summary

UpdateResultArgs

<a name='M-CSLibrary-Net-UpdateResultArgs-#ctor-CSLibrary-Net-UpdateResult-'></a>
### #ctor(Result) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| Result | [CSLibrary.Net.UpdateResult](#T-CSLibrary-Net-UpdateResult 'CSLibrary.Net.UpdateResult') |  |

<a name='P-CSLibrary-Net-UpdateResultArgs-Result'></a>
### Result `property`

##### Summary

Update Result

<a name='T-CSLibrary-Structures-Version'></a>
## Version `type`

##### Namespace

CSLibrary.Structures

##### Summary

Version Structure

<a name='M-CSLibrary-Structures-Version-#ctor'></a>
### #ctor() `constructor`

##### Summary

Constructor

##### Parameters

This constructor has no parameters.

<a name='F-CSLibrary-Structures-Version-major'></a>
### major `constants`

##### Summary

Major

<a name='F-CSLibrary-Structures-Version-minor'></a>
### minor `constants`

##### Summary

Minor

<a name='F-CSLibrary-Structures-Version-patch'></a>
### patch `constants`

##### Summary

Patch

<a name='M-CSLibrary-Structures-Version-ToString'></a>
### ToString() `method`

##### Summary

Convert Version to string

##### Returns



##### Parameters

This method has no parameters.

<a name='T-CSLibrary-Win32'></a>
## Win32 `type`

##### Namespace

CSLibrary

<a name='M-CSLibrary-Win32-GetExitCodeThread-System-UInt32,System-UInt32@-'></a>
### GetExitCodeThread(dest,src,size) `method`

##### Summary

Unsafe GetExitCodeThread

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| dest | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| src | [System.UInt32@](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32@ 'System.UInt32@') |  |

<a name='M-CSLibrary-Win32-_lrotl-System-UInt32,System-UInt32-'></a>
### _lrotl(value,shift) `method`

##### Summary



##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| value | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| shift | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |

<a name='M-CSLibrary-Win32-_lrotr-System-UInt32,System-UInt32-'></a>
### _lrotr(value,shift) `method`

##### Summary



##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| value | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |
| shift | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') |  |

<a name='M-CSLibrary-Win32-memcmp-System-Byte[],System-Byte[],System-Int32-'></a>
### memcmp(src1,src2,size) `method`

##### Summary

Unsafe memory Compare

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| src1 | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| src2 | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| size | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |

<a name='T-CSLibrary-Structures-WriteParms'></a>
## WriteParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

A tag-write command allows an application to write one or more 16-bit words to 
the specified memory bank of the ISO 18000-6C tags of interest.  The data 
returned from the tag write will adhere to the format specified in [REC].  An 
application is given some flexibility in the execution of a write to an ISO 18000-
6C tag.

<a name='M-CSLibrary-Structures-WriteParms-#ctor-System-Boolean-'></a>
### #ctor(initial) `constructor`

##### Summary

Initial Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| initial | [System.Boolean](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Boolean 'System.Boolean') |  |

<a name='F-CSLibrary-Structures-WriteParms-accessPassword'></a>
### accessPassword `constants`

##### Summary

The access password for the tags.  A value of zero indicates no access 
password.

<a name='F-CSLibrary-Structures-WriteParms-common'></a>
### common `constants`

##### Summary

The common tag-protocol operation parameters.

<a name='F-CSLibrary-Structures-WriteParms-length'></a>
### length `constants`

##### Summary

Structure size

<a name='F-CSLibrary-Structures-WriteParms-writeRandomParms'></a>
### writeRandomParms `constants`

##### Summary

The write parameters.  This is a discriminated union, with writeType 
as the discriminator (i.e., determines which structure within the union is 
used). .  The following table lists the valid values for the writeType 
field and their corresponding structures within this union.

<a name='F-CSLibrary-Structures-WriteParms-writeSequentialParms'></a>
### writeSequentialParms `constants`

##### Summary

The write parameters.  This is a discriminated union, with writeType 
as the discriminator (i.e., determines which structure within the union is 
used). .  The following table lists the valid values for the writeType 
field and their corresponding structures within this union.

<a name='F-CSLibrary-Structures-WriteParms-writeType'></a>
### writeType `constants`

##### Summary

The type of write that will be performed – i.e., sequential or random.  
The value of this field determines which of the structures within 
parameters contains the write parameters.

<a name='T-CSLibrary-Structures-WriteRandomParms'></a>
## WriteRandomParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Write  one  or  more  16-bit  words  to  potentially  non-contiguous  16-bit 
offsets to one of the tag's memory banks.  This can be thought of as a 
random-access write to a single tag memory bank.

<a name='M-CSLibrary-Structures-WriteRandomParms-#ctor-CSLibrary-Constants-MemoryBank,System-UInt16,System-UInt16[],System-UInt16[]-'></a>
### #ctor(bnk,count,offset,data) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| bnk | [CSLibrary.Constants.MemoryBank](#T-CSLibrary-Constants-MemoryBank 'CSLibrary.Constants.MemoryBank') | The memory bank from which to write.  Valid values are: 
MemoryBank.RESERVED 
MemoryBank.EPC  
MemoryBank.TID 
MemoryBank.USER |
| count | [System.UInt16](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16 'System.UInt16') | The number of 16-bit words to be written to the tag's specified 
memory bank.  For version 1.1 of the RFID Reader Library, this 
parameter must contain a value between 1 and 8, inclusive. |
| offset | [System.UInt16[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16[] 'System.UInt16[]') | The offset of the first 16-bit word, where zero is the first 16-bit 
word in the memory bank, to write in the specified memory bank. |
| data | [System.UInt16[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16[] 'System.UInt16[]') | A buffer of count 16-bit values to be written 
sequentially to the tag's specified memory bank.  The high-order 
byte of pData[n] will be written to the tag's memory-bank byte at 
16-bit offset (offset+n).  The low-order byte will be written to the 
next byte.  For example, if offset is 2 and pData[0] is 0x1122, 
then the tag-memory byte at 16-bit offset 2 (byte offset 4) will have 
0x11 written to it and the next byte (byte offset 5) will have 0x22 
written to it.  This field must not be NULL. |

<a name='F-CSLibrary-Structures-WriteRandomParms-bank'></a>
### bank `constants`

##### Summary

The memory bank from which to write.  Valid values are: 
MemoryBank.RESERVED 
MemoryBank.EPC  
MemoryBank.TID 
MemoryBank.USER

<a name='F-CSLibrary-Structures-WriteRandomParms-count'></a>
### count `constants`

##### Summary

The number of 16-bit words to be written to the tag's specified 
memory bank.  For version 1.1 of the RFID Reader Library, this 
parameter must contain a value between 1 and 8, inclusive.

<a name='F-CSLibrary-Structures-WriteRandomParms-length'></a>
### length `constants`

##### Summary

The length of this structure.

<a name='F-CSLibrary-Structures-WriteRandomParms-pData'></a>
### pData `constants`

##### Summary

A buffer of count 16-bit values to be written to the tag's 
specified memory bank.  The high-order byte of pData[n] will be 
written to the tag's memory-bank byte at pOffset[n].  The low-order 
byte will be written to the next byte.  For example, if pOffset[n] is 2 
and pData[n] is 0x1122, then the tag-memory byte at 16-bit offset 2 
(byte offset 4) will have 0x11 written to it and the next byte (byte offset 
5) will have 0x22 written to it.  This field must not be NULL.

<a name='F-CSLibrary-Structures-WriteRandomParms-pOffset'></a>
### pOffset `constants`

##### Summary

An array of count 16-bit values that specify 16-bit tag-
memory-bank offsets, with zero being the first 16-bit word in the 
memory bank, where the corresponding 16-bit words in the pData 
array will be written.  i.e., the 16-bit word in pData[n] will be written to 
the 16-bit tag-memory-bank offset contained in pOffset[n].  This 
field must not be NULL.

<a name='F-CSLibrary-Structures-WriteRandomParms-reserved'></a>
### reserved `constants`

##### Summary

Reserved for future use.  Set to zero.

<a name='M-CSLibrary-Structures-WriteRandomParms-Dispose'></a>
### Dispose() `method`

##### Summary

Release all resources

##### Parameters

This method has no parameters.

<a name='T-CSLibrary-Structures-WriteSequentialParms'></a>
## WriteSequentialParms `type`

##### Namespace

CSLibrary.Structures

##### Summary

Write, beginning at the specified 16-bit offset, a contiguous set of one or 
more 16-bit words to one of the tag's memory banks.

<a name='M-CSLibrary-Structures-WriteSequentialParms-#ctor-CSLibrary-Constants-MemoryBank,System-UInt16,System-UInt16,System-UInt16[]-'></a>
### #ctor(bnk,count,offset,data) `constructor`

##### Summary

Constructor

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| bnk | [CSLibrary.Constants.MemoryBank](#T-CSLibrary-Constants-MemoryBank 'CSLibrary.Constants.MemoryBank') | The memory bank from which to write.  Valid values are: 
MemoryBank.RESERVED 
MemoryBank.EPC  
MemoryBank.TID 
MemoryBank.USER |
| count | [System.UInt16](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16 'System.UInt16') | The number of 16-bit words to be written to the tag's specified 
memory bank.  For version 1.1 of the RFID Reader Library, this 
parameter must contain a value between 1 and 8, inclusive. |
| offset | [System.UInt16](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16 'System.UInt16') | The offset of the first 16-bit word, where zero is the first 16-bit 
word in the memory bank, to write in the specified memory bank. |
| data | [System.UInt16[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16[] 'System.UInt16[]') | A buffer of count 16-bit values to be written 
sequentially to the tag's specified memory bank.  The high-order 
byte of pData[n] will be written to the tag's memory-bank byte at 
16-bit offset (offset+n).  The low-order byte will be written to the 
next byte.  For example, if offset is 2 and pData[0] is 0x1122, 
then the tag-memory byte at 16-bit offset 2 (byte offset 4) will have 
0x11 written to it and the next byte (byte offset 5) will have 0x22 
written to it.  This field must not be NULL. |

<a name='F-CSLibrary-Structures-WriteSequentialParms-bank'></a>
### bank `constants`

##### Summary

The memory bank from which to write.  Valid values are: 
MemoryBank.RESERVED 
MemoryBank.EPC  
MemoryBank.TID 
MemoryBank.USER

<a name='F-CSLibrary-Structures-WriteSequentialParms-count'></a>
### count `constants`

##### Summary

The number of 16-bit words to be written to the tag's specified 
memory bank.  For version 1.1 of the RFID Reader Library, this 
parameter must contain a value between 1 and 8, inclusive.

<a name='F-CSLibrary-Structures-WriteSequentialParms-length'></a>
### length `constants`

##### Summary

The length of this structure.

<a name='F-CSLibrary-Structures-WriteSequentialParms-offset'></a>
### offset `constants`

##### Summary

The offset of the first 16-bit word, where zero is the first 16-bit 
word in the memory bank, to write in the specified memory bank.

<a name='F-CSLibrary-Structures-WriteSequentialParms-pData'></a>
### pData `constants`

##### Summary

A buffer of count 16-bit values to be written 
sequentially to the tag's specified memory bank.  The high-order 
byte of pData[n] will be written to the tag's memory-bank byte at 
16-bit offset (offset+n).  The low-order byte will be written to the 
next byte.  For example, if offset is 2 and pData[0] is 0x1122, 
then the tag-memory byte at 16-bit offset 2 (byte offset 4) will have 
0x11 written to it and the next byte (byte offset 5) will have 0x22 
written to it.  This field must not be NULL.

<a name='F-CSLibrary-Structures-WriteSequentialParms-reserved'></a>
### reserved `constants`

##### Summary

Reserved for future use.  Set to zero.

<a name='M-CSLibrary-Structures-WriteSequentialParms-Dispose'></a>
### Dispose() `method`

##### Summary

Release all resources

##### Parameters

This method has no parameters.

<a name='T-CSLibrary-Constants-WriteType'></a>
## WriteType `type`

##### Namespace

CSLibrary.Constants

##### Summary

The type of write that will be performed – i.e., sequential or random.  
The value of this field determines which of the structures within 
parameters contains the write parameters.

<a name='F-CSLibrary-Constants-WriteType-RANDOM'></a>
### RANDOM `constants`

##### Summary

Write tag method by random

<a name='F-CSLibrary-Constants-WriteType-SEQUENTIAL'></a>
### SEQUENTIAL `constants`

##### Summary

Write tag method by sequential

<a name='F-CSLibrary-Constants-WriteType-UNKNOWN'></a>
### UNKNOWN `constants`

##### Summary

Unknown type

<a name='T-CSLibrary-Text-oldHex'></a>
## oldHex `type`

##### Namespace

CSLibrary.Text

##### Summary

Summary description for HexEncoding.

<a name='M-CSLibrary-Text-oldHex-Compare-System-String,System-String-'></a>
### Compare(source,target) `method`

##### Summary

Compare Hex String, ie, source = "11ffaa", target = "11FFaa", it will return true

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| source | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | Source Hex string |
| target | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | Target comparing Hex string |

<a name='M-CSLibrary-Text-oldHex-Compare-System-Byte[],System-Byte[]-'></a>
### Compare(source,target) `method`

##### Summary

Compare Hex

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| source | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | Source Hex |
| target | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | Target comparing Hex |

<a name='M-CSLibrary-Text-oldHex-Compare-System-Byte[],System-Byte[],System-Int32-'></a>
### Compare(source,target,size) `method`

##### Summary

Compare Hex

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| source | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | Source Hex |
| target | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | Target comparing Hex |
| size | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') | Size to compare |

<a name='M-CSLibrary-Text-oldHex-Compare``1-``0[],``0[]-'></a>
### Compare\`\`1(a,b) `method`

##### Summary

Generic compare two array

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| a | [\`\`0[]](#T-``0[] '``0[]') |  |
| b | [\`\`0[]](#T-``0[] '``0[]') |  |

##### Generic Types

| Name | Description |
| ---- | ----------- |
| T | Type of array |

<a name='M-CSLibrary-Text-oldHex-Copy-System-Byte[],System-Byte[],System-Int32-'></a>
### Copy(src,dst,count) `method`

##### Summary

Copy One array to another array

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| src | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| dst | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| count | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |

<a name='M-CSLibrary-Text-oldHex-Copy-System-Byte[],System-Byte[],System-Int32,System-Int32-'></a>
### Copy(src,dst,dstIndex,count) `method`

##### Summary

Copy One array to another array

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| src | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| dst | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| dstIndex | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |
| count | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |

<a name='M-CSLibrary-Text-oldHex-Copy-System-Byte[],System-Int32,System-Byte[],System-Int32,System-Int32-'></a>
### Copy(src,srcIndex,dst,dstIndex,count) `method`

##### Summary

Copy One array to another array

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| src | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| srcIndex | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |
| dst | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| dstIndex | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |
| count | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |

<a name='M-CSLibrary-Text-oldHex-GenPostMatchMask-System-String-'></a>
### GenPostMatchMask(hexString) `method`

##### Summary

Creates a byte array from the hexadecimal string. Each two characters are combined
to create one byte. First two hexadecimal characters become first byte in returned array.
Non-hexadecimal characters are ignored.

##### Returns

byte array, in the same left-to-right order as the hexString

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| hexString | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | string to convert to byte array |

<a name='M-CSLibrary-Text-oldHex-GenSelectMask-System-String-'></a>
### GenSelectMask(hexString) `method`

##### Summary

Creates a byte array from the hexadecimal string. Each two characters are combined
to create one byte. First two hexadecimal characters become first byte in returned array.
Non-hexadecimal characters are ignored.

##### Returns

byte array, in the same left-to-right order as the hexString

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| hexString | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | string to convert to byte array |

<a name='M-CSLibrary-Text-oldHex-GetBitCount-System-String-'></a>
### GetBitCount(hexString) `method`

##### Summary

Get bit length from string

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| hexString | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |  |

<a name='M-CSLibrary-Text-oldHex-GetBitCount-System-Byte[]-'></a>
### GetBitCount(bytes) `method`

##### Summary

Get bit length from string

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| bytes | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |

<a name='M-CSLibrary-Text-oldHex-GetByteCount-System-String-'></a>
### GetByteCount(hexString) `method`

##### Summary

GetByteCount

##### Returns

Number of Byte Count

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| hexString | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | Input Hex String |

<a name='M-CSLibrary-Text-oldHex-GetWordCount-System-String-'></a>
### GetWordCount(hexString) `method`

##### Summary

Get Word length from string

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| hexString | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |  |

<a name='M-CSLibrary-Text-oldHex-HexToByte-System-String-'></a>
### HexToByte(hex) `method`

##### Summary

Converts 1 or 2 character string into equivalant byte value

##### Returns

byte

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| hex | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | 1 or 2 character string |

<a name='M-CSLibrary-Text-oldHex-IsHexFormat-System-String-'></a>
### IsHexFormat(hexString) `method`

##### Summary

Determines if given string is in proper hexadecimal string format

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| hexString | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |  |

<a name='M-CSLibrary-Text-oldHex-ToByte-System-String-'></a>
### ToByte(hexString) `method`

##### Summary

return a byte from string

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| hexString | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |  |

<a name='M-CSLibrary-Text-oldHex-ToBytes-System-String-'></a>
### ToBytes(hexString) `method`

##### Summary

Creates a byte array from the hexadecimal string. Each two characters are combined
to create one byte. First two hexadecimal characters become first byte in returned array.
Non-hexadecimal characters are ignored.

##### Returns

byte array, in the same left-to-right order as the hexString

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| hexString | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | string to convert to byte array |

<a name='M-CSLibrary-Text-oldHex-ToBytes-System-UInt16[]-'></a>
### ToBytes(data) `method`

##### Summary

Convent ushort array to byte array

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| data | [System.UInt16[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16[] 'System.UInt16[]') |  |

<a name='M-CSLibrary-Text-oldHex-ToInt16-System-Byte[],System-Int32-'></a>
### ToInt16(buffer,offset) `method`

##### Summary

Convert 2 Bytes to one short

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| buffer | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| offset | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |

<a name='M-CSLibrary-Text-oldHex-ToString-System-Byte[]-'></a>
### ToString(bytes) `method`

##### Summary

Byte to String Conversion

##### Returns

Return a String

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| bytes | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | Input Byte Array |

<a name='M-CSLibrary-Text-oldHex-ToString-System-Byte[],System-UInt32,System-UInt32-'></a>
### ToString(bytes,offset,count) `method`

##### Summary

Byte to String Conversion

##### Returns

Return a String

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| bytes | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') | Input Byte Array |
| offset | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Start offset |
| count | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Number of Count to converse |

<a name='M-CSLibrary-Text-oldHex-ToString-System-UInt16[]-'></a>
### ToString(data) `method`

##### Summary

ushort to String Conversion

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| data | [System.UInt16[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16[] 'System.UInt16[]') |  |

<a name='M-CSLibrary-Text-oldHex-ToString-System-UInt16[],System-UInt32,System-UInt32-'></a>
### ToString(data,offset,count) `method`

##### Summary

ushort to String Conversion

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| data | [System.UInt16[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt16[] 'System.UInt16[]') | source data |
| offset | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Start offset |
| count | [System.UInt32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.UInt32 'System.UInt32') | Number of Count to converse |

<a name='M-CSLibrary-Text-oldHex-ToUInt16-System-Byte[],System-Int32-'></a>
### ToUInt16(buffer,offset) `method`

##### Summary

Convert 2 Bytes to one short

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| buffer | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| offset | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |

<a name='M-CSLibrary-Text-oldHex-ToUInt32-System-Byte[],System-Int32-'></a>
### ToUInt32(buffer,offset) `method`

##### Summary

Convert 4 Bytes to one uint32

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| buffer | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| offset | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |

<a name='M-CSLibrary-Text-oldHex-ToUInt32-System-String-'></a>
### ToUInt32(hexString) `method`

##### Summary

Convert string to one uint32

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| hexString | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |  |

<a name='M-CSLibrary-Text-oldHex-ToUInt64-System-Byte[],System-Int32-'></a>
### ToUInt64(buffer,offset) `method`

##### Summary

Convert 4 bytes to long

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| buffer | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |
| offset | [System.Int32](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Int32 'System.Int32') |  |

<a name='M-CSLibrary-Text-oldHex-ToUshort-System-String-'></a>
### ToUshort(str) `method`

##### Summary

return ushort from byte string

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| str | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |  |

<a name='M-CSLibrary-Text-oldHex-ToUshorts-System-Byte[]-'></a>
### ToUshorts(Input) `method`

##### Summary

return ushort array from byte array

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| Input | [System.Byte[]](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Byte[] 'System.Byte[]') |  |

<a name='M-CSLibrary-Text-oldHex-ToUshorts-System-String-'></a>
### ToUshorts(Input) `method`

##### Summary

return ushort array from string input

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| Input | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |  |
