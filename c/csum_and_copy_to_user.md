# Function: <code>csum_and_copy_to_user</code>

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
__wsum csum_and_copy_to_user(const void *src, void *dst, int len, __wsum isum, int *errp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff815fd2b0)
Location: arch/x86/lib/csum-wrappers_64.c:85
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
```
**Symbols:**

```
ffffffff815fd2b0-ffffffff815fd376: csum_and_copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__wsum csum_and_copy_to_user(const void *src, void *dst, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81621fb0)
Location: arch/x86/lib/csum-wrappers_64.c:49
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
```
**Symbols:**

```
ffffffff81621fb0-ffffffff81622024: csum_and_copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__wsum csum_and_copy_to_user(const void *src, void *dst, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff816058c0)
Location: arch/x86/lib/csum-wrappers_64.c:49
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
```
**Symbols:**

```
ffffffff816058c0-ffffffff81605917: csum_and_copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__wsum csum_and_copy_to_user(const void *src, void *dst, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff816741b0)
Location: arch/x86/lib/csum-wrappers_64.c:49
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
```
**Symbols:**

```
ffffffff816741b0-ffffffff81674207: csum_and_copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__wsum csum_and_copy_to_user(const void *src, void *dst, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff8178e8d0)
Location: arch/x86/lib/csum-wrappers_64.c:48
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
```
**Symbols:**

```
ffffffff8178e8d0-ffffffff8178e930: csum_and_copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__wsum csum_and_copy_to_user(const void *src, void *dst, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff8204c200)
Location: arch/x86/lib/csum-wrappers_64.c:48
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
```
**Symbols:**

```
ffffffff8204c200-ffffffff8204c260: csum_and_copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__wsum csum_and_copy_to_user(const void *src, void *dst, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff820cab00)
Location: arch/x86/lib/csum-wrappers_64.c:48
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
```
**Symbols:**

```
ffffffff820cab00-ffffffff820cab6d: csum_and_copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__wsum csum_and_copy_to_user(const void *src, void *dst, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff821a5340)
Location: arch/x86/lib/csum-wrappers_64.c:44
Inline: False
Direct callers:
  - net/core/datagram.c:csum_and_copy_to_iter
  - net/core/datagram.c:csum_and_copy_to_iter
```
**Symbols:**

```
ffffffff821a5340-ffffffff821a53ad: csum_and_copy_to_user (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (ffff800010632760)
Location: include/net/checksum.h:40
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
```
**Symbols:**

```
ffff80001062e6b0-ffff80001062e8b4: csum_and_copy_to_user.constprop.0 (STB_LOCAL)
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
In lib/iov_iter.c (c07d8910)
Location: include/net/checksum.h:40
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__wsum csum_and_copy_to_user(const void *src, void *dst, int len, __wsum sum, int *err_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/lib/checksum_wrappers.c (c0000000000a9da0)
Location: arch/powerpc/lib/checksum_wrappers.c:57
Inline: False
Direct callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
```
**Symbols:**

```
c0000000000a9da0-c0000000000a9f44: csum_and_copy_to_user (STB_GLOBAL)
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
In lib/iov_iter.c (ffffffe000460cbc)
Location: include/net/checksum.h:40
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
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
