# Function: <code>bpf_map_flags_access_ok</code>

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
In kernel/bpf/hashtab.c (ffffffff811e71d9)
Location: include/linux/bpf.h:467
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff811e98c5)
Location: include/linux/bpf.h:467
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/lpm_trie.c (ffffffff811ec1f2)
Location: include/linux/bpf.h:467
Inline: True
```
```
In kernel/bpf/local_storage.c (ffffffff811ec89a)
Location: include/linux/bpf.h:467
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff811ed8ca)
Location: include/linux/bpf.h:467
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc_check
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
In kernel/bpf/hashtab.c (ffffffff811f3939)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff811f6025)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/lpm_trie.c (ffffffff811f8952)
Location: include/linux/bpf.h:470
Inline: True
```
```
In kernel/bpf/local_storage.c (ffffffff811f8fea)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff811f9fda)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc_check
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
In kernel/bpf/hashtab.c (ffffffff81217139)
Location: include/linux/bpf.h:859
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff812196e7)
Location: include/linux/bpf.h:859
Inline: True
```
```
In kernel/bpf/lpm_trie.c (ffffffff8121c117)
Location: include/linux/bpf.h:859
Inline: True
```
```
In kernel/bpf/local_storage.c (ffffffff8121cdea)
Location: include/linux/bpf.h:859
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff8121de4a)
Location: include/linux/bpf.h:859
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc_check
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
In kernel/bpf/hashtab.c (ffffffff81219409)
Location: include/linux/bpf.h:1014
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff8121c037)
Location: include/linux/bpf.h:1014
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/lpm_trie.c (ffffffff8121f067)
Location: include/linux/bpf.h:1014
Inline: True
```
```
In kernel/bpf/local_storage.c (ffffffff8121fc12)
Location: include/linux/bpf.h:1014
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff81220bea)
Location: include/linux/bpf.h:1014
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc_check
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
In kernel/bpf/hashtab.c (ffffffff8121ce09)
Location: include/linux/bpf.h:1041
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff8121fa37)
Location: include/linux/bpf.h:1041
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/lpm_trie.c (ffffffff81222af7)
Location: include/linux/bpf.h:1041
Inline: True
```
```
In kernel/bpf/local_storage.c (ffffffff81223699)
Location: include/linux/bpf.h:1041
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff8122467a)
Location: include/linux/bpf.h:1041
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc_check
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
In kernel/bpf/hashtab.c (ffffffff81253dd9)
Location: include/linux/bpf.h:1078
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff81257227)
Location: include/linux/bpf.h:1078
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/lpm_trie.c (ffffffff8125a8a7)
Location: include/linux/bpf.h:1078
Inline: True
```
```
In kernel/bpf/local_storage.c (ffffffff8125b4c8)
Location: include/linux/bpf.h:1078
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff8125c5ba)
Location: include/linux/bpf.h:1078
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc_check
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
In kernel/bpf/hashtab.c (ffffffff8129c2c9)
Location: include/linux/bpf.h:1261
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff8129fc4b)
Location: include/linux/bpf.h:1261
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/lpm_trie.c (ffffffff812a39d3)
Location: include/linux/bpf.h:1261
Inline: True
```
```
In kernel/bpf/bloom_filter.c (ffffffff812a4910)
Location: include/linux/bpf.h:1261
Inline: True
Inline callers:
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
```
```
In kernel/bpf/local_storage.c (ffffffff812a4f5c)
Location: include/linux/bpf.h:1261
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff812a629a)
Location: include/linux/bpf.h:1261
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc_check
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
In kernel/bpf/hashtab.c (ffffffff812f8509)
Location: include/linux/bpf.h:1573
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff812fcc09)
Location: include/linux/bpf.h:1573
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/lpm_trie.c (ffffffff813015c3)
Location: include/linux/bpf.h:1573
Inline: True
```
```
In kernel/bpf/bloom_filter.c (ffffffff81302650)
Location: include/linux/bpf.h:1573
Inline: True
Inline callers:
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
```
```
In kernel/bpf/local_storage.c (ffffffff81302cd9)
Location: include/linux/bpf.h:1573
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff8130403a)
Location: include/linux/bpf.h:1573
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc_check
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
In kernel/bpf/hashtab.c (ffffffff8132654f)
Location: include/linux/bpf.h:1700
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff8132b839)
Location: include/linux/bpf.h:1700
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/lpm_trie.c (ffffffff8133012d)
Location: include/linux/bpf.h:1700
Inline: True
```
```
In kernel/bpf/bloom_filter.c (ffffffff813313fd)
Location: include/linux/bpf.h:1700
Inline: True
Inline callers:
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
```
```
In kernel/bpf/local_storage.c (ffffffff81331775)
Location: include/linux/bpf.h:1700
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff81332828)
Location: include/linux/bpf.h:1700
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc_check
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
In kernel/bpf/hashtab.c (ffffffff8134ab8f)
Location: include/linux/bpf.h:1825
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff8134fd09)
Location: include/linux/bpf.h:1825
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/lpm_trie.c (ffffffff8135464d)
Location: include/linux/bpf.h:1825
Inline: True
```
```
In kernel/bpf/bloom_filter.c (ffffffff8135599d)
Location: include/linux/bpf.h:1825
Inline: True
Inline callers:
  - kernel/bpf/bloom_filter.c:bloom_map_alloc
