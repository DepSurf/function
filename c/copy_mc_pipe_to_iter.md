# Function: <code>copy_mc_pipe_to_iter</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t copy_mc_pipe_to_iter(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a4d20)
Location: lib/iov_iter.c:671
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_mc_to_iter
```
**Symbols:**

```
ffffffff815a4d20-ffffffff815a4e7d: copy_mc_pipe_to_iter (STB_LOCAL)
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
In lib/iov_iter.c (ffffffff815aba27)
Location: lib/iov_iter.c:694
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_mc_to_iter
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
In lib/iov_iter.c (ffffffff8161829f)
Location: lib/iov_iter.c:641
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_mc_to_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t copy_mc_pipe_to_iter(const void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816e1d70)
Location: lib/iov_iter.c:686
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_mc_to_iter
```
**Symbols:**

```
ffffffff816e1d70-ffffffff816e1f69: copy_mc_pipe_to_iter (STB_LOCAL)
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
In lib/iov_iter.c (ffffffff817d5c2b)
Location: lib/iov_iter.c:548
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_mc_to_iter
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
</ul>
