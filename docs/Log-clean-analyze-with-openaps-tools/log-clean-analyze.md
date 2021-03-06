# Phase 1: Logging, Cleaning, and Analyzing Your Data

Phase 1 focuses on accessing, logging, cleaning up, and analyzing data from the pump and CGM. Data fidelity is extremely important, especially when dosing is being considered. Take the time to review what the openaps tools are outputting and carefully compare the logs against your own CareLink and CGM reports.

### Outline of Phase 1

* Upon Completion
    * Be able to download, record, and recall data logs from pump and CGM
    * Be able to download “real time” data
    * Have data being sent via wireless connection to a cloud database for user access
    * Have built a system able to collect data and be able to help others do the same


* Phase Tasks
    * Initalize new openaps environment
    * Add device tools, including oref0 virtual devices
    * Use tools to download data from pump and CGM (add reports)
    * Log data for future analysis, use in algorithms (invoke reports, create aliases)
    * Ensure fidelity and accuracy of recorded readings
    * Test edge cases
    * Log data “in real time” to test hardware functionality
    * Set up cloud database to accept uploaded data (optional)
    * Have logged data syncing to cloud database (optional)
    * Have your system backed up


* Community Contribution
    * Provide feedback on ...
        * Model-specific data issues (e.g. Medtronic 722 v 723)
        * Using software tools
        * Following guides to accomplish above phase tasks
    * Provide improved or alternative implementations

# Summary

* [Introduction](../../README.md)
* [Phase 0: General Setup](../../docs/getting-started/setup.md)
* [Phase 1: Logging, Cleaning, and Analyzing Your Data](../../docs/Log-clean-analyze-with-openaps-tools/log-clean-analyze.md)
   * [Configuring and Learning to Use openaps Tools](../../docs/Log-clean-analyze-with-openaps-tools/using.md)
* [Phase 2: Build a Manual System](../../docs/Build-manual-system/considerations.md)
* [Phase 3: Automate Your System](../../docs/Automate-system/considerations.md)
* [Phase 4: Iterate and Improve](../../docs/Iterate-improve/improvement-projects.md)
* [Resources](../../docs/Resources/resources.md)
