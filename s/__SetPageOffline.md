# Function: <code>__SetPageOffline</code>

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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/balloon_compaction.c (ffffffff812bfd95)
Location: include/linux/page-flags.h:749
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8163e3fe)
Location: include/linux/page-flags.h:749
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffffffff81642687)
Location: include/linux/page-flags.h:749
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:xen_online_page
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
In mm/balloon_compaction.c (ffffffff812d1ce5)
Location: include/linux/page-flags.h:765
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81660968)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffffffff816648d5)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_append
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
In mm/balloon_compaction.c (ffffffff81307925)
Location: include/linux/page-flags.h:791
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8171064d)
Location: include/linux/page-flags.h:791
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffffffff82d16c99)
Location: include/linux/page-flags.h:791
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:xen_online_page
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
In mm/balloon_compaction.c (ffffffff81313655)
Location: include/linux/page-flags.h:767
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172d22d)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffffffff81731657)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:xen_online_page
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
In mm/balloon_compaction.c (ffffffff813197e5)
Location: include/linux/page-flags.h:761
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710f9d)
Location: include/linux/page-flags.h:761
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffffffff81715057)
Location: include/linux/page-flags.h:761
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:xen_online_page
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
In mm/balloon_compaction.c (ffffffff81365fb5)
Location: include/linux/page-flags.h:775
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178dab7)
Location: include/linux/page-flags.h:775
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffffffff81792067)
Location: include/linux/page-flags.h:775
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:xen_online_page
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
In mm/balloon_compaction.c (ffffffff813e2f5f)
Location: include/linux/page-flags.h:998
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c6272)
Location: include/linux/page-flags.h:998
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffffffff834b0a53)
Location: include/linux/page-flags.h:998
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/balloon.c:xen_free_ballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:xen_online_page
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
In mm/balloon_compaction.c (ffffffff8146a89f)
Location: include/linux/page-flags.h:977
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a16ba9)
Location: include/linux/page-flags.h:977
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffffffff83eea60f)
Location: include/linux/page-flags.h:977
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/balloon.c:xen_free_ballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:xen_online_page
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
In mm/balloon_compaction.c (ffffffff8149f72f)
Location: include/linux/page-flags.h:966
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5fc39)
Location: include/linux/page-flags.h:966
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffffffff83710000)
Location: include/linux/page-flags.h:966
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/balloon.c:xen_free_ballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:xen_online_page
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
In mm/balloon_compaction.c (ffffffff814cee7f)
Location: include/linux/page-flags.h:1012
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab2449)
Location: include/linux/page-flags.h:1012
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffffffff83943975)
Location: include/linux/page-flags.h:1012
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/balloon.c:xen_free_ballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:xen_online_page
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
In mm/balloon_compaction.c (ffff800010377520)
Location: include/linux/page-flags.h:765
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082b0d8)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffff80001082e660)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_append
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
In mm/balloon_compaction.c (c05631f8)
Location: include/linux/page-flags.h:765
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (c09475ac)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/balloon_compaction.c (c000000000469ce0)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d6690)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/balloon_compaction.c (ffffffe00024f826)
Location: include/linux/page-flags.h:765
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffe00051fcb4)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/balloon_compaction.c (ffffffff812ca2c5)
Location: include/linux/page-flags.h:765
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816267d8)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffffffff8162a745)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_append
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
In mm/balloon_compaction.c (ffffffff812bb305)
Location: include/linux/page-flags.h:765
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161ae58)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/balloon_compaction.c (ffffffff812c80d5)
Location: include/linux/page-flags.h:765
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816547a8)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffffffff81658715)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_append
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
In mm/balloon_compaction.c (ffffffff812d8de5)
Location: include/linux/page-flags.h:765
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8166f228)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffffffff81672d15)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_append
```
</details>
</li>
</ul>

## Differences
