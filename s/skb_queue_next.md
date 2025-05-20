# Function: <code>skb_queue_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff815f7480)
Location: include/linux/skbuff.h:1166
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/ipv4/tcp_input.c (ffffffff8176f07d)
Location: include/linux/skbuff.h:1166
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (ffffffff81778710)
Location: include/linux/skbuff.h:1166
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81657623)
Location: include/linux/skbuff.h:1257
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/ipv4/tcp_input.c (ffffffff817d8e1d)
Location: include/linux/skbuff.h:1257
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (ffffffff817e5755)
Location: include/linux/skbuff.h:1257
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81685303)
Location: include/linux/skbuff.h:1272
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/ipv4/tcp_input.c (ffffffff81809631)
Location: include/linux/skbuff.h:1272
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (ffffffff81815b96)
Location: include/linux/skbuff.h:1272
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff8169a71c)
Location: include/linux/skbuff.h:1265
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
```
```
In net/ipv4/tcp_input.c (ffffffff81829b3e)
Location: include/linux/skbuff.h:1265
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (ffffffff81835f3a)
Location: include/linux/skbuff.h:1265
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
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
In drivers/net/ppp/ppp_generic.c (ffffffff81704ebe)
Location: include/linux/skbuff.h:1367
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffff81743657)
Location: include/linux/skbuff.h:1378
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffff81767e8e)
Location: include/linux/skbuff.h:1447
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
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
In drivers/net/ppp/ppp_generic.c (ffffffff817a3595)
Location: include/linux/skbuff.h:1537
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
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
In drivers/net/ppp/ppp_generic.c (ffffffff817c6fe5)
Location: include/linux/skbuff.h:1547
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
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
In drivers/net/ppp/ppp_generic.c (ffffffff81892c75)
Location: include/linux/skbuff.h:1558
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
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
In drivers/net/ppp/ppp_generic.c (ffffffff818a0d15)
Location: include/linux/skbuff.h:1579
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
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
In drivers/net/ppp/ppp_generic.c (ffffffff818833a5)
Location: include/linux/skbuff.h:1595
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
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
In drivers/net/ppp/ppp_generic.c (ffffffff81914d45)
Location: include/linux/skbuff.h:1608
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
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
In drivers/net/ppp/ppp_generic.c (ffffffff81a6a385)
Location: include/linux/skbuff.h:1957
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
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
In drivers/net/ppp/ppp_generic.c (ffffffff81bfd0cf)
Location: include/linux/skbuff.h:1815
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
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
In drivers/net/ppp/ppp_generic.c (ffffffff81c6274f)
Location: include/linux/skbuff.h:1851
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
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
In drivers/net/ppp/ppp_generic.c (ffffffff81d1916f)
Location: include/linux/skbuff.h:1858
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
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
In drivers/net/ppp/ppp_generic.c (ffff8000109fe208)
Location: include/linux/skbuff.h:1547
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
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
In drivers/net/ppp/ppp_generic.c (c0adbb5c)
Location: include/linux/skbuff.h:1547
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
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
In drivers/net/ppp/ppp_generic.c (c000000000aa5ba0)
Location: include/linux/skbuff.h:1547
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
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
In drivers/net/ppp/ppp_generic.c (ffffffe00062bad8)
Location: include/linux/skbuff.h:1547
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
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
In drivers/net/ppp/ppp_generic.c (ffffffff8178bac5)
Location: include/linux/skbuff.h:1547
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
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
In drivers/net/ppp/ppp_generic.c (ffffffff81774895)
Location: include/linux/skbuff.h:1547
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
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
In drivers/net/ppp/ppp_generic.c (ffffffff817bbe65)
Location: include/linux/skbuff.h:1547
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
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
In drivers/net/ppp/ppp_generic.c (ffffffff817d60b5)
Location: include/linux/skbuff.h:1547
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
```
</details>
</li>
</ul>

## Differences
