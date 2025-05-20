# Function: <code>memcpy_mcsafe_to_page</code>

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
long unsigned int memcpy_mcsafe_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c5a00)
Location: lib/iov_iter.c:586
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
```
**Symbols:**

```
ffffffff814c5a00-ffffffff814c5a5e: memcpy_mcsafe_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int memcpy_mcsafe_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814da1a0)
Location: lib/iov_iter.c:630
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
```
**Symbols:**

```
ffffffff814da1a0-ffffffff814da1fe: memcpy_mcsafe_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int memcpy_mcsafe_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815059b0)
Location: lib/iov_iter.c:631
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
```
**Symbols:**

```
ffffffff815059b0-ffffffff81505a11: memcpy_mcsafe_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int memcpy_mcsafe_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81523960)
Location: lib/iov_iter.c:631
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
```
**Symbols:**

```
ffffffff81523960-ffffffff815239c1: memcpy_mcsafe_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int memcpy_mcsafe_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81587a90)
Location: lib/iov_iter.c:649
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:copy_pipe_to_iter_mcsafe
```
**Symbols:**

```
ffffffff81587a90-ffffffff81587af1: memcpy_mcsafe_to_page (STB_LOCAL)
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
long unsigned int memcpy_mcsafe_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d0bf0)
Location: lib/iov_iter.c:631
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
```
**Symbols:**

```
c0000000007d0bf0-c0000000007d0c6c: memcpy_mcsafe_to_page (STB_LOCAL)
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
long unsigned int memcpy_mcsafe_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151bf40)
Location: lib/iov_iter.c:631
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
```
**Symbols:**

```
ffffffff8151bf40-ffffffff8151bfa1: memcpy_mcsafe_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int memcpy_mcsafe_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150c230)
Location: lib/iov_iter.c:631
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
```
**Symbols:**

```
ffffffff8150c230-ffffffff8150c291: memcpy_mcsafe_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int memcpy_mcsafe_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81517fd0)
Location: lib/iov_iter.c:631
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
```
**Symbols:**

```
ffffffff81517fd0-ffffffff81518031: memcpy_mcsafe_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int memcpy_mcsafe_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81531790)
Location: lib/iov_iter.c:631
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
```
**Symbols:**

```
ffffffff81531790-ffffffff81531808: memcpy_mcsafe_to_page (STB_LOCAL)
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
