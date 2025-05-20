# Function: <code>btf_member_bitfield_size</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811da59f)
Location: kernel/bpf/btf.c:438
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
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
In kernel/bpf/btf.c (ffffffff811ef517)
Location: kernel/bpf/btf.c:481
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
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
In kernel/bpf/btf.c (ffffffff811fbc57)
Location: kernel/bpf/btf.c:481
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
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
In kernel/bpf/btf.c (ffffffff81225030)
Location: include/linux/btf.h:132
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_struct_seq_show
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8122ff2c)
Location: include/linux/btf.h:132
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
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
In kernel/bpf/btf.c (ffffffff812283e7)
Location: include/linux/btf.h:192
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_walk
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff812383dc)
Location: include/linux/btf.h:192
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
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
In kernel/bpf/btf.c (ffffffff8122ce45)
Location: include/linux/btf.h:202
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_walk
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8123cbcc)
Location: include/linux/btf.h:202
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
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
In kernel/bpf/btf.c (ffffffff812657d5)
Location: include/linux/btf.h:203
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_walk
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8127761c)
Location: include/linux/btf.h:203
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
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
In tools/lib/bpf/relo_core.c (ffffffff812c9d3b)
Location: include/linux/btf.h:313
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
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
In tools/lib/bpf/relo_core.c (ffffffff81330e6b)
Location: include/linux/btf.h:415
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
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
In tools/lib/bpf/relo_core.c (ffffffff81361b0b)
Location: include/linux/btf.h:431
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
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
In tools/lib/bpf/relo_core.c (ffffffff8138a9bb)
Location: include/linux/btf.h:442
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffff80001028216c)
Location: kernel/bpf/btf.c:481
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
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
In kernel/bpf/btf.c (c04b1de4)
Location: kernel/bpf/btf.c:481
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
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
In kernel/bpf/btf.c (c00000000032c720)
Location: kernel/bpf/btf.c:481
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
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
In kernel/bpf/btf.c (ffffffe0001b82c4)
Location: kernel/bpf/btf.c:481
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
```
</details>
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
In kernel/bpf/btf.c (ffffffff811f4277)
Location: kernel/bpf/btf.c:481
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
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
In kernel/bpf/btf.c (ffffffff811e6fc7)
Location: kernel/bpf/btf.c:481
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
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
In kernel/bpf/btf.c (ffffffff811f2047)
Location: kernel/bpf/btf.c:481
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
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
In kernel/bpf/btf.c (ffffffff81200557)
Location: kernel/bpf/btf.c:481
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
```
</details>
</li>
</ul>

## Differences
