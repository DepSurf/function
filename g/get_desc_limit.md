# Function: <code>get_desc_limit</code>

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
In arch/x86/kernel/tls.c (ffffffff8103d5f6)
Location: arch/x86/include/asm/desc.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
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
In arch/x86/kernel/tls.c (ffffffff8103d364)
Location: arch/x86/include/asm/desc.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
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
In arch/x86/kernel/tls.c (ffffffff8103cc54)
Location: arch/x86/include/asm/desc.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
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
In arch/x86/kernel/tls.c (ffffffff8103ac94)
Location: arch/x86/include/asm/desc.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
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
In arch/x86/kernel/tls.c (ffffffff8103d6c4)
Location: arch/x86/include/asm/desc.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
```
```
In arch/x86/lib/insn-eval.c (ffffffff819838b4)
Location: arch/x86/include/asm/desc.h:378
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/kernel/tls.c (ffffffff8103ec34)
Location: arch/x86/include/asm/desc.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
```
```
In arch/x86/lib/insn-eval.c (ffffffff819dfcf7)
Location: arch/x86/include/asm/desc.h:378
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/kernel/tls.c (ffffffff81040224)
Location: arch/x86/include/asm/desc.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
```
```
In arch/x86/lib/insn-eval.c (ffffffff81a1abe6)
Location: arch/x86/include/asm/desc.h:378
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/kernel/tls.c (ffffffff810428c4)
Location: arch/x86/include/asm/desc.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
```
```
In arch/x86/lib/insn-eval.c (ffffffff81a8a93f)
Location: arch/x86/include/asm/desc.h:378
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/kernel/tls.c (ffffffff81043034)
Location: arch/x86/include/asm/desc.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
```
```
In arch/x86/lib/insn-eval.c (ffffffff81ac1bff)
Location: arch/x86/include/asm/desc.h:378
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/kernel/tls.c (ffffffff810468c0)
Location: arch/x86/include/asm/desc.h:373
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:__ia32_sys_get_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_get_thread_area
```
```
In arch/x86/lib/insn-eval.c (ffffffff815fe2cb)
Location: arch/x86/include/asm/desc.h:373
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/kernel/tls.c (ffffffff8104650c)
Location: arch/x86/include/asm/desc.h:373
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
  - arch/x86/kernel/tls.c:do_get_thread_area
```
```
In arch/x86/lib/insn-eval.c (ffffffff816230c9)
Location: arch/x86/include/asm/desc.h:373
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/kernel/tls.c (ffffffff81047f2a)
Location: arch/x86/include/asm/desc.h:373
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
  - arch/x86/kernel/tls.c:do_get_thread_area
```
```
In arch/x86/lib/insn-eval.c (ffffffff81606975)
Location: arch/x86/include/asm/desc.h:373
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/kernel/tls.c (ffffffff8104e83a)
Location: arch/x86/include/asm/desc.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
  - arch/x86/kernel/tls.c:do_get_thread_area
```
```
In arch/x86/lib/insn-eval.c (ffffffff816753b9)
Location: arch/x86/include/asm/desc.h:394
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/kernel/tls.c (ffffffff810599e8)
Location: arch/x86/include/asm/desc.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
  - arch/x86/kernel/tls.c:do_get_thread_area
```
```
In arch/x86/lib/insn-eval.c (ffffffff8178fe5e)
Location: arch/x86/include/asm/desc.h:394
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/kernel/tls.c (ffffffff81067388)
Location: arch/x86/include/asm/desc.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
  - arch/x86/kernel/tls.c:do_get_thread_area
```
```
In arch/x86/lib/insn-eval.c (ffffffff8204d9de)
Location: arch/x86/include/asm/desc.h:394
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/kernel/tls.c (ffffffff810684e6)
Location: arch/x86/include/asm/desc.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
```
```
In arch/x86/lib/insn-eval.c (ffffffff820cc23c)
Location: arch/x86/include/asm/desc.h:394
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/kernel/tls.c (ffffffff8106f966)
Location: arch/x86/include/asm/desc.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
```
```
In arch/x86/lib/insn-eval.c (ffffffff821a6a6c)
Location: arch/x86/include/asm/desc.h:394
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/kernel/tls.c (ffffffff810431b4)
Location: arch/x86/include/asm/desc.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
```
```
In arch/x86/lib/insn-eval.c (ffffffff81a60a4f)
Location: arch/x86/include/asm/desc.h:378
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/kernel/tls.c (ffffffff810327d4)
Location: arch/x86/include/asm/desc.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
```
```
In arch/x86/lib/insn-eval.c (ffffffff81a1dba0)
Location: arch/x86/include/asm/desc.h:378
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/kernel/tls.c (ffffffff81042ff4)
Location: arch/x86/include/asm/desc.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
```
```
In arch/x86/lib/insn-eval.c (ffffffff81acce3f)
Location: arch/x86/include/asm/desc.h:378
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
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
In arch/x86/kernel/tls.c (ffffffff81044244)
Location: arch/x86/include/asm/desc.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:fill_user_desc
```
```
In arch/x86/lib/insn-eval.c (ffffffff81ad934f)
Location: arch/x86/include/asm/desc.h:378
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
```
</details>
</li>
</ul>

## Differences
