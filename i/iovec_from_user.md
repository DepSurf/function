# Function: <code>iovec_from_user</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct iovec *iovec_from_user(const struct iovec *uvec, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec *fast_iov, bool compat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a8d30)
Location: lib/iov_iter.c:1705
Inline: True
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - lib/iov_iter.c:__import_iovec
```
**Symbols:**

```
ffffffff815a8d30-ffffffff815a8e47: iovec_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct iovec *iovec_from_user(const struct iovec *uvec, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec *fast_iov, bool compat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (ffffffff815b3a9e)
Location: lib/iov_iter.c:1993
Inline: True
Inline callers:
  - lib/iov_iter.c:__import_iovec
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - lib/iov_iter.c:__import_iovec
```
**Symbols:**

```
ffffffff815ab030-ffffffff815ab1ba: iovec_from_user.part.0 (STB_LOCAL)
ffffffff815b3a50-ffffffff815b3a78: iovec_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct iovec *iovec_from_user(const struct iovec *uvec, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec *fast_iov, bool compat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (ffffffff81619c0e)
Location: lib/iov_iter.c:1851
Inline: True
Inline callers:
  - lib/iov_iter.c:__import_iovec
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - lib/iov_iter.c:__import_iovec
```
**Symbols:**

```
ffffffff81614940-ffffffff81614aca: iovec_from_user.part.0 (STB_LOCAL)
ffffffff81619bc0-ffffffff81619be8: iovec_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct iovec *iovec_from_user(const struct iovec *uvec, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec *fast_iov, bool compat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (ffffffff816e70ae)
Location: lib/iov_iter.c:1900
Inline: True
Inline callers:
  - lib/iov_iter.c:__import_iovec
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - lib/iov_iter.c:__import_iovec
```
**Symbols:**

```
ffffffff816e1620-ffffffff816e17b3: iovec_from_user.part.0 (STB_LOCAL)
ffffffff816e7040-ffffffff816e7086: iovec_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct iovec *iovec_from_user(const struct iovec *uvec, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec *fast_iov, bool compat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (ffffffff817d68ae)
Location: lib/iov_iter.c:1752
Inline: True
Inline callers:
  - lib/iov_iter.c:__import_iovec
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - lib/iov_iter.c:__import_iovec
```
**Symbols:**

```
ffffffff817d1c10-ffffffff817d1da5: iovec_from_user.part.0 (STB_LOCAL)
ffffffff817d6830-ffffffff817d6876: iovec_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct iovec *iovec_from_user(const struct iovec *uvec, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec *fast_iov, bool compat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (ffffffff8181586c)
Location: lib/iov_iter.c:1384
Inline: True
Inline callers:
  - lib/iov_iter.c:__import_iovec
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - lib/iov_iter.c:__import_iovec
```
**Symbols:**

```
ffffffff81810a80-ffffffff81810b43: iovec_from_user.part.0 (STB_LOCAL)
ffffffff81815750-ffffffff81815796: iovec_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct iovec *iovec_from_user(const struct iovec *uvec, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec *fast_iov, bool compat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (ffffffff8185a9bc)
Location: lib/iov_iter.c:1209
Inline: True
Inline callers:
  - lib/iov_iter.c:__import_iovec
Direct callers:
  - mm/process_vm_access.c:process_vm_rw
  - lib/iov_iter.c:__import_iovec
```
**Symbols:**

```
ffffffff81856eb0-ffffffff81856f73: iovec_from_user.part.0 (STB_LOCAL)
ffffffff8185a930-ffffffff8185a976: iovec_from_user (STB_GLOBAL)
```
</details>
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
