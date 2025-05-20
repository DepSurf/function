# Function: <code>bpf_lru_pop_free</code>

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
struct bpf_lru_node *bpf_lru_pop_free(struct bpf_lru *lru, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81196620)
Location: kernel/bpf/bpf_lru_list.c:497
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff81196620-ffffffff81196a98: bpf_lru_pop_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct bpf_lru_node *bpf_lru_pop_free(struct bpf_lru *lru, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8119da00)
Location: kernel/bpf/bpf_lru_list.c:497
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_lru_pop
```
**Symbols:**

```
ffffffff8119da00-ffffffff8119def7: bpf_lru_pop_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct bpf_lru_node *bpf_lru_pop_free(struct bpf_lru *lru, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811ad5c0)
Location: kernel/bpf/bpf_lru_list.c:497
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_lru_pop
```
**Symbols:**

```
ffffffff811ad5c0-ffffffff811adb01: bpf_lru_pop_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct bpf_lru_node *bpf_lru_pop_free(struct bpf_lru *lru, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811c4b50)
Location: kernel/bpf/bpf_lru_list.c:497
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_lru_pop
```
**Symbols:**

```
ffffffff811c4b50-ffffffff811c5088: bpf_lru_pop_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct bpf_lru_node *bpf_lru_pop_free(struct bpf_lru *lru, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811d6740)
Location: kernel/bpf/bpf_lru_list.c:497
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_lru_pop
```
**Symbols:**

```
ffffffff811d6740-ffffffff811d6c83: bpf_lru_pop_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bpf_lru_node *bpf_lru_pop_free(struct bpf_lru *lru, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811eb570)
Location: kernel/bpf/bpf_lru_list.c:494
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_lru_pop
```
**Symbols:**

```
ffffffff811eb570-ffffffff811eb679: bpf_lru_pop_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bpf_lru_node *bpf_lru_pop_free(struct bpf_lru *lru, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811f7cd0)
Location: kernel/bpf/bpf_lru_list.c:494
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_lru_pop
```
**Symbols:**

```
ffffffff811f7cd0-ffffffff811f7dd9: bpf_lru_pop_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_lru_node *bpf_lru_pop_free(struct bpf_lru *lru, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121bbd0)
Location: kernel/bpf/bpf_lru_list.c:494
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_lru_pop
```
**Symbols:**

```
ffffffff8121bbd0-ffffffff8121bbf0: bpf_lru_pop_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_lru_node *bpf_lru_pop_free(struct bpf_lru *lru, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121eb50)
Location: kernel/bpf/bpf_lru_list.c:494
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_lru_pop
```
**Symbols:**

```
ffffffff8121eb50-ffffffff8121eb70: bpf_lru_pop_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_lru_node *bpf_lru_pop_free(struct bpf_lru *lru, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81222450)
Location: kernel/bpf/bpf_lru_list.c:494
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_lru_pop
```
**Symbols:**

```
ffffffff81222450-ffffffff81222555: bpf_lru_pop_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct bpf_lru_node *bpf_lru_pop_free(struct bpf_lru *lru, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:494
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_lru_pop
```
**Symbols:**

```
ffffffff81cb9265-ffffffff81cb927a: bpf_lru_pop_free.cold (STB_LOCAL)
ffffffff8125a0a0-ffffffff8125a1dc: bpf_lru_pop_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct bpf_lru_node *bpf_lru_pop_free(struct bpf_lru *lru, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:494
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_lru_pop
```
**Symbols:**

```
ffffffff81e6a543-ffffffff81e6a557: bpf_lru_pop_free.cold (STB_LOCAL)
ffffffff812a3120-ffffffff812a3264: bpf_lru_pop_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct bpf_lru_node *bpf_lru_pop_free(struct bpf_lru *lru, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:494
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_lru_pop
```
**Symbols:**

```
ffffffff82061696-ffffffff820616aa: bpf_lru_pop_free.cold (STB_LOCAL)
ffffffff81300c70-ffffffff81300db4: bpf_lru_pop_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct bpf_lru_node *bpf_lru_pop_free(struct bpf_lru *lru, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:499
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_lru_pop
```
**Symbols:**

```
ffffffff820e0c31-ffffffff820e0c45: bpf_lru_pop_free.cold (STB_LOCAL)
ffffffff8132f7d0-ffffffff8132f914: bpf_lru_pop_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct bpf_lru_node *bpf_lru_pop_free(struct bpf_lru *lru, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:499
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_lru_pop
```
**Symbols:**

```
ffffffff821bd3e6-ffffffff821bd3fa: bpf_lru_pop_free.cold (STB_LOCAL)
ffffffff81353cf0-ffffffff81353e34: bpf_lru_pop_free (STB_GLOBAL)
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
struct bpf_lru_node *bpf_lru_pop_free(struct bpf_lru *lru, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffff80001027c7b0)
Location: kernel/bpf/bpf_lru_list.c:494
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_lru_pop
```
**Symbols:**

```
ffff80001027c7b0-ffff80001027ce7c: bpf_lru_pop_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bpf_lru_node *bpf_lru_pop_free(struct bpf_lru *lru, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (c04ae7b0)
Location: kernel/bpf/bpf_lru_list.c:494
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_lru_pop
```
**Symbols:**

```
c04ae7b0-c04ae8cc: bpf_lru_pop_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bpf_lru_node *bpf_lru_pop_free(struct bpf_lru *lru, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (c000000000326790)
Location: kernel/bpf/bpf_lru_list.c:494
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_lru_pop
```
**Symbols:**

```
c000000000326790-c000000000326904: bpf_lru_pop_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bpf_lru_node *bpf_lru_pop_free(struct bpf_lru *lru, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffe0001b4380)
Location: kernel/bpf/bpf_lru_list.c:494
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffe0001b4380-ffffffe0001b4484: bpf_lru_pop_free (STB_GLOBAL)
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
struct bpf_lru_node *bpf_lru_pop_free(struct bpf_lru *lru, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811f02f0)
Location: kernel/bpf/bpf_lru_list.c:494
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_lru_pop
```
**Symbols:**

```
ffffffff811f02f0-ffffffff811f03f9: bpf_lru_pop_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bpf_lru_node *bpf_lru_pop_free(struct bpf_lru *lru, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811e3040)
Location: kernel/bpf/bpf_lru_list.c:494
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_lru_pop
```
**Symbols:**

```
ffffffff811e3040-ffffffff811e3149: bpf_lru_pop_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bpf_lru_node *bpf_lru_pop_free(struct bpf_lru *lru, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811ee0c0)
Location: kernel/bpf/bpf_lru_list.c:494
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_lru_pop
```
**Symbols:**

```
ffffffff811ee0c0-ffffffff811ee1c9: bpf_lru_pop_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bpf_lru_node *bpf_lru_pop_free(struct bpf_lru *lru, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811fc590)
Location: kernel/bpf/bpf_lru_list.c:494
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_lru_pop
```
**Symbols:**

```
ffffffff811fc590-ffffffff811fc699: bpf_lru_pop_free (STB_GLOBAL)
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
