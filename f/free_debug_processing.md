# Function: <code>free_debug_processing</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct kmem_cache_node *free_debug_processing(struct kmem_cache *s, struct page *page, void *head, void *tail, int bulk_cnt, long unsigned int addr, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811e9b30)
Location: mm/slub.c:1069
Inline: False
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff811e9b30-ffffffff811e9e16: free_debug_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int free_debug_processing(struct kmem_cache *s, struct page *page, void *head, void *tail, int bulk_cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81209130)
Location: mm/slub.c:1137
Inline: False
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff81209130-ffffffff81209478: free_debug_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int free_debug_processing(struct kmem_cache *s, struct page *page, void *head, void *tail, int bulk_cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121b1b0)
Location: mm/slub.c:1136
Inline: False
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff8121b1b0-ffffffff8121b4ed: free_debug_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int free_debug_processing(struct kmem_cache *s, struct page *page, void *head, void *tail, int bulk_cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81226be0)
Location: mm/slub.c:1138
Inline: False
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff81226be0-ffffffff81226f11: free_debug_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int free_debug_processing(struct kmem_cache *s, struct page *page, void *head, void *tail, int bulk_cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81241c10)
Location: mm/slub.c:1173
Inline: False
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff81241c10-ffffffff81241f48: free_debug_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int free_debug_processing(struct kmem_cache *s, struct page *page, void *head, void *tail, int bulk_cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1161
Inline: False
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff812678c0-ffffffff81267ae6: free_debug_processing (STB_LOCAL)
ffffffff8126b088-ffffffff8126b1a2: free_debug_processing.cold.96 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int free_debug_processing(struct kmem_cache *s, struct page *page, void *head, void *tail, int bulk_cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1176
Inline: False
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff8127c780-ffffffff8127c9a6: free_debug_processing (STB_LOCAL)
ffffffff8127f94c-ffffffff8127fa66: free_debug_processing.cold.99 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int free_debug_processing(struct kmem_cache *s, struct page *page, void *head, void *tail, int bulk_cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1167
Inline: False
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff81298350-ffffffff81298562: free_debug_processing (STB_LOCAL)
ffffffff8129b85f-ffffffff8129b9c3: free_debug_processing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int free_debug_processing(struct kmem_cache *s, struct page *page, void *head, void *tail, int bulk_cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1168
Inline: False
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff812a81b0-ffffffff812a83c2: free_debug_processing (STB_LOCAL)
ffffffff812ab6eb-ffffffff812ab84f: free_debug_processing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int free_debug_processing(struct kmem_cache *s, struct page *page, void *head, void *tail, int bulk_cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1213
Inline: False
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff812dd560-ffffffff812dd75d: free_debug_processing (STB_LOCAL)
ffffffff812e015b-ffffffff812e025b: free_debug_processing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int free_debug_processing(struct kmem_cache *s, struct page *page, void *head, void *tail, int bulk_cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1208
Inline: False
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff812e6350-ffffffff812e654d: free_debug_processing (STB_LOCAL)
ffffffff81be9826-ffffffff81be9926: free_debug_processing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int free_debug_processing(struct kmem_cache *s, struct page *page, void *head, void *tail, int bulk_cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1220
Inline: False
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff812edae0-ffffffff812edcdd: free_debug_processing (STB_LOCAL)
ffffffff81bdb89f-ffffffff81bdb99f: free_debug_processing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int free_debug_processing(struct kmem_cache *s, struct page *page, void *head, void *tail, int bulk_cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1344
Inline: False
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff81335ec0-ffffffff813360bd: free_debug_processing (STB_LOCAL)
ffffffff81cc188b-ffffffff81cc198b: free_debug_processing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int free_debug_processing(struct kmem_cache *s, struct slab *slab, void *head, void *tail, int bulk_cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1389
Inline: False
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff813a76f0-ffffffff813a797f: free_debug_processing (STB_LOCAL)
ffffffff81e73d4e-ffffffff81e73e32: free_debug_processing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool free_debug_processing(struct kmem_cache *s, struct slab *slab, void *head, void *tail, int *bulk_cnt, long unsigned int addr, depot_stack_handle_t handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8142b590)
Location: mm/slub.c:2889
Inline: False
Direct callers:
  - mm/slub.c:free_to_partial_list
```
**Symbols:**

```
ffffffff8142b590-ffffffff8142b947: free_debug_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool free_debug_processing(struct kmem_cache *s, struct slab *slab, void *head, void *tail, int *bulk_cnt, long unsigned int addr, depot_stack_handle_t handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81460b00)
Location: mm/slub.c:2899
Inline: False
Direct callers:
  - mm/slub.c:free_to_partial_list
```
**Symbols:**

```
ffffffff81460b00-ffffffff81460eb7: free_debug_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool free_debug_processing(struct kmem_cache *s, struct slab *slab, void *head, void *tail, int *bulk_cnt, long unsigned int addr, depot_stack_handle_t handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81458ac0)
Location: mm/slub.c:3173
Inline: False
Direct callers:
  - mm/slub.c:free_to_partial_list
```
**Symbols:**

```
ffffffff81458ac0-ffffffff81458e77: free_debug_processing (STB_LOCAL)
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
int free_debug_processing(struct kmem_cache *s, struct page *page, void *head, void *tail, int bulk_cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff800010349860)
Location: mm/slub.c:1168
Inline: False
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffff800010349860-ffff800010349c84: free_debug_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int free_debug_processing(struct kmem_cache *s, struct page *page, void *head, void *tail, int bulk_cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c054d940)
Location: mm/slub.c:1168
Inline: False
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
c054d940-c054dd10: free_debug_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int free_debug_processing(struct kmem_cache *s, struct page *page, void *head, void *tail, int bulk_cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c000000000428630)
Location: mm/slub.c:1168
Inline: False
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
c000000000428630-c000000000428ae0: free_debug_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int free_debug_processing(struct kmem_cache *s, struct page *page, void *head, void *tail, int bulk_cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023b496)
Location: mm/slub.c:1168
Inline: False
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffe00023b496-ffffffe00023b7ac: free_debug_processing (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int free_debug_processing(struct kmem_cache *s, struct page *page, void *head, void *tail, int bulk_cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1168
Inline: False
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff812a0790-ffffffff812a09a2: free_debug_processing (STB_LOCAL)
ffffffff812a3ccb-ffffffff812a3e2f: free_debug_processing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int free_debug_processing(struct kmem_cache *s, struct page *page, void *head, void *tail, int bulk_cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1168
Inline: False
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff812922a0-ffffffff812924b2: free_debug_processing (STB_LOCAL)
ffffffff8129579b-ffffffff812958ff: free_debug_processing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int free_debug_processing(struct kmem_cache *s, struct page *page, void *head, void *tail, int bulk_cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1168
Inline: False
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff8129e5a0-ffffffff8129e7b2: free_debug_processing (STB_LOCAL)
ffffffff812a1adb-ffffffff812a1c3f: free_debug_processing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int free_debug_processing(struct kmem_cache *s, struct page *page, void *head, void *tail, int bulk_cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1168
Inline: False
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff812ae610-ffffffff812ae849: free_debug_processing (STB_LOCAL)
ffffffff812b1c8b-ffffffff812b1dfa: free_debug_processing.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int *flags</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct kmem_cache_node *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct slab *slab</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>depot_stack_handle_t handle</code>
</li>
<li>
<b>Param type changed. </b>
<code>int bulk_cnt</code> ➡️ <code>int *bulk_cnt</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
