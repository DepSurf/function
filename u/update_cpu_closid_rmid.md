# Function: <code>update_cpu_closid_rmid</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void update_cpu_closid_rmid(void *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81041bcf)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff81042630-ffffffff81042663: update_cpu_closid_rmid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void update_cpu_closid_rmid(void *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81044fff)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:226
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff81045af0-ffffffff81045b21: update_cpu_closid_rmid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void update_cpu_closid_rmid(void *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81047470)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:227
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff81047e50-ffffffff81047e81: update_cpu_closid_rmid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void update_cpu_closid_rmid(void *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81056480)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:306
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff81057e30-ffffffff81057e61: update_cpu_closid_rmid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void update_cpu_closid_rmid(void *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81059922)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:300
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff8105b0b0-ffffffff8105b0e2: update_cpu_closid_rmid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void update_cpu_closid_rmid(void *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105a212)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:300
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff8105b9c0-ffffffff8105b9f2: update_cpu_closid_rmid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void update_cpu_closid_rmid(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ff50)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:300
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff8105ff50-ffffffff8105ff82: update_cpu_closid_rmid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void update_cpu_closid_rmid(void *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105eefb)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:300
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff8105eb40-ffffffff8105eb72: update_cpu_closid_rmid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void update_cpu_closid_rmid(void *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105f4fb)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:300
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff8105f360-ffffffff8105f392: update_cpu_closid_rmid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void update_cpu_closid_rmid(void *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81068e4b)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff810688c0-ffffffff810688ef: update_cpu_closid_rmid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void update_cpu_closid_rmid(void *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81075ff8)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff810759e0-ffffffff81075a1f: update_cpu_closid_rmid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void update_cpu_closid_rmid(void *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108655b)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff81086320-ffffffff810863d1: update_cpu_closid_rmid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void update_cpu_closid_rmid(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81088f50)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:316
Inline: False
```
**Symbols:**

```
ffffffff81088f50-ffffffff81089001: update_cpu_closid_rmid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void update_cpu_closid_rmid(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810906f0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:321
Inline: False
```
**Symbols:**

```
ffffffff810906f0-ffffffff810907a1: update_cpu_closid_rmid (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void update_cpu_closid_rmid(void *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81059d92)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:300
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff8105b540-ffffffff8105b572: update_cpu_closid_rmid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void update_cpu_closid_rmid(void *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104b032)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:300
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff8104b6b0-ffffffff8104b6e2: update_cpu_closid_rmid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void update_cpu_closid_rmid(void *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105a1c2)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:300
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff8105b970-ffffffff8105b9a2: update_cpu_closid_rmid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void update_cpu_closid_rmid(void *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b5a9)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:300
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
**Symbols:**

```
ffffffff8105ce40-ffffffff8105ce72: update_cpu_closid_rmid (STB_LOCAL)
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
