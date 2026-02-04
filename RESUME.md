# Jeffrey W. Meadows
Infrastructure Engineer
| [mrmrsm3@gmail.com](mailto:mrmrsm3@gmail.com)
| [816 431 6956](tel:8164316956)

## About me
Logically driven person with a very long technical history in a variety of areas in datacenter infrastructure.

## Experience Summary

- Eight years Satellite Ground Station Technician in the Air Force, six of which involved administration of UNIX computer systems.
- Twenty six years of Business IT experience administering different platforms of UNIX machines in various production and database environments.
- Nineteen years experience with various platforms of Linux both in and out of the Air Force.
- Over fifteen years experience (both professional and personal) in various platforms of Windows and various Windows services to include DNS, Active Directory, and Windows SFU (Services For UNIX).
- Over twelve years experience with HPUX in an enterprise environment.
- Fourteen years professional experience with various platforms of Solaris in an enterprise environment.
- Fourteen years accumulative experience in various platforms of AIX.
- Four solid years experience in MC Service Guard cluster architecture in SAN environments to include SAN management.
- Ten years managing MC Service Guard clusters on the HPUX platform in an enterprise environment.
- Twenty five years deploying various services in a UNIX environment to include FTP, Web, DHCP, DNS, Samba, NIS, NFS, and various rapid deployment solutions, not including the years I managed these services.
- Five years experience in managing Oracle Middleware 10g environments for Web, OID, SSO, OAM, and Portal.
- Five years working with Linux and Unix virtualization and HP Blade enclosures.
- Ten years of operational experience with VMWare vSphere and VM deployment.
- Five years with Cisco blade server deployment.
- Eight years of Puppet Enterprise experience with infrastructure and custom module development.
- Four years of Ansible Automation Platform experience building roles, playbooks, tasks, templates, inventories, workflows, projects, job templates, and password vaults.
- Other skills include installation, maintenance, troubleshooting and repair of the Satellite Readout Station satellite telemetry, Command, and Control systems, Mark IVB MDS satellite telemetry systems.  RF Electronics transmit and receive.  Component level electronic component repair, development of simple block diagrams and other shop documentation.

## Software Skills

### Windows Experience

Windows Server 2008, Windows Server 2003, Windows 11, Windows 10, Windows Vista, Windows 7, Windows XP Professional, Windows 2000 Professional, Windows 2000 Advanced Server, Windows NT4 Workstation, Windows (95,98, & ME), Microsoft office (95, 97, 2000, XP,  2003, 2007, 2010, o356), Norton Ghost & Multicast, PC Anywhere, VNC, Reflextions, Exceed, Oracle (Install Only), SQL (Install Only), Disk Access, MKS, ClearCase, Lotus Notes, CIFS File & Print Sharing, Apache for Windows (Web Server), Windows Terminal Server, MoveIt FTP server, FTP Client and Server applications, Windows Remote Desktop Protocol, Windows Terminal, VSCode, Notepad ++, Windows Services for Linux (WSLv1 & WSLv2), CygWin, and PuTTY.

### Linux/UNIX Experience

LINUX (Redhat, Slackware, Mandrake, & Caldera, SUSE, Lycoris, Knoppix, Debian, Ubuntu, CentOS, Fedora Silverblue, Fedora, Arch), UNIX (MASCOM, AIX, Solaris, HP-UX, & Tru64), IgniteUX, Jumpstart, Kickstart, SMIT (and SMITTY), BladeLogic, VIM, VI, and Midnight Commander script editors, SUN Star Office (5.0 & 5.1), Image Magic, SAMBA, IPChains, Apache (HTTPD), Ngrep (Sniffer), Pine (Command Line Mail Client), TCP/IP, IPX/SPX, FTP, Telnet, Minicom, Hyper term, ProComm Plus, VNC (For Linux), Oracle (Install Only), Clearcase, RCS, CVS, Subversion, Git (including Gitlab server), NIS, NTP, NFS, Rockridge (CD ISO Mastering Software), HTTP, EXT, XFS, ReiserFS, BTRFS, NTFS, HPFS, FAT (16, VFAT, & 32) X-Windows (KDE, CDE, Window maker, After step, GNOME, Black box, & Free Window Manager [FWM]), Volume managers (LVM, Veritas,  Solstice Disk Suite), Package Managers (MC Service Guard & Veritas Cluster Service), LP, Dazel, Open View (Omniback), and Veritas (Netbackup), Kernel Compiling and tweaking, RedHat Enterprise Virtualization Manager (RHEVM), RedHat Network Satellite Server (V5x AKA. Spacewalk & V6.x AKA Foreman), Puppet Enterprise, Ansible Automation Platform, VMWare (vSphere),  Jboss (EAP, EWS, and JON), Apache, Nginx, NetIQ (Access Gateways, Identity Providers, Network Access Manager, eDir), SSS, LDAP, Kerberos, OpenLDAP, KOAN, Cobbler, Ruby, Python, Shell Scripting.

