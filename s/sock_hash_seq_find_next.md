# Function: <code>sock_hash_seq_find_next</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *sock_hash_seq_find_next(struct sock_hash_seq_info *info, struct bpf_shtab_elem *prev_elem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a5440d)
Location: net/core/sock_map.c:1311
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_seq_start
Direct callers:
  - net/core/sock_map.c:sock_hash_seq_next
```
**Symbols:**

```
ffffffff81a53580-ffffffff81a535e6: sock_hash_seq_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *sock_hash_seq_find_next(struct sock_hash_seq_info *info, struct bpf_shtab_elem *prev_elem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4ff2a)
Location: net/core/sock_map.c:1294
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_seq_start
Direct callers:
  - net/core/sock_map.c:sock_hash_seq_next
```
**Symbols:**

```
ffffffff81a4f190-ffffffff81a4f1f6: sock_hash_seq_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *sock_hash_seq_find_next(struct sock_hash_seq_info *info, struct bpf_shtab_elem *prev_elem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81b08b0a)
Location: net/core/sock_map.c:1285
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_seq_start
Direct callers:
  - net/core/sock_map.c:sock_hash_seq_next
```
**Symbols:**

```
ffffffff81b07d70-ffffffff81b07dd6: sock_hash_seq_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void *sock_hash_seq_find_next(struct sock_hash_seq_info *info, struct bpf_shtab_elem *prev_elem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81c8eb20)
Location: net/core/sock_map.c:1287
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_seq_start
Direct callers:
  - net/core/sock_map.c:sock_hash_seq_next
```
**Symbols:**

```
ffffffff81c8db60-ffffffff81c8dbde: sock_hash_seq_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *sock_hash_seq_find_next(struct sock_hash_seq_info *info, struct bpf_shtab_elem *prev_elem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81e49c80)
Location: net/core/sock_map.c:1289
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_seq_start
Direct callers:
  - net/core/sock_map.c:sock_hash_seq_next
```
**Symbols:**

```
ffffffff81e48a40-ffffffff81e48abe: sock_hash_seq_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *sock_hash_seq_find_next(struct sock_hash_seq_info *info, struct bpf_shtab_elem *prev_elem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81ea5340)
Location: net/core/sock_map.c:1292
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_seq_start
Direct callers:
  - net/core/sock_map.c:sock_hash_seq_next
```
**Symbols:**

```
ffffffff81ea4110-ffffffff81ea419d: sock_hash_seq_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *sock_hash_seq_find_next(struct sock_hash_seq_info *info, struct bpf_shtab_elem *prev_elem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81f67b80)
Location: net/core/sock_map.c:1298
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_seq_start
Direct callers:
  - net/core/sock_map.c:sock_hash_seq_next
```
**Symbols:**

```
ffffffff81f66a10-ffffffff81f66a9d: sock_hash_seq_find_next (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
