# Function: <code>check_xstate_against_struct</code>

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
In arch/x86/kernel/fpu/xstate.c (ffffffff81f69d33)
Location: arch/x86/kernel/fpu/xstate.c:449
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
In arch/x86/kernel/fpu/xstate.c (ffffffff81f91daf)
Location: arch/x86/kernel/fpu/xstate.c:520
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
In arch/x86/kernel/fpu/xstate.c (ffffffff81fcd05f)
Location: arch/x86/kernel/fpu/xstate.c:525
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
In arch/x86/kernel/fpu/xstate.c (ffffffff820ad796)
Location: arch/x86/kernel/fpu/xstate.c:526
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b669)
Location: arch/x86/kernel/fpu/xstate.c:544
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8103cb55)
Location: arch/x86/kernel/fpu/xstate.c:544
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8103e079)
Location: arch/x86/kernel/fpu/xstate.c:544
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void check_xstate_against_struct(int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff810408fc)
Location: arch/x86/kernel/fpu/xstate.c:538
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
**Symbols:**

```
ffffffff810408fc-ffffffff81040b46: check_xstate_against_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void check_xstate_against_struct(int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104108e)
Location: arch/x86/kernel/fpu/xstate.c:538
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
**Symbols:**

```
ffffffff8104108e-ffffffff810412d8: check_xstate_against_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void check_xstate_against_struct(int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff810442c5)
Location: arch/x86/kernel/fpu/xstate.c:576
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
```
**Symbols:**

```
ffffffff810442c5-ffffffff8104450f: check_xstate_against_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void check_xstate_against_struct(int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81bd476f)
Location: arch/x86/kernel/fpu/xstate.c:581
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
```
**Symbols:**

```
ffffffff81bd476f-ffffffff81bd4a15: check_xstate_against_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void check_xstate_against_struct(int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81bc6bc5)
Location: arch/x86/kernel/fpu/xstate.c:616
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
```
**Symbols:**

```
ffffffff81bc6bc5-ffffffff81bc6e63: check_xstate_against_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void check_xstate_against_struct(int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81c9a020)
Location: arch/x86/kernel/fpu/xstate.c:517
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
```
**Symbols:**

```
ffffffff81c9a020-ffffffff81c9a3d4: check_xstate_against_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool check_xstate_against_struct(int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8345a29a)
Location: arch/x86/kernel/fpu/xstate.c:524
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
```
**Symbols:**

```
ffffffff8345a29a-ffffffff8345a827: check_xstate_against_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool check_xstate_against_struct(int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff83e7a080)
Location: arch/x86/kernel/fpu/xstate.c:524
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
```
**Symbols:**

```
ffffffff83e7a080-ffffffff83e7a67d: check_xstate_against_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool check_xstate_against_struct(int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8369c7a0)
Location: arch/x86/kernel/fpu/xstate.c:524
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
```
**Symbols:**

```
ffffffff8369c7a0-ffffffff8369cd40: check_xstate_against_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool check_xstate_against_struct(int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff838cc490)
Location: arch/x86/kernel/fpu/xstate.c:528
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
```
**Symbols:**

```
ffffffff838cc490-ffffffff838ccab2: check_xstate_against_struct (STB_LOCAL)
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
void check_xstate_against_struct(int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104120e)
Location: arch/x86/kernel/fpu/xstate.c:538
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
**Symbols:**

```
ffffffff8104120e-ffffffff81041458: check_xstate_against_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void check_xstate_against_struct(int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff810308b0)
Location: arch/x86/kernel/fpu/xstate.c:538
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
**Symbols:**

```
ffffffff810308b0-ffffffff81030b2c: check_xstate_against_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void check_xstate_against_struct(int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104104e)
Location: arch/x86/kernel/fpu/xstate.c:538
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
**Symbols:**

```
ffffffff8104104e-ffffffff81041298: check_xstate_against_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void check_xstate_against_struct(int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104242e)
Location: arch/x86/kernel/fpu/xstate.c:538
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
**Symbols:**

```
ffffffff8104242e-ffffffff81042678: check_xstate_against_struct (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
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
