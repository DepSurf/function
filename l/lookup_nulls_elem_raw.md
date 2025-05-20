# Function: <code>lookup_nulls_elem_raw</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct htab_elem *lookup_nulls_elem_raw(struct hlist_nulls_head *head, u32 hash, void *key, u32 key_size, u32 n_buckets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8119a400)
Location: kernel/bpf/hashtab.c:417
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
**Symbols:**

```
ffffffff8119a400-ffffffff8119a477: lookup_nulls_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct htab_elem *lookup_nulls_elem_raw(struct hlist_nulls_head *head, u32 hash, void *key, u32 key_size, u32 n_buckets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811a9c10)
Location: kernel/bpf/hashtab.c:426
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
**Symbols:**

```
ffffffff811a9c10-ffffffff811a9c87: lookup_nulls_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct htab_elem *lookup_nulls_elem_raw(struct hlist_nulls_head *head, u32 hash, void *key, u32 key_size, u32 n_buckets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811c10c0)
Location: kernel/bpf/hashtab.c:436
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
**Symbols:**

```
ffffffff811c10c0-ffffffff811c113c: lookup_nulls_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct htab_elem *lookup_nulls_elem_raw(struct hlist_nulls_head *head, u32 hash, void *key, u32 key_size, u32 n_buckets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811d2620)
Location: kernel/bpf/hashtab.c:450
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
**Symbols:**

```
ffffffff811d2620-ffffffff811d269c: lookup_nulls_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct htab_elem *lookup_nulls_elem_raw(struct hlist_nulls_head *head, u32 hash, void *key, u32 key_size, u32 n_buckets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811e6d90)
Location: kernel/bpf/hashtab.c:438
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
**Symbols:**

```
ffffffff811e6d90-ffffffff811e6e10: lookup_nulls_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct htab_elem *lookup_nulls_elem_raw(struct hlist_nulls_head *head, u32 hash, void *key, u32 key_size, u32 n_buckets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f34f0)
Location: kernel/bpf/hashtab.c:438
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
**Symbols:**

```
ffffffff811f34f0-ffffffff811f3570: lookup_nulls_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct htab_elem *lookup_nulls_elem_raw(struct hlist_nulls_head *head, u32 hash, void *key, u32 key_size, u32 n_buckets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81216d20)
Location: kernel/bpf/hashtab.c:550
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffff81216d20-ffffffff81216d9c: lookup_nulls_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct htab_elem *lookup_nulls_elem_raw(struct hlist_nulls_head *head, u32 hash, void *key, u32 key_size, u32 n_buckets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812190e0)
Location: kernel/bpf/hashtab.c:569
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffff812190e0-ffffffff8121915c: lookup_nulls_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct htab_elem *lookup_nulls_elem_raw(struct hlist_nulls_head *head, u32 hash, void *key, u32 key_size, u32 n_buckets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121cae0)
Location: kernel/bpf/hashtab.c:569
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffff8121cae0-ffffffff8121cb5c: lookup_nulls_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct htab_elem *lookup_nulls_elem_raw(struct hlist_nulls_head *head, u32 hash, void *key, u32 key_size, u32 n_buckets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812539e0)
Location: kernel/bpf/hashtab.c:599
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffff812539e0-ffffffff81253a5c: lookup_nulls_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct htab_elem *lookup_nulls_elem_raw(struct hlist_nulls_head *head, u32 hash, void *key, u32 key_size, u32 n_buckets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8129bdf0)
Location: kernel/bpf/hashtab.c:615
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffff8129bdf0-ffffffff8129be77: lookup_nulls_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct htab_elem *lookup_nulls_elem_raw(struct hlist_nulls_head *head, u32 hash, void *key, u32 key_size, u32 n_buckets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812f82f0)
Location: kernel/bpf/hashtab.c:630
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffff812f82f0-ffffffff812f8377: lookup_nulls_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct htab_elem *lookup_nulls_elem_raw(struct hlist_nulls_head *head, u32 hash, void *key, u32 key_size, u32 n_buckets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81326340)
Location: kernel/bpf/hashtab.c:637
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffff81326340-ffffffff813263c7: lookup_nulls_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct htab_elem *lookup_nulls_elem_raw(struct hlist_nulls_head *head, u32 hash, void *key, u32 key_size, u32 n_buckets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8134a980)
Location: kernel/bpf/hashtab.c:648
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffff8134a980-ffffffff8134aa07: lookup_nulls_elem_raw (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct htab_elem *lookup_nulls_elem_raw(struct hlist_nulls_head *head, u32 hash, void *key, u32 key_size, u32 n_buckets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffff800010277318)
Location: kernel/bpf/hashtab.c:438
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
**Symbols:**

```
ffff800010277318-ffff8000102773c8: lookup_nulls_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct htab_elem *lookup_nulls_elem_raw(struct hlist_nulls_head *head, u32 hash, void *key, u32 key_size, u32 n_buckets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c04a9c5c)
Location: kernel/bpf/hashtab.c:438
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
**Symbols:**

```
c04a9c5c-c04a9cf0: lookup_nulls_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct htab_elem *lookup_nulls_elem_raw(struct hlist_nulls_head *head, u32 hash, void *key, u32 key_size, u32 n_buckets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c00000000031f830)
Location: kernel/bpf/hashtab.c:438
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
**Symbols:**

```
c00000000031f830-c00000000031f94c: lookup_nulls_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct htab_elem *lookup_nulls_elem_raw(struct hlist_nulls_head *head, u32 hash, void *key, u32 key_size, u32 n_buckets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffe0001af5d4)
Location: kernel/bpf/hashtab.c:438
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
**Symbols:**

```
ffffffe0001af5d4-ffffffe0001af662: lookup_nulls_elem_raw (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct htab_elem *lookup_nulls_elem_raw(struct hlist_nulls_head *head, u32 hash, void *key, u32 key_size, u32 n_buckets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811ebb10)
Location: kernel/bpf/hashtab.c:438
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
**Symbols:**

```
ffffffff811ebb10-ffffffff811ebb90: lookup_nulls_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct htab_elem *lookup_nulls_elem_raw(struct hlist_nulls_head *head, u32 hash, void *key, u32 key_size, u32 n_buckets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811de8a0)
Location: kernel/bpf/hashtab.c:438
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
**Symbols:**

```
ffffffff811de8a0-ffffffff811de920: lookup_nulls_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct htab_elem *lookup_nulls_elem_raw(struct hlist_nulls_head *head, u32 hash, void *key, u32 key_size, u32 n_buckets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811e98e0)
Location: kernel/bpf/hashtab.c:438
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
**Symbols:**

```
ffffffff811e98e0-ffffffff811e9960: lookup_nulls_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct htab_elem *lookup_nulls_elem_raw(struct hlist_nulls_head *head, u32 hash, void *key, u32 key_size, u32 n_buckets);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f7cb0)
Location: kernel/bpf/hashtab.c:438
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_get_next_key
  - kernel/bpf/hashtab.c:__htab_map_lookup_elem
```
**Symbols:**

```
ffffffff811f7cb0-ffffffff811f7d30: lookup_nulls_elem_raw (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
