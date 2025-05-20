# Function: <code>mds_select_mitigation</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff828acaa3)
Location: arch/x86/kernel/cpu/bugs.c:229
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mds_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff828af16c)
Location: arch/x86/kernel/cpu/bugs.c:238
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff828af16c-ffffffff828af1fa: mds_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mds_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff82cd4389)
Location: arch/x86/kernel/cpu/bugs.c:241
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
```
**Symbols:**

```
ffffffff82cd4389-ffffffff82cd4417: mds_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mds_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff82fc0316)
Location: arch/x86/kernel/cpu/bugs.c:241
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
```
**Symbols:**

```
ffffffff82fc0316-ffffffff82fc03a4: mds_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mds_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff831ca78b)
Location: arch/x86/kernel/cpu/bugs.c:241
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff831ca78b-ffffffff831ca817: mds_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mds_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff832ac05c)
Location: arch/x86/kernel/cpu/bugs.c:251
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff832ac05c-ffffffff832ac104: mds_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mds_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8345c945)
Location: arch/x86/kernel/cpu/bugs.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:md_clear_update_mitigation
```
**Symbols:**

```
ffffffff8345c945-ffffffff8345ca01: mds_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mds_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff83e7cd10)
Location: arch/x86/kernel/cpu/bugs.c:278
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:md_clear_update_mitigation
```
**Symbols:**

```
ffffffff83e7cd10-ffffffff83e7cddf: mds_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mds_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8369f970)
Location: arch/x86/kernel/cpu/bugs.c:244
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
  - arch/x86/kernel/cpu/bugs.c:md_clear_update_mitigation
```
**Symbols:**

```
ffffffff8369f970-ffffffff8369fa3f: mds_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mds_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff838cf7f0)
Location: arch/x86/kernel/cpu/bugs.c:241
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
  - arch/x86/kernel/cpu/bugs.c:md_clear_update_mitigation
```
**Symbols:**

```
ffffffff838cf7f0-ffffffff838cf8c6: mds_select_mitigation (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void mds_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8289d18b)
Location: arch/x86/kernel/cpu/bugs.c:238
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff8289d18b-ffffffff8289d219: mds_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mds_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff82895373)
Location: arch/x86/kernel/cpu/bugs.c:238
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff82895373-ffffffff82895401: mds_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mds_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff828b014e)
Location: arch/x86/kernel/cpu/bugs.c:238
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff828b014e-ffffffff828b01dc: mds_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mds_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff828b017c)
Location: arch/x86/kernel/cpu/bugs.c:238
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff828b017c-ffffffff828b020a: mds_select_mitigation (STB_LOCAL)
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
