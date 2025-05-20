# Function: <code>bpf_sk_storage_map_seq_find_next</code>

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
struct bpf_local_storage_elem *bpf_sk_storage_map_seq_find_next(struct bpf_iter_seq_sk_storage_map_info *info, struct bpf_local_storage_elem *prev_selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a692e0)
Location: net/core/bpf_sk_storage.c:730
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_next
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_start
```
**Symbols:**

```
ffffffff81a692e0-ffffffff81a693d4: bpf_sk_storage_map_seq_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_local_storage_elem *bpf_sk_storage_map_seq_find_next(struct bpf_iter_seq_sk_storage_map_info *info, struct bpf_local_storage_elem *prev_selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a51a60)
Location: net/core/bpf_sk_storage.c:730
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_next
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_start
```
**Symbols:**

```
ffffffff81a51a60-ffffffff81a51b63: bpf_sk_storage_map_seq_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct bpf_local_storage_elem *bpf_sk_storage_map_seq_find_next(struct bpf_iter_seq_sk_storage_map_info *info, struct bpf_local_storage_elem *prev_selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (0)
Location: net/core/bpf_sk_storage.c:729
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_next
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_start
```
**Symbols:**

```
ffffffff81b0a6c0-ffffffff81b0a7f2: bpf_sk_storage_map_seq_find_next (STB_LOCAL)
ffffffff81d38bb1-ffffffff81d38bfb: bpf_sk_storage_map_seq_find_next.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct bpf_local_storage_elem *bpf_sk_storage_map_seq_find_next(struct bpf_iter_seq_sk_storage_map_info *info, struct bpf_local_storage_elem *prev_selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (0)
Location: net/core/bpf_sk_storage.c:740
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_next
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_start
```
**Symbols:**

```
ffffffff81c90c00-ffffffff81c90d54: bpf_sk_storage_map_seq_find_next (STB_LOCAL)
ffffffff81f0540b-ffffffff81f0544f: bpf_sk_storage_map_seq_find_next.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct bpf_local_storage_elem *bpf_sk_storage_map_seq_find_next(struct bpf_iter_seq_sk_storage_map_info *info, struct bpf_local_storage_elem *prev_selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (0)
Location: net/core/bpf_sk_storage.c:710
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_next
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_start
```
**Symbols:**

```
ffffffff81e4bfc0-ffffffff81e4c114: bpf_sk_storage_map_seq_find_next (STB_LOCAL)
ffffffff820ad418-ffffffff820ad45c: bpf_sk_storage_map_seq_find_next.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct bpf_local_storage_elem *bpf_sk_storage_map_seq_find_next(struct bpf_iter_seq_sk_storage_map_info *info, struct bpf_local_storage_elem *prev_selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (0)
Location: net/core/bpf_sk_storage.c:708
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_next
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_start
```
**Symbols:**

```
ffffffff81ea76c0-ffffffff81ea781b: bpf_sk_storage_map_seq_find_next (STB_LOCAL)
ffffffff8212e5ab-ffffffff8212e5db: bpf_sk_storage_map_seq_find_next.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct bpf_local_storage_elem *bpf_sk_storage_map_seq_find_next(struct bpf_iter_seq_sk_storage_map_info *info, struct bpf_local_storage_elem *prev_selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (0)
Location: net/core/bpf_sk_storage.c:709
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_next
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_seq_start
```
**Symbols:**

```
ffffffff81f6a170-ffffffff81f6a2cb: bpf_sk_storage_map_seq_find_next (STB_LOCAL)
ffffffff8221035e-ffffffff8221038e: bpf_sk_storage_map_seq_find_next.cold (STB_LOCAL)
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
