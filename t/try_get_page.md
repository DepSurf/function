# Function: <code>try_get_page</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124cd1e)
Location: include/linux/mm.h:1014
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In fs/pipe.c (ffffffff812d5418)
Location: include/linux/mm.h:1014
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125b24e)
Location: include/linux/mm.h:1027
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In fs/pipe.c (ffffffff812e6f88)
Location: include/linux/mm.h:1027
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool try_get_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81287660)
Location: include/linux/mm.h:1143
Inline: True
```
```
In fs/pipe.c (ffffffff8131e7f8)
Location: include/linux/mm.h:1143
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
**Symbols:**

```
ffffffff81287660-ffffffff81287684: try_get_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool try_get_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812914a0)
Location: include/linux/mm.h:1185
Inline: True
```
```
In fs/pipe.c (ffffffff81329d58)
Location: include/linux/mm.h:1185
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
**Symbols:**

```
ffffffff812914a0-ffffffff812914c4: try_get_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81297aec)
Location: include/linux/mm.h:1218
Inline: True
```
```
In fs/pipe.c (ffffffff8132fd18)
Location: include/linux/mm.h:1218
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812d852c)
Location: include/linux/mm.h:1222
Inline: True
```
```
In fs/pipe.c (ffffffff8137d4d8)
Location: include/linux/mm.h:1222
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff813fe2a8)
Location: include/linux/mm.h:1179
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81487f08)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814bcde8)
Location: include/linux/mm.h:1415
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814ef298)
Location: include/linux/mm.h:1469
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffff8000102f2100)
Location: include/linux/mm.h:1027
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In fs/pipe.c (ffff80001038fd24)
Location: include/linux/mm.h:1027
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0514a60)
Location: include/linux/mm.h:1027
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In fs/pipe.c (c05766a4)
Location: include/linux/mm.h:1027
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003b8098)
Location: include/linux/mm.h:1027
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In fs/pipe.c (c0000000004872ec)
Location: include/linux/mm.h:1027
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffe000204886)
Location: include/linux/mm.h:1027
Inline: True
```
```
In fs/pipe.c (ffffffe00025f572)
Location: include/linux/mm.h:1027
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125389e)
Location: include/linux/mm.h:1027
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In fs/pipe.c (ffffffff812df568)
Location: include/linux/mm.h:1027
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81246525)
Location: include/linux/mm.h:1027
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In fs/pipe.c (ffffffff812d01a8)
Location: include/linux/mm.h:1027
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125163e)
Location: include/linux/mm.h:1027
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In fs/pipe.c (ffffffff812dd378)
Location: include/linux/mm.h:1027
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81260fd7)
Location: include/linux/mm.h:1027
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In fs/pipe.c (ffffffff812ee308)
Location: include/linux/mm.h:1027
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
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
</ul>
