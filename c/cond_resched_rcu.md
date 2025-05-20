# Function: <code>cond_resched_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811a8a6a)
Location: include/linux/sched.h:2953
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811bf9c0)
Location: include/linux/sched.h:3230
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff8121c8e3)
Location: include/linux/sched.h:3230
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/shmem.c (ffffffff811cff94)
Location: include/linux/sched.h:3390
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff8122e27d)
Location: include/linux/sched.h:3390
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/shmem.c (ffffffff811d96cd)
Location: include/linux/sched.h:1554
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff8123a6e4)
Location: include/linux/sched.h:1554
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/shmem.c (ffffffff811ee989)
Location: include/linux/sched.h:1588
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff8125961f)
Location: include/linux/sched.h:1588
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/shmem.c (ffffffff81213afa)
Location: include/linux/sched.h:1702
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff8127d7ef)
Location: include/linux/sched.h:1702
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memfd.c (ffffffff81294466)
Location: include/linux/sched.h:1702
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
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
In mm/shmem.c (ffffffff81226a87)
Location: include/linux/sched.h:1715
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff8129221f)
Location: include/linux/sched.h:1715
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/shmem.c (ffffffff8123623d)
Location: include/linux/sched.h:1788
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812acc7c)
Location: include/linux/sched.h:1788
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In net/core/bpf_sk_storage.c (ffffffff81952f0b)
Location: include/linux/sched.h:1788
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
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
In mm/shmem.c (ffffffff8124447d)
Location: include/linux/sched.h:1781
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812be53a)
Location: include/linux/sched.h:1781
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In net/core/bpf_sk_storage.c (ffffffff8198935b)
Location: include/linux/sched.h:1781
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
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
In mm/shmem.c (ffffffff8126e396)
Location: include/linux/sched.h:1831
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812f2494)
Location: include/linux/sched.h:1831
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
```
```
In net/core/bpf_sk_storage.c (ffffffff81a60e4b)
Location: include/linux/sched.h:1831
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
```
```
In net/ipv4/fib_trie.c (ffffffff81af1aef)
Location: include/linux/sched.h:1831
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
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
In kernel/bpf/bpf_local_storage.c (ffffffff812302bb)
Location: include/linux/sched.h:1892
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
```
```
In mm/shmem.c (ffffffff8127c598)
Location: include/linux/sched.h:1892
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812fe953)
Location: include/linux/sched.h:1892
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
```
```
In net/ipv4/fib_trie.c (ffffffff81afeb6f)
Location: include/linux/sched.h:1892
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
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
In kernel/bpf/bpf_local_storage.c (ffffffff81225879)
Location: include/linux/sched.h:1947
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
```
```
In mm/shmem.c (ffffffff81281767)
Location: include/linux/sched.h:1947
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff813055cb)
Location: include/linux/sched.h:1947
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
```
```
In net/ipv4/fib_trie.c (ffffffff81aea325)
Location: include/linux/sched.h:1947
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
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
In kernel/bpf/hashtab.c (ffffffff8125479b)
Location: include/linux/sched.h:2064
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8125d889)
Location: include/linux/sched.h:2064
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
```
```
In mm/shmem.c (ffffffff812bcd29)
Location: include/linux/sched.h:2064
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff8134f3ef)
Location: include/linux/sched.h:2064
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
```
```
In net/ipv4/fib_trie.c (ffffffff81bab43b)
Location: include/linux/sched.h:2064
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
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
In kernel/bpf/hashtab.c (0)
Location: include/linux/sched.h:2113
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/sched.h:2113
Inline: True
```
```
In mm/shmem.c (ffffffff81318c62)
Location: include/linux/sched.h:2113
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff813c6086)
Location: include/linux/sched.h:2113
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/sched.h:2113
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
In kernel/bpf/hashtab.c (0)
Location: include/linux/sched.h:2140
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/sched.h:2140
Inline: True
```
```
In mm/shmem.c (ffffffff8138cb22)
Location: include/linux/sched.h:2140
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff8144abf4)
Location: include/linux/sched.h:2140
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/sched.h:2140
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
In kernel/bpf/hashtab.c (0)
Location: include/linux/sched.h:2157
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/sched.h:2157
Inline: True
```
```
In mm/filemap.c (ffffffff8138cc8c)
Location: include/linux/sched.h:2157
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
```
```
In mm/shmem.c (ffffffff813bf1e6)
Location: include/linux/sched.h:2157
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff81480dfb)
Location: include/linux/sched.h:2157
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/sched.h:2157
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
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate_wait.h:59
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/rcupdate_wait.h:59
Inline: True
```
```
In mm/filemap.c (ffffffff813b6799)
Location: include/linux/rcupdate_wait.h:59
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
```
```
In mm/shmem.c (ffffffff813ea236)
Location: include/linux/rcupdate_wait.h:59
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff814aedcf)
Location: include/linux/rcupdate_wait.h:59
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/rcupdate_wait.h:59
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
In mm/shmem.c (ffff8000102d65dc)
Location: include/linux/sched.h:1781
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffff80001035febc)
Location: include/linux/sched.h:1781
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In net/core/bpf_sk_storage.c (ffff800010c319c0)
Location: include/linux/sched.h:1781
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
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
In mm/shmem.c (c04fe85c)
Location: include/linux/sched.h:1781
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In net/core/bpf_sk_storage.c (c0d48360)
Location: include/linux/sched.h:1781
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
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
In mm/shmem.c (c0000000003968b0)
Location: include/linux/sched.h:1781
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (c00000000044afbc)
Location: include/linux/sched.h:1781
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In net/core/bpf_sk_storage.c (c000000000d2a6a0)
Location: include/linux/sched.h:1781
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
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
In mm/shmem.c (ffffffe0001f1dce)
Location: include/linux/sched.h:1781
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a743c)
Location: include/linux/sched.h:1781
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
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
In mm/shmem.c (ffffffff8123cacd)
Location: include/linux/sched.h:1781
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812b6b1a)
Location: include/linux/sched.h:1781
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In net/core/bpf_sk_storage.c (ffffffff819291cb)
Location: include/linux/sched.h:1781
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
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
In mm/shmem.c (ffffffff8122facd)
Location: include/linux/sched.h:1781
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812a7cea)
Location: include/linux/sched.h:1781
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In net/core/bpf_sk_storage.c (ffffffff818e2f7b)
Location: include/linux/sched.h:1781
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
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
In mm/shmem.c (ffffffff8123a86d)
Location: include/linux/sched.h:1781
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812b492a)
Location: include/linux/sched.h:1781
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In net/core/bpf_sk_storage.c (ffffffff8197a35b)
Location: include/linux/sched.h:1781
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
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
In mm/shmem.c (ffffffff81249f67)
Location: include/linux/sched.h:1781
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812c5358)
Location: include/linux/sched.h:1781
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/sched.h:1781
Inline: True
```
</details>
</li>
</ul>

## Differences
