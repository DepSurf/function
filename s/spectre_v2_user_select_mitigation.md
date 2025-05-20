# Function: <code>spectre_v2_user_select_mitigation</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff82894c2b)
Location: arch/x86/kernel/cpu/bugs.c:327
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
In arch/x86/kernel/cpu/bugs.c (ffffffff828ac75d)
Location: arch/x86/kernel/cpu/bugs.c:481
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
In arch/x86/kernel/cpu/bugs.c (ffffffff828af8ce)
Location: arch/x86/kernel/cpu/bugs.c:603
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
void spectre_v2_user_select_mitigation(enum spectre_v2_mitigation_cmd v2_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff82cd484d)
Location: arch/x86/kernel/cpu/bugs.c:706
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
```
**Symbols:**

```
ffffffff82cd484d-ffffffff82cd4a9e: spectre_v2_user_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void spectre_v2_user_select_mitigation(enum spectre_v2_mitigation_cmd v2_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff82fc07ec)
Location: arch/x86/kernel/cpu/bugs.c:704
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
```
**Symbols:**

```
ffffffff82fc07ec-ffffffff82fc0a44: spectre_v2_user_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void spectre_v2_user_select_mitigation(enum spectre_v2_mitigation_cmd v2_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff831caa61)
Location: arch/x86/kernel/cpu/bugs.c:704
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
```
**Symbols:**

```
ffffffff831caa61-ffffffff831cacce: spectre_v2_user_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void spectre_v2_user_select_mitigation(enum spectre_v2_mitigation_cmd v2_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff832ac104)
Location: arch/x86/kernel/cpu/bugs.c:778
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
```
**Symbols:**

```
ffffffff832ac104-ffffffff832ac407: spectre_v2_user_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void spectre_v2_user_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8345c624)
Location: arch/x86/kernel/cpu/bugs.c:1107
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff8345c624-ffffffff8345c945: spectre_v2_user_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void spectre_v2_user_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff83e7d680)
Location: arch/x86/kernel/cpu/bugs.c:1148
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff83e7d680-ffffffff83e7da47: spectre_v2_user_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void spectre_v2_user_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff836a02f0)
Location: arch/x86/kernel/cpu/bugs.c:1253
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
```
**Symbols:**

```
ffffffff836a02f0-ffffffff836a06af: spectre_v2_user_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void spectre_v2_user_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff838d0140)
Location: arch/x86/kernel/cpu/bugs.c:1318
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
```
**Symbols:**

```
ffffffff838d0140-ffffffff838d04ff: spectre_v2_user_select_mitigation (STB_LOCAL)
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
In arch/x86/kernel/cpu/bugs.c (ffffffff8289d8ed)
Location: arch/x86/kernel/cpu/bugs.c:603
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
In arch/x86/kernel/cpu/bugs.c (ffffffff82895afe)
Location: arch/x86/kernel/cpu/bugs.c:603
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
In arch/x86/kernel/cpu/bugs.c (ffffffff828b08b0)
Location: arch/x86/kernel/cpu/bugs.c:603
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
In arch/x86/kernel/cpu/bugs.c (ffffffff828b08de)
Location: arch/x86/kernel/cpu/bugs.c:603
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>enum spectre_v2_mitigation_cmd v2_cmd</code>
</li>
</ul>
</details>
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
