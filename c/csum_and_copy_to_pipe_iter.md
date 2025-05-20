# Function: <code>csum_and_copy_to_pipe_iter</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814de5df)
Location: lib/iov_iter.c:571
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
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
In lib/iov_iter.c (ffffffff8150a1dc)
Location: lib/iov_iter.c:572
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
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
In lib/iov_iter.c (ffffffff81528300)
Location: lib/iov_iter.c:572
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t csum_and_copy_to_pipe_iter(const void *addr, size_t bytes, __wsum *csum, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81587490)
Location: lib/iov_iter.c:587
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
```
**Symbols:**

```
ffffffff81587490-ffffffff81587617: csum_and_copy_to_pipe_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t csum_and_copy_to_pipe_iter(const void *addr, size_t bytes, struct csum_state *csstate, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a4e80)
Location: lib/iov_iter.c:594
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
```
**Symbols:**

```
ffffffff815a4e80-ffffffff815a501c: csum_and_copy_to_pipe_iter (STB_LOCAL)
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
In lib/iov_iter.c (ffffffff815b325b)
Location: lib/iov_iter.c:615
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
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
In lib/iov_iter.c (ffffffff816195bf)
Location: lib/iov_iter.c:585
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
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
In lib/iov_iter.c (ffffffff816e698e)
Location: lib/iov_iter.c:630
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
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
In lib/iov_iter.c (ffffffff817d6262)
Location: lib/iov_iter.c:489
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
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
In lib/iov_iter.c (ffff800010632898)
Location: lib/iov_iter.c:572
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
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
In lib/iov_iter.c (c07d8af4)
Location: lib/iov_iter.c:572
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
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
In lib/iov_iter.c (c0000000007d5fe0)
Location: lib/iov_iter.c:572
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
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
In lib/iov_iter.c (ffffffe000460e22)
Location: lib/iov_iter.c:572
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
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
In lib/iov_iter.c (ffffffff815208e0)
Location: lib/iov_iter.c:572
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
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
In lib/iov_iter.c (ffffffff81510bd0)
Location: lib/iov_iter.c:572
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
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
In lib/iov_iter.c (ffffffff8151c970)
Location: lib/iov_iter.c:572
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
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
In lib/iov_iter.c (ffffffff815361cb)
Location: lib/iov_iter.c:572
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct csum_state *csstate</code>
</li>
<li>
<b>Param removed. </b>
<code>__wsum *csum</code>
</li>
</ul>
</details>
</li>
</ul>
