# Function: <code>swap_write_unplug</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void swap_write_unplug(struct swap_iocb *sio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff813798f0)
Location: mm/page_io.c:373
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff813798f0-ffffffff813799bf: swap_write_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void swap_write_unplug(struct swap_iocb *sio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff813f7380)
Location: mm/page_io.c:373
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:swap_writepage_fs
```
**Symbols:**

```
ffffffff813f7380-ffffffff813f744f: swap_write_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void swap_write_unplug(struct swap_iocb *sio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8142a670)
Location: mm/page_io.c:390
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:swap_writepage_fs
```
**Symbols:**

```
ffffffff8142a670-ffffffff8142a73c: swap_write_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void swap_write_unplug(struct swap_iocb *sio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff81463d30)
Location: mm/page_io.c:392
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:swap_writepage_fs
```
**Symbols:**

```
ffffffff81463d30-ffffffff81463dfc: swap_write_unplug (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
