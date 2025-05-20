# Function: <code>tcp_sack_compress_send_ack</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab362e)
Location: net/ipv4/tcp_input.c:4319
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81ab0920-ffffffff81ab09a0: tcp_sack_compress_send_ack.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abf2ee)
Location: net/ipv4/tcp_input.c:4458
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81abba60-ffffffff81abbae0: tcp_sack_compress_send_ack.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa7446)
Location: net/ipv4/tcp_input.c:4468
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
```
**Symbols:**

```
ffffffff81aa6a20-ffffffff81aa6aa0: tcp_sack_compress_send_ack.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b63876)
Location: net/ipv4/tcp_input.c:4502
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
```
**Symbols:**

```
ffffffff81b62e10-ffffffff81b62e90: tcp_sack_compress_send_ack.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf2386)
Location: net/ipv4/tcp_input.c:4520
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
```
**Symbols:**

```
ffffffff81cf1ad0-ffffffff81cf1b53: tcp_sack_compress_send_ack.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb6d76)
Location: net/ipv4/tcp_input.c:4533
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
```
**Symbols:**

```
ffffffff81eb6320-ffffffff81eb63a3: tcp_sack_compress_send_ack.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_sack_compress_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f15196)
Location: net/ipv4/tcp_input.c:4538
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
```
**Symbols:**

```
ffffffff81f14740-ffffffff81f147c3: tcp_sack_compress_send_ack.part.0 (STB_LOCAL)
ffffffff81f1df90-ffffffff81f1dfb6: tcp_sack_compress_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_sack_compress_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fd97f6)
Location: net/ipv4/tcp_input.c:4669
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
Direct callers:
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
  - net/ipv4/tcp_input.c:tcp_sack_new_ofo_skb
```
**Symbols:**

```
ffffffff81fd8c20-ffffffff81fd8ca3: tcp_sack_compress_send_ack.part.0 (STB_LOCAL)
ffffffff81fe2670-ffffffff81fe2696: tcp_sack_compress_send_ack (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