## Hardware Skills

HP Proliant, HP C7000 Blade Enclosure, Integrity and Xeon HP blades, Cisco Blade Enclosure, HP9000 rackmount servers (integrity and PA-RISC), Dell PowerEdge servers, EMC Symetrics and Clarion disk arrays, HP XP disk arrays, MASCOM, DEC, IBM RISC6000, NetApp FAS filer appliances, Raritain KVM switches iLO and iDRAC web consoles, Network routers and switches, Fiber Optic, Twinax, and Cat 5/6 cabling HP tape libraries, STK Timberwolf tape libraries, various laptop and desktop systems.

## Work Experience

### UNIX/Linux Systems Engineer and Infrastructure Automation Engineer for UMB, Kansas City, MO.
*January 2015 - Present*
 
- Created BEA Blade Logic automation for managing configurations on new servers as they are built
- Moved user resolution and authentication to SSSD using kerberos and the LDAP component of Active Directory.
- Moved that SSSD configuration to use NetIQ eDir IDPs and separated Production and Non-Production authentication back-ends.
- Simplified the Sudo configuration to use snippets and group membership for elevated rights (nothing granted at the user level) to prepare for move to LDAP (eDir) group resolution
- Setup RedHat Satellite for server build automation using templates and snippets to make Kickstart work to deploy and maintain VM templates and bare-metal builds.
- Setup SSH trusted hosts once Blade Logic was decommissioned.
- Created a reports server with Nginx, Python, Flask, and CSS with tables rendered with Pandas and Java script from Excel and CSV auto-generated files.
- Created automated reports for user access, storage allocation, patch status, Cyber Resiliency VM restore reports that are dropped into the Nginx/Flask reports server.
- Part of the setup team for Puppet Enterprise as well as created several custom modules used for configuration and compliance management.
- Setup Oracle RAC servers and set up a method for Oracle DBAs to manage their agent configuration files using Puppet templates.
- Setup Workflows, Job Templates, password vaults, inventories, projects, playbooks, roles, tasks, and templates in Ansible Automation Project in our Cyber Resilience environment that is responsible for daily replication into that environment from Production.
- Created multiple Gitlab projects to support Puppet Enterprise and Ansible Automation Platform
- Through our automation with Puppet and Satellite, was able to get server builds down to ~15 minutes.

### Lead Systems Administrator for the National Association of Insurance Commissioners, Kansas City, MO.
*October 2006 - January 2015*

