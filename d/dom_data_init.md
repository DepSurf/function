# Function: <code>dom_data_init</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff810447c7)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:408
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:rdt_get_mon_l3_config
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff81047f98)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:408
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:rdt_get_mon_l3_config
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff8104a816)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:564
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:rdt_get_mon_l3_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105ab96)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:561
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105deb0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:553
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e76c)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:553
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810638f0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:557
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
```
**Symbols:**

```
ffffffff810638f0-ffffffff810639b3: dom_data_init.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81061d10)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:609
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
```
**Symbols:**

```
ffffffff81061d10-ffffffff81061dd3: dom_data_init.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810624e0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:608
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
```
**Symbols:**

```
ffffffff810624e0-ffffffff810625a0: dom_data_init.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8106c350)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:623
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
```
**Symbols:**

```
ffffffff8106c350-ffffffff8106c410: dom_data_init.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81079710)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:623
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
```
**Symbols:**

```
ffffffff81079710-ffffffff810797ee: dom_data_init.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108a510)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:704
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
```
**Symbols:**

```
ffffffff8108a510-ffffffff8108a5ee: dom_data_init.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108d580)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:716
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
```
**Symbols:**

```
ffffffff8108d580-ffffffff8108d65e: dom_data_init.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81094910)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:716
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
```
**Symbols:**

```
ffffffff81094910-ffffffff810949ee: dom_data_init.isra.0 (STB_LOCAL)
```
</details>
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e2ec)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:553
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8104e61c)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:553
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e71c)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:553
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105fc5c)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:553
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
```
</details>
</li>
</ul>

## Differences
