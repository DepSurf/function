# Function: <code>scsi_run_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void scsi_run_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff815ad3a0)
Location: drivers/scsi/scsi_lib.c:486
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_requeue_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff815ad3a0-ffffffff815ad65c: scsi_run_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void scsi_run_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816052d0)
Location: drivers/scsi/scsi_lib.c:452
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_requeue_run_queue
```
**Symbols:**

```
ffffffff816052d0-ffffffff816055a3: scsi_run_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void scsi_run_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816347f0)
Location: drivers/scsi/scsi_lib.c:461
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_requeue_run_queue
```
**Symbols:**

```
ffffffff816347f0-ffffffff81634ac3: scsi_run_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void scsi_run_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81649840)
Location: drivers/scsi/scsi_lib.c:490
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_device_resume
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_requeue_run_queue
```
**Symbols:**

```
ffffffff81649840-ffffffff81649b0b: scsi_run_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_run_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b2a60)
Location: drivers/scsi/scsi_lib.c:515
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_requeue_run_queue
```
**Symbols:**

```
ffffffff816b2a60-ffffffff816b2d2b: scsi_run_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_run_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816eebd0)
Location: drivers/scsi/scsi_lib.c:528
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_requeue_run_queue
```
**Symbols:**

```
ffffffff816eebd0-ffffffff816eee97: scsi_run_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scsi_run_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81712740)
Location: drivers/scsi/scsi_lib.c:517
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_requeue_run_queue
```
**Symbols:**

```
ffffffff81712740-ffffffff817129ec: scsi_run_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void scsi_run_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8174e0b0)
Location: drivers/scsi/scsi_lib.c:514
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_requeue_run_queue
```
**Symbols:**

```
ffffffff8174e0b0-ffffffff8174e381: scsi_run_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void scsi_run_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81772260)
Location: drivers/scsi/scsi_lib.c:514
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_requeue_run_queue
```
**Symbols:**

```
ffffffff81772260-ffffffff81772531: scsi_run_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void scsi_run_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81834a00)
Location: drivers/scsi/scsi_lib.c:494
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_unblock_requests
  - drivers/scsi/scsi_lib.c:scsi_requeue_run_queue
```
**Symbols:**

```
ffffffff81834a00-ffffffff81834a51: scsi_run_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void scsi_run_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818453e0)
Location: drivers/scsi/scsi_lib.c:479
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_unblock_requests
  - drivers/scsi/scsi_lib.c:scsi_requeue_run_queue
```
**Symbols:**

```
ffffffff818453e0-ffffffff81845431: scsi_run_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void scsi_run_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81828480)
Location: drivers/scsi/scsi_lib.c:446
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_unblock_requests
  - drivers/scsi/scsi_lib.c:scsi_requeue_run_queue
```
**Symbols:**

```
ffffffff81828480-ffffffff818285b7: scsi_run_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void scsi_run_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b3dc0)
Location: drivers/scsi/scsi_lib.c:451
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_unblock_requests
  - drivers/scsi/scsi_lib.c:scsi_requeue_run_queue
```
**Symbols:**

```
ffffffff818b3dc0-ffffffff818b3ef7: scsi_run_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void scsi_run_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff819feda0)
Location: drivers/scsi/scsi_lib.c:452
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_unblock_requests
  - drivers/scsi/scsi_lib.c:scsi_requeue_run_queue
```
**Symbols:**

```
ffffffff819feda0-ffffffff819feee8: scsi_run_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scsi_run_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b7d3f0)
Location: drivers/scsi/scsi_lib.c:448
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_unblock_requests
  - drivers/scsi/scsi_lib.c:scsi_requeue_run_queue
```
**Symbols:**

```
ffffffff81b7d3f0-ffffffff81b7d4b8: scsi_run_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scsi_run_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd1170)
Location: drivers/scsi/scsi_lib.c:446
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_unblock_requests
  - drivers/scsi/scsi_lib.c:scsi_requeue_run_queue
```
**Symbols:**

```
ffffffff81bd1170-ffffffff81bd1243: scsi_run_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scsi_run_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c25de0)
Location: drivers/scsi/scsi_lib.c:444
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_unblock_requests
  - drivers/scsi/scsi_lib.c:scsi_requeue_run_queue
```
**Symbols:**

```
ffffffff81c25de0-ffffffff81c25eb1: scsi_run_queue (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void scsi_run_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffff800010977398)
Location: drivers/scsi/scsi_lib.c:514
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_requeue_run_queue
```
**Symbols:**

```
ffff800010977398-ffff800010977838: scsi_run_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void scsi_run_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c0a49ff8)
Location: drivers/scsi/scsi_lib.c:514
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_requeue_run_queue
```
**Symbols:**

```
c0a49ff8-c0a4a2c0: scsi_run_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void scsi_run_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c000000000a2f920)
Location: drivers/scsi/scsi_lib.c:514
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_requeue_run_queue
```
**Symbols:**

```
c000000000a2f920-c000000000a2fca8: scsi_run_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void scsi_run_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffe0005ddf80)
Location: drivers/scsi/scsi_lib.c:514
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_requeue_run_queue
```
**Symbols:**

```
ffffffe0005ddf80-ffffffe0005de1bc: scsi_run_queue (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void scsi_run_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81726950)
Location: drivers/scsi/scsi_lib.c:514
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_requeue_run_queue
```
**Symbols:**

```
ffffffff81726950-ffffffff81726c21: scsi_run_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void scsi_run_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816ffd80)
Location: drivers/scsi/scsi_lib.c:514
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_requeue_run_queue
```
**Symbols:**

```
ffffffff816ffd80-ffffffff81700051: scsi_run_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void scsi_run_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81765720)
Location: drivers/scsi/scsi_lib.c:514
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_requeue_run_queue
```
**Symbols:**

```
ffffffff81765720-ffffffff817659f1: scsi_run_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void scsi_run_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81780db0)
Location: drivers/scsi/scsi_lib.c:514
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_host_queues
  - drivers/scsi/scsi_lib.c:scsi_requeue_run_queue
```
**Symbols:**

```
ffffffff81780db0-ffffffff81781081: scsi_run_queue (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
