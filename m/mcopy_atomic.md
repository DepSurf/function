# Function: <code>mcopy_atomic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t mcopy_atomic(struct mm_struct *dst_mm, long unsigned int dst_start, long unsigned int src_start, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff81207800)
Location: mm/userfaultfd.c:298
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81207800-ffffffff81207d40: mcopy_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t mcopy_atomic(struct mm_struct *dst_mm, long unsigned int dst_start, long unsigned int src_start, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff8122d0d0)
Location: mm/userfaultfd.c:297
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff8122d0d0-ffffffff8122d6b0: mcopy_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t mcopy_atomic(struct mm_struct *dst_mm, long unsigned int dst_start, long unsigned int src_start, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff8123f5f0)
Location: mm/userfaultfd.c:297
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff8123f5f0-ffffffff8123fbec: mcopy_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t mcopy_atomic(struct mm_struct *dst_mm, long unsigned int dst_start, long unsigned int src_start, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff8124af50)
Location: mm/userfaultfd.c:550
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff8124af50-ffffffff8124b9f9: mcopy_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t mcopy_atomic(struct mm_struct *dst_mm, long unsigned int dst_start, long unsigned int src_start, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff8126b1f0)
Location: mm/userfaultfd.c:566
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff8126b1f0-ffffffff8126bd4b: mcopy_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t mcopy_atomic(struct mm_struct *dst_mm, long unsigned int dst_start, long unsigned int src_start, long unsigned int len, bool *mmap_changing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff8128fbc0)
Location: mm/userfaultfd.c:575
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff8128fbc0-ffffffff8129082e: mcopy_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t mcopy_atomic(struct mm_struct *dst_mm, long unsigned int dst_start, long unsigned int src_start, long unsigned int len, bool *mmap_changing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff812a4ae0)
Location: mm/userfaultfd.c:605
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff812a4ae0-ffffffff812a5809: mcopy_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t mcopy_atomic(struct mm_struct *dst_mm, long unsigned int dst_start, long unsigned int src_start, long unsigned int len, bool *mmap_changing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/userfaultfd.c (0)
Location: mm/userfaultfd.c:602
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff812c1441-ffffffff812c1470: mcopy_atomic.cold (STB_LOCAL)
ffffffff812c00a0-ffffffff812c0f00: mcopy_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t mcopy_atomic(struct mm_struct *dst_mm, long unsigned int dst_start, long unsigned int src_start, long unsigned int len, bool *mmap_changing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff812d1ff0)
Location: mm/userfaultfd.c:602
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff812d1ff0-ffffffff812d2e4a: mcopy_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t mcopy_atomic(struct mm_struct *dst_mm, long unsigned int dst_start, long unsigned int src_start, long unsigned int len, bool *mmap_changing, __u64 mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff81308350)
Location: mm/userfaultfd.c:625
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_copy
```
**Symbols:**

```
ffffffff81308350-ffffffff81308c67: mcopy_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t mcopy_atomic(struct mm_struct *dst_mm, long unsigned int dst_start, long unsigned int src_start, long unsigned int len, bool *mmap_changing, __u64 mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff813140e0)
Location: mm/userfaultfd.c:625
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_copy
```
**Symbols:**

```
ffffffff813140e0-ffffffff81314a53: mcopy_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t mcopy_atomic(struct mm_struct *dst_mm, long unsigned int dst_start, long unsigned int src_start, long unsigned int len, bool *mmap_changing, __u64 mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff8131a290)
Location: mm/userfaultfd.c:626
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_copy
```
**Symbols:**

```
ffffffff8131a290-ffffffff8131ac05: mcopy_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t mcopy_atomic(struct mm_struct *dst_mm, long unsigned int dst_start, long unsigned int src_start, long unsigned int len, atomic_t *mmap_changing, __u64 mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff813671a0)
Location: mm/userfaultfd.c:651
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_copy
```
**Symbols:**

```
ffffffff813671a0-ffffffff81367ac1: mcopy_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t mcopy_atomic(struct mm_struct *dst_mm, long unsigned int dst_start, long unsigned int src_start, long unsigned int len, atomic_t *mmap_changing, __u64 mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff813e47c0)
Location: mm/userfaultfd.c:684
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_copy
```
**Symbols:**

```
ffffffff813e47c0-ffffffff813e51db: mcopy_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t mcopy_atomic(struct mm_struct *dst_mm, long unsigned int dst_start, long unsigned int src_start, long unsigned int len, atomic_t *mmap_changing, __u64 mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff8146c060)
Location: mm/userfaultfd.c:705
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_copy
```
**Symbols:**

```
ffffffff8146c060-ffffffff8146cca9: mcopy_atomic (STB_GLOBAL)
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
ssize_t mcopy_atomic(struct mm_struct *dst_mm, long unsigned int dst_start, long unsigned int src_start, long unsigned int len, bool *mmap_changing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffff800010378308)
Location: mm/userfaultfd.c:602
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffff800010378308-ffff800010378a60: mcopy_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t mcopy_atomic(struct mm_struct *dst_mm, long unsigned int dst_start, long unsigned int src_start, long unsigned int len, bool *mmap_changing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (c0563644)
Location: mm/userfaultfd.c:602
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
c0563644-c0563ec4: mcopy_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t mcopy_atomic(struct mm_struct *dst_mm, long unsigned int dst_start, long unsigned int src_start, long unsigned int len, bool *mmap_changing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (c00000000046a550)
Location: mm/userfaultfd.c:602
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
c00000000046a550-c00000000046b6f4: mcopy_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t mcopy_atomic(struct mm_struct *dst_mm, long unsigned int dst_start, long unsigned int src_start, long unsigned int len, bool *mmap_changing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffe00024faa0)
Location: mm/userfaultfd.c:602
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffe00024faa0-ffffffe0002503ba: mcopy_atomic (STB_GLOBAL)
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
ssize_t mcopy_atomic(struct mm_struct *dst_mm, long unsigned int dst_start, long unsigned int src_start, long unsigned int len, bool *mmap_changing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff812ca5d0)
Location: mm/userfaultfd.c:602
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff812ca5d0-ffffffff812cb42a: mcopy_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t mcopy_atomic(struct mm_struct *dst_mm, long unsigned int dst_start, long unsigned int src_start, long unsigned int len, bool *mmap_changing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff812bb610)
Location: mm/userfaultfd.c:602
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff812bb610-ffffffff812bc339: mcopy_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t mcopy_atomic(struct mm_struct *dst_mm, long unsigned int dst_start, long unsigned int src_start, long unsigned int len, bool *mmap_changing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff812c83e0)
Location: mm/userfaultfd.c:602
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff812c83e0-ffffffff812c923a: mcopy_atomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t mcopy_atomic(struct mm_struct *dst_mm, long unsigned int dst_start, long unsigned int src_start, long unsigned int len, bool *mmap_changing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff812d90f0)
Location: mm/userfaultfd.c:602
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff812d90f0-ffffffff812d9f18: mcopy_atomic (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool *mmap_changing</code>
</li>
</ul>
</details>
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
<code>__u64 mode</code>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>bool *mmap_changing</code> ➡️ <code>atomic_t *mmap_changing</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
