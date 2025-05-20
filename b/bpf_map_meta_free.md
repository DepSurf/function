# Function: <code>bpf_map_meta_free</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bpf_map_meta_free(struct bpf_map *map_meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff8119eb30)
Location: kernel/bpf/map_in_map.c:54
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff8119eb30-ffffffff8119eb40: bpf_map_meta_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bpf_map_meta_free(struct bpf_map *map_meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811ae9c0)
Location: kernel/bpf/map_in_map.c:54
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff811ae9c0-ffffffff811ae9d0: bpf_map_meta_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bpf_map_meta_free(struct bpf_map *map_meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811c6170)
Location: kernel/bpf/map_in_map.c:54
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff811c6170-ffffffff811c6180: bpf_map_meta_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpf_map_meta_free(struct bpf_map *map_meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811d7c60)
Location: kernel/bpf/map_in_map.c:69
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff811d7c60-ffffffff811d7c70: bpf_map_meta_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_map_meta_free(struct bpf_map *map_meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811ec5f0)
Location: kernel/bpf/map_in_map.c:72
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff811ec5f0-ffffffff811ec600: bpf_map_meta_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_map_meta_free(struct bpf_map *map_meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811f8d50)
Location: kernel/bpf/map_in_map.c:72
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff811f8d50-ffffffff811f8d60: bpf_map_meta_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_map_meta_free(struct bpf_map *map_meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff8121cb50)
Location: kernel/bpf/map_in_map.c:72
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff8121cb50-ffffffff8121cb60: bpf_map_meta_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_map_meta_free(struct bpf_map *map_meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff8121fa80)
Location: kernel/bpf/map_in_map.c:66
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff8121fa80-ffffffff8121fa90: bpf_map_meta_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_map_meta_free(struct bpf_map *map_meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff81223500)
Location: kernel/bpf/map_in_map.c:66
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff81223500-ffffffff81223510: bpf_map_meta_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_map_meta_free(struct bpf_map *map_meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff8125b2f0)
Location: kernel/bpf/map_in_map.c:72
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff8125b2f0-ffffffff8125b315: bpf_map_meta_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_map_meta_free(struct bpf_map *map_meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff812a44e0)
Location: kernel/bpf/map_in_map.c:73
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff812a44e0-ffffffff812a450f: bpf_map_meta_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_map_meta_free(struct bpf_map *map_meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff81302150)
Location: kernel/bpf/map_in_map.c:100
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff81302150-ffffffff8130218b: bpf_map_meta_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_map_meta_free(struct bpf_map *map_meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff81330cf0)
Location: kernel/bpf/map_in_map.c:90
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff81330cf0-ffffffff81330d1f: bpf_map_meta_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_map_meta_free(struct bpf_map *map_meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff81355250)
Location: kernel/bpf/map_in_map.c:90
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff81355250-ffffffff8135527f: bpf_map_meta_free (STB_GLOBAL)
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
void bpf_map_meta_free(struct bpf_map *map_meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffff80001027e278)
Location: kernel/bpf/map_in_map.c:72
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffff80001027e278-ffff80001027e2a4: bpf_map_meta_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_map_meta_free(struct bpf_map *map_meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (c04af9f0)
Location: kernel/bpf/map_in_map.c:72
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
c04af9f0-c04afa0c: bpf_map_meta_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_map_meta_free(struct bpf_map *map_meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (c000000000328090)
Location: kernel/bpf/map_in_map.c:72
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
c000000000328090-c0000000003280c4: bpf_map_meta_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bpf_map_meta_free(struct bpf_map *map_meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffe0001b5420)
Location: kernel/bpf/map_in_map.c:72
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffe0001b5420-ffffffe0001b544a: bpf_map_meta_free (STB_GLOBAL)
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
void bpf_map_meta_free(struct bpf_map *map_meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811f1370)
Location: kernel/bpf/map_in_map.c:72
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff811f1370-ffffffff811f1380: bpf_map_meta_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_map_meta_free(struct bpf_map *map_meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811e40c0)
Location: kernel/bpf/map_in_map.c:72
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff811e40c0-ffffffff811e40d0: bpf_map_meta_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_map_meta_free(struct bpf_map *map_meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811ef140)
Location: kernel/bpf/map_in_map.c:72
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff811ef140-ffffffff811ef150: bpf_map_meta_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_map_meta_free(struct bpf_map *map_meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811fd610)
Location: kernel/bpf/map_in_map.c:72
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_free
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff811fd610-ffffffff811fd620: bpf_map_meta_free (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
