# Function: <code>__ssb_select_mitigation</code>

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
In arch/x86/kernel/cpu/bugs.c (ffffffff826de79b)
Location: arch/x86/kernel/cpu/bugs.c:476
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
In arch/x86/kernel/cpu/bugs.c (ffffffff82894e4a)
Location: arch/x86/kernel/cpu/bugs.c:700
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
enum ssb_mitigation __ssb_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff828ac295)
Location: arch/x86/kernel/cpu/bugs.c:889
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff828ac295-ffffffff828ac414: __ssb_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
enum ssb_mitigation __ssb_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff828af40b)
Location: arch/x86/kernel/cpu/bugs.c:1019
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff828af40b-ffffffff828af586: __ssb_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum ssb_mitigation __ssb_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff82cd4db0)
Location: arch/x86/kernel/cpu/bugs.c:1126
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff82cd4db0-ffffffff82cd4e76: __ssb_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum ssb_mitigation __ssb_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff82fc0d56)
Location: arch/x86/kernel/cpu/bugs.c:1120
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff82fc0d56-ffffffff82fc0e1c: __ssb_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum ssb_mitigation __ssb_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff831cb10d)
Location: arch/x86/kernel/cpu/bugs.c:1120
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff831cb10d-ffffffff831cb29d: __ssb_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum ssb_mitigation __ssb_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff832ac74f)
Location: arch/x86/kernel/cpu/bugs.c:1242
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff832ac74f-ffffffff832ac90d: __ssb_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum ssb_mitigation __ssb_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8345d29a)
Location: arch/x86/kernel/cpu/bugs.c:1754
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff8345d29a-ffffffff8345d470: __ssb_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum ssb_mitigation __ssb_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff83e7d460)
Location: arch/x86/kernel/cpu/bugs.c:1803
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff83e7d460-ffffffff83e7d666: __ssb_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum ssb_mitigation __ssb_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff836a00d0)
Location: arch/x86/kernel/cpu/bugs.c:1914
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
```
**Symbols:**

```
ffffffff836a00d0-ffffffff836a02d6: __ssb_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum ssb_mitigation __ssb_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff838d0510)
Location: arch/x86/kernel/cpu/bugs.c:2055
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
```
**Symbols:**

```
ffffffff838d0510-ffffffff838d0716: __ssb_select_mitigation (STB_LOCAL)
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
enum ssb_mitigation __ssb_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8289d42a)
Location: arch/x86/kernel/cpu/bugs.c:1019
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff8289d42a-ffffffff8289d5a5: __ssb_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
enum ssb_mitigation __ssb_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff82895612)
Location: arch/x86/kernel/cpu/bugs.c:1019
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff82895612-ffffffff82895794: __ssb_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
enum ssb_mitigation __ssb_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff828b03ed)
Location: arch/x86/kernel/cpu/bugs.c:1019
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff828b03ed-ffffffff828b0568: __ssb_select_mitigation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
enum ssb_mitigation __ssb_select_mitigation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff828b041b)
Location: arch/x86/kernel/cpu/bugs.c:1019
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff828b041b-ffffffff828b0596: __ssb_select_mitigation (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
