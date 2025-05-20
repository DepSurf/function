# Function: <code>alloc_htab_elem</code>

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
struct htab_elem *alloc_htab_elem(struct bpf_htab *htab, void *key, void *value, u32 key_size, u32 hash, bool percpu, bool onallcpus, bool old_elem_exists);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81185f70)
Location: kernel/bpf/hashtab.c:423
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff81185f70-ffffffff811861fa: alloc_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct htab_elem *alloc_htab_elem(struct bpf_htab *htab, void *key, void *value, u32 key_size, u32 hash, bool percpu, bool onallcpus, bool old_elem_exists);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81193550)
Location: kernel/bpf/hashtab.c:573
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff81193550-ffffffff81193722: alloc_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct htab_elem *alloc_htab_elem(struct bpf_htab *htab, void *key, void *value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem *old_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8119a770)
Location: kernel/bpf/hashtab.c:670
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff8119a770-ffffffff8119a98e: alloc_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct htab_elem *alloc_htab_elem(struct bpf_htab *htab, void *key, void *value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem *old_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811a9f60)
Location: kernel/bpf/hashtab.c:702
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff811a9f60-ffffffff811aa182: alloc_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct htab_elem *alloc_htab_elem(struct bpf_htab *htab, void *key, void *value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem *old_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811c1500)
Location: kernel/bpf/hashtab.c:716
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff811c1500-ffffffff811c1718: alloc_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct htab_elem *alloc_htab_elem(struct bpf_htab *htab, void *key, void *value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem *old_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811d2d60)
Location: kernel/bpf/hashtab.c:730
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff811d2d60-ffffffff811d2f78: alloc_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct htab_elem *alloc_htab_elem(struct bpf_htab *htab, void *key, void *value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem *old_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811e74d0)
Location: kernel/bpf/hashtab.c:721
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff811e74d0-ffffffff811e7737: alloc_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct htab_elem *alloc_htab_elem(struct bpf_htab *htab, void *key, void *value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem *old_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f3c30)
Location: kernel/bpf/hashtab.c:721
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff811f3c30-ffffffff811f3e97: alloc_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct htab_elem *alloc_htab_elem(struct bpf_htab *htab, void *key, void *value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem *old_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81217db0)
Location: kernel/bpf/hashtab.c:830
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff81217db0-ffffffff81218051: alloc_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct htab_elem *alloc_htab_elem(struct bpf_htab *htab, void *key, void *value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem *old_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81219f20)
Location: kernel/bpf/hashtab.c:877
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff81219f20-ffffffff8121a1d8: alloc_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct htab_elem *alloc_htab_elem(struct bpf_htab *htab, void *key, void *value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem *old_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121d6f0)
Location: kernel/bpf/hashtab.c:877
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff8121d6f0-ffffffff8121d993: alloc_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct htab_elem *alloc_htab_elem(struct bpf_htab *htab, void *key, void *value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem *old_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812567c0)
Location: kernel/bpf/hashtab.c:919
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff812567c0-ffffffff81256a59: alloc_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct htab_elem *alloc_htab_elem(struct bpf_htab *htab, void *key, void *value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem *old_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8129f120)
Location: kernel/bpf/hashtab.c:938
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff8129f120-ffffffff8129f40c: alloc_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct htab_elem *alloc_htab_elem(struct bpf_htab *htab, void *key, void *value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem *old_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/hashtab.c (0)
Location: kernel/bpf/hashtab.c:965
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff812f9910-ffffffff812f9ba2: alloc_htab_elem (STB_LOCAL)
ffffffff820615f4-ffffffff82061626: alloc_htab_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct htab_elem *alloc_htab_elem(struct bpf_htab *htab, void *key, void *value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem *old_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/hashtab.c (0)
Location: kernel/bpf/hashtab.c:977
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff81327d10-ffffffff81327fdd: alloc_htab_elem (STB_LOCAL)
ffffffff820e0b8f-ffffffff820e0bc1: alloc_htab_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct htab_elem *alloc_htab_elem(struct bpf_htab *htab, void *key, void *value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem *old_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/hashtab.c (0)
Location: kernel/bpf/hashtab.c:994
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff8134c3d0-ffffffff8134c6c2: alloc_htab_elem (STB_LOCAL)
ffffffff821bd34f-ffffffff821bd37f: alloc_htab_elem.cold (STB_LOCAL)
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
struct htab_elem *alloc_htab_elem(struct bpf_htab *htab, void *key, void *value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem *old_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffff8000102782b8)
Location: kernel/bpf/hashtab.c:721
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffff8000102782b8-ffff800010278530: alloc_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct htab_elem *alloc_htab_elem(struct bpf_htab *htab, void *key, void *value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem *old_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c04aa3a8)
Location: kernel/bpf/hashtab.c:721
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
c04aa3a8-c04aa634: alloc_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct htab_elem *alloc_htab_elem(struct bpf_htab *htab, void *key, void *value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem *old_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c000000000320530)
Location: kernel/bpf/hashtab.c:721
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
c000000000320530-c00000000032086c: alloc_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct htab_elem *alloc_htab_elem(struct bpf_htab *htab, void *key, void *value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem *old_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffe0001afaf6)
Location: kernel/bpf/hashtab.c:721
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffe0001afaf6-ffffffe0001afd1c: alloc_htab_elem (STB_LOCAL)
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
struct htab_elem *alloc_htab_elem(struct bpf_htab *htab, void *key, void *value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem *old_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811ec250)
Location: kernel/bpf/hashtab.c:721
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff811ec250-ffffffff811ec4b7: alloc_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct htab_elem *alloc_htab_elem(struct bpf_htab *htab, void *key, void *value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem *old_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811defe0)
Location: kernel/bpf/hashtab.c:721
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff811defe0-ffffffff811df247: alloc_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct htab_elem *alloc_htab_elem(struct bpf_htab *htab, void *key, void *value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem *old_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811ea020)
Location: kernel/bpf/hashtab.c:721
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff811ea020-ffffffff811ea287: alloc_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct htab_elem *alloc_htab_elem(struct bpf_htab *htab, void *key, void *value, u32 key_size, u32 hash, bool percpu, bool onallcpus, struct htab_elem *old_elem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f8400)
Location: kernel/bpf/hashtab.c:721
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff811f8400-ffffffff811f8667: alloc_htab_elem (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct htab_elem *old_elem</code>
</li>
<li>
<b>Param removed. </b>
<code>bool old_elem_exists</code>
</li>
</ul>
</details>
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
