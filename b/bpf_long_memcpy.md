# Function: <code>bpf_long_memcpy</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8118748c)
Location: include/linux/bpf.h:265
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/arraymap.c (ffffffff81187cf2)
Location: include/linux/bpf.h:265
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
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
In kernel/bpf/hashtab.c (ffffffff8119542d)
Location: include/linux/bpf.h:280
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
```
```
In kernel/bpf/arraymap.c (ffffffff81195ca9)
Location: include/linux/bpf.h:280
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
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
In kernel/bpf/hashtab.c (ffffffff8119c6d8)
Location: include/linux/bpf.h:309
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
```
```
In kernel/bpf/arraymap.c (ffffffff8119d1e5)
Location: include/linux/bpf.h:309
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
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
In kernel/bpf/hashtab.c (ffffffff811ac01d)
Location: include/linux/bpf.h:400
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
```
```
In kernel/bpf/arraymap.c (ffffffff811acd88)
Location: include/linux/bpf.h:400
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
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
In kernel/bpf/hashtab.c (ffffffff811c3488)
Location: include/linux/bpf.h:475
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
```
```
In kernel/bpf/arraymap.c (ffffffff811c437e)
Location: include/linux/bpf.h:475
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
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
In kernel/bpf/hashtab.c (ffffffff811d4f18)
Location: include/linux/bpf.h:547
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
```
```
In kernel/bpf/arraymap.c (ffffffff811d5f1e)
Location: include/linux/bpf.h:547
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/local_storage.c (ffffffff811d8487)
Location: include/linux/bpf.h:547
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
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
In kernel/bpf/hashtab.c (ffffffff811e96f8)
Location: include/linux/bpf.h:696
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
```
```
In kernel/bpf/arraymap.c (ffffffff811ea8ca)
Location: include/linux/bpf.h:696
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/local_storage.c (ffffffff811ecf2c)
Location: include/linux/bpf.h:696
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
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
In kernel/bpf/hashtab.c (ffffffff811f5e58)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
```
```
In kernel/bpf/arraymap.c (ffffffff811f702a)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/local_storage.c (ffffffff811f967c)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
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
In kernel/bpf/hashtab.c (ffffffff812194d2)
Location: include/linux/bpf.h:1225
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
```
```
In kernel/bpf/arraymap.c (ffffffff8121acbb)
Location: include/linux/bpf.h:1225
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/local_storage.c (ffffffff8121d507)
Location: include/linux/bpf.h:1225
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
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
In kernel/bpf/hashtab.c (ffffffff8121bdf2)
Location: include/linux/bpf.h:1408
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
```
```
In kernel/bpf/arraymap.c (ffffffff8121c5d3)
Location: include/linux/bpf.h:1408
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/local_storage.c (ffffffff81220417)
Location: include/linux/bpf.h:1408
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
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
In kernel/bpf/hashtab.c (ffffffff8121f7f2)
Location: include/linux/bpf.h:1472
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
```
```
In kernel/bpf/arraymap.c (ffffffff8121fff6)
Location: include/linux/bpf.h:1472
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/local_storage.c (ffffffff81223ead)
Location: include/linux/bpf.h:1472
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
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
In kernel/bpf/hashtab.c (ffffffff81256fc7)
Location: include/linux/bpf.h:1561
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
```
```
In kernel/bpf/arraymap.c (ffffffff8125763c)
Location: include/linux/bpf.h:1561
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/local_storage.c (ffffffff8125bd76)
Location: include/linux/bpf.h:1561
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
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
In kernel/bpf/hashtab.c (ffffffff8129f957)
Location: include/linux/bpf.h:1683
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
```
```
In kernel/bpf/arraymap.c (ffffffff812a0220)
Location: include/linux/bpf.h:1683
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/local_storage.c (ffffffff812a5880)
Location: include/linux/bpf.h:1683
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
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
In kernel/bpf/syscall.c (0)
Location: include/linux/bpf.h:367
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/bpf.h:367
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff812fc8dd)
Location: include/linux/bpf.h:367
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
```
```
In kernel/bpf/arraymap.c (ffffffff812fd8b9)
Location: include/linux/bpf.h:367
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:bpf_obj_memcpy
```
```
In kernel/bpf/local_storage.c (ffffffff813037ee)
Location: include/linux/bpf.h:367
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/bpf.h:367
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/bpf.h:367
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
In kernel/bpf/syscall.c (0)
Location: include/linux/bpf.h:421
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/bpf.h:421
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff81326721)
Location: include/linux/bpf.h:421
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_obj_memcpy
```
```
In kernel/bpf/arraymap.c (ffffffff8132c561)
Location: include/linux/bpf.h:421
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:bpf_obj_memcpy
```
```
In kernel/bpf/local_storage.c (ffffffff8133221e)
Location: include/linux/bpf.h:421
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/bpf.h:421
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/bpf.h:421
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
In kernel/bpf/syscall.c (0)
Location: include/linux/bpf.h:452
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/bpf.h:452
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff8134ad61)
Location: include/linux/bpf.h:452
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_obj_memcpy
```
```
In kernel/bpf/arraymap.c (ffffffff81350aa1)
Location: include/linux/bpf.h:452
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:bpf_obj_memcpy
```
```
In kernel/bpf/local_storage.c (ffffffff813567ce)
Location: include/linux/bpf.h:452
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/bpf.h:452
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/bpf.h:452
Inline: True
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
In kernel/bpf/hashtab.c (ffff80001027a314)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
```
```
In kernel/bpf/arraymap.c (ffff80001027bb28)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/local_storage.c (ffff80001027ef1c)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
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
In kernel/bpf/hashtab.c (c04ac534)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
```
```
In kernel/bpf/arraymap.c (c04ad9e8)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/local_storage.c (c04b0440)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
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
In kernel/bpf/hashtab.c (c0000000003234d8)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
```
```
In kernel/bpf/arraymap.c (c000000000325198)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/local_storage.c (c00000000032904c)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
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
In kernel/bpf/hashtab.c (ffffffe0001b21aa)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
```
```
In kernel/bpf/arraymap.c (ffffffe0001b3626)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/local_storage.c (ffffffe0001b5d4e)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
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
In kernel/bpf/hashtab.c (ffffffff811ee478)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
```
```
In kernel/bpf/arraymap.c (ffffffff811ef64a)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/local_storage.c (ffffffff811f1c9c)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
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
In kernel/bpf/hashtab.c (ffffffff811e1208)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
```
```
In kernel/bpf/arraymap.c (ffffffff811e23da)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/local_storage.c (ffffffff811e49ec)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
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
In kernel/bpf/hashtab.c (ffffffff811ec248)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
```
```
In kernel/bpf/arraymap.c (ffffffff811ed41a)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/local_storage.c (ffffffff811efa6c)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
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
In kernel/bpf/hashtab.c (ffffffff811fa656)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
```
```
In kernel/bpf/arraymap.c (ffffffff811fb8c6)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/local_storage.c (ffffffff811fdf7a)
Location: include/linux/bpf.h:701
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
```
</details>
</li>
</ul>

## Differences
