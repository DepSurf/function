# Function: <code>__htab_lru_percpu_map_update_elem</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __htab_lru_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81194b00)
Location: kernel/bpf/hashtab.c:831
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_update_elem
```
**Symbols:**

```
ffffffff81194b00-ffffffff81194e63: __htab_lru_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __htab_lru_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8119ba10)
Location: kernel/bpf/hashtab.c:926
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_update_elem
```
**Symbols:**

```
ffffffff8119ba10-ffffffff8119bd59: __htab_lru_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __htab_lru_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811ab270)
Location: kernel/bpf/hashtab.c:959
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_update_elem
```
**Symbols:**

```
ffffffff811ab270-ffffffff811ab5cb: __htab_lru_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __htab_lru_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811c2b00)
Location: kernel/bpf/hashtab.c:979
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_update_elem
```
**Symbols:**

```
ffffffff811c2b00-ffffffff811c2ea3: __htab_lru_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __htab_lru_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811d4140)
Location: kernel/bpf/hashtab.c:993
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_update_elem
```
**Symbols:**

```
ffffffff811d4140-ffffffff811d4557: __htab_lru_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __htab_lru_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811e8a80)
Location: kernel/bpf/hashtab.c:1028
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_update_elem
```
**Symbols:**

```
ffffffff811e8a80-ffffffff811e8ea6: __htab_lru_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __htab_lru_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f51e0)
Location: kernel/bpf/hashtab.c:1028
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_update_elem
```
**Symbols:**

```
ffffffff811f51e0-ffffffff811f5606: __htab_lru_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __htab_lru_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81217af0)
Location: kernel/bpf/hashtab.c:1135
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_update_elem
```
**Symbols:**

```
ffffffff81217af0-ffffffff81217d85: __htab_lru_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __htab_lru_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121b360)
Location: kernel/bpf/hashtab.c:1189
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_update_elem
```
**Symbols:**

```
ffffffff8121b360-ffffffff8121b5df: __htab_lru_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __htab_lru_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121e410)
Location: kernel/bpf/hashtab.c:1189
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_update_elem
```
**Symbols:**

```
ffffffff8121e410-ffffffff8121e679: __htab_lru_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __htab_lru_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81255820)
Location: kernel/bpf/hashtab.c:1243
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_update_elem
```
**Symbols:**

```
ffffffff81255820-ffffffff81255a89: __htab_lru_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __htab_lru_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8129d580)
Location: kernel/bpf/hashtab.c:1262
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_update_elem
```
**Symbols:**

```
ffffffff8129d580-ffffffff8129d7b1: __htab_lru_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __htab_lru_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812fa530)
Location: kernel/bpf/hashtab.c:1284
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_update_elem
```
**Symbols:**

```
ffffffff812fa530-ffffffff812fa786: __htab_lru_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __htab_lru_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81328bc0)
Location: kernel/bpf/hashtab.c:1297
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_update_elem
```
**Symbols:**

```
ffffffff81328bc0-ffffffff81328e88: __htab_lru_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __htab_lru_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8134d9a0)
Location: kernel/bpf/hashtab.c:1316
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_update_elem
```
**Symbols:**

```
ffffffff8134d9a0-ffffffff8134dc4d: __htab_lru_percpu_map_update_elem (STB_LOCAL)
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
int __htab_lru_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffff8000102795d0)
Location: kernel/bpf/hashtab.c:1028
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_update_elem
```
**Symbols:**

```
ffff8000102795d0-ffff8000102799c0: __htab_lru_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __htab_lru_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c04ab960)
Location: kernel/bpf/hashtab.c:1028
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_update_elem
```
**Symbols:**

```
c04ab960-c04abd30: __htab_lru_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __htab_lru_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c0000000003224a0)
Location: kernel/bpf/hashtab.c:1028
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_update_elem
```
**Symbols:**

```
c0000000003224a0-c0000000003229e8: __htab_lru_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __htab_lru_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffe0001b1646)
Location: kernel/bpf/hashtab.c:1028
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_update_elem
```
**Symbols:**

```
ffffffe0001b1646-ffffffe0001b1a82: __htab_lru_percpu_map_update_elem (STB_LOCAL)
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
int __htab_lru_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811ed800)
Location: kernel/bpf/hashtab.c:1028
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_update_elem
```
**Symbols:**

```
ffffffff811ed800-ffffffff811edc26: __htab_lru_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __htab_lru_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811e0590)
Location: kernel/bpf/hashtab.c:1028
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_update_elem
```
**Symbols:**

```
ffffffff811e0590-ffffffff811e09b6: __htab_lru_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __htab_lru_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811eb5d0)
Location: kernel/bpf/hashtab.c:1028
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_update_elem
```
**Symbols:**

```
ffffffff811eb5d0-ffffffff811eb9f6: __htab_lru_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __htab_lru_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f99d0)
Location: kernel/bpf/hashtab.c:1028
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_update_elem
```
**Symbols:**

```
ffffffff811f99d0-ffffffff811f9df6: __htab_lru_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
