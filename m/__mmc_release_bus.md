# Function: <code>__mmc_release_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __mmc_release_bus(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816bda70)
Location: drivers/mmc/core/core.c:1783
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_power_restore_host
  - drivers/mmc/core/core.c:mmc_power_restore_host
  - drivers/mmc/core/core.c:mmc_power_save_host
  - drivers/mmc/core/core.c:mmc_power_save_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
```
**Symbols:**

```
ffffffff816bda70-ffffffff816bdaa4: __mmc_release_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __mmc_release_bus(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8171f690)
Location: drivers/mmc/core/core.c:1799
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_power_restore_host
  - drivers/mmc/core/core.c:mmc_power_restore_host
  - drivers/mmc/core/core.c:mmc_power_save_host
  - drivers/mmc/core/core.c:mmc_power_save_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
```
**Symbols:**

```
ffffffff8171f690-ffffffff8171f6c4: __mmc_release_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81755db6)
Location: drivers/mmc/core/core.c:1869
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_power_restore_host
  - drivers/mmc/core/core.c:mmc_power_restore_host
  - drivers/mmc/core/core.c:mmc_power_save_host
  - drivers/mmc/core/core.c:mmc_power_save_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_detach_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81773e68)
Location: drivers/mmc/core/core.c:1694
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_power_restore_host
  - drivers/mmc/core/core.c:mmc_power_restore_host
  - drivers/mmc/core/core.c:mmc_power_save_host
  - drivers/mmc/core/core.c:mmc_power_save_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_detach_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __mmc_release_bus(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817e6520)
Location: drivers/mmc/core/core.c:1908
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_power_restore_host
  - drivers/mmc/core/core.c:mmc_power_restore_host
  - drivers/mmc/core/core.c:mmc_power_save_host
  - drivers/mmc/core/core.c:mmc_power_save_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_detach_bus
```
**Symbols:**

```
ffffffff817e6520-ffffffff817e654d: __mmc_release_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __mmc_release_bus(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8182f320)
Location: drivers/mmc/core/core.c:1712
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_power_restore_host
  - drivers/mmc/core/core.c:mmc_power_restore_host
  - drivers/mmc/core/core.c:mmc_power_save_host
  - drivers/mmc/core/core.c:mmc_power_save_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_detach_bus
```
**Symbols:**

```
ffffffff8182f320-ffffffff8182f34d: __mmc_release_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __mmc_release_bus(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185b590)
Location: drivers/mmc/core/core.c:1715
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_detach_bus
```
**Symbols:**

```
ffffffff8185b590-ffffffff8185b5bd: __mmc_release_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __mmc_release_bus(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1397
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_detach_bus
```
**Symbols:**

```
ffffffff8189f9d0-ffffffff8189f9f8: __mmc_release_bus (STB_LOCAL)
ffffffff818a3cd7-ffffffff818a3cea: __mmc_release_bus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818d6150)
Location: drivers/mmc/core/core.c:1397
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_detach_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a8a94)
Location: drivers/mmc/core/core.c:1380
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_detach_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819abb54)
Location: drivers/mmc/core/core.c:1380
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_detach_bus
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2ff20)
Location: drivers/mmc/core/core.c:1397
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_detach_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c0c0b06c)
Location: drivers/mmc/core/core.c:1397
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_detach_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __mmc_release_bus(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c23300)
Location: drivers/mmc/core/core.c:1397
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_detach_bus
```
**Symbols:**

```
c000000000c23300-c000000000c23324: __mmc_release_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe000708ec0)
Location: drivers/mmc/core/core.c:1397
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_detach_bus
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81879b10)
Location: drivers/mmc/core/core.c:1397
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_detach_bus
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818cafb0)
Location: drivers/mmc/core/core.c:1397
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_detach_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818e7ad0)
Location: drivers/mmc/core/core.c:1397
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_sw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_hw_reset
  - drivers/mmc/core/core.c:mmc_detach_bus
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
