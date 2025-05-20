# Function: <code>rtas_call</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rtas_call(int token, int nargs, int nret, int *outputs, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/rtas.c (c00000000003d280)
Location: arch/powerpc/kernel/rtas.c:444
Inline: False
Direct callers:
  - arch/powerpc/kernel/rtas.c:rtas_give_timebase
  - arch/powerpc/kernel/rtas.c:rtas_give_timebase
  - arch/powerpc/kernel/rtas.c:__rtas_suspend_last_cpu
  - arch/powerpc/kernel/rtas.c:rtas_os_term
  - arch/powerpc/kernel/rtas.c:rtas_halt
  - arch/powerpc/kernel/rtas.c:rtas_power_off
  - arch/powerpc/kernel/rtas.c:rtas_restart
  - arch/powerpc/kernel/rtas.c:rtas_set_indicator_fast
  - arch/powerpc/kernel/rtas.c:rtas_set_indicator
  - arch/powerpc/kernel/rtas.c:rtas_get_sensor_fast
  - arch/powerpc/kernel/rtas.c:rtas_get_sensor
  - arch/powerpc/kernel/rtas.c:rtas_set_power_level
  - arch/powerpc/kernel/rtas.c:rtas_get_power_level
  - arch/powerpc/kernel/rtas-rtc.c:rtas_set_rtc_time
  - arch/powerpc/kernel/rtas-rtc.c:rtas_get_rtc_time
  - arch/powerpc/kernel/rtas-rtc.c:rtas_get_boot_time
  - arch/powerpc/kernel/rtas_pci.c:rtas_read_config
  - arch/powerpc/kernel/rtas_pci.c:rtas_read_config
  - arch/powerpc/kernel/rtasd.c:rtas_event_scan
  - arch/powerpc/kernel/rtas-proc.c:ppc_rtas_tone_volume_write
  - arch/powerpc/kernel/rtas-proc.c:ppc_rtas_tone_freq_write
  - arch/powerpc/kernel/rtas-proc.c:ppc_rtas_sensors_show
  - arch/powerpc/kernel/rtas-proc.c:ppc_rtas_clock_show
  - arch/powerpc/kernel/rtas-proc.c:ppc_rtas_clock_write
  - arch/powerpc/kernel/rtas-proc.c:ppc_rtas_poweron_write
  - arch/powerpc/sysdev/xics/ics-rtas.c:ics_rtas_get_server
  - arch/powerpc/sysdev/xics/ics-rtas.c:ics_rtas_map
  - arch/powerpc/sysdev/xics/ics-rtas.c:ics_rtas_set_affinity
  - arch/powerpc/sysdev/xics/ics-rtas.c:ics_rtas_set_affinity
  - arch/powerpc/sysdev/xics/ics-rtas.c:ics_rtas_unmask_irq
  - arch/powerpc/sysdev/xics/ics-rtas.c:ics_rtas_unmask_irq
  - arch/powerpc/platforms/pseries/lpar.c:pseries_lpar_read_hblkrm_characteristics
  - arch/powerpc/platforms/pseries/nvram.c:pSeries_nvram_write
  - arch/powerpc/platforms/pseries/nvram.c:pSeries_nvram_read
  - arch/powerpc/platforms/pseries/setup.c:pseries_power_off
  - arch/powerpc/platforms/pseries/setup.c:pseries_power_off
  - arch/powerpc/platforms/pseries/setup.c:pSeries_cmo_feature_init
  - arch/powerpc/platforms/pseries/setup.c:pSeries_setup_arch
  - arch/powerpc/platforms/pseries/iommu.c:enable_ddw
  - arch/powerpc/platforms/pseries/iommu.c:enable_ddw
  - arch/powerpc/platforms/pseries/iommu.c:remove_ddw
  - arch/powerpc/platforms/pseries/ras.c:fwnmi_release_errinfo
  - arch/powerpc/platforms/pseries/ras.c:ras_error_interrupt
  - arch/powerpc/platforms/pseries/ras.c:ras_epow_interrupt
  - arch/powerpc/platforms/pseries/ras.c:ras_hotplug_interrupt
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_release_drc
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_acquire_drc
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_configure_connector
  - arch/powerpc/platforms/pseries/mobility.c:post_mobility_fixup
  - arch/powerpc/platforms/pseries/mobility.c:mobility_rtas_call
  - arch/powerpc/platforms/pseries/pci.c:pseries_send_map_pe
  - arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_send_allow_unfreeze
  - arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_configure_bridge
  - arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_get_log
  - arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_reset
  - arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_reset
  - arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_get_state
  - arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_get_state
  - arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_get_pe_addr
  - arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_get_pe_addr
  - arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_get_pe_addr
  - arch/powerpc/platforms/pseries/msi.c:rtas_change_msi
  - arch/powerpc/platforms/pseries/msi.c:rtas_change_msi
  - arch/powerpc/platforms/pseries/smp.c:smp_pSeries_kick_cpu
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:__machine_initcall_pseries_pseries_cpu_hotplug_init
  - arch/powerpc/platforms/pseries/io_event_irq.c:ioei_interrupt
  - arch/powerpc/platforms/pseries/lparcfg.c:parse_system_parameter_string
  - arch/powerpc/platforms/pseries/rtas-fadump.c:rtas_fadump_invalidate
  - arch/powerpc/platforms/pseries/rtas-fadump.c:rtas_fadump_unregister
  - arch/powerpc/platforms/pseries/rtas-fadump.c:rtas_fadump_register
  - drivers/tty/hvc/hvc_rtas.c:hvc_rtas_read_console
  - drivers/tty/hvc/hvc_rtas.c:hvc_rtas_write_console
```
**Symbols:**

```
c00000000003d280-c00000000003d5b8: rtas_call (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
