# Function: <code>sbitmap_deferred_clear_bit</code>

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
In lib/sbitmap.c (ffffffff8150cc24)
Location: include/linux/sbitmap.h:336
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
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
In lib/sbitmap.c (ffffffff8153b0c4)
Location: include/linux/sbitmap.h:325
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
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
In lib/sbitmap.c (ffffffff8155bee4)
Location: include/linux/sbitmap.h:325
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
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
In lib/sbitmap.c (ffffffff815e5f74)
Location: include/linux/sbitmap.h:316
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
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
In lib/sbitmap.c (ffffffff8160a3c4)
Location: include/linux/sbitmap.h:311
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
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
In lib/sbitmap.c (ffffffff815ed589)
Location: include/linux/sbitmap.h:311
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182bac7)
Location: include/linux/sbitmap.h:311
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
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
In lib/sbitmap.c (ffffffff81659f60)
Location: include/linux/sbitmap.h:311
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b7657)
Location: include/linux/sbitmap.h:311
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
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
In lib/sbitmap.c (ffffffff81772e97)
Location: include/linux/sbitmap.h:323
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a02d4d)
Location: include/linux/sbitmap.h:323
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
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
In lib/sbitmap.c (ffffffff818a32c7)
Location: include/linux/sbitmap.h:329
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b81787)
Location: include/linux/sbitmap.h:329
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
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
In lib/sbitmap.c (ffffffff818e5617)
Location: include/linux/sbitmap.h:329
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd548d)
Location: include/linux/sbitmap.h:329
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
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
In lib/sbitmap.c (ffffffff8192c617)
Location: include/linux/sbitmap.h:329
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c2a0e5)
Location: include/linux/sbitmap.h:329
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
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
In lib/sbitmap.c (ffff80001066a414)
Location: include/linux/sbitmap.h:325
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
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
In lib/sbitmap.c (c0811d20)
Location: include/linux/sbitmap.h:325
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
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
In lib/sbitmap.c (c00000000081ec44)
Location: include/linux/sbitmap.h:325
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
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
In lib/sbitmap.c (ffffffe000494330)
Location: include/linux/sbitmap.h:325
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
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
In lib/sbitmap.c (ffffffff815544d4)
Location: include/linux/sbitmap.h:325
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
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
In lib/sbitmap.c (ffffffff81544754)
Location: include/linux/sbitmap.h:325
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
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
In lib/sbitmap.c (ffffffff81550214)
Location: include/linux/sbitmap.h:325
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
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
In lib/sbitmap.c (ffffffff8156a054)
Location: include/linux/sbitmap.h:325
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
```
</details>
</li>
</ul>

## Differences
