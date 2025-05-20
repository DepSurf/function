# Function: <code>select_bucket</code>

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
In kernel/bpf/hashtab.c (ffffffff8117790e)
Location: kernel/bpf/hashtab.c:123
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81186ad6)
Location: kernel/bpf/hashtab.c:277
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81193870)
Location: kernel/bpf/hashtab.c:369
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8119ad08)
Location: kernel/bpf/hashtab.c:394
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811aa528)
Location: kernel/bpf/hashtab.c:403
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811c1b67)
Location: kernel/bpf/hashtab.c:413
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In kernel/bpf/sockmap.c (ffffffff811d04f1)
Location: kernel/bpf/sockmap.c:282
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:sock_hash_get_next_key
  - kernel/bpf/sockmap.c:sock_hash_get_next_key
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
In kernel/bpf/hashtab.c (ffffffff811d3087)
Location: kernel/bpf/hashtab.c:427
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811e7d69)
Location: kernel/bpf/hashtab.c:415
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff81952985)
Location: net/core/bpf_sk_storage.c:90
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f44c9)
Location: kernel/bpf/hashtab.c:415
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff81988cd5)
Location: net/core/bpf_sk_storage.c:93
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812186b9)
Location: kernel/bpf/hashtab.c:527
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff81a60995)
Location: net/core/bpf_sk_storage.c:94
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81219eb9)
Location: kernel/bpf/hashtab.c:546
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8122fc25)
Location: kernel/bpf/bpf_local_storage.c:18
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121db79)
Location: kernel/bpf/hashtab.c:546
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812251e5)
Location: kernel/bpf/bpf_local_storage.c:18
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812549d9)
Location: kernel/bpf/hashtab.c:576
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8125d175)
Location: kernel/bpf/bpf_local_storage.c:18
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8129d0e9)
Location: kernel/bpf/hashtab.c:592
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free_timers
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812a72d5)
Location: kernel/bpf/bpf_local_storage.c:21
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812f8fd9)
Location: kernel/bpf/hashtab.c:607
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff813059b5)
Location: kernel/bpf/bpf_local_storage.c:21
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81327ab9)
Location: kernel/bpf/hashtab.c:614
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81334695)
Location: kernel/bpf/bpf_local_storage.c:21
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8134c179)
Location: kernel/bpf/hashtab.c:625
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81358da5)
Location: kernel/bpf/bpf_local_storage.c:21
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffff800010277ff8)
Location: kernel/bpf/hashtab.c:415
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In net/core/bpf_sk_storage.c (ffff800010c311c8)
Location: net/core/bpf_sk_storage.c:93
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c04aa758)
Location: kernel/bpf/hashtab.c:415
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In net/core/bpf_sk_storage.c (c0d47db0)
Location: net/core/bpf_sk_storage.c:93
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c0000000003211d0)
Location: kernel/bpf/hashtab.c:415
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In net/core/bpf_sk_storage.c (c000000000d29ea0)
Location: net/core/bpf_sk_storage.c:93
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffe0001b022c)
Location: kernel/bpf/hashtab.c:415
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a6e20)
Location: net/core/bpf_sk_storage.c:93
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811ecae9)
Location: kernel/bpf/hashtab.c:415
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff81928b45)
Location: net/core/bpf_sk_storage.c:93
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811df879)
Location: kernel/bpf/hashtab.c:415
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff818e28f5)
Location: net/core/bpf_sk_storage.c:93
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811ea8b9)
Location: kernel/bpf/hashtab.c:415
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff81979cd5)
Location: net/core/bpf_sk_storage.c:93
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f8c99)
Location: kernel/bpf/hashtab.c:415
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff8199c205)
Location: net/core/bpf_sk_storage.c:93
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
</details>
</li>
</ul>

## Differences
