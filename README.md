# DVC-demo

- Data Version Control tool 
- Some time we put our data as well on GitHub like .csv file and all. But if data is small then its fine but if its huge then GitHub will not allow it then what to do? that’s where the role of DVC comes 
- If data is huge then you will not be able to push the data to GitHub and that problem is solved DVC.
- Using DVC, without committing huge data to your git repo we can control its version.
- In Git we only tracking the metadata of huge files and actual data can be stored/tracked by some other system, could be in Git or AWS S3 or Azure 
- DVC manages the Metadata version for us which in turn manages the actual data version on other systems. 