- Implemented and managed SAN storage arrays (EMC CX520c, HP XP12000 & XP20000, NetApp FAS3240 & FAS3270).
- Implemented and managed NAS storage appliances (EMC Celarra, NetApp OnTap 8.0.X 7 mode).
- Implemented and maintained a Linux RedHat environment using RedHat Satellite Server and Kickstart.
- Implemented and maintained a Linux virtualized environment using RedHat Enterprise Virtualization Manager.
- Implemented and maintained an HP-UX Virtualized environment using HP Integrety Virtualization.
- Implemented and maintained MC ServiceGuard clusters for HP-UX backend application servers.
- Designed, implemented, tested, and maintained a DR process for SAN and UNIX/LINUX systems using storage replication and shell scripting.
- Integrated NetIQ E-Dir with Linux systems using Open LDAP for user authentication.
- Implemented JBoss EAP 6.X servers and EWS servers with JON and RTI collectors and plugins.
- Designed, implemented, and maintained sudo for access control of our UNIX/Linux systems.
- Migrated the NAIC UNIX/Linux environment from Telnet and Rlogin/RSH to SSH.
- Built and administered servers running HP-UX 11.i v1, PH-UX 11.i v2, and HP-UX 11.i V3 on PA RISC and Integrity Blade and Rack-mount platform.
- Built and maintained servers running RedHat Enterprise Linux 4.x, 5.x, and 6.x (32 bit and 64 bit) running on HP Proliant (Xeon) Blade and Rack-mount platforms.
- Aided implementation and maintained Oracle Application Server Web and Security middleware services running on HP-UX and RHEL Linux
- Designed script automation for updating Java Web Applications for web middleware components and provided documentation for other departments

### IT Consultant for Gold Systems, Boulder, CO.
*June 2006 - August 2006*
 
- Built Avaya IR 2.0 (Interactive Response) machines for research and development of the Gold Systems software packages.
- Built Sun Sparc (Sunfire) machines with Solaris 8 and 10 with custom drive, services, and network configurations.
- Installed Oracle 10g on the Sun Sparc platform and configured a starting database along with some Oracle User administration and table configurations to work with Avaya IR and Gold Systems software.
- Created easy to follow documentation for installing and configuring Solaris, Oracle, Avaya IR software, and Gold Systems software.
- Designed and implemented centralization of user environments for easy administration using Samba, NFS, NIS, Windows Active Directory and SFU services.
- Designed backup method and infrastructure for taking backup images of Avaya IR and IVR machines for disaster recovery.

### AIX System Management Specialist for IBM (CDI Contractor), Boulder, CO.
*February 2006 - June 2006*
 
- Managed AIX, Solaris, Windows 2000 Servers, and Windows 2003 Servers located in Berbank, California from a remote location in Boulder, Colorado.
- Diagnosed and solved basic OS and file system issues.
- Diagnosed and solved problems with SAP online backup to tape issues with Maestro Job Scheduler and Veritas Netbackup.
- Diagnosed and solved problems with OS and file system tape backups with Maestro Job Scheduler and Veritas Netbackup and Ultra Back.
- Escalated and routed trouble and change tickets to specialized groups within the team as needed using Service Center.
- Responsible to perform all OS and SAP tape restores as needed for disaster recovery using Veritas Netbackup.
- Assisted with Client Backup Infrastructure changes on a regular weekly basis using Maestro Job Scheduler to manage Online Backup to Tape jobs as needed.

### Systems Administrator for HP (Synova Contractor), Ft. Collins, CO.
*October 2004 - February 2006*
 
- Designed, deployed, and maintained High Availability MC Serviceguard clusters.
- Configured XP, SA20, and VA (7100-7410) Storage Arrays.
- Configured Storage Area Network for SVL PA RISC chip development lab.
- Administered Remedy (BLT) and Print Infrastructure servers.
- Designed, Deployed, and Administered HPUX 10.20 - 11.23 (PA & IA) and Debian/Redhat  Linux (X86\_64, X86, & IA64) servers for the SVL lab.
- Designed, Deployed, and Administered CVS repositories for Serviceguard (cluster and package) configuration files for ease of use and track-ability.
- Configured LVM volume groups and logical volumes (Commandline and GUI) for VXFS (HPUX) and Reiserfs (Debian Linux)
- Developed custom shell scripts for automation and ease of use of system administration processes.
- Designed Debian and Red-Hat images for rapid deployment using System Imager.
- UNIX/Linux kernel tweaking and re-compiling to meet developers needs.
- Designed custom shell scripts for propagation and automation of maintenance tasks for UNIX/Linux systems.
 
### Systems Administrator for IBM (GCI Contractor), Boulder, CO.
*October 2003 - October 2004*
 
