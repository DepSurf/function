# Function: <code>ss_wakeup</code>

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
In ipc/msg.c (ffffffff81325985)
Location: ipc/msg.c:175
Inline: True
Inline callers:
  - ipc/msg.c:freeque
  - ipc/msg.c:do_msgrcv
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
In ipc/msg.c (ffffffff8135b557)
Location: ipc/msg.c:175
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ss_wakeup(struct msg_queue *msq, struct wake_q_head *wake_q, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81370a10)
Location: ipc/msg.c:178
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff81370a10-ffffffff81370ae9: ss_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ss_wakeup(struct msg_queue *msq, struct wake_q_head *wake_q, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81383db0)
Location: ipc/msg.c:178
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff81383db0-ffffffff81383e8e: ss_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ss_wakeup(struct msg_queue *msq, struct wake_q_head *wake_q, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813a8350)
Location: ipc/msg.c:179
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff813a8350-ffffffff813a842e: ss_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ss_wakeup(struct msg_queue *msq, struct wake_q_head *wake_q, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813d7580)
Location: ipc/msg.c:196
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff813d7580-ffffffff813d7664: ss_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ss_wakeup(struct msg_queue *msq, struct wake_q_head *wake_q, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813f1b90)
Location: ipc/msg.c:197
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff813f1b90-ffffffff813f1c74: ss_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ss_wakeup(struct msg_queue *msq, struct wake_q_head *wake_q, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8141de70)
Location: ipc/msg.c:197
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff8141de70-ffffffff8141df63: ss_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ss_wakeup(struct msg_queue *msq, struct wake_q_head *wake_q, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81437cc0)
Location: ipc/msg.c:197
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff81437cc0-ffffffff81437db3: ss_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ss_wakeup(struct msg_queue *msq, struct wake_q_head *wake_q, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81487c90)
Location: ipc/msg.c:211
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff81487c90-ffffffff81487d83: ss_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ss_wakeup(struct msg_queue *msq, struct wake_q_head *wake_q, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814a52b0)
Location: ipc/msg.c:211
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff814a52b0-ffffffff814a53a3: ss_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ss_wakeup(struct msg_queue *msq, struct wake_q_head *wake_q, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814ab250)
Location: ipc/msg.c:211
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff814ab250-ffffffff814ab343: ss_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ss_wakeup(struct msg_queue *msq, struct wake_q_head *wake_q, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81503710)
Location: ipc/msg.c:211
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff81503710-ffffffff81503803: ss_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ss_wakeup(struct msg_queue *msq, struct wake_q_head *wake_q, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81595010)
Location: ipc/msg.c:211
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff81595010-ffffffff81595102: ss_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ss_wakeup(struct msg_queue *msq, struct wake_q_head *wake_q, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8163dd30)
Location: ipc/msg.c:212
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff8163dd30-ffffffff8163de22: ss_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ss_wakeup(struct msg_queue *msq, struct wake_q_head *wake_q, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81676220)
Location: ipc/msg.c:212
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff81676220-ffffffff81676312: ss_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ss_wakeup(struct msg_queue *msq, struct wake_q_head *wake_q, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff816b25e0)
Location: ipc/msg.c:212
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff816b25e0-ffffffff816b26d2: ss_wakeup (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/msg.c (ffff80001051ed98)
Location: ipc/msg.c:197
Inline: True
Inline callers:
  - ipc/msg.c:freeque
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:msgctl_down
```
**Symbols:**

```
ffff80001051ec30-ffff80001051ed14: ss_wakeup.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/msg.c (c06dab64)
Location: ipc/msg.c:197
Inline: True
Inline callers:
  - ipc/msg.c:freeque
Direct callers:
  - ipc/msg.c:msgctl_down
```
**Symbols:**

```
c06dae58-c06daf18: ss_wakeup.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/msg.c (c000000000668758)
Location: ipc/msg.c:197
Inline: True
Inline callers:
  - ipc/msg.c:freeque
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:msgctl_down
```
**Symbols:**

```
c000000000668380-c0000000006684a8: ss_wakeup.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/msg.c (ffffffe000385e50)
Location: ipc/msg.c:197
Inline: True
Inline callers:
  - ipc/msg.c:freeque
Direct callers:
  - ipc/msg.c:msgctl_down
```
**Symbols:**

```
ffffffe000385d4e-ffffffe000385df0: ss_wakeup.constprop.0 (STB_LOCAL)
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
void ss_wakeup(struct msg_queue *msq, struct wake_q_head *wake_q, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814302a0)
Location: ipc/msg.c:197
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff814302a0-ffffffff81430393: ss_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ss_wakeup(struct msg_queue *msq, struct wake_q_head *wake_q, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81420d20)
Location: ipc/msg.c:197
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff81420d20-ffffffff81420e13: ss_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ss_wakeup(struct msg_queue *msq, struct wake_q_head *wake_q, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8142c440)
Location: ipc/msg.c:197
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff8142c440-ffffffff8142c533: ss_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ss_wakeup(struct msg_queue *msq, struct wake_q_head *wake_q, bool kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81443790)
Location: ipc/msg.c:197
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:msgctl_down
  - ipc/msg.c:freeque
```
**Symbols:**

```
ffffffff81443790-ffffffff81443883: ss_wakeup (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
