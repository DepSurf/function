# Function: <code>xfeatures_mask_independent</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104b08e)
Location: arch/x86/include/asm/fpu/xstate.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:validate_xsaves_xrstors
  - arch/x86/kernel/fpu/xstate.c:validate_xsaves_xrstors
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u64 xfeatures_mask_independent();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81055dbe)
Location: arch/x86/kernel/fpu/xstate.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:validate_independent_components
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
**Symbols:**

```
ffffffff810553d0-ffffffff810553e6: xfeatures_mask_independent (STB_LOCAL)
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
In arch/x86/kernel/fpu/xstate.c (ffffffff81063c1e)
Location: arch/x86/kernel/fpu/xstate.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:validate_independent_components
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8106556e)
Location: arch/x86/kernel/fpu/xstate.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:validate_independent_components
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8106c9ce)
Location: arch/x86/kernel/fpu/xstate.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:validate_independent_components
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
