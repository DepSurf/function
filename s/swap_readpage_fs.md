# Function: <code>swap_readpage_fs</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void swap_readpage_fs(struct page *page, struct swap_iocb **plug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:411
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
```
**Symbols:**

```
ffffffff8137a080-ffffffff8137a420: swap_readpage_fs (STB_LOCAL)
ffffffff81e70a56-ffffffff81e70aa0: swap_readpage_fs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void swap_readpage_fs(struct page *page, struct swap_iocb **plug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:411
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
```
**Symbols:**

```
ffffffff813f7b70-ffffffff813f7ea5: swap_readpage_fs (STB_LOCAL)
ffffffff82065a00-ffffffff82065a88: swap_readpage_fs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void swap_readpage_fs(struct page *page, struct swap_iocb **plug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:428
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
```
**Symbols:**

```
ffffffff8142ad30-ffffffff8142af98: swap_readpage_fs (STB_LOCAL)
ffffffff820e5204-ffffffff820e5267: swap_readpage_fs.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
