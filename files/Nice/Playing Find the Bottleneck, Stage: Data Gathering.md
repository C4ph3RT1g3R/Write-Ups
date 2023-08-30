# Playing Find the Bottleneck, Stage: Data Gathering

## Scenario
Not Recorded

## Tools Used
| performance monitor | crystal disk mark 8.0.4 | 
| :--- | :--- |

## Documentation
**Issue**: Disk lag <br>
**Task**: Create disk performance and benchmarking reports for disk IOPS/throughput analysis. <br>

### Performance Monitor: Create a user defined data collector set and select physical disk performance counters as follows: 
 - %Disk Read Time
 - %Disk Time
 - %Disk Write Time
 - %Idle Time
 - Current Disk Queue Length
 - Disk Reads/sec
 - Disk Writes/sec
 - Split IO/Sec
 - Set intervals at 15 seconds. Run report.
 - Report will save as a .blg. Management requested a .csv. To convert the .blg, open the report in performance monitor, right-click on the graph for a menu that will allow you to save the new data type as .csv. Note the path statement as well. The report should be filed in C:\Perflogs\Admin

### Crystal Disk: Evaluate disk performance using benchmark software.
 - Open Crystal Disk Mark 8.0.4
 - Select "All" Settings as follows: (defaults) Test count = 5; Test size = 1 GiB; Select test drive C:; Output measure = MB/s
 - Press All button to run report. The test measures sequential and random performance on a read/write/max.
 - Save the report as a .txt file using the same path as the previous report.
 - Report names: Disk_report1.csv and Disk_Report2.txt
