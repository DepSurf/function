# Function: <code>copy_map_value</code>

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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d4cf7)
Location: include/linux/bpf.h:119
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/helpers.c (ffffffff811e67b6)
Location: include/linux/bpf.h:119
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff811e7621)
Location: include/linux/bpf.h:119
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (ffffffff811e9ff7)
Location: include/linux/bpf.h:119
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
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
In kernel/bpf/syscall.c (ffffffff811e1411)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/helpers.c (ffffffff811f2f06)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff811f3d81)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (ffffffff811f6757)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff81989d18)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
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
In kernel/bpf/syscall.c (ffffffff811ff270)
Location: include/linux/bpf.h:153
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/helpers.c (ffffffff81214ec6)
Location: include/linux/bpf.h:153
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff81218a94)
Location: include/linux/bpf.h:153
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (ffffffff81219d47)
Location: include/linux/bpf.h:153
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff81a6133d)
Location: include/linux/bpf.h:153
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
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
In kernel/bpf/syscall.c (ffffffff811fe5ff)
Location: include/linux/bpf.h:195
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/helpers.c (ffffffff81216ab6)
Location: include/linux/bpf.h:195
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff8121adaf)
Location: include/linux/bpf.h:195
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (ffffffff8121c988)
Location: include/linux/bpf.h:195
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff81a69c2d)
Location: include/linux/bpf.h:195
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
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
In kernel/bpf/syscall.c (ffffffff811ff08f)
Location: include/linux/bpf.h:206
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/helpers.c (ffffffff812197f6)
Location: include/linux/bpf.h:206
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff8121ea4d)
Location: include/linux/bpf.h:206
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (ffffffff812204a8)
Location: include/linux/bpf.h:206
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff81a5269d)
Location: include/linux/bpf.h:206
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate ⚠️</summary>

```c
void copy_map_value(struct bpf_map *map, void *dst, void *src);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8122cea0)
Location: include/linux/bpf.h:215
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/helpers.c (ffffffff8124fae0)
Location: include/linux/bpf.h:215
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff81253ac0)
Location: include/linux/bpf.h:215
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (ffffffff81257a90)
Location: include/linux/bpf.h:215
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0a5a0)
Location: include/linux/bpf.h:215
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff8122cea0-ffffffff8122cfb2: copy_map_value (STB_LOCAL)
ffffffff8124fae0-ffffffff8124fbf2: copy_map_value (STB_LOCAL)
ffffffff81253ac0-ffffffff81253bd2: copy_map_value (STB_LOCAL)
ffffffff81257a90-ffffffff81257ba2: copy_map_value (STB_LOCAL)
ffffffff81b0a5a0-ffffffff81b0a6b2: copy_map_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate ⚠️</summary>

```c
void copy_map_value(struct bpf_map *map, void *dst, void *src);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8126f320)
Location: include/linux/bpf.h:277
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/helpers.c (ffffffff81296f30)
Location: include/linux/bpf.h:277
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff8129bfa0)
Location: include/linux/bpf.h:277
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (ffffffff812a0700)
Location: include/linux/bpf.h:277
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff81c90b00)
Location: include/linux/bpf.h:277
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff8126f320-ffffffff8126f420: copy_map_value (STB_LOCAL)
ffffffff81296f30-ffffffff81297030: copy_map_value (STB_LOCAL)
ffffffff8129bfa0-ffffffff8129c0a0: copy_map_value (STB_LOCAL)
ffffffff812a0700-ffffffff812a0800: copy_map_value (STB_LOCAL)
ffffffff81c90b00-ffffffff81c90c00: copy_map_value (STB_LOCAL)
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
In kernel/bpf/syscall.c (ffffffff812cb032)
Location: include/linux/bpf.h:403
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/helpers.c (ffffffff812f2c4d)
Location: include/linux/bpf.h:403
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff812fc15f)
Location: include/linux/bpf.h:403
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (ffffffff812fda10)
Location: include/linux/bpf.h:403
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff813057f8)
Location: include/linux/bpf.h:403
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_alloc
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4cd43)
Location: include/linux/bpf.h:403
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
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
In kernel/bpf/syscall.c (ffffffff812f2a10)
Location: include/linux/bpf.h:457
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/helpers.c (ffffffff8131f98d)
Location: include/linux/bpf.h:457
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff8132a9e0)
Location: include/linux/bpf.h:457
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (ffffffff8132c610)
Location: include/linux/bpf.h:457
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff813341b4)
Location: include/linux/bpf.h:457
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_alloc
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea8462)
Location: include/linux/bpf.h:457
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
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
In kernel/bpf/syscall.c (ffffffff81311889)
Location: include/linux/bpf.h:488
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/helpers.c (ffffffff81341e7d)
Location: include/linux/bpf.h:488
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff8134ee16)
Location: include/linux/bpf.h:488
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (ffffffff81350b50)
Location: include/linux/bpf.h:488
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff813588a4)
Location: include/linux/bpf.h:488
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_alloc
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6af22)
Location: include/linux/bpf.h:488
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
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
In kernel/bpf/syscall.c (ffff800010264090)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/helpers.c (ffff800010276a1c)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffff8000102783c8)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (ffff80001027af00)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In net/core/bpf_sk_storage.c (ffff800010c323a4)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
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
In kernel/bpf/syscall.c (c0496684)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/helpers.c (c04a9010)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (c04aa5c0)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (c04acf60)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In net/core/bpf_sk_storage.c (c0d48df8)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
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
In kernel/bpf/syscall.c (c000000000308f6c)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/helpers.c (c00000000031efb4)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (c000000000320730)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (c000000000324404)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In net/core/bpf_sk_storage.c (c000000000d2b730)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
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
In kernel/bpf/syscall.c (ffffffe0001a01ee)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/helpers.c (ffffffe0001aed8a)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffe0001afc1a)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (ffffffe0001b2bcc)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a7d0e)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
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
In kernel/bpf/syscall.c (ffffffff811d9a31)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/helpers.c (ffffffff811eb526)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff811ec3a1)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (ffffffff811eed77)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff81929b88)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
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
In kernel/bpf/syscall.c (ffffffff811cc7f1)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/helpers.c (ffffffff811de2c9)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff811df131)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (ffffffff811e1b07)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff818e3938)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
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
In kernel/bpf/syscall.c (ffffffff811d7801)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/helpers.c (ffffffff811e92f6)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff811ea171)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (ffffffff811ecb47)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff8197ad18)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
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
In kernel/bpf/syscall.c (ffffffff811e5bc4)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/helpers.c (ffffffff811f76ad)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff811f8551)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (ffffffff811fafe7)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff8199d27d)
Location: include/linux/bpf.h:122
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
