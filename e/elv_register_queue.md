# Function: <code>elv_register_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int elv_register_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813b3380)
Location: block/elevator.c:792
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
  - block/blk-sysfs.c:blk_register_queue
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff813b3380-ffffffff813b3426: elv_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int elv_register_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813f7080)
Location: block/elevator.c:791
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
  - block/blk-sysfs.c:blk_register_queue
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff813f7080-ffffffff813f7126: elv_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int elv_register_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81410a90)
Location: block/elevator.c:789
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
  - block/blk-sysfs.c:blk_register_queue
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff81410a90-ffffffff81410b36: elv_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int elv_register_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8141e4e0)
Location: block/elevator.c:850
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:blk_register_queue
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff8141e4e0-ffffffff8141e58b: elv_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int elv_register_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81448c80)
Location: block/elevator.c:867
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:blk_register_queue
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff81448c80-ffffffff81448d2e: elv_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int elv_register_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8147cf90)
Location: block/elevator.c:836
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffff8147cf90-ffffffff8147d03e: elv_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int elv_register_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8149a990)
Location: block/elevator.c:472
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffff8149a990-ffffffff8149aa23: elv_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int elv_register_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814c8a60)
Location: block/elevator.c:473
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffff814c8a60-ffffffff814c8ae6: elv_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int elv_register_queue(struct request_queue *q, bool uevent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814e1b80)
Location: block/elevator.c:488
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffff814e1b80-ffffffff814e1c15: elv_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int elv_register_queue(struct request_queue *q, bool uevent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81540750)
Location: block/elevator.c:488
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch_mq
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffff81540750-ffffffff815407e2: elv_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int elv_register_queue(struct request_queue *q, bool uevent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8155cef0)
Location: block/elevator.c:482
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch_mq
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffff8155cef0-ffffffff8155cf85: elv_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int elv_register_queue(struct request_queue *q, bool uevent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81565780)
Location: block/elevator.c:482
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch_mq
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffff81565780-ffffffff81565815: elv_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int elv_register_queue(struct request_queue *q, bool uevent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815c9b70)
Location: block/elevator.c:490
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch_mq
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffff815c9b70-ffffffff815c9c05: elv_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int elv_register_queue(struct request_queue *q, bool uevent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81674ed0)
Location: block/elevator.c:495
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffff81674ed0-ffffffff81674f70: elv_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int elv_register_queue(struct request_queue *q, bool uevent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81730c80)
Location: block/elevator.c:463
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffff81730c80-ffffffff81730d1f: elv_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int elv_register_queue(struct request_queue *q, bool uevent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8176cee0)
Location: block/elevator.c:463
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffff8176cee0-ffffffff8176cf7f: elv_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int elv_register_queue(struct request_queue *q, bool uevent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff817af110)
Location: block/elevator.c:463
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffff817af110-ffffffff817af1ac: elv_register_queue (STB_GLOBAL)
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
int elv_register_queue(struct request_queue *q, bool uevent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffff8000105ded40)
Location: block/elevator.c:488
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffff8000105ded40-ffff8000105dedfc: elv_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int elv_register_queue(struct request_queue *q, bool uevent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c078bc4c)
Location: block/elevator.c:488
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
c078bc4c-c078bd00: elv_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int elv_register_queue(struct request_queue *q, bool uevent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c000000000770c40)
Location: block/elevator.c:488
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
c000000000770c40-c000000000770d38: elv_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int elv_register_queue(struct request_queue *q, bool uevent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffe000421852)
Location: block/elevator.c:488
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffe000421852-ffffffe0004218f2: elv_register_queue (STB_GLOBAL)
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
int elv_register_queue(struct request_queue *q, bool uevent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814da160)
Location: block/elevator.c:488
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffff814da160-ffffffff814da1f5: elv_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int elv_register_queue(struct request_queue *q, bool uevent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814cab10)
Location: block/elevator.c:488
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffff814cab10-ffffffff814caba5: elv_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int elv_register_queue(struct request_queue *q, bool uevent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d61f0)
Location: block/elevator.c:488
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffff814d61f0-ffffffff814d6285: elv_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int elv_register_queue(struct request_queue *q, bool uevent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814eedf0)
Location: block/elevator.c:488
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffff814eedf0-ffffffff814eee85: elv_register_queue (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool uevent</code>
</li>
</ul>
</details>
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
