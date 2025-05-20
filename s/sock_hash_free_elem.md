# Function: <code>sock_hash_free_elem</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818f343e)
Location: net/core/sock_map.c:570
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sock_hash_free_elem(struct bpf_htab *htab, struct bpf_htab_elem *elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81943cc0)
Location: net/core/sock_map.c:574
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
**Symbols:**

```
ffffffff81943cc0-ffffffff81943ce2: sock_hash_free_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sock_hash_free_elem(struct bpf_htab *htab, struct bpf_htab_elem *elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81978cb0)
Location: net/core/sock_map.c:582
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
**Symbols:**

```
ffffffff81978cb0-ffffffff81978cd2: sock_hash_free_elem (STB_LOCAL)
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
In net/core/sock_map.c (ffffffff81a4ea77)
Location: net/core/sock_map.c:760
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
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
In net/core/sock_map.c (ffffffff81a54a57)
Location: net/core/sock_map.c:900
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
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
In net/core/sock_map.c (ffffffff81a50677)
Location: net/core/sock_map.c:892
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
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
In net/core/sock_map.c (ffffffff81b09205)
Location: net/core/sock_map.c:883
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
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
In net/core/sock_map.c (ffffffff81c8f295)
Location: net/core/sock_map.c:885
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_hash_delete_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81e4a4f5)
Location: net/core/sock_map.c:887
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_hash_delete_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81ea5c05)
Location: net/core/sock_map.c:892
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_hash_delete_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81f686c5)
Location: net/core/sock_map.c:896
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_hash_delete_elem
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
void sock_hash_free_elem(struct bpf_htab *htab, struct bpf_htab_elem *elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffff800010c1fbb8)
Location: net/core/sock_map.c:582
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
**Symbols:**

```
ffff800010c1fbb8-ffff800010c1fc18: sock_hash_free_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sock_hash_free_elem(struct bpf_htab *htab, struct bpf_htab_elem *elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c0d37460)
Location: net/core/sock_map.c:582
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
**Symbols:**

```
c0d37460-c0d374ac: sock_hash_free_elem (STB_LOCAL)
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
In net/core/sock_map.c (c000000000d143bc)
Location: net/core/sock_map.c:582
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
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
In net/core/sock_map.c (ffffffe00079aaee)
Location: net/core/sock_map.c:582
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
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
void sock_hash_free_elem(struct bpf_htab *htab, struct bpf_htab_elem *elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81918b20)
Location: net/core/sock_map.c:582
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
**Symbols:**

```
ffffffff81918b20-ffffffff81918b42: sock_hash_free_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sock_hash_free_elem(struct bpf_htab *htab, struct bpf_htab_elem *elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818d28d0)
Location: net/core/sock_map.c:582
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
**Symbols:**

```
ffffffff818d28d0-ffffffff818d28f2: sock_hash_free_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sock_hash_free_elem(struct bpf_htab *htab, struct bpf_htab_elem *elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81969cb0)
Location: net/core/sock_map.c:582
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
**Symbols:**

```
ffffffff81969cb0-ffffffff81969cd2: sock_hash_free_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sock_hash_free_elem(struct bpf_htab *htab, struct bpf_htab_elem *elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8198c0d0)
Location: net/core/sock_map.c:582
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
**Symbols:**

```
ffffffff8198c0d0-ffffffff8198c0f2: sock_hash_free_elem (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
