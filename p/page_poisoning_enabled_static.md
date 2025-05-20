# Function: <code>page_poisoning_enabled_static</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81112205)
Location: include/linux/mm.h:2930
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_page
```
```
In mm/page_alloc.c (ffffffff812be00f)
Location: include/linux/mm.h:2930
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172d0f2)
Location: include/linux/mm.h:2930
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
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
In kernel/power/snapshot.c (ffffffff81113fb2)
Location: include/linux/mm.h:2927
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In mm/page_alloc.c (ffffffff812c47c5)
Location: include/linux/mm.h:2927
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710552)
Location: include/linux/mm.h:2927
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
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
In kernel/power/snapshot.c (ffffffff811340bf)
Location: include/linux/mm.h:2985
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In mm/page_alloc.c (ffffffff8130863e)
Location: include/linux/mm.h:2985
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178cf2f)
Location: include/linux/mm.h:2985
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
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
In kernel/power/snapshot.c (ffffffff8115618f)
Location: include/linux/mm.h:3097
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In mm/page_alloc.c (ffffffff813709ef)
Location: include/linux/mm.h:3097
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c502f)
Location: include/linux/mm.h:3097
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
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
In kernel/power/snapshot.c (ffffffff811866ed)
Location: include/linux/mm.h:3289
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In mm/page_alloc.c (ffffffff813ece71)
Location: include/linux/mm.h:3289
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a158cf)
Location: include/linux/mm.h:3289
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
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
In kernel/power/snapshot.c (ffffffff8119786e)
Location: include/linux/mm.h:3464
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In mm/page_alloc.c (ffffffff81421daf)
Location: include/linux/mm.h:3464
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__free_pages_ok
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5ec4f)
Location: include/linux/mm.h:3464
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
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
In kernel/power/snapshot.c (ffffffff811a64ba)
Location: include/linux/mm.h:3670
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In mm/page_alloc.c (ffffffff8144ebe1)
Location: include/linux/mm.h:3670
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__free_pages_ok
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab13af)
Location: include/linux/mm.h:3670
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
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
