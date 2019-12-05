# prometheus

Following OID are provinding metrics from the exporter


metrics:
  - name: sysUpTime
    oid: 1.3.6.1.2.1.1.3
    
  - name: ifNumber
    oid: 1.3.6.1.2.1.2.1
   
  - name: ifIndex
    oid: 1.3.6.1.2.1.2.2.1.1
    
  - name: ifDescr
    oid: 1.3.6.1.2.1.2.2.1.2
    
  - name: ifType
    oid: 1.3.6.1.2.1.2.2.1.3
    
  - name: ifMtu
    oid: 1.3.6.1.2.1.2.2.1.4
    
  - name: ifSpeed
    oid: 1.3.6.1.2.1.2.2.1.5
   
  - name: ifPhysAddress
    oid: 1.3.6.1.2.1.2.2.1.6
    
  - name: ifAdminStatus
    oid: 1.3.6.1.2.1.2.2.1.7
    
  - name: ifOperStatus
    oid: 1.3.6.1.2.1.2.2.1.8
    
  - name: ifLastChange
    oid: 1.3.6.1.2.1.2.2.1.9
    
  - name: ifInOctets
    oid: 1.3.6.1.2.1.2.2.1.10
   
  - name: ifInUcastPkts
    oid: 1.3.6.1.2.1.2.2.1.11
   
  - name: ifInNUcastPkts
    oid: 1.3.6.1.2.1.2.2.1.12
   
  - name: ifInDiscards
    oid: 1.3.6.1.2.1.2.2.1.13
    
  - name: ifInErrors
    oid: 1.3.6.1.2.1.2.2.1.14
   
   - name: ifInUnknownProtos
    oid: 1.3.6.1.2.1.2.2.1.15
    
   - name: ifOutOctets
    oid: 1.3.6.1.2.1.2.2.1.16
    
   - name: ifOutUcastPkts
    oid: 1.3.6.1.2.1.2.2.1.17
    
   - name: ifOutNUcastPkts
    oid: 1.3.6.1.2.1.2.2.1.18
    
   - name: ifOutDiscards
    oid: 1.3.6.1.2.1.2.2.1.19
    
   - name: ifOutErrors
    oid: 1.3.6.1.2.1.2.2.1.20
    
   - name: ifOutQLen
    oid: 1.3.6.1.2.1.2.2.1.21
 
 The Following OID return values from SNMPWALK but do not return metrics from the exporter.
 
 - name: upsOutletGroupStatusTableSize
    oid: 1.3.6.1.4.1.318.1.1.1.12.1.1
    
- name: upsOutletGroupStatusIndex
    oid: 1.3.6.1.4.1.318.1.1.1.12.1.2.1.1
    
labelname: upsOutletGroupStatusName
      oid: 1.3.6.1.4.1.318.1.1.1.12.1.2.1.2
      
name: upsOutletGroupStatusName
    oid: 1.3.6.1.4.1.318.1.1.1.12.1.2.1.2
    
labelname: upsOutletGroupStatusName
      oid: 1.3.6.1.4.1.318.1.1.1.12.1.2.1.2
     
 name: upsOutletGroupStatusGroupState
    oid: 1.3.6.1.4.1.318.1.1.1.12.1.2.1.3
    
labelname: upsOutletGroupStatusName
      oid: 1.3.6.1.4.1.318.1.1.1.12.1.2.1.2

 name: upsOutletGroupStatusCommandPending
    oid: 1.3.6.1.4.1.318.1.1.1.12.1.2.1.4
 
 labelname: upsOutletGroupStatusName
      oid: 1.3.6.1.4.1.318.1.1.1.12.1.2.1.2
      
 - name: upsOutletGroupStatusOutletType
    oid: 1.3.6.1.4.1.318.1.1.1.12.1.2.1.5
    
labelname: upsOutletGroupStatusName
      oid: 1.3.6.1.4.1.318.1.1.1.12.1.2.1.2
      
name: upsOutletGroupStatusGroupFullState
    oid: 1.3.6.1.4.1.318.1.1.1.12.1.2.1.6

