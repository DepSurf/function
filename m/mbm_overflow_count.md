# Function: <code>mbm_overflow_count</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff8104a097)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:228
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_update
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:__mon_event_count
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105a417)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:225
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105d70d)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:217
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105dfbd)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:217
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81063b5f)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:217
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_bw_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81061f77)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:280
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_bw_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8106261b)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:280
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 mbm_overflow_count(u64 prev_msr, u64 cur_msr, unsigned int width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:280
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
```
**Symbols:**

```
ffffffff8106c140-ffffffff8106c162: mbm_overflow_count (STB_LOCAL)
ffffffff81c9cc01-ffffffff81c9cc60: mbm_overflow_count.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 mbm_overflow_count(u64 prev_msr, u64 cur_msr, unsigned int width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:280
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
```
**Symbols:**

```
ffffffff810794b0-ffffffff810794de: mbm_overflow_count (STB_LOCAL)
ffffffff81e4bf50-ffffffff81e4bfb9: mbm_overflow_count.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108a78c)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:207
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:resctrl_arch_rmid_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108d874)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:224
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:resctrl_arch_rmid_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81094c04)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:224
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:resctrl_arch_rmid_read
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105db3d)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:217
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8104dd66)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:217
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105df6d)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:217
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105f48d)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:217
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
