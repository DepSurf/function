# Function: <code>bio_full</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (0)
Location: include/linux/bio.h:130
Inline: True
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
In fs/iomap.c (0)
Location: include/linux/bio.h:126
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/bio.h:126
Inline: True
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
In fs/iomap/buffered-io.c (ffffffff8134b91f)
Location: include/linux/bio.h:113
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In block/bio.c (ffffffff814c6e1c)
Location: include/linux/bio.h:113
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_add_pc_page
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
In fs/iomap/buffered-io.c (ffffffff81363bef)
Location: include/linux/bio.h:113
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In block/bio.c (ffffffff814dfc8c)
Location: include/linux/bio.h:113
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
  - block/bio.c:__bio_add_page
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
In fs/iomap/buffered-io.c (ffffffff813aa31f)
Location: include/linux/bio.h:113
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In block/bio.c (ffffffff8153f892)
Location: include/linux/bio.h:113
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
  - block/bio.c:__bio_add_page
  - block/bio.c:bio_add_hw_page
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
In fs/iomap/buffered-io.c (ffffffff813bb96e)
Location: include/linux/bio.h:111
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In block/bio.c (ffffffff8155c0b2)
Location: include/linux/bio.h:111
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
  - block/bio.c:__bio_add_page
  - block/bio.c:bio_add_hw_page
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
In fs/iomap/buffered-io.c (ffffffff813c2a64)
Location: include/linux/bio.h:114
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In block/bio.c (ffffffff81562fbf)
Location: include/linux/bio.h:114
Inline: True
Inline callers:
  - block/bio.c:bio_add_page
  - block/bio.c:__bio_add_page
  - block/bio.c:bio_add_hw_page
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
In block/bio.c (ffffffff815c75f8)
Location: include/linux/bio.h:113
Inline: True
Inline callers:
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
  - block/bio.c:__bio_add_page
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
In block/bio.c (ffffffff81673ad6)
Location: block/bio.c:847
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_folio
  - block/bio.c:__bio_add_page
  - block/bio.c:bio_add_hw_page
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
In block/bio.c (ffffffff8172fa02)
Location: block/bio.c:898
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_folio
  - block/bio.c:__bio_add_page
  - block/bio.c:bio_add_hw_page
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
In block/bio.c (ffffffff8176bc43)
Location: block/bio.c:897
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_folio_nofail
  - block/bio.c:bio_add_page
  - block/bio.c:bio_add_hw_page
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
In block/bio.c (ffffffff817ae0d9)
Location: block/bio.c:897
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_folio_nofail
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
In fs/iomap/buffered-io.c (ffff80001042bf88)
Location: include/linux/bio.h:113
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In block/bio.c (ffff8000105dc818)
Location: include/linux/bio.h:113
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
  - block/bio.c:__bio_add_page
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
In fs/iomap/buffered-io.c (c05f3888)
Location: include/linux/bio.h:113
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In block/bio.c (c0789c40)
Location: include/linux/bio.h:113
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
  - block/bio.c:__bio_add_page
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
In fs/iomap/buffered-io.c (c00000000053b4d0)
Location: include/linux/bio.h:113
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In block/bio.c (c00000000076d9a8)
Location: include/linux/bio.h:113
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
  - block/bio.c:__bio_add_page
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
In fs/iomap/buffered-io.c (ffffffe0002c8400)
Location: include/linux/bio.h:113
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In block/bio.c (ffffffe00041fbce)
Location: include/linux/bio.h:113
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
  - block/bio.c:__bio_add_page
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
In fs/iomap/buffered-io.c (ffffffff8135c1cf)
Location: include/linux/bio.h:113
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In block/bio.c (ffffffff814d826c)
Location: include/linux/bio.h:113
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
  - block/bio.c:__bio_add_page
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
In fs/iomap/buffered-io.c (ffffffff8134ce6f)
Location: include/linux/bio.h:113
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In block/bio.c (ffffffff814c8c1c)
Location: include/linux/bio.h:113
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
  - block/bio.c:__bio_add_page
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
In fs/iomap/buffered-io.c (ffffffff81359c9f)
Location: include/linux/bio.h:113
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In block/bio.c (ffffffff814d42fc)
Location: include/linux/bio.h:113
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
  - block/bio.c:__bio_add_page
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
In fs/iomap/buffered-io.c (ffffffff8136d3af)
Location: include/linux/bio.h:113
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In block/bio.c (ffffffff814eceac)
Location: include/linux/bio.h:113
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_page
  - block/bio.c:__bio_add_page
```
</details>
</li>
</ul>

## Differences
