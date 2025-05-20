# Function: <code>__rmid_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 __rmid_read(u32 rmid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/cqm.c (ffffffff8100d530)
Location: arch/x86/events/intel/cqm.c:140
Inline: False
Direct callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_stable
  - arch/x86/events/intel/cqm.c:__intel_cqm_event_count
```
**Symbols:**

```
ffffffff8100d530-ffffffff8100d585: __rmid_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 __rmid_read(u32 rmid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/cqm.c (ffffffff8100d780)
Location: arch/x86/events/intel/cqm.c:140
Inline: False
Direct callers:
  - arch/x86/events/intel/cqm.c:__intel_cqm_event_count
  - arch/x86/events/intel/cqm.c:intel_cqm_stable
```
**Symbols:**

```
ffffffff8100d780-ffffffff8100d7aa: __rmid_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 __rmid_read(u32 rmid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/cqm.c (ffffffff8100d840)
Location: arch/x86/events/intel/cqm.c:121
Inline: False
Direct callers:
  - arch/x86/events/intel/cqm.c:__intel_cqm_event_count
  - arch/x86/events/intel/cqm.c:intel_cqm_stable
```
**Symbols:**

```
ffffffff8100d840-ffffffff8100d86a: __rmid_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 __rmid_read(u32 rmid, u32 eventid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff810440d0)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:88
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:__mon_event_count
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:__check_limbo
```
**Symbols:**

```
ffffffff810440d0-ffffffff810440f7: __rmid_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 __rmid_read(u32 rmid, u32 eventid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff810478a0)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:88
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:__mon_event_count
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:__check_limbo
```
**Symbols:**

```
ffffffff810478a0-ffffffff810478c7: __rmid_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 __rmid_read(u32 rmid, u32 eventid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff81049ec0)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:88
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_update
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:__mon_event_count
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:__check_limbo
```
**Symbols:**

```
ffffffff81049ec0-ffffffff81049ee7: __rmid_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 __rmid_read(u32 rmid, u32 eventid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105a240)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:85
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
**Symbols:**

```
ffffffff8105a240-ffffffff8105a267: __rmid_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 __rmid_read(u32 rmid, u32 eventid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105d510)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
**Symbols:**

```
ffffffff8105d510-ffffffff8105d537: __rmid_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 __rmid_read(u32 rmid, u32 eventid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105ddc0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
**Symbols:**

```
ffffffff8105ddc0-ffffffff8105dde7: __rmid_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 __rmid_read(u32 rmid, u32 eventid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810639c0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_bw_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
**Symbols:**

```
ffffffff810639c0-ffffffff810639e7: __rmid_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 __rmid_read(u32 rmid, u32 eventid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81061de0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:140
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_bw_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
**Symbols:**

```
ffffffff81061de0-ffffffff81061e07: __rmid_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 __rmid_read(u32 rmid, u32 eventid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810625a0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:140
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
**Symbols:**

```
ffffffff810625a0-ffffffff810625c7: __rmid_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 __rmid_read(u32 rmid, u32 eventid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8106c410)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:140
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
**Symbols:**

```
ffffffff8106c410-ffffffff8106c437: __rmid_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 __rmid_read(u32 rmid, u32 eventid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810797f0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:140
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
**Symbols:**

```
ffffffff810797f0-ffffffff8107982d: __rmid_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __rmid_read(u32 rmid, enum resctrl_event_id eventid, u64 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108a490)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:resctrl_arch_rmid_read
  - arch/x86/kernel/cpu/resctrl/monitor.c:resctrl_arch_reset_rmid
```
**Symbols:**

```
ffffffff8108a490-ffffffff8108a4f4: __rmid_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __rmid_read(u32 rmid, enum resctrl_event_id eventid, u64 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108d500)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:resctrl_arch_rmid_read
  - arch/x86/kernel/cpu/resctrl/monitor.c:resctrl_arch_reset_rmid
```
**Symbols:**

```
ffffffff8108d500-ffffffff8108d564: __rmid_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __rmid_read(u32 rmid, enum resctrl_event_id eventid, u64 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81094890)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:resctrl_arch_rmid_read
  - arch/x86/kernel/cpu/resctrl/monitor.c:resctrl_arch_reset_rmid
```
**Symbols:**

```
ffffffff81094890-ffffffff810948f4: __rmid_read (STB_LOCAL)
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
u64 __rmid_read(u32 rmid, u32 eventid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105d940)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
**Symbols:**

```
ffffffff8105d940-ffffffff8105d967: __rmid_read (STB_LOCAL)
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8104dd24)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:77
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 __rmid_read(u32 rmid, u32 eventid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105dd70)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
**Symbols:**

```
ffffffff8105dd70-ffffffff8105dd97: __rmid_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 __rmid_read(u32 rmid, u32 eventid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105f290)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
**Symbols:**

```
ffffffff8105f290-ffffffff8105f2b7: __rmid_read (STB_LOCAL)
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 eventid</code>
</li>
</ul>
</details>
</li>
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
<b>Param added. </b>
<code>u64 *val</code>
</li>
<li>
<b>Param type changed. </b>
<code>u32 eventid</code> ➡️ <code>enum resctrl_event_id eventid</code>
</li>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
