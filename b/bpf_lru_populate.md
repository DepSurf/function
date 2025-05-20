# Function: <code>bpf_lru_populate</code>

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
void bpf_lru_populate(struct bpf_lru *lru, void *buf, u32 node_offset, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81196d60)
Location: kernel/bpf/bpf_lru_list.c:608
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff81196d60-ffffffff81196db5: bpf_lru_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bpf_lru_populate(struct bpf_lru *lru, void *buf, u32 node_offset, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8119e020)
Location: kernel/bpf/bpf_lru_list.c:610
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff8119e020-ffffffff8119e14e: bpf_lru_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bpf_lru_populate(struct bpf_lru *lru, void *buf, u32 node_offset, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811adc30)
Location: kernel/bpf/bpf_lru_list.c:610
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff811adc30-ffffffff811add52: bpf_lru_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bpf_lru_populate(struct bpf_lru *lru, void *buf, u32 node_offset, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811c51a0)
Location: kernel/bpf/bpf_lru_list.c:610
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff811c51a0-ffffffff811c52c7: bpf_lru_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpf_lru_populate(struct bpf_lru *lru, void *buf, u32 node_offset, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811d6da0)
Location: kernel/bpf/bpf_lru_list.c:610
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff811d6da0-ffffffff811d6ec7: bpf_lru_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_lru_populate(struct bpf_lru *lru, void *buf, u32 node_offset, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811eb790)
Location: kernel/bpf/bpf_lru_list.c:607
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff811eb790-ffffffff811eb8b8: bpf_lru_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_lru_populate(struct bpf_lru *lru, void *buf, u32 node_offset, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811f7ef0)
Location: kernel/bpf/bpf_lru_list.c:607
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff811f7ef0-ffffffff811f8018: bpf_lru_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_lru_populate(struct bpf_lru *lru, void *buf, u32 node_offset, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121bc70)
Location: kernel/bpf/bpf_lru_list.c:607
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_init
```
**Symbols:**

```
ffffffff8121bc70-ffffffff8121bd98: bpf_lru_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_lru_populate(struct bpf_lru *lru, void *buf, u32 node_offset, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121ebf0)
Location: kernel/bpf/bpf_lru_list.c:608
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_init
```
**Symbols:**

```
ffffffff8121ebf0-ffffffff8121ed18: bpf_lru_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_lru_populate(struct bpf_lru *lru, void *buf, u32 node_offset, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81222670)
Location: kernel/bpf/bpf_lru_list.c:608
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_init
```
**Symbols:**

```
ffffffff81222670-ffffffff812227ac: bpf_lru_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void bpf_lru_populate(struct bpf_lru *lru, void *buf, u32 node_offset, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:608
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_init
```
**Symbols:**

```
ffffffff81cb928e-ffffffff81cb92ab: bpf_lru_populate.cold (STB_LOCAL)
ffffffff8125a350-ffffffff8125a4c0: bpf_lru_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void bpf_lru_populate(struct bpf_lru *lru, void *buf, u32 node_offset, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:608
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_init
```
**Symbols:**

```
ffffffff81e6a56c-ffffffff81e6a581: bpf_lru_populate.cold (STB_LOCAL)
ffffffff812a33f0-ffffffff812a3597: bpf_lru_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void bpf_lru_populate(struct bpf_lru *lru, void *buf, u32 node_offset, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:608
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_init
```
**Symbols:**

```
ffffffff820616bf-ffffffff820616d4: bpf_lru_populate.cold (STB_LOCAL)
ffffffff81300f60-ffffffff81301110: bpf_lru_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void bpf_lru_populate(struct bpf_lru *lru, void *buf, u32 node_offset, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:613
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_init
```
**Symbols:**

```
ffffffff820e0c5a-ffffffff820e0c77: bpf_lru_populate.cold (STB_LOCAL)
ffffffff8132fab0-ffffffff8132fc56: bpf_lru_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void bpf_lru_populate(struct bpf_lru *lru, void *buf, u32 node_offset, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:613
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_init
```
**Symbols:**

```
ffffffff821bd40f-ffffffff821bd42c: bpf_lru_populate.cold (STB_LOCAL)
ffffffff81353fd0-ffffffff81354176: bpf_lru_populate (STB_GLOBAL)
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
void bpf_lru_populate(struct bpf_lru *lru, void *buf, u32 node_offset, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffff80001027d0b0)
Location: kernel/bpf/bpf_lru_list.c:607
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffff80001027d0b0-ffff80001027d20c: bpf_lru_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_lru_populate(struct bpf_lru *lru, void *buf, u32 node_offset, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (c04aea90)
Location: kernel/bpf/bpf_lru_list.c:607
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
c04aea90-c04aec58: bpf_lru_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_lru_populate(struct bpf_lru *lru, void *buf, u32 node_offset, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (c000000000326b20)
Location: kernel/bpf/bpf_lru_list.c:607
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
c000000000326b20-c000000000326d14: bpf_lru_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bpf_lru_populate(struct bpf_lru *lru, void *buf, u32 node_offset, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffe0001b4598)
Location: kernel/bpf/bpf_lru_list.c:607
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffe0001b4598-ffffffe0001b46ca: bpf_lru_populate (STB_GLOBAL)
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
void bpf_lru_populate(struct bpf_lru *lru, void *buf, u32 node_offset, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811f0510)
Location: kernel/bpf/bpf_lru_list.c:607
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff811f0510-ffffffff811f0638: bpf_lru_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_lru_populate(struct bpf_lru *lru, void *buf, u32 node_offset, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811e3260)
Location: kernel/bpf/bpf_lru_list.c:607
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff811e3260-ffffffff811e3388: bpf_lru_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_lru_populate(struct bpf_lru *lru, void *buf, u32 node_offset, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811ee2e0)
Location: kernel/bpf/bpf_lru_list.c:607
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff811ee2e0-ffffffff811ee408: bpf_lru_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_lru_populate(struct bpf_lru *lru, void *buf, u32 node_offset, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811fc7b0)
Location: kernel/bpf/bpf_lru_list.c:607
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff811fc7b0-ffffffff811fc8d8: bpf_lru_populate (STB_GLOBAL)
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
