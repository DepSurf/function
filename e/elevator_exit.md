# Function: <code>elevator_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void elevator_exit(struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813b32c0)
Location: block/elevator.c:234
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
  - block/blk-sysfs.c:blk_release_queue
```
**Symbols:**

```
ffffffff813b32c0-ffffffff813b3305: elevator_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void elevator_exit(struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813f6fc0)
Location: block/elevator.c:234
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
  - block/blk-sysfs.c:blk_release_queue
```
**Symbols:**

```
ffffffff813f6fc0-ffffffff813f7005: elevator_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void elevator_exit(struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814109d0)
Location: block/elevator.c:234
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
  - block/blk-sysfs.c:blk_release_queue
```
**Symbols:**

```
ffffffff814109d0-ffffffff81410a15: elevator_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void elevator_exit(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8141e400)
Location: block/elevator.c:256
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff8141e400-ffffffff8141e466: elevator_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void elevator_exit(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81448ba0)
Location: block/elevator.c:273
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff81448ba0-ffffffff81448c09: elevator_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void elevator_exit(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8147c5a0)
Location: block/elevator.c:243
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/blk-core.c:blk_exit_queue
```
**Symbols:**

```
ffffffff8147c5a0-ffffffff8147c609: elevator_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void elevator_exit(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8149a5b0)
Location: block/elevator.c:180
Inline: False
Direct callers:
  - block/blk-core.c:blk_exit_queue
```
**Symbols:**

```
ffffffff8149a5b0-ffffffff8149a5fd: elevator_exit (STB_GLOBAL)
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
In block/elevator.c (ffffffff814c8b47)
Location: block/blk.h:194
Inline: True
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
In block/elevator.c (ffffffff814e1c7d)
Location: block/blk.h:206
Inline: True
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
In block/elevator.c (ffffffff81540880)
Location: block/blk.h:205
Inline: True
Inline callers:
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elevator_switch_mq
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
In block/elevator.c (ffffffff8155d01c)
Location: block/blk.h:196
Inline: True
Inline callers:
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elevator_switch_mq
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
In block/elevator.c (ffffffff815658ac)
Location: block/blk.h:202
Inline: True
Inline callers:
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elevator_switch_mq
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
In block/elevator.c (ffffffff815c9c8c)
Location: block/blk.h:206
Inline: True
Inline callers:
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elevator_switch_mq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void elevator_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81674900)
Location: block/elevator.c:191
Inline: True
Direct callers:
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff81674900-ffffffff8167495b: elevator_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void elevator_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff817310f6)
Location: block/elevator.c:159
Inline: True
Inline callers:
  - block/elevator.c:elevator_disable
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff81730620-ffffffff8173067b: elevator_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void elevator_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8176d356)
Location: block/elevator.c:159
Inline: True
Inline callers:
  - block/elevator.c:elevator_disable
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff8176c880-ffffffff8176c8db: elevator_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void elevator_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff817af586)
Location: block/elevator.c:159
Inline: True
Inline callers:
  - block/elevator.c:elevator_disable
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff817aeab0-ffffffff817aeb0b: elevator_exit (STB_GLOBAL)
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
In block/elevator.c (ffff8000105dee78)
Location: block/blk.h:206
Inline: True
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
In block/elevator.c (c078bd70)
Location: block/blk.h:206
Inline: True
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
In block/elevator.c (c000000000770dc0)
Location: block/blk.h:206
Inline: True
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
In block/elevator.c (ffffffe000421954)
Location: block/blk.h:206
Inline: True
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
In block/elevator.c (ffffffff814da25d)
Location: block/blk.h:206
Inline: True
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
In block/elevator.c (ffffffff814cac0d)
Location: block/blk.h:206
Inline: True
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
In block/elevator.c (ffffffff814d62ed)
Location: block/blk.h:206
Inline: True
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
In block/elevator.c (ffffffff814eeeeb)
Location: block/blk.h:206
Inline: True
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param reordered. </b>
<code>e</code> ➡️ <code>q, e</code>
</li>
</ul>
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
