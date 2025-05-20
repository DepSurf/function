# Function: <code>page_pool_init</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff818bd8d4)
Location: net/core/page_pool.c:17
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff818e4c24)
Location: net/core/page_pool.c:17
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff8193446f)
Location: net/core/page_pool.c:21
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff8196709f)
Location: net/core/page_pool.c:24
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int page_pool_init(struct page_pool *pool, const struct page_pool_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a3a3e0)
Location: net/core/page_pool.c:24
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_create
```
**Symbols:**

```
ffffffff81a3a3e0-ffffffff81a3a51a: page_pool_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int page_pool_init(struct page_pool *pool, const struct page_pool_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a3c970)
Location: net/core/page_pool.c:26
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_create
```
**Symbols:**

```
ffffffff81a3c970-ffffffff81a3caaa: page_pool_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a238ce)
Location: net/core/page_pool.c:26
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81ad7efe)
Location: net/core/page_pool.c:29
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int page_pool_init(struct page_pool *pool, const struct page_pool_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81c58c40)
Location: net/core/page_pool.c:136
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_create
```
**Symbols:**

```
ffffffff81c58c40-ffffffff81c58da5: page_pool_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int page_pool_init(struct page_pool *pool, const struct page_pool_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81e0eb30)
Location: net/core/page_pool.c:136
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_create
```
**Symbols:**

```
ffffffff81e0eb30-ffffffff81e0ec95: page_pool_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int page_pool_init(struct page_pool *pool, const struct page_pool_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81e82190)
Location: net/core/page_pool.c:160
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_create
```
**Symbols:**

```
ffffffff81e82190-ffffffff81e8231c: page_pool_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int page_pool_init(struct page_pool *pool, const struct page_pool_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81f43150)
Location: net/core/page_pool.c:173
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_create
```
**Symbols:**

```
ffffffff81f43150-ffffffff81f4330b: page_pool_init (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffff800010c0c738)
Location: net/core/page_pool.c:24
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (c0d24ddc)
Location: net/core/page_pool.c:24
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (c000000000cf7e30)
Location: net/core/page_pool.c:24
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
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
In net/core/page_pool.c (ffffffe000789aea)
Location: net/core/page_pool.c:24
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff8190706f)
Location: net/core/page_pool.c:24
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff818c0e7f)
Location: net/core/page_pool.c:24
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff8195809f)
Location: net/core/page_pool.c:24
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff8197a1af)
Location: net/core/page_pool.c:24
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
