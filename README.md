# Towards net-zero manufacturing: carbon-aware scheduling for GHG emissions reduction

This project contains the instance files for the paper titled "Towards net-zero manufacturing: carbon-aware scheduling for GHG emissions reduction" by Andrea Mencaroni, Pieter Leyman, Birger Raa, Stijn De Vuyst, and Dieter Claeys, see: [https://doi.org/10.1016/j.jclepro.2025.146787]

## Contact

Contact name	( Andrea.Mencaroni@UGent.be )  
Authors		( Andrea.Mencaroni@UGent.be; Pieter.Leyman@UGent.be; Birger.Raa@UGent.be; Stijn.DeVuyst@UGent.be; Dieter.Claeys@UGent.be)  
ZAP name	( Dieter.Claeys@UGent.be )  
Website		( http://www.ugent.be/m-f/en )  

## Executable release


A standalone executable version of the **MA-CAS-PFSP** algorithm (no installation required) is available in the  
[**Releases section**](../../releases/latest)

**Included:**
- `MA-CAS-PFSP_run.exe` – self-contained executable  
- Example `.bat` file to run a sample instance  
- Config files and instance datasets  

See the release notes for full instructions on how to run the executable.

## Citation

When using the instance files contained in this repo, please cite the following work:

```
Andrea Mencaroni, Pieter Leyman, Birger Raa, Stijn De Vuyst, Dieter Claeys,
Towards net-zero manufacturing: Carbon-aware scheduling for GHG emissions reduction,
Journal of Cleaner Production,
Volume 529,
2025,
146787,
ISSN 0959-6526,
https://doi.org/10.1016/j.jclepro.2025.146787.
```

## Instance files structure

All instance files follow the structure shown below:  

#machines, #days, #jobs, tot duration, tot energy reqs, min duration/operation, median duration/operation, max duration/operation, min req, median req, max req, LB  
Power reqs of job 1 on machine 1 per timeslot  
Power reqs of job 1 on machine 2 per timeslot  
Power reqs of job 1 on machine 3 per timeslot  
....   
Power reqs of job 1 on machine M per timeslot  
Power reqs of job 2 on machine 1 per timeslot  
Power reqs of job 2 on machine 2 per timeslot  
....  
....  
Power reqs of job N on machine M per timeslot  
Available on-site generation per timeslot  
Grid carbon intensity per timeslot  
Day-ahead electricity price per timeslot

## License
[GPL-3.0 license](https://www.gnu.org/licenses/gpl-3.0.html#license-text)

Copyright 2025 © [Andrea Mencaroni](https://ea18.ugent.be/people/24/andrea-mencaroni/)

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. 

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details. 

You should have received a copy of the GNU General Public License along with this program. If not, see <https://www.gnu.org/licenses/>. 

## Contacting the author

We would very much appreciate hearing from you if you use CAS-PFSP and find problems, or if you can think of ways it could be improved - and even (or is that 'especially'?) if you just think it's great.
Even if the facility you would like to see appears to be of interest only to you, tell us about it - you'd be surprised how many ideas in that class have a much wider appeal. 
See above for further contact information.  

We read and consider all mail we receive, even though we may not have time to reply.
