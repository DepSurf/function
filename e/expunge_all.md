# Function: <code>expunge_all</code>

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
In ipc/msg.c (ffffffff81325941)
Location: ipc/msg.c:186
Inline: True
Inline callers:
  - ipc/msg.c:freeque
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
In ipc/msg.c (ffffffff8135a541)
Location: ipc/msg.c:186
Inline: True
Inline callers:
  - ipc/msg.c:freeque
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
In ipc/msg.c (ffffffff81370b14)
Location: ipc/msg.c:215
Inline: True
Inline callers:
  - ipc/msg.c:freeque
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81383ead)
Location: ipc/msg.c:215
Inline: True
Inline callers:
  - ipc/msg.c:freeque
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
In ipc/msg.c (ffffffff813a86a3)
Location: ipc/msg.c:216
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
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
In ipc/msg.c (ffffffff813d8642)
Location: ipc/msg.c:233
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
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
In ipc/msg.c (ffffffff813f32b2)
Location: ipc/msg.c:234
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
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
In ipc/msg.c (ffffffff8141efca)
Location: ipc/msg.c:234
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
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
In ipc/msg.c (ffffffff81438e1f)
Location: ipc/msg.c:234
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void expunge_all(struct msg_queue *msq, int res, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814881a0)
Location: ipc/msg.c:248
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff814881a0-ffffffff8148822e: expunge_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void expunge_all(struct msg_queue *msq, int res, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814a57c0)
Location: ipc/msg.c:248
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff814a57c0-ffffffff814a584e: expunge_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void expunge_all(struct msg_queue *msq, int res, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814ab770)
Location: ipc/msg.c:248
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff814ab770-ffffffff814ab816: expunge_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void expunge_all(struct msg_queue *msq, int res, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81503c30)
Location: ipc/msg.c:248
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff81503c30-ffffffff81503cd6: expunge_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void expunge_all(struct msg_queue *msq, int res, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff815955e0)
Location: ipc/msg.c:248
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff815955e0-ffffffff81595699: expunge_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void expunge_all(struct msg_queue *msq, int res, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8163e560)
Location: ipc/msg.c:249
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff8163e560-ffffffff8163e619: expunge_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void expunge_all(struct msg_queue *msq, int res, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81676a50)
Location: ipc/msg.c:249
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff81676a50-ffffffff81676b09: expunge_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void expunge_all(struct msg_queue *msq, int res, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff816b2e10)
Location: ipc/msg.c:249
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff816b2e10-ffffffff816b2ec9: expunge_all (STB_LOCAL)
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
In ipc/msg.c (ffff800010520280)
Location: ipc/msg.c:234
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
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
In ipc/msg.c (c06db068)
Location: ipc/msg.c:234
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
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
In ipc/msg.c (c0000000006694f4)
Location: ipc/msg.c:234
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
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
In ipc/msg.c (ffffffe00038653c)
Location: ipc/msg.c:234
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
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
In ipc/msg.c (ffffffff814313ff)
Location: ipc/msg.c:234
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
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
In ipc/msg.c (ffffffff81421e7f)
Location: ipc/msg.c:234
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
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
In ipc/msg.c (ffffffff8142d59f)
Location: ipc/msg.c:234
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
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
In ipc/msg.c (ffffffff81443fc9)
Location: ipc/msg.c:234
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
