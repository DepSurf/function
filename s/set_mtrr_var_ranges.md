# Function: <code>set_mtrr_var_ranges</code>

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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104c1cd)
Location: arch/x86/kernel/cpu/mtrr/generic.c:654
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104c278)
Location: arch/x86/kernel/cpu/mtrr/generic.c:657
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104e6c8)
Location: arch/x86/kernel/cpu/mtrr/generic.c:657
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104e62f)
Location: arch/x86/kernel/cpu/mtrr/generic.c:657
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81051f9f)
Location: arch/x86/kernel/cpu/mtrr/generic.c:657
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81054c6f)
Location: arch/x86/kernel/cpu/mtrr/generic.c:657
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105232f)
Location: arch/x86/kernel/cpu/mtrr/generic.c:657
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105542f)
Location: arch/x86/kernel/cpu/mtrr/generic.c:658
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055d2f)
Location: arch/x86/kernel/cpu/mtrr/generic.c:658
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
bool set_mtrr_var_ranges(unsigned int index, struct mtrr_var_range *vr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105ae20)
Location: arch/x86/kernel/cpu/mtrr/generic.c:658
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
```
**Symbols:**

```
ffffffff8105ae20-ffffffff8105aed5: set_mtrr_var_ranges (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool set_mtrr_var_ranges(unsigned int index, struct mtrr_var_range *vr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81059980)
Location: arch/x86/kernel/cpu/mtrr/generic.c:658
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
```
**Symbols:**

```
ffffffff81059980-ffffffff81059a35: set_mtrr_var_ranges (STB_LOCAL)
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105a489)
Location: arch/x86/kernel/cpu/mtrr/generic.c:657
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81063980)
Location: arch/x86/kernel/cpu/mtrr/generic.c:657
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810705cb)
Location: arch/x86/kernel/cpu/mtrr/generic.c:657
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810807bb)
Location: arch/x86/kernel/cpu/mtrr/generic.c:641
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81082c2b)
Location: arch/x86/kernel/cpu/mtrr/generic.c:875
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8108a73b)
Location: arch/x86/kernel/cpu/mtrr/generic.c:881
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810558af)
Location: arch/x86/kernel/cpu/mtrr/generic.c:658
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810459d7)
Location: arch/x86/kernel/cpu/mtrr/generic.c:658
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055cdf)
Location: arch/x86/kernel/cpu/mtrr/generic.c:658
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105717f)
Location: arch/x86/kernel/cpu/mtrr/generic.c:658
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
</ul>
