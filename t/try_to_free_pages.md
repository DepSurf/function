# Function: <code>try_to_free_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int try_to_free_pages(struct zonelist *zonelist, int order, gfp_t gfp_mask, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811a5090)
Location: mm/vmscan.c:2826
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - fs/buffer.c:free_more_memory
```
**Symbols:**

```
ffffffff811a5090-ffffffff811a5210: try_to_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int try_to_free_pages(struct zonelist *zonelist, int order, gfp_t gfp_mask, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811bbb40)
Location: mm/vmscan.c:2941
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - fs/buffer.c:free_more_memory
```
**Symbols:**

```
ffffffff811bbb40-ffffffff811bbccf: try_to_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int try_to_free_pages(struct zonelist *zonelist, int order, gfp_t gfp_mask, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811cc200)
Location: mm/vmscan.c:2950
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - fs/buffer.c:free_more_memory
```
**Symbols:**

```
ffffffff811cc200-ffffffff811cc38f: try_to_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int try_to_free_pages(struct zonelist *zonelist, int order, gfp_t gfp_mask, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811d4da0)
Location: mm/vmscan.c:3017
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - fs/buffer.c:free_more_memory
```
**Symbols:**

```
ffffffff811d4da0-ffffffff811d4f61: try_to_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int try_to_free_pages(struct zonelist *zonelist, int order, gfp_t gfp_mask, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811ea2d0)
Location: mm/vmscan.c:3041
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff811ea2d0-ffffffff811ea496: try_to_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int try_to_free_pages(struct zonelist *zonelist, int order, gfp_t gfp_mask, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8120ba90)
Location: mm/vmscan.c:3050
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff8120ba90-ffffffff8120bc53: try_to_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int try_to_free_pages(struct zonelist *zonelist, int order, gfp_t gfp_mask, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8121e770)
Location: mm/vmscan.c:3217
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff8121e770-ffffffff8121e91b: try_to_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int try_to_free_pages(struct zonelist *zonelist, int order, gfp_t gfp_mask, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122de10)
Location: mm/vmscan.c:3178
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff8122de10-ffffffff8122dfd4: try_to_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int try_to_free_pages(struct zonelist *zonelist, int order, gfp_t gfp_mask, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123bfa0)
Location: mm/vmscan.c:3264
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff8123bfa0-ffffffff8123c164: try_to_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int try_to_free_pages(struct zonelist *zonelist, int order, gfp_t gfp_mask, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8126a3e0)
Location: mm/vmscan.c:3238
Inline: False
```
**Symbols:**

```
ffffffff8126a3e0-ffffffff8126a59f: try_to_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int try_to_free_pages(struct zonelist *zonelist, int order, gfp_t gfp_mask, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81274ec0)
Location: mm/vmscan.c:3242
Inline: False
```
**Symbols:**

```
ffffffff81274ec0-ffffffff81275055: try_to_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int try_to_free_pages(struct zonelist *zonelist, int order, gfp_t gfp_mask, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8127a1c0)
Location: mm/vmscan.c:3440
Inline: False
```
**Symbols:**

```
ffffffff8127a1c0-ffffffff8127a361: try_to_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int try_to_free_pages(struct zonelist *zonelist, int order, gfp_t gfp_mask, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b81f0)
Location: mm/vmscan.c:3597
Inline: False
```
**Symbols:**

```
ffffffff812b81f0-ffffffff812b83ba: try_to_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int try_to_free_pages(struct zonelist *zonelist, int order, gfp_t gfp_mask, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81313b50)
Location: mm/vmscan.c:3740
Inline: False
```
**Symbols:**

```
ffffffff81313b50-ffffffff81313d5c: try_to_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int try_to_free_pages(struct zonelist *zonelist, int order, gfp_t gfp_mask, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81387bb0)
Location: mm/vmscan.c:6676
Inline: False
```
**Symbols:**

```
ffffffff81387bb0-ffffffff81387dc5: try_to_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int try_to_free_pages(struct zonelist *zonelist, int order, gfp_t gfp_mask, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813b9eb0)
Location: mm/vmscan.c:7039
Inline: False
```
**Symbols:**

```
ffffffff813b9eb0-ffffffff813ba0bf: try_to_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int try_to_free_pages(struct zonelist *zonelist, int order, gfp_t gfp_mask, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813e2fd0)
Location: mm/vmscan.c:6406
Inline: False
```
**Symbols:**

```
ffffffff813e2fd0-ffffffff813e31df: try_to_free_pages (STB_GLOBAL)
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
long unsigned int try_to_free_pages(struct zonelist *zonelist, int order, gfp_t gfp_mask, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102cd140)
Location: mm/vmscan.c:3264
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffff8000102cd140-ffff8000102cd37c: try_to_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int try_to_free_pages(struct zonelist *zonelist, int order, gfp_t gfp_mask, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f6f80)
Location: mm/vmscan.c:3264
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
c04f6f80-c04f7460: try_to_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int try_to_free_pages(struct zonelist *zonelist, int order, gfp_t gfp_mask, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c00000000038ab10)
Location: mm/vmscan.c:3264
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
c00000000038ab10-c00000000038ad8c: try_to_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int try_to_free_pages(struct zonelist *zonelist, int order, gfp_t gfp_mask, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001eba10)
Location: mm/vmscan.c:3264
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffe0001eba10-ffffffe0001ebbd4: try_to_free_pages (STB_GLOBAL)
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
long unsigned int try_to_free_pages(struct zonelist *zonelist, int order, gfp_t gfp_mask, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812345f0)
Location: mm/vmscan.c:3264
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff812345f0-ffffffff812347b4: try_to_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int try_to_free_pages(struct zonelist *zonelist, int order, gfp_t gfp_mask, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81227660)
Location: mm/vmscan.c:3264
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff81227660-ffffffff81227824: try_to_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int try_to_free_pages(struct zonelist *zonelist, int order, gfp_t gfp_mask, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81232390)
Location: mm/vmscan.c:3264
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff81232390-ffffffff81232554: try_to_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int try_to_free_pages(struct zonelist *zonelist, int order, gfp_t gfp_mask, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812417f0)
Location: mm/vmscan.c:3264
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff812417f0-ffffffff812419e2: try_to_free_pages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
