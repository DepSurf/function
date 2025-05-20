# Function: <code>bpf_for_each_hash_elem</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_for_each_hash_elem(struct bpf_map *map, void *callback_fn, void *callback_ctx, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121c940)
Location: kernel/bpf/hashtab.c:1872
Inline: False
```
**Symbols:**

```
ffffffff8121c940-ffffffff8121ca6f: bpf_for_each_hash_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_for_each_hash_elem(struct bpf_map *map, void *callback_fn, void *callback_ctx, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81253840)
Location: kernel/bpf/hashtab.c:2052
Inline: False
```
**Symbols:**

```
ffffffff81253840-ffffffff8125396f: bpf_for_each_hash_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_for_each_hash_elem(struct bpf_map *map, bpf_callback_t callback_fn, void *callback_ctx, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8129bc20)
Location: kernel/bpf/hashtab.c:2091
Inline: False
```
**Symbols:**

```
ffffffff8129bc20-ffffffff8129bd68: bpf_for_each_hash_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_for_each_hash_elem(struct bpf_map *map, bpf_callback_t callback_fn, void *callback_ctx, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812f8100)
Location: kernel/bpf/hashtab.c:2122
Inline: False
```
**Symbols:**

```
ffffffff812f8100-ffffffff812f8248: bpf_for_each_hash_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int bpf_for_each_hash_elem(struct bpf_map *map, bpf_callback_t callback_fn, void *callback_ctx, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81326140)
Location: kernel/bpf/hashtab.c:2135
Inline: False
```
**Symbols:**

```
ffffffff81326140-ffffffff81326291: bpf_for_each_hash_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int bpf_for_each_hash_elem(struct bpf_map *map, bpf_callback_t callback_fn, void *callback_ctx, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8134a780)
Location: kernel/bpf/hashtab.c:2157
Inline: False
```
**Symbols:**

```
ffffffff8134a780-ffffffff8134a8d1: bpf_for_each_hash_elem (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void *callback_fn</code> ➡️ <code>bpf_callback_t callback_fn</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>long int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
