# Function: <code>netlink_rcv_wake</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void netlink_rcv_wake(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8174afc0)
Location: net/netlink/af_netlink.c:293
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_poll
```
**Symbols:**

```
ffffffff8174afc0-ffffffff8174b009: netlink_rcv_wake (STB_LOCAL)
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
In net/netlink/af_netlink.c (ffffffff817b8376)
Location: net/netlink/af_netlink.c:293
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
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
In net/netlink/af_netlink.c (ffffffff817e7e56)
Location: net/netlink/af_netlink.c:293
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
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
In net/netlink/af_netlink.c (ffffffff81807b7d)
Location: net/netlink/af_netlink.c:324
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
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
In net/netlink/af_netlink.c (ffffffff818866ed)
Location: net/netlink/af_netlink.c:326
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
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
In net/netlink/af_netlink.c (ffffffff818d9fd5)
Location: net/netlink/af_netlink.c:360
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
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
In net/netlink/af_netlink.c (ffffffff81906acf)
Location: net/netlink/af_netlink.c:360
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
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
In net/netlink/af_netlink.c (ffffffff81967d6f)
Location: net/netlink/af_netlink.c:351
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
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
In net/netlink/af_netlink.c (ffffffff8199e80f)
Location: net/netlink/af_netlink.c:351
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
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
In net/netlink/af_netlink.c (ffffffff81a7842f)
Location: net/netlink/af_netlink.c:351
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
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
In net/netlink/af_netlink.c (ffffffff81a81224)
Location: net/netlink/af_netlink.c:352
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
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
In net/netlink/af_netlink.c (ffffffff81a6999d)
Location: net/netlink/af_netlink.c:360
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
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
In net/netlink/af_netlink.c (ffffffff81b22f5a)
Location: net/netlink/af_netlink.c:360
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
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
In net/netlink/af_netlink.c (ffffffff81cabb37)
Location: net/netlink/af_netlink.c:364
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
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
In net/netlink/af_netlink.c (ffffffff81e68957)
Location: net/netlink/af_netlink.c:364
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
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
In net/netlink/af_netlink.c (ffffffff81ec47e3)
Location: net/netlink/af_netlink.c:364
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
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
In net/netlink/af_netlink.c (ffffffff81f87bab)
Location: net/netlink/af_netlink.c:362
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
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
In net/netlink/af_netlink.c (ffff800010c4d500)
Location: net/netlink/af_netlink.c:351
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
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
In net/netlink/af_netlink.c (c0d5c68c)
Location: net/netlink/af_netlink.c:351
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
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
In net/netlink/af_netlink.c (c000000000d4a0d0)
Location: net/netlink/af_netlink.c:351
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
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
In net/netlink/af_netlink.c (ffffffe0007b929e)
Location: net/netlink/af_netlink.c:351
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
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
In net/netlink/af_netlink.c (ffffffff8193e67f)
Location: net/netlink/af_netlink.c:351
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
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
In net/netlink/af_netlink.c (ffffffff818f817f)
Location: net/netlink/af_netlink.c:351
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
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
In net/netlink/af_netlink.c (ffffffff8198f80f)
Location: net/netlink/af_netlink.c:351
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
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
In net/netlink/af_netlink.c (ffffffff819b20ef)
Location: net/netlink/af_netlink.c:351
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
