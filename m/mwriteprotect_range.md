# Function: <code>mwriteprotect_range</code>

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
int mwriteprotect_range(struct mm_struct *dst_mm, long unsigned int start, long unsigned int len, bool enable_wp, bool *mmap_changing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff81308ff0)
Location: mm/userfaultfd.c:639
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_writeprotect
```
**Symbols:**

```
ffffffff81308ff0-ffffffff81309103: mwriteprotect_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mwriteprotect_range(struct mm_struct *dst_mm, long unsigned int start, long unsigned int len, bool enable_wp, bool *mmap_changing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff81314e30)
Location: mm/userfaultfd.c:639
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_writeprotect
```
**Symbols:**

```
ffffffff81314e30-ffffffff81314f7e: mwriteprotect_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mwriteprotect_range(struct mm_struct *dst_mm, long unsigned int start, long unsigned int len, bool enable_wp, bool *mmap_changing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff8131b570)
Location: mm/userfaultfd.c:648
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_writeprotect
```
**Symbols:**

```
ffffffff8131b570-ffffffff8131b6bb: mwriteprotect_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mwriteprotect_range(struct mm_struct *dst_mm, long unsigned int start, long unsigned int len, bool enable_wp, atomic_t *mmap_changing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff81368840)
Location: mm/userfaultfd.c:673
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_writeprotect
```
**Symbols:**

```
ffffffff81368840-ffffffff81368987: mwriteprotect_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mwriteprotect_range(struct mm_struct *dst_mm, long unsigned int start, long unsigned int len, bool enable_wp, atomic_t *mmap_changing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff813e6150)
Location: mm/userfaultfd.c:723
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_writeprotect
```
**Symbols:**

```
ffffffff813e6150-ffffffff813e62f0: mwriteprotect_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mwriteprotect_range(struct mm_struct *dst_mm, long unsigned int start, long unsigned int len, bool enable_wp, atomic_t *mmap_changing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff8146dc10)
Location: mm/userfaultfd.c:744
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_writeprotect
```
**Symbols:**

```
ffffffff8146dc10-ffffffff8146ddcc: mwriteprotect_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mwriteprotect_range(struct mm_struct *dst_mm, long unsigned int start, long unsigned int len, bool enable_wp, atomic_t *mmap_changing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff814a2610)
Location: mm/userfaultfd.c:734
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_writeprotect
```
**Symbols:**

```
ffffffff814a2610-ffffffff814a2815: mwriteprotect_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mwriteprotect_range(struct mm_struct *dst_mm, long unsigned int start, long unsigned int len, bool enable_wp, atomic_t *mmap_changing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff814d26d0)
Location: mm/userfaultfd.c:796
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_writeprotect
```
**Symbols:**

```
ffffffff814d26d0-ffffffff814d28d4: mwriteprotect_range (STB_GLOBAL)
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
