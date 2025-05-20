# Function: <code>user_fpu_begin</code>

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
In arch/x86/kernel/fpu/core.c (ffffffff8103a314)
Location: arch/x86/include/asm/fpu/internal.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103ada9)
Location: arch/x86/include/asm/fpu/internal.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81039a2e)
Location: arch/x86/include/asm/fpu/internal.h:660
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a609)
Location: arch/x86/include/asm/fpu/internal.h:660
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810392f7)
Location: arch/x86/include/asm/fpu/internal.h:605
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81039ef9)
Location: arch/x86/include/asm/fpu/internal.h:605
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81037237)
Location: arch/x86/include/asm/fpu/internal.h:615
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81037ecd)
Location: arch/x86/include/asm/fpu/internal.h:615
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81039502)
Location: arch/x86/include/asm/fpu/internal.h:571
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a1b4)
Location: arch/x86/include/asm/fpu/internal.h:571
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103aa50)
Location: arch/x86/include/asm/fpu/internal.h:571
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103b5df)
Location: arch/x86/include/asm/fpu/internal.h:571
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
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
In arch/x86/kernel/fpu/core.c (ffffffff8103bf50)
Location: arch/x86/include/asm/fpu/internal.h:574
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103cbf9)
Location: arch/x86/include/asm/fpu/internal.h:574
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
</details>
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
