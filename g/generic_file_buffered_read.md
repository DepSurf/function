# Function: <code>generic_file_buffered_read</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ceb32)
Location: mm/filemap.c:2053
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_read_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t generic_file_buffered_read(struct kiocb *iocb, struct iov_iter *iter, ssize_t written);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ee280)
Location: mm/filemap.c:2050
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
ffffffff811ee280-ffffffff811eeca7: generic_file_buffered_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t generic_file_buffered_read(struct kiocb *iocb, struct iov_iter *iter, ssize_t written);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ff9e0)
Location: mm/filemap.c:2038
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
ffffffff811ff9e0-ffffffff81200548: generic_file_buffered_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t generic_file_buffered_read(struct kiocb *iocb, struct iov_iter *iter, ssize_t written);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81216af0)
Location: mm/filemap.c:2029
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
ffffffff81216af0-ffffffff812176e3: generic_file_buffered_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t generic_file_buffered_read(struct kiocb *iocb, struct iov_iter *iter, ssize_t written);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81224400)
Location: mm/filemap.c:2009
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
ffffffff81224400-ffffffff81225001: generic_file_buffered_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t generic_file_buffered_read(struct kiocb *iocb, struct iov_iter *iter, ssize_t written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812520e0)
Location: mm/filemap.c:1991
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
ffffffff812520e0-ffffffff81252a18: generic_file_buffered_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t generic_file_buffered_read(struct kiocb *iocb, struct iov_iter *iter, ssize_t written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125c140)
Location: mm/filemap.c:2443
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
ffffffff8125c140-ffffffff8125c5d7: generic_file_buffered_read (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
ssize_t generic_file_buffered_read(struct kiocb *iocb, struct iov_iter *iter, ssize_t written);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b1ab0)
Location: mm/filemap.c:2009
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
ffff8000102b1ab0-ffff8000102b2338: generic_file_buffered_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t generic_file_buffered_read(struct kiocb *iocb, struct iov_iter *iter, ssize_t written);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04de6d0)
Location: mm/filemap.c:2009
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
c04de6d0-c04df27c: generic_file_buffered_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t generic_file_buffered_read(struct kiocb *iocb, struct iov_iter *iter, ssize_t written);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000367830)
Location: mm/filemap.c:2009
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
c000000000367830-c00000000036878c: generic_file_buffered_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t generic_file_buffered_read(struct kiocb *iocb, struct iov_iter *iter, ssize_t written);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d73ce)
Location: mm/filemap.c:2009
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
ffffffe0001d73ce-ffffffe0001d7c68: generic_file_buffered_read (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
ssize_t generic_file_buffered_read(struct kiocb *iocb, struct iov_iter *iter, ssize_t written);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121ca50)
Location: mm/filemap.c:2009
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
ffffffff8121ca50-ffffffff8121d651: generic_file_buffered_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t generic_file_buffered_read(struct kiocb *iocb, struct iov_iter *iter, ssize_t written);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120fc30)
Location: mm/filemap.c:2009
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
ffffffff8120fc30-ffffffff81210827: generic_file_buffered_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t generic_file_buffered_read(struct kiocb *iocb, struct iov_iter *iter, ssize_t written);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121a7f0)
Location: mm/filemap.c:2009
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
ffffffff8121a7f0-ffffffff8121b3f1: generic_file_buffered_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t generic_file_buffered_read(struct kiocb *iocb, struct iov_iter *iter, ssize_t written);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812298c0)
Location: mm/filemap.c:2009
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
```
**Symbols:**

```
ffffffff812298c0-ffffffff8122a45a: generic_file_buffered_read (STB_LOCAL)
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
