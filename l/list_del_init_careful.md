# Function: <code>list_del_init_careful</code>

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
In kernel/sched/wait.c (ffffffff810fd782)
Location: include/linux/list.h:296
Inline: True
```
```
In mm/filemap.c (ffffffff8125932c)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - mm/filemap.c:wake_page_function
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
In kernel/sched/wait.c (ffffffff810ffb62)
Location: include/linux/list.h:296
Inline: True
```
```
In mm/filemap.c (ffffffff8125cc2c)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - mm/filemap.c:wake_page_function
```
```
In block/blk-iocost.c (ffffffff81594922)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_wake_fn
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
In kernel/sched/wait.c (ffffffff8111bc62)
Location: include/linux/list.h:296
Inline: True
```
```
In mm/filemap.c (ffffffff81298b7c)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - mm/filemap.c:wake_page_function
```
```
In block/blk-iocost.c (ffffffff815fbe12)
Location: include/linux/list.h:296
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_wake_fn
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
In kernel/sched/build_utility.c (ffffffff81141e1a)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:var_wake_function
  - kernel/sched/build_utility.c:wake_bit_function
```
```
In mm/filemap.c (ffffffff812ef1f8)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - mm/filemap.c:wake_page_function
```
```
In block/blk-iocost.c (ffffffff816b20a4)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_wake_fn
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
In kernel/sched/build_utility.c (ffffffff8116cb1a)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:var_wake_function
  - kernel/sched/build_utility.c:wake_bit_function
```
```
In mm/filemap.c (ffffffff81359d08)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - mm/filemap.c:wake_page_function
```
```
In block/blk-iocost.c (ffffffff81770d14)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_wake_fn
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
In kernel/sched/build_utility.c (ffffffff8117d372)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:var_wake_function
  - kernel/sched/build_utility.c:wake_bit_function
```
```
In mm/filemap.c (ffffffff8138b648)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - mm/filemap.c:wake_page_function
```
```
In fs/eventpoll.c (ffffffff8151d37e)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_autoremove_wake_function
```
```
In block/blk-iocost.c (ffffffff817b08c4)
Location: include/linux/list.h:306
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_wake_fn
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
In kernel/sched/build_utility.c (ffffffff8118b0b2)
Location: include/linux/list.h:387
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:var_wake_function
  - kernel/sched/build_utility.c:wake_bit_function
```
```
In mm/filemap.c (ffffffff813b5168)
Location: include/linux/list.h:387
Inline: True
Inline callers:
  - mm/filemap.c:wake_page_function
```
```
In fs/eventpoll.c (ffffffff8155195e)
Location: include/linux/list.h:387
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_autoremove_wake_function
```
```
In fs/aio.c (ffffffff8155d8aa)
Location: include/linux/list.h:387
Inline: True
Inline callers:
  - fs/aio.c:aio_complete
```
```
In block/blk-iocost.c (ffffffff817f46d4)
Location: include/linux/list.h:387
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_wake_fn
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
