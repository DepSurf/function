# Function: <code>__arch_xprod_64</code>

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
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
uint64_t __arch_xprod_64(uint64_t m, uint64_t n, bool bias);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/vfp/vfpsingle.c (c0307540)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - arch/arm/vfp/vfpsingle.c:vfp_estimate_sqrt_significand
```
```
In arch/arm/vfp/vfpdouble.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In arch/arm/kernel/smp.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In arch/arm/mach-omap2/timer.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In arch/arm/mach-omap2/vc.c (c1517674)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - arch/arm/mach-omap2/vc.c:omap_vc_init_channel
  - arch/arm/mach-omap2/vc.c:omap_vc_init_channel
```
```
In kernel/sched/core.c (c038771c)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_max_write
  - kernel/sched/core.c:cpu_max_show
  - kernel/sched/core.c:cpu_weight_write_u64
  - kernel/sched/core.c:cpu_extra_stat_show
  - kernel/sched/core.c:tg_cfs_schedulable_down
  - kernel/sched/core.c:cpu_cfs_period_read_u64
  - kernel/sched/core.c:tg_get_cfs_quota
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:cpu_uclamp_max_show
  - kernel/sched/core.c:cpu_uclamp_min_show
```
```
In kernel/sched/cputime.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In kernel/sched/rt.c (c039edc8)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_group_rt_period
  - kernel/sched/rt.c:sched_group_rt_runtime
