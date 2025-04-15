# CBT654
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 654 is from Tommy Sprinkle and contains his FSI (Full     *   FILE 654
//*           Screen Interface) for MVS TSO.  This package was      *   FILE 654
//*           inspired by running MVS 3.8 under Hercules.           *   FILE 654
//*                                                                 *   FILE 654
//*       Two installation jobs are included here:  $RECEIVE        *   FILE 654
//*       will create the FSI execution libraries using the TSO     *   FILE 654
//*       RECEIVE command.  If you are not running TSO/E and        *   FILE 654
//*       you don't have TSO RECEIVE, you can run the $PDSLOAD      *   FILE 654
//*       job to create all the libraries except the load library   *   FILE 654
//*       and you can get the load library from the LOADT member    *   FILE 654
//*       in REVLMOD format (CBT Tape Files 134, 135).              *   FILE 654
//*                                                                 *   FILE 654
//*       Description of the Package:                               *   FILE 654
//*                                                                 *   FILE 654
//*       Full Screen Interface (FSI) is a programming library      *   FILE 654
//*       modeled after SPF that supports full screen 3270          *   FILE 654
//*       programming.  To use FSI, one more more application       *   FILE 654
//*       panels are coded and stored in the Panel Library or       *   FILE 654
//*       PLIB data set.  The application program uses a            *   FILE 654
//*       Display function call to display the panel.  Input /      *   FILE 654
//*       output variables are used to allow the application to     *   FILE 654
//*       display dynamic content to the screen and allow the       *   FILE 654
//*       application program to retrieve input data from the       *   FILE 654
//*       terminal.                                                 *   FILE 654
//*                                                                 *   FILE 654
//*       FSI uses an execution environment that the application    *   FILE 654
//*       program must run underneath.  To run a FSI application,   *   FILE 654
//*       the FSI environment must first be created using the       *   FILE 654
//*       FSISTART command specifying the application name as a     *   FILE 654
//*       parameter.  The FSISTART command will load the FSI        *   FILE 654
//*       environment and then attach the application program.      *   FILE 654
//*                                                                 *   FILE 654
//*           email:  tommy@tommysprinkle.com                       *   FILE 654
//*                                                                 *   FILE 654
```
