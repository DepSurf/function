# Function: <code>print_mtrr_state</code>

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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81f6b6f7)
Location: arch/x86/kernel/cpu/mtrr/generic.c:402
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81f93a29)
Location: arch/x86/kernel/cpu/mtrr/generic.c:402
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81fcf035)
Location: arch/x86/kernel/cpu/mtrr/generic.c:402
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff820afa7a)
Location: arch/x86/kernel/cpu/mtrr/generic.c:402
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff826b6286)
Location: arch/x86/kernel/cpu/mtrr/generic.c:402
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff826dffc5)
Location: arch/x86/kernel/cpu/mtrr/generic.c:402
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff82895f85)
Location: arch/x86/kernel/cpu/mtrr/generic.c:402
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff828adb32)
Location: arch/x86/kernel/cpu/mtrr/generic.c:403
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff828b0e76)
Location: arch/x86/kernel/cpu/mtrr/generic.c:403
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void print_mtrr_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff82cd5e5e)
Location: arch/x86/kernel/cpu/mtrr/generic.c:403
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
**Symbols:**

```
ffffffff82cd5e5e-ffffffff82cd6040: print_mtrr_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void print_mtrr_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff82fc1e21)
Location: arch/x86/kernel/cpu/mtrr/generic.c:403
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
**Symbols:**

```
ffffffff82fc1e21-ffffffff82fc2003: print_mtrr_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void print_mtrr_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff831cc44b)
Location: arch/x86/kernel/cpu/mtrr/generic.c:402
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
**Symbols:**

```
ffffffff831cc44b-ffffffff831cc639: print_mtrr_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void print_mtrr_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff832add0b)
Location: arch/x86/kernel/cpu/mtrr/generic.c:402
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
**Symbols:**

```
ffffffff832add0b-ffffffff832adfd8: print_mtrr_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void print_mtrr_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8345ec4c)
Location: arch/x86/kernel/cpu/mtrr/generic.c:402
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
**Symbols:**

```
ffffffff8345ec4c-ffffffff8345ef2d: print_mtrr_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void print_mtrr_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff83e7ff50)
Location: arch/x86/kernel/cpu/mtrr/generic.c:400
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
**Symbols:**

```
ffffffff83e7ff50-ffffffff83e80440: print_mtrr_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void print_mtrr_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff836a2cd0)
Location: arch/x86/kernel/cpu/mtrr/generic.c:632
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
**Symbols:**

```
ffffffff836a2cd0-ffffffff836a318f: print_mtrr_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void print_mtrr_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff838d2d50)
Location: arch/x86/kernel/cpu/mtrr/generic.c:638
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
**Symbols:**

```
ffffffff838d2d50-ffffffff838d320f: print_mtrr_state (STB_LOCAL)
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8289ee95)
Location: arch/x86/kernel/cpu/mtrr/generic.c:403
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff82897062)
Location: arch/x86/kernel/cpu/mtrr/generic.c:403
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff828b1e58)
Location: arch/x86/kernel/cpu/mtrr/generic.c:403
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff828b1e86)
Location: arch/x86/kernel/cpu/mtrr/generic.c:403
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
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
