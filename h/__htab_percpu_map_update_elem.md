# Function: <code>__htab_percpu_map_update_elem</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81186670)
Location: kernel/bpf/hashtab.c:574
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_percpu_map_update_elem
```
**Symbols:**

```
ffffffff81186670-ffffffff811869ed: __htab_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81194540)
Location: kernel/bpf/hashtab.c:778
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_percpu_map_update_elem
```
**Symbols:**

```
ffffffff81194540-ffffffff81194809: __htab_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8119b460)
Location: kernel/bpf/hashtab.c:873
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_percpu_map_update_elem
```
**Symbols:**

```
ffffffff8119b460-ffffffff8119b71c: __htab_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811aaca0)
Location: kernel/bpf/hashtab.c:906
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_percpu_map_update_elem
```
**Symbols:**

```
ffffffff811aaca0-ffffffff811aaf65: __htab_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811c22c0)
Location: kernel/bpf/hashtab.c:926
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_percpu_map_update_elem
```
**Symbols:**

```
ffffffff811c22c0-ffffffff811c257f: __htab_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811d3a90)
Location: kernel/bpf/hashtab.c:940
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_percpu_map_update_elem
```
**Symbols:**

```
ffffffff811d3a90-ffffffff811d3dd0: __htab_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811e8790)
Location: kernel/bpf/hashtab.c:975
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_percpu_map_update_elem
```
**Symbols:**

```
ffffffff811e8790-ffffffff811e8a5f: __htab_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f4ef0)
Location: kernel/bpf/hashtab.c:975
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_percpu_map_update_elem
```
**Symbols:**

```
ffffffff811f4ef0-ffffffff811f51bf: __htab_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81218060)
Location: kernel/bpf/hashtab.c:1083
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_percpu_map_update_elem
```
**Symbols:**

```
ffffffff81218060-ffffffff812181a8: __htab_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121a830)
Location: kernel/bpf/hashtab.c:1135
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_percpu_map_update_elem
```
**Symbols:**

```
ffffffff8121a830-ffffffff8121a9ec: __htab_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121e230)
Location: kernel/bpf/hashtab.c:1135
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_percpu_map_update_elem
```
**Symbols:**

```
ffffffff8121e230-ffffffff8121e3ec: __htab_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81256d20)
Location: kernel/bpf/hashtab.c:1188
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_percpu_map_update_elem
```
**Symbols:**

```
ffffffff81256d20-ffffffff81256edc: __htab_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8129f6a0)
Location: kernel/bpf/hashtab.c:1207
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_percpu_map_update_elem
```
**Symbols:**

```
ffffffff8129f6a0-ffffffff8129f844: __htab_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812fa2e0)
Location: kernel/bpf/hashtab.c:1229
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_percpu_map_update_elem
```
**Symbols:**

```
ffffffff812fa2e0-ffffffff812fa4d2: __htab_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __htab_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81328910)
Location: kernel/bpf/hashtab.c:1242
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_percpu_map_update_elem
```
**Symbols:**

```
ffffffff81328910-ffffffff81328b6f: __htab_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __htab_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8134d740)
Location: kernel/bpf/hashtab.c:1261
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_percpu_map_update_elem
```
**Symbols:**

```
ffffffff8134d740-ffffffff8134d942: __htab_percpu_map_update_elem (STB_LOCAL)
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
int __htab_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffff800010279208)
Location: kernel/bpf/hashtab.c:975
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_percpu_map_update_elem
```
**Symbols:**

```
ffff800010279208-ffff800010279580: __htab_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c04ab640)
Location: kernel/bpf/hashtab.c:975
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_percpu_map_update_elem
```
**Symbols:**

```
c04ab640-c04ab92c: __htab_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c000000000322080)
Location: kernel/bpf/hashtab.c:975
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_percpu_map_update_elem
```
**Symbols:**

```
c000000000322080-c000000000322474: __htab_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffe0001b12f2)
Location: kernel/bpf/hashtab.c:975
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_percpu_map_update_elem
```
**Symbols:**

```
ffffffe0001b12f2-ffffffe0001b1602: __htab_percpu_map_update_elem (STB_LOCAL)
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
int __htab_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811ed510)
Location: kernel/bpf/hashtab.c:975
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_percpu_map_update_elem
```
**Symbols:**

```
ffffffff811ed510-ffffffff811ed7df: __htab_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811e02a0)
Location: kernel/bpf/hashtab.c:975
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_percpu_map_update_elem
```
**Symbols:**

```
ffffffff811e02a0-ffffffff811e056f: __htab_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811eb2e0)
Location: kernel/bpf/hashtab.c:975
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_percpu_map_update_elem
```
**Symbols:**

```
ffffffff811eb2e0-ffffffff811eb5af: __htab_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f96e0)
Location: kernel/bpf/hashtab.c:975
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_update
  - kernel/bpf/hashtab.c:htab_percpu_map_update_elem
```
**Symbols:**

```
ffffffff811f96e0-ffffffff811f99af: __htab_percpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
