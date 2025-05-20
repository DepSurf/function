# Function: <code>push_pipe</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t push_pipe(struct iov_iter *i, size_t size, int *idxp, size_t *offp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8145f7d0)
Location: lib/iov_iter.c:468
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_to_iter
```
**Symbols:**

```
ffffffff8145f7d0-ffffffff8145f92e: push_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t push_pipe(struct iov_iter *i, size_t size, int *idxp, size_t *offp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81464ac0)
Location: lib/iov_iter.c:488
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff81464ac0-ffffffff81464c31: push_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t push_pipe(struct iov_iter *i, size_t size, int *idxp, size_t *offp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81490a40)
Location: lib/iov_iter.c:488
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff81490a40-ffffffff81490bb1: push_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t push_pipe(struct iov_iter *i, size_t size, int *idxp, size_t *offp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c57f0)
Location: lib/iov_iter.c:488
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff814c57f0-ffffffff814c5961: push_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t push_pipe(struct iov_iter *i, size_t size, int *idxp, size_t *offp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814d9f90)
Location: lib/iov_iter.c:494
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff814d9f90-ffffffff814da101: push_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t push_pipe(struct iov_iter *i, size_t size, int *idxp, size_t *offp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815057a0)
Location: lib/iov_iter.c:495
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff815057a0-ffffffff81505904: push_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t push_pipe(struct iov_iter *i, size_t size, int *idxp, size_t *offp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81523750)
Location: lib/iov_iter.c:495
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff81523750-ffffffff815238b4: push_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t push_pipe(struct iov_iter *i, size_t size, int *iter_headp, size_t *offp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81586e70)
Location: lib/iov_iter.c:504
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:pipe_zero
  - lib/iov_iter.c:copy_pipe_to_iter_mcsafe
  - lib/iov_iter.c:csum_and_copy_to_pipe_iter
  - lib/iov_iter.c:copy_pipe_to_iter
```
**Symbols:**

```
ffffffff81586e70-ffffffff81586fd2: push_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t push_pipe(struct iov_iter *i, size_t size, int *iter_headp, size_t *offp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a4650)
Location: lib/iov_iter.c:511
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:pipe_zero
  - lib/iov_iter.c:copy_mc_pipe_to_iter
  - lib/iov_iter.c:csum_and_copy_to_pipe_iter
  - lib/iov_iter.c:copy_pipe_to_iter
```
**Symbols:**

```
ffffffff815a4650-ffffffff815a47b2: push_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t push_pipe(struct iov_iter *i, size_t size, int *iter_headp, size_t *offp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815ab520)
Location: lib/iov_iter.c:532
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff815ab520-ffffffff815ab677: push_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t push_pipe(struct iov_iter *i, size_t size, int *iter_headp, size_t *offp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81615460)
Location: lib/iov_iter.c:501
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:pipe_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff81615460-ffffffff816155c3: push_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t push_pipe(struct iov_iter *i, size_t size, int *iter_headp, size_t *offp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816e1aa0)
Location: lib/iov_iter.c:546
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:pipe_get_pages_alloc
  - lib/iov_iter.c:pipe_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_mc_pipe_to_iter
  - lib/iov_iter.c:copy_pipe_to_iter
```
**Symbols:**

```
ffffffff816e1aa0-ffffffff816e1c18: push_pipe (STB_LOCAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
size_t push_pipe(struct iov_iter *i, size_t size, int *idxp, size_t *offp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff80001062d638)
Location: lib/iov_iter.c:495
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffff80001062d638-ffff80001062d80c: push_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t push_pipe(struct iov_iter *i, size_t size, int *idxp, size_t *offp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d426c)
Location: lib/iov_iter.c:495
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
c07d426c-c07d4428: push_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t push_pipe(struct iov_iter *i, size_t size, int *idxp, size_t *offp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d0850)
Location: lib/iov_iter.c:495
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
c0000000007d0850-c0000000007d0aa0: push_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t push_pipe(struct iov_iter *i, size_t size, int *idxp, size_t *offp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe00045d536)
Location: lib/iov_iter.c:495
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffe00045d536-ffffffe00045d676: push_pipe (STB_LOCAL)
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
size_t push_pipe(struct iov_iter *i, size_t size, int *idxp, size_t *offp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151bd30)
Location: lib/iov_iter.c:495
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff8151bd30-ffffffff8151be94: push_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t push_pipe(struct iov_iter *i, size_t size, int *idxp, size_t *offp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150c020)
Location: lib/iov_iter.c:495
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff8150c020-ffffffff8150c184: push_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t push_pipe(struct iov_iter *i, size_t size, int *idxp, size_t *offp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81517dc0)
Location: lib/iov_iter.c:495
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff81517dc0-ffffffff81517f24: push_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t push_pipe(struct iov_iter *i, size_t size, int *idxp, size_t *offp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81531560)
Location: lib/iov_iter.c:495
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff81531560-ffffffff815316c4: push_pipe (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int *iter_headp</code>
</li>
<li>
<b>Param removed. </b>
<code>int *idxp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
