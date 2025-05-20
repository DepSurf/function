# Function: <code>bpf_lru_destroy</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bpf_lru_destroy(struct bpf_lru *lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81196f90)
Location: kernel/bpf/bpf_lru_list.c:689
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
```
**Symbols:**

```
ffffffff81196f90-ffffffff81196fba: bpf_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bpf_lru_destroy(struct bpf_lru *lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8119e310)
Location: kernel/bpf/bpf_lru_list.c:691
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
ffffffff8119e310-ffffffff8119e33a: bpf_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bpf_lru_destroy(struct bpf_lru *lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811adf00)
Location: kernel/bpf/bpf_lru_list.c:691
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
ffffffff811adf00-ffffffff811adf2a: bpf_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bpf_lru_destroy(struct bpf_lru *lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811c5480)
Location: kernel/bpf/bpf_lru_list.c:691
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
ffffffff811c5480-ffffffff811c54aa: bpf_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpf_lru_destroy(struct bpf_lru *lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811d7080)
Location: kernel/bpf/bpf_lru_list.c:691
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
ffffffff811d7080-ffffffff811d70aa: bpf_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_lru_destroy(struct bpf_lru *lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811eba50)
Location: kernel/bpf/bpf_lru_list.c:688
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
ffffffff811eba50-ffffffff811eba7a: bpf_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_lru_destroy(struct bpf_lru *lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811f81b0)
Location: kernel/bpf/bpf_lru_list.c:688
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
ffffffff811f81b0-ffffffff811f81da: bpf_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_lru_destroy(struct bpf_lru *lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121bf30)
Location: kernel/bpf/bpf_lru_list.c:688
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff8121bf30-ffffffff8121bf5a: bpf_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_lru_destroy(struct bpf_lru *lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121eeb0)
Location: kernel/bpf/bpf_lru_list.c:689
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff8121eeb0-ffffffff8121eeda: bpf_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_lru_destroy(struct bpf_lru *lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81222940)
Location: kernel/bpf/bpf_lru_list.c:689
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff81222940-ffffffff8122296a: bpf_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void bpf_lru_destroy(struct bpf_lru *lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:689
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff81cb92ab-ffffffff81cb92c0: bpf_lru_destroy.cold (STB_LOCAL)
ffffffff8125a6d0-ffffffff8125a715: bpf_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void bpf_lru_destroy(struct bpf_lru *lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:689
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff81e6a581-ffffffff81e6a596: bpf_lru_destroy.cold (STB_LOCAL)
ffffffff812a37c0-ffffffff812a3815: bpf_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void bpf_lru_destroy(struct bpf_lru *lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:689
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff820616d4-ffffffff820616e9: bpf_lru_destroy.cold (STB_LOCAL)
ffffffff81301370-ffffffff813013c5: bpf_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void bpf_lru_destroy(struct bpf_lru *lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:694
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff820e0c77-ffffffff820e0c8c: bpf_lru_destroy.cold (STB_LOCAL)
ffffffff8132fec0-ffffffff8132ff15: bpf_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void bpf_lru_destroy(struct bpf_lru *lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:694
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff821bd42c-ffffffff821bd441: bpf_lru_destroy.cold (STB_LOCAL)
ffffffff813543e0-ffffffff81354435: bpf_lru_destroy (STB_GLOBAL)
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
void bpf_lru_destroy(struct bpf_lru *lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffff80001027d3a0)
Location: kernel/bpf/bpf_lru_list.c:688
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
ffff80001027d3a0-ffff80001027d3e8: bpf_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_lru_destroy(struct bpf_lru *lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (c04aedf0)
Location: kernel/bpf/bpf_lru_list.c:688
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
c04aedf0-c04aee1c: bpf_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_lru_destroy(struct bpf_lru *lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (c000000000326f50)
Location: kernel/bpf/bpf_lru_list.c:688
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
c000000000326f50-c000000000326fbc: bpf_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bpf_lru_destroy(struct bpf_lru *lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffe0001b4840)
Location: kernel/bpf/bpf_lru_list.c:688
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
ffffffe0001b4840-ffffffe0001b4884: bpf_lru_destroy (STB_GLOBAL)
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
void bpf_lru_destroy(struct bpf_lru *lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811f07d0)
Location: kernel/bpf/bpf_lru_list.c:688
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
ffffffff811f07d0-ffffffff811f07fa: bpf_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_lru_destroy(struct bpf_lru *lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811e3520)
Location: kernel/bpf/bpf_lru_list.c:688
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
ffffffff811e3520-ffffffff811e354a: bpf_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_lru_destroy(struct bpf_lru *lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811ee5a0)
Location: kernel/bpf/bpf_lru_list.c:688
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
ffffffff811ee5a0-ffffffff811ee5ca: bpf_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_lru_destroy(struct bpf_lru *lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811fca70)
Location: kernel/bpf/bpf_lru_list.c:688
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
ffffffff811fca70-ffffffff811fca9a: bpf_lru_destroy (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
