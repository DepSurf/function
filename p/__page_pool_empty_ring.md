# Function: <code>__page_pool_empty_ring</code>

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
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __page_pool_empty_ring(struct page_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:267
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_destroy
  - net/core/page_pool.c:__page_pool_destroy_rcu
```
**Symbols:**

```
ffffffff818bda80-ffffffff818bdb6b: __page_pool_empty_ring (STB_LOCAL)
ffffffff818be01b-ffffffff818be038: __page_pool_empty_ring.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __page_pool_empty_ring(struct page_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:267
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_destroy
  - net/core/page_pool.c:__page_pool_destroy_rcu
```
**Symbols:**

```
ffffffff818e4e60-ffffffff818e4f4b: __page_pool_empty_ring (STB_LOCAL)
ffffffff818e53fb-ffffffff818e5418: __page_pool_empty_ring.cold.16 (STB_LOCAL)
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
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:333
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_request_shutdown
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
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:324
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:324
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
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
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:324
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
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
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:324
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
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
In net/core/page_pool.c (ffffffe000789c56)
Location: net/core/page_pool.c:324
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
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
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:324
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
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
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:324
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
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
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:324
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
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
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:324
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
