# Function: <code>scsi_uninit_cmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff815ad10c)
Location: drivers/scsi/scsi_lib.c:615
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_unprep_fn
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8160504c)
Location: drivers/scsi/scsi_lib.c:521
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_unprep_fn
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8163472c)
Location: drivers/scsi/scsi_lib.c:530
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_unprep_fn
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void scsi_uninit_cmd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81649010)
Location: drivers/scsi/scsi_lib.c:559
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_unprep_fn
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
**Symbols:**

```
ffffffff81649010-ffffffff8164904f: scsi_uninit_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_uninit_cmd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b2100)
Location: drivers/scsi/scsi_lib.c:584
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_unprep_fn
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
**Symbols:**

```
ffffffff816b2100-ffffffff816b2142: scsi_uninit_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_uninit_cmd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816ee410)
Location: drivers/scsi/scsi_lib.c:597
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_unprep_fn
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
**Symbols:**

```
ffffffff816ee410-ffffffff816ee451: scsi_uninit_cmd (STB_LOCAL)
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
In drivers/scsi/scsi_lib.c (ffffffff817145d2)
Location: drivers/scsi/scsi_lib.c:547
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
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
In drivers/scsi/scsi_lib.c (ffffffff8174ff33)
Location: drivers/scsi/scsi_lib.c:544
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
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
In drivers/scsi/scsi_lib.c (ffffffff81774123)
Location: drivers/scsi/scsi_lib.c:544
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void scsi_uninit_cmd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81834230)
Location: drivers/scsi/scsi_lib.c:524
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
```
**Symbols:**

```
ffffffff81834230-ffffffff81834271: scsi_uninit_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void scsi_uninit_cmd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81844bc0)
Location: drivers/scsi/scsi_lib.c:509
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
```
**Symbols:**

```
ffffffff81844bc0-ffffffff81844bfe: scsi_uninit_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void scsi_uninit_cmd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81827db0)
Location: drivers/scsi/scsi_lib.c:476
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
```
**Symbols:**

```
ffffffff81827db0-ffffffff81827dee: scsi_uninit_cmd (STB_LOCAL)
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
In drivers/scsi/scsi_lib.c (ffffffff818b794f)
Location: drivers/scsi/scsi_lib.c:481
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81a02ec3)
Location: drivers/scsi/scsi_lib.c:482
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b81a15)
Location: drivers/scsi/scsi_lib.c:478
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd575a)
Location: drivers/scsi/scsi_lib.c:477
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c2a3ae)
Location: drivers/scsi/scsi_lib.c:475
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
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
In drivers/scsi/scsi_lib.c (ffff800010978188)
Location: drivers/scsi/scsi_lib.c:544
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
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
In drivers/scsi/scsi_lib.c (c0a4bf98)
Location: drivers/scsi/scsi_lib.c:544
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
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
In drivers/scsi/scsi_lib.c (c000000000a325ec)
Location: drivers/scsi/scsi_lib.c:544
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
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
In drivers/scsi/scsi_lib.c (ffffffe0005dfc38)
Location: drivers/scsi/scsi_lib.c:544
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
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
In drivers/scsi/scsi_lib.c (ffffffff81728813)
Location: drivers/scsi/scsi_lib.c:544
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
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
In drivers/scsi/scsi_lib.c (ffffffff81701c43)
Location: drivers/scsi/scsi_lib.c:544
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
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
In drivers/scsi/scsi_lib.c (ffffffff817675e3)
Location: drivers/scsi/scsi_lib.c:544
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
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
In drivers/scsi/scsi_lib.c (ffffffff81782d03)
Location: drivers/scsi/scsi_lib.c:544
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
