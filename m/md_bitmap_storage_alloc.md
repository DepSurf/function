# Function: <code>md_bitmap_storage_alloc</code>

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
In drivers/md/md-bitmap.c (ffffffff8183034e)
Location: drivers/md/md-bitmap.c:777
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
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
In drivers/md/md-bitmap.c (ffffffff81872aa3)
Location: drivers/md/md-bitmap.c:778
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
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
In drivers/md/md-bitmap.c (ffffffff818a48a3)
Location: drivers/md/md-bitmap.c:778
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int md_bitmap_storage_alloc(struct bitmap_storage *store, long unsigned int chunks, int with_super, int slot_number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81972910)
Location: drivers/md/md-bitmap.c:774
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
**Symbols:**

```
ffffffff81972910-ffffffff81972a98: md_bitmap_storage_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int md_bitmap_storage_alloc(struct bitmap_storage *store, long unsigned int chunks, int with_super, int slot_number);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81977af0)
Location: drivers/md/md-bitmap.c:775
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
**Symbols:**

```
ffffffff81977af0-ffffffff81977c78: md_bitmap_storage_alloc (STB_LOCAL)
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
In drivers/md/md-bitmap.c (ffffffff8195d741)
Location: drivers/md/md-bitmap.c:775
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
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
In drivers/md/md-bitmap.c (ffffffff81a02fda)
Location: drivers/md/md-bitmap.c:775
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
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
In drivers/md/md-bitmap.c (ffffffff81b6abf3)
Location: drivers/md/md-bitmap.c:776
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
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
In drivers/md/md-bitmap.c (ffffffff81d06a18)
Location: drivers/md/md-bitmap.c:776
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
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
In drivers/md/md-bitmap.c (ffffffff81d6fce6)
Location: drivers/md/md-bitmap.c:792
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
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
In drivers/md/md-bitmap.c (ffffffff81e26dde)
Location: drivers/md/md-bitmap.c:809
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
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
In drivers/md/md-bitmap.c (ffff800010af8f80)
Location: drivers/md/md-bitmap.c:778
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
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
In drivers/md/md-bitmap.c (c0bd9ea4)
Location: drivers/md/md-bitmap.c:778
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
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
In drivers/md/md-bitmap.c (c000000000be70a0)
Location: drivers/md/md-bitmap.c:778
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
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
In drivers/md/md-bitmap.c (ffffffe0006eb196)
Location: drivers/md/md-bitmap.c:778
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
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
In drivers/md/md-bitmap.c (ffffffff8184a723)
Location: drivers/md/md-bitmap.c:778
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
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
In drivers/md/md-bitmap.c (ffffffff81811d53)
Location: drivers/md/md-bitmap.c:778
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
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
In drivers/md/md-bitmap.c (ffffffff81899d53)
Location: drivers/md/md-bitmap.c:778
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
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
In drivers/md/md-bitmap.c (ffffffff818b5ec3)
Location: drivers/md/md-bitmap.c:778
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
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
