# Function: <code>percpu_setup_exception_stacks</code>

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
In arch/x86/mm/cpu_entry_area.c (ffffffff828bd09b)
Location: arch/x86/mm/cpu_entry_area.c:89
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
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
In arch/x86/mm/cpu_entry_area.c (ffffffff828c3525)
Location: arch/x86/mm/cpu_entry_area.c:89
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void percpu_setup_exception_stacks(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff82ce6622)
Location: arch/x86/mm/cpu_entry_area.c:93
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
```
**Symbols:**

```
ffffffff82ce6622-ffffffff82ce6721: percpu_setup_exception_stacks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void percpu_setup_exception_stacks(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff82fd3f93)
Location: arch/x86/mm/cpu_entry_area.c:94
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
```
**Symbols:**

```
ffffffff82fd3f93-ffffffff82fd4086: percpu_setup_exception_stacks (STB_LOCAL)
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
In arch/x86/mm/cpu_entry_area.c (ffffffff831deb94)
Location: arch/x86/mm/cpu_entry_area.c:94
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void percpu_setup_exception_stacks(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff832c1e4a)
Location: arch/x86/mm/cpu_entry_area.c:94
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
```
**Symbols:**

```
ffffffff832c1e4a-ffffffff832c1fdd: percpu_setup_exception_stacks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void percpu_setup_exception_stacks(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff8347450e)
Location: arch/x86/mm/cpu_entry_area.c:94
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
```
**Symbols:**

```
ffffffff8347450e-ffffffff834746af: percpu_setup_exception_stacks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void percpu_setup_exception_stacks(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff83e9c410)
Location: arch/x86/mm/cpu_entry_area.c:132
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
**Symbols:**

```
ffffffff83e9c410-ffffffff83e9c6b2: percpu_setup_exception_stacks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void percpu_setup_exception_stacks(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff836bff30)
Location: arch/x86/mm/cpu_entry_area.c:139
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
**Symbols:**

```
ffffffff836bff30-ffffffff836c01d2: percpu_setup_exception_stacks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void percpu_setup_exception_stacks(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff838f0a50)
Location: arch/x86/mm/cpu_entry_area.c:139
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
**Symbols:**

```
ffffffff838f0a50-ffffffff838f0cf2: percpu_setup_exception_stacks (STB_LOCAL)
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
In arch/x86/mm/cpu_entry_area.c (ffffffff828ae4fb)
Location: arch/x86/mm/cpu_entry_area.c:89
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
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
In arch/x86/mm/cpu_entry_area.c (ffffffff828a66ed)
Location: arch/x86/mm/cpu_entry_area.c:89
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
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
In arch/x86/mm/cpu_entry_area.c (ffffffff828c13fa)
Location: arch/x86/mm/cpu_entry_area.c:89
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
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
In arch/x86/mm/cpu_entry_area.c (ffffffff828c4545)
Location: arch/x86/mm/cpu_entry_area.c:89
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
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
