# Function: <code>add_rmid_to_limbo</code>

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
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff810445a3)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid
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
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff81047d73)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid
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
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff8104a450)
Location: arch/x86/kernel/cpu/intel_rdt_monitor.c:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:free_rmid
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105a7d0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105dac0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e370)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void add_rmid_to_limbo(struct rmid_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81063c70)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:165
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
```
**Symbols:**

```
ffffffff81063c70-ffffffff81063d8c: add_rmid_to_limbo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void add_rmid_to_limbo(struct rmid_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810620a0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:228
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
```
**Symbols:**

```
ffffffff810620a0-ffffffff810621bc: add_rmid_to_limbo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void add_rmid_to_limbo(struct rmid_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81062b00)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:228
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
```
**Symbols:**

```
ffffffff81062b00-ffffffff81062be7: add_rmid_to_limbo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void add_rmid_to_limbo(struct rmid_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8106c990)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:228
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
```
**Symbols:**

```
ffffffff8106c990-ffffffff8106ca77: add_rmid_to_limbo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void add_rmid_to_limbo(struct rmid_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81079df0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:228
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
```
**Symbols:**

```
ffffffff81079df0-ffffffff81079f06: add_rmid_to_limbo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void add_rmid_to_limbo(struct rmid_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108ae80)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:317
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
```
**Symbols:**

```
ffffffff8108ae80-ffffffff8108afd6: add_rmid_to_limbo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void add_rmid_to_limbo(struct rmid_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108df20)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:334
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
```
**Symbols:**

```
ffffffff8108df20-ffffffff8108e076: add_rmid_to_limbo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void add_rmid_to_limbo(struct rmid_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810952b0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:334
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
```
**Symbols:**

```
ffffffff810952b0-ffffffff81095406: add_rmid_to_limbo (STB_LOCAL)
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105def0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8104e1b8)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e320)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105f840)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
