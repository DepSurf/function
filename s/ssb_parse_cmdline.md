# Function: <code>ssb_parse_cmdline</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff826de7b0)
Location: arch/x86/kernel/cpu/bugs.c:445
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
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
In arch/x86/kernel/cpu/bugs.c (ffffffff82894e5f)
Location: arch/x86/kernel/cpu/bugs.c:669
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
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
In arch/x86/kernel/cpu/bugs.c (ffffffff828ac2cc)
Location: arch/x86/kernel/cpu/bugs.c:857
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
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
In arch/x86/kernel/cpu/bugs.c (ffffffff828af442)
Location: arch/x86/kernel/cpu/bugs.c:987
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum ssb_mitigation_cmd ssb_parse_cmdline();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff82cd42ab)
Location: arch/x86/kernel/cpu/bugs.c:1094
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
```
**Symbols:**

```
ffffffff82cd42ab-ffffffff82cd4389: ssb_parse_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum ssb_mitigation_cmd ssb_parse_cmdline();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff82fc0238)
Location: arch/x86/kernel/cpu/bugs.c:1088
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
```
**Symbols:**

```
ffffffff82fc0238-ffffffff82fc0316: ssb_parse_cmdline (STB_LOCAL)
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
In arch/x86/kernel/cpu/bugs.c (ffffffff831cb142)
Location: arch/x86/kernel/cpu/bugs.c:1088
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
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
In arch/x86/kernel/cpu/bugs.c (ffffffff832ac784)
Location: arch/x86/kernel/cpu/bugs.c:1210
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
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
In arch/x86/kernel/cpu/bugs.c (ffffffff8345d2d0)
Location: arch/x86/kernel/cpu/bugs.c:1722
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
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
In arch/x86/kernel/cpu/bugs.c (ffffffff83e7d496)
Location: arch/x86/kernel/cpu/bugs.c:1771
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
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
In arch/x86/kernel/cpu/bugs.c (ffffffff836a0106)
Location: arch/x86/kernel/cpu/bugs.c:1882
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
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
In arch/x86/kernel/cpu/bugs.c (ffffffff838d0546)
Location: arch/x86/kernel/cpu/bugs.c:2023
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
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
In arch/x86/kernel/cpu/bugs.c (ffffffff8289d461)
Location: arch/x86/kernel/cpu/bugs.c:987
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
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
In arch/x86/kernel/cpu/bugs.c (ffffffff82895649)
Location: arch/x86/kernel/cpu/bugs.c:987
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
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
In arch/x86/kernel/cpu/bugs.c (ffffffff828b0424)
Location: arch/x86/kernel/cpu/bugs.c:987
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
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
In arch/x86/kernel/cpu/bugs.c (ffffffff828b0452)
Location: arch/x86/kernel/cpu/bugs.c:987
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
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
