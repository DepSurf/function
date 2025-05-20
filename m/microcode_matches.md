# Function: <code>microcode_matches</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81050101)
Location: arch/x86/kernel/cpu/microcode/intel.c:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81050166)
Location: arch/x86/kernel/cpu/microcode/intel.c:109
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053b96)
Location: arch/x86/kernel/cpu/microcode/intel.c:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056823)
Location: arch/x86/kernel/cpu/microcode/intel.c:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053eb3)
Location: arch/x86/kernel/cpu/microcode/intel.c:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810570b3)
Location: arch/x86/kernel/cpu/microcode/intel.c:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057983)
Location: arch/x86/kernel/cpu/microcode/intel.c:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool microcode_matches(struct microcode_header_intel *mc_header, long unsigned int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105c210)
Location: arch/x86/kernel/cpu/microcode/intel.c:110
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff8105c210-ffffffff8105c316: microcode_matches (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057503)
Location: arch/x86/kernel/cpu/microcode/intel.c:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810476f3)
Location: arch/x86/kernel/cpu/microcode/intel.c:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057933)
Location: arch/x86/kernel/cpu/microcode/intel.c:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81058dd3)
Location: arch/x86/kernel/cpu/microcode/intel.c:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
