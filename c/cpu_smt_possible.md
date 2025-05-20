# Function: <code>cpu_smt_possible</code>

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
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool cpu_smt_possible();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff828cac86)
Location: kernel/cpu.c:442
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_smt_disable
```
**Symbols:**

```
ffffffff810a1ad0-ffffffff810a1aea: cpu_smt_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool cpu_smt_possible();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff82ced0a3)
Location: kernel/cpu.c:443
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_smt_disable
```
**Symbols:**

```
ffffffff810a8930-ffffffff810a894a: cpu_smt_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool cpu_smt_possible();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff82fd96fd)
Location: kernel/cpu.c:443
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_smt_disable
```
**Symbols:**

```
ffffffff810a4380-ffffffff810a439a: cpu_smt_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool cpu_smt_possible();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff831e4051)
Location: kernel/cpu.c:455
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_smt_disable
```
**Symbols:**

```
ffffffff810a4fd0-ffffffff810a4fea: cpu_smt_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool cpu_smt_possible();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff832c7c2e)
Location: kernel/cpu.c:466
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_smt_disable
```
**Symbols:**

```
ffffffff810b6810-ffffffff810b682a: cpu_smt_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool cpu_smt_possible();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8347ac3c)
Location: kernel/cpu.c:467
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_smt_disable
```
**Symbols:**

```
ffffffff810ccd70-ffffffff810ccd8e: cpu_smt_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool cpu_smt_possible();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff83ea5558)
Location: kernel/cpu.c:467
Inline: True
Inline callers:
  - kernel/cpu.c:smt_cmdline_disable
```
**Symbols:**

```
ffffffff810ead40-ffffffff810ead5e: cpu_smt_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool cpu_smt_possible();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff836c9928)
Location: kernel/cpu.c:646
Inline: True
Inline callers:
  - kernel/cpu.c:smt_cmdline_disable
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:srso_select_mitigation
```
**Symbols:**

```
ffffffff810f6980-ffffffff810f699e: cpu_smt_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool cpu_smt_possible();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff838fa578)
Location: kernel/cpu.c:688
Inline: True
Inline callers:
  - kernel/cpu.c:smt_cmdline_disable
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:srso_select_mitigation
```
**Symbols:**

```
ffffffff810ffd30-ffffffff810ffd4e: cpu_smt_possible (STB_GLOBAL)
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
bool cpu_smt_possible();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff828b3a79)
Location: kernel/cpu.c:442
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_smt_disable
```
**Symbols:**

```
ffffffff8109b3f0-ffffffff8109b40a: cpu_smt_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool cpu_smt_possible();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff828abbfa)
Location: kernel/cpu.c:442
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_smt_disable
```
**Symbols:**

```
ffffffff81089e20-ffffffff81089e3a: cpu_smt_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool cpu_smt_possible();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff828c6978)
Location: kernel/cpu.c:442
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_smt_disable
```
**Symbols:**

```
ffffffff8109b3a0-ffffffff8109b3ba: cpu_smt_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool cpu_smt_possible();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff828cbcc3)
Location: kernel/cpu.c:442
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_smt_disable
```
**Symbols:**

```
ffffffff810a3010-ffffffff810a302a: cpu_smt_possible (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
