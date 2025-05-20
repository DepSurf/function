# Function: <code>wake_all_kswapds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81197029)
Location: mm/page_alloc.c:2901
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void wake_all_kswapds(unsigned int order, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a6670)
Location: mm/page_alloc.c:3239
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff811a6670-ffffffff811a6713: wake_all_kswapds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wake_all_kswapds(unsigned int order, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b69e0)
Location: mm/page_alloc.c:3344
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff811b69e0-ffffffff811b6a83: wake_all_kswapds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wake_all_kswapds(unsigned int order, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811be890)
Location: mm/page_alloc.c:3577
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff811be890-ffffffff811be92c: wake_all_kswapds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wake_all_kswapds(unsigned int order, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d3600)
Location: mm/page_alloc.c:3680
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff811d3600-ffffffff811d369c: wake_all_kswapds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f48a0)
Location: mm/page_alloc.c:3812
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff811f48a0-ffffffff811f4951: wake_all_kswapds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81206ce0)
Location: mm/page_alloc.c:3982
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff81206ce0-ffffffff81206d91: wake_all_kswapds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126cd20)
Location: mm/page_alloc.c:4149
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff8126cd20-ffffffff8126cdce: wake_all_kswapds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127bb30)
Location: mm/page_alloc.c:4143
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff8127bb30-ffffffff8127bbde: wake_all_kswapds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812ae050)
Location: mm/page_alloc.c:4258
Inline: False
```
**Symbols:**

```
ffffffff812ae050-ffffffff812ae0fe: wake_all_kswapds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b9a90)
Location: mm/page_alloc.c:4414
Inline: False
```
**Symbols:**

```
ffffffff812b9a90-ffffffff812b9b3e: wake_all_kswapds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bef00)
Location: mm/page_alloc.c:4463
Inline: False
```
**Symbols:**

```
ffffffff812bef00-ffffffff812befae: wake_all_kswapds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81301ae0)
Location: mm/page_alloc.c:4639
Inline: False
```
**Symbols:**

```
ffffffff81301ae0-ffffffff81301b8e: wake_all_kswapds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81369190)
Location: mm/page_alloc.c:4687
Inline: False
```
**Symbols:**

```
ffffffff81369190-ffffffff81369259: wake_all_kswapds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813e4f30)
Location: mm/page_alloc.c:4796
Inline: False
```
**Symbols:**

```
ffffffff813e4f30-ffffffff813e4ff9: wake_all_kswapds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81419e60)
Location: mm/page_alloc.c:3724
Inline: False
```
**Symbols:**

```
ffffffff81419e60-ffffffff81419f29: wake_all_kswapds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff814468f0)
Location: mm/page_alloc.c:3814
Inline: False
```
**Symbols:**

```
ffffffff814468f0-ffffffff814469b9: wake_all_kswapds (STB_LOCAL)
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
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff8000103130d0)
Location: mm/page_alloc.c:4143
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffff8000103130d0-ffff8000103131a8: wake_all_kswapds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c052ddbc)
Location: mm/page_alloc.c:4143
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
c052ddbc-c052de84: wake_all_kswapds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e4580)
Location: mm/page_alloc.c:4143
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
c0000000003e4580-c0000000003e46b4: wake_all_kswapds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021a4a0)
Location: mm/page_alloc.c:4143
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffe00021a4a0-ffffffe00021a54c: wake_all_kswapds (STB_LOCAL)
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
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81274180)
Location: mm/page_alloc.c:4143
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff81274180-ffffffff8127422e: wake_all_kswapds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812660f0)
Location: mm/page_alloc.c:4143
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff812660f0-ffffffff8126619e: wake_all_kswapds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81271f20)
Location: mm/page_alloc.c:4143
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff81271f20-ffffffff81271fce: wake_all_kswapds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81281980)
Location: mm/page_alloc.c:4143
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff81281980-ffffffff81281a2e: wake_all_kswapds (STB_LOCAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp_mask</code>
</li>
<li>
<b>Param reordered. </b>
<code>order, ac</code> ➡️ <code>order, gfp_mask, ac</code>
</li>
</ul>
</details>
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
