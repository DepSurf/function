# Function: <code>__mon_event_count</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
int __mon_event_count(u32 rmid, struct rmid_read *rr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff81044100)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:228
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_update
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_update
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mon_event_count
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mon_event_count
```
**Symbols:**

```
ffffffff81044100-ffffffff810441cc: __mon_event_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __mon_event_count(u32 rmid, struct rmid_read *rr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff810478d0)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:228
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_update
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_update
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mon_event_count
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mon_event_count
```
**Symbols:**

```
ffffffff810478d0-ffffffff8104799c: __mon_event_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __mon_event_count(u32 rmid, struct rmid_read *rr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff81049ef0)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:236
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_update
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_update
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mon_event_count
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mon_event_count
```
**Symbols:**

```
ffffffff81049ef0-ffffffff81049fe0: __mon_event_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __mon_event_count(u32 rmid, struct rmid_read *rr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105a270)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:233
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
```
**Symbols:**

```
ffffffff8105a270-ffffffff8105a360: __mon_event_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __mon_event_count(u32 rmid, struct rmid_read *rr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105d540)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
```
**Symbols:**

```
ffffffff8105d540-ffffffff8105d643: __mon_event_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __mon_event_count(u32 rmid, struct rmid_read *rr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105ddf0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
```
**Symbols:**

```
ffffffff8105ddf0-ffffffff8105def3: __mon_event_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __mon_event_count(u32 rmid, struct rmid_read *rr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810639f0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
```
**Symbols:**

```
ffffffff810639f0-ffffffff81063b03: __mon_event_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __mon_event_count(u32 rmid, struct rmid_read *rr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81061e10)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:288
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
```
**Symbols:**

```
ffffffff81061e10-ffffffff81061f2b: __mon_event_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 __mon_event_count(u32 rmid, struct rmid_read *rr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810625d0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:288
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
```
**Symbols:**

```
ffffffff810625d0-ffffffff810626d8: __mon_event_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 __mon_event_count(u32 rmid, struct rmid_read *rr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:288
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
```
**Symbols:**

```
ffffffff8106c440-ffffffff8106c551: __mon_event_count (STB_LOCAL)
ffffffff81c9cc8c-ffffffff81c9cca7: __mon_event_count.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 __mon_event_count(u32 rmid, struct rmid_read *rr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:288
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
```
**Symbols:**

```
ffffffff81079830-ffffffff8107993f: __mon_event_count (STB_LOCAL)
ffffffff81e4bfe5-ffffffff81e4c000: __mon_event_count.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __mon_event_count(u32 rmid, struct rmid_read *rr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:369
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
```
**Symbols:**

```
ffffffff8108a810-ffffffff8108a93b: __mon_event_count (STB_LOCAL)
ffffffff82053634-ffffffff82053664: __mon_event_count.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __mon_event_count(u32 rmid, struct rmid_read *rr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:399
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
```
**Symbols:**

```
ffffffff8108d8e0-ffffffff8108d9d1: __mon_event_count (STB_LOCAL)
ffffffff820d1c42-ffffffff820d1c57: __mon_event_count.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __mon_event_count(u32 rmid, struct rmid_read *rr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:399
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
```
**Symbols:**

```
ffffffff81094c70-ffffffff81094d61: __mon_event_count (STB_LOCAL)
ffffffff821ac8a6-ffffffff821ac8bb: __mon_event_count.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int __mon_event_count(u32 rmid, struct rmid_read *rr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105d970)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
```
**Symbols:**

```
ffffffff8105d970-ffffffff8105da73: __mon_event_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __mon_event_count(u32 rmid, struct rmid_read *rr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8104db10)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
```
**Symbols:**

```
ffffffff8104db10-ffffffff8104dc76: __mon_event_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __mon_event_count(u32 rmid, struct rmid_read *rr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105dda0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
```
**Symbols:**

```
ffffffff8105dda0-ffffffff8105dea3: __mon_event_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __mon_event_count(u32 rmid, struct rmid_read *rr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105f2c0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:mon_event_count
```
**Symbols:**

```
ffffffff8105f2c0-ffffffff8105f3c3: __mon_event_count (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>u64</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>u64</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
