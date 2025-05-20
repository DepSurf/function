# Function: <code>mempool_create_kmalloc_pool</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8186b2e8)
Location: include/linux/mempool.h:86
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (ffffffff8189d0d2)
Location: include/linux/mempool.h:86
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8196d7ca)
Location: include/linux/mempool.h:86
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8197472c)
Location: include/linux/mempool.h:86
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
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
In drivers/md/md.c (ffffffff8195874e)
Location: include/linux/mempool.h:86
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
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
In drivers/md/md.c (ffffffff819fdeed)
Location: include/linux/mempool.h:86
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
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
In mm/page_io.c (ffffffff8137987e)
Location: include/linux/mempool.h:86
Inline: True
Inline callers:
  - mm/page_io.c:sio_pool_init
```
```
In drivers/md/md.c (ffffffff81b654c4)
Location: include/linux/mempool.h:86
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
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
In mm/page_io.c (ffffffff813f72fe)
Location: include/linux/mempool.h:91
Inline: True
Inline callers:
  - mm/page_io.c:sio_pool_init
```
```
In drivers/md/md.c (ffffffff81d006d2)
Location: include/linux/mempool.h:91
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
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
In mm/page_io.c (ffffffff8142a5ee)
Location: include/linux/mempool.h:91
Inline: True
Inline callers:
  - mm/page_io.c:sio_pool_init
```
```
In drivers/md/md.c (ffffffff81d638b3)
Location: include/linux/mempool.h:91
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
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
In mm/page_io.c (ffffffff81463cae)
Location: include/linux/mempool.h:92
Inline: True
Inline callers:
  - mm/page_io.c:sio_pool_init
```
```
In drivers/md/md.c (ffffffff81e1a80e)
Location: include/linux/mempool.h:92
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
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
In drivers/md/md.c (ffff800010af1c24)
Location: include/linux/mempool.h:86
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (c0bd3190)
Location: include/linux/mempool.h:86
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (c000000000bde2b4)
Location: include/linux/mempool.h:86
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (ffffffe0006e5a36)
Location: include/linux/mempool.h:86
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (ffffffff81842f52)
Location: include/linux/mempool.h:86
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (ffffffff8180a5b2)
Location: include/linux/mempool.h:86
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (ffffffff81892582)
Location: include/linux/mempool.h:86
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (ffffffff818ae15d)
Location: include/linux/mempool.h:86
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
</details>
</li>
</ul>

## Differences
