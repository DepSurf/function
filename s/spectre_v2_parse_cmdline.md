# Function: <code>spectre_v2_parse_cmdline</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff826b4ba8)
Location: arch/x86/kernel/cpu/bugs.c:156
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
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
In arch/x86/kernel/cpu/bugs.c (ffffffff826de580)
Location: arch/x86/kernel/cpu/bugs.c:279
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
In arch/x86/kernel/cpu/bugs.c (ffffffff828949e9)
Location: arch/x86/kernel/cpu/bugs.c:437
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
In arch/x86/kernel/cpu/bugs.c (ffffffff828ac518)
Location: arch/x86/kernel/cpu/bugs.c:591
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
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
In arch/x86/kernel/cpu/bugs.c (ffffffff828af68d)
Location: arch/x86/kernel/cpu/bugs.c:713
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum spectre_v2_mitigation_cmd spectre_v2_parse_cmdline();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff82cd4167)
Location: arch/x86/kernel/cpu/bugs.c:820
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
```
**Symbols:**

```
ffffffff82cd4167-ffffffff82cd42ab: spectre_v2_parse_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum spectre_v2_mitigation_cmd spectre_v2_parse_cmdline();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff82fc00f4)
Location: arch/x86/kernel/cpu/bugs.c:814
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
```
**Symbols:**

```
ffffffff82fc00f4-ffffffff82fc0238: spectre_v2_parse_cmdline (STB_LOCAL)
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
In arch/x86/kernel/cpu/bugs.c (ffffffff831cacff)
Location: arch/x86/kernel/cpu/bugs.c:814
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum spectre_v2_mitigation_cmd spectre_v2_parse_cmdline();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff832abe3f)
Location: arch/x86/kernel/cpu/bugs.c:894
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
```
**Symbols:**

```
ffffffff832abe3f-ffffffff832ac05c: spectre_v2_parse_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum spectre_v2_mitigation_cmd spectre_v2_parse_cmdline();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8345c332)
Location: arch/x86/kernel/cpu/bugs.c:1233
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
```
**Symbols:**

```
ffffffff8345c332-ffffffff8345c624: spectre_v2_parse_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum spectre_v2_mitigation_cmd spectre_v2_parse_cmdline();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff83e7da60)
Location: arch/x86/kernel/cpu/bugs.c:1281
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
```
**Symbols:**

```
ffffffff83e7da60-ffffffff83e7ddc0: spectre_v2_parse_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum spectre_v2_mitigation_cmd spectre_v2_parse_cmdline();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff836a06c0)
Location: arch/x86/kernel/cpu/bugs.c:1388
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
```
**Symbols:**

```
ffffffff836a06c0-ffffffff836a09f5: spectre_v2_parse_cmdline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum spectre_v2_mitigation_cmd spectre_v2_parse_cmdline();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff838d0730)
Location: arch/x86/kernel/cpu/bugs.c:1453
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
```
**Symbols:**

```
ffffffff838d0730-ffffffff838d0a65: spectre_v2_parse_cmdline (STB_LOCAL)
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
In arch/x86/kernel/cpu/bugs.c (ffffffff8289d6ac)
Location: arch/x86/kernel/cpu/bugs.c:713
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
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
In arch/x86/kernel/cpu/bugs.c (ffffffff828958b6)
Location: arch/x86/kernel/cpu/bugs.c:713
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
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
In arch/x86/kernel/cpu/bugs.c (ffffffff828b066f)
Location: arch/x86/kernel/cpu/bugs.c:713
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
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
In arch/x86/kernel/cpu/bugs.c (ffffffff828b069d)
Location: arch/x86/kernel/cpu/bugs.c:713
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
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
