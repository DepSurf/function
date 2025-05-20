# Function: <code>page_pool_release</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int page_pool_release(struct page_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:371
Inline: False
```
**Symbols:**

```
ffffffff819674a0-ffffffff81967781: page_pool_release (STB_LOCAL)
ffffffff81967abc-ffffffff81967ad8: page_pool_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int page_pool_release(struct page_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a3abb0)
Location: net/core/page_pool.c:467
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_release_retry
```
**Symbols:**

```
ffffffff81a3abb0-ffffffff81a3acd4: page_pool_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int page_pool_release(struct page_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a3cfd0)
Location: net/core/page_pool.c:517
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_release_retry
```
**Symbols:**

```
ffffffff81a3cfd0-ffffffff81a3d0f1: page_pool_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int page_pool_release(struct page_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:550
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_release_retry
```
**Symbols:**

```
ffffffff81a23c30-ffffffff81a23f13: page_pool_release (STB_LOCAL)
ffffffff81c23aba-ffffffff81c23ad6: page_pool_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int page_pool_release(struct page_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:659
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_release_retry
```
**Symbols:**

```
ffffffff81ad82d0-ffffffff81ad85cc: page_pool_release (STB_LOCAL)
ffffffff81d37863-ffffffff81d3787f: page_pool_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int page_pool_release(struct page_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:796
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_release_retry
```
**Symbols:**

```
ffffffff81c590f0-ffffffff81c5948b: page_pool_release (STB_LOCAL)
ffffffff81f0421f-ffffffff81f0423c: page_pool_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int page_pool_release(struct page_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81e0f060)
Location: net/core/page_pool.c:797
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_release_retry
```
**Symbols:**

```
ffffffff81e0f060-ffffffff81e0f40a: page_pool_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int page_pool_release(struct page_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81e82820)
Location: net/core/page_pool.c:823
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_release_retry
```
**Symbols:**

```
ffffffff81e82820-ffffffff81e82bd6: page_pool_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int page_pool_release(struct page_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81f44a10)
Location: net/core/page_pool.c:891
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_release_retry
```
**Symbols:**

```
ffffffff81f44a10-ffffffff81f44c18: page_pool_release (STB_LOCAL)
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
int page_pool_release(struct page_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffff800010c0ca00)
Location: net/core/page_pool.c:371
Inline: False
```
**Symbols:**

```
ffff800010c0ca00-ffff800010c0cd60: page_pool_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int page_pool_release(struct page_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (c0d25164)
Location: net/core/page_pool.c:371
Inline: False
```
**Symbols:**

```
c0d25164-c0d25428: page_pool_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int page_pool_release(struct page_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (c000000000cf8330)
Location: net/core/page_pool.c:371
Inline: False
```
**Symbols:**

```
c000000000cf8330-c000000000cf87cc: page_pool_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int page_pool_release(struct page_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffe000789bdc)
Location: net/core/page_pool.c:371
Inline: False
```
**Symbols:**

```
ffffffe000789bdc-ffffffe000789e42: page_pool_release (STB_LOCAL)
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
int page_pool_release(struct page_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:371
Inline: False
```
**Symbols:**

```
ffffffff81907470-ffffffff81907751: page_pool_release (STB_LOCAL)
ffffffff81907a8c-ffffffff81907aa8: page_pool_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int page_pool_release(struct page_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:371
Inline: False
```
**Symbols:**

```
ffffffff818c1280-ffffffff818c1561: page_pool_release (STB_LOCAL)
ffffffff818c189c-ffffffff818c18b8: page_pool_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int page_pool_release(struct page_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:371
Inline: False
```
**Symbols:**

```
ffffffff819584a0-ffffffff81958781: page_pool_release (STB_LOCAL)
ffffffff81958abc-ffffffff81958ad8: page_pool_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int page_pool_release(struct page_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:371
Inline: False
```
**Symbols:**

```
ffffffff8197a5d0-ffffffff8197a8c2: page_pool_release (STB_LOCAL)
ffffffff8197abfc-ffffffff8197ac18: page_pool_release.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
