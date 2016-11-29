# munin plugins

some munin plugins i wrote. typically in php.

- ``processes_memory`` : monitor top `n` processes rss/vsz over time
  - requires: `bcmath`
  - the rss/vsz value of all descendant processes are being summed up
  - usage 
    - example: ``processes_memory_20_rss`` to plot the top 20 rss processes over time
    - example: ``processes_memory_10_vsz`` to plot the top 10 vsz processes over time