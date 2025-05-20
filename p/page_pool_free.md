# Function: <code>page_pool_free</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff8192fc7c)
Location: include/net/page_pool.h:133
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_mem_allocator_rcu_free
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
In net/core/page_pool.c (ffffffff81967734)
Location: net/core/page_pool.c:339
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a3ac91)
Location: net/core/page_pool.c:426
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a3d0ae)
Location: net/core/page_pool.c:476
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
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
In net/core/page_pool.c (ffffffff81a23ec6)
Location: net/core/page_pool.c:509
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
In net/core/page_pool.c (ffffffff81ad856b)
Location: net/core/page_pool.c:618
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
In net/core/page_pool.c (ffffffff81c593f7)
Location: net/core/page_pool.c:752
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
In net/core/page_pool.c (ffffffff81e0f37b)
Location: net/core/page_pool.c:753
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
In net/core/page_pool.c (ffffffff81e82b3b)
Location: net/core/page_pool.c:779
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
</details>
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
In net/core/page_pool.c (ffff800010c0cce4)
Location: net/core/page_pool.c:339
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
In net/core/page_pool.c (c0d25330)
Location: net/core/page_pool.c:339
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
In net/core/page_pool.c (c000000000cf8730)
Location: net/core/page_pool.c:339
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
In net/core/page_pool.c (ffffffe000789d94)
Location: net/core/page_pool.c:339
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
In net/core/page_pool.c (ffffffff81907704)
Location: net/core/page_pool.c:339
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
In net/core/page_pool.c (ffffffff818c1514)
Location: net/core/page_pool.c:339
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
In net/core/page_pool.c (ffffffff81958734)
Location: net/core/page_pool.c:339
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
In net/core/page_pool.c (ffffffff8197a856)
Location: net/core/page_pool.c:339
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
</details>
</li>
</ul>

## Differences
