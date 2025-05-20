# Function: <code>tcp_pacing_delay</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81930ffb)
Location: include/net/tcp.h:1251
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff8193a7b6)
Location: include/net/tcp.h:1251
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81994679)
Location: include/net/tcp.h:1253
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff8199ead7)
Location: include/net/tcp.h:1253
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819cb1c7)
Location: include/net/tcp.h:1274
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff819d55e7)
Location: include/net/tcp.h:1274
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab802b)
Location: include/net/tcp.h:1294
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81ac1f27)
Location: include/net/tcp.h:1294
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abd7c3)
Location: include/net/tcp.h:1299
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_probe
```
```
In net/ipv4/tcp_output.c (ffffffff81acd9af)
Location: include/net/tcp.h:1299
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
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
In net/ipv4/tcp_input.c (ffffffff81aae5df)
Location: include/net/tcp.h:1291
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81ab8b6f)
Location: include/net/tcp.h:1291
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
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
In net/ipv4/tcp_input.c (ffffffff81b6b15c)
Location: include/net/tcp.h:1284
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81b75d8f)
Location: include/net/tcp.h:1284
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
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
In net/ipv4/tcp_input.c (ffffffff81cfa2be)
Location: include/net/tcp.h:1313
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81d056aa)
Location: include/net/tcp.h:1313
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
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
In net/ipv4/tcp_input.c (ffffffff81ebedcb)
Location: include/net/tcp.h:1329
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81eca7ba)
Location: include/net/tcp.h:1329
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
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
In net/ipv4/tcp_input.c (ffffffff81f1d25e)
Location: include/net/tcp.h:1327
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81f292fa)
Location: include/net/tcp.h:1327
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
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
In net/ipv4/tcp_input.c (ffffffff81fe176f)
Location: include/net/tcp.h:1364
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81fede3a)
Location: include/net/tcp.h:1364
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c7dd58)
Location: include/net/tcp.h:1274
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffff800010c88294)
Location: include/net/tcp.h:1274
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d8cd18)
Location: include/net/tcp.h:1274
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (c0d9756c)
Location: include/net/tcp.h:1274
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d87dc4)
Location: include/net/tcp.h:1274
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (c000000000d951ac)
Location: include/net/tcp.h:1274
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007e0252)
Location: include/net/tcp.h:1274
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffe0007e94c8)
Location: include/net/tcp.h:1274
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8196b037)
Location: include/net/tcp.h:1274
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff81975457)
Location: include/net/tcp.h:1274
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81924b27)
Location: include/net/tcp.h:1274
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff8192ef17)
Location: include/net/tcp.h:1274
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d5807)
Location: include/net/tcp.h:1274
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff819dfc27)
Location: include/net/tcp.h:1274
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819df3ea)
Location: include/net/tcp.h:1274
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_output.c (ffffffff819e98d7)
Location: include/net/tcp.h:1274
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
</details>
</li>
</ul>

## Differences
