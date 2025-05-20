# Function: <code>sched_clock_register</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (0)
Location: include/linux/sched_clock.h:16
Inline: True
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void sched_clock_register(u64 (*read)(), int bits, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/sched_clock.c (ffff800011449170)
Location: kernel/time/sched_clock.c:168
Inline: False
Direct callers:
  - kernel/time/sched_clock.c:generic_sched_clock_init
  - drivers/clocksource/timer-rockchip.c:rk_timer_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-owl.c:owl_timer_init
  - drivers/clocksource/arm_arch_timer.c:arch_timer_common_init
  - drivers/clocksource/timer-sp804.c:__sp804_clocksource_and_sched_clock_init
  - drivers/clocksource/timer-versatile.c:versatile_sched_clock_init
```
**Symbols:**

```
ffff800011449170-ffff800011449360: sched_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sched_clock_register(u64 (*read)(), int bits, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/sched_clock.c (c1523250)
Location: kernel/time/sched_clock.c:168
Inline: False
Direct callers:
  - arch/arm/mach-omap2/timer.c:__omap_sync32k_timer_init
  - arch/arm/plat-omap/counter_32k.c:omap_init_clocksource_32k
  - kernel/time/sched_clock.c:generic_sched_clock_init
  - drivers/clocksource/renesas-ostm.c:ostm_init
  - drivers/clocksource/dw_apb_timer_of.c:dw_apb_timer_init
  - drivers/clocksource/timer-rockchip.c:rk_timer_init
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_common_init
  - drivers/clocksource/timer-orion.c:orion_timer_init
  - drivers/clocksource/timer-meson6.c:meson6_timer_init
  - drivers/clocksource/timer-tegra.c:tegra_init_timer
  - drivers/clocksource/exynos_mct.c:mct_init_dt
  - drivers/clocksource/timer-qcom.c:msm_dt_timer_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-ti-32k.c:ti_32k_timer_init
  - drivers/clocksource/timer-owl.c:owl_timer_init
  - drivers/clocksource/timer-milbeaut.c:mlb_timer_init
  - drivers/clocksource/arm_arch_timer.c:arch_timer_common_init
  - drivers/clocksource/arm_global_timer.c:global_timer_of_register
  - drivers/clocksource/timer-sp804.c:__sp804_clocksource_and_sched_clock_init
  - drivers/clocksource/timer-versatile.c:versatile_sched_clock_init
  - drivers/clocksource/timer-imx-gpt.c:_mxc_timer_init
  - drivers/clocksource/timer-imx-tpm.c:tpm_timer_init
```
**Symbols:**

```
c1523250-c152350c: sched_clock_register (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sched_clock_register(u64 (*read)(), int bits, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/sched_clock.c (ffffffe00000a638)
Location: kernel/time/sched_clock.c:168
Inline: False
Direct callers:
  - kernel/time/sched_clock.c:generic_sched_clock_init
  - drivers/clocksource/timer-riscv.c:riscv_timer_init_dt
```
**Symbols:**

```
ffffffe00000a638-ffffffe00000a7ec: sched_clock_register (STB_GLOBAL)
```
</details>
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
