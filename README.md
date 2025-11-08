# Rob Beasley

### Seeking
    Staff\Principal\Senior Software Engineer Roles – Oregon, Portugal, or Remote

### Skills
    Embedded Software                          15 years
    Hardware Bring–up                          12 years
    C\C++                                      15 years
    SW\HW Debug                                15 years
    C#                                         10 years
    SOC Debug & Validation                      4 years
    Python                                      8 years
    Linux I2C & SPI Drivers                     2 years

<details>
  <summary><h3>Work History</h3></summary>
  
  → [Detailed Work Experience](#detailed-work-experience)  
  → <https://www.linkedin.com/in/robbeasley>
</details>  

<sub> December 2024 – Current </sub>  
&nbsp;`Senior Embedded Software Engineer      – Thermo Fisher – Hillsboro, OR`  
<sub> September 2014 – November 2024 </sub>  
&nbsp;`Senior Software Engineer               – Intel         – Hillsboro, OR`  
<sub> March 2011 – August 2014 </sub>  
&nbsp;`Senior Software Development Engineer   – Harmonic      – Beaverton, OR`  
<sub> April 2008 – March 2011 </sub>  
&nbsp;`Principal & Senior Software Engineer   – Cognex        – Tigard, OR`  
<sub> June 2001 – March 2008 </sub>  
&nbsp;`Software Design Engineer III, II, & I  – Tektronix     – Beaverton, OR`  

### Education
    BS Computer Science – 2001           University of Idaho – Moscow, ID

### Publications & Accomplishments
    US Patent 7,227,549 B2 (Software)
    US Patent 7,516,028 B2 (Software)
    US Patent 8,055,077 B2 (FPGA & Software)
    Certified ScrumMaster®: Credential ID 468579
    President's Award at Cognex for developing Track&Trace audit logging system.
    Program Manager for HW & SW: Cognex In–Sight ® 1740 Series Wafer ID Readers
    Hobby development of 4.6–star iOS app 'The Bowling Buddy' (12 years)

### What I Bring
    I am passionate about software, but even more passionate about people.
    Everything we do is for people. Our customers, co–workers, and community
    all play a vital role in our success. I believe that business moves at the
    speed of trust. By building trust with the people touched by our business
    and products, we generate lasting success together. I bring this philosophy
    with me each day. Striving to generate trust with my team, our customers,
    and stakeholders to jointly create robust solutions to complex problems.

    We should talk, call or text me at +1(503)718–8456.
    –Rob

********************************************************************************

## Detailed Work Experience

#### Thermo Fisher Scientific – Senior Embedded Software Engineer
    TEMLink™ Software: Led team as Scrum Master while continuing to develop software.  
    Quickly ramped on existing legacy codebase, looking for opportunities to reduce  
    architectural complexity and improve product reliability. Modernized outdated  
    legacy code to x64, C++20, and latest .NET releases, using a gRPC microservice  
    architecture. Added support for a new camera and other new hardware.  
    Reworked the CI/CD pipeline utilizing Jenkins, GitLab, NuGet and Thermo Fisher’s  
    in–house dependency manager. Implemented automated versioning, packaging, and 
    deployment of backend API NuGet package, for use by other teams across the  
    organization. Improved error handling and propagation across process boundaries,  
    including marshaling data from native to managed memory spaces. Created 
    installer package for backend, UI, services, and dependencies for the full 
    software stack.  This included managing user level security access, creating 
    and deploying SSL certificates, and managing DCOM security and registration.
#### Intel Corporation – Senior Software Engineer
    Worked on multiple versions of client–side update application (Python\C++).
    Developed features and bug fixes for a headless SDK model of the update
    service for Windows. Scrum Master and contributor for effort to port the SDK
    to work on both Windows and Ubuntu from a single codebase managed in Git.
    Efforts included reworking the build system, unit tests, and acceptance
    tests to function correctly on both OSes.

    Led our team in developing a proof–of–concept IoT manageability application.
    We delivered high quality demo code with a feature set exceeding original
    expectations, despite resource constraints, tight schedule, and logistical
    challenges. After the demo, we extended the reach of our solution by making
    it a cross–platform (Linux/Windows/OS X), set of micro–services and clients
    in C++ cross–complied using CMAKE.

    Platform level SOC debug and validation for Over Clocking, Power Management,
    and Type–C Subsystem for Intel’s workstation platforms (Server CPU paired
    with Consumer PCH). Utilized WinDbg, Intel IPT eXtended Debug Port, power
    meters, and my own code to characterize and debug SOC platform and Windows
    behavior with each prerelease combination of firmware\OS\drivers (created
    every two weeks). Coordinated work of US contractors reporting to Bangalore
    based manager and company.

    Worked on a wide variety of technologies implementing features and bug fixes
    for the Context SDK. Highly agile environment with multiple disparate
    customers and priorities. We provided the SDK in Swift, NodeJS, C#, Java,
    and Go. Led the development of the Swift version of the Context SDK that
    works for both iOS and macOS. Mentored new team members when team doubled in
    size, training them on Git/GitLab, the build system, our microservices
    architecture, and our development environment.

    Spearheaded effort to develop Planning Systems & Software for manufacturing
    capacity planning needs. Systems were built using SQL Server Data Tools, C#,
    and related technologies. When budget and schedule constraints arose, I
    rearchitected both frontend and backend solutions to allow a six–month
    project to be completed in 3 months with just 2 developers instead of 5.

#### Harmonic Inc. – Senior Software Development Engineer
    Wrote C++ embedded applications, drivers, diagnostics, and environmental
    controls (thermal management) for video servers running Linux. Worked with
    Hardware/FPGA Team to bring up new board with custom FPGA. Wrote combined
    Linux Kernel Drivers for an I2C and SPI bus sharing a common PCIe memory
    mapped register. Architected and implemented embedded C++ microservice for
    environmental control. The microservice had to use readings from various
    embedded sensors on the backplane board and on two separate hot swappable
    units each with independent CPUs in a 1 RU chassis. Wrote several diagnostic
    tests for Manufacturing to use from testing the I2C buses and various
    devices such as power supplies, NVRAM components, and temperature sensors
    scattered across the various I2C buses of the 3 boards.

#### Cognex – Principal Software Engineer & Senior Software Engineer
    Wafer ID: Program Manager and key contributor for firmware(C++) and UI(C#)
    of 1740 Series products. Firmware and GUI development of numerous product
    enhancements through multiple release cycles. Developed firmware solution to
    automatically select the best settings for lighting, character size, and
    dynamically applying image processing algorithms for optimal OCR accuracy.
    Improved ID reading algorithm to simultaneously check for black–on–white
    and white–on–black characters with zero increase in processing time.

    Track and Trace: Firmware and Windows application development of Audit
    logging system. Developed a .NET TCP/IP messaging system in C++/C# to log
    settings changes made to embedded camera. Architected a messaging protocol,
    implemented queued TCP/IP messaging in the firmware (C++), developed a 
    Windows service(C#) to receive the messages, created a GUI to manage this
    service, and provided an API for customers that allowed them to easily
    integrate the data with their manufacturing systems.

#### Tektronix Software Design Engineer III, II, and I
    Technical Lead for small software team building cross process memory manager
    for C++/C# applications. Software utilized remote procedure calls to 
    coordinate data creation and utilization between Windows .NET applications
    without the need for a centralized service.

    Wrote embedded C/C++ software for oscilloscopes using VxWorks and Windows.
    Designed and implemented embedded software for 3 generations of display
    hardware embedded in a custom ASIC. Collaborated with hardware engineers in
    turning on and debugging chips/boards. Leveraged multiple custom ASICs to
    draw a single coherent display, increasing display frame rates 10X. Created
    reusable display software utilized on multiple models of oscilloscopes, each
    with varying numbers of ASICs. Also designed, implemented, and maintained
    automated CI\CD system for nightly and on demand software builds.

    Designed and implemented MultiView Zoom™ feature of Tektronix Oscilloscopes.
    
********************************************************************************

See more @ <https://www.linkedin.com/in/robbeasley>

<details>
<summary> </summary>
  
  → <https://www.linkedin.com/in/robbeasley> 
  → <https://www.linkedin.com/in/robbeasley> 
</details>
