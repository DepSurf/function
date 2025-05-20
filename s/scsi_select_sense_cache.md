# Function: <code>scsi_select_sense_cache</code>

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
In drivers/scsi/scsi_lib.c (ffffffff81649c55)
Location: drivers/scsi/scsi_lib.c:48
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_exit_rq
  - drivers/scsi/scsi_lib.c:scsi_init_rq
  - drivers/scsi/scsi_lib.c:scsi_init_rq
  - drivers/scsi/scsi_lib.c:scsi_exit_request
  - drivers/scsi/scsi_lib.c:scsi_init_request
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
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
In drivers/scsi/scsi_lib.c (ffffffff816b2d85)
Location: drivers/scsi/scsi_lib.c:50
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_old_exit_rq
  - drivers/scsi/scsi_lib.c:scsi_old_init_rq
  - drivers/scsi/scsi_lib.c:scsi_old_init_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_exit_request
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
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
In drivers/scsi/scsi_lib.c (ffffffff816eeff3)
Location: drivers/scsi/scsi_lib.c:50
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_old_exit_rq
  - drivers/scsi/scsi_lib.c:scsi_old_init_rq
  - drivers/scsi/scsi_lib.c:scsi_old_init_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_exit_request
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
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
In drivers/scsi/scsi_lib.c (ffffffff81712c0e)
Location: drivers/scsi/scsi_lib.c:50
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_exit_request
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
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
In drivers/scsi/scsi_lib.c (ffffffff8174e71d)
Location: drivers/scsi/scsi_lib.c:63
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_exit_request
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
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
In drivers/scsi/scsi_lib.c (ffffffff817728cd)
Location: drivers/scsi/scsi_lib.c:63
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_exit_request
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
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
In drivers/scsi/scsi_lib.c (ffffffff81835d2b)
Location: drivers/scsi/scsi_lib.c:63
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_exit_request
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
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
In drivers/scsi/scsi_lib.c (ffffffff8184683b)
Location: drivers/scsi/scsi_lib.c:62
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_exit_request
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
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
In drivers/scsi/scsi_lib.c (ffff800010975e28)
Location: drivers/scsi/scsi_lib.c:63
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_exit_request
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
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
In drivers/scsi/scsi_lib.c (c0a4a6f0)
Location: drivers/scsi/scsi_lib.c:63
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_exit_request
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
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
In drivers/scsi/scsi_lib.c (c000000000a30234)
Location: drivers/scsi/scsi_lib.c:63
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_exit_request
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
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
In drivers/scsi/scsi_lib.c (ffffffe0005de4fe)
Location: drivers/scsi/scsi_lib.c:63
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_exit_request
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
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
In drivers/scsi/scsi_lib.c (ffffffff81726fbd)
Location: drivers/scsi/scsi_lib.c:63
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_exit_request
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
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
In drivers/scsi/scsi_lib.c (ffffffff817003ed)
Location: drivers/scsi/scsi_lib.c:63
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_exit_request
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
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
In drivers/scsi/scsi_lib.c (ffffffff81765d8d)
Location: drivers/scsi/scsi_lib.c:63
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_exit_request
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
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
In drivers/scsi/scsi_lib.c (ffffffff8178141d)
Location: drivers/scsi/scsi_lib.c:63
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_exit_request
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_init_sense_cache
```
</details>
</li>
</ul>

## Differences
