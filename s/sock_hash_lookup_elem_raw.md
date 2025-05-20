# Function: <code>sock_hash_lookup_elem_raw</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
struct bpf_htab_elem *sock_hash_lookup_elem_raw(struct hlist_head *head, u32 hash, void *key, u32 key_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818f17c0)
Location: net/core/sock_map.c:540
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
**Symbols:**

```
ffffffff818f17c0-ffffffff818f1833: sock_hash_lookup_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bpf_htab_elem *sock_hash_lookup_elem_raw(struct hlist_head *head, u32 hash, void *key, u32 key_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81943c40)
Location: net/core/sock_map.c:544
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
**Symbols:**

```
ffffffff81943c40-ffffffff81943cb7: sock_hash_lookup_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bpf_htab_elem *sock_hash_lookup_elem_raw(struct hlist_head *head, u32 hash, void *key, u32 key_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81978c30)
Location: net/core/sock_map.c:552
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
**Symbols:**

```
ffffffff81978c30-ffffffff81978ca7: sock_hash_lookup_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4de00)
Location: net/core/sock_map.c:730
Inline: True
Direct callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
**Symbols:**

```
ffffffff81a4de00-ffffffff81a4de62: sock_hash_lookup_elem_raw.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (ffffffff81a53df0)
Location: net/core/sock_map.c:870
Inline: True
Direct callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
**Symbols:**

```
ffffffff81a53df0-ffffffff81a53e52: sock_hash_lookup_elem_raw.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4f900)
Location: net/core/sock_map.c:862
Inline: True
Direct callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
**Symbols:**

```
ffffffff81a4f900-ffffffff81a4f962: sock_hash_lookup_elem_raw.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bpf_shtab_elem *sock_hash_lookup_elem_raw(struct hlist_head *head, u32 hash, void *key, u32 key_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81b08070)
Location: net/core/sock_map.c:853
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
**Symbols:**

```
ffffffff81b08070-ffffffff81b080cf: sock_hash_lookup_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_shtab_elem *sock_hash_lookup_elem_raw(struct hlist_head *head, u32 hash, void *key, u32 key_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81c8de90)
Location: net/core/sock_map.c:855
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
**Symbols:**

```
ffffffff81c8de90-ffffffff81c8defa: sock_hash_lookup_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_shtab_elem *sock_hash_lookup_elem_raw(struct hlist_head *head, u32 hash, void *key, u32 key_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81e48de0)
Location: net/core/sock_map.c:857
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
**Symbols:**

```
ffffffff81e48de0-ffffffff81e48e4a: sock_hash_lookup_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_shtab_elem *sock_hash_lookup_elem_raw(struct hlist_head *head, u32 hash, void *key, u32 key_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81ea4500)
Location: net/core/sock_map.c:862
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
**Symbols:**

```
ffffffff81ea4500-ffffffff81ea456a: sock_hash_lookup_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_shtab_elem *sock_hash_lookup_elem_raw(struct hlist_head *head, u32 hash, void *key, u32 key_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81f66f20)
Location: net/core/sock_map.c:866
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
**Symbols:**

```
ffffffff81f66f20-ffffffff81f66f8a: sock_hash_lookup_elem_raw (STB_LOCAL)
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
struct bpf_htab_elem *sock_hash_lookup_elem_raw(struct hlist_head *head, u32 hash, void *key, u32 key_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffff800010c1f7f8)
Location: net/core/sock_map.c:552
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
**Symbols:**

```
ffff800010c1f7f8-ffff800010c1f88c: sock_hash_lookup_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bpf_htab_elem *sock_hash_lookup_elem_raw(struct hlist_head *head, u32 hash, void *key, u32 key_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c0d373e4)
Location: net/core/sock_map.c:552
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
**Symbols:**

```
c0d373e4-c0d37460: sock_hash_lookup_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bpf_htab_elem *sock_hash_lookup_elem_raw(struct hlist_head *head, u32 hash, void *key, u32 key_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c000000000d11880)
Location: net/core/sock_map.c:552
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
**Symbols:**

```
c000000000d11880-c000000000d11968: sock_hash_lookup_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bpf_htab_elem *sock_hash_lookup_elem_raw(struct hlist_head *head, u32 hash, void *key, u32 key_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffe000799148)
Location: net/core/sock_map.c:552
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
**Symbols:**

```
ffffffe000799148-ffffffe0007991b2: sock_hash_lookup_elem_raw (STB_LOCAL)
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
struct bpf_htab_elem *sock_hash_lookup_elem_raw(struct hlist_head *head, u32 hash, void *key, u32 key_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81918aa0)
Location: net/core/sock_map.c:552
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
**Symbols:**

```
ffffffff81918aa0-ffffffff81918b17: sock_hash_lookup_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bpf_htab_elem *sock_hash_lookup_elem_raw(struct hlist_head *head, u32 hash, void *key, u32 key_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818d2850)
Location: net/core/sock_map.c:552
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
**Symbols:**

```
ffffffff818d2850-ffffffff818d28c7: sock_hash_lookup_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bpf_htab_elem *sock_hash_lookup_elem_raw(struct hlist_head *head, u32 hash, void *key, u32 key_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81969c30)
Location: net/core/sock_map.c:552
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
**Symbols:**

```
ffffffff81969c30-ffffffff81969ca7: sock_hash_lookup_elem_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bpf_htab_elem *sock_hash_lookup_elem_raw(struct hlist_head *head, u32 hash, void *key, u32 key_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8198c050)
Location: net/core/sock_map.c:552
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_get_next_key
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:__sock_hash_lookup_elem
```
**Symbols:**

```
ffffffff8198c050-ffffffff8198c0c7: sock_hash_lookup_elem_raw (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
