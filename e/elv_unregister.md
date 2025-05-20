# Function: <code>elv_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void elv_unregister(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813b3610)
Location: block/elevator.c:869
Inline: False
Direct callers:
  - block/noop-iosched.c:noop_exit
  - block/deadline-iosched.c:deadline_exit
  - block/cfq-iosched.c:cfq_exit
```
**Symbols:**

```
ffffffff813b3610-ffffffff813b367e: elv_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void elv_unregister(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813f7310)
Location: block/elevator.c:868
Inline: False
Direct callers:
  - block/noop-iosched.c:noop_exit
  - block/deadline-iosched.c:deadline_exit
  - block/cfq-iosched.c:cfq_exit
```
**Symbols:**

```
ffffffff813f7310-ffffffff813f737e: elv_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void elv_unregister(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81410d20)
Location: block/elevator.c:866
Inline: False
Direct callers:
  - block/noop-iosched.c:noop_exit
  - block/deadline-iosched.c:deadline_exit
  - block/cfq-iosched.c:cfq_exit
```
**Symbols:**

```
ffffffff81410d20-ffffffff81410d8e: elv_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8141ecc0)
Location: block/elevator.c:929
Inline: True
Direct callers:
  - block/noop-iosched.c:noop_exit
  - block/deadline-iosched.c:deadline_exit
  - block/cfq-iosched.c:cfq_exit
```
**Symbols:**

```
ffffffff8141ecc0-ffffffff8141ed2e: elv_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814497a0)
Location: block/elevator.c:946
Inline: True
Direct callers:
  - block/noop-iosched.c:noop_exit
  - block/deadline-iosched.c:deadline_exit
  - block/cfq-iosched.c:cfq_exit
```
**Symbols:**

```
ffffffff814497a0-ffffffff8144980e: elv_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8147c270)
Location: block/elevator.c:917
Inline: True
Direct callers:
  - block/noop-iosched.c:noop_exit
  - block/deadline-iosched.c:deadline_exit
  - block/cfq-iosched.c:cfq_exit
```
**Symbols:**

```
ffffffff8147c270-ffffffff8147c2de: elv_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8149a370)
Location: block/elevator.c:544
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_exit
```
**Symbols:**

```
ffffffff8149a370-ffffffff8149a3de: elv_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814c8460)
Location: block/elevator.c:543
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_exit
```
**Symbols:**

```
ffffffff814c8460-ffffffff814c84ce: elv_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814e1560)
Location: block/elevator.c:562
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_exit
```
**Symbols:**

```
ffffffff814e1560-ffffffff814e15ce: elv_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81540070)
Location: block/elevator.c:562
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_exit
```
**Symbols:**

```
ffffffff81540070-ffffffff815400e1: elv_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8155c810)
Location: block/elevator.c:555
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_exit
```
**Symbols:**

```
ffffffff8155c810-ffffffff8155c881: elv_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815650a0)
Location: block/elevator.c:555
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_exit
```
**Symbols:**

```
ffffffff815650a0-ffffffff81565111: elv_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815c9420)
Location: block/elevator.c:565
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_exit
```
**Symbols:**

```
ffffffff815c9420-ffffffff815c9491: elv_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff816744a0)
Location: block/elevator.c:572
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_exit
```
**Symbols:**

```
ffffffff816744a0-ffffffff8167451b: elv_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff817301d0)
Location: block/elevator.c:536
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_exit
```
**Symbols:**

```
ffffffff817301d0-ffffffff8173024b: elv_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8176c400)
Location: block/elevator.c:539
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_exit
```
**Symbols:**

```
ffffffff8176c400-ffffffff8176c47b: elv_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff817ae5f0)
Location: block/elevator.c:539
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_exit
```
**Symbols:**

```
ffffffff817ae5f0-ffffffff817ae66b: elv_unregister (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffff8000105de4d0)
Location: block/elevator.c:562
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_exit
```
**Symbols:**

```
ffff8000105de4d0-ffff8000105de580: elv_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (c078b740)
Location: block/elevator.c:562
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_exit
```
**Symbols:**

```
c078b740-c078b7c0: elv_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (c000000000770330)
Location: block/elevator.c:562
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_exit
```
**Symbols:**

```
c000000000770330-c000000000770400: elv_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffe000421172)
Location: block/elevator.c:562
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_exit
```
**Symbols:**

```
ffffffe000421172-ffffffe000421218: elv_unregister (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d9b40)
Location: block/elevator.c:562
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_exit
```
**Symbols:**

```
ffffffff814d9b40-ffffffff814d9bae: elv_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814ca4f0)
Location: block/elevator.c:562
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_exit
```
**Symbols:**

```
ffffffff814ca4f0-ffffffff814ca55e: elv_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d5bd0)
Location: block/elevator.c:562
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_exit
```
**Symbols:**

```
ffffffff814d5bd0-ffffffff814d5c3e: elv_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void elv_unregister(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814ee8d0)
Location: block/elevator.c:562
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_exit
```
**Symbols:**

```
ffffffff814ee8d0-ffffffff814ee93c: elv_unregister (STB_GLOBAL)
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
