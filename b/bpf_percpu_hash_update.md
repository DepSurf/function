# Function: <code>bpf_percpu_hash_update</code>

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
int bpf_percpu_hash_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81187530)
Location: kernel/bpf/hashtab.c:775
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff81187530-ffffffff81187546: bpf_percpu_hash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bpf_percpu_hash_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811954e0)
Location: kernel/bpf/hashtab.c:1100
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811954e0-ffffffff81195508: bpf_percpu_hash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bpf_percpu_hash_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8119c780)
Location: kernel/bpf/hashtab.c:1186
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
**Symbols:**

```
ffffffff8119c780-ffffffff8119c7a8: bpf_percpu_hash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bpf_percpu_hash_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811ac0c0)
Location: kernel/bpf/hashtab.c:1220
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
**Symbols:**

```
ffffffff811ac0c0-ffffffff811ac0e8: bpf_percpu_hash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bpf_percpu_hash_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811c34f0)
Location: kernel/bpf/hashtab.c:1242
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811c34f0-ffffffff811c3518: bpf_percpu_hash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_percpu_hash_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811d4f80)
Location: kernel/bpf/hashtab.c:1279
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811d4f80-ffffffff811d4fa8: bpf_percpu_hash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_percpu_hash_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811e9750)
Location: kernel/bpf/hashtab.c:1315
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811e9750-ffffffff811e9778: bpf_percpu_hash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_percpu_hash_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f5eb0)
Location: kernel/bpf/hashtab.c:1315
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811f5eb0-ffffffff811f5ed8: bpf_percpu_hash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_percpu_hash_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81219520)
Location: kernel/bpf/hashtab.c:1705
Inline: False
```
**Symbols:**

```
ffffffff81219520-ffffffff81219548: bpf_percpu_hash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_percpu_hash_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121be50)
Location: kernel/bpf/hashtab.c:1964
Inline: False
```
**Symbols:**

```
ffffffff8121be50-ffffffff8121be98: bpf_percpu_hash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_percpu_hash_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121f850)
Location: kernel/bpf/hashtab.c:2025
Inline: False
```
**Symbols:**

```
ffffffff8121f850-ffffffff8121f898: bpf_percpu_hash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_percpu_hash_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81257040)
Location: kernel/bpf/hashtab.c:2209
Inline: False
```
**Symbols:**

```
ffffffff81257040-ffffffff81257088: bpf_percpu_hash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_percpu_hash_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8129f9f0)
Location: kernel/bpf/hashtab.c:2274
Inline: False
```
**Symbols:**

```
ffffffff8129f9f0-ffffffff8129fa7a: bpf_percpu_hash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_percpu_hash_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812fc980)
Location: kernel/bpf/hashtab.c:2305
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_update_value
```
**Symbols:**

```
ffffffff812fc980-ffffffff812fca0a: bpf_percpu_hash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_percpu_hash_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8132b5b0)
Location: kernel/bpf/hashtab.c:2358
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_update_value
```
**Symbols:**

```
ffffffff8132b5b0-ffffffff8132b63a: bpf_percpu_hash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_percpu_hash_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8134fa70)
Location: kernel/bpf/hashtab.c:2380
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_update_value
```
**Symbols:**

```
ffffffff8134fa70-ffffffff8134fafa: bpf_percpu_hash_update (STB_GLOBAL)
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
int bpf_percpu_hash_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffff80001027a380)
Location: kernel/bpf/hashtab.c:1315
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffff80001027a380-ffff80001027a3f4: bpf_percpu_hash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_percpu_hash_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c04ac56c)
Location: kernel/bpf/hashtab.c:1315
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
c04ac56c-c04ac5bc: bpf_percpu_hash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_percpu_hash_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c000000000323570)
Location: kernel/bpf/hashtab.c:1315
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
c000000000323570-c0000000003235d4: bpf_percpu_hash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_percpu_hash_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffe0001b2252)
Location: kernel/bpf/hashtab.c:1315
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffe0001b2252-ffffffe0001b22c0: bpf_percpu_hash_update (STB_GLOBAL)
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
int bpf_percpu_hash_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811ee4d0)
Location: kernel/bpf/hashtab.c:1315
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811ee4d0-ffffffff811ee4f8: bpf_percpu_hash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_percpu_hash_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811e1260)
Location: kernel/bpf/hashtab.c:1315
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811e1260-ffffffff811e1288: bpf_percpu_hash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_percpu_hash_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811ec2a0)
Location: kernel/bpf/hashtab.c:1315
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811ec2a0-ffffffff811ec2c8: bpf_percpu_hash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_percpu_hash_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811fa6b0)
Location: kernel/bpf/hashtab.c:1315
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811fa6b0-ffffffff811fa715: bpf_percpu_hash_update (STB_GLOBAL)
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
