# Function: <code>ssbd_tif_to_spec_ctrl</code>

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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103972c)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculative_store_bypass_update
  - arch/x86/kernel/process.c:speculative_store_bypass_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104384d)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103aa23)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81044fbd)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d01e)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810479ee)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d7de)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104822e)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81040af0)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104bd4e)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81040a49)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104b28e)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81042441)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104cff7)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8104878e)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81054667)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81051a7f)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8105f464)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8105f0fb)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106dba7)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff810607fb)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106f4c7)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff810678a6)
Location: arch/x86/include/asm/spec-ctrl.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81076887)
Location: arch/x86/include/asm/spec-ctrl.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d95e)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104839e)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8102d053)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810376ed)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d79e)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810481de)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103e8ba)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810495ee)
Location: arch/x86/include/asm/spec-ctrl.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
</details>
</li>
</ul>

## Differences
