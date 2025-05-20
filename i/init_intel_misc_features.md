# Function: <code>init_intel_misc_features</code>

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
In arch/x86/kernel/cpu/intel.c (ffffffff8103fe26)
Location: arch/x86/kernel/cpu/intel.c:497
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
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
In arch/x86/kernel/cpu/intel.c (ffffffff8104319b)
Location: arch/x86/kernel/cpu/intel.c:552
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
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
In arch/x86/kernel/cpu/intel.c (ffffffff81044fbb)
Location: arch/x86/kernel/cpu/intel.c:631
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
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
In arch/x86/kernel/cpu/intel.c (ffffffff810469cd)
Location: arch/x86/kernel/cpu/intel.c:639
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
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
In arch/x86/kernel/cpu/intel.c (ffffffff810493c8)
Location: arch/x86/kernel/cpu/intel.c:636
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
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
In arch/x86/kernel/cpu/intel.c (ffffffff81049c9c)
Location: arch/x86/kernel/cpu/intel.c:637
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void init_intel_misc_features(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8104de10)
Location: arch/x86/kernel/cpu/intel.c:585
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff8104de10-ffffffff8104defb: init_intel_misc_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void init_intel_misc_features(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8104d340)
Location: arch/x86/kernel/cpu/intel.c:586
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff8104d340-ffffffff8104d42b: init_intel_misc_features (STB_LOCAL)
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
In arch/x86/kernel/cpu/intel.c (ffffffff8104f395)
Location: arch/x86/kernel/cpu/intel.c:587
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
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
In arch/x86/kernel/cpu/intel.c (ffffffff810574f7)
Location: arch/x86/kernel/cpu/intel.c:589
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
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
In arch/x86/kernel/cpu/intel.c (ffffffff8106386a)
Location: arch/x86/kernel/cpu/intel.c:624
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
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
In arch/x86/kernel/cpu/intel.c (ffffffff8107296a)
Location: arch/x86/kernel/cpu/intel.c:766
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
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
In arch/x86/kernel/cpu/intel.c (ffffffff8107455a)
Location: arch/x86/kernel/cpu/intel.c:766
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
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
In arch/x86/kernel/cpu/intel.c (ffffffff8107ba2d)
Location: arch/x86/kernel/cpu/intel.c:586
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
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
In arch/x86/kernel/cpu/intel.c (ffffffff81049e0c)
Location: arch/x86/kernel/cpu/intel.c:637
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
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
In arch/x86/kernel/cpu/intel.c (ffffffff81039166)
Location: arch/x86/kernel/cpu/intel.c:637
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
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
In arch/x86/kernel/cpu/intel.c (ffffffff81049c4c)
Location: arch/x86/kernel/cpu/intel.c:637
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
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
In arch/x86/kernel/cpu/intel.c (ffffffff8104b05c)
Location: arch/x86/kernel/cpu/intel.c:637
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
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
