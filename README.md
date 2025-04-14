# CBT200
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 200 is from TWA and contains the following programs:      *   FILE 200
//*                                                                 *   FILE 200
//*    Most of these programs were written by Rex Widmer and/or     *   FILE 200
//*    Peter Farrell.                                               *   FILE 200
//*                                                                 *   FILE 200
//*    Some fixes were made by Roland Schiradin and Sam Golob.      *   FILE 200
//*    These were just so the programs would work.  The COBOL       *   FILE 200
//*    load module programs still need modernization.               *   FILE 200
//*                                                                 *   FILE 200
//*    WHATSNEW  THIS PROGRAM ANALYZES A PDS AND LISTS              *   FILE 200
//*              THE MEMBERS IN MOST RECENTLY CHANGED ORDER         *   FILE 200
//*              A CHANGE IS CONSTITUTED TO MEAN A RE-LINKEDIT,     *   FILE 200
//*              OR A CHANGE BY SUPERZAP.  IT IS DRIVEN BY THE      *   FILE 200
//*              IDR DATA RECORDS WITHIN THE PDS.                   *   FILE 200
//*                                                                 *   FILE 200
//*              (Program updated for DFSORT Release 13.0 and       *   FILE 200
//*              z/OS Rel 1.13.  OLD VERSION STILL INCLUDED.)       *   FILE 200
//*                                                                 *   FILE 200
//*              This version needs Y2D sort parameter to be        *   FILE 200
//*              supported.                                         *   FILE 200
//*                                                                 *   FILE 200
//*    WHEREUSD  THIS PROGRAM ANALYZES A PDS AND LISTS ALL MEMBERS  *   FILE 200
//*              WHICH CONTAIN A REFERENCE TO A GIVEN EXTERNAL      *   FILE 200
//*              SYMBOL.                                            *   FILE 200
//*                                                                 *   FILE 200
//*              Updated for Y2K - Format dates in header of the    *   FILE 200
//*                                report.                          *   FILE 200
//*                                                                 *   FILE 200
//*    COMPARE   THIS PROGRAM ANALYZES GIVEN MEMBERS WHICH EXIST IN *   FILE 200
//*              A PAIR OF PDS'S.  THE MEMBERS ARE CHECKED FOR      *   FILE 200
//*              DIFFERENCES AND FOR ADHERENCE TO INSTALLATION      *   FILE 200
//*              STANDARDS AS A PRE-IMPLEMENTATION Q/C MEASURE.     *   FILE 200
//*                                                                 *   FILE 200
//*    COBREAD   THIS PROGRAM ANALYZES A PDS AND LISTS ALL MEMBERS  *   FILE 200
//*              ALONG WITH THE COBOL ATTRIBUTES ASSOCIATED WITH    *   FILE 200
//*              THE MAIN CSECT WITHIN THE MODULE.  SUCH ITEMS AS   *   FILE 200
//*              COBOL / STATE / / FLOW / / OPTIMIZATION / /TEST/,  *   FILE 200
//*              / ENDJOB /,  AND  / DYNAM / ARE LISTED.            *   FILE 200
//*              THE ABILITY TO SELECTIVELY ANALYZE A SINGLE        *   FILE 200
//*              MEMBER IS ALSO SUPPORTED.                          *   FILE 200
//*                                                                 *   FILE 200
//*              I would suggest running COBANAL from File 321.     *   FILE 200
//*              That's a more modern program, which does the job   *   FILE 200
//*              better.   (SBG 03/00)                              *   FILE 200
//*                                                                 *   FILE 200
//*              This program must be linkedited AMODE 31 or ANY.   *   FILE 200
//*                                                                 *   FILE 200
//*    XREF1     THIS PROGRAM SCANS A PDS AND PRODUCES INTERMEDIATE *   FILE 200
//*              RECORDS TO ALLOW XREF2 TO CREATE A GLOBAL CROSS-   *   FILE 200
//*              REFERENCE OF EXTERNAL SYMBOLS IN THE PDS.  THIS    *   FILE 200
//*              REPORT PROVIDES INFORMATION OF THE FORM: CSECT IS  *   FILE 200
//*              CONTAINED IN THE FOLLOWING LOAD MODULES ...        *   FILE 200
//*                                                                 *   FILE 200
//*    XREF2     THIS IS THE REPORT PROGRAM TO PROCESS THE OUTPUT   *   FILE 200
//*              OF XREF1.  IT MAY HAVE MULTIPLE XREF1 FILES AS     *   FILE 200
//*              INPUT.  ALL INPUTS WILL BE MERGED WITHIN THE       *   FILE 200
//*              REPORT GENERATION PROCESS.                         *   FILE 200
//*                                                                 *   FILE 200
//*    CPUID     PROGRAM TO LIST CPUIDS OF ALL PROCESSORS           *   FILE 200
//*              (WRITTEN BY REX WIDMER. RESCUED FROM GILBERT       *   FILE 200
//*              SAINT-FLOUR'S ARCHIVES.)                           *   FILE 200
//*                                                                 *   FILE 200
//*    CPUIDX    REXX FROM MARCEL SCHMIDT TO LIST CPUIDS OF ALL     *   FILE 200
//*              PROCESSORS.  PROBABLY BETTER THAN THE CPUID        *   FILE 200
//*              PROGRAM.  THAT IS WHY WE INCLUDED IT HERE.         *   FILE 200
//*                                                                 *   FILE 200
```
