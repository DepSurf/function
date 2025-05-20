# Function: <code>page_pool_inflight</code>

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
In net/core/page_pool.c (ffffffff819340f5)
Location: net/core/page_pool.c:199
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_safe_to_destroy
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
In net/core/page_pool.c (ffffffff81967638)
Location: net/core/page_pool.c:195
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
s32 page_pool_inflight(struct page_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a3a7a0)
Location: net/core/page_pool.c:265
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_release
```
**Symbols:**

```
ffffffff81a3a7a0-ffffffff81a3a848: page_pool_inflight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
s32 page_pool_inflight(struct page_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a3cc70)
Location: net/core/page_pool.c:267
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_release
```
**Symbols:**

```
ffffffff81a3cc70-ffffffff81a3ccee: page_pool_inflight (STB_LOCAL)
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
In net/core/page_pool.c (ffffffff81a23deb)
Location: net/core/page_pool.c:306
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
In net/core/page_pool.c (ffffffff81ad8493)
Location: net/core/page_pool.c:330
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
In net/core/page_pool.c (ffffffff81c592fc)
Location: net/core/page_pool.c:450
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
In net/core/page_pool.c (ffffffff81e0f280)
Location: net/core/page_pool.c:451
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
In net/core/page_pool.c (ffffffff81e82a40)
Location: net/core/page_pool.c:476
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
s32 page_pool_inflight(const struct page_pool *pool, bool strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81f44960)
Location: net/core/page_pool.c:532
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool_user.c:page_pool_nl_fill
```
**Symbols:**

```
ffffffff81f44960-ffffffff81f449fb: page_pool_inflight (STB_GLOBAL)
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
In net/core/page_pool.c (ffff800010c0cbd0)
Location: net/core/page_pool.c:195
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
In net/core/page_pool.c (c0d252bc)
Location: net/core/page_pool.c:195
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
In net/core/page_pool.c (c000000000cf84fc)
Location: net/core/page_pool.c:195
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
In net/core/page_pool.c (ffffffe000789d0c)
Location: net/core/page_pool.c:195
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
In net/core/page_pool.c (ffffffff81907608)
Location: net/core/page_pool.c:195
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
In net/core/page_pool.c (ffffffff818c1418)
Location: net/core/page_pool.c:195
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
In net/core/page_pool.c (ffffffff81958638)
Location: net/core/page_pool.c:195
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
In net/core/page_pool.c (ffffffff8197a768)
Location: net/core/page_pool.c:195
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
