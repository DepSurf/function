# Function: <code>bpf_map_offload_delete_elem</code>

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
int bpf_map_offload_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811cc070)
Location: kernel/bpf/offload.c:390
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_delete_elem
```
**Symbols:**

```
ffffffff811cc070-ffffffff811cc0ca: bpf_map_offload_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_map_offload_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811e01a0)
Location: kernel/bpf/offload.c:429
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811e01a0-ffffffff811e01fa: bpf_map_offload_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_map_offload_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f5d50)
Location: kernel/bpf/offload.c:465
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811f5d50-ffffffff811f5db1: bpf_map_offload_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_map_offload_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81202d60)
Location: kernel/bpf/offload.c:465
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff81202d60-ffffffff81202dc1: bpf_map_offload_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_map_offload_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff8122a330)
Location: kernel/bpf/offload.c:465
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_delete_elem
```
**Symbols:**

```
ffffffff8122a330-ffffffff8122a391: bpf_map_offload_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_map_offload_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81231ec0)
Location: kernel/bpf/offload.c:465
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_delete_elem
```
**Symbols:**

```
ffffffff81231ec0-ffffffff81231f21: bpf_map_offload_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_map_offload_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81236040)
Location: kernel/bpf/offload.c:465
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_delete_elem
```
**Symbols:**

```
ffffffff81236040-ffffffff812360a1: bpf_map_offload_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_map_offload_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81270290)
Location: kernel/bpf/offload.c:465
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_delete_elem
```
**Symbols:**

```
ffffffff81270290-ffffffff812702f1: bpf_map_offload_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_map_offload_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff812bf370)
Location: kernel/bpf/offload.c:465
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_delete_elem
```
**Symbols:**

```
ffffffff812bf370-ffffffff812bf3d2: bpf_map_offload_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_map_offload_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81322a60)
Location: kernel/bpf/offload.c:462
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_delete_elem
```
**Symbols:**

```
ffffffff81322a60-ffffffff81322ac2: bpf_map_offload_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_map_offload_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81352a10)
Location: kernel/bpf/offload.c:603
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_delete_elem
```
**Symbols:**

```
ffffffff81352a10-ffffffff81352a72: bpf_map_offload_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_map_offload_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81379ef0)
Location: kernel/bpf/offload.c:613
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_delete_elem
```
**Symbols:**

```
ffffffff81379ef0-ffffffff81379f52: bpf_map_offload_delete_elem (STB_GLOBAL)
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
int bpf_map_offload_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffff80001028b300)
Location: kernel/bpf/offload.c:465
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffff80001028b300-ffff80001028b374: bpf_map_offload_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_map_offload_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (c04baae8)
Location: kernel/bpf/offload.c:465
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
c04baae8-c04bab50: bpf_map_offload_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_map_offload_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (c0000000003371c0)
Location: kernel/bpf/offload.c:465
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
c0000000003371c0-c000000000337268: bpf_map_offload_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_map_offload_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffe0001bf052)
Location: kernel/bpf/offload.c:465
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffe0001bf052-ffffffe0001bf0ae: bpf_map_offload_delete_elem (STB_GLOBAL)
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
int bpf_map_offload_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811fb380)
Location: kernel/bpf/offload.c:465
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811fb380-ffffffff811fb3e1: bpf_map_offload_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_map_offload_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811ee0d0)
Location: kernel/bpf/offload.c:465
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811ee0d0-ffffffff811ee131: bpf_map_offload_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_map_offload_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f9150)
Location: kernel/bpf/offload.c:465
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811f9150-ffffffff811f91b1: bpf_map_offload_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_map_offload_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81207bf0)
Location: kernel/bpf/offload.c:465
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff81207bf0-ffffffff81207c51: bpf_map_offload_delete_elem (STB_GLOBAL)
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
