# Function: <code>set_mtrr_cpuslocked</code>

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
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104cfb4)
Location: arch/x86/kernel/cpu/mtrr/main.c:240
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page
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
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff810508b0)
Location: arch/x86/kernel/cpu/mtrr/main.c:240
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page
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
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810534fe)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:241
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
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
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81050b7e)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:241
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
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
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81053c45)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:241
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
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
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81054535)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:241
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
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
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810595c5)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:241
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
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
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81058395)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:241
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
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
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81058ccc)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:239
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81061e21)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:239
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8106e81f)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:239
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void set_mtrr_cpuslocked(unsigned int reg, long unsigned int base, long unsigned int size, mtrr_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8107eb91)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:209
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page
```
**Symbols:**

```
ffffffff8107e150-ffffffff8107e1bf: set_mtrr_cpuslocked (STB_LOCAL)
```
</details>
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
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810540b5)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:241
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
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
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81044185)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:241
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
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
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810544e5)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:241
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
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
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81055965)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:241
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
