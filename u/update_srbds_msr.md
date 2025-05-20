# Function: <code>update_srbds_msr</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void update_srbds_msr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104bdf0)
Location: arch/x86/kernel/cpu/bugs.c:426
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/bugs.c:srbds_select_mitigation
```
**Symbols:**

```
ffffffff8104bdf0-ffffffff8104be65: update_srbds_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void update_srbds_msr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104b330)
Location: arch/x86/kernel/cpu/bugs.c:426
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/bugs.c:srbds_select_mitigation
```
**Symbols:**

```
ffffffff8104b330-ffffffff8104b3a5: update_srbds_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void update_srbds_msr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104d0a0)
Location: arch/x86/kernel/cpu/bugs.c:426
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff8104d0a0-ffffffff8104d115: update_srbds_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void update_srbds_msr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81054700)
Location: arch/x86/kernel/cpu/bugs.c:436
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff81054700-ffffffff81054775: update_srbds_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void update_srbds_msr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81060380)
Location: arch/x86/kernel/cpu/bugs.c:583
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff81060380-ffffffff81060433: update_srbds_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void update_srbds_msr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106eac0)
Location: arch/x86/kernel/cpu/bugs.c:591
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff8106eac0-ffffffff8106eb73: update_srbds_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void update_srbds_msr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810702b0)
Location: arch/x86/kernel/cpu/bugs.c:557
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
```
**Symbols:**

```
ffffffff810702b0-ffffffff81070363: update_srbds_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void update_srbds_msr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81077b90)
Location: arch/x86/kernel/cpu/bugs.c:623
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
```
**Symbols:**

```
ffffffff81077b90-ffffffff81077c43: update_srbds_msr (STB_GLOBAL)
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
