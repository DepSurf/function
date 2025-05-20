# Function: <code>sk_psock_queue_empty</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81a1886f)
Location: include/linux/skmsg.h:288
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
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
In net/ipv4/tcp_bpf.c (ffffffff81b099b4)
Location: include/linux/skmsg.h:293
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
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
In net/ipv4/tcp_bpf.c (ffffffff81b17dce)
Location: include/linux/skmsg.h:293
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81b05a31)
Location: include/linux/skmsg.h:334
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv4/udp_bpf.c (ffffffff81b05db1)
Location: include/linux/skmsg.h:334
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81bc858e)
Location: include/linux/skmsg.h:367
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/ipv4/udp_bpf.c (ffffffff81bc8a86)
Location: include/linux/skmsg.h:367
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/unix/unix_bpf.c (ffffffff81beb81c)
Location: include/linux/skmsg.h:367
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81d5d91a)
Location: include/linux/skmsg.h:357
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/ipv4/udp_bpf.c (ffffffff81d5e207)
Location: include/linux/skmsg.h:357
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/unix/unix_bpf.c (ffffffff81d83afb)
Location: include/linux/skmsg.h:357
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81f27b5a)
Location: include/linux/skmsg.h:359
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/ipv4/udp_bpf.c (ffffffff81f28842)
Location: include/linux/skmsg.h:359
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/unix/unix_bpf.c (ffffffff81f512fb)
Location: include/linux/skmsg.h:359
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81f8797f)
Location: include/linux/skmsg.h:359
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/ipv4/udp_bpf.c (ffffffff81f881ee)
Location: include/linux/skmsg.h:359
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/unix/unix_bpf.c (ffffffff81fb0b1f)
Location: include/linux/skmsg.h:359
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff8204f022)
Location: include/linux/skmsg.h:365
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/ipv4/udp_bpf.c (ffffffff8204f90e)
Location: include/linux/skmsg.h:365
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
```
In net/unix/unix_bpf.c (ffffffff8207e1bf)
Location: include/linux/skmsg.h:365
Inline: True
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
In net/ipv4/tcp_bpf.c (ffff800010cd4378)
Location: include/linux/skmsg.h:288
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
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
In net/ipv4/tcp_bpf.c (c0dde534)
Location: include/linux/skmsg.h:288
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
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
In net/ipv4/tcp_bpf.c (c000000000df23ac)
Location: include/linux/skmsg.h:288
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
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
In net/ipv4/tcp_bpf.c (ffffffe0008253ec)
Location: include/linux/skmsg.h:288
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
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
In net/ipv4/tcp_bpf.c (ffffffff819b7eff)
Location: include/linux/skmsg.h:288
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
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
In net/ipv4/tcp_bpf.c (ffffffff81974cef)
Location: include/linux/skmsg.h:288
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
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
In net/ipv4/tcp_bpf.c (ffffffff81a2297f)
Location: include/linux/skmsg.h:288
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
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
In net/ipv4/tcp_bpf.c (ffffffff81a2dd70)
Location: include/linux/skmsg.h:288
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
</details>
</li>
</ul>

## Differences
