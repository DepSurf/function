# Function: <code>plist_node_empty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff810ff949)
Location: include/linux/plist.h:221
Inline: True
Inline callers:
  - kernel/futex.c:__unqueue_futex
```
```
In mm/swapfile.c (ffffffff811d3ea0)
Location: include/linux/plist.h:221
Inline: True
Inline callers:
  - mm/swapfile.c:swap_entry_free
  - mm/swapfile.c:get_swap_page
```
```
In lib/plist.c (ffffffff813ede18)
Location: include/linux/plist.h:221
Inline: True
Inline callers:
  - lib/plist.c:plist_add
  - lib/plist.c:plist_requeue
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
In kernel/futex.c (ffffffff811070ef)
Location: include/linux/plist.h:221
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:__unqueue_futex
```
```
In mm/swapfile.c (ffffffff811f1cb4)
Location: include/linux/plist.h:221
Inline: True
Inline callers:
  - mm/swapfile.c:swap_entry_free
  - mm/swapfile.c:swap_entry_free
  - mm/swapfile.c:get_swap_page
  - mm/swapfile.c:get_swap_page
```
```
In lib/plist.c (ffffffff814340bd)
Location: include/linux/plist.h:221
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/futex.c (ffffffff8110e8af)
Location: include/linux/plist.h:221
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:__unqueue_futex
```
```
In mm/swapfile.c (ffffffff812026a4)
Location: include/linux/plist.h:221
Inline: True
Inline callers:
  - mm/swapfile.c:swap_entry_free
  - mm/swapfile.c:swap_entry_free
  - mm/swapfile.c:get_swap_page
  - mm/swapfile.c:get_swap_page
```
```
In lib/plist.c (ffffffff8145034d)
Location: include/linux/plist.h:221
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/futex.c (ffffffff8110fda5)
Location: include/linux/plist.h:221
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:__unqueue_futex
```
```
In mm/swapfile.c (ffffffff8120efe0)
Location: include/linux/plist.h:221
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
  - mm/swapfile.c:swap_range_free
```
```
In lib/plist.c (ffffffff818f00a8)
Location: include/linux/plist.h:221
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/futex.c (ffffffff8111b095)
Location: include/linux/plist.h:221
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:__unqueue_futex
```
```
In mm/swapfile.c (ffffffff8122a718)
Location: include/linux/plist.h:221
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:add_to_avail_list
```
```
In lib/plist.c (ffffffff819764fd)
Location: include/linux/plist.h:221
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/futex.c (ffffffff811281df)
Location: include/linux/plist.h:221
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:__unqueue_futex
```
```
In mm/swapfile.c (ffffffff8124b9c9)
Location: include/linux/plist.h:221
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:add_to_avail_list
```
```
In lib/plist.c (ffffffff819d2cc8)
Location: include/linux/plist.h:221
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/futex.c (ffffffff81133abf)
Location: include/linux/plist.h:221
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:__unqueue_futex
```
```
In mm/swapfile.c (ffffffff8126005e)
Location: include/linux/plist.h:221
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:add_to_avail_list
```
```
In lib/plist.c (ffffffff81a0c348)
Location: include/linux/plist.h:221
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/futex.c (ffffffff8113ea1f)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:__unqueue_futex
```
```
In mm/swapfile.c (ffffffff8127acdd)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:add_to_avail_list
```
```
In lib/plist.c (ffffffff81a7bcb1)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/futex.c (ffffffff8114a994)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:__unqueue_futex
```
```
In mm/swapfile.c (ffffffff8128a7bd)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:add_to_avail_list
```
```
In lib/plist.c (ffffffff81ab3011)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/futex.c (ffffffff8115b5b4)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:__unqueue_futex
```
```
In mm/swapfile.c (ffffffff812bd59d)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:add_to_avail_list
```
```
In lib/plist.c (ffffffff815ed888)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/futex.c (ffffffff811576e4)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:__unqueue_futex
```
```
In mm/swapfile.c (ffffffff812c90ba)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:add_to_avail_list
```
```
In lib/plist.c (ffffffff81611fb8)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/futex.c (ffffffff81158b33)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:__unqueue_futex
```
```
In mm/swapfile.c (ffffffff812cfb3c)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:add_to_avail_list
```
```
In lib/plist.c (ffffffff815f56a8)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/futex.c (ffffffff8117da10)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:__unqueue_futex
```
```
In mm/swapfile.c (ffffffff8131510c)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:add_to_avail_list
```
```
In lib/plist.c (ffffffff81662b08)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/futex/core.c (ffffffff811b3223)
Location: include/linux/plist.h:222
Inline: True
Inline callers:
  - kernel/futex/core.c:__futex_unqueue
