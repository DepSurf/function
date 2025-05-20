# Function: <code>pipe_zero</code>

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
In lib/iov_iter.c (ffffffff81461715)
Location: lib/iov_iter.c:674
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
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
In lib/iov_iter.c (ffffffff81466e44)
Location: lib/iov_iter.c:733
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
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
In lib/iov_iter.c (ffffffff81492c64)
Location: lib/iov_iter.c:735
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
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
In lib/iov_iter.c (ffffffff814c80cf)
Location: lib/iov_iter.c:865
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
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
In lib/iov_iter.c (ffffffff814dca31)
Location: lib/iov_iter.c:911
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
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
In lib/iov_iter.c (ffffffff81508377)
Location: lib/iov_iter.c:925
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
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
In lib/iov_iter.c (ffffffff81526497)
Location: lib/iov_iter.c:925
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t pipe_zero(size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81587770)
Location: lib/iov_iter.c:946
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_zero
```
**Symbols:**

```
ffffffff81587770-ffffffff81587872: pipe_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t pipe_zero(size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a5170)
Location: lib/iov_iter.c:953
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_zero
```
**Symbols:**

```
ffffffff815a5170-ffffffff815a5272: pipe_zero (STB_LOCAL)
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
In lib/iov_iter.c (ffffffff815afe88)
Location: lib/iov_iter.c:1023
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
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
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:869
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
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
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:921
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
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
In lib/iov_iter.c (ffffffff817d4fa2)
Location: lib/iov_iter.c:770
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
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
In lib/iov_iter.c (ffff8000106305ec)
Location: lib/iov_iter.c:925
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
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
In lib/iov_iter.c (c07d6f58)
Location: lib/iov_iter.c:925
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
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
In lib/iov_iter.c (c0000000007d4620)
Location: lib/iov_iter.c:925
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
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
In lib/iov_iter.c (ffffffe00045f6a0)
Location: lib/iov_iter.c:925
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
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
In lib/iov_iter.c (ffffffff8151ea77)
Location: lib/iov_iter.c:925
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
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
In lib/iov_iter.c (ffffffff8150ed67)
Location: lib/iov_iter.c:925
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
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
In lib/iov_iter.c (ffffffff8151ab07)
Location: lib/iov_iter.c:925
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
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
In lib/iov_iter.c (ffffffff81534337)
Location: lib/iov_iter.c:925
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
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
