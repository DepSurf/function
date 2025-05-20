# Function: <code>fpstate_init_fxstate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/init.c (ffffffff81f697db)
Location: arch/x86/include/asm/fpu/internal.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039a8a)
Location: arch/x86/include/asm/fpu/internal.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__activate_fpstate_read
  - arch/x86/kernel/fpu/core.c:fpu__activate_fpstate_write
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
In arch/x86/kernel/fpu/core.c (ffffffff81038d40)
Location: arch/x86/include/asm/fpu/internal.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpstate_init
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
In arch/x86/kernel/fpu/core.c (ffffffff81038837)
Location: arch/x86/include/asm/fpu/internal.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpstate_init
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
In arch/x86/kernel/fpu/core.c (ffffffff810368f6)
Location: arch/x86/include/asm/fpu/internal.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpstate_init
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
In arch/x86/kernel/fpu/core.c (ffffffff81038cf6)
Location: arch/x86/include/asm/fpu/internal.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpstate_init
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
In arch/x86/kernel/fpu/core.c (ffffffff8103a176)
Location: arch/x86/include/asm/fpu/internal.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpstate_init
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
In arch/x86/kernel/fpu/core.c (ffffffff8103b696)
Location: arch/x86/include/asm/fpu/internal.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpstate_init
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
In arch/x86/kernel/fpu/core.c (ffffffff8103dcb6)
Location: arch/x86/include/asm/fpu/internal.h:98
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpstate_init
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
In arch/x86/kernel/fpu/core.c (ffffffff8103e476)
Location: arch/x86/include/asm/fpu/internal.h:98
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpstate_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81041466)
Location: arch/x86/include/asm/fpu/internal.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpstate_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81041546)
Location: arch/x86/include/asm/fpu/internal.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpstate_init
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
In arch/x86/kernel/fpu/core.c (ffffffff81042f46)
Location: arch/x86/include/asm/fpu/internal.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpstate_init
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
In arch/x86/kernel/fpu/core.c (ffffffff81049246)
Location: arch/x86/kernel/fpu/core.c:215
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpstate_init
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
In arch/x86/kernel/fpu/core.c (ffffffff8105295d)
Location: arch/x86/kernel/fpu/core.c:484
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_alloc_guest_fpstate
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
In arch/x86/kernel/fpu/core.c (ffffffff8105ffcd)
Location: arch/x86/kernel/fpu/core.c:481
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_alloc_guest_fpstate
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
In arch/x86/kernel/fpu/core.c (ffffffff8106173d)
Location: arch/x86/kernel/fpu/core.c:481
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_alloc_guest_fpstate
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
In arch/x86/kernel/fpu/core.c (ffffffff8106884d)
Location: arch/x86/kernel/fpu/core.c:482
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_alloc_guest_fpstate
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
In arch/x86/kernel/fpu/core.c (ffffffff8103e5f6)
Location: arch/x86/include/asm/fpu/internal.h:98
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpstate_init
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
In arch/x86/kernel/fpu/core.c (ffffffff8102ddf6)
Location: arch/x86/include/asm/fpu/internal.h:98
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpstate_init
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
In arch/x86/kernel/fpu/core.c (ffffffff8103e436)
Location: arch/x86/include/asm/fpu/internal.h:98
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpstate_init
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
In arch/x86/kernel/fpu/core.c (ffffffff8103f5c6)
Location: arch/x86/include/asm/fpu/internal.h:98
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpstate_init
```
</details>
</li>
</ul>

## Differences
