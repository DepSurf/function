# Function: <code>elevator_switch</code>

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
In block/elevator.c (ffffffff813b3702)
Location: block/elevator.c:894
Inline: True
Inline callers:
  - block/elevator.c:__elevator_change
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
In block/elevator.c (ffffffff813f7405)
Location: block/elevator.c:893
Inline: True
Inline callers:
  - block/elevator.c:__elevator_change
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
In block/elevator.c (ffffffff81410e15)
Location: block/elevator.c:891
Inline: True
Inline callers:
  - block/elevator.c:__elevator_change
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int elevator_switch(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8141eac0)
Location: block/elevator.c:990
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elv_iosched_store
```
**Symbols:**

```
ffffffff8141eac0-ffffffff8141ecba: elevator_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int elevator_switch(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81449590)
Location: block/elevator.c:1007
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elv_iosched_store
```
**Symbols:**

```
ffffffff81449590-ffffffff8144979b: elevator_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int elevator_switch(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8147d040)
Location: block/elevator.c:1016
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elv_iosched_store
```
**Symbols:**

```
ffffffff8147d040-ffffffff8147d266: elevator_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int elevator_switch(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8149ab20)
Location: block/elevator.c:638
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elv_iosched_store
```
**Symbols:**

```
ffffffff8149ab20-ffffffff8149ab65: elevator_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int elevator_switch(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814c8c00)
Location: block/elevator.c:637
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elv_iosched_store
```
**Symbols:**

```
ffffffff814c8c00-ffffffff814c8c47: elevator_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int elevator_switch(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814e1d40)
Location: block/elevator.c:710
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elv_iosched_store
```
**Symbols:**

```
ffffffff814e1d40-ffffffff814e1d87: elevator_switch (STB_LOCAL)
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
In block/elevator.c (ffffffff81540a1b)
Location: block/elevator.c:710
Inline: True
Inline callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
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
In block/elevator.c (ffffffff8155d19b)
Location: block/elevator.c:703
Inline: True
Inline callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
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
In block/elevator.c (ffffffff81565a27)
Location: block/elevator.c:704
Inline: True
Inline callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
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
In block/elevator.c (ffffffff815c9df7)
Location: block/elevator.c:722
Inline: True
Inline callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
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
In block/elevator.c (ffffffff816751b9)
Location: block/elevator.c:726
Inline: True
Inline callers:
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int elevator_switch(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81730f50)
Location: block/elevator.c:657
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff81730f50-ffffffff817310c0: elevator_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int elevator_switch(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8176d1b0)
Location: block/elevator.c:660
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff8176d1b0-ffffffff8176d320: elevator_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int elevator_switch(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff817af3e0)
Location: block/elevator.c:660
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff817af3e0-ffffffff817af550: elevator_switch (STB_GLOBAL)
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
int elevator_switch(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffff8000105def30)
Location: block/elevator.c:710
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elv_iosched_store
```
**Symbols:**

```
ffff8000105def30-ffff8000105def8c: elevator_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int elevator_switch(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c078be24)
Location: block/elevator.c:710
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
```
**Symbols:**

```
c078be24-c078be74: elevator_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int elevator_switch(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c000000000770ed0)
Location: block/elevator.c:710
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elv_iosched_store
```
**Symbols:**

```
c000000000770ed0-c000000000770f54: elevator_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int elevator_switch(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffe000421a00)
Location: block/elevator.c:710
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elv_iosched_store
```
**Symbols:**

```
ffffffe000421a00-ffffffe000421a5e: elevator_switch (STB_LOCAL)
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
int elevator_switch(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814da320)
Location: block/elevator.c:710
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elv_iosched_store
```
**Symbols:**

```
ffffffff814da320-ffffffff814da367: elevator_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int elevator_switch(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814cacd0)
Location: block/elevator.c:710
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elv_iosched_store
```
**Symbols:**

```
ffffffff814cacd0-ffffffff814cad17: elevator_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int elevator_switch(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d63b0)
Location: block/elevator.c:710
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elv_iosched_store
```
**Symbols:**

```
ffffffff814d63b0-ffffffff814d63f7: elevator_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int elevator_switch(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814eefb0)
Location: block/elevator.c:710
Inline: False
Direct callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elv_iosched_store
```
**Symbols:**

```
ffffffff814eefb0-ffffffff814eeff7: elevator_switch (STB_LOCAL)
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
