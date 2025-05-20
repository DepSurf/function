# Function: <code>cgroup_storage_type</code>

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
In kernel/bpf/helpers.c (ffffffff811d1fd5)
Location: include/linux/bpf-cgroup.h:112
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_local_storage
```
```
In kernel/bpf/local_storage.c (ffffffff811d8732)
Location: include/linux/bpf-cgroup.h:112
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
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
In kernel/bpf/helpers.c (ffffffff811e62f5)
Location: include/linux/bpf-cgroup.h:135
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_local_storage
```
```
In kernel/bpf/local_storage.c (ffffffff811ed202)
Location: include/linux/bpf-cgroup.h:135
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
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
In kernel/bpf/helpers.c (ffffffff811f2a45)
Location: include/linux/bpf-cgroup.h:135
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_local_storage
```
```
In kernel/bpf/local_storage.c (ffffffff811f9952)
Location: include/linux/bpf-cgroup.h:135
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
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
In kernel/bpf/helpers.c (ffffffff812148d5)
Location: include/linux/bpf-cgroup.h:146
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_local_storage
```
```
In kernel/bpf/local_storage.c (ffffffff8121d7d2)
Location: include/linux/bpf-cgroup.h:146
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
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
In kernel/bpf/helpers.c (ffffffff812163b5)
Location: include/linux/bpf-cgroup.h:150
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_local_storage
```
```
In kernel/bpf/local_storage.c (ffffffff812204e2)
Location: include/linux/bpf-cgroup.h:150
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
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
In kernel/bpf/helpers.c (ffffffff81219155)
Location: include/linux/bpf-cgroup.h:166
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_local_storage
```
```
In kernel/bpf/local_storage.c (ffffffff81223f72)
Location: include/linux/bpf-cgroup.h:166
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
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
In kernel/bpf/helpers.c (ffffffff8124f7a5)
Location: include/linux/bpf-cgroup.h:217
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_local_storage
```
```
In kernel/bpf/local_storage.c (ffffffff8125be73)
Location: include/linux/bpf-cgroup.h:217
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
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
In kernel/bpf/helpers.c (ffffffff81296935)
Location: include/linux/bpf-cgroup.h:144
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_local_storage
```
```
In kernel/bpf/local_storage.c (ffffffff812a59a3)
Location: include/linux/bpf-cgroup.h:144
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
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
In kernel/bpf/local_storage.c (ffffffff8130393b)
Location: include/linux/bpf-cgroup.h:151
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
```
```
In kernel/bpf/cgroup.c (ffffffff81325d05)
Location: include/linux/bpf-cgroup.h:151
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:bpf_get_local_storage
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
In kernel/bpf/local_storage.c (ffffffff8133236b)
Location: include/linux/bpf-cgroup.h:151
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
```
```
In kernel/bpf/cgroup.c (ffffffff81355ed5)
Location: include/linux/bpf-cgroup.h:151
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:bpf_get_local_storage
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
In kernel/bpf/local_storage.c (ffffffff8135691b)
Location: include/linux/bpf-cgroup.h:158
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
```
```
In kernel/bpf/cgroup.c (ffffffff8137ea05)
Location: include/linux/bpf-cgroup.h:158
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:bpf_get_local_storage
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
In kernel/bpf/helpers.c (ffff80001027690c)
Location: include/linux/bpf-cgroup.h:135
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_local_storage
```
```
In kernel/bpf/local_storage.c (ffff80001027f32c)
Location: include/linux/bpf-cgroup.h:135
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
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
In kernel/bpf/helpers.c (c04a8a00)
Location: include/linux/bpf-cgroup.h:135
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_local_storage
```
```
In kernel/bpf/local_storage.c (c04b0728)
Location: include/linux/bpf-cgroup.h:135
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
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
In kernel/bpf/helpers.c (c00000000031e8d0)
Location: include/linux/bpf-cgroup.h:135
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_local_storage
```
```
In kernel/bpf/local_storage.c (c0000000003294f8)
Location: include/linux/bpf-cgroup.h:135
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
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
In kernel/bpf/helpers.c (ffffffe0001ae946)
Location: include/linux/bpf-cgroup.h:135
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_local_storage
```
```
In kernel/bpf/local_storage.c (ffffffe0001b6014)
Location: include/linux/bpf-cgroup.h:135
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
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
In kernel/bpf/helpers.c (ffffffff811eb065)
Location: include/linux/bpf-cgroup.h:135
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_local_storage
```
```
In kernel/bpf/local_storage.c (ffffffff811f1f72)
Location: include/linux/bpf-cgroup.h:135
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
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
In kernel/bpf/helpers.c (ffffffff811dde15)
Location: include/linux/bpf-cgroup.h:135
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_local_storage
```
```
In kernel/bpf/local_storage.c (ffffffff811e4cc2)
Location: include/linux/bpf-cgroup.h:135
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
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
In kernel/bpf/helpers.c (ffffffff811e8e35)
Location: include/linux/bpf-cgroup.h:135
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_local_storage
```
```
In kernel/bpf/local_storage.c (ffffffff811efd42)
Location: include/linux/bpf-cgroup.h:135
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
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
In kernel/bpf/helpers.c (ffffffff811f71e5)
Location: include/linux/bpf-cgroup.h:135
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_local_storage
```
```
In kernel/bpf/local_storage.c (ffffffff811fe252)
Location: include/linux/bpf-cgroup.h:135
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
```
</details>
</li>
</ul>

## Differences
