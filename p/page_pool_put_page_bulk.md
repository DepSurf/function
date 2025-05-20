# Function: <code>page_pool_put_page_bulk</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void page_pool_put_page_bulk(struct page_pool *pool, void **data, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a3d230)
Location: net/core/page_pool.c:424
Inline: False
```
**Symbols:**

```
ffffffff81a3d230-ffffffff81a3d529: page_pool_put_page_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void page_pool_put_page_bulk(struct page_pool *pool, void **data, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a24050)
Location: net/core/page_pool.c:457
Inline: False
```
**Symbols:**

```
ffffffff81a24050-ffffffff81a24341: page_pool_put_page_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void page_pool_put_page_bulk(struct page_pool *pool, void **data, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81ad8620)
Location: net/core/page_pool.c:488
Inline: False
```
**Symbols:**

```
ffffffff81ad8620-ffffffff81ad8937: page_pool_put_page_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void page_pool_put_page_bulk(struct page_pool *pool, void **data, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81c59500)
Location: net/core/page_pool.c:613
Inline: False
```
**Symbols:**

```
ffffffff81c59500-ffffffff81c59906: page_pool_put_page_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void page_pool_put_page_bulk(struct page_pool *pool, void **data, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81e0f4e0)
Location: net/core/page_pool.c:614
Inline: False
```
**Symbols:**

```
ffffffff81e0f4e0-ffffffff81e0f8e6: page_pool_put_page_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void page_pool_put_page_bulk(struct page_pool *pool, void **data, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81e82cb0)
Location: net/core/page_pool.c:639
Inline: False
```
**Symbols:**

```
ffffffff81e82cb0-ffffffff81e83127: page_pool_put_page_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void page_pool_put_page_bulk(struct page_pool *pool, void **data, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81f43ab0)
Location: net/core/page_pool.c:714
Inline: False
```
**Symbols:**

```
ffffffff81f43ab0-ffffffff81f43dfa: page_pool_put_page_bulk (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
