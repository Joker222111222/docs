<?xml version="1.0"?>

-<ResetSession Phase="Online" TargetPath="\" TargetOffset="1078984704" TargetLocation="PCIROOT(0)#PCI(1F02)#ATA(C00T00L00)" TargetCapacity="500107862016" TargetSignature="{9DD82C32-ED1D-418B-B41B-5096AAC6609C}" TargetSet="True">

<Options PreserveWorkplace="False" OverwriteSpace="False" WipeData="False" Scenario="Reset"/>


+<OfflineBoot OriginalBCDTimeout="0" OriginalBCDDefault="{00000000-0000-0000-0000-000000000000}" OriginalFirmwareTimeout="0" IsStaged="False">

<ExecState Remediation="Continue" IgoreDiskSpaceValidate="False" SavedWinRE="True" SetupSourcesDirPath="\$WINDOWS.~BT\Sources" SetupSourcesDirOffset="1078984704" SetupSourcesDirLocation="PCIROOT(0)#PCI(1F02)#ATA(C00T00L00)" SetupSourcesDirCapacity="500107862016" SetupSourcesDirSignature="{9DD82C32-ED1D-418B-B41B-5096AAC6609C}" SetupSourcesDirSet="True" SetupSourcesCleaned="True" NewOSBootEntry="{04FC90BD-5E63-11EC-AD24-DFC99D9136BF}" NewOSRootPath="\" NewOSRootOffset="1078984704" NewOSRootLocation="PCIROOT(0)#PCI(1F02)#ATA(C00T00L00)" NewOSRootCapacity="500107862016" NewOSRootSignature="{9DD82C32-ED1D-418B-B41B-5096AAC6609C}" NewOSRootSet="True" HaveNewOS="True" OldOSRootPath="\Windows.old" OldOSRootOffset="1078984704" OldOSRootLocation="PCIROOT(0)#PCI(1F02)#ATA(C00T00L00)" OldOSRootCapacity="500107862016" OldOSRootSignature="{9DD82C32-ED1D-418B-B41B-5096AAC6609C}" OldOSRootSet="True" HaveOldOS="True" TargetVolumeFreeSpace="197624647680" TargetVolumeCapacity="212114337792" TargetVolumeRootPath="\" TargetVolumeRootOffset="1078984704" TargetVolumeRootLocation="PCIROOT(0)#PCI(1F02)#ATA(C00T00L00)" TargetVolumeRootCapacity="500107862016" TargetVolumeRootSignature="{9DD82C32-ED1D-418B-B41B-5096AAC6609C}" TargetVolumeRootSet="True" TargetVolumeAccessible="True" HaveTargetVolume="True"/>
  
<OnlinePhase/>

</ResetSession>