```
```
In kernel/futex/waitwake.c (ffffffff811b7210)
Location: include/linux/plist.h:222
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wait_queue
```
```
In mm/swapfile.c (ffffffff813806db)
Location: include/linux/plist.h:222
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:add_to_avail_list
```
```
In lib/plist.c (ffffffff8177c9f7)
Location: include/linux/plist.h:222
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/futex/core.c (ffffffff811f4143)
Location: include/linux/plist.h:222
Inline: True
Inline callers:
  - kernel/futex/core.c:__futex_unqueue
```
```
In kernel/futex/waitwake.c (ffffffff811f83b0)
Location: include/linux/plist.h:222
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wait_queue
```
```
In mm/swapfile.c (ffffffff813fefcb)
Location: include/linux/plist.h:222
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:add_to_avail_list
```
```
In lib/plist.c (ffffffff82039451)
Location: include/linux/plist.h:222
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/futex/core.c (ffffffff812088d3)
Location: include/linux/plist.h:222
Inline: True
Inline callers:
  - kernel/futex/core.c:__futex_unqueue
```
```
In kernel/futex/waitwake.c (ffffffff8120cb70)
Location: include/linux/plist.h:222
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wait_queue
```
```
In mm/swapfile.c (ffffffff81431f03)
Location: include/linux/plist.h:222
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:add_to_avail_list
```
```
In lib/plist.c (ffffffff820b7771)
Location: include/linux/plist.h:222
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/futex/core.c (ffffffff8121f945)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_unqueue_pi
  - kernel/futex/core.c:__futex_unqueue
```
```
In kernel/futex/waitwake.c (ffffffff81223f40)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wait_queue
```
```
In mm/swapfile.c (ffffffff8146b2f3)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
```
```
In lib/plist.c (ffffffff82192081)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/futex.c (ffff8000101b66b8)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:__unqueue_futex
```
```
In mm/swapfile.c (ffff8000103259b4)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:add_to_avail_list
```
```
In lib/plist.c (ffff800010d8d2b8)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/futex.c (c04011c0)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:__unqueue_futex
```
```
In mm/swapfile.c (c053d198)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:add_to_avail_list
```
```
In lib/plist.c (c0e877b8)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/futex.c (c00000000021c058)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:__unqueue_futex
```
```
In mm/swapfile.c (c0000000003fbc4c)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:add_to_avail_list
```
```
In lib/plist.c (c000000000ecf544)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/futex.c (ffffffe00013cb92)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:__unqueue_futex
```
```
In mm/swapfile.c (ffffffe000225e10)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:add_to_avail_list
```
```
In lib/plist.c (ffffffe0008b5f42)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/futex.c (ffffffff81142fb4)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:__unqueue_futex
```
```
In mm/swapfile.c (ffffffff81282d9d)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:add_to_avail_list
```
```
In lib/plist.c (ffffffff81a51e61)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/futex.c (ffffffff81136314)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:__unqueue_futex
```
```
In mm/swapfile.c (ffffffff812748bd)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:add_to_avail_list
```
```
In lib/plist.c (ffffffff81a0ef61)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/futex.c (ffffffff81140e64)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:__unqueue_futex
```
```
In mm/swapfile.c (ffffffff81280bad)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:add_to_avail_list
```
```
In lib/plist.c (ffffffff81abe251)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/futex.c (ffffffff8114d3f2)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:__unqueue_futex
```
```
In mm/swapfile.c (ffffffff81290919)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:add_to_avail_list
```
```
In lib/plist.c (ffffffff81aca6f1)
Location: include/linux/plist.h:219
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
```
</details>
</li>
</ul>

## Differences
