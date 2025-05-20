# Function: <code>__iov_iter_get_pages_alloc</code>

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
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t __iov_iter_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, unsigned int maxpages, size_t *start, unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:1432
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc2
  - lib/iov_iter.c:iov_iter_get_pages2
```
**Symbols:**

```
ffffffff817d2950-ffffffff817d2db0: __iov_iter_get_pages_alloc (STB_LOCAL)
ffffffff820780a1-ffffffff82078104: __iov_iter_get_pages_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t __iov_iter_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, unsigned int maxpages, size_t *start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:1083
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_get_pages2
```
**Symbols:**

```
ffffffff818133c0-ffffffff818137bb: __iov_iter_get_pages_alloc (STB_LOCAL)
ffffffff820f86d9-ffffffff820f872a: __iov_iter_get_pages_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t __iov_iter_get_pages_alloc(struct iov_iter *i, struct page ***pages, size_t maxsize, unsigned int maxpages, size_t *start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:980
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_get_pages2
```
**Symbols:**

```
ffffffff81858f70-ffffffff81859397: __iov_iter_get_pages_alloc (STB_LOCAL)
ffffffff821d6345-ffffffff821d6381: __iov_iter_get_pages_alloc.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int gup_flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
