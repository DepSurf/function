# Function: <code>set_mtrr_state</code>

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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104c19c)
Location: arch/x86/kernel/cpu/mtrr/generic.c:687
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104c24d)
Location: arch/x86/kernel/cpu/mtrr/generic.c:690
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104e69d)
Location: arch/x86/kernel/cpu/mtrr/generic.c:690
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104e60d)
Location: arch/x86/kernel/cpu/mtrr/generic.c:690
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81051f7d)
Location: arch/x86/kernel/cpu/mtrr/generic.c:690
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81054c2d)
Location: arch/x86/kernel/cpu/mtrr/generic.c:690
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810522ed)
Location: arch/x86/kernel/cpu/mtrr/generic.c:690
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810553ed)
Location: arch/x86/kernel/cpu/mtrr/generic.c:691
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055ced)
Location: arch/x86/kernel/cpu/mtrr/generic.c:691
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int set_mtrr_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105b0b0)
Location: arch/x86/kernel/cpu/mtrr/generic.c:691
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
```
**Symbols:**

```
ffffffff8105b0b0-ffffffff8105b174: set_mtrr_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int set_mtrr_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81059c10)
Location: arch/x86/kernel/cpu/mtrr/generic.c:691
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
```
**Symbols:**

```
ffffffff81059c10-ffffffff81059cd4: set_mtrr_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long unsigned int set_mtrr_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: arch/x86/kernel/cpu/mtrr/generic.c:690
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
```
**Symbols:**

```
ffffffff8105a430-ffffffff8105a66a: set_mtrr_state (STB_LOCAL)
ffffffff81bc81f9-ffffffff81bc822a: set_mtrr_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int set_mtrr_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: arch/x86/kernel/cpu/mtrr/generic.c:690
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
```
**Symbols:**

```
ffffffff810638a0-ffffffff81063bb1: set_mtrr_state (STB_LOCAL)
ffffffff81c9c074-ffffffff81c9c0a5: set_mtrr_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int set_mtrr_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: arch/x86/kernel/cpu/mtrr/generic.c:690
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
```
**Symbols:**

```
ffffffff81070570-ffffffff8107089f: set_mtrr_state (STB_LOCAL)
ffffffff81e4b491-ffffffff81e4b4c2: set_mtrr_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int set_mtrr_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81080760)
Location: arch/x86/kernel/cpu/mtrr/generic.c:677
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_generic_set_state
```
**Symbols:**

```
ffffffff81080760-ffffffff81080abb: set_mtrr_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long unsigned int set_mtrr_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: arch/x86/kernel/cpu/mtrr/generic.c:909
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_generic_set_state
```
**Symbols:**

```
ffffffff81082bd0-ffffffff81082f0d: set_mtrr_state (STB_LOCAL)
ffffffff820d1502-ffffffff820d1517: set_mtrr_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long unsigned int set_mtrr_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: arch/x86/kernel/cpu/mtrr/generic.c:915
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_generic_set_state
```
**Symbols:**

```
ffffffff8108a6e0-ffffffff8108aa1d: set_mtrr_state (STB_LOCAL)
ffffffff821ac0ca-ffffffff821ac0df: set_mtrr_state.cold (STB_LOCAL)
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105586d)
Location: arch/x86/kernel/cpu/mtrr/generic.c:691
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81045990)
Location: arch/x86/kernel/cpu/mtrr/generic.c:691
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055c9d)
Location: arch/x86/kernel/cpu/mtrr/generic.c:691
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105713d)
Location: arch/x86/kernel/cpu/mtrr/generic.c:691
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
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
