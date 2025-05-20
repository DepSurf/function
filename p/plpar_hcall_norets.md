# Function: <code>plpar_hcall_norets</code>

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

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/powerpc/kernel/rtas.c:__rtas_suspend_cpu
  - arch/powerpc/kernel/rtas.c:__rtas_suspend_cpu
  - arch/powerpc/kernel/rtas.c:__rtas_suspend_last_cpu
  - arch/powerpc/lib/locks.c:splpar_rw_yield
  - arch/powerpc/lib/locks.c:splpar_spin_yield
  - arch/powerpc/sysdev/xics/icp-hv.c:icp_hv_ipi_action
  - arch/powerpc/sysdev/xics/icp-hv.c:icp_hv_cause_ipi
  - arch/powerpc/sysdev/xics/icp-hv.c:icp_hv_set_cpu_priority
  - arch/powerpc/sysdev/xics/icp-hv.c:icp_hv_get_irq
  - arch/powerpc/sysdev/xics/icp-hv.c:icp_hv_flush_ipi
  - arch/powerpc/sysdev/xics/icp-hv.c:icp_hv_teardown_cpu
  - arch/powerpc/sysdev/xics/icp-hv.c:icp_hv_eoi
  - arch/powerpc/sysdev/xive/spapr.c:xive_spapr_sync_source
  - arch/powerpc/sysdev/xive/spapr.c:xive_spapr_shutdown
  - arch/powerpc/sysdev/xive/spapr.c:xive_spapr_configure_irq
  - arch/powerpc/sysdev/xive/spapr.c:plpar_int_set_queue_config
  - arch/powerpc/platforms/pseries/lpar.c:pseries_lpar_resize_hpt
  - arch/powerpc/platforms/pseries/lpar.c:pseries_lpar_resize_hpt
  - arch/powerpc/platforms/pseries/lpar.c:pseries_lpar_resize_hpt_commit
  - arch/powerpc/platforms/pseries/lpar.c:pSeries_lpar_hpte_updateboltedpp
  - arch/powerpc/platforms/pseries/lpar.c:pSeries_lpar_hpte_updatepp
  - arch/powerpc/platforms/pseries/lpar.c:vpa_init
  - arch/powerpc/platforms/pseries/lpar.c:vpa_init
  - arch/powerpc/platforms/pseries/lpar.c:dtl_worker_offline
  - arch/powerpc/platforms/pseries/lpar.c:register_dtl_buffer
  - arch/powerpc/platforms/pseries/setup.c:pseries_set_dawr
  - arch/powerpc/platforms/pseries/setup.c:pseries_set_xdabr
  - arch/powerpc/platforms/pseries/setup.c:pseries_set_dabr
  - arch/powerpc/platforms/pseries/setup.c:pseries_little_endian_exceptions
  - arch/powerpc/platforms/pseries/setup.c:pseries_big_endian_exceptions
  - arch/powerpc/platforms/pseries/setup.c:pseries_disable_reloc_on_exc
  - arch/powerpc/platforms/pseries/setup.c:pseries_enable_reloc_on_exc
  - arch/powerpc/platforms/pseries/setup.c:pseries_lpar_enable_pmcs
  - arch/powerpc/platforms/pseries/iommu.c:tce_exchange_pseries
  - arch/powerpc/platforms/pseries/iommu.c:tce_setrange_multi_pSeriesLP
  - arch/powerpc/platforms/pseries/iommu.c:tce_clearrange_multi_pSeriesLP
  - arch/powerpc/platforms/pseries/iommu.c:tce_free_pSeriesLP
  - arch/powerpc/platforms/pseries/smp.c:smp_pSeries_kick_cpu
  - arch/powerpc/platforms/pseries/kexec.c:pseries_kexec_cpu_down
  - arch/powerpc/platforms/pseries/kexec.c:pseries_kexec_cpu_down
  - arch/powerpc/platforms/pseries/kexec.c:pseries_kexec_cpu_down
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_remove
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_mach_cpu_die
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_mach_cpu_die
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_mach_cpu_die
  - arch/powerpc/platforms/pseries/hvconsole.c:hvc_put_chars
  - arch/powerpc/platforms/pseries/dtl.c:dtl_file_release
  - arch/powerpc/platforms/pseries/dtl.c:dtl_file_open
  - arch/powerpc/platforms/pseries/lparcfg.c:update_mpp
  - arch/powerpc/platforms/pseries/lparcfg.c:update_ppp
  - arch/powerpc/platforms/pseries/vio.c:vio_disable_interrupts
  - arch/powerpc/platforms/pseries/vio.c:vio_enable_interrupts
  - arch/powerpc/platforms/pseries/vio.c:vio_h_cop_sync
  - arch/powerpc/perf/hv-24x7.c:make_24x7_request
  - arch/powerpc/perf/hv-24x7.c:h_get_24x7_catalog_page_
  - arch/powerpc/perf/hv-gpci.c:single_gpci_request
  - arch/powerpc/perf/hv-common.c:hv_perf_caps_get
  - drivers/tty/hvc/hvsi.c:hvsi_unthrottle
  - drivers/tty/hvc/hvsi.c:hvsi_unthrottle
  - drivers/tty/hvc/hvsi.c:hvsi_throttle
  - drivers/tty/hvc/hvsi.c:hvsi_throttle
  - drivers/tty/hvc/hvsi.c:hvsi_close
  - drivers/tty/hvc/hvsi.c:hvsi_open
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe
  - drivers/char/tpm/tpm_ibmvtpm.c:ibmvtpm_interrupt
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_resume
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_suspend
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_remove
  - drivers/char/tpm/tpm_ibmvtpm.c:ibmvtpm_crq_send_init
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_send
  - drivers/cpuidle/cpuidle-pseries.c:check_and_cede_processor
```
**Symbols:**

```
c0000000000eb804-c0000000000eb804: plpar_hcall_norets (STB_GLOBAL)
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
