# Function: <code>pipe_get_pages</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81462f0b)
Location: lib/iov_iter.c:908
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81465133)
Location: lib/iov_iter.c:1035
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814910b3)
Location: lib/iov_iter.c:1037
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c9fef)
Location: lib/iov_iter.c:1167
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages
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
In lib/iov_iter.c (ffffffff814ded1e)
Location: lib/iov_iter.c:1239
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages
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
In lib/iov_iter.c (ffffffff8150a994)
Location: lib/iov_iter.c:1253
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages
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
In lib/iov_iter.c (ffffffff815289a4)
Location: lib/iov_iter.c:1253
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages
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
In lib/iov_iter.c (ffffffff815889b9)
Location: lib/iov_iter.c:1290
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages
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
In lib/iov_iter.c (ffffffff815a8393)
Location: lib/iov_iter.c:1297
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages
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
In lib/iov_iter.c (ffffffff815acebf)
Location: lib/iov_iter.c:1429
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages
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
In lib/iov_iter.c (ffffffff81616096)
Location: lib/iov_iter.c:1341
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t pipe_get_pages(struct iov_iter *i, struct page **pages, size_t maxsize, unsigned int maxpages, size_t *start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816e1f70)
Location: lib/iov_iter.c:1393
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_get_pages
```
**Symbols:**

```
ffffffff816e1f70-ffffffff816e2133: pipe_get_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t pipe_get_pages(struct iov_iter *i, struct page ***pages, size_t maxsize, unsigned int maxpages, size_t *start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff817d2750)
Location: lib/iov_iter.c:1312
Inline: False
Direct callers:
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
```
**Symbols:**

```
ffffffff817d2750-ffffffff817d2939: pipe_get_pages (STB_LOCAL)
```
</details>
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
In lib/iov_iter.c (ffff800010633328)
Location: lib/iov_iter.c:1253
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages
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
In lib/iov_iter.c (c07d9850)
Location: lib/iov_iter.c:1253
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages
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
In lib/iov_iter.c (c0000000007d7f9c)
Location: lib/iov_iter.c:1253
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages
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
In lib/iov_iter.c (ffffffe00046130e)
Location: lib/iov_iter.c:1253
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages
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
In lib/iov_iter.c (ffffffff81520f84)
Location: lib/iov_iter.c:1253
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages
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
In lib/iov_iter.c (ffffffff81511274)
Location: lib/iov_iter.c:1253
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages
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
In lib/iov_iter.c (ffffffff8151d014)
Location: lib/iov_iter.c:1253
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages
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
In lib/iov_iter.c (ffffffff81536884)
Location: lib/iov_iter.c:1253
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct page **pages</code> ➡️ <code>struct page ***pages</code>
</li>
</ul>
</details>
</li>
</ul>
