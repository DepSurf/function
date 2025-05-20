# Function: <code>pwrdm_state_switch_nolock</code>

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
int pwrdm_state_switch_nolock(struct powerdomain *pwrdm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/mach-omap2/powerdomain.c (c0345d90)
Location: arch/arm/mach-omap2/powerdomain.c:974
Inline: True
Direct callers:
  - arch/arm/mach-omap2/powerdomain.c:omap_set_pwrdm_state
  - arch/arm/mach-omap2/powerdomain.c:pwrdm_state_switch
  - arch/arm/mach-omap2/clockdomain.c:clkdm_hwmod_disable
  - arch/arm/mach-omap2/clockdomain.c:clkdm_clk_disable
  - arch/arm/mach-omap2/clockdomain.c:_clkdm_clk_hwmod_enable
  - arch/arm/mach-omap2/clockdomain.c:clkdm_wakeup_nolock
  - arch/arm/mach-omap2/clockdomain.c:clkdm_sleep_nolock
```
**Symbols:**

```
c0345d90-c0345de8: pwrdm_state_switch_nolock (STB_GLOBAL)
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
