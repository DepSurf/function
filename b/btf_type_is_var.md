# Function: <code>btf_type_is_var</code>

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
In kernel/bpf/btf.c (ffffffff811f09c6)
Location: kernel/bpf/btf.c:390
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
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
In kernel/bpf/btf.c (ffffffff811fd0d6)
Location: kernel/bpf/btf.c:390
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
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
In kernel/bpf/btf.c (ffffffff812233a6)
Location: kernel/bpf/btf.c:375
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
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
In kernel/bpf/verifier.c (ffffffff81205db4)
Location: include/linux/btf.h:155
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
```
In kernel/bpf/btf.c (ffffffff81229902)
Location: include/linux/btf.h:155
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
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
In kernel/bpf/verifier.c (ffffffff81207bee)
Location: include/linux/btf.h:165
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
```
In kernel/bpf/btf.c (ffffffff8122e19c)
Location: include/linux/btf.h:165
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
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
In kernel/bpf/verifier.c (ffffffff8123b47e)
Location: include/linux/btf.h:166
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
```
In kernel/bpf/btf.c (ffffffff81266d9c)
Location: include/linux/btf.h:166
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
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
In kernel/bpf/verifier.c (ffffffff81280fad)
Location: include/linux/btf.h:247
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
```
In kernel/bpf/btf.c (ffffffff812b3fea)
Location: include/linux/btf.h:247
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
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
In kernel/bpf/verifier.c (ffffffff812d8d1d)
Location: include/linux/btf.h:339
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
```
In kernel/bpf/btf.c (ffffffff81315b39)
Location: include/linux/btf.h:339
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
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
In kernel/bpf/verifier.c (ffffffff812f7e2d)
Location: include/linux/btf.h:355
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
```
In kernel/bpf/btf.c (ffffffff81345b18)
Location: include/linux/btf.h:355
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
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
In kernel/bpf/verifier.c (ffffffff813162cd)
Location: include/linux/btf.h:366
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
```
In kernel/bpf/btf.c (ffffffff8136baa8)
Location: include/linux/btf.h:366
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
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
In kernel/bpf/btf.c (ffff800010283e8c)
Location: kernel/bpf/btf.c:390
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
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
In kernel/bpf/btf.c (c04b45a0)
Location: kernel/bpf/btf.c:390
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
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
In kernel/bpf/btf.c (c00000000032e5c4)
Location: kernel/bpf/btf.c:390
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
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
In kernel/bpf/btf.c (ffffffe0001b972c)
Location: kernel/bpf/btf.c:390
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
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
In kernel/bpf/btf.c (ffffffff811f56f6)
Location: kernel/bpf/btf.c:390
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
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
In kernel/bpf/btf.c (ffffffff811e8446)
Location: kernel/bpf/btf.c:390
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
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
In kernel/bpf/btf.c (ffffffff811f34c6)
Location: kernel/bpf/btf.c:390
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
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
In kernel/bpf/btf.c (ffffffff812019d6)
Location: kernel/bpf/btf.c:390
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
</details>
</li>
</ul>

## Differences
