# Function: <code>bpf_percpu_array_update</code>

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
int bpf_percpu_array_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81187c90)
Location: kernel/bpf/arraymap.c:206
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff81187c90-ffffffff81187d77: bpf_percpu_array_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bpf_percpu_array_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81195c40)
Location: kernel/bpf/arraymap.c:201
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff81195c40-ffffffff81195d33: bpf_percpu_array_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bpf_percpu_array_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8119d180)
Location: kernel/bpf/arraymap.c:229
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
**Symbols:**

```
ffffffff8119d180-ffffffff8119d269: bpf_percpu_array_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bpf_percpu_array_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811acd20)
Location: kernel/bpf/arraymap.c:274
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
**Symbols:**

```
ffffffff811acd20-ffffffff811acdfd: bpf_percpu_array_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bpf_percpu_array_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811c42e0)
Location: kernel/bpf/arraymap.c:279
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811c42e0-ffffffff811c43b8: bpf_percpu_array_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_percpu_array_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811d5e80)
Location: kernel/bpf/arraymap.c:279
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811d5e80-ffffffff811d5f58: bpf_percpu_array_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_percpu_array_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ea830)
Location: kernel/bpf/arraymap.c:309
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811ea830-ffffffff811ea925: bpf_percpu_array_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_percpu_array_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811f6f90)
Location: kernel/bpf/arraymap.c:309
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811f6f90-ffffffff811f7085: bpf_percpu_array_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_percpu_array_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8121ac20)
Location: kernel/bpf/arraymap.c:335
Inline: False
```
**Symbols:**

```
ffffffff8121ac20-ffffffff8121ad09: bpf_percpu_array_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_percpu_array_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8121d9a0)
Location: kernel/bpf/arraymap.c:328
Inline: False
```
**Symbols:**

```
ffffffff8121d9a0-ffffffff8121da8e: bpf_percpu_array_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_percpu_array_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff812214c0)
Location: kernel/bpf/arraymap.c:328
Inline: False
```
**Symbols:**

```
ffffffff812214c0-ffffffff812215ae: bpf_percpu_array_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_percpu_array_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81258e80)
Location: kernel/bpf/arraymap.c:335
Inline: False
```
**Symbols:**

```
ffffffff81258e80-ffffffff81258fa8: bpf_percpu_array_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_percpu_array_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff812a1d30)
Location: kernel/bpf/arraymap.c:357
Inline: False
```
**Symbols:**

```
ffffffff812a1d30-ffffffff812a1e9d: bpf_percpu_array_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_percpu_array_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff812ff410)
Location: kernel/bpf/arraymap.c:349
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_update_value
```
**Symbols:**

```
ffffffff812ff410-ffffffff812ff57c: bpf_percpu_array_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_percpu_array_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8132df70)
Location: kernel/bpf/arraymap.c:349
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_update_value
```
**Symbols:**

```
ffffffff8132df70-ffffffff8132e0dc: bpf_percpu_array_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_percpu_array_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81352340)
Location: kernel/bpf/arraymap.c:349
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_update_value
```
**Symbols:**

```
ffffffff81352340-ffffffff813524ac: bpf_percpu_array_update (STB_GLOBAL)
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
int bpf_percpu_array_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffff80001027ba68)
Location: kernel/bpf/arraymap.c:309
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffff80001027ba68-ffff80001027bbb4: bpf_percpu_array_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_percpu_array_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (c04ad930)
Location: kernel/bpf/arraymap.c:309
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
c04ad930-c04ada3c: bpf_percpu_array_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_percpu_array_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (c0000000003250b0)
Location: kernel/bpf/arraymap.c:309
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
c0000000003250b0-c000000000325254: bpf_percpu_array_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_percpu_array_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffe0001b35ce)
Location: kernel/bpf/arraymap.c:309
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffe0001b35ce-ffffffe0001b36ec: bpf_percpu_array_update (STB_GLOBAL)
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
int bpf_percpu_array_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ef5b0)
Location: kernel/bpf/arraymap.c:309
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811ef5b0-ffffffff811ef6a5: bpf_percpu_array_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_percpu_array_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811e2340)
Location: kernel/bpf/arraymap.c:309
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811e2340-ffffffff811e2435: bpf_percpu_array_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_percpu_array_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ed380)
Location: kernel/bpf/arraymap.c:309
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811ed380-ffffffff811ed475: bpf_percpu_array_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_percpu_array_update(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811fb820)
Location: kernel/bpf/arraymap.c:309
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811fb820-ffffffff811fb926: bpf_percpu_array_update (STB_GLOBAL)
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
