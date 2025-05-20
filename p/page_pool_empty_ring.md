# Function: <code>page_pool_empty_ring</code>

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
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void page_pool_empty_ring(struct page_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:411
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_release
```
**Symbols:**

```
ffffffff81a3a950-ffffffff81a3aaa6: page_pool_empty_ring (STB_LOCAL)
ffffffff81a3b31e-ffffffff81a3b33b: page_pool_empty_ring.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void page_pool_empty_ring(struct page_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:461
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_release
```
**Symbols:**

```
ffffffff81a3ce70-ffffffff81a3cfc3: page_pool_empty_ring (STB_LOCAL)
ffffffff81c317d6-ffffffff81c317f3: page_pool_empty_ring.cold (STB_LOCAL)
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
In net/core/page_pool.c (ffffffff81a23cce)
Location: net/core/page_pool.c:494
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
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
In net/core/page_pool.c (ffffffff81ad8379)
Location: net/core/page_pool.c:603
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81c59189)
Location: net/core/page_pool.c:737
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81e0f0f9)
Location: net/core/page_pool.c:738
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81e828b9)
Location: net/core/page_pool.c:764
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81f44a7f)
Location: net/core/page_pool.c:838
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
