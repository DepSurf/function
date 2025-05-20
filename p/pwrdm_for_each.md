# Function: <code>pwrdm_for_each</code>

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
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pwrdm_for_each(int (*fn)(struct powerdomain *, void *), void *user);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/mach-omap2/powerdomain.c (c0346538)
Location: arch/arm/mach-omap2/powerdomain.c:437
Inline: True
Inline callers:
  - arch/arm/mach-omap2/powerdomain.c:pwrdms_lost_power
  - arch/arm/mach-omap2/powerdomain.c:pwrdms_restore_context
  - arch/arm/mach-omap2/powerdomain.c:pwrdms_save_context
  - arch/arm/mach-omap2/powerdomain.c:pwrdm_post_transition
  - arch/arm/mach-omap2/powerdomain.c:pwrdm_pre_transition
Direct callers:
  - arch/arm/mach-omap2/pm34xx.c:omap3_pm_init
  - arch/arm/mach-omap2/pm44xx.c:omap4_pm_init
  - arch/arm/mach-omap2/pm-debug.c:__pm_dbg_init
  - arch/arm/mach-omap2/pm-debug.c:pm_dbg_timers_show
  - arch/arm/mach-omap2/pm-debug.c:pm_dbg_counters_show
```
**Symbols:**

```
c0344fec-c0345058: pwrdm_for_each (STB_GLOBAL)
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
