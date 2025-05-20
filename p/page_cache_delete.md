# Function: <code>page_cache_delete</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812005cd)
Location: mm/filemap.c:116
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
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
In mm/filemap.c (ffffffff812181fd)
Location: mm/filemap.c:118
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
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
In mm/filemap.c (ffffffff81225a8d)
Location: mm/filemap.c:119
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void page_cache_delete(struct address_space *mapping, struct page *page, void *shadow);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8124e5d0)
Location: mm/filemap.c:119
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache
```
**Symbols:**

```
ffffffff8124e5d0-ffffffff8124e744: page_cache_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void page_cache_delete(struct address_space *mapping, struct page *page, void *shadow);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81258880)
Location: mm/filemap.c:120
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache
```
**Symbols:**

```
ffffffff81258880-ffffffff812589eb: page_cache_delete (STB_LOCAL)
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
In mm/filemap.c (ffffffff8126124d)
Location: mm/filemap.c:122
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129dead)
Location: mm/filemap.c:124
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
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
In mm/filemap.c (ffffffff812f4e6d)
Location: mm/filemap.c:124
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_remove_folio
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
In mm/filemap.c (ffffffff8135ed3d)
Location: mm/filemap.c:124
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_remove_folio
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
In mm/filemap.c (ffffffff8138fe5d)
Location: mm/filemap.c:129
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_remove_folio
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
In mm/filemap.c (ffffffff813b98cd)
Location: mm/filemap.c:127
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_remove_folio
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
In mm/filemap.c (ffff8000102b2b24)
Location: mm/filemap.c:119
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
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
In mm/filemap.c (c04dfdac)
Location: mm/filemap.c:119
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
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
In mm/filemap.c (c000000000369578)
Location: mm/filemap.c:119
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
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
In mm/filemap.c (ffffffe0001d843e)
Location: mm/filemap.c:119
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
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
In mm/filemap.c (ffffffff8121e0dd)
Location: mm/filemap.c:119
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
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
In mm/filemap.c (ffffffff8121129d)
Location: mm/filemap.c:119
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
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
In mm/filemap.c (ffffffff8121be7d)
Location: mm/filemap.c:119
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
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
In mm/filemap.c (ffffffff8122aecd)
Location: mm/filemap.c:119
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
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
