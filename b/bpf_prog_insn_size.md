# Function: <code>bpf_prog_insn_size</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118a678)
Location: include/linux/filter.h:519
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_calc_tag
```
```
In kernel/bpf/syscall.c (ffffffff8118d563)
Location: include/linux/filter.h:519
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
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
In kernel/bpf/core.c (ffffffff8118edb8)
Location: include/linux/filter.h:572
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_calc_tag
```
```
In kernel/bpf/syscall.c (ffffffff811937a9)
Location: include/linux/filter.h:572
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
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
In kernel/bpf/core.c (ffffffff8119d228)
Location: include/linux/filter.h:577
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_calc_tag
```
```
In kernel/bpf/syscall.c (ffffffff8119eef4)
Location: include/linux/filter.h:577
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_load
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
In kernel/bpf/core.c (ffffffff811b1a29)
Location: include/linux/filter.h:617
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
```
```
In kernel/bpf/syscall.c (ffffffff811b5da0)
Location: include/linux/filter.h:617
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
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
In kernel/bpf/core.c (ffffffff811c0269)
Location: include/linux/filter.h:652
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
```
```
In kernel/bpf/syscall.c (ffffffff811c39d3)
Location: include/linux/filter.h:652
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
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
In kernel/bpf/core.c (ffffffff811d0bf9)
Location: include/linux/filter.h:708
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
```
```
In kernel/bpf/syscall.c (ffffffff811d516c)
Location: include/linux/filter.h:708
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
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
In kernel/bpf/core.c (ffffffff811dd189)
Location: include/linux/filter.h:708
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
```
```
In kernel/bpf/syscall.c (ffffffff811e1875)
Location: include/linux/filter.h:708
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
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
In kernel/bpf/core.c (ffffffff811f9bb7)
Location: include/linux/filter.h:739
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
```
```
In kernel/bpf/syscall.c (ffffffff811fbec6)
Location: include/linux/filter.h:739
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
  - kernel/bpf/syscall.c:bpf_prog_load
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
In kernel/bpf/core.c (ffffffff811f8be7)
Location: include/linux/filter.h:748
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
```
```
In kernel/bpf/syscall.c (ffffffff811faf96)
Location: include/linux/filter.h:748
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
  - kernel/bpf/syscall.c:bpf_prog_load
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
In kernel/bpf/core.c (ffffffff811f99d7)
Location: include/linux/filter.h:791
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
```
```
In kernel/bpf/syscall.c (ffffffff811fbd86)
Location: include/linux/filter.h:791
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
  - kernel/bpf/syscall.c:bpf_prog_load
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
In kernel/bpf/core.c (ffffffff8122b087)
Location: include/linux/filter.h:812
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
```
```
In kernel/bpf/syscall.c (ffffffff8122d376)
Location: include/linux/filter.h:812
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
  - kernel/bpf/syscall.c:bpf_prog_load
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
In kernel/bpf/core.c (ffffffff8126ca6a)
Location: include/linux/filter.h:815
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
```
```
In kernel/bpf/syscall.c (ffffffff8126f8bf)
Location: include/linux/filter.h:815
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
  - kernel/bpf/syscall.c:bpf_prog_load
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
In kernel/bpf/core.c (ffffffff812c1b7a)
Location: include/linux/filter.h:787
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
```
```
In kernel/bpf/syscall.c (ffffffff812c81f1)
Location: include/linux/filter.h:787
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
  - kernel/bpf/syscall.c:bpf_prog_load
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
In kernel/bpf/core.c (ffffffff812e89ef)
Location: include/linux/filter.h:787
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
```
```
In kernel/bpf/syscall.c (ffffffff812ef6b1)
Location: include/linux/filter.h:787
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
  - kernel/bpf/syscall.c:bpf_prog_load
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
In kernel/bpf/core.c (ffffffff81306d5f)
Location: include/linux/filter.h:821
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
```
```
In kernel/bpf/syscall.c (ffffffff8130e491)
Location: include/linux/filter.h:821
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_insn_prepare_dump
  - kernel/bpf/syscall.c:bpf_prog_load
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
In kernel/bpf/core.c (ffff80001025dce8)
Location: include/linux/filter.h:708
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
```
```
In kernel/bpf/syscall.c (ffff8000102648e4)
Location: include/linux/filter.h:708
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0491324)
Location: include/linux/filter.h:708
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
  - kernel/bpf/core.c:bpf_prog_calc_tag
```
```
In kernel/bpf/syscall.c (c0494360)
Location: include/linux/filter.h:708
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_load
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0000000003027e0)
Location: include/linux/filter.h:708
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
```
```
In kernel/bpf/syscall.c (c0000000003092f8)
Location: include/linux/filter.h:708
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019c170)
Location: include/linux/filter.h:708
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
```
```
In kernel/bpf/syscall.c (ffffffe0001a055e)
Location: include/linux/filter.h:708
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
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
In kernel/bpf/core.c (ffffffff811d57a9)
Location: include/linux/filter.h:708
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
```
```
In kernel/bpf/syscall.c (ffffffff811d9e95)
Location: include/linux/filter.h:708
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
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
In kernel/bpf/core.c (ffffffff811c8569)
Location: include/linux/filter.h:708
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
```
```
In kernel/bpf/syscall.c (ffffffff811ccc55)
Location: include/linux/filter.h:708
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
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
In kernel/bpf/core.c (ffffffff811d3579)
Location: include/linux/filter.h:708
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
```
```
In kernel/bpf/syscall.c (ffffffff811d7c65)
Location: include/linux/filter.h:708
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
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
In kernel/bpf/core.c (ffffffff811e1869)
Location: include/linux/filter.h:708
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_calc_tag
```
```
In kernel/bpf/syscall.c (ffffffff811e6005)
Location: include/linux/filter.h:708
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
</details>
</li>
</ul>

## Differences
