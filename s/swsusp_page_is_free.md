# Function: <code>swsusp_page_is_free</code>

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
In kernel/power/snapshot.c (ffffffff810d054d)
Location: kernel/power/snapshot.c:895
Inline: True
Inline callers:
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:snapshot_write_next
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
In kernel/power/snapshot.c (ffffffff810d7301)
Location: kernel/power/snapshot.c:993
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:get_image_page
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
In kernel/power/snapshot.c (ffffffff810dde88)
Location: kernel/power/snapshot.c:993
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:get_image_page
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
In kernel/power/snapshot.c (ffffffff810dcf86)
Location: kernel/power/snapshot.c:995
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:get_image_page
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
In kernel/power/snapshot.c (ffffffff810e51b1)
Location: kernel/power/snapshot.c:997
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:get_image_page
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
In kernel/power/snapshot.c (ffffffff810ece2c)
Location: kernel/power/snapshot.c:997
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:get_image_page
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
In kernel/power/snapshot.c (ffffffff810f84cc)
Location: kernel/power/snapshot.c:998
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:get_image_page
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
In kernel/power/snapshot.c (ffffffff81100ab3)
Location: kernel/power/snapshot.c:999
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:get_image_page
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
In kernel/power/snapshot.c (ffffffff8110cf13)
Location: kernel/power/snapshot.c:1006
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:get_image_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int swsusp_page_is_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81116550)
Location: kernel/power/snapshot.c:1005
Inline: True
Inline callers:
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - kernel/power/snapshot.c:saveable_page
```
**Symbols:**

```
ffffffff8111823a-ffffffff8111826a: swsusp_page_is_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int swsusp_page_is_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811129d0)
Location: kernel/power/snapshot.c:1039
Inline: True
Inline callers:
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - kernel/power/snapshot.c:saveable_page
```
**Symbols:**

```
ffffffff81bdf6d1-ffffffff81bdf701: swsusp_page_is_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int swsusp_page_is_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81113420)
Location: kernel/power/snapshot.c:1039
Inline: True
Inline callers:
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - kernel/power/snapshot.c:saveable_page
```
**Symbols:**

```
ffffffff81bd16b0-ffffffff81bd16e0: swsusp_page_is_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int swsusp_page_is_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811335c0)
Location: kernel/power/snapshot.c:1032
Inline: True
Inline callers:
  - kernel/power/snapshot.c:get_image_page
```
**Symbols:**

```
ffffffff81caa28b-ffffffff81caa2bb: swsusp_page_is_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int swsusp_page_is_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81155442)
Location: kernel/power/snapshot.c:1036
Inline: True
Inline callers:
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - kernel/power/snapshot.c:saveable_page
```
**Symbols:**

```
ffffffff81e5a665-ffffffff81e5a6a9: swsusp_page_is_free (STB_LOCAL)
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
In kernel/power/snapshot.c (ffffffff81185cdf)
Location: kernel/power/snapshot.c:1036
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:get_image_page
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
In kernel/power/snapshot.c (ffffffff81196eaf)
Location: kernel/power/snapshot.c:1036
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:get_image_page
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
In kernel/power/snapshot.c (ffffffff811a5960)
Location: kernel/power/snapshot.c:1046
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:get_image_page
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
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int swsusp_page_is_free(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (c03bdae0)
Location: kernel/power/snapshot.c:1006
Inline: False
Direct callers:
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:saveable_highmem_page
  - kernel/power/snapshot.c:get_image_page
```
**Symbols:**

```
c03bdae0-c03bdb48: swsusp_page_is_free (STB_LOCAL)
```
</details>
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81105133)
Location: kernel/power/snapshot.c:1005
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:get_image_page
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
In kernel/power/snapshot.c (ffffffff810f63d3)
Location: kernel/power/snapshot.c:1006
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:get_image_page
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
In kernel/power/snapshot.c (ffffffff811033e3)
Location: kernel/power/snapshot.c:1006
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:get_image_page
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
In kernel/power/snapshot.c (ffffffff8110e7d3)
Location: kernel/power/snapshot.c:1006
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:get_image_page
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
</ul>
<b>Arch</b>
<ul>
</ul>
