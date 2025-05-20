# Function: <code>copy_init_fpstate_to_fpregs</code>

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
In arch/x86/kernel/fpu/core.c (ffffffff8103a290)
Location: arch/x86/kernel/fpu/core.c:408
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
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
In arch/x86/kernel/fpu/core.c (ffffffff810399c2)
Location: arch/x86/kernel/fpu/core.c:500
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
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
In arch/x86/kernel/fpu/core.c (ffffffff81039309)
Location: arch/x86/kernel/fpu/core.c:443
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
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
In arch/x86/kernel/fpu/core.c (ffffffff81037249)
Location: arch/x86/kernel/fpu/core.c:436
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
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
In arch/x86/kernel/fpu/core.c (ffffffff81039524)
Location: arch/x86/kernel/fpu/core.c:365
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
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
In arch/x86/kernel/fpu/core.c (ffffffff8103aa64)
Location: arch/x86/kernel/fpu/core.c:366
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
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
In arch/x86/kernel/fpu/core.c (ffffffff8103bf64)
Location: arch/x86/kernel/fpu/core.c:364
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
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
In arch/x86/kernel/fpu/core.c (ffffffff8103e433)
Location: arch/x86/kernel/fpu/core.c:297
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
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
In arch/x86/kernel/fpu/core.c (ffffffff8103ebf3)
Location: arch/x86/kernel/fpu/core.c:297
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void copy_init_fpstate_to_fpregs(u64 features_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81041870)
Location: arch/x86/kernel/fpu/core.c:303
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
**Symbols:**

```
ffffffff81041870-ffffffff810418b4: copy_init_fpstate_to_fpregs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void copy_init_fpstate_to_fpregs(u64 features_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810418e0)
Location: arch/x86/kernel/fpu/core.c:343
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
**Symbols:**

```
ffffffff810418e0-ffffffff81041924: copy_init_fpstate_to_fpregs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void copy_init_fpstate_to_fpregs(u64 features_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810432e0)
Location: arch/x86/kernel/fpu/core.c:343
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
**Symbols:**

```
ffffffff810432e0-ffffffff81043324: copy_init_fpstate_to_fpregs (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In arch/x86/kernel/fpu/core.c (ffffffff8103ed73)
Location: arch/x86/kernel/fpu/core.c:297
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
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
In arch/x86/kernel/fpu/core.c (ffffffff8102e573)
Location: arch/x86/kernel/fpu/core.c:297
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
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
In arch/x86/kernel/fpu/core.c (ffffffff8103ebb3)
Location: arch/x86/kernel/fpu/core.c:297
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
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
In arch/x86/kernel/fpu/core.c (ffffffff8103fe53)
Location: arch/x86/kernel/fpu/core.c:297
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
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
</ul>
