# Function: <code>PageIsolated</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811d019d)
Location: include/linux/page-flags.h:664
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/migrate.c (ffffffff812116f9)
Location: include/linux/page-flags.h:664
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/balloon_compaction.c (ffffffff8122cef7)
Location: include/linux/page-flags.h:664
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81513f59)
Location: include/linux/page-flags.h:664
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/compaction.c (ffffffff811e01bd)
Location: include/linux/page-flags.h:680
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/migrate.c (ffffffff812238b9)
Location: include/linux/page-flags.h:680
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/balloon_compaction.c (ffffffff8123f417)
Location: include/linux/page-flags.h:680
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81540389)
Location: include/linux/page-flags.h:680
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/compaction.c (ffffffff811e9fca)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/migrate.c (ffffffff8122f1ad)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/balloon_compaction.c (ffffffff8124ad6e)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815541d0)
Location: include/linux/page-flags.h:683
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/compaction.c (ffffffff81200325)
Location: include/linux/page-flags.h:684
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/migrate.c (ffffffff8124bef9)
Location: include/linux/page-flags.h:684
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/balloon_compaction.c (ffffffff8126afde)
Location: include/linux/page-flags.h:684
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815b7c10)
Location: include/linux/page-flags.h:684
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/compaction.c (ffffffff81221753)
Location: include/linux/page-flags.h:704
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/migrate.c (ffffffff8126faae)
Location: include/linux/page-flags.h:704
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/balloon_compaction.c (ffffffff8128f9cb)
Location: include/linux/page-flags.h:704
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815f0165)
Location: include/linux/page-flags.h:704
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/compaction.c (ffffffff812347b0)
Location: include/linux/page-flags.h:727
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/migrate.c (ffffffff8128413e)
Location: include/linux/page-flags.h:727
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/balloon_compaction.c (ffffffff812a48eb)
Location: include/linux/page-flags.h:727
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8160a748)
Location: include/linux/page-flags.h:727
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/compaction.c (ffffffff8124467a)
Location: include/linux/page-flags.h:769
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/migrate.c (ffffffff8129f306)
Location: include/linux/page-flags.h:769
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/balloon_compaction.c (ffffffff812bfc96)
Location: include/linux/page-flags.h:769
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8163e499)
Location: include/linux/page-flags.h:769
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/compaction.c (ffffffff81252b3a)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/migrate.c (ffffffff812afcf6)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/balloon_compaction.c (ffffffff812d1be6)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81660a03)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/compaction.c (ffffffff81282ee1)
Location: include/linux/page-flags.h:811
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/migrate.c (ffffffff812e5da6)
Location: include/linux/page-flags.h:811
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/balloon_compaction.c (ffffffff81307b15)
Location: include/linux/page-flags.h:811
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff817106e7)
Location: include/linux/page-flags.h:811
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/compaction.c (ffffffff8128ceae)
Location: include/linux/page-flags.h:781
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/migrate.c (ffffffff812f1166)
Location: include/linux/page-flags.h:781
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/balloon_compaction.c (ffffffff81313845)
Location: include/linux/page-flags.h:781
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172d2c4)
Location: include/linux/page-flags.h:781
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/compaction.c (ffffffff81292057)
Location: include/linux/page-flags.h:775
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/migrate.c (ffffffff812f7466)
Location: include/linux/page-flags.h:775
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/balloon_compaction.c (ffffffff813199d5)
Location: include/linux/page-flags.h:775
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81711031)
Location: include/linux/page-flags.h:775
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/compaction.c (ffffffff812d176f)
Location: include/linux/page-flags.h:794
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/migrate.c (ffffffff81341acf)
Location: include/linux/page-flags.h:794
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/balloon_compaction.c (ffffffff813661c5)
Location: include/linux/page-flags.h:794
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178db4b)
Location: include/linux/page-flags.h:794
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/compaction.c (ffffffff813310b6)
Location: include/linux/page-flags.h:1017
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/migrate.c (ffffffff813b3081)
Location: include/linux/page-flags.h:1017
Inline: True
Inline callers:
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/balloon_compaction.c (ffffffff813e31a6)
Location: include/linux/page-flags.h:1017
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c6304)
Location: include/linux/page-flags.h:1017
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/compaction.c (ffffffff813a7da4)
Location: include/linux/page-flags.h:996
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/migrate.c (ffffffff81433501)
Location: include/linux/page-flags.h:996
Inline: True
Inline callers:
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/balloon_compaction.c (ffffffff8146ab25)
Location: include/linux/page-flags.h:996
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a16c33)
Location: include/linux/page-flags.h:996
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/compaction.c (ffffffff813db30f)
Location: include/linux/page-flags.h:985
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/balloon_compaction.c (ffffffff8149f9b5)
Location: include/linux/page-flags.h:985
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5fcc3)
Location: include/linux/page-flags.h:985
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/compaction.c (ffffffff81405021)
Location: include/linux/page-flags.h:1031
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/balloon_compaction.c (ffffffff814cf105)
Location: include/linux/page-flags.h:1031
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab24d3)
Location: include/linux/page-flags.h:1031
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/compaction.c (ffff8000102eb51c)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/migrate.c (ffff800010350c34)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/balloon_compaction.c (ffff800010377a44)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082b1bc)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/compaction.c (c050ec84)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/migrate.c (c0552328)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/balloon_compaction.c (c0563404)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (c0947660)
Location: include/linux/page-flags.h:785
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
In mm/compaction.c (c0000000003acab0)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/migrate.c (c000000000435c30)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/balloon_compaction.c (c00000000046a070)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d675c)
Location: include/linux/page-flags.h:785
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
In mm/compaction.c (ffffffe0001ff8e4)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/migrate.c (ffffffe00023f63e)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/balloon_compaction.c (ffffffe00024f6e2)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffe00051fd66)
Location: include/linux/page-flags.h:785
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
In mm/compaction.c (ffffffff8124b18a)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/migrate.c (ffffffff812a82d6)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/balloon_compaction.c (ffffffff812ca1c6)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81626873)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/compaction.c (ffffffff8123e12a)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/migrate.c (ffffffff81299c96)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/balloon_compaction.c (ffffffff812bb206)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161aef3)
Location: include/linux/page-flags.h:785
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
In mm/compaction.c (ffffffff81248f2a)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/migrate.c (ffffffff812a60e6)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/balloon_compaction.c (ffffffff812c7fd6)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81654843)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In mm/compaction.c (ffffffff8125876b)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/migrate.c (ffffffff812b6431)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/balloon_compaction.c (ffffffff812d8ce6)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8166f2c3)
Location: include/linux/page-flags.h:785
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
</details>
</li>
</ul>

## Differences
