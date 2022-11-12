# [GUIDE] Advanced-Power-Option-Windows

# Basic Option

## Require a Password on wakeup 
Require a password to unlock the computer when it wakes from sleep.
Parameter:

Yes *Will required password*

No *Automatically unlock to desktop*

## Device idle policy
Specifies the policy for devices powering down while the system is running.
Parameter:

Performance **It will ignoore idle mode**

Power Savings **Prioritize idle mode**

## Disconnected Standby Mode
Specifies the disconnected standby mode.
Parameter:

Normal **Computer will prioritize C3 (Sleep) than C1/C2**

Aggresive  **Prioritize C1/C2**

## Networking connectivity in Standby
Specifies network connection state in standby.
Parameter:

Disable **Network will disconnected if in standby mode**

Enable **Network will keep**

Managed by Windows **Automate by Windows**

# Hard disk
## AHCI Link Power Management - HIPM/DIPM
Parameter:

Active **Neither HIPM or DIPM allowed. Link power management is not used. (Performance)**

HIPM **HIPM (Host Initiated Link Power Management) only is allowed**

HIPM+DIPM **HIPM and DIPM are allowed**

DIPM **DIPM (Device Initiated Link Power Management) only is allowed**

Lowest **HIPM, DIPM, and DEVSLP (if DEVSLP is supported by the storage device) are allowed. (Battery life)**

## APST ITPT for non-operational power states (ms) on Hybrid Optane drive
Parameter:

0-60000 millisecond **Lower for performance. Higher for battery life**

## Maximum Power
Specifies the power consumption level storage devices should not exceed.
Parameter:
0-100% **Lower for battery life. Higher for performance**

## APST ITPT for non-operational power states (ms) on Hybrid Nand Drive
Parameter:

0-60000 millisecond **Lower for performance. Higher for battery life**

## APST ITPT for non-operational power states (ms) on any NVMe drive
Parameter:

0-60000 millisecond **Lower for performance. Higher for battery life**

## Turn off hard disk after
Parameter:

0-70999999 **Lower for battery life**

## APST ITPT for operational power states (ms) on NVMe drive
Parameter:

0-60000 millisecond **Higher for performance. Lower for battery life**

## Hard disk burst ignore time
Ignore a burst of disk activity up to the specified time when determining if the disk is idle.
Parameter:

0-70999999 **Higher for battery life. Lower for  performance.**

## APST ITPT for operational power states (ms) on Hybrid Nand drive
Parameter:

0-60000 millisecond **Higher for performance. Lower for battery life**

## APST ITPT for operational power states (ms) on Hybrid Optane drive
Parameter:

0-60000 millisecond **Higher for performance. Lower for battery life**

## Secondary NVMe idle Timeout
Specifies the amount of time the NVMe device must be in the primary not-operational power state before transitioning to the secodnary non-operational power state.
Parameter:

0-60000 millisecond **Higher for performance. Lower for battery life**



# Desktop background settings


# Sleep

# USB settings

# idle Resiliency

# Interrupt Steering Settings

#  Power buttons and lid

# PCI Express

# Processor power management
## Proessor performance increase threshold
## Processor performance increase threshold for Processor Power Efficiency Class 1
## Processor performance core parking min cores
## Processor performance core parking min cores for Processor Power Efficiency Class 1
## Processor performance decrease threshold
## Processor performance decrease threshold for Processor Power Efficiency Class 1
## Initial performance for Processor Power Efficiency Class 1
## Processor performance core parking concurrency threshold
## Processor performance core parking increase time
## Processor energy performance prefrence policy
## Processor energy performance prefrence policy for Processor Power Efficiency Class 1
## Allow Throttle States
Allow processors to use throttle states in addition to performance states.
## Processor performance increase time for Processor Power Efficiency Class 1
## Processor performance decrease policy
## Processor performance decrease policy for Processor Power Efficiency Class 1
## Long running threads processor architecture lower limit
## Processor performance core parking parked performance state
## Processor performance core parking parked performance state for Processor Power Efficiency Class 1
## Processor performance boost policy
## Processor performance increase policy
## Processor performance increase policy for Processor Power Efficiency Class 1
## Processor idle demote threshold
## Processor performance core parking distribution threshold
## Processor duty cycling
## Short running threads' processor architecture lower limit
## Processor idle disable
Parameter:
Enable idle
Disable idle **Use all resource CPU that will make **



# Graphics settings

# Display

# Presence Aware Power Behavior

# Energy Saver settings
## Display brightness weight
## Energy Saver Policy
## Charge level
# Battery
