# Function: <code>balloon_page_enqueue_one</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void balloon_page_enqueue_one(struct balloon_dev_info *b_dev_info, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff812bfd70)
Location: mm/balloon_compaction.c:14
Inline: True
Direct callers:
  - mm/balloon_compaction.c:balloon_page_enqueue
  - mm/balloon_compaction.c:balloon_page_list_enqueue
```
**Symbols:**

```
ffffffff812bfd70-ffffffff812bfdeb: balloon_page_enqueue_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void balloon_page_enqueue_one(struct balloon_dev_info *b_dev_info, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff812d1cc0)
Location: mm/balloon_compaction.c:14
Inline: True
Direct callers:
  - mm/balloon_compaction.c:balloon_page_enqueue
  - mm/balloon_compaction.c:balloon_page_list_enqueue
```
**Symbols:**

```
ffffffff812d1cc0-ffffffff812d1d3b: balloon_page_enqueue_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void balloon_page_enqueue_one(struct balloon_dev_info *b_dev_info, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff81307900)
Location: mm/balloon_compaction.c:14
Inline: True
Direct callers:
  - mm/balloon_compaction.c:balloon_page_enqueue
  - mm/balloon_compaction.c:balloon_page_list_enqueue
```
**Symbols:**

```
ffffffff81307900-ffffffff8130797b: balloon_page_enqueue_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void balloon_page_enqueue_one(struct balloon_dev_info *b_dev_info, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff81313630)
Location: mm/balloon_compaction.c:14
Inline: True
Direct callers:
  - mm/balloon_compaction.c:balloon_page_enqueue
  - mm/balloon_compaction.c:balloon_page_list_enqueue
```
**Symbols:**

```
ffffffff81313630-ffffffff813136ab: balloon_page_enqueue_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void balloon_page_enqueue_one(struct balloon_dev_info *b_dev_info, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff813197c0)
Location: mm/balloon_compaction.c:14
Inline: True
Direct callers:
  - mm/balloon_compaction.c:balloon_page_enqueue
  - mm/balloon_compaction.c:balloon_page_list_enqueue
```
**Symbols:**

```
ffffffff813197c0-ffffffff8131983b: balloon_page_enqueue_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void balloon_page_enqueue_one(struct balloon_dev_info *b_dev_info, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff81365f90)
Location: mm/balloon_compaction.c:14
Inline: False
Direct callers:
  - mm/balloon_compaction.c:balloon_page_enqueue
  - mm/balloon_compaction.c:balloon_page_list_enqueue
```
**Symbols:**

```
ffffffff81365f90-ffffffff8136600b: balloon_page_enqueue_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void balloon_page_enqueue_one(struct balloon_dev_info *b_dev_info, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff813e2f30)
Location: mm/balloon_compaction.c:14
Inline: False
Direct callers:
  - mm/balloon_compaction.c:balloon_page_enqueue
  - mm/balloon_compaction.c:balloon_page_list_enqueue
```
**Symbols:**

```
ffffffff813e2f30-ffffffff813e2ff0: balloon_page_enqueue_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void balloon_page_enqueue_one(struct balloon_dev_info *b_dev_info, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff8146a870)
Location: mm/balloon_compaction.c:14
Inline: False
Direct callers:
  - mm/balloon_compaction.c:balloon_page_enqueue
  - mm/balloon_compaction.c:balloon_page_list_enqueue
```
**Symbols:**

```
ffffffff8146a870-ffffffff8146a92e: balloon_page_enqueue_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void balloon_page_enqueue_one(struct balloon_dev_info *b_dev_info, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff8149f700)
Location: mm/balloon_compaction.c:14
Inline: False
Direct callers:
  - mm/balloon_compaction.c:balloon_page_enqueue
  - mm/balloon_compaction.c:balloon_page_list_enqueue
