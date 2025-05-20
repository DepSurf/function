# Function: <code>__ClearPageOffline</code>

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
In mm/balloon_compaction.c (ffffffff812bfc77)
Location: include/linux/page-flags.h:749
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8163e489)
Location: include/linux/page-flags.h:749
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffffffff81642d11)
Location: include/linux/page-flags.h:749
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
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
In mm/balloon_compaction.c (ffffffff812d1bc7)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816609f3)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffffffff8166531c)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
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
In mm/balloon_compaction.c (ffffffff81307af6)
Location: include/linux/page-flags.h:791
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff817106d5)
Location: include/linux/page-flags.h:791
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffffffff81714b28)
Location: include/linux/page-flags.h:791
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:increase_reservation
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
In mm/balloon_compaction.c (ffffffff81313826)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172d2b2)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffffffff81731788)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:increase_reservation
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
In mm/balloon_compaction.c (ffffffff813199b6)
Location: include/linux/page-flags.h:761
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8171101f)
Location: include/linux/page-flags.h:761
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffffffff81715197)
Location: include/linux/page-flags.h:761
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
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
In mm/balloon_compaction.c (ffffffff813661a6)
Location: include/linux/page-flags.h:775
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178db39)
Location: include/linux/page-flags.h:775
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffffffff817921a7)
Location: include/linux/page-flags.h:775
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_thread
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
In mm/balloon_compaction.c (ffffffff813e3192)
Location: include/linux/page-flags.h:998
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c62f4)
Location: include/linux/page-flags.h:998
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffffffff818ca42a)
Location: include/linux/page-flags.h:998
Inline: True
Inline callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
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
In mm/balloon_compaction.c (ffffffff8146ab06)
Location: include/linux/page-flags.h:977
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a16c23)
Location: include/linux/page-flags.h:977
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffffffff81a1b96a)
Location: include/linux/page-flags.h:977
Inline: True
Inline callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
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
In mm/balloon_compaction.c (ffffffff8149f996)
Location: include/linux/page-flags.h:966
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5fcb3)
Location: include/linux/page-flags.h:966
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffffffff81a64b0a)
Location: include/linux/page-flags.h:966
Inline: True
Inline callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
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
In mm/balloon_compaction.c (ffffffff814cf0e6)
Location: include/linux/page-flags.h:1012
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab24c3)
Location: include/linux/page-flags.h:1012
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffffffff81ab736a)
Location: include/linux/page-flags.h:1012
Inline: True
Inline callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
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
In mm/balloon_compaction.c (ffff800010377a2c)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082b1a4)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffff80001082eb18)
Location: include/linux/page-flags.h:765
Inline: True
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
In mm/balloon_compaction.c (c05633e8)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (c0947650)
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
In mm/balloon_compaction.c (c00000000046a050)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d6740)
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
In mm/balloon_compaction.c (ffffffe00024f6cc)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffe00051fd4e)
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
In mm/balloon_compaction.c (ffffffff812ca1a7)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81626863)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffffffff8162af3d)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
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
In mm/balloon_compaction.c (ffffffff812bb1e7)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161aee3)
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
In mm/balloon_compaction.c (ffffffff812c7fb7)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81654833)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffffffff8165915c)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
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
In mm/balloon_compaction.c (ffffffff812d8cc7)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8166f2b3)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/balloon.c (ffffffff8167375c)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
</details>
</li>
</ul>

## Differences
