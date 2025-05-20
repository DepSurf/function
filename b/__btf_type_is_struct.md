# Function: <code>__btf_type_is_struct</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f1cd4)
Location: kernel/bpf/btf.c:370
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_find_spin_lock
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
In kernel/bpf/btf.c (ffffffff811fe3e4)
Location: kernel/bpf/btf.c:370
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_find_spin_lock
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
In kernel/bpf/btf.c (ffffffff81224a65)
Location: kernel/bpf/btf.c:365
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_find_spin_lock
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
In kernel/bpf/btf.c (ffffffff8122b16e)
Location: kernel/bpf/btf.c:446
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_find_spin_lock
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
In kernel/bpf/btf.c (ffffffff8122fb5c)
Location: kernel/bpf/btf.c:447
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_find_spin_lock
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
In kernel/bpf/btf.c (ffffffff8126200b)
Location: kernel/bpf/btf.c:447
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_find_field
  - kernel/bpf/btf.c:btf_find_field
  - kernel/bpf/btf.c:btf_find_field
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
In kernel/bpf/btf.c (ffffffff812b2b60)
Location: kernel/bpf/btf.c:479
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_find_field
  - kernel/bpf/btf.c:btf_find_field
  - kernel/bpf/btf.c:btf_find_field
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
In kernel/bpf/verifier.c (ffffffff812eae36)
Location: include/linux/btf.h:359
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff81317c2f)
Location: include/linux/btf.h:359
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_parse_fields
  - kernel/bpf/btf.c:btf_parse_fields
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
In kernel/bpf/verifier.c (ffffffff813174c3)
Location: include/linux/btf.h:375
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff813421d6)
Location: include/linux/btf.h:375
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_iter_kfuncs
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_parse_fields
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
In kernel/bpf/verifier.c (ffffffff813394c1)
Location: include/linux/btf.h:386
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff81368716)
Location: include/linux/btf.h:386
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_iter_kfuncs
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_validate_prog_ctx_type
  - kernel/bpf/btf.c:btf_validate_prog_ctx_type
  - kernel/bpf/btf.c:btf_validate_prog_ctx_type
  - kernel/bpf/btf.c:btf_validate_prog_ctx_type
  - kernel/bpf/btf.c:btf_validate_prog_ctx_type
  - kernel/bpf/btf.c:btf_parse_fields
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
In kernel/bpf/btf.c (ffff80001028537c)
Location: kernel/bpf/btf.c:370
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_find_spin_lock
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
In kernel/bpf/btf.c (c04b59d0)
Location: kernel/bpf/btf.c:370
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_find_spin_lock
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
In kernel/bpf/btf.c (c00000000032ffcc)
Location: kernel/bpf/btf.c:370
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_find_spin_lock
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
In kernel/bpf/btf.c (ffffffe0001ba80a)
Location: kernel/bpf/btf.c:370
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_find_spin_lock
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
In kernel/bpf/btf.c (ffffffff811f6a04)
Location: kernel/bpf/btf.c:370
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_find_spin_lock
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
In kernel/bpf/btf.c (ffffffff811e9754)
Location: kernel/bpf/btf.c:370
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_find_spin_lock
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
In kernel/bpf/btf.c (ffffffff811f47d4)
Location: kernel/bpf/btf.c:370
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_find_spin_lock
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
In kernel/bpf/btf.c (ffffffff81202ce4)
Location: kernel/bpf/btf.c:370
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_find_spin_lock
```
</details>
</li>
</ul>

## Differences
