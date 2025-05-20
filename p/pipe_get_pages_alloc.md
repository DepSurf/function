# Function: <code>pipe_get_pages_alloc</code>

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
In lib/iov_iter.c (ffffffff81460015)
Location: lib/iov_iter.c:974
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
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
In lib/iov_iter.c (ffffffff81468921)
Location: lib/iov_iter.c:1098
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
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
In lib/iov_iter.c (ffffffff81494bd1)
Location: lib/iov_iter.c:1100
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
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
In lib/iov_iter.c (ffffffff814c5dbd)
Location: lib/iov_iter.c:1230
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
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
In lib/iov_iter.c (ffffffff814da5d3)
Location: lib/iov_iter.c:1305
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
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
In lib/iov_iter.c (ffffffff81505df9)
Location: lib/iov_iter.c:1321
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
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
In lib/iov_iter.c (ffffffff81523dd9)
Location: lib/iov_iter.c:1321
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
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
In lib/iov_iter.c (ffffffff81587162)
Location: lib/iov_iter.c:1357
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
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
In lib/iov_iter.c (ffffffff815a4942)
Location: lib/iov_iter.c:1364
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
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
In lib/iov_iter.c (ffffffff815ae0b3)
Location: lib/iov_iter.c:1568
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t pipe_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, size_t *start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816155d0)
Location: lib/iov_iter.c:1519
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
**Symbols:**

```
ffffffff816155d0-ffffffff816157cf: pipe_get_pages_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t pipe_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, size_t *start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816e2140)
Location: lib/iov_iter.c:1569
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
**Symbols:**

```
ffffffff816e2140-ffffffff816e2374: pipe_get_pages_alloc (STB_LOCAL)
```
</details>
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
In lib/iov_iter.c (ffff80001062dca4)
Location: lib/iov_iter.c:1321
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
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
In lib/iov_iter.c (c07d4d0c)
Location: lib/iov_iter.c:1321
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
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
In lib/iov_iter.c (c0000000007d12e0)
Location: lib/iov_iter.c:1321
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
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
In lib/iov_iter.c (ffffffe00045d902)
Location: lib/iov_iter.c:1321
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
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
In lib/iov_iter.c (ffffffff8151c3b9)
Location: lib/iov_iter.c:1321
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
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
In lib/iov_iter.c (ffffffff8150c6a9)
Location: lib/iov_iter.c:1321
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
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
In lib/iov_iter.c (ffffffff81518449)
Location: lib/iov_iter.c:1321
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
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
In lib/iov_iter.c (ffffffff81531cc9)
Location: lib/iov_iter.c:1321
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
