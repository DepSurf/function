# Function: <code>remove_siblinginfo</code>

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
In arch/x86/kernel/smpboot.c (ffffffff81052476)
Location: arch/x86/kernel/smpboot.c:1446
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
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
In arch/x86/kernel/smpboot.c (ffffffff81052546)
Location: arch/x86/kernel/smpboot.c:1472
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
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
In arch/x86/kernel/smpboot.c (ffffffff81054e46)
Location: arch/x86/kernel/smpboot.c:1500
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
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
In arch/x86/kernel/smpboot.c (ffffffff81054766)
Location: arch/x86/kernel/smpboot.c:1506
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
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
In arch/x86/kernel/smpboot.c (ffffffff81058566)
Location: arch/x86/kernel/smpboot.c:1419
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
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
In arch/x86/kernel/smpboot.c (ffffffff8105b219)
Location: arch/x86/kernel/smpboot.c:1474
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
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
In arch/x86/kernel/smpboot.c (ffffffff81060e8a)
Location: arch/x86/kernel/smpboot.c:1475
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
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
In arch/x86/kernel/smpboot.c (ffffffff8106449d)
Location: arch/x86/kernel/smpboot.c:1537
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
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
In arch/x86/kernel/smpboot.c (ffffffff81064b1d)
Location: arch/x86/kernel/smpboot.c:1532
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void remove_siblinginfo(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81069f50)
Location: arch/x86/kernel/smpboot.c:1545
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
```
**Symbols:**

```
ffffffff81069f50-ffffffff8106a1d3: remove_siblinginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void remove_siblinginfo(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106bc20)
Location: arch/x86/kernel/smpboot.c:1539
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
```
**Symbols:**

```
ffffffff8106bc20-ffffffff8106bea3: remove_siblinginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void remove_siblinginfo(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106c560)
Location: arch/x86/kernel/smpboot.c:1540
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
```
**Symbols:**

```
ffffffff8106c560-ffffffff8106c7ff: remove_siblinginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void remove_siblinginfo(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81077290)
Location: arch/x86/kernel/smpboot.c:1542
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
```
**Symbols:**

```
ffffffff81077290-ffffffff810777f4: remove_siblinginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void remove_siblinginfo(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810862b0)
Location: arch/x86/kernel/smpboot.c:1604
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
```
**Symbols:**

```
ffffffff810862b0-ffffffff81086906: remove_siblinginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void remove_siblinginfo(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810997f0)
Location: arch/x86/kernel/smpboot.c:1604
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
```
**Symbols:**

```
ffffffff810997f0-ffffffff81099ebe: remove_siblinginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void remove_siblinginfo(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8109cc70)
Location: arch/x86/kernel/smpboot.c:1521
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
```
**Symbols:**

```
ffffffff8109cc70-ffffffff8109d33e: remove_siblinginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void remove_siblinginfo(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810a41b0)
Location: arch/x86/kernel/smpboot.c:1387
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
```
**Symbols:**

```
ffffffff810a41b0-ffffffff810a487f: remove_siblinginfo (STB_LOCAL)
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
In arch/x86/kernel/smpboot.c (ffffffff8106460d)
Location: arch/x86/kernel/smpboot.c:1532
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
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
In arch/x86/kernel/smpboot.c (ffffffff810548fd)
Location: arch/x86/kernel/smpboot.c:1532
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
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
In arch/x86/kernel/smpboot.c (ffffffff81064abd)
Location: arch/x86/kernel/smpboot.c:1532
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
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
In arch/x86/kernel/smpboot.c (ffffffff8106609d)
Location: arch/x86/kernel/smpboot.c:1532
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
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