```
```
In kernel/bpf/local_storage.c (ffffffff81355d15)
Location: include/linux/bpf.h:1825
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff81356df8)
Location: include/linux/bpf.h:1825
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc_check
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
In kernel/bpf/hashtab.c (ffff800010277ccc)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffff80001027a6c8)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/lpm_trie.c (ffff80001027d8f4)
Location: include/linux/bpf.h:470
Inline: True
```
```
In kernel/bpf/local_storage.c (ffff80001027e624)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffff80001027f858)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc_check
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
In kernel/bpf/hashtab.c (c04aa0f0)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (c04ac754)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/lpm_trie.c (c04af5c0)
Location: include/linux/bpf.h:470
Inline: True
```
```
In kernel/bpf/local_storage.c (c04b0078)
Location: include/linux/bpf.h:470
Inline: True
```
```
In kernel/bpf/queue_stack_maps.c (c04b0d70)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc_check
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
In kernel/bpf/hashtab.c (c00000000032006c)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (c0000000003237e0)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/lpm_trie.c (c000000000327aec)
Location: include/linux/bpf.h:470
Inline: True
```
```
In kernel/bpf/local_storage.c (c0000000003284e0)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (c000000000329e30)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc_check
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
In kernel/bpf/hashtab.c (ffffffe0001af892)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffe0001b23e0)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/lpm_trie.c (ffffffe0001b50d4)
Location: include/linux/bpf.h:470
Inline: True
```
```
In kernel/bpf/local_storage.c (ffffffe0001b5ac4)
Location: include/linux/bpf.h:470
Inline: True
```
```
In kernel/bpf/queue_stack_maps.c (ffffffe0001b65c0)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc_check
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
In kernel/bpf/hashtab.c (ffffffff811ebf59)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff811ee645)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/lpm_trie.c (ffffffff811f0f72)
Location: include/linux/bpf.h:470
Inline: True
```
```
In kernel/bpf/local_storage.c (ffffffff811f160a)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff811f25fa)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc_check
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
In kernel/bpf/hashtab.c (ffffffff811dece9)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff811e13d5)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/lpm_trie.c (ffffffff811e3cc2)
Location: include/linux/bpf.h:470
Inline: True
```
```
In kernel/bpf/local_storage.c (ffffffff811e435a)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff811e534a)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc_check
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
In kernel/bpf/hashtab.c (ffffffff811e9d29)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff811ec415)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/lpm_trie.c (ffffffff811eed42)
Location: include/linux/bpf.h:470
Inline: True
```
```
In kernel/bpf/local_storage.c (ffffffff811ef3da)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff811f03ca)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc_check
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
In kernel/bpf/hashtab.c (ffffffff811f80f9)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc_check
```
```
In kernel/bpf/arraymap.c (ffffffff811fa885)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc_check
```
```
In kernel/bpf/lpm_trie.c (ffffffff811fd212)
Location: include/linux/bpf.h:470
Inline: True
```
```
In kernel/bpf/local_storage.c (ffffffff811fd8aa)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
```
```
In kernel/bpf/queue_stack_maps.c (ffffffff811fe8da)
Location: include/linux/bpf.h:470
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc_check
```
</details>
</li>
</ul>

## Differences
