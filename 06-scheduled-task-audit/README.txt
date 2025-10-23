About: review scheduled task health.
Goal: find disabled or failing tasks.
Practice: joining task metadata with runtime state.

Example
-------

Task                                 State   LastResult  Enabled
\Microsoft\Windows\Defrag\ScheduledDefrag Ready 0        True
Daily-Backup                          Disabled 0          False
Custom-Report                         Ready    0x1        False
