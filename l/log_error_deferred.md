# Function: <code>log_error_deferred</code>

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
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104a6eb)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:832
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
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
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104e12b)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:817
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
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
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81050bb2)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:869
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8104e21f)
Location: arch/x86/kernel/cpu/mce/amd.c:869
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810510ad)
Location: arch/x86/kernel/cpu/mce/amd.c:949
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81051a0d)
Location: arch/x86/kernel/cpu/mce/amd.c:951
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void log_error_deferred(unsigned int bank);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810566c0)
Location: arch/x86/kernel/cpu/mce/amd.c:964
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
```
**Symbols:**

```
ffffffff810566c0-ffffffff810567f7: log_error_deferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void log_error_deferred(unsigned int bank);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810555e0)
Location: arch/x86/kernel/cpu/mce/amd.c:964
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
```
**Symbols:**

```
ffffffff810555e0-ffffffff8105570c: log_error_deferred (STB_LOCAL)
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105679f)
Location: arch/x86/kernel/cpu/mce/amd.c:964
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105f3bf)
Location: arch/x86/kernel/cpu/mce/amd.c:977
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8106bc70)
Location: arch/x86/kernel/cpu/mce/amd.c:800
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107bc93)
Location: arch/x86/kernel/cpu/mce/amd.c:818
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107df93)
Location: arch/x86/kernel/cpu/mce/amd.c:814
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81085443)
Location: arch/x86/kernel/cpu/mce/amd.c:864
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81051b0d)
Location: arch/x86/kernel/cpu/mce/amd.c:951
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81041306)
Location: arch/x86/kernel/cpu/mce/amd.c:951
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810519bd)
Location: arch/x86/kernel/cpu/mce/amd.c:951
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81052dfd)
Location: arch/x86/kernel/cpu/mce/amd.c:951
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
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
