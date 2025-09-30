# FITCHECK Report Automation

This tool automates the processing of Nutanix Collector excel reports. It extracts key VM metrics (CPU, memory, disk), generates visual charts, and provides a summarized report for stakeholders. 

# Key Features
- Automated parsing of FITCHECK Excel files.  
- Summary report (`vm_stats.txt`) highlighting:  
  - Overutilized and underutilized VMs.  
  - Optimization opportunities for CPU, memory, and storage.  
- Visual charts (CPU, memory, disk) saved as PNGs alongside the reports.  

# Benefits
- Improves visibility into cluster resource utilization.  
- Identifies optimization opportunities at a glance.  
- Provides both technical (charts) and executive-friendly (summary file) outputs.  

# Usage
- Place FITCHECK Excel files in the input folder.  
- Run the notebook/script.  
- Review generated outputs:  
  - Charts (`memory_usage.png`, `cpu_usage.png`, `disk_usage.png`)  
  - Summary Report (`vm_stats.txt`)  
