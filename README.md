==============================================
 ADHOC/BAU Tasks Playbooks and Roles
==============================================

Goal: Reduce the time to efficiently manage adhoc tasks required for Daily Checks, Incident and Problem Management

----------------------------------------------
 CHECKING UPTIME
----------------------------------------------
 Use Case: 	Check server uptime/status after infra-wide issues/outages
 Playbook: 	~/playbooks/adhoc-tasks/c_uptime.yml
 Role:		~/roles/check_uptime
----------------------------------------------

----------------------------------------------
 CHECKING LOGS
----------------------------------------------
 Use Case: 	Check server logs after infra-wide issues/outages
 Playbook: 	~/playbooks/adhoc-tasks/c_logs.yml
 Role:		~/roles/check_logs
----------------------------------------------

----------------------------------------------
 GATHERING SERVER STATS
----------------------------------------------
 Use Case: 	Gather server performance stats for incident/problem investigation
 Playbook: 	~/playbooks/adhoc-tasks/c_stats.yml
 Role:		~/roles/check_stats
----------------------------------------------

----------------------------------------------
 INSTALL PACKAGES
----------------------------------------------
 Use Case: 	Install additional packages required for incident/problem investigation
 Playbook: 	~/playbooks/adhoc-tasks/r_install.yml
 Role:		~/roles/install_tool
----------------------------------------------

----------------------------------------------
 SCHEDULING CRON JOBS
----------------------------------------------
 Use Case: 	Install scheduled jobs via cron for various purposes
 Playbook: 	~/playbooks/adhoc-tasks/r_cron.yml
 Role:		~/roles/install_cron
----------------------------------------------

----------------------------------------------
 RUNNING SCRIPTS
----------------------------------------------
 Use Case: 	Run scripts remotely for various vulnerability checks
 Playbook: 	~/playbooks/adhoc-tasks/r_script.yml
 Role:		~/roles/run_scr
----------------------------------------------