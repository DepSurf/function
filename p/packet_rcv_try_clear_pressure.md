# Function: <code>packet_rcv_try_clear_pressure</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a53fda)
Location: net/packet/af_packet.c:1274
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
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
In net/packet/af_packet.c (ffffffff81a8abea)
Location: net/packet/af_packet.c:1275
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
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
In net/packet/af_packet.c (ffffffff81b867a0)
Location: net/packet/af_packet.c:1278
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
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
In net/packet/af_packet.c (ffffffff81b960d0)
Location: net/packet/af_packet.c:1282
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
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
In net/packet/af_packet.c (ffffffff81b84fb0)
Location: net/packet/af_packet.c:1283
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
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
In net/packet/af_packet.c (ffffffff81c51460)
Location: net/packet/af_packet.c:1284
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
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
In net/packet/af_packet.c (ffffffff81df2926)
Location: net/packet/af_packet.c:1320
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
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
In net/packet/af_packet.c (ffffffff81fc6a46)
Location: net/packet/af_packet.c:1320
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void packet_rcv_try_clear_pressure(struct packet_sock *po);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff82027040)
Location: net/packet/af_packet.c:1323
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff82027040-ffffffff82027089: packet_rcv_try_clear_pressure (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void packet_rcv_try_clear_pressure(struct packet_sock *po);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff820f68a0)
Location: net/packet/af_packet.c:1323
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
```
**Symbols:**

```
ffffffff820f68a0-ffffffff820f68e9: packet_rcv_try_clear_pressure (STB_LOCAL)
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
In net/packet/af_packet.c (ffff800010d58c24)
Location: net/packet/af_packet.c:1275
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
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
In net/packet/af_packet.c (c0e5a4bc)
Location: net/packet/af_packet.c:1275
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
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
In net/packet/af_packet.c (c000000000e93804)
Location: net/packet/af_packet.c:1275
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
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
In net/packet/af_packet.c (ffffffe00088f792)
Location: net/packet/af_packet.c:1275
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
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
In net/packet/af_packet.c (ffffffff81a2a27a)
Location: net/packet/af_packet.c:1275
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
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
In net/packet/af_packet.c (ffffffff819e746a)
Location: net/packet/af_packet.c:1275
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
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
In net/packet/af_packet.c (ffffffff81a95e2a)
Location: net/packet/af_packet.c:1275
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
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
In net/packet/af_packet.c (ffffffff81aa2a9a)
Location: net/packet/af_packet.c:1275
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
