# Function: <code>csum_and_copy_from_user</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__wsum csum_and_copy_from_user(const void *src, void *dst, int len, __wsum isum, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff815fd1c0)
Location: arch/x86/lib/csum-wrappers_64.c:24
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
**Symbols:**

```
ffffffff815fd1c0-ffffffff815fd2a8: csum_and_copy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__wsum csum_and_copy_from_user(const void *src, void *dst, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81622030)
Location: arch/x86/lib/csum-wrappers_64.c:24
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
**Symbols:**

```
ffffffff81622030-ffffffff816220a4: csum_and_copy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__wsum csum_and_copy_from_user(const void *src, void *dst, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81605920)
Location: arch/x86/lib/csum-wrappers_64.c:24
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
**Symbols:**

```
ffffffff81605920-ffffffff81605977: csum_and_copy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__wsum csum_and_copy_from_user(const void *src, void *dst, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81674210)
Location: arch/x86/lib/csum-wrappers_64.c:24
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_from_iter
```
**Symbols:**

```
ffffffff81674210-ffffffff81674267: csum_and_copy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__wsum csum_and_copy_from_user(const void *src, void *dst, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff8178e870)
Location: arch/x86/lib/csum-wrappers_64.c:24
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_from_iter
```
**Symbols:**

```
ffffffff8178e870-ffffffff8178e8d0: csum_and_copy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__wsum csum_and_copy_from_user(const void *src, void *dst, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff8204c190)
Location: arch/x86/lib/csum-wrappers_64.c:24
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
**Symbols:**

```
ffffffff8204c190-ffffffff8204c1f0: csum_and_copy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__wsum csum_and_copy_from_user(const void *src, void *dst, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff820caa80)
Location: arch/x86/lib/csum-wrappers_64.c:24
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
**Symbols:**

```
ffffffff820caa80-ffffffff820caaed: csum_and_copy_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__wsum csum_and_copy_from_user(const void *src, void *dst, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff821a52c0)
Location: arch/x86/lib/csum-wrappers_64.c:22
Inline: False
Direct callers:
  - net/core/skbuff.c:csum_and_copy_from_iter_full
  - net/core/skbuff.c:csum_and_copy_from_iter_full
```
**Symbols:**

```
ffffffff821a52c0-ffffffff821a532d: csum_and_copy_from_user (STB_GLOBAL)
```
</details>
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
In lib/iov_iter.c (ffff8000106300a0)
Location: include/net/checksum.h:26
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
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
In lib/iov_iter.c (c07d6a48)
Location: include/net/checksum.h:26
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__wsum csum_and_copy_from_user(const void *src, void *dst, int len, __wsum sum, int *err_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/lib/checksum_wrappers.c (c0000000000a9f50)
Location: arch/powerpc/lib/checksum_wrappers.c:14
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
**Symbols:**

```
c0000000000a9f50-c0000000000aa148: csum_and_copy_from_user (STB_GLOBAL)
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
In lib/iov_iter.c (ffffffe00045f280)
Location: include/net/checksum.h:26
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
</details>
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
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>__wsum isum</code>
</li>
<li>
<b>Param removed. </b>
<code>int *errp</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