```
```
In kernel/sched/deadline.c (c03a0a44)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/sched/pelt.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In kernel/sched/debug.c (c03ac718)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - kernel/sched/debug.c:nsec_low
```
```
In kernel/sched/psi.c (c03b3854)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_destroy
```
```
In kernel/power/main.c (c03ba0ec)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - kernel/power/main.c:ksys_sync_helper
```
```
In kernel/power/process.c (c03ba528)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In kernel/power/hibernate.c (c03bc5fc)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - kernel/power/hibernate.c:swsusp_show_speed
```
```
In kernel/power/snapshot.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In kernel/power/wakelock.c (c03c4330)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/printk/printk.c (c03c5bf0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - kernel/printk/printk.c:msg_print_text
```
```
In kernel/time/time.c (c03e5314)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - kernel/time/time.c:nsecs_to_jiffies
  - kernel/time/time.c:nsec_to_clock_t
  - kernel/time/time.c:jiffies_64_to_clock_t
  - kernel/time/time.c:jiffies_to_clock_t
  - kernel/time/time.c:jiffies_to_timeval
  - kernel/time/time.c:jiffies_to_timespec64
```
```
In kernel/time/timer.c (c03e9bec)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - kernel/time/timer.c:get_next_timer_interrupt
```
```
In kernel/time/hrtimer.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In kernel/time/ntp.c (c03f0ba8)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_update_frequency
  - kernel/time/ntp.c:ntp_update_frequency
```
```
In kernel/time/clocksource.c (c03f1edc)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_max_adjustment
```
```
In kernel/time/jiffies.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In kernel/time/tick-sched.c (c03ff10c)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:get_cpu_iowait_time_us
  - kernel/time/tick-sched.c:get_cpu_idle_time_us
```
```
In kernel/acct.c (c040e658)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - kernel/acct.c:fill_ac
  - kernel/acct.c:fill_ac
  - kernel/acct.c:fill_ac
  - kernel/acct.c:fill_ac
  - kernel/acct.c:check_free_space
  - kernel/acct.c:check_free_space
```
```
In kernel/cgroup/cgroup.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In kernel/cgroup/rstat.c (c041c7ac)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
```
In kernel/debug/kdb/kdb_main.c (c043f338)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In kernel/relay.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In kernel/taskstats.c (c044c140)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/tsacct.c (c044cb84)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/trace/ftrace.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In kernel/trace/trace.c (c045fedc)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
```
```
In kernel/trace/trace_output.c (c0469e20)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
```
```
In kernel/trace/trace_hwlat.c (c046dc9c)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/trace/trace_functions_graph.c (c046f300)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_print_graph_duration
  - kernel/trace/trace_functions_graph.c:print_graph_rel_time
  - kernel/trace/trace_functions_graph.c:print_graph_abs_time
```
```
In kernel/trace/blktrace.c (c0471bd8)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_log_action_classic
```
```
In kernel/bpf/verifier.c (c049a700)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In kernel/events/core.c (c04c49e0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - kernel/events/core.c:update_perf_cpu_limits
```
```
In mm/page-writeback.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In mm/vmscan.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In mm/shmem.c (c04fa7b4)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_one
```
```
In mm/vmstat.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In mm/page_alloc.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In mm/slub.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In fs/proc/uptime.c (c060da84)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In fs/ext4/extents_status.c (c062f074)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In fs/ext4/resize.c (c066a06c)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (c0683828)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:perf_trace_ext4_es_shrink
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink
```
```
In fs/jbd2/journal.c (c06975c4)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In security/keys/proc.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In block/blk-sysfs.c (c0793730)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wb_lat_show
```
```
In block/blk-settings.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In block/blk-merge.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In block/blk-lib.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: False
```
```
In block/blk-stat.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In block/genhd.c (c07a5554)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In block/partition-generic.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In block/partitions/efi.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In block/blk-throttle.c (c07bd3e0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
```
```
In block/blk-iocost.c (c07c12a8)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_now
```
```
In block/blk-wbt.c (c07c9acc)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
```
```
In lib/string_helpers.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In lib/kstrtox.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In lib/math/div64.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In lib/math/reciprocal_div.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In lib/dim/dim.c (c080e824)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - lib/dim/dim.c:dim_calc_stats
```
```
In drivers/phy/phy-core-mipi-dphy.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/gpio/gpio-mvebu.c (c086b5d0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_apply
  - drivers/gpio/gpio-mvebu.c:mvebu_pwm_apply
```
```
In drivers/pwm/core.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/pci/setup-bus.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/clk-divider.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/clk-fixed-factor.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/clk-fractional-divider.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/clk-hsdk-pll.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/clk-npcm7xx.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/clk-qoriq.c (c1556304)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - drivers/clk/clk-qoriq.c:clockgen_init
```
```
In drivers/clk/actions/owl-factor.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/berlin/berlin2-avpll.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/berlin/berlin2-pll.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/imx/clk-frac-pll.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/imx/clk-pfd.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/imx/clk-pfdv2.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/imx/clk-pllv1.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/imx/clk-pllv2.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/imx/clk-pllv3.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/imx/clk-pllv4.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/imx/clk-sccg-pll.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/imx/clk-pll14xx.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/mediatek/clk-pll.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/meson/clk-mpll.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/meson/clk-pll.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/mvebu/common.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/renesas/clk-rcar-gen2.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/renesas/rcar-gen2-cpg.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/rockchip/clk-pll.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/rockchip/clk-half-divider.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/samsung/clk-pll.c (c090a8e4)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - drivers/clk/samsung/clk-pll.c:samsung_pll46xx_set_rate
  - drivers/clk/samsung/clk-pll.c:samsung_pll45xx_set_rate
```
```
In drivers/clk/tegra/clk-divider.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/tegra/clk-periph-fixed.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/tegra/clk-pll.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/tegra/clk-sdmmc-mux.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/tegra/clk-utils.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/ti/divider.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/ti/clkt_dpll.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/ti/clkctrl.c (c0918604)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/ti/dpll3xxx.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/ti/fapll.c (c091a144)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - drivers/clk/ti/fapll.c:ti_fapll_synth_round_rate
```
```
In drivers/clk/ti/adpll.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/clk/versatile/icst.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/soc/amlogic/meson-clk-measure.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/soc/tegra/pmc.c (c093dfa8)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - drivers/soc/tegra/pmc.c:tegra_pmc_enter_suspend_mode
  - drivers/soc/tegra/pmc.c:tegra_pmc_enter_suspend_mode
```
```
In drivers/tty/serial/imx.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/base/dd.c (c09d83dc)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/base/power/sysfs.c (c09e3f64)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:runtime_suspended_time_show
  - drivers/base/power/sysfs.c:runtime_active_time_show
```
```
In drivers/base/power/main.c (c09eabf4)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_show_time
```
```
In drivers/base/power/wakeup.c (c09ee6d4)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/base/power/wakeup_stats.c (c09ef5b8)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show
  - drivers/base/power/wakeup_stats.c:last_change_ms_show
  - drivers/base/power/wakeup_stats.c:max_time_ms_show
  - drivers/base/power/wakeup_stats.c:total_time_ms_show
  - drivers/base/power/wakeup_stats.c:active_time_ms_show
```
```
In drivers/base/power/domain.c (c09f3e3c)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - drivers/base/power/domain.c:active_time_show
  - drivers/base/power/domain.c:idle_states_show
```
```
In drivers/ata/libata-scsi.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_std_bios_param
```
```
In drivers/ata/libata-transport.c (c0a7d5a8)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/mtd/mtdcore.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/mtd/mtdconcat.c (c0a915b4)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/mtd/mtdpart.c (c0a94c28)
Location: arch/arm/include/asm/div64.h:75
Inline: False
```
```
In drivers/mtd/nand/core.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/mtd/nand/raw/nand_base.c (c0a9ef84)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_base.c:nand_erase_op
  - drivers/mtd/nand/raw/nand_base.c:nand_prog_page_end_op
  - drivers/mtd/nand/raw/nand_base.c:nand_exec_prog_page_op
  - drivers/mtd/nand/raw/nand_base.c:nand_read_param_page_op
  - drivers/mtd/nand/raw/nand_base.c:nand_read_page_op
  - drivers/mtd/nand/raw/nand_base.c:nand_lp_exec_read_page_op
```
```
In drivers/spi/spi.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/net/ethernet/ti/cpts.c (c0ad1834)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpts.c:cpts_ptp_adjfreq
```
```
In drivers/net/ethernet/ti/davinci_cpdma.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/usb/dwc2/core.c (c0b0d518)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/usb/host/xhci.c (c0b4414c)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_calculate_u2_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u1_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u1_timeout
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c0b99bc0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/i2c/busses/i2c-s3c2410.c (c0b9e8d8)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_wait_idle
```
```
In drivers/ptp/ptp_clock.c (c0ba6ef0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/power/supply/charger-manager.c (c0baf8c4)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/thermal/thermal_sysfs.c (c0bb7eb8)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
```
```
In drivers/thermal/power_allocator.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/thermal/cpu_cooling.c (c0bbcb7c)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
```
```
In drivers/thermal/devfreq_cooling.c (c0bbd5e8)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:get_dynamic_power
```
```
In drivers/md/md.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/md/dm.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/md/dm-stripe.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/md/dm-io.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: False
```
```
In drivers/md/dm-stats.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (c0bfab04)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (c0bff80c)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (c0c0175c)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/cpuidle/governors/menu.c (c0c03e5c)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/cpuidle/governors/teo.c (c0c0477c)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/mmc/host/mmci.c (c0c20a38)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_start_data
```
```
In drivers/mmc/host/sdhci.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/mmc/host/omap_hsmmc.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/firmware/tegra/bpmp.c (c0c41f58)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer_atomic
```
```
In drivers/clocksource/sh_cmt.c (c0c44ce8)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/devfreq/governor_simpleondemand.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In drivers/memory/tegra/mc.c (c0c73ff0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - drivers/memory/tegra/mc.c:tegra_mc_probe
```
```
In sound/core/pcm_lib.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In sound/soc/codecs/sgtl5000.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In sound/soc/fsl/fsl_ssi.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In net/ipv4/tcp.c (c0d7f0a0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_time_stamp_raw
```
```
In net/ipv4/tcp_input.c (c0d8ceac)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (c0d93da0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_mstamp_refresh
```
```
In net/ipv4/tcp_timer.c (c0d97b48)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (c0d9c1a0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack
```
```
In net/ipv4/tcp_minisocks.c (c0d9e590)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In net/ipv4/tcp_rate.c (c0da2bf4)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (c0da3068)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
  - net/ipv4/tcp_recovery.c:tcp_rack_skb_timeout
```
```
In net/ipv4/af_inet.c (c0db7c18)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_current_timestamp
```
```
In net/ipv4/fib_semantics.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In net/ipv4/syncookies.c (c0ddbc50)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv4/tcp_cubic.c (c0ddcddc)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/ipv6/addrconf.c (c0e0e1c0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
```
```
In net/ipv6/route.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (c0e39f10)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack
```
```
In net/ipv6/syncookies.c (c0e4d6cc)
Location: arch/arm/include/asm/div64.h:75
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
```
In net/xdp/xdp_umem.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
```
In lib/vsprintf.c (0)
Location: arch/arm/include/asm/div64.h:75
Inline: True
```
**Symbols:**

```
c066b770-c066b808: __arch_xprod_64 (STB_LOCAL)
c0a915b4-c0a9164c: __arch_xprod_64 (STB_LOCAL)
c0a94c28-c0a94cc8: __arch_xprod_64 (STB_LOCAL)
c0ad0520-c0ad05b8: __arch_xprod_64 (STB_LOCAL)
c0ddc7a0-c0ddc838: __arch_xprod_64 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
