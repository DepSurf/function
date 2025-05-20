# Function: <code>btf_type_member</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811c7729)
Location: kernel/bpf/btf.c:408
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_struct_check_meta
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
In kernel/bpf/btf.c (ffffffff811da589)
Location: kernel/bpf/btf.c:455
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_struct_check_meta
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
In kernel/bpf/btf.c (ffffffff811ef509)
Location: kernel/bpf/btf.c:498
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_check_meta
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
In kernel/bpf/btf.c (ffffffff811fbc49)
Location: kernel/bpf/btf.c:498
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_check_meta
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
In kernel/bpf/verifier.c (0)
Location: include/linux/btf.h:139
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff81224ff8)
Location: include/linux/btf.h:139
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_check_meta
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8122f79c)
Location: include/linux/btf.h:139
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
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
In kernel/bpf/verifier.c (0)
Location: include/linux/btf.h:199
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff8122839d)
Location: include/linux/btf.h:199
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_check_meta
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81237c9c)
Location: include/linux/btf.h:199
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
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
In kernel/bpf/verifier.c (0)
Location: include/linux/btf.h:209
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff8122cdff)
Location: include/linux/btf.h:209
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_check_meta
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8123c4b9)
Location: include/linux/btf.h:209
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
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
In kernel/bpf/verifier.c (0)
Location: include/linux/btf.h:210
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff8126578f)
Location: include/linux/btf.h:210
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_find_field
  - kernel/bpf/btf.c:btf_struct_check_meta
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81276e75)
Location: include/linux/btf.h:210
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
```
In net/ipv4/bpf_tcp_ca.c (0)
Location: include/linux/btf.h:210
Inline: True
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
In kernel/bpf/verifier.c (0)
Location: include/linux/btf.h:320
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff812b1619)
Location: include/linux/btf.h:320
Inline: True
Inline callers:
  - kernel/bpf/btf.c:__btf_type_is_scalar_struct
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_find_field
  - kernel/bpf/btf.c:btf_struct_check_meta
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff812c6a9f)
Location: include/linux/btf.h:320
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
```
In net/ipv4/bpf_tcp_ca.c (0)
Location: include/linux/btf.h:320
Inline: True
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
In kernel/bpf/verifier.c (ffffffff812dbfd9)
Location: include/linux/btf.h:422
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
```
```
In kernel/bpf/btf.c (ffffffff81311d07)
Location: include/linux/btf.h:422
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_parse_fields
  - kernel/bpf/btf.c:btf_struct_check_meta
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8132c30f)
Location: include/linux/btf.h:422
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
```
In net/ipv4/bpf_tcp_ca.c (0)
Location: include/linux/btf.h:422
Inline: True
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
In kernel/bpf/verifier.c (ffffffff812f7b08)
Location: include/linux/btf.h:438
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
```
```
In kernel/bpf/btf.c (ffffffff8134aecb)
Location: include/linux/btf.h:438
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_nested_type_is_trusted
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_check_meta
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8135c8c9)
Location: include/linux/btf.h:438
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
```
In net/ipv4/bpf_tcp_ca.c (0)
Location: include/linux/btf.h:438
Inline: True
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
In kernel/trace/trace_btf.c (ffffffff812f8569)
Location: include/linux/btf.h:449
Inline: True
Inline callers:
  - kernel/trace/trace_btf.c:btf_find_struct_member
```
```
In kernel/bpf/verifier.c (ffffffff81315fa8)
Location: include/linux/btf.h:449
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
```
```
In kernel/bpf/btf.c (ffffffff813716dd)
Location: include/linux/btf.h:449
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_nested_type_is_trusted
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_check_meta
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81385bf6)
Location: include/linux/btf.h:449
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
```
In net/ipv4/bpf_tcp_ca.c (0)
Location: include/linux/btf.h:449
Inline: True
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
In kernel/bpf/btf.c (ffff800010282130)
Location: kernel/bpf/btf.c:498
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_check_meta
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
In kernel/bpf/btf.c (c04b1dbc)
Location: kernel/bpf/btf.c:498
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_check_meta
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
In kernel/bpf/btf.c (c00000000032c708)
Location: kernel/bpf/btf.c:498
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_check_meta
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
In kernel/bpf/btf.c (ffffffe0001b8276)
Location: kernel/bpf/btf.c:498
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_check_meta
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
In kernel/bpf/btf.c (ffffffff811f4269)
Location: kernel/bpf/btf.c:498
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_check_meta
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
In kernel/bpf/btf.c (ffffffff811e6fb9)
Location: kernel/bpf/btf.c:498
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_check_meta
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
In kernel/bpf/btf.c (ffffffff811f2039)
Location: kernel/bpf/btf.c:498
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_check_meta
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
In kernel/bpf/btf.c (ffffffff81200549)
Location: kernel/bpf/btf.c:498
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_check_meta
```
</details>
</li>
</ul>

## Differences
