# Function: <code>bpf_prog_was_classic</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (0)
Location: include/linux/filter.h:589
Inline: True
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
In kernel/bpf/core.c (0)
Location: include/linux/filter.h:594
Inline: True
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
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/filter.h:634
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/filter.h:634
Inline: True
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
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/filter.h:669
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/filter.h:669
Inline: True
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
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/filter.h:725
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/filter.h:725
Inline: True
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
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/filter.h:725
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/filter.h:725
Inline: True
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810a1966)
Location: include/linux/filter.h:756
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
```
In kernel/bpf/core.c (ffffffff811fa1c6)
Location: include/linux/filter.h:756
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
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
In arch/x86/net/bpf_jit_comp.c (ffffffff8109c375)
Location: include/linux/filter.h:765
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
```
In kernel/bpf/core.c (ffffffff811f91f6)
Location: include/linux/filter.h:765
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
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
In arch/x86/net/bpf_jit_comp.c (ffffffff8109ccd5)
Location: include/linux/filter.h:808
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
```
In kernel/bpf/core.c (ffffffff811f9fde)
Location: include/linux/filter.h:808
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810ad205)
Location: include/linux/filter.h:829
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
```
In kernel/bpf/core.c (ffffffff8122b6ae)
Location: include/linux/filter.h:829
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810c3113)
Location: include/linux/filter.h:832
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
```
In kernel/bpf/core.c (ffffffff8126d12e)
Location: include/linux/filter.h:832
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810dfeb1)
Location: include/linux/filter.h:804
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
```
In kernel/bpf/core.c (ffffffff812c228e)
Location: include/linux/filter.h:804
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810eb401)
Location: include/linux/filter.h:804
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
```
In kernel/bpf/core.c (ffffffff812e914e)
Location: include/linux/filter.h:804
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810f4c08)
Location: include/linux/filter.h:838
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
```
In kernel/bpf/core.c (ffffffff813074be)
Location: include/linux/filter.h:838
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/net/bpf_jit_comp.c (ffff8000100b4a30)
Location: include/linux/filter.h:725
Inline: True
Inline callers:
  - arch/arm64/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/bpf/core.c (0)
Location: include/linux/filter.h:725
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c049187c)
Location: include/linux/filter.h:725
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (0)
Location: include/linux/filter.h:725
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (0)
Location: include/linux/filter.h:725
Inline: True
```
</details>
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
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/filter.h:725
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/filter.h:725
Inline: True
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
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/filter.h:725
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/filter.h:725
Inline: True
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
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/filter.h:725
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/filter.h:725
Inline: True
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
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/filter.h:725
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/filter.h:725
Inline: True
```
</details>
</li>
</ul>

## Differences
