# Function: <code>__copy_user_flushcache</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int __copy_user_flushcache(void *dst, const void *src, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff818fd7a0)
Location: arch/x86/lib/usercopy_64.c:106
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff818fd7a0-ffffffff818fd888: __copy_user_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int __copy_user_flushcache(void *dst, const void *src, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81985290)
Location: arch/x86/lib/usercopy_64.c:106
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff81985290-ffffffff81985378: __copy_user_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int __copy_user_flushcache(void *dst, const void *src, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff819e17e0)
Location: arch/x86/lib/usercopy_64.c:126
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff819e17e0-ffffffff819e18c6: __copy_user_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __copy_user_flushcache(void *dst, const void *src, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a1c7a0)
Location: arch/x86/lib/usercopy_64.c:126
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff81a1c7a0-ffffffff81a1c886: __copy_user_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __copy_user_flushcache(void *dst, const void *src, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a8c3d0)
Location: arch/x86/lib/usercopy_64.c:107
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff81a8c3d0-ffffffff81a8c4b6: __copy_user_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __copy_user_flushcache(void *dst, const void *src, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81ac3690)
Location: arch/x86/lib/usercopy_64.c:107
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff81ac3690-ffffffff81ac3776: __copy_user_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __copy_user_flushcache(void *dst, const void *src, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff815ffbe0)
Location: arch/x86/lib/usercopy_64.c:108
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff815ffbe0-ffffffff815ffc78: __copy_user_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __copy_user_flushcache(void *dst, const void *src, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81624ad0)
Location: arch/x86/lib/usercopy_64.c:87
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff81624ad0-ffffffff81624b68: __copy_user_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __copy_user_flushcache(void *dst, const void *src, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81608480)
Location: arch/x86/lib/usercopy_64.c:87
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff81608480-ffffffff8160851b: __copy_user_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __copy_user_flushcache(void *dst, const void *src, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff816770c0)
Location: arch/x86/lib/usercopy_64.c:87
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff816770c0-ffffffff8167715b: __copy_user_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __copy_user_flushcache(void *dst, const void *src, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff817920d0)
Location: arch/x86/lib/usercopy_64.c:85
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff817920d0-ffffffff8179218b: __copy_user_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __copy_user_flushcache(void *dst, const void *src, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff8204fe90)
Location: arch/x86/lib/usercopy_64.c:45
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff8204fe90-ffffffff8204ff4b: __copy_user_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __copy_user_flushcache(void *dst, const void *src, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff820ce3e0)
Location: arch/x86/lib/usercopy_64.c:46
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff820ce3e0-ffffffff820ce49b: __copy_user_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __copy_user_flushcache(void *dst, const void *src, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff821a8bf0)
Location: arch/x86/lib/usercopy_64.c:46
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff821a8bf0-ffffffff821a8cab: __copy_user_flushcache (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long unsigned int __copy_user_flushcache(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/lib/uaccess_flushcache.c (ffff800010d835e8)
Location: arch/arm64/lib/uaccess_flushcache.c:28
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffff800010d835e8-ffff800010d8373c: __copy_user_flushcache (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int __copy_user_flushcache(void *dst, const void *src, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a624e0)
Location: arch/x86/lib/usercopy_64.c:107
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff81a624e0-ffffffff81a625c6: __copy_user_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __copy_user_flushcache(void *dst, const void *src, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a1f550)
Location: arch/x86/lib/usercopy_64.c:107
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff81a1f550-ffffffff81a1f636: __copy_user_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __copy_user_flushcache(void *dst, const void *src, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81ace8d0)
Location: arch/x86/lib/usercopy_64.c:107
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff81ace8d0-ffffffff81ace9b6: __copy_user_flushcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __copy_user_flushcache(void *dst, const void *src, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81adade0)
Location: arch/x86/lib/usercopy_64.c:107
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
```
**Symbols:**

```
ffffffff81adade0-ffffffff81adaec6: __copy_user_flushcache (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *to</code>
</li>
<li>
<b>Param added. </b>
<code>const void *from</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int n</code>
</li>
<li>
<b>Param removed. </b>
<code>void *dst</code>
</li>
<li>
<b>Param removed. </b>
<code>const void *src</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int size</code>
</li>
<li>
<b>Return type changed. </b>
<code>long int</code> ➡️ <code>long unsigned int</code>
</li>
</ul>
</details>
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
