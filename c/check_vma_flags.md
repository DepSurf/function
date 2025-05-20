# Function: <code>check_vma_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811bac54)
Location: mm/gup.c:359
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811d53bb)
Location: mm/gup.c:419
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811e53d2)
Location: mm/gup.c:430
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811efa94)
Location: mm/gup.c:513
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81206e5c)
Location: mm/gup.c:538
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81227bd0)
Location: mm/gup.c:554
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
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
In mm/gup.c (ffffffff8123b3c4)
Location: mm/gup.c:571
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
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
In mm/gup.c (ffffffff8124c8cc)
Location: mm/gup.c:687
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
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
In mm/gup.c (ffffffff8125adfc)
Location: mm/gup.c:686
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812895ba)
Location: mm/gup.c:923
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8129328e)
Location: mm/gup.c:880
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81298c26)
Location: mm/gup.c:965
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int check_vma_flags(struct vm_area_struct *vma, long unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812d72c0)
Location: mm/gup.c:991
Inline: False
Direct callers:
  - mm/gup.c:faultin_vma_page_range
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff812d72c0-ffffffff812d7422: check_vma_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int check_vma_flags(struct vm_area_struct *vma, long unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81336e60)
Location: mm/gup.c:1009
Inline: False
Direct callers:
  - mm/gup.c:faultin_vma_page_range
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff81336e60-ffffffff81336ffd: check_vma_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int check_vma_flags(struct vm_area_struct *vma, long unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813ae370)
Location: mm/gup.c:963
Inline: False
Direct callers:
  - mm/gup.c:faultin_vma_page_range
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff813ae370-ffffffff813ae4f2: check_vma_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int check_vma_flags(struct vm_area_struct *vma, long unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e27d0)
Location: mm/gup.c:1037
Inline: False
Direct callers:
  - mm/gup.c:faultin_vma_page_range
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff813e27d0-ffffffff813e2950: check_vma_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int check_vma_flags(struct vm_area_struct *vma, long unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8140d000)
Location: mm/gup.c:1032
Inline: False
Direct callers:
  - mm/gup.c:faultin_vma_page_range
  - mm/gup.c:__get_user_pages
```
**Symbols:**

```
ffffffff8140d000-ffffffff8140d190: check_vma_flags (STB_LOCAL)
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
In mm/gup.c (ffff8000102f2560)
Location: mm/gup.c:686
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
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
In mm/gup.c (c0514754)
Location: mm/gup.c:686
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
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
In mm/gup.c (c0000000003b8b04)
Location: mm/gup.c:686
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
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
In mm/gup.c (ffffffe000204b0a)
Location: mm/gup.c:686
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
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
In mm/gup.c (ffffffff8125344c)
Location: mm/gup.c:686
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
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
In mm/gup.c (ffffffff81246129)
Location: mm/gup.c:686
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
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
In mm/gup.c (ffffffff812511ec)
Location: mm/gup.c:686
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
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
In mm/gup.c (ffffffff81260b6c)
Location: mm/gup.c:686
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
