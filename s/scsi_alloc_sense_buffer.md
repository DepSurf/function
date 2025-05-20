# Function: <code>scsi_alloc_sense_buffer</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81649ef0)
Location: drivers/scsi/scsi_lib.c:60
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_rq
  - drivers/scsi/scsi_lib.c:scsi_init_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b3040)
Location: drivers/scsi/scsi_lib.c:62
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_old_init_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816ef260)
Location: drivers/scsi/scsi_lib.c:62
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_old_init_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81712c4e)
Location: drivers/scsi/scsi_lib.c:62
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
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
In drivers/scsi/scsi_lib.c (ffffffff8174e76e)
Location: drivers/scsi/scsi_lib.c:75
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
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
In drivers/scsi/scsi_lib.c (ffffffff8177291e)
Location: drivers/scsi/scsi_lib.c:75
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
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
In drivers/scsi/scsi_lib.c (ffffffff81835a44)
Location: drivers/scsi/scsi_lib.c:75
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
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
In drivers/scsi/scsi_lib.c (ffffffff818465a4)
Location: drivers/scsi/scsi_lib.c:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/scsi/scsi_lib.c (ffff800010975ea8)
Location: drivers/scsi/scsi_lib.c:75
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
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
In drivers/scsi/scsi_lib.c (c0a4a74c)
Location: drivers/scsi/scsi_lib.c:75
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
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
In drivers/scsi/scsi_lib.c (c000000000a302d0)
Location: drivers/scsi/scsi_lib.c:75
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
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
In drivers/scsi/scsi_lib.c (ffffffe0005de564)
Location: drivers/scsi/scsi_lib.c:75
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
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
In drivers/scsi/scsi_lib.c (ffffffff8172700e)
Location: drivers/scsi/scsi_lib.c:75
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
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
In drivers/scsi/scsi_lib.c (ffffffff8170043e)
Location: drivers/scsi/scsi_lib.c:75
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
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
In drivers/scsi/scsi_lib.c (ffffffff81765dde)
Location: drivers/scsi/scsi_lib.c:75
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
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
In drivers/scsi/scsi_lib.c (ffffffff8178146e)
Location: drivers/scsi/scsi_lib.c:75
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
```
</details>
</li>
</ul>

## Differences
