# Function: <code>gnttab_dma_free_pages</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gnttab_dma_free_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8160c640)
Location: drivers/xen/grant-table.c:905
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
**Symbols:**

```
ffffffff8160c640-ffffffff8160c72b: gnttab_dma_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int gnttab_dma_free_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff816417a0)
Location: drivers/xen/grant-table.c:905
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
**Symbols:**

```
ffffffff816417a0-ffffffff81641889: gnttab_dma_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gnttab_dma_free_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81662940)
Location: drivers/xen/grant-table.c:905
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
**Symbols:**

```
ffffffff81662940-ffffffff81662a29: gnttab_dma_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gnttab_dma_free_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff817120a0)
Location: drivers/xen/grant-table.c:903
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
**Symbols:**

```
ffffffff817120a0-ffffffff81712189: gnttab_dma_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gnttab_dma_free_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8172ee30)
Location: drivers/xen/grant-table.c:1026
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
**Symbols:**

```
ffffffff8172ee30-ffffffff8172ef19: gnttab_dma_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gnttab_dma_free_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81712880)
Location: drivers/xen/grant-table.c:1026
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
**Symbols:**

```
ffffffff81712880-ffffffff81712969: gnttab_dma_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gnttab_dma_free_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1033
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
**Symbols:**

```
ffffffff81cf52a4-ffffffff81cf52b9: gnttab_dma_free_pages.cold (STB_LOCAL)
ffffffff8178f3b0-ffffffff8178f4ba: gnttab_dma_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gnttab_dma_free_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1099
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
**Symbols:**

```
ffffffff81ebd3f7-ffffffff81ebd414: gnttab_dma_free_pages.cold (STB_LOCAL)
ffffffff818c76a0-ffffffff818c77d2: gnttab_dma_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int gnttab_dma_free_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1102
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
**Symbols:**

```
ffffffff8209460c-ffffffff82094629: gnttab_dma_free_pages.cold (STB_LOCAL)
ffffffff81a18210-ffffffff81a18342: gnttab_dma_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int gnttab_dma_free_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1120
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
**Symbols:**

```
ffffffff82115381-ffffffff8211539e: gnttab_dma_free_pages.cold (STB_LOCAL)
ffffffff81a612a0-ffffffff81a613d0: gnttab_dma_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int gnttab_dma_free_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1118
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
**Symbols:**

```
ffffffff821f3021-ffffffff821f303e: gnttab_dma_free_pages.cold (STB_LOCAL)
ffffffff81ab3ad0-ffffffff81ab3c00: gnttab_dma_free_pages (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int gnttab_dma_free_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffff80001082cb38)
Location: drivers/xen/grant-table.c:905
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
**Symbols:**

```
ffff80001082cb38-ffff80001082cc30: gnttab_dma_free_pages (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int gnttab_dma_free_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff816287b0)
Location: drivers/xen/grant-table.c:905
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
**Symbols:**

```
ffffffff816287b0-ffffffff81628899: gnttab_dma_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int gnttab_dma_free_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81656780)
Location: drivers/xen/grant-table.c:905
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
**Symbols:**

```
ffffffff81656780-ffffffff81656869: gnttab_dma_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gnttab_dma_free_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81670d60)
Location: drivers/xen/grant-table.c:905
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
**Symbols:**

```
ffffffff81670d60-ffffffff81670e49: gnttab_dma_free_pages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
