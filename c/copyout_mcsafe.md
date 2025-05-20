# Function: <code>copyout_mcsafe</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int copyout_mcsafe(void *to, const void *from, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c6050)
Location: lib/iov_iter.c:577
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
```
**Symbols:**

```
ffffffff814c6050-ffffffff814c6083: copyout_mcsafe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int copyout_mcsafe(void *to, const void *from, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814da810)
Location: lib/iov_iter.c:621
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
```
**Symbols:**

```
ffffffff814da810-ffffffff814da843: copyout_mcsafe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int copyout_mcsafe(void *to, const void *from, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81506180)
Location: lib/iov_iter.c:622
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
```
**Symbols:**

```
ffffffff81506180-ffffffff815061b4: copyout_mcsafe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int copyout_mcsafe(void *to, const void *from, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815241b0)
Location: lib/iov_iter.c:622
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
```
**Symbols:**

```
ffffffff815241b0-ffffffff815241e4: copyout_mcsafe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int copyout_mcsafe(void *to, const void *from, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81586e30)
Location: lib/iov_iter.c:640
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
```
**Symbols:**

```
ffffffff81586e30-ffffffff81586e64: copyout_mcsafe (STB_LOCAL)
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
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int copyout_mcsafe(void *to, const void *from, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d1780)
Location: lib/iov_iter.c:622
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
```
**Symbols:**

```
c0000000007d1780-c0000000007d18c4: copyout_mcsafe (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int copyout_mcsafe(void *to, const void *from, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151c790)
Location: lib/iov_iter.c:622
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
```
**Symbols:**

```
ffffffff8151c790-ffffffff8151c7c4: copyout_mcsafe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int copyout_mcsafe(void *to, const void *from, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150ca80)
Location: lib/iov_iter.c:622
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
```
**Symbols:**

```
ffffffff8150ca80-ffffffff8150cab4: copyout_mcsafe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int copyout_mcsafe(void *to, const void *from, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81518820)
Location: lib/iov_iter.c:622
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
```
**Symbols:**

```
ffffffff81518820-ffffffff81518854: copyout_mcsafe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int copyout_mcsafe(void *to, const void *from, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81531fe0)
Location: lib/iov_iter.c:622
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
```
**Symbols:**

```
ffffffff81531fe0-ffffffff81532014: copyout_mcsafe (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
