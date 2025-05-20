# Function: <code>split_lock_setup</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void split_lock_setup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff82cd509d)
Location: arch/x86/kernel/cpu/intel.c:1019
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:cpu_set_core_cap_bits
```
**Symbols:**

```
ffffffff82cd509d-ffffffff82cd51f1: split_lock_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void split_lock_setup();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff82fc1055)
Location: arch/x86/kernel/cpu/intel.c:1020
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:cpu_set_core_cap_bits
```
**Symbols:**

```
ffffffff82fc1055-ffffffff82fc11a9: split_lock_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void split_lock_setup(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff831cb675)
Location: arch/x86/kernel/cpu/intel.c:1207
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:sld_setup
```
**Symbols:**

```
ffffffff831cb675-ffffffff831cb739: split_lock_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void split_lock_setup(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff832acf1d)
Location: arch/x86/kernel/cpu/intel.c:1243
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:sld_setup
```
**Symbols:**

```
ffffffff832acf1d-ffffffff832acfe1: split_lock_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void split_lock_setup(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8345dce5)
Location: arch/x86/kernel/cpu/intel.c:1297
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:sld_setup
```
**Symbols:**

```
ffffffff8345dce5-ffffffff8345dddc: split_lock_setup (STB_LOCAL)
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
In arch/x86/kernel/cpu/intel.c (ffffffff83e7ecd5)
Location: arch/x86/kernel/cpu/intel.c:1482
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:sld_setup
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
In arch/x86/kernel/cpu/intel.c (ffffffff836a1a35)
Location: arch/x86/kernel/cpu/intel.c:1464
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:sld_setup
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
In arch/x86/kernel/cpu/intel.c (ffffffff838d1b35)
Location: arch/x86/kernel/cpu/intel.c:1280
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:sld_setup
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct cpuinfo_x86 *c</code>
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
</ul>