labelname: upsOutletGroupStatusName
      oid: 1.3.6.1.4.1.318.1.1.1.12.1.2.1.2
      
  - name: upsOutletGroupConfigTableSize
    oid: 1.3.6.1.4.1.318.1.1.1.12.2.1

  - name: upsOutletGroupConfigIndex
    oid: 1.3.6.1.4.1.318.1.1.1.12.2.2.1.1

  - name: upsOutletGroupConfigName
    oid: 1.3.6.1.4.1.318.1.1.1.12.2.2.1.2

  - name: upsOutletGroupConfigPowerOnDelay
    oid: 1.3.6.1.4.1.318.1.1.1.12.2.2.1.3

  - name: upsOutletGroupConfigPowerOffDelay
    oid: 1.3.6.1.4.1.318.1.1.1.12.2.2.1.4
    
  - name: upsOutletGroupConfigRebootDuration
    oid: 1.3.6.1.4.1.318.1.1.1.12.2.2.1.5

  - name: upsOutletGroupConfigMinReturnRuntime
    oid: 1.3.6.1.4.1.318.1.1.1.12.2.2.1.6
    
  - name: upsOutletGroupConfigOutletType
    oid: 1.3.6.1.4.1.318.1.1.1.12.2.2.1.7

- name: upsOutletGroupConfigLoadShedControlSkipOffDelay
    oid: 1.3.6.1.4.1.318.1.1.1.12.2.2.1.8
    
  - name: upsOutletGroupConfigLoadShedControlAutoRestart
    oid: 1.3.6.1.4.1.318.1.1.1.12.2.2.1.9

  - name: upsOutletGroupConfigLoadShedControlTimeOnBattery
    oid: 1.3.6.1.4.1.318.1.1.1.12.2.2.1.10

  - name: upsOutletGroupConfigLoadShedControlRuntimeRemaining
    oid: 1.3.6.1.4.1.318.1.1.1.12.2.2.1.11

  - name: upsOutletGroupConfigLoadShedControlInOverload
    oid: 1.3.6.1.4.1.318.1.1.1.12.2.2.1.12

  - name: upsOutletGroupConfigLoadShedTimeOnBattery
    oid: 1.3.6.1.4.1.318.1.1.1.12.2.2.1.13

  - name: upsOutletGroupConfigLoadShedRuntimeRemaining
    oid: 1.3.6.1.4.1.318.1.1.1.12.2.2.1.14
    type: gauge

  - name: upsOutletGroupControlTableSize
    oid: 1.3.6.1.4.1.318.1.1.1.12.3.1

  - name: upsOutletGroupControlIndex
    oid: 1.3.6.1.4.1.318.1.1.1.12.3.2.1.1

  - name: upsOutletGroupControlName
    oid: 1.3.6.1.4.1.318.1.1.1.12.3.2.1.2

  - name: upsOutletGroupControlCommand
    oid: 1.3.6.1.4.1.318.1.1.1.12.3.2.1.3
  
   name: upsOutletGroupControlOutletType
    oid: 1.3.6.1.4.1.318.1.1.1.12.3.2.1.4
    
 name: upsBasicBatteryStatus
    oid: 1.3.6.1.4.1.318.1.1.1.2.1.1

  - name: upsBasicBatteryTimeOnBattery
    oid: 1.3.6.1.4.1.318.1.1.1.2.1.2

  - name: upsBasicBatteryLastReplaceDate
    oid: 1.3.6.1.4.1.318.1.1.1.2.1.3

  - name: upsAdvBatteryCapacity
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.1

  - name: upsAdvBatteryTemperature
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.2

  - name: upsAdvBatteryRunTimeRemaining
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.3

  - name: upsAdvBatteryReplaceIndicator
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.4

  - name: upsAdvBatteryNumOfBattPacks
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.5

  - name: upsAdvBatteryNumOfBadBattPacks
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.6

  - name: upsAdvBatteryNominalVoltage
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.7

  - name: upsAdvBatteryActualVoltage
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.8

  - name: upsAdvBatteryCurrent
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.9

  - name: upsAdvTotalDCCurrent
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.10

  - name: upsAdvBatteryFullCapacity
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.11

  - name: upsAdvBatteryActualVoltageTableIndex
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.12.1.1

  - name: upsAdvBatteryActualVoltagePolarity
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.12.1.2
    type: gauge

  - name: upsAdvBatteryFrameActualVoltage
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.12.1.3

  - name: upsAdvTotalDCCurrentTableIndex
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.13.1.1

- name: upsAdvTotalDCCurrentPolarity
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.13.1.2

  - name: upsAdvTotalFrameDCCurrent
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.13.1.3
    
  - name: upsAdvBatteryCurrentTableIndex
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.14.1.1
    type: gauge

  - name: upsAdvBatteryCurrentIndex
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.14.1.2

  - name: upsAdvBatteryCurrentPolarity
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.14.1.3

  - name: upsAdvBatteryFrameCurrent
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.14.1.4

  - name: upsAdvBatteryEstimatedChargeTime
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.15

  - name: upsAdvBatteryPower
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.16

  - name: upsAdvBatteryChargerStatus
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.17

  - name: upsAdvBatteryInternalSKU
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.19

  - name: upsAdvBatteryExternalSKU
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.20

  - name: upsAdvBatteryRecommendedReplaceDate
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.21
    
