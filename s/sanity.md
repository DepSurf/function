# Function: <code>sanity</code>

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
bool sanity(const struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8145f6f0)
Location: lib/iov_iter.c:300
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_to_iter
```
**Symbols:**

```
ffffffff8145f6f0-ffffffff8145f7cc: sanity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool sanity(const struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814649f0)
Location: lib/iov_iter.c:320
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff814649f0-ffffffff81464abd: sanity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool sanity(const struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81490970)
Location: lib/iov_iter.c:320
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff81490970-ffffffff81490a3d: sanity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
bool sanity(const struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:320
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff814c5770-ffffffff814c57ef: sanity (STB_LOCAL)
ffffffff814ca234-ffffffff814ca295: sanity.cold.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
bool sanity(const struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:324
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff814d9f10-ffffffff814d9f8f: sanity (STB_LOCAL)
ffffffff814def5d-ffffffff814defbe: sanity.cold.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool sanity(const struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:325
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff815056a0-ffffffff81505719: sanity (STB_LOCAL)
ffffffff8150ac0b-ffffffff8150ac78: sanity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool sanity(const struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:325
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff815236d0-ffffffff81523749: sanity (STB_LOCAL)
ffffffff81528c30-ffffffff81528c91: sanity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool sanity(const struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:326
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:pipe_zero
  - lib/iov_iter.c:copy_pipe_to_iter_mcsafe
  - lib/iov_iter.c:csum_and_copy_to_pipe_iter
  - lib/iov_iter.c:copy_pipe_to_iter
  - lib/iov_iter.c:copy_page_to_iter_pipe
```
**Symbols:**

```
ffffffff81586cd0-ffffffff81586d4c: sanity (STB_LOCAL)
ffffffff8158c502-ffffffff8158c563: sanity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool sanity(const struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:333
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:pipe_zero
  - lib/iov_iter.c:copy_mc_pipe_to_iter
  - lib/iov_iter.c:csum_and_copy_to_pipe_iter
  - lib/iov_iter.c:copy_pipe_to_iter
  - lib/iov_iter.c:copy_page_to_iter_pipe
```
**Symbols:**

```
ffffffff815a3fa0-ffffffff815a401c: sanity (STB_LOCAL)
ffffffff81bf3f6f-ffffffff81bf3fd0: sanity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool sanity(const struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:375
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff815aaeb0-ffffffff815aaf2c: sanity (STB_LOCAL)
ffffffff81be5dca-ffffffff81be5e2b: sanity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool sanity(const struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:342
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:pipe_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff81614330-ffffffff816143ac: sanity (STB_LOCAL)
ffffffff81cda824-ffffffff81cda885: sanity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool sanity(const struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:340
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:pipe_get_pages_alloc
  - lib/iov_iter.c:pipe_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:copy_mc_pipe_to_iter
  - lib/iov_iter.c:copy_pipe_to_iter
```
**Symbols:**

```
ffffffff816e0d40-ffffffff816e0dda: sanity (STB_LOCAL)
ffffffff81e92e65-ffffffff81e92ec6: sanity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (ffffffff817d1dc0)
Location: lib/iov_iter.c:196
Inline: True
Direct callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:pipe_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:copy_pipe_to_iter
```
**Symbols:**

```
ffffffff817d1dc0-ffffffff817d1eba: sanity.isra.0 (STB_LOCAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
bool sanity(const struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff80001062d538)
Location: lib/iov_iter.c:325
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffff80001062d538-ffff80001062d634: sanity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool sanity(const struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d4150)
Location: lib/iov_iter.c:325
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
c07d4150-c07d426c: sanity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool sanity(const struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d0700)
Location: lib/iov_iter.c:325
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
c0000000007d0700-c0000000007d084c: sanity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool sanity(const struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe00045d470)
Location: lib/iov_iter.c:325
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffe00045d470-ffffffe00045d536: sanity (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
bool sanity(const struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:325
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff8151bcb0-ffffffff8151bd29: sanity (STB_LOCAL)
ffffffff81521210-ffffffff81521271: sanity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
bool sanity(const struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:325
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff8150bfa0-ffffffff8150c019: sanity (STB_LOCAL)
ffffffff81511500-ffffffff81511561: sanity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
bool sanity(const struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:325
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff81517d40-ffffffff81517db9: sanity (STB_LOCAL)
ffffffff8151d2a0-ffffffff8151d301: sanity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool sanity(const struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:325
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff815314e0-ffffffff81531559: sanity (STB_LOCAL)
ffffffff81536b10-ffffffff81536b71: sanity.cold (STB_LOCAL)
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
