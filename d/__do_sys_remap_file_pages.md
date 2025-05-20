# Function: <code>__do_sys_remap_file_pages</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812385b0)
Location: mm/mmap.c:2817
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8124bf70)
Location: mm/mmap.c:2879
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125e3f0)
Location: mm/mmap.c:2885
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126cc00)
Location: mm/mmap.c:2891
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
long int __do_sys_remap_file_pages(long unsigned int start, long unsigned int size, long unsigned int prot, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmap.c (0)
Location: mm/mmap.c:2901
Inline: False
Direct callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
```
**Symbols:**

```
ffffffff8129c970-ffffffff8129cc3b: __do_sys_remap_file_pages (STB_LOCAL)
ffffffff8129d7c7-ffffffff8129d7f4: __do_sys_remap_file_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
long int __do_sys_remap_file_pages(long unsigned int start, long unsigned int size, long unsigned int prot, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmap.c (0)
Location: mm/mmap.c:2964
Inline: False
Direct callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
```
**Symbols:**

```
ffffffff812a7cc0-ffffffff812a7fef: __do_sys_remap_file_pages (STB_LOCAL)
ffffffff81be7a7b-ffffffff81be7aa0: __do_sys_remap_file_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long int __do_sys_remap_file_pages(long unsigned int start, long unsigned int size, long unsigned int prot, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmap.c (0)
Location: mm/mmap.c:2968
Inline: False
Direct callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
```
**Symbols:**

```
ffffffff812ad980-ffffffff812adbd0: __do_sys_remap_file_pages (STB_LOCAL)
ffffffff81bd98dd-ffffffff81bd9902: __do_sys_remap_file_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int __do_sys_remap_file_pages(long unsigned int start, long unsigned int size, long unsigned int prot, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmap.c (0)
Location: mm/mmap.c:2940
Inline: False
Direct callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
```
**Symbols:**

```
ffffffff812ef060-ffffffff812ef33b: __do_sys_remap_file_pages (STB_LOCAL)
ffffffff81cbc907-ffffffff81cbc94a: __do_sys_remap_file_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int __do_sys_remap_file_pages(long unsigned int start, long unsigned int size, long unsigned int prot, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmap.c (0)
Location: mm/mmap.c:2940
Inline: False
Direct callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
```
**Symbols:**

```
ffffffff81352440-ffffffff81352788: __do_sys_remap_file_pages (STB_LOCAL)
ffffffff81e6e4f7-ffffffff81e6e53a: __do_sys_remap_file_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int __do_sys_remap_file_pages(long unsigned int start, long unsigned int size, long unsigned int prot, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmap.c (0)
Location: mm/mmap.c:2811
Inline: False
Direct callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
```
**Symbols:**

```
ffffffff813cc430-ffffffff813cc7ae: __do_sys_remap_file_pages (STB_LOCAL)
ffffffff820643e5-ffffffff820643fa: __do_sys_remap_file_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int __do_sys_remap_file_pages(long unsigned int start, long unsigned int size, long unsigned int prot, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmap.c (0)
Location: mm/mmap.c:2925
Inline: False
Direct callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
```
**Symbols:**

```
ffffffff81400d80-ffffffff8140107a: __do_sys_remap_file_pages (STB_LOCAL)
ffffffff820e3ac3-ffffffff820e3ad8: __do_sys_remap_file_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int __do_sys_remap_file_pages(long unsigned int start, long unsigned int size, long unsigned int prot, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmap.c (0)
Location: mm/mmap.c:3014
Inline: False
Direct callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
```
**Symbols:**

```
ffffffff8142d3c0-ffffffff8142d6b9: __do_sys_remap_file_pages (STB_LOCAL)
ffffffff821c066c-ffffffff821c0681: __do_sys_remap_file_pages.cold (STB_LOCAL)
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
In mm/mmap.c (ffff800010303e64)
Location: mm/mmap.c:2891
Inline: True
Inline callers:
  - mm/mmap.c:__arm64_sys_remap_file_pages
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
In mm/mmap.c (c0522640)
Location: mm/mmap.c:2891
Inline: True
Inline callers:
  - mm/mmap.c:__se_sys_remap_file_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003d0b84)
Location: mm/mmap.c:2891
Inline: True
Inline callers:
  - mm/mmap.c:__se_sys_remap_file_pages
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
In mm/mmap.c (ffffffe0002107be)
Location: mm/mmap.c:2891
Inline: True
Inline callers:
  - mm/mmap.c:__se_sys_remap_file_pages
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81265250)
Location: mm/mmap.c:2891
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81257670)
Location: mm/mmap.c:2891
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81262ff0)
Location: mm/mmap.c:2891
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812729b0)
Location: mm/mmap.c:2891
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
```
</details>
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
