# Function: <code>request_to_qc_t</code>

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
In block/blk-mq.c (ffffffff814313e1)
Location: block/blk-mq.c:1478
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:__blk_mq_try_issue_directly
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
In block/blk-mq.c (ffffffff8145cdcf)
Location: block/blk-mq.c:1610
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:__blk_mq_try_issue_directly
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
In block/blk-mq.c (ffffffff81490696)
Location: block/blk-mq.c:1634
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:__blk_mq_try_issue_directly
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
In block/blk-mq.c (ffffffff814aaabf)
Location: include/linux/blk-mq.h:360
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_try_issue_directly
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
In block/blk-mq.c (ffffffff814d855c)
Location: include/linux/blk-mq.h:359
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:__blk_mq_try_issue_directly
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
In block/blk-mq.c (ffffffff814f190c)
Location: include/linux/blk-mq.h:367
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:__blk_mq_try_issue_directly
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
In block/blk-mq.c (ffffffff81551012)
Location: include/linux/blk-mq.h:576
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
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
In block/blk-mq.c (ffffffff8156eec8)
Location: include/linux/blk-mq.h:581
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
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
In block/blk-mq.c (ffffffff81576aa1)
Location: include/linux/blk-mq.h:598
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
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
In block/blk-exec.c (ffffffff815d37b7)
Location: include/linux/blk-mq.h:608
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq
```
```
In block/blk-mq.c (ffffffff815db751)
Location: include/linux/blk-mq.h:608
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
```
</details>
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
In block/blk-mq.c (ffff8000105f0fc8)
Location: include/linux/blk-mq.h:367
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:__blk_mq_try_issue_directly
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
In block/blk-mq.c (c079d050)
Location: include/linux/blk-mq.h:367
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
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
In block/blk-mq.c (c000000000787cb4)
Location: include/linux/blk-mq.h:367
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
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
In block/blk-mq.c (ffffffe00042fc7a)
Location: include/linux/blk-mq.h:367
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
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
In block/blk-mq.c (ffffffff814e9eec)
Location: include/linux/blk-mq.h:367
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:__blk_mq_try_issue_directly
```
```
In drivers/nvme/host/core.c (ffffffff81743b4e)
Location: include/linux/blk-mq.h:367
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:__nvme_submit_sync_cmd
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
In block/blk-mq.c (ffffffff814da44c)
Location: include/linux/blk-mq.h:367
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:__blk_mq_try_issue_directly
```
```
In drivers/nvme/host/core.c (ffffffff817257de)
Location: include/linux/blk-mq.h:367
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:__nvme_submit_sync_cmd
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
In block/blk-mq.c (ffffffff814e5f7c)
Location: include/linux/blk-mq.h:367
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:__blk_mq_try_issue_directly
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
In block/blk-mq.c (ffffffff814feeec)
Location: include/linux/blk-mq.h:367
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:__blk_mq_try_issue_directly
```
</details>
</li>
</ul>

## Differences
