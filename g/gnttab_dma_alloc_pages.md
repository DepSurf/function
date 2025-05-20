# Function: <code>gnttab_dma_alloc_pages</code>

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
int gnttab_dma_alloc_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8160cbf0)
Location: drivers/xen/grant-table.c:850
Inline: False
```
**Symbols:**

```
ffffffff8160cbf0-ffffffff8160ce7f: gnttab_dma_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int gnttab_dma_alloc_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81641890)
Location: drivers/xen/grant-table.c:850
Inline: False
```
**Symbols:**

```
ffffffff81641890-ffffffff81641b3d: gnttab_dma_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gnttab_dma_alloc_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81662ea0)
Location: drivers/xen/grant-table.c:850
Inline: False
```
**Symbols:**

```
ffffffff81662ea0-ffffffff8166314d: gnttab_dma_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gnttab_dma_alloc_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff817133d0)
Location: drivers/xen/grant-table.c:848
Inline: False
```
**Symbols:**

```
ffffffff817133d0-ffffffff81713695: gnttab_dma_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gnttab_dma_alloc_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff817302c0)
Location: drivers/xen/grant-table.c:971
Inline: False
```
**Symbols:**

```
ffffffff817302c0-ffffffff81730585: gnttab_dma_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gnttab_dma_alloc_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81713e60)
Location: drivers/xen/grant-table.c:971
Inline: False
```
**Symbols:**

```
ffffffff81713e60-ffffffff81714125: gnttab_dma_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gnttab_dma_alloc_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:978
Inline: False
```
**Symbols:**

```
ffffffff81cf53ee-ffffffff81cf5431: gnttab_dma_alloc_pages.cold (STB_LOCAL)
ffffffff81790890-ffffffff81790b5a: gnttab_dma_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gnttab_dma_alloc_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1044
Inline: False
```
**Symbols:**

```
ffffffff81ebd5d6-ffffffff81ebd606: gnttab_dma_alloc_pages.cold (STB_LOCAL)
ffffffff818c9770-ffffffff818c99dd: gnttab_dma_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int gnttab_dma_alloc_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1044
Inline: False
```
**Symbols:**

```
ffffffff8209463d-ffffffff8209466d: gnttab_dma_alloc_pages.cold (STB_LOCAL)
ffffffff81a1a540-ffffffff81a1a7d0: gnttab_dma_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int gnttab_dma_alloc_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1062
Inline: False
```
**Symbols:**

```
ffffffff821153b2-ffffffff821153e2: gnttab_dma_alloc_pages.cold (STB_LOCAL)
ffffffff81a633c0-ffffffff81a63650: gnttab_dma_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int gnttab_dma_alloc_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1060
Inline: False
```
**Symbols:**

```
ffffffff821f3052-ffffffff821f3082: gnttab_dma_alloc_pages.cold (STB_LOCAL)
ffffffff81ab5be0-ffffffff81ab5e70: gnttab_dma_alloc_pages (STB_GLOBAL)
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
int gnttab_dma_alloc_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffff80001082cc30)
Location: drivers/xen/grant-table.c:850
Inline: False
```
**Symbols:**

```
ffff80001082cc30-ffff80001082ce44: gnttab_dma_alloc_pages (STB_GLOBAL)
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
int gnttab_dma_alloc_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81628d10)
Location: drivers/xen/grant-table.c:850
Inline: False
```
**Symbols:**

```
ffffffff81628d10-ffffffff81628fbd: gnttab_dma_alloc_pages (STB_GLOBAL)
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
int gnttab_dma_alloc_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81656ce0)
Location: drivers/xen/grant-table.c:850
Inline: False
```
**Symbols:**

```
ffffffff81656ce0-ffffffff81656f8d: gnttab_dma_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gnttab_dma_alloc_pages(struct gnttab_dma_alloc_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff816712c0)
Location: drivers/xen/grant-table.c:850
Inline: False
```
**Symbols:**

```
ffffffff816712c0-ffffffff81671589: gnttab_dma_alloc_pages (STB_GLOBAL)
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
