# Function: <code>pipelined_send</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813263fd)
Location: ipc/msg.c:569
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (ffffffff8132d807)
Location: ipc/mqueue.c:919
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8135b026)
Location: ipc/msg.c:569
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (ffffffff81362473)
Location: ipc/mqueue.c:917
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813714f2)
Location: ipc/msg.c:602
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (ffffffff81378c73)
Location: ipc/mqueue.c:917
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8138489c)
Location: ipc/msg.c:602
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (ffffffff8138be1f)
Location: ipc/mqueue.c:924
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813a8bb3)
Location: ipc/msg.c:706
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (ffffffff813b11cf)
Location: ipc/mqueue.c:924
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813d8108)
Location: ipc/msg.c:753
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (ffffffff813e1fb9)
Location: ipc/mqueue.c:870
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813f2d78)
Location: ipc/msg.c:763
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (ffffffff813fca09)
Location: ipc/mqueue.c:870
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8141e8a2)
Location: ipc/msg.c:788
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (ffffffff81428996)
Location: ipc/mqueue.c:925
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814386f2)
Location: ipc/msg.c:789
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (ffffffff814426c6)
Location: ipc/mqueue.c:924
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81488927)
Location: ipc/msg.c:808
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (ffffffff81492f86)
Location: ipc/mqueue.c:1017
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814a5f56)
Location: ipc/msg.c:808
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (ffffffff814b0886)
Location: ipc/mqueue.c:1017
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814abf1f)
Location: ipc/msg.c:810
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (ffffffff814b66d6)
Location: ipc/mqueue.c:1020
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff815043f9)
Location: ipc/msg.c:810
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (ffffffff8150f016)
Location: ipc/mqueue.c:1022
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8159629f)
Location: ipc/msg.c:810
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (ffffffff815a1b01)
Location: ipc/mqueue.c:1034
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8163f145)
Location: ipc/msg.c:816
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (ffffffff8164b581)
Location: ipc/mqueue.c:1033
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81677675)
Location: ipc/msg.c:816
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (ffffffff81683c99)
Location: ipc/mqueue.c:1033
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff816b3a35)
Location: ipc/msg.c:816
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (ffffffff816c00ad)
Location: ipc/mqueue.c:1034
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffff80001051f36c)
Location: ipc/msg.c:789
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (ffff80001052b820)
Location: ipc/mqueue.c:924
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (c06db954)
Location: ipc/msg.c:789
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (c06e391c)
Location: ipc/mqueue.c:924
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (c000000000668cb8)
Location: ipc/msg.c:789
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (c000000000677180)
Location: ipc/mqueue.c:924
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffe0003861a2)
Location: ipc/msg.c:789
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (ffffffe00038ddf0)
Location: ipc/mqueue.c:924
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_timedsend
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81430cd2)
Location: ipc/msg.c:789
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (ffffffff8143aca6)
Location: ipc/mqueue.c:924
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81421752)
Location: ipc/msg.c:789
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (ffffffff8142b716)
Location: ipc/mqueue.c:924
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8142ce72)
Location: ipc/msg.c:789
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (ffffffff81436e46)
Location: ipc/mqueue.c:924
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81444d07)
Location: ipc/msg.c:789
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (ffffffff8144d3c3)
Location: ipc/mqueue.c:924
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
```
</details>
</li>
</ul>

## Differences
