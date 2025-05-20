# Function: <code>bpf_fd_reuseport_array_update_elem</code>

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
int bpf_fd_reuseport_array_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff811e29c0)
Location: kernel/bpf/reuseport_array.c:251
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811e29c0-ffffffff811e2b6a: bpf_fd_reuseport_array_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff811f9b40)
Location: kernel/bpf/reuseport_array.c:248
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811f9b40-ffffffff811f9cf7: bpf_fd_reuseport_array_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff81206c10)
Location: kernel/bpf/reuseport_array.c:248
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff81206c10-ffffffff81206dc7: bpf_fd_reuseport_array_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff8122f1e0)
Location: kernel/bpf/reuseport_array.c:251
Inline: False
```
**Symbols:**

```
ffffffff8122f1e0-ffffffff8122f3aa: bpf_fd_reuseport_array_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff81237710)
Location: kernel/bpf/reuseport_array.c:241
Inline: False
```
**Symbols:**

```
ffffffff81237710-ffffffff812378da: bpf_fd_reuseport_array_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff8123bf30)
Location: kernel/bpf/reuseport_array.c:241
Inline: False
```
**Symbols:**

```
ffffffff8123bf30-ffffffff8123c0fb: bpf_fd_reuseport_array_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff812768c0)
Location: kernel/bpf/reuseport_array.c:241
Inline: False
```
**Symbols:**

```
ffffffff812768c0-ffffffff81276a8b: bpf_fd_reuseport_array_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff812c63a0)
Location: kernel/bpf/reuseport_array.c:238
Inline: False
```
**Symbols:**

```
ffffffff812c63a0-ffffffff812c6570: bpf_fd_reuseport_array_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff8132bb50)
Location: kernel/bpf/reuseport_array.c:235
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_update_value
```
**Symbols:**

```
ffffffff8132bb50-ffffffff8132bd20: bpf_fd_reuseport_array_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff8135bcc0)
Location: kernel/bpf/reuseport_array.c:232
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_update_value
```
**Symbols:**

```
ffffffff8135bcc0-ffffffff8135be90: bpf_fd_reuseport_array_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff81384950)
Location: kernel/bpf/reuseport_array.c:232
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_update_value
```
**Symbols:**

```
ffffffff81384950-ffffffff81384b20: bpf_fd_reuseport_array_update_elem (STB_GLOBAL)
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
int bpf_fd_reuseport_array_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffff800010290720)
Location: kernel/bpf/reuseport_array.c:248
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffff800010290720-ffff800010290a14: bpf_fd_reuseport_array_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (c04bfa44)
Location: kernel/bpf/reuseport_array.c:248
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
c04bfa44-c04bfc04: bpf_fd_reuseport_array_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (c00000000033d300)
Location: kernel/bpf/reuseport_array.c:248
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
c00000000033d300-c00000000033d5d0: bpf_fd_reuseport_array_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffe0001c2f7c)
Location: kernel/bpf/reuseport_array.c:248
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffe0001c2f7c-ffffffe0001c3108: bpf_fd_reuseport_array_update_elem (STB_GLOBAL)
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
int bpf_fd_reuseport_array_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff811ff230)
Location: kernel/bpf/reuseport_array.c:248
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811ff230-ffffffff811ff3e7: bpf_fd_reuseport_array_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff811f1f80)
Location: kernel/bpf/reuseport_array.c:248
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811f1f80-ffffffff811f2137: bpf_fd_reuseport_array_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff811fd000)
Location: kernel/bpf/reuseport_array.c:248
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811fd000-ffffffff811fd1b7: bpf_fd_reuseport_array_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_fd_reuseport_array_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/reuseport_array.c (ffffffff8120bcd0)
Location: kernel/bpf/reuseport_array.c:248
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff8120bcd0-ffffffff8120be87: bpf_fd_reuseport_array_update_elem (STB_GLOBAL)
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
