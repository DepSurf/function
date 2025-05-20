# Function: <code>setup_cpu_entry_area</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff826c3b22)
Location: arch/x86/mm/cpu_entry_area.c:68
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
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
In arch/x86/mm/cpu_entry_area.c (ffffffff826eddc9)
Location: arch/x86/mm/cpu_entry_area.c:80
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
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
In arch/x86/mm/cpu_entry_area.c (ffffffff828a4aed)
Location: arch/x86/mm/cpu_entry_area.c:82
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
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
In arch/x86/mm/cpu_entry_area.c (ffffffff828bcfe4)
Location: arch/x86/mm/cpu_entry_area.c:115
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
In arch/x86/mm/cpu_entry_area.c (ffffffff828c346e)
Location: arch/x86/mm/cpu_entry_area.c:115
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
void setup_cpu_entry_area(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff82ce6721)
Location: arch/x86/mm/cpu_entry_area.c:124
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
**Symbols:**

```
ffffffff82ce6721-ffffffff82ce686e: setup_cpu_entry_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void setup_cpu_entry_area(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff82fd4086)
Location: arch/x86/mm/cpu_entry_area.c:125
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
**Symbols:**

```
ffffffff82fd4086-ffffffff82fd41b4: setup_cpu_entry_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void setup_cpu_entry_area(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff831dead4)
Location: arch/x86/mm/cpu_entry_area.c:125
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
**Symbols:**

```
ffffffff831dead4-ffffffff831decbd: setup_cpu_entry_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void setup_cpu_entry_area(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff832c1fdd)
Location: arch/x86/mm/cpu_entry_area.c:132
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
**Symbols:**

```
ffffffff832c1fdd-ffffffff832c2193: setup_cpu_entry_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void setup_cpu_entry_area(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff834746af)
Location: arch/x86/mm/cpu_entry_area.c:132
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
**Symbols:**

```
ffffffff834746af-ffffffff83474873: setup_cpu_entry_area (STB_LOCAL)
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
In arch/x86/mm/cpu_entry_area.c (ffffffff83e9c727)
Location: arch/x86/mm/cpu_entry_area.c:170
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
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
In arch/x86/mm/cpu_entry_area.c (ffffffff836c0247)
Location: arch/x86/mm/cpu_entry_area.c:177
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
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
In arch/x86/mm/cpu_entry_area.c (ffffffff838f0d67)
Location: arch/x86/mm/cpu_entry_area.c:177
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
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
In arch/x86/mm/cpu_entry_area.c (ffffffff828ae444)
Location: arch/x86/mm/cpu_entry_area.c:115
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
In arch/x86/mm/cpu_entry_area.c (ffffffff828a6636)
Location: arch/x86/mm/cpu_entry_area.c:115
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
In arch/x86/mm/cpu_entry_area.c (ffffffff828c1343)
Location: arch/x86/mm/cpu_entry_area.c:115
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
In arch/x86/mm/cpu_entry_area.c (ffffffff828c448e)
Location: arch/x86/mm/cpu_entry_area.c:115
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
