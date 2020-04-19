# Application: DeleteJobNotify.jar

## What the application will do.
* Best used on MySQL or OracleDB. Connection issues may occurr using MicroSoft SSMS

1) The application will monitor the progress of a delete job by running a query against the oracle database twice after a set interval.
	
2) The application will then compare the count and see if there a difference.

3) If there is a difference, the application will then print out the appropriate message. This will act as a notification to ensure that job runs without manual monitoring.

---
### Creators:
	Akash Jangle
	James Gilles

Development environment: Java
---
Date: August 18, 2019
