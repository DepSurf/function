# Function: <code>array_map_lookup_elem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *array_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81177fd0)
Location: kernel/bpf/arraymap.c:65
Inline: False
```
**Symbols:**

```
ffffffff81177fd0-ffffffff81177fef: array_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *array_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81187690)
Location: kernel/bpf/arraymap.c:110
Inline: False
```
**Symbols:**

```
ffffffff81187690-ffffffff811876af: array_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *array_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81195650)
Location: kernel/bpf/arraymap.c:105
Inline: False
```
**Symbols:**

```
ffffffff81195650-ffffffff8119566f: array_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void *array_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8119c9f5)
Location: kernel/bpf/arraymap.c:109
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_lookup_elem
  - kernel/bpf/arraymap.c:bpf_fd_array_map_lookup_elem
```
**Symbols:**

```
ffffffff8119c9d0-ffffffff8119c9ef: array_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void *array_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ac375)
Location: kernel/bpf/arraymap.c:147
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_lookup_elem
  - kernel/bpf/arraymap.c:bpf_fd_array_map_lookup_elem
```
**Symbols:**

```
ffffffff811ac340-ffffffff811ac36b: array_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void *array_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811c38b5)
Location: kernel/bpf/arraymap.c:152
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_lookup_elem
  - kernel/bpf/arraymap.c:bpf_fd_array_map_lookup_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
```
**Symbols:**

```
ffffffff811c3690-ffffffff811c36bb: array_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void *array_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811d5395)
Location: kernel/bpf/arraymap.c:152
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_lookup_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_fd_array_map_lookup_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
```
**Symbols:**

```
ffffffff811d5120-ffffffff811d514b: array_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void *array_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811e9b85)
Location: kernel/bpf/arraymap.c:143
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_lookup_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_fd_array_map_lookup_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
```
**Symbols:**

```
ffffffff811e9b50-ffffffff811e9b7b: array_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *array_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811f62e5)
Location: kernel/bpf/arraymap.c:143
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_lookup_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_fd_array_map_lookup_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
```
**Symbols:**

```
ffffffff811f62b0-ffffffff811f62db: array_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *array_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81219865)
Location: kernel/bpf/arraymap.c:169
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_lookup_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_fd_array_map_lookup_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
```
**Symbols:**

```
ffffffff81219830-ffffffff8121985b: array_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *array_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8121c2b5)
Location: kernel/bpf/arraymap.c:159
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_lookup_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_fd_array_map_lookup_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
```
**Symbols:**

```
ffffffff8121c280-ffffffff8121c2ab: array_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *array_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8121fcb5)
Location: kernel/bpf/arraymap.c:159
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_lookup_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_fd_array_map_lookup_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
```
**Symbols:**

```
ffffffff8121fc80-ffffffff8121fcab: array_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *array_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff812574a5)
Location: kernel/bpf/arraymap.c:159
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_lookup_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_fd_array_map_lookup_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
```
**Symbols:**

```
ffffffff81257470-ffffffff8125749b: array_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void *array_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8129ffc5)
Location: kernel/bpf/arraymap.c:165
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_lookup_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_fd_array_map_lookup_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
```
**Symbols:**

```
ffffffff8129ff70-ffffffff8129ffb2: array_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *array_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff812fd025)
Location: kernel/bpf/arraymap.c:163
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_lookup_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_fd_array_map_lookup_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
```
**Symbols:**

```
ffffffff812fcfc0-ffffffff812fd002: array_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *array_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8132bc55)
Location: kernel/bpf/arraymap.c:163
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_lookup_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_fd_array_map_lookup_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
```
**Symbols:**

```
ffffffff8132bbf0-ffffffff8132bc32: array_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *array_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81350125)
Location: kernel/bpf/arraymap.c:163
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_lookup_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_fd_array_map_lookup_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
```
**Symbols:**

```
ffffffff813500c0-ffffffff81350102: array_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void *array_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffff80001027a9ac)
Location: kernel/bpf/arraymap.c:143
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_lookup_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_fd_array_map_lookup_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
```
**Symbols:**

```
ffff80001027a930-ffff80001027a98c: array_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *array_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (c04ac998)
Location: kernel/bpf/arraymap.c:143
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_lookup_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_fd_array_map_lookup_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
```
**Symbols:**

```
c04ac948-c04ac984: array_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void *array_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (c000000000323c78)
Location: kernel/bpf/arraymap.c:143
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_lookup_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_fd_array_map_lookup_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
```
**Symbols:**

```
c000000000323c20-c000000000323c68: array_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void *array_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffe0001b2762)
Location: kernel/bpf/arraymap.c:143
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_lookup_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_fd_array_map_lookup_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
```
**Symbols:**

```
ffffffe0001b26f2-ffffffe0001b2748: array_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void *array_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ee905)
Location: kernel/bpf/arraymap.c:143
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_lookup_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_fd_array_map_lookup_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
```
**Symbols:**

```
ffffffff811ee8d0-ffffffff811ee8fb: array_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *array_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811e1695)
Location: kernel/bpf/arraymap.c:143
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_lookup_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_fd_array_map_lookup_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
```
**Symbols:**

```
ffffffff811e1660-ffffffff811e168b: array_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *array_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ec6d5)
Location: kernel/bpf/arraymap.c:143
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_lookup_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_fd_array_map_lookup_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
```
**Symbols:**

```
ffffffff811ec6a0-ffffffff811ec6cb: array_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *array_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811faac5)
Location: kernel/bpf/arraymap.c:143
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_lookup_elem
  - kernel/bpf/arraymap.c:prog_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:bpf_fd_array_map_lookup_elem
  - kernel/bpf/arraymap.c:array_map_seq_show_elem
```
**Symbols:**

```
ffffffff811faa90-ffffffff811faabb: array_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
