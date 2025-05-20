# Function: <code>intel_check_pebs_isolation</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void intel_check_pebs_isolation();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8289d88b)
Location: arch/x86/events/intel/core.c:4000
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pebs_isolation_quirk
```
**Symbols:**

```
ffffffff8100c2d0-ffffffff8100c301: intel_check_pebs_isolation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void intel_check_pebs_isolation();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff828a08fa)
Location: arch/x86/events/intel/core.c:4018
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pebs_isolation_quirk
```
**Symbols:**

```
ffffffff8100c700-ffffffff8100c731: intel_check_pebs_isolation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void intel_check_pebs_isolation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d850)
Location: arch/x86/events/intel/core.c:4056
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pebs_isolation_quirk
```
**Symbols:**

```
ffffffff8100d850-ffffffff8100d881: intel_check_pebs_isolation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void intel_check_pebs_isolation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c930)
Location: arch/x86/events/intel/core.c:4423
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pebs_isolation_quirk
```
**Symbols:**

```
ffffffff8100c930-ffffffff8100c961: intel_check_pebs_isolation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_check_pebs_isolation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d360)
Location: arch/x86/events/intel/core.c:4710
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pebs_isolation_quirk
```
**Symbols:**

```
ffffffff8100d360-ffffffff8100d391: intel_check_pebs_isolation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intel_check_pebs_isolation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d800)
Location: arch/x86/events/intel/core.c:4730
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pebs_isolation_quirk
```
**Symbols:**

```
ffffffff8100d800-ffffffff8100d831: intel_check_pebs_isolation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_check_pebs_isolation();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100eba0)
Location: arch/x86/events/intel/core.c:4800
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pebs_isolation_quirk
```
**Symbols:**

```
ffffffff8100eba0-ffffffff8100ebdb: intel_check_pebs_isolation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void intel_check_pebs_isolation();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff83e66135)
Location: arch/x86/events/intel/core.c:4926
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pebs_isolation_quirk
```
**Symbols:**

```
ffffffff810122b0-ffffffff810122eb: intel_check_pebs_isolation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void intel_check_pebs_isolation();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff836867a5)
Location: arch/x86/events/intel/core.c:5057
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pebs_isolation_quirk
```
**Symbols:**

```
ffffffff810117b0-ffffffff810117eb: intel_check_pebs_isolation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void intel_check_pebs_isolation();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff838b59b5)
Location: arch/x86/events/intel/core.c:5221
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pebs_isolation_quirk
```
**Symbols:**

```
ffffffff81016f50-ffffffff81016f8b: intel_check_pebs_isolation (STB_LOCAL)
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
void intel_check_pebs_isolation();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8288e8fa)
Location: arch/x86/events/intel/core.c:4018
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pebs_isolation_quirk
```
**Symbols:**

```
ffffffff8100c700-ffffffff8100c731: intel_check_pebs_isolation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void intel_check_pebs_isolation();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8288c860)
Location: arch/x86/events/intel/core.c:4018
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pebs_isolation_quirk
```
**Symbols:**

```
ffffffff8100af00-ffffffff8100af31: intel_check_pebs_isolation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void intel_check_pebs_isolation();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff828a18fa)
Location: arch/x86/events/intel/core.c:4018
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pebs_isolation_quirk
```
**Symbols:**

```
ffffffff8100c6c0-ffffffff8100c6f1: intel_check_pebs_isolation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void intel_check_pebs_isolation();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff828a190e)
Location: arch/x86/events/intel/core.c:4018
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pebs_isolation_quirk
```
**Symbols:**

```
ffffffff8100c8f0-ffffffff8100c921: intel_check_pebs_isolation (STB_LOCAL)
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
