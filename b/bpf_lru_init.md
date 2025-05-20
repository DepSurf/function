# Function: <code>bpf_lru_init</code>

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
int bpf_lru_init(struct bpf_lru *lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void *del_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81196dc0)
Location: kernel/bpf/bpf_lru_list.c:646
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff81196dc0-ffffffff81196f8a: bpf_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bpf_lru_init(struct bpf_lru *lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void *del_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8119e150)
Location: kernel/bpf/bpf_lru_list.c:648
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff8119e150-ffffffff8119e30a: bpf_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bpf_lru_init(struct bpf_lru *lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void *del_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811add60)
Location: kernel/bpf/bpf_lru_list.c:648
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff811add60-ffffffff811adf00: bpf_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bpf_lru_init(struct bpf_lru *lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void *del_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811c52d0)
Location: kernel/bpf/bpf_lru_list.c:648
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff811c52d0-ffffffff811c5473: bpf_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_lru_init(struct bpf_lru *lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void *del_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811d6ed0)
Location: kernel/bpf/bpf_lru_list.c:648
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff811d6ed0-ffffffff811d7073: bpf_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_lru_init(struct bpf_lru *lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void *del_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811eb8c0)
Location: kernel/bpf/bpf_lru_list.c:645
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff811eb8c0-ffffffff811eba4b: bpf_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_lru_init(struct bpf_lru *lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void *del_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811f8020)
Location: kernel/bpf/bpf_lru_list.c:645
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff811f8020-ffffffff811f81ab: bpf_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_lru_init(struct bpf_lru *lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void *del_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121bda0)
Location: kernel/bpf/bpf_lru_list.c:645
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_init
```
**Symbols:**

```
ffffffff8121bda0-ffffffff8121bf2b: bpf_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_lru_init(struct bpf_lru *lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void *del_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121ed20)
Location: kernel/bpf/bpf_lru_list.c:646
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_init
```
**Symbols:**

```
ffffffff8121ed20-ffffffff8121eeab: bpf_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_lru_init(struct bpf_lru *lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void *del_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff812227b0)
Location: kernel/bpf/bpf_lru_list.c:646
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_init
```
**Symbols:**

```
ffffffff812227b0-ffffffff81222936: bpf_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_lru_init(struct bpf_lru *lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void *del_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8125a4c0)
Location: kernel/bpf/bpf_lru_list.c:646
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_init
```
**Symbols:**

```
ffffffff8125a4c0-ffffffff8125a6c9: bpf_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_lru_init(struct bpf_lru *lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void *del_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff812a35a0)
Location: kernel/bpf/bpf_lru_list.c:646
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_init
```
**Symbols:**

```
ffffffff812a35a0-ffffffff812a37b6: bpf_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_lru_init(struct bpf_lru *lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void *del_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81301120)
Location: kernel/bpf/bpf_lru_list.c:646
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_init
```
**Symbols:**

```
ffffffff81301120-ffffffff81301360: bpf_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_lru_init(struct bpf_lru *lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void *del_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8132fc70)
Location: kernel/bpf/bpf_lru_list.c:651
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_init
```
**Symbols:**

```
ffffffff8132fc70-ffffffff8132feb0: bpf_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_lru_init(struct bpf_lru *lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void *del_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81354190)
Location: kernel/bpf/bpf_lru_list.c:651
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_init
```
**Symbols:**

```
ffffffff81354190-ffffffff813543d0: bpf_lru_init (STB_GLOBAL)
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
int bpf_lru_init(struct bpf_lru *lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void *del_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffff80001027d210)
Location: kernel/bpf/bpf_lru_list.c:645
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffff80001027d210-ffff80001027d3a0: bpf_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_lru_init(struct bpf_lru *lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void *del_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (c04aec58)
Location: kernel/bpf/bpf_lru_list.c:645
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
c04aec58-c04aedf0: bpf_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_lru_init(struct bpf_lru *lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void *del_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (c000000000326d20)
Location: kernel/bpf/bpf_lru_list.c:645
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
c000000000326d20-c000000000326f48: bpf_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_lru_init(struct bpf_lru *lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void *del_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffe0001b46ca)
Location: kernel/bpf/bpf_lru_list.c:645
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffe0001b46ca-ffffffe0001b4840: bpf_lru_init (STB_GLOBAL)
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
int bpf_lru_init(struct bpf_lru *lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void *del_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811f0640)
Location: kernel/bpf/bpf_lru_list.c:645
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff811f0640-ffffffff811f07cb: bpf_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_lru_init(struct bpf_lru *lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void *del_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811e3390)
Location: kernel/bpf/bpf_lru_list.c:645
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff811e3390-ffffffff811e351b: bpf_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_lru_init(struct bpf_lru *lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void *del_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811ee410)
Location: kernel/bpf/bpf_lru_list.c:645
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff811ee410-ffffffff811ee59b: bpf_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_lru_init(struct bpf_lru *lru, bool percpu, u32 hash_offset, del_from_htab_func del_from_htab, void *del_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811fc8e0)
Location: kernel/bpf/bpf_lru_list.c:645
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff811fc8e0-ffffffff811fca6b: bpf_lru_init (STB_GLOBAL)
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