- I supported around 300 servers in Boulder CO. and Westminister CO. Lincroft NJ.  Also supported infrastructure machines from Johnson & Johnson, Lucent , and Avaya.
- Maintained operating systems and their major file systems.
- Responded to ITO error messages and node downs routed to our group by our managed operations.
- I was responsible for dispatching vendor support for all Sun, HP, and IBM hardware problems.
- I created server change ticket information using HP Openview Service Desk system and managed the teams Manage Now trouble ticketing system.
- At this site I managed systems running Sun OS 2.5, 2.6, 2.7, 2.8, 2.9; HPUX 10.2 and 11.0; and AIX 4.3.3 and 5.1.
- I managed volume groups using Veritas volume manager, Solstice Disk Suite, and HPUX LVM (Logical Volume Manager).
- I managed software packages using Service Guard and Veritas Cluster Manager.
- Performed Tier 2 support for Omniback and Veritas Netbackup backups to remove stuck tapes and restart failed jobs.  Also I reinitialize hung tape drive arrays when Tier 3 was not on site.
- Ran Sym commands to manage EMC Symetrics arrays for splits and establishes needed for offline and online Oracle SAP backups.
- Designed custom shell scripts for propagation and automation of maintenance tasks for UNIX/Linux systems.

### Systems Administrator for HP (Kemtah Group Contractor), Ft. Collins, CO.
*February 2003 - October 2003*
 
- Performed custom installs of UNIX (Solaris, HPUX, Tru64, and AIX) workstations and servers for testers and developers in the HP Openview R&D lab.
- Performed custom installs of Linux workstations and servers for testers and developers in the HP Openview R&D Lab.
- Performed custom install of Windows (2000, 2003, & XP) workstations and servers for testers and developers in the HP Openview R&D Lab.
- Managed Omniback 3.5 and 4 environment for all development machines in the HP Openview R&D lab.
- Setup and configured all the development and testing machines for NIS NTP and Clearcase for Solaris, Linux, HPUX, Tru64, AIX, and windows.
- Performed multilingual installs of UNIX Linux and windows development machines.
- Mastered ISOs and media for developmental software for the UNIX and Windows platforms.
- Administered all test machines (UNIX, Linux, and Windows) for the HP Openview R&D lab.
- Did UNIX/Linux kernel tweaking and re-compiling to meet developers needs.
- Designed custom shell scripts for propagation and automation of maintenance tasks for UNIX/Linux systems.

### UNIX Systems Administrator for IBM (Analysts International Contractor), Boulder, CO.
*November 2000 - February 2002*
 
- I supported around 300 servers in Boulder CO. and Southbury New Jersey.
- Maintained operating systems and their major file systems.
- Responded to ITO error messages and node downs.
- I was responsible for dispatching vendor support for all Sun, HP, and NCR hardware problems.
- I created server change ticket information using IMSS mainframe system and managed the teams DPU trouble ticketing system.
- At this site I managed systems running Sun OS 2.5, 2.6, 2.7, & 2.8 and HPUX 10.2 and 11.0.
- I managed volume groups using Veritas volume manager, Solstice Disk Suite, and HPUX LVM (Logical Volume Manager).
- I managed software packages using Service Guard.
- Managed remote printers and their queues using  UNIX LP.
- Managed remote FAX systems using Dazel.
- Performed Tier 2 support for Omniback backups to remove stuck tapes and reinitialize hung tape drive arrays when Tier 3 was not on site.
- Performed filesystem backups using F-Backup on Sun and NCR servers.
- Designed custom shell scripts for propagation and automation of maintenance tasks for UNIX/Linux systems.

### Computer Consultant for BP/Amoco (Analyst International Contractor), Texas, Wyoming, Utah, New Mexico.
*July 2000 - August 2000*
 
- I personally installed and upgraded around 100 PCs and Laptops for BP/Amoco at refinery sites in Wyoming, Texas, and New Mexico.
- Setup personal Windows 2000 accounts to use the new COE (Common Operating Environment).
- Migrated Office 2000 user data from old PC to a swing server and back to new Windows 2000 IBM PCs or laptops.
- Installed new IBM PC with Windows 2000 using a Norton Multicast server running Windows 2000 Server.
- Upgraded old systems with new hard drives and memory to bring them up to date.

