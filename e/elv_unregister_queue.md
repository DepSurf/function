# Function: <code>elv_unregister_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void elv_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813b3430)
Location: block/elevator.c:816
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/blk-sysfs.c:blk_unregister_queue
```
**Symbols:**

```
ffffffff813b3430-ffffffff813b3468: elv_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void elv_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813f7130)
Location: block/elevator.c:815
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/blk-sysfs.c:blk_unregister_queue
```
**Symbols:**

```
ffffffff813f7130-ffffffff813f7168: elv_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void elv_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81410b40)
Location: block/elevator.c:813
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/blk-sysfs.c:blk_unregister_queue
```
**Symbols:**

```
ffffffff81410b40-ffffffff81410b78: elv_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void elv_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/elevator.c (ffffffff8141eaff)
Location: block/elevator.c:874
Inline: True
Inline callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:blk_unregister_queue
```
**Symbols:**

```
ffffffff8141ea50-ffffffff8141ea91: elv_unregister_queue.part.18 (STB_LOCAL)
ffffffff8141eaa0-ffffffff8141eab7: elv_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void elv_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/elevator.c (ffffffff814495cf)
Location: block/elevator.c:891
Inline: True
Inline callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:blk_unregister_queue
```
**Symbols:**

```
ffffffff81449520-ffffffff81449561: elv_unregister_queue.part.20 (STB_LOCAL)
ffffffff81449570-ffffffff81449587: elv_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void elv_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/elevator.c (ffffffff8147d07f)
Location: block/elevator.c:861
Inline: True
Inline callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:blk_unregister_queue
```
**Symbols:**

```
ffffffff8147c160-ffffffff8147c1a1: elv_unregister_queue.part.26 (STB_LOCAL)
ffffffff8147d270-ffffffff8147d286: elv_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void elv_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/elevator.c (ffffffff8149a280)
Location: block/elevator.c:495
Inline: True
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
```
**Symbols:**

```
ffffffff8149a280-ffffffff8149a2c1: elv_unregister_queue.part.20 (STB_LOCAL)
ffffffff8149aa30-ffffffff8149aa46: elv_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void elv_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/elevator.c (ffffffff814c8360)
Location: block/elevator.c:496
Inline: True
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
```
**Symbols:**

```
ffffffff814c8360-ffffffff814c83a1: elv_unregister_queue.part.0 (STB_LOCAL)
ffffffff814c8af0-ffffffff814c8b06: elv_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void elv_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/elevator.c (ffffffff814e1460)
Location: block/elevator.c:516
Inline: True
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
```
**Symbols:**

```
ffffffff814e1460-ffffffff814e14a1: elv_unregister_queue.part.0 (STB_LOCAL)
ffffffff814e1c20-ffffffff814e1c36: elv_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81540863)
Location: block/elevator.c:516
Inline: True
Inline callers:
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elevator_switch_mq
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
```
**Symbols:**

```
ffffffff815407f0-ffffffff81540837: elv_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8155cfff)
Location: block/elevator.c:507
Inline: True
Inline callers:
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elevator_switch_mq
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
```
**Symbols:**

```
ffffffff8155cf90-ffffffff8155cfd7: elv_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8156588f)
Location: block/elevator.c:507
Inline: True
Inline callers:
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elevator_switch_mq
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
```
**Symbols:**

```
ffffffff81565820-ffffffff81565867: elv_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815c9c6f)
Location: block/elevator.c:515
Inline: True
Inline callers:
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elevator_switch_mq
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
```
**Symbols:**

```
ffffffff815c9c10-ffffffff815c9c48: elv_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81674f70)
Location: block/elevator.c:520
Inline: True
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffff81674f70-ffffffff81674fc6: elv_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void elv_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81730d30)
Location: block/elevator.c:488
Inline: False
Direct callers:
  - block/elevator.c:elevator_disable
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffff81730d30-ffffffff81730d80: elv_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void elv_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8176cf90)
Location: block/elevator.c:488
Inline: False
Direct callers:
  - block/elevator.c:elevator_disable
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffff8176cf90-ffffffff8176cfe0: elv_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void elv_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff817af1c0)
Location: block/elevator.c:488
Inline: False
Direct callers:
  - block/elevator.c:elevator_disable
  - block/elevator.c:elevator_switch
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
```
**Symbols:**

```
ffffffff817af1c0-ffffffff817af210: elv_unregister_queue (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void elv_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/elevator.c (ffff8000105de470)
Location: block/elevator.c:516
Inline: True
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
```
**Symbols:**

```
ffff8000105de470-ffff8000105de4cc: elv_unregister_queue.part.0 (STB_LOCAL)
ffff8000105dee00-ffff8000105dee30: elv_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void elv_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/elevator.c (c078b7c0)
Location: block/elevator.c:516
Inline: True
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
```
**Symbols:**

```
c078b7c0-c078b80c: elv_unregister_queue.part.0 (STB_LOCAL)
c078bd00-c078bd24: elv_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void elv_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/elevator.c (c000000000770400)
Location: block/elevator.c:516
Inline: True
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
```
**Symbols:**

```
c000000000770400-c000000000770484: elv_unregister_queue.part.0 (STB_LOCAL)
c000000000770d40-c000000000770d5c: elv_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void elv_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/elevator.c (ffffffe000421040)
Location: block/elevator.c:516
Inline: True
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
```
**Symbols:**

```
ffffffe000421040-ffffffe00042109a: elv_unregister_queue.part.0 (STB_LOCAL)
ffffffe0004218f2-ffffffe00042191e: elv_unregister_queue (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void elv_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/elevator.c (ffffffff814d9a40)
Location: block/elevator.c:516
Inline: True
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
```
**Symbols:**

```
ffffffff814d9a40-ffffffff814d9a81: elv_unregister_queue.part.0 (STB_LOCAL)
ffffffff814da200-ffffffff814da216: elv_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void elv_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/elevator.c (ffffffff814ca3f0)
Location: block/elevator.c:516
Inline: True
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
```
**Symbols:**

```
ffffffff814ca3f0-ffffffff814ca431: elv_unregister_queue.part.0 (STB_LOCAL)
ffffffff814cabb0-ffffffff814cabc6: elv_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void elv_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/elevator.c (ffffffff814d5ad0)
Location: block/elevator.c:516
Inline: True
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
```
**Symbols:**

```
ffffffff814d5ad0-ffffffff814d5b11: elv_unregister_queue.part.0 (STB_LOCAL)
ffffffff814d6290-ffffffff814d62a6: elv_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void elv_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/elevator.c (ffffffff814ee940)
Location: block/elevator.c:516
Inline: True
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
```
**Symbols:**

```
ffffffff814ee940-ffffffff814ee981: elv_unregister_queue.part.0 (STB_LOCAL)
ffffffff814eee90-ffffffff814eeea6: elv_unregister_queue (STB_GLOBAL)
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
