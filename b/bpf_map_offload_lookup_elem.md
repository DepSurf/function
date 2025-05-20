# Function: <code>bpf_map_offload_lookup_elem</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bpf_map_offload_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811cbf80)
Location: kernel/bpf/offload.c:359
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811cbf80-ffffffff811cbfe4: bpf_map_offload_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_map_offload_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811e00b0)
Location: kernel/bpf/offload.c:398
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811e00b0-ffffffff811e0114: bpf_map_offload_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_map_offload_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f5c50)
Location: kernel/bpf/offload.c:434
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811f5c50-ffffffff811f5cbb: bpf_map_offload_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_map_offload_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81202c60)
Location: kernel/bpf/offload.c:434
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff81202c60-ffffffff81202ccb: bpf_map_offload_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_map_offload_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff8122a230)
Location: kernel/bpf/offload.c:434
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff8122a230-ffffffff8122a29b: bpf_map_offload_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_map_offload_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81231dc0)
Location: kernel/bpf/offload.c:434
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff81231dc0-ffffffff81231e2b: bpf_map_offload_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_map_offload_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81235f40)
Location: kernel/bpf/offload.c:434
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff81235f40-ffffffff81235fab: bpf_map_offload_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_map_offload_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81270190)
Location: kernel/bpf/offload.c:434
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff81270190-ffffffff812701fb: bpf_map_offload_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_map_offload_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff812bf250)
Location: kernel/bpf/offload.c:434
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff812bf250-ffffffff812bf2be: bpf_map_offload_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_map_offload_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81322920)
Location: kernel/bpf/offload.c:431
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff81322920-ffffffff8132298e: bpf_map_offload_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_map_offload_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff813528d0)
Location: kernel/bpf/offload.c:572
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff813528d0-ffffffff8135293e: bpf_map_offload_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_map_offload_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81379db0)
Location: kernel/bpf/offload.c:582
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff81379db0-ffffffff81379e1e: bpf_map_offload_lookup_elem (STB_GLOBAL)
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
int bpf_map_offload_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffff80001028b1d0)
Location: kernel/bpf/offload.c:434
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffff80001028b1d0-ffff80001028b24c: bpf_map_offload_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_map_offload_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (c04ba9e0)
Location: kernel/bpf/offload.c:434
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
c04ba9e0-c04baa50: bpf_map_offload_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_map_offload_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (c000000000337000)
Location: kernel/bpf/offload.c:434
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
c000000000337000-c0000000003370b8: bpf_map_offload_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_map_offload_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffe0001bef76)
Location: kernel/bpf/offload.c:434
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffe0001bef76-ffffffe0001befda: bpf_map_offload_lookup_elem (STB_GLOBAL)
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
int bpf_map_offload_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811fb280)
Location: kernel/bpf/offload.c:434
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811fb280-ffffffff811fb2eb: bpf_map_offload_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_map_offload_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811edfd0)
Location: kernel/bpf/offload.c:434
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811edfd0-ffffffff811ee03b: bpf_map_offload_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_map_offload_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f9050)
Location: kernel/bpf/offload.c:434
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811f9050-ffffffff811f90bb: bpf_map_offload_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_map_offload_lookup_elem(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81207af0)
Location: kernel/bpf/offload.c:434
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff81207af0-ffffffff81207b5b: bpf_map_offload_lookup_elem (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
