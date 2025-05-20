# Function: <code>sock_hash_alloc_elem</code>

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
In net/core/sock_map.c (ffffffff818f281c)
Location: net/core/sock_map.c:625
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8194495f)
Location: net/core/sock_map.c:629
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
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
In net/core/sock_map.c (ffffffff8197995f)
Location: net/core/sock_map.c:637
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_htab_elem *sock_hash_alloc_elem(struct bpf_htab *htab, void *key, u32 key_size, u32 hash, struct sock *sk, struct bpf_htab_elem *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4db80)
Location: net/core/sock_map.c:815
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
```
**Symbols:**

```
ffffffff81a4db80-ffffffff81a4dc2e: sock_hash_alloc_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_shtab_elem *sock_hash_alloc_elem(struct bpf_shtab *htab, void *key, u32 key_size, u32 hash, struct sock *sk, struct bpf_shtab_elem *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a538e0)
Location: net/core/sock_map.c:955
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
```
**Symbols:**

```
ffffffff81a538e0-ffffffff81a5398e: sock_hash_alloc_elem (STB_LOCAL)
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
In net/core/sock_map.c (ffffffff81a50dec)
Location: net/core/sock_map.c:947
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
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
In net/core/sock_map.c (ffffffff81b09e99)
Location: net/core/sock_map.c:938
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
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
In net/core/sock_map.c (ffffffff81c90112)
Location: net/core/sock_map.c:940
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_shtab_elem *sock_hash_alloc_elem(struct bpf_shtab *htab, void *key, u32 key_size, u32 hash, struct sock *sk, struct bpf_shtab_elem *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81e492a0)
Location: net/core/sock_map.c:942
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
```
**Symbols:**

```
ffffffff81e492a0-ffffffff81e4935d: sock_hash_alloc_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_shtab_elem *sock_hash_alloc_elem(struct bpf_shtab *htab, void *key, u32 key_size, u32 hash, struct sock *sk, struct bpf_shtab_elem *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81ea49c0)
Location: net/core/sock_map.c:947
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
```
**Symbols:**

```
ffffffff81ea49c0-ffffffff81ea4a7d: sock_hash_alloc_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_shtab_elem *sock_hash_alloc_elem(struct bpf_shtab *htab, void *key, u32 key_size, u32 hash, struct sock *sk, struct bpf_shtab_elem *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81f673e0)
Location: net/core/sock_map.c:951
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
```
**Symbols:**

```
ffffffff81f673e0-ffffffff81f6749d: sock_hash_alloc_elem (STB_LOCAL)
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
In net/core/sock_map.c (ffff800010c20e00)
Location: net/core/sock_map.c:637
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
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
In net/core/sock_map.c (c0d386d8)
Location: net/core/sock_map.c:637
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
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
In net/core/sock_map.c (c000000000d12f9c)
Location: net/core/sock_map.c:637
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
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
In net/core/sock_map.c (ffffffe000799bfc)
Location: net/core/sock_map.c:637
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
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
In net/core/sock_map.c (ffffffff819197cf)
Location: net/core/sock_map.c:637
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
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
In net/core/sock_map.c (ffffffff818d357f)
Location: net/core/sock_map.c:637
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
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
In net/core/sock_map.c (ffffffff8196a95f)
Location: net/core/sock_map.c:637
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
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
In net/core/sock_map.c (ffffffff8198cdcf)
Location: net/core/sock_map.c:637
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bpf_htab *htab</code> ➡️ <code>struct bpf_shtab *htab</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct bpf_htab_elem *old</code> ➡️ <code>struct bpf_shtab_elem *old</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct bpf_htab_elem *</code> ➡️ <code>struct bpf_shtab_elem *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
