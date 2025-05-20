# Function: <code>bpf_percpu_hash_copy</code>

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
int bpf_percpu_hash_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81187450)
Location: kernel/bpf/hashtab.c:746
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff81187450-ffffffff81187525: bpf_percpu_hash_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bpf_percpu_hash_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811953e0)
Location: kernel/bpf/hashtab.c:1068
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811953e0-ffffffff811954db: bpf_percpu_hash_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bpf_percpu_hash_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8119c690)
Location: kernel/bpf/hashtab.c:1154
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
**Symbols:**

```
ffffffff8119c690-ffffffff8119c778: bpf_percpu_hash_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bpf_percpu_hash_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811abfd0)
Location: kernel/bpf/hashtab.c:1188
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
**Symbols:**

```
ffffffff811abfd0-ffffffff811ac0b9: bpf_percpu_hash_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bpf_percpu_hash_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811c3400)
Location: kernel/bpf/hashtab.c:1210
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811c3400-ffffffff811c34e4: bpf_percpu_hash_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_percpu_hash_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811d4e90)
Location: kernel/bpf/hashtab.c:1247
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811d4e90-ffffffff811d4f74: bpf_percpu_hash_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_percpu_hash_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811e9680)
Location: kernel/bpf/hashtab.c:1283
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811e9680-ffffffff811e9744: bpf_percpu_hash_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_percpu_hash_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f5de0)
Location: kernel/bpf/hashtab.c:1283
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811f5de0-ffffffff811f5ea4: bpf_percpu_hash_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_percpu_hash_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81219420)
Location: kernel/bpf/hashtab.c:1673
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff81219420-ffffffff81219520: bpf_percpu_hash_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_percpu_hash_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121bd40)
Location: kernel/bpf/hashtab.c:1932
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff8121bd40-ffffffff8121be4a: bpf_percpu_hash_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_percpu_hash_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121f740)
Location: kernel/bpf/hashtab.c:1993
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff8121f740-ffffffff8121f84b: bpf_percpu_hash_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_percpu_hash_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81256f00)
Location: kernel/bpf/hashtab.c:2177
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff81256f00-ffffffff81257039: bpf_percpu_hash_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_percpu_hash_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8129f880)
Location: kernel/bpf/hashtab.c:2242
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff8129f880-ffffffff8129f9e2: bpf_percpu_hash_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_percpu_hash_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812fc800)
Location: kernel/bpf/hashtab.c:2273
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff812fc800-ffffffff812fc96b: bpf_percpu_hash_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_percpu_hash_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8132b380)
Location: kernel/bpf/hashtab.c:2326
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff8132b380-ffffffff8132b599: bpf_percpu_hash_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_percpu_hash_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8134f830)
Location: kernel/bpf/hashtab.c:2348
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff8134f830-ffffffff8134fa59: bpf_percpu_hash_copy (STB_GLOBAL)
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
int bpf_percpu_hash_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffff80001027a268)
Location: kernel/bpf/hashtab.c:1283
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffff80001027a268-ffff80001027a380: bpf_percpu_hash_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_percpu_hash_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c04ac498)
Location: kernel/bpf/hashtab.c:1283
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
c04ac498-c04ac56c: bpf_percpu_hash_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_percpu_hash_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c000000000323400)
Location: kernel/bpf/hashtab.c:1283
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
c000000000323400-c000000000323568: bpf_percpu_hash_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_percpu_hash_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffe0001b2156)
Location: kernel/bpf/hashtab.c:1283
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffe0001b2156-ffffffe0001b2252: bpf_percpu_hash_copy (STB_GLOBAL)
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
int bpf_percpu_hash_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811ee400)
Location: kernel/bpf/hashtab.c:1283
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811ee400-ffffffff811ee4c4: bpf_percpu_hash_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_percpu_hash_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811e1190)
Location: kernel/bpf/hashtab.c:1283
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811e1190-ffffffff811e1254: bpf_percpu_hash_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_percpu_hash_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811ec1d0)
Location: kernel/bpf/hashtab.c:1283
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811ec1d0-ffffffff811ec294: bpf_percpu_hash_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_percpu_hash_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811fa5d0)
Location: kernel/bpf/hashtab.c:1283
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811fa5d0-ffffffff811fa6ac: bpf_percpu_hash_copy (STB_GLOBAL)
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
