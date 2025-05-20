# Function: <code>mapping_exiting</code>

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
In mm/vmscan.c (ffffffff811a02bd)
Location: include/linux/pagemap.h:62
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a201e)
Location: include/linux/pagemap.h:62
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/vmscan.c (ffffffff811b7437)
Location: include/linux/pagemap.h:62
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b1e83)
Location: include/linux/pagemap.h:63
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/vmscan.c (ffffffff811c7a93)
Location: include/linux/pagemap.h:63
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b8b45)
Location: include/linux/pagemap.h:82
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/vmscan.c (ffffffff811d01a5)
Location: include/linux/pagemap.h:82
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ca234)
Location: include/linux/pagemap.h:85
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffff811e5655)
Location: include/linux/pagemap.h:85
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811f0c71)
Location: include/linux/pagemap.h:85
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffff81206c85)
Location: include/linux/pagemap.h:85
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81202acd)
Location: include/linux/pagemap.h:85
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffff8121980a)
Location: include/linux/pagemap.h:85
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81219efe)
Location: include/linux/pagemap.h:85
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffff812292e7)
Location: include/linux/pagemap.h:85
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
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
In mm/filemap.c (ffffffff8122786e)
Location: include/linux/pagemap.h:85
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffff812371b4)
Location: include/linux/pagemap.h:85
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812541ad)
Location: include/linux/pagemap.h:86
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffff81264044)
Location: include/linux/pagemap.h:86
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81be6a4d)
Location: include/linux/pagemap.h:88
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffff8126ea67)
Location: include/linux/pagemap.h:88
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
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
In mm/filemap.c (ffffffff81bd87e3)
Location: include/linux/pagemap.h:93
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffff81273b97)
Location: include/linux/pagemap.h:93
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
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
In mm/filemap.c (ffffffff81cb9e3a)
Location: include/linux/pagemap.h:93
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffff812b2c3d)
Location: include/linux/pagemap.h:93
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81e6b471)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/vmscan.c (ffffffff8130cdd0)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81359a0b)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/vmscan.c (ffffffff81376279)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138b35b)
Location: include/linux/pagemap.h:261
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/vmscan.c (ffffffff813a62a6)
Location: include/linux/pagemap.h:261
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b4e88)
Location: include/linux/pagemap.h:265
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/vmscan.c (ffffffff813cfe13)
Location: include/linux/pagemap.h:265
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
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
In mm/filemap.c (ffff8000102aeea0)
Location: include/linux/pagemap.h:85
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffff8000102c821c)
Location: include/linux/pagemap.h:85
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
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
In mm/filemap.c (c04daad4)
Location: include/linux/pagemap.h:85
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (c04f2104)
Location: include/linux/pagemap.h:85
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
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
In mm/filemap.c (c0000000003623f8)
Location: include/linux/pagemap.h:85
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (c000000000383510)
Location: include/linux/pagemap.h:85
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
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
In mm/filemap.c (ffffffe0001d4404)
Location: include/linux/pagemap.h:85
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffe0001e7690)
Location: include/linux/pagemap.h:85
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
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
In mm/filemap.c (ffffffff8121febe)
Location: include/linux/pagemap.h:85
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffff8122f804)
Location: include/linux/pagemap.h:85
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
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
In mm/filemap.c (ffffffff8121306e)
Location: include/linux/pagemap.h:85
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffff812228c4)
Location: include/linux/pagemap.h:85
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
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
In mm/filemap.c (ffffffff8121dc5e)
Location: include/linux/pagemap.h:85
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffff8122d5a4)
Location: include/linux/pagemap.h:85
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
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
In mm/filemap.c (ffffffff8122ccce)
Location: include/linux/pagemap.h:85
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/vmscan.c (ffffffff8123c9a4)
Location: include/linux/pagemap.h:85
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
</details>
</li>
</ul>

## Differences
