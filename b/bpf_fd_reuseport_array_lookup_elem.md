# Function: <code>bpf_fd_reuseport_array_lookup_elem</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff811e2970)
Location: kernel/bpf/reuseport_array.c:184
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811e2970-ffffffff811e29b3: bpf_fd_reuseport_array_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff811f9af0)
Location: kernel/bpf/reuseport_array.c:181
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811f9af0-ffffffff811f9b38: bpf_fd_reuseport_array_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff81206bc0)
Location: kernel/bpf/reuseport_array.c:181
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff81206bc0-ffffffff81206c08: bpf_fd_reuseport_array_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff8122f190)
Location: kernel/bpf/reuseport_array.c:184
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff8122f190-ffffffff8122f1d8: bpf_fd_reuseport_array_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff812376b0)
Location: kernel/bpf/reuseport_array.c:174
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff812376b0-ffffffff81237707: bpf_fd_reuseport_array_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff8123bed0)
Location: kernel/bpf/reuseport_array.c:174
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff8123bed0-ffffffff8123bf27: bpf_fd_reuseport_array_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff81276860)
Location: kernel/bpf/reuseport_array.c:174
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff81276860-ffffffff812768b7: bpf_fd_reuseport_array_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff812c6330)
Location: kernel/bpf/reuseport_array.c:171
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff812c6330-ffffffff812c639e: bpf_fd_reuseport_array_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff8132bad0)
Location: kernel/bpf/reuseport_array.c:168
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff8132bad0-ffffffff8132bb3e: bpf_fd_reuseport_array_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff8135bc40)
Location: kernel/bpf/reuseport_array.c:165
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff8135bc40-ffffffff8135bcae: bpf_fd_reuseport_array_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff813848d0)
Location: kernel/bpf/reuseport_array.c:165
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff813848d0-ffffffff8138493e: bpf_fd_reuseport_array_lookup_elem (STB_GLOBAL)
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
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffff800010290698)
Location: kernel/bpf/reuseport_array.c:181
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffff800010290698-ffff800010290720: bpf_fd_reuseport_array_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (c04bf9d8)
Location: kernel/bpf/reuseport_array.c:181
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
c04bf9d8-c04bfa44: bpf_fd_reuseport_array_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (c00000000033d250)
Location: kernel/bpf/reuseport_array.c:181
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
c00000000033d250-c00000000033d2f8: bpf_fd_reuseport_array_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffe0001c2f16)
Location: kernel/bpf/reuseport_array.c:181
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffe0001c2f16-ffffffe0001c2f7c: bpf_fd_reuseport_array_lookup_elem (STB_GLOBAL)
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
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff811ff1e0)
Location: kernel/bpf/reuseport_array.c:181
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811ff1e0-ffffffff811ff228: bpf_fd_reuseport_array_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff811f1f30)
Location: kernel/bpf/reuseport_array.c:181
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811f1f30-ffffffff811f1f78: bpf_fd_reuseport_array_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff811fcfb0)
Location: kernel/bpf/reuseport_array.c:181
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811fcfb0-ffffffff811fcff8: bpf_fd_reuseport_array_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff8120bc60)
Location: kernel/bpf/reuseport_array.c:181
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff8120bc60-ffffffff8120bccc: bpf_fd_reuseport_array_lookup_elem (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
