# Function: <code>copy_pipe_to_iter_mcsafe</code>

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
In lib/iov_iter.c (ffffffff814c7c44)
Location: lib/iov_iter.c:599
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
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
In lib/iov_iter.c (ffffffff814dc51c)
Location: lib/iov_iter.c:643
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
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
In lib/iov_iter.c (ffffffff81507ea1)
Location: lib/iov_iter.c:644
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
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
In lib/iov_iter.c (ffffffff81525fc1)
Location: lib/iov_iter.c:644
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t copy_pipe_to_iter_mcsafe(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81587b00)
Location: lib/iov_iter.c:662
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
```
**Symbols:**

```
ffffffff81587b00-ffffffff81587c13: copy_pipe_to_iter_mcsafe (STB_LOCAL)
```
</details>
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d2f20)
Location: lib/iov_iter.c:644
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In lib/iov_iter.c (ffffffff8151e5a1)
Location: lib/iov_iter.c:644
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
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
In lib/iov_iter.c (ffffffff8150e891)
Location: lib/iov_iter.c:644
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
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
In lib/iov_iter.c (ffffffff8151a631)
Location: lib/iov_iter.c:644
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
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
In lib/iov_iter.c (ffffffff81533e61)
Location: lib/iov_iter.c:644
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