### Technician, 3rd Communication Squadron (Active Duty Air Force), Elmendorf Air Force Base, AK.
*May 1997 - May 2000*
 
- Installed, operated, maintained, troubleshot, and repaired the Mascom mainframe computer for the Mark IVB MDS running Mascom UNIX.
- Installed, maintained, operated, troubleshot and repaired two DEC Alpha workstations and one DEC Alpha Mainframe running True 64 UNIX.
- Helped design and configure an HTTP WAN network.
- Helped design and configure a firewall for the Mark IVB MDS LAN using Redhat 6.0.
- Designed a maintenance PC running Mandrake 7.0 complete with dialup backdoor and telnet through SSH2 for remote maintenance.
- Maintained National Weather Service (NWS) computer running HP-UX which NWS uses to get Defense Meteorological Satellite Program (DMSP) Weather Imagery.
- Designed, installed, maintained, troubleshot, and repaired a SAMBA file and print server for the building using Caldera Open LINUX.
- Configured, operated, and maintained around 10 Windows NT workstations for the SAMBA domain using TCP/IP.
- Installed and experimented with Slackware LINUX and x86 version of Solaris UNIX.
- Did UNIX/Linux kernel tweaking and re-compiling to meet the needs of the infrastructure.
- Designed custom shell scripts for propagation and automation of maintenance tasks for UNIX/Linux systems.

### Technician, 2nd Space Warning Squadron (Active Duty Air Force), Buckley Space Force Base, CO.
*September 1992 - May 1997*
 
- Maintained, Troubleshot, and repaired five IBM RISC600 workstations.
- Loaded and administered AIX UNIX and other system specific software.
- Archived system fault logs.
- Configured, maintained, and troubleshot the Satellite Readout Station in an X-Windows environment through a TCP/IP LAN.
- Designed Custom block diagrams for the Satellite Readout Station Status and control and Satellite Tracking and Status/Command Buffer LANs for training purposes.
- Trained eight other crew members on critical operations of the Satellite Readout Station.

## Education

## Space Systems Equipment Specialist Apprentice
*Lowry Air Force Base, CO*
*1992 - 1993*

## Space Systems Equipment Specialist Journeyman
*Buckley Space Force Base, CO*
*1993 - 1994*

## Satellite Readout Station Upgrade Maintenance
*IBM, Boulder, CO*
*1994 - 1994*

## Mark IV B Meteorological Data Station Operations and Maintenance
*Keesler Air Force Base, MS*
*1997 - 1997*

## Introduction to POSIX/UNIX
*Keesler Air Force Base, MS*
*1997 - 1997*

## Air Force Technical Order System
*Elmendorf Air Force Base, AK*
*1998 - 1998*

## Clear Case Overview Training
*HP, Ft. Collins, CO*
*2003 - 2003*

## Oracle Application Server Admin 1 Training
*Oracle, Colorado Springs, CO*
*2008 - 2008*

## HP Integrity Virtualization Training
*HP Virtual Classroom*
*2010 - 2010*

## HP Blade Enclosure Administration Training
*HP Virtual Classroom*
*2010 - 2010*

## HP Advanced Linux for Solaris and HP-UX Administrators training
*HP Virtual Classroom*
*2011 - 2011*

## Oracle WebLogic 11G Admin 1 Training
*Oracle Online Training*
*2012 - 2012*

## Puppet Enterprise Practitioner Instructor Lead
*Puppet Enterprise Online Classroom*
*2017 - 2017*

## Puppet Enterprise Advanced Developer Instructor Lead
*Puppet Enterprise Online Classroom*
*2018 - 2018*

## Other Skills

Extensive knowledge of RF and electronics test equipment, development of simple signal flow block diagrams, checklist development, and instructor skills.

## Hobbies

- Painting
- Sculpting
- Custom PCs
- Home server lab
- Retro Hardware Emulation