```
**Symbols:**

```
ffffffff8149f700-ffffffff8149f7be: balloon_page_enqueue_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void balloon_page_enqueue_one(struct balloon_dev_info *b_dev_info, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff814cee50)
Location: mm/balloon_compaction.c:14
Inline: False
Direct callers:
  - mm/balloon_compaction.c:balloon_page_enqueue
  - mm/balloon_compaction.c:balloon_page_list_enqueue
```
**Symbols:**

```
ffffffff814cee50-ffffffff814cef0b: balloon_page_enqueue_one (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void balloon_page_enqueue_one(struct balloon_dev_info *b_dev_info, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffff8000103774c0)
Location: mm/balloon_compaction.c:14
Inline: True
Direct callers:
  - mm/balloon_compaction.c:balloon_page_enqueue
  - mm/balloon_compaction.c:balloon_page_list_enqueue
```
**Symbols:**

```
ffff8000103774c0-ffff8000103775a4: balloon_page_enqueue_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void balloon_page_enqueue_one(struct balloon_dev_info *b_dev_info, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (c0563184)
Location: mm/balloon_compaction.c:14
Inline: True
Direct callers:
  - mm/balloon_compaction.c:balloon_page_enqueue
  - mm/balloon_compaction.c:balloon_page_list_enqueue
```
**Symbols:**

```
c0563184-c0563278: balloon_page_enqueue_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void balloon_page_enqueue_one(struct balloon_dev_info *b_dev_info, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (c000000000469c80)
Location: mm/balloon_compaction.c:14
Inline: False
Direct callers:
  - mm/balloon_compaction.c:balloon_page_enqueue
  - mm/balloon_compaction.c:balloon_page_list_enqueue
```
**Symbols:**

```
c000000000469c80-c000000000469d5c: balloon_page_enqueue_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void balloon_page_enqueue_one(struct balloon_dev_info *b_dev_info, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffe00024f7f8)
Location: mm/balloon_compaction.c:14
Inline: True
Direct callers:
  - mm/balloon_compaction.c:balloon_page_enqueue
  - mm/balloon_compaction.c:balloon_page_list_enqueue
```
**Symbols:**

```
ffffffe00024f7f8-ffffffe00024f8a2: balloon_page_enqueue_one (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void balloon_page_enqueue_one(struct balloon_dev_info *b_dev_info, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff812ca2a0)
Location: mm/balloon_compaction.c:14
Inline: True
Direct callers:
  - mm/balloon_compaction.c:balloon_page_enqueue
  - mm/balloon_compaction.c:balloon_page_list_enqueue
```
**Symbols:**

```
ffffffff812ca2a0-ffffffff812ca31b: balloon_page_enqueue_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void balloon_page_enqueue_one(struct balloon_dev_info *b_dev_info, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff812bb2e0)
Location: mm/balloon_compaction.c:14
Inline: True
Direct callers:
  - mm/balloon_compaction.c:balloon_page_enqueue
  - mm/balloon_compaction.c:balloon_page_list_enqueue
```
**Symbols:**

```
ffffffff812bb2e0-ffffffff812bb35b: balloon_page_enqueue_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void balloon_page_enqueue_one(struct balloon_dev_info *b_dev_info, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff812c80b0)
Location: mm/balloon_compaction.c:14
Inline: True
Direct callers:
  - mm/balloon_compaction.c:balloon_page_enqueue
  - mm/balloon_compaction.c:balloon_page_list_enqueue
```
**Symbols:**

```
ffffffff812c80b0-ffffffff812c812b: balloon_page_enqueue_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void balloon_page_enqueue_one(struct balloon_dev_info *b_dev_info, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff812d8dc0)
Location: mm/balloon_compaction.c:14
Inline: True
Direct callers:
  - mm/balloon_compaction.c:balloon_page_enqueue
  - mm/balloon_compaction.c:balloon_page_list_enqueue
```
**Symbols:**

```
ffffffff812d8dc0-ffffffff812d8e3b: balloon_page_enqueue_one (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
