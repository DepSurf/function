# Function: <code>bpf_map_meta_alloc</code>

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
struct bpf_map *bpf_map_meta_alloc(int inner_map_ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff8119ea40)
Location: kernel/bpf/map_in_map.c:12
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff8119ea40-ffffffff8119eb28: bpf_map_meta_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct bpf_map *bpf_map_meta_alloc(int inner_map_ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811ae8d0)
Location: kernel/bpf/map_in_map.c:12
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff811ae8d0-ffffffff811ae9b6: bpf_map_meta_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct bpf_map *bpf_map_meta_alloc(int inner_map_ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811c6090)
Location: kernel/bpf/map_in_map.c:12
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff811c6090-ffffffff811c6162: bpf_map_meta_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct bpf_map *bpf_map_meta_alloc(int inner_map_ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811d7b50)
Location: kernel/bpf/map_in_map.c:12
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff811d7b50-ffffffff811d7c60: bpf_map_meta_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bpf_map *bpf_map_meta_alloc(int inner_map_ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811ec4c0)
Location: kernel/bpf/map_in_map.c:9
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff811ec4c0-ffffffff811ec5f0: bpf_map_meta_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bpf_map *bpf_map_meta_alloc(int inner_map_ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811f8c20)
Location: kernel/bpf/map_in_map.c:9
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff811f8c20-ffffffff811f8d50: bpf_map_meta_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_map *bpf_map_meta_alloc(int inner_map_ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff8121ca10)
Location: kernel/bpf/map_in_map.c:9
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff8121ca10-ffffffff8121cb41: bpf_map_meta_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_map *bpf_map_meta_alloc(int inner_map_ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff8121f920)
Location: kernel/bpf/map_in_map.c:9
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff8121f920-ffffffff8121fa7d: bpf_map_meta_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_map *bpf_map_meta_alloc(int inner_map_ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff812233a0)
Location: kernel/bpf/map_in_map.c:9
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff812233a0-ffffffff812234fd: bpf_map_meta_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct bpf_map *bpf_map_meta_alloc(int inner_map_ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/map_in_map.c (0)
Location: kernel/bpf/map_in_map.c:10
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff81cb92c0-ffffffff81cb92d5: bpf_map_meta_alloc.cold (STB_LOCAL)
ffffffff8125b150-ffffffff8125b2e6: bpf_map_meta_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct bpf_map *bpf_map_meta_alloc(int inner_map_ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/map_in_map.c (0)
Location: kernel/bpf/map_in_map.c:10
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff81e6a596-ffffffff81e6a5ab: bpf_map_meta_alloc.cold (STB_LOCAL)
ffffffff812a4340-ffffffff812a44d9: bpf_map_meta_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct bpf_map *bpf_map_meta_alloc(int inner_map_ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/map_in_map.c (0)
Location: kernel/bpf/map_in_map.c:10
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff820616e9-ffffffff820616fe: bpf_map_meta_alloc.cold (STB_LOCAL)
ffffffff81301f90-ffffffff81302139: bpf_map_meta_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct bpf_map *bpf_map_meta_alloc(int inner_map_ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/map_in_map.c (0)
Location: kernel/bpf/map_in_map.c:10
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff820e0c8c-ffffffff820e0ca0: bpf_map_meta_alloc.cold (STB_LOCAL)
ffffffff81330b30-ffffffff81330cdd: bpf_map_meta_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct bpf_map *bpf_map_meta_alloc(int inner_map_ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/map_in_map.c (0)
Location: kernel/bpf/map_in_map.c:10
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff821bd441-ffffffff821bd455: bpf_map_meta_alloc.cold (STB_LOCAL)
ffffffff81355090-ffffffff8135523d: bpf_map_meta_alloc (STB_GLOBAL)
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
struct bpf_map *bpf_map_meta_alloc(int inner_map_ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffff80001027e130)
Location: kernel/bpf/map_in_map.c:9
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffff80001027e130-ffff80001027e274: bpf_map_meta_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bpf_map *bpf_map_meta_alloc(int inner_map_ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (c04af860)
Location: kernel/bpf/map_in_map.c:9
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
c04af860-c04af9f0: bpf_map_meta_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bpf_map *bpf_map_meta_alloc(int inner_map_ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (c000000000327e90)
Location: kernel/bpf/map_in_map.c:9
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
c000000000327e90-c000000000328084: bpf_map_meta_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bpf_map *bpf_map_meta_alloc(int inner_map_ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffe0001b5312)
Location: kernel/bpf/map_in_map.c:9
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffe0001b5312-ffffffe0001b5420: bpf_map_meta_alloc (STB_GLOBAL)
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
struct bpf_map *bpf_map_meta_alloc(int inner_map_ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811f1240)
Location: kernel/bpf/map_in_map.c:9
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff811f1240-ffffffff811f1370: bpf_map_meta_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bpf_map *bpf_map_meta_alloc(int inner_map_ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811e3f90)
Location: kernel/bpf/map_in_map.c:9
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff811e3f90-ffffffff811e40c0: bpf_map_meta_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bpf_map *bpf_map_meta_alloc(int inner_map_ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811ef010)
Location: kernel/bpf/map_in_map.c:9
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff811ef010-ffffffff811ef140: bpf_map_meta_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bpf_map *bpf_map_meta_alloc(int inner_map_ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811fd4e0)
Location: kernel/bpf/map_in_map.c:9
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_alloc
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff811fd4e0-ffffffff811fd610: bpf_map_meta_alloc (STB_GLOBAL)
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