name: upsAdvBatteryNominalBackupTime
    oid: 1.3.6.1.4.1.318.1.1.1.2.2.22

  - name: upsHighPrecBatteryCapacity
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.1

  - name: upsHighPrecBatteryTemperature
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.2

  - name: upsHighPrecBatteryNominalVoltage
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.3

  - name: upsHighPrecBatteryActualVoltage
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.4

  - name: upsHighPrecBatteryCurrent
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.5

  - name: upsHighPrecTotalDCCurrent
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.6

  - name: upsHighPrecBatteryActualVoltageTableIndex
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.7.1.1

  - name: upsHighPrecBatteryActualVoltagePolarity
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.7.1.2

  - name: upsHighPrecBatteryVoltage
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.7.1.3

  - name: upsHighPrecTotalDCCurrentTableIndex
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.8.1.1

  - name: upsHighPrecTotalDCCurrentPolarity
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.8.1.2

  - name: upsHighPrecTotalDCFrameCurrent
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.8.1.3

  - name: upsHighPrecBatteryCurrentTableIndex
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.9.1.1

  - name: upsHighPrecBatteryCurrentIndex
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.9.1.2
    
    name: upsHighPrecBatteryCurrentPolarity
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.9.1.3

  - name: upsHighPrecBatteryFrameCurrent
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.9.1.4

  - name: upsHighPrecBatteryPackTableSize
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.10.1

  - name: upsHighPrecBatteryPackIndex
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.10.2.1.1

  - name: upsHighPrecBatteryCartridgeIndex
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.10.2.1.2

  - name: upsHighPrecBatteryPackFirmwareRevision
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.10.2.1.3

  - name: upsHighPrecBatteryPackSerialNumber
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.10.2.1.4

  - name: upsHighPrecBatteryPackTemperature
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.10.2.1.5

  - name: upsHighPrecBatteryPackStatus
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.10.2.1.6

  - name: upsHighPrecBatteryPackCartridgeHealth
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.10.2.1.7

  - name: upsHighPrecBatteryPackCartridgeReplaceDate
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.10.2.1.8
    
  name: upsHighPrecBatteryPackCartridgeInstallDate
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.10.2.1.9
  
  - name: upsHighPrecBatteryPackCartridgeStatus
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.10.2.1.10
   
  - name: upsHighPrecBatteryHealth
    oid: 1.3.6.1.4.1.318.1.1.1.2.3.11
   
  - name: upsBasicInputPhase
    oid: 1.3.6.1.4.1.318.1.1.1.3.1.1
    
  - name: upsAdvInputLineVoltage
    oid: 1.3.6.1.4.1.318.1.1.1.3.2.1
   
  - name: upsAdvInputMaxLineVoltage
    oid: 1.3.6.1.4.1.318.1.1.1.3.2.2
   
  - name: upsAdvInputMinLineVoltage
    oid: 1.3.6.1.4.1.318.1.1.1.3.2.3
   
  - name: upsAdvInputFrequency
    oid: 1.3.6.1.4.1.318.1.1.1.3.2.4
   
  - name: upsAdvInputLineFailCause
    oid: 1.3.6.1.4.1.318.1.1.1.3.2.5
 
  - name: upsAdvInputNominalFrequency
    oid: 1.3.6.1.4.1.318.1.1.1.3.2.6
    
  - name: upsAdvInputNominalVoltage
    oid: 1.3.6.1.4.1.318.1.1.1.3.2.7
    
  - name: upsAdvInputBypassNominalFrequency
    oid: 1.3.6.1.4.1.318.1.1.1.3.2.8
  
  - name: upsAdvInputBypassNominalVoltage
    oid: 1.3.6.1.4.1.318.1.1.1.3.2.9
   
  - name: upsAdvInputStatisticsIndex
    oid: 1.3.6.1.4.1.318.1.1.1.3.2.10.1.1
   
  - name: upsAdvInputApparentPower
    oid: 1.3.6.1.4.1.318.1.1.1.3.2.10.1.2
 
 name: upsAdvInputVoltageTHD
    oid: 1.3.6.1.4.1.318.1.1.1.3.2.10.1.3

  - name: upsAdvInputBypassVoltageTHD
    oid: 1.3.6.1.4.1.318.1.1.1.3.2.10.1.4

  - name: upsAdvInputPeakCurrent
    oid: 1.3.6.1.4.1.318.1.1.1.3.2.10.1.5

  - name: upsAdvInputBypassPeakCurrent
    oid: 1.3.6.1.4.1.318.1.1.1.3.2.10.1.6

  - name: upsAdvInputActivePower
    oid: 1.3.6.1.4.1.318.1.1.1.3.2.10.1.7

  - name: upsAdvInputTotalApparentPower
    oid: 1.3.6.1.4.1.318.1.1.1.3.2.11

  - name: upsAdvInputTotalActivePower
    oid: 1.3.6.1.4.1.318.1.1.1.3.2.12

  - name: upsAdvInputBypassTotalApparentPower
    oid: 1.3.6.1.4.1.318.1.1.1.3.2.13

  - name: upsAdvInputBypassTotalActivePower
    oid: 1.3.6.1.4.1.318.1.1.1.3.2.14

  - name: upsAdvInputEnergyUsage
    oid: 1.3.6.1.4.1.318.1.1.1.3.2.15

  - name: upsHighPrecInputLineVoltage
    oid: 1.3.6.1.4.1.318.1.1.1.3.3.1

  - name: upsHighPrecInputMaxLineVoltage
    oid: 1.3.6.1.4.1.318.1.1.1.3.3.2

  - name: upsHighPrecInputMinLineVoltage
    oid: 1.3.6.1.4.1.318.1.1.1.3.3.3

  - name: upsHighPrecInputFrequency
    oid: 1.3.6.1.4.1.318.1.1.1.3.3.4

  - name: upsHighPrecInputEnergyUsage
    oid: 1.3.6.1.4.1.318.1.1.1.3.3.5

  - name: upsHighPrecInputBypassVoltage
    oid: 1.3.6.1.4.1.318.1.1.1.3.3.6

  - name: upsHighPrecInputBypassFrequency
    oid: 1.3.6.1.4.1.318.1.1.1.3.3.7
    
  - name: upsBasicOutputStatus
    oid: 1.3.6.1.4.1.318.1.1.1.4.1.1

  - name: upsBasicOutputPhase
    oid: 1.3.6.1.4.1.318.1.1.1.4.1.2
    type: gauge

  - name: upsBasicSystemStatus
    oid: 1.3.6.1.4.1.318.1.1.1.4.1.3
    type: gauge
  
  - name: upsBasicSystemInternalTemperature
    oid: 1.3.6.1.4.1.318.1.1.1.4.1.4
    type: gauge

  - name: upsBasicSystemInverterStatus
    oid: 1.3.6.1.4.1.318.1.1.1.4.1.5
    type: gauge
   
  - name: upsBasicSystemPFCStatus
    oid: 1.3.6.1.4.1.318.1.1.1.4.1.6
    type: gauge

  - name: upsBasicOutputACwiringConfiguration
    oid: 1.3.6.1.4.1.318.1.1.1.4.1.7
    type: gauge

  - name: upsAdvOutputVoltage
    oid: 1.3.6.1.4.1.318.1.1.1.4.2.1

  - name: upsAdvOutputFrequency
    oid: 1.3.6.1.4.1.318.1.1.1.4.2.2

  - name: upsAdvOutputLoad
    oid: 1.3.6.1.4.1.318.1.1.1.4.2.3

 name: upsAdvOutputCurrent
    oid: 1.3.6.1.4.1.318.1.1.1.4.2.4

  - name: upsAdvOutputRedundancy
    oid: 1.3.6.1.4.1.318.1.1.1.4.2.5

  - name: upsAdvOutputKVACapacity
    oid: 1.3.6.1.4.1.318.1.1.1.4.2.6

  - name: upsAdvOutputNominalFrequency
    oid: 1.3.6.1.4.1.318.1.1.1.4.2.7

  - name: upsAdvOutputActivePower
    oid: 1.3.6.1.4.1.318.1.1.1.4.2.8

  - name: upsAdvOutputApparentPower
    oid: 1.3.6.1.4.1.318.1.1.1.4.2.9

  - name: upsAdvOutputStatisticsIndex
    oid: 1.3.6.1.4.1.318.1.1.1.4.2.10.1.1
    
  - name: upsAdvOutputPeakCurrent
    oid: 1.3.6.1.4.1.318.1.1.1.4.2.10.1.2

  - name: upsAdvOutputCurrentTHD
    oid: 1.3.6.1.4.1.318.1.1.1.4.2.10.1.3

  - name: upsAdvOutputCrestFactor
    oid: 1.3.6.1.4.1.318.1.1.1.4.2.10.1.4
    
  - name: upsAdvOutputNeutralCurrent
    oid: 1.3.6.1.4.1.318.1.1.1.4.2.11

  - name: upsAdvOutputEnergyUsage
    oid: 1.3.6.1.4.1.318.1.1.1.4.2.12

  - name: upsAdvOutputSourceSynchronization
    oid: 1.3.6.1.4.1.318.1.1.1.4.2.13

  - name: upsHighPrecOutputVoltage
    oid: 1.3.6.1.4.1.318.1.1.1.4.3.1

  - name: upsHighPrecOutputFrequency
    oid: 1.3.6.1.4.1.318.1.1.1.4.3.2

  - name: upsHighPrecOutputLoad
    oid: 1.3.6.1.4.1.318.1.1.1.4.3.3

  - name: upsHighPrecOutputCurrent
    oid: 1.3.6.1.4.1.318.1.1.1.4.3.4

  - name: upsHighPrecOutputEfficiency
    oid: 1.3.6.1.4.1.318.1.1.1.4.3.5

  - name: upsHighPrecOutputEnergyUsage
    oid: 1.3.6.1.4.1.318.1.1.1.4.3.6

  - name: upsAdvTestDiagnosticSchedule
    oid: 1.3.6.1.4.1.318.1.1.1.7.2.1
   
  - name: upsAdvTestDiagnostics
    oid: 1.3.6.1.4.1.318.1.1.1.7.2.2
    type: gauge
    
  - name: upsAdvTestDiagnosticsResults
    oid: 1.3.6.1.4.1.318.1.1.1.7.2.3

  - name: upsAdvTestLastDiagnosticsDate
    oid: 1.3.6.1.4.1.318.1.1.1.7.2.4
    
  - name: upsAdvTestRuntimeCalibration
    oid: 1.3.6.1.4.1.318.1.1.1.7.2.5
    
 name: upsAdvTestCalibrationResults
    oid: 1.3.6.1.4.1.318.1.1.1.7.2.6
   
  - name: upsAdvTestCalibrationDate
    oid: 1.3.6.1.4.1.318.1.1.1.7.2.7
  
  - name: upsAdvTestDiagnosticTime
    oid: 1.3.6.1.4.1.318.1.1.1.7.2.8
   
  - name: upsAdvTestDiagnosticDay
    oid: 1.3.6.1.4.1.318.1.1.1.7.2.9
   
  - name: upsAdvTestBatteryInterval
    oid: 1.3.6.1.4.1.318.1.1.1.7.2.10
   
  - name: upsCommStatus
    oid: 1.3.6.1.4.1.318.1.1.1.8.1
   
  - name: iemStatusProbeNumber
    oid: 1.3.6.1.4.1.318.1.1.10.2.3.2.1.1
  
  - name: iemStatusProbeName
    oid: 1.3.6.1.4.1.318.1.1.10.2.3.2.1.2
   
  - name: iemStatusProbeStatus
    oid: 1.3.6.1.4.1.318.1.1.10.2.3.2.1.3
   
  - name: iemStatusProbeCurrentTemp
    oid: 1.3.6.1.4.1.318.1.1.10.2.3.2.1.4
  
  - name: iemStatusProbeTempUnits
    oid: 1.3.6.1.4.1.318.1.1.10.2.3.2.1.5

