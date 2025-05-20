# Function: <code>get_user_pages_fast_only</code>

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
int get_user_pages_fast_only(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8128b540)
Location: mm/gup.c:2839
Inline: False
Direct callers:
  - kernel/events/core.c:perf_virt_to_phys
```
**Symbols:**

```
ffffffff8128b540-ffffffff8128b560: get_user_pages_fast_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_user_pages_fast_only(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81295390)
Location: mm/gup.c:2632
Inline: False
Direct callers:
  - kernel/events/core.c:perf_virt_to_phys
```
**Symbols:**

```
ffffffff81295390-ffffffff812953b3: get_user_pages_fast_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_user_pages_fast_only(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8129ad10)
Location: mm/gup.c:2698
Inline: False
Direct callers:
  - kernel/events/core.c:perf_virt_to_phys
```
**Symbols:**

```
ffffffff8129ad10-ffffffff8129ad30: get_user_pages_fast_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_user_pages_fast_only(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812db6e0)
Location: mm/gup.c:2793
Inline: False
Direct callers:
  - kernel/events/core.c:perf_virt_to_phys
```
**Symbols:**

```
ffffffff812db6e0-ffffffff812db700: get_user_pages_fast_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_user_pages_fast_only(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8133b3d0)
Location: mm/gup.c:2943
Inline: False
Direct callers:
  - kernel/events/core.c:perf_virt_to_phys
```
**Symbols:**

```
ffffffff8133b3d0-ffffffff8133b3fc: get_user_pages_fast_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_user_pages_fast_only(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813b2f20)
Location: mm/gup.c:2969
Inline: False
Direct callers:
  - kernel/events/core.c:perf_virt_to_phys
```
**Symbols:**

```
ffffffff813b2f20-ffffffff813b2f4c: get_user_pages_fast_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_user_pages_fast_only(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e7bf0)
Location: mm/gup.c:3230
Inline: False
Direct callers:
  - kernel/events/core.c:perf_virt_to_phys
```
**Symbols:**

```
ffffffff813e7bf0-ffffffff813e7c6f: get_user_pages_fast_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_user_pages_fast_only(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81412860)
Location: mm/gup.c:3248
Inline: False
Direct callers:
  - kernel/events/core.c:perf_virt_to_phys
```
**Symbols:**

```
ffffffff81412860-ffffffff814128df: get_user_pages_fast_only (STB_GLOBAL)
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
