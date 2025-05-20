# Function: <code>stibp_tif_to_spec_ctrl</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103aa7d)
Location: arch/x86/include/asm/spec-ctrl.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81045022)
Location: arch/x86/include/asm/spec-ctrl.h:56
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff8103d0b9)
Location: arch/x86/include/asm/spec-ctrl.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047a54)
Location: arch/x86/include/asm/spec-ctrl.h:56
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff8103d879)
Location: arch/x86/include/asm/spec-ctrl.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048294)
Location: arch/x86/include/asm/spec-ctrl.h:56
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff81040934)
Location: arch/x86/include/asm/spec-ctrl.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104bda2)
Location: arch/x86/include/asm/spec-ctrl.h:56
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff81040884)
Location: arch/x86/include/asm/spec-ctrl.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104b2e2)
Location: arch/x86/include/asm/spec-ctrl.h:56
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff8104227b)
Location: arch/x86/include/asm/spec-ctrl.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104d049)
Location: arch/x86/include/asm/spec-ctrl.h:56
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff810485c8)
Location: arch/x86/include/asm/spec-ctrl.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810546b6)
Location: arch/x86/include/asm/spec-ctrl.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
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
In arch/x86/kernel/process.c (ffffffff8105197d)
Location: arch/x86/include/asm/spec-ctrl.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
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
In arch/x86/kernel/process.c (ffffffff8105effd)
Location: arch/x86/include/asm/spec-ctrl.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
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
In arch/x86/kernel/process.c (ffffffff810606fd)
Location: arch/x86/include/asm/spec-ctrl.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
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
In arch/x86/kernel/process.c (ffffffff81067785)
Location: arch/x86/include/asm/spec-ctrl.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
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
In arch/x86/kernel/process.c (ffffffff8103d9f9)
Location: arch/x86/include/asm/spec-ctrl.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048404)
Location: arch/x86/include/asm/spec-ctrl.h:56
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff8102d0eb)
Location: arch/x86/include/asm/spec-ctrl.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81037756)
Location: arch/x86/include/asm/spec-ctrl.h:56
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff8103d839)
Location: arch/x86/include/asm/spec-ctrl.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048244)
Location: arch/x86/include/asm/spec-ctrl.h:56
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff8103e914)
Location: arch/x86/include/asm/spec-ctrl.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81049654)
Location: arch/x86/include/asm/spec-ctrl.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
</details>
</li>
</ul>

## Differences