name: iemStatusProbeCurrentHumid
    oid: 1.3.6.1.4.1.318.1.1.10.2.3.2.1.6

  - name: iemStatusProbeHighTempViolation
    oid: 1.3.6.1.4.1.318.1.1.10.2.3.2.1.7

  - name: iemStatusProbeLowTempViolation
    oid: 1.3.6.1.4.1.318.1.1.10.2.3.2.1.8

  - name: iemStatusProbeHighHumidViolation
    oid: 1.3.6.1.4.1.318.1.1.10.2.3.2.1.9

  - name: iemStatusProbeLowHumidViolation
    oid: 1.3.6.1.4.1.318.1.1.10.2.3.2.1.10

  - name: iemStatusProbeMaxTempViolation
    oid: 1.3.6.1.4.1.318.1.1.10.2.3.2.1.11

  - name: iemStatusProbeMinTempViolation
    oid: 1.3.6.1.4.1.318.1.1.10.2.3.2.1.12
    
  - name: iemStatusProbeMaxHumidViolation
    oid: 1.3.6.1.4.1.318.1.1.10.2.3.2.1.13
    
  - name: iemStatusProbeMinHumidViolation
    oid: 1.3.6.1.4.1.318.1.1.10.2.3.2.1.14
    
name: iemStatusProbeLocation
    oid: 1.3.6.1.4.1.318.1.1.10.2.3.2.1.15
    
 
