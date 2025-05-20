# Function: <code>wait_for_master_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81041092)
Location: arch/x86/kernel/cpu/common.c:1307
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81040fa9)
Location: arch/x86/kernel/cpu/common.c:1426
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff810409f1)
Location: arch/x86/kernel/cpu/common.c:1397
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff8103e97b)
Location: arch/x86/kernel/cpu/common.c:1451
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff81041641)
Location: arch/x86/kernel/cpu/common.c:1546
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff81042f20)
Location: arch/x86/kernel/cpu/common.c:1656
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff810444f9)
Location: arch/x86/kernel/cpu/common.c:1652
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff81046ac9)
Location: arch/x86/kernel/cpu/common.c:1737
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff81047249)
Location: arch/x86/kernel/cpu/common.c:1769
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wait_for_master_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104a070)
Location: arch/x86/kernel/cpu/common.c:1761
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
**Symbols:**

```
ffffffff8104a070-ffffffff8104a096: wait_for_master_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wait_for_master_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81049510)
Location: arch/x86/kernel/cpu/common.c:1831
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
**Symbols:**

```
ffffffff81049510-ffffffff81049536: wait_for_master_cpu (STB_LOCAL)
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
In arch/x86/kernel/cpu/common.c (ffffffff8104bfe1)
Location: arch/x86/kernel/cpu/common.c:1835
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff810533e2)
Location: arch/x86/kernel/cpu/common.c:1875
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff8105ee82)
Location: arch/x86/kernel/cpu/common.c:2118
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff8106d5f2)
Location: arch/x86/kernel/cpu/common.c:2120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff810473c9)
Location: arch/x86/kernel/cpu/common.c:1769
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff8103654d)
Location: arch/x86/kernel/cpu/common.c:1769
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff81047209)
Location: arch/x86/kernel/cpu/common.c:1769
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
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
In arch/x86/kernel/cpu/common.c (ffffffff81048609)
Location: arch/x86/kernel/cpu/common.c:1769
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
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
</ul>
