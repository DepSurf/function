# Function: <code>prealloc_lru_pop</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81194cc3)
Location: kernel/bpf/hashtab.c:108
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct htab_elem *prealloc_lru_pop(struct bpf_htab *htab, void *key, u32 hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8119a590)
Location: kernel/bpf/hashtab.c:118
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff8119a590-ffffffff8119a5d6: prealloc_lru_pop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct htab_elem *prealloc_lru_pop(struct bpf_htab *htab, void *key, u32 hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811a9da0)
Location: kernel/bpf/hashtab.c:123
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff811a9da0-ffffffff811a9de9: prealloc_lru_pop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct htab_elem *prealloc_lru_pop(struct bpf_htab *htab, void *key, u32 hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811c1340)
Location: kernel/bpf/hashtab.c:123
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff811c1340-ffffffff811c1387: prealloc_lru_pop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct htab_elem *prealloc_lru_pop(struct bpf_htab *htab, void *key, u32 hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811d2ba0)
Location: kernel/bpf/hashtab.c:127
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff811d2ba0-ffffffff811d2be7: prealloc_lru_pop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct htab_elem *prealloc_lru_pop(struct bpf_htab *htab, void *key, u32 hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811e72f0)
Location: kernel/bpf/hashtab.c:119
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff811e72f0-ffffffff811e7337: prealloc_lru_pop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct htab_elem *prealloc_lru_pop(struct bpf_htab *htab, void *key, u32 hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f3a50)
Location: kernel/bpf/hashtab.c:119
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff811f3a50-ffffffff811f3a97: prealloc_lru_pop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct htab_elem *prealloc_lru_pop(struct bpf_htab *htab, void *key, u32 hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81217270)
Location: kernel/bpf/hashtab.c:234
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff81217270-ffffffff812172b7: prealloc_lru_pop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct htab_elem *prealloc_lru_pop(struct bpf_htab *htab, void *key, u32 hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81219530)
Location: kernel/bpf/hashtab.c:261
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff81219530-ffffffff81219577: prealloc_lru_pop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct htab_elem *prealloc_lru_pop(struct bpf_htab *htab, void *key, u32 hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121cf30)
Location: kernel/bpf/hashtab.c:261
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff8121cf30-ffffffff8121cf77: prealloc_lru_pop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct htab_elem *prealloc_lru_pop(struct bpf_htab *htab, void *key, u32 hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81255780)
Location: kernel/bpf/hashtab.c:287
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff81255780-ffffffff81255811: prealloc_lru_pop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct htab_elem *prealloc_lru_pop(struct bpf_htab *htab, void *key, u32 hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8129c410)
Location: kernel/bpf/hashtab.c:307
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff8129c410-ffffffff8129c461: prealloc_lru_pop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct htab_elem *prealloc_lru_pop(struct bpf_htab *htab, void *key, u32 hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812f87b0)
Location: kernel/bpf/hashtab.c:287
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff812f87b0-ffffffff812f8815: prealloc_lru_pop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct htab_elem *prealloc_lru_pop(struct bpf_htab *htab, void *key, u32 hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff813268b0)
Location: kernel/bpf/hashtab.c:298
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff813268b0-ffffffff81326915: prealloc_lru_pop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct htab_elem *prealloc_lru_pop(struct bpf_htab *htab, void *key, u32 hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8134aef0)
Location: kernel/bpf/hashtab.c:302
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff8134aef0-ffffffff8134af60: prealloc_lru_pop (STB_LOCAL)
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
struct htab_elem *prealloc_lru_pop(struct bpf_htab *htab, void *key, u32 hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffff800010277dd8)
Location: kernel/bpf/hashtab.c:119
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffff800010277dd8-ffff800010277e4c: prealloc_lru_pop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct htab_elem *prealloc_lru_pop(struct bpf_htab *htab, void *key, u32 hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c04aa1f4)
Location: kernel/bpf/hashtab.c:119
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
c04aa1f4-c04aa244: prealloc_lru_pop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct htab_elem *prealloc_lru_pop(struct bpf_htab *htab, void *key, u32 hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c000000000320210)
Location: kernel/bpf/hashtab.c:119
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
c000000000320210-c0000000003202b0: prealloc_lru_pop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffe0001b18ac)
Location: kernel/bpf/hashtab.c:119
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
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
struct htab_elem *prealloc_lru_pop(struct bpf_htab *htab, void *key, u32 hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811ec070)
Location: kernel/bpf/hashtab.c:119
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff811ec070-ffffffff811ec0b7: prealloc_lru_pop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct htab_elem *prealloc_lru_pop(struct bpf_htab *htab, void *key, u32 hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811dee00)
Location: kernel/bpf/hashtab.c:119
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff811dee00-ffffffff811dee47: prealloc_lru_pop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct htab_elem *prealloc_lru_pop(struct bpf_htab *htab, void *key, u32 hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811e9e40)
Location: kernel/bpf/hashtab.c:119
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff811e9e40-ffffffff811e9e87: prealloc_lru_pop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct htab_elem *prealloc_lru_pop(struct bpf_htab *htab, void *key, u32 hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f8210)
Location: kernel/bpf/hashtab.c:119
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff811f8210-ffffffff811f8257: prealloc_lru_pop (STB_LOCAL)
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
