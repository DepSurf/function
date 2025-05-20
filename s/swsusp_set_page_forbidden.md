# Function: <code>swsusp_set_page_forbidden</code>

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
In kernel/power/snapshot.c (ffffffff810d0379)
Location: kernel/power/snapshot.c:907
Inline: True
Inline callers:
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
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
In kernel/power/snapshot.c (ffffffff810d7265)
Location: kernel/power/snapshot.c:1005
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
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
In kernel/power/snapshot.c (ffffffff810dddf6)
Location: kernel/power/snapshot.c:1005
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
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
In kernel/power/snapshot.c (ffffffff810dcf06)
Location: kernel/power/snapshot.c:1007
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
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
In kernel/power/snapshot.c (ffffffff810e5131)
Location: kernel/power/snapshot.c:1009
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
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
In kernel/power/snapshot.c (ffffffff810ecdac)
Location: kernel/power/snapshot.c:1009
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
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
In kernel/power/snapshot.c (ffffffff810f844c)
Location: kernel/power/snapshot.c:1010
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
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
In kernel/power/snapshot.c (ffffffff81100a2d)
Location: kernel/power/snapshot.c:1011
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
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
In kernel/power/snapshot.c (ffffffff8110ce8d)
Location: kernel/power/snapshot.c:1018
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void swsusp_set_page_forbidden(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811164e5)
Location: kernel/power/snapshot.c:1017
Inline: True
Inline callers:
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - kernel/power/snapshot.c:alloc_image_page
```
**Symbols:**

```
ffffffff811181e4-ffffffff8111820f: swsusp_set_page_forbidden (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void swsusp_set_page_forbidden(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81112965)
Location: kernel/power/snapshot.c:1051
Inline: True
Inline callers:
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - kernel/power/snapshot.c:alloc_image_page
```
**Symbols:**

```
ffffffff81bdf67b-ffffffff81bdf6a6: swsusp_set_page_forbidden (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void swsusp_set_page_forbidden(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811133b5)
Location: kernel/power/snapshot.c:1051
Inline: True
Inline callers:
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - kernel/power/snapshot.c:alloc_image_page
```
**Symbols:**

```
ffffffff81bd1685-ffffffff81bd16b0: swsusp_set_page_forbidden (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void swsusp_set_page_forbidden(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81133555)
Location: kernel/power/snapshot.c:1044
Inline: True
Inline callers:
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - kernel/power/snapshot.c:alloc_image_page
```
**Symbols:**

```
ffffffff81caa260-ffffffff81caa28b: swsusp_set_page_forbidden (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void swsusp_set_page_forbidden(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811553f6)
Location: kernel/power/snapshot.c:1048
Inline: True
Inline callers:
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - kernel/power/snapshot.c:alloc_image_page
```
**Symbols:**

```
ffffffff81e5a6a9-ffffffff81e5a6e4: swsusp_set_page_forbidden (STB_LOCAL)
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
In kernel/power/snapshot.c (ffffffff8118750a)
Location: kernel/power/snapshot.c:1048
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:preallocate_image_memory
  - kernel/power/snapshot.c:get_image_page
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
In kernel/power/snapshot.c (ffffffff8119869a)
Location: kernel/power/snapshot.c:1048
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:preallocate_image_memory
  - kernel/power/snapshot.c:get_image_page
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
In kernel/power/snapshot.c (ffffffff811a751b)
Location: kernel/power/snapshot.c:1058
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:preallocate_image_memory
  - kernel/power/snapshot.c:get_image_page
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
void swsusp_set_page_forbidden(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (c03bdbbc)
Location: kernel/power/snapshot.c:1018
Inline: False
Direct callers:
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
```
**Symbols:**

```
c03bdbbc-c03bdc1c: swsusp_set_page_forbidden (STB_LOCAL)
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
In kernel/power/snapshot.c (ffffffff811050ad)
Location: kernel/power/snapshot.c:1017
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
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
In kernel/power/snapshot.c (ffffffff810f634d)
Location: kernel/power/snapshot.c:1018
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
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
In kernel/power/snapshot.c (ffffffff8110335d)
Location: kernel/power/snapshot.c:1018
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
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
In kernel/power/snapshot.c (ffffffff8110e74d)
Location: kernel/power/snapshot.c:1018
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
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
