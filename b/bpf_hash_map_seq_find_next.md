# Function: <code>bpf_hash_map_seq_find_next</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
struct htab_elem *bpf_hash_map_seq_find_next(struct bpf_iter_seq_hash_map_info *info, struct htab_elem *prev_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81218f30)
Location: kernel/bpf/hashtab.c:1698
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_next
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_start
```
**Symbols:**

```
ffffffff81218f30-ffffffff81218ff2: bpf_hash_map_seq_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct htab_elem *bpf_hash_map_seq_find_next(struct bpf_iter_seq_hash_map_info *info, struct htab_elem *prev_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121c810)
Location: kernel/bpf/hashtab.c:1698
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_next
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_start
```
**Symbols:**

```
ffffffff8121c810-ffffffff8121c8c3: bpf_hash_map_seq_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct htab_elem *bpf_hash_map_seq_find_next(struct bpf_iter_seq_hash_map_info *info, struct htab_elem *prev_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81253710)
Location: kernel/bpf/hashtab.c:1878
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_next
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_start
```
**Symbols:**

```
ffffffff81253710-ffffffff812537c3: bpf_hash_map_seq_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct htab_elem *bpf_hash_map_seq_find_next(struct bpf_iter_seq_hash_map_info *info, struct htab_elem *prev_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8129bae0)
Location: kernel/bpf/hashtab.c:1915
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_next
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_start
```
**Symbols:**

```
ffffffff8129bae0-ffffffff8129bba3: bpf_hash_map_seq_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct htab_elem *bpf_hash_map_seq_find_next(struct bpf_iter_seq_hash_map_info *info, struct htab_elem *prev_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812f7f90)
Location: kernel/bpf/hashtab.c:1946
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_next
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_start
```
**Symbols:**

```
ffffffff812f7f90-ffffffff812f8053: bpf_hash_map_seq_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct htab_elem *bpf_hash_map_seq_find_next(struct bpf_iter_seq_hash_map_info *info, struct htab_elem *prev_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81325fb0)
Location: kernel/bpf/hashtab.c:1959
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_next
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_start
```
**Symbols:**

```
ffffffff81325fb0-ffffffff81326092: bpf_hash_map_seq_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct htab_elem *bpf_hash_map_seq_find_next(struct bpf_iter_seq_hash_map_info *info, struct htab_elem *prev_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8134a5f0)
Location: kernel/bpf/hashtab.c:1981
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_next
  - kernel/bpf/hashtab.c:bpf_hash_map_seq_start
```
**Symbols:**

```
ffffffff8134a5f0-ffffffff8134a6d2: bpf_hash_map_seq_find_next (STB_LOCAL)
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
