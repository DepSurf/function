# Function: <code>tcp_fast_path_check</code>

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
In net/ipv4/tcp.c (ffffffff8176782e)
Location: include/net/tcp.h:646
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff8177042d)
Location: include/net/tcp.h:646
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp.c (ffffffff817d3cd6)
Location: include/net/tcp.h:642
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff817df29e)
Location: include/net/tcp.h:642
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp.c (ffffffff81803a1c)
Location: include/net/tcp.h:640
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff8180f5bf)
Location: include/net/tcp.h:640
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp.c (ffffffff81824567)
Location: include/net/tcp.h:648
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff8182f28e)
Location: include/net/tcp.h:648
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_ack
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818a5e61)
Location: include/net/tcp.h:624
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff818aecbd)
Location: include/net/tcp.h:624
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_ack
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818f76e0)
Location: include/net/tcp.h:634
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff81904266)
Location: include/net/tcp.h:634
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_ack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81925d4f)
Location: include/net/tcp.h:661
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff8193250c)
Location: include/net/tcp.h:661
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp.c (ffffffff81989867)
Location: include/net/tcp.h:662
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff819962cf)
Location: include/net/tcp.h:662
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp.c (ffffffff819c0cdd)
Location: include/net/tcp.h:683
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff819cce4f)
Location: include/net/tcp.h:683
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp.c (ffffffff81aab868)
Location: include/net/tcp.h:688
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff81ab90fc)
Location: include/net/tcp.h:688
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In net/ipv4/tcp.c (ffffffff81ab6822)
Location: include/net/tcp.h:694
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
```
```
In net/ipv4/tcp_input.c (ffffffff81ac451f)
Location: include/net/tcp.h:694
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In net/ipv4/tcp.c (ffffffff81aa1973)
Location: include/net/tcp.h:699
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
```
```
In net/ipv4/tcp_input.c (ffffffff81aaf5f3)
Location: include/net/tcp.h:699
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In net/ipv4/tcp.c (ffffffff81b5d904)
Location: include/net/tcp.h:692
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
```
```
In net/ipv4/tcp_input.c (ffffffff81b6c2fe)
Location: include/net/tcp.h:692
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp.c (ffffffff81cec2b2)
Location: include/net/tcp.h:706
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
```
```
In net/ipv4/tcp_input.c (ffffffff81cfb3ce)
Location: include/net/tcp.h:706
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp.c (ffffffff81eb01ae)
Location: include/net/tcp.h:719
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
```
```
In net/ipv4/tcp_input.c (ffffffff81ebff0e)
Location: include/net/tcp.h:719
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp.c (ffffffff81f0e5fe)
Location: include/net/tcp.h:714
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
```
```
In net/ipv4/tcp_input.c (ffffffff81f1e44e)
Location: include/net/tcp.h:714
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp.c (ffffffff81fd276a)
Location: include/net/tcp.h:727
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
```
```
In net/ipv4/tcp_input.c (ffffffff81fe2cde)
Location: include/net/tcp.h:727
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In net/ipv4/tcp.c (ffff800010c710cc)
Location: include/net/tcp.h:683
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffff800010c7f8ec)
Location: include/net/tcp.h:683
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp.c (c0d801fc)
Location: include/net/tcp.h:683
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (c0d8eb44)
Location: include/net/tcp.h:683
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp.c (c000000000d7833c)
Location: include/net/tcp.h:683
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (c000000000d8a2b4)
Location: include/net/tcp.h:683
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp.c (ffffffe0007d6366)
Location: include/net/tcp.h:683
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffe0007e1b0a)
Location: include/net/tcp.h:683
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp.c (ffffffff81960b4d)
Location: include/net/tcp.h:683
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff8196ccbf)
Location: include/net/tcp.h:683
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp.c (ffffffff8191a63d)
Location: include/net/tcp.h:683
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff819267af)
Location: include/net/tcp.h:683
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp.c (ffffffff819cb31d)
Location: include/net/tcp.h:683
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff819d748f)
Location: include/net/tcp.h:683
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
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
In net/ipv4/tcp.c (ffffffff819d4ead)
Location: include/net/tcp.h:683
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/tcp_input.c (ffffffff819e10af)
Location: include/net/tcp.h:683
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
</details>
</li>
</ul>

## Differences
