# Function: <code>tcp_data_ready</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tcp_data_ready(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819051ac)
Location: net/ipv4/tcp_input.c:4669
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
Direct callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
**Symbols:**

```
ffffffff819036c0-ffffffff819036f4: tcp_data_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tcp_data_ready(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81933376)
Location: net/ipv4/tcp_input.c:4687
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
Direct callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
**Symbols:**

```
ffffffff81931860-ffffffff81931894: tcp_data_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tcp_data_ready(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81996c6a)
Location: net/ipv4/tcp_input.c:4698
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
Direct callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
**Symbols:**

```
ffffffff81994f60-ffffffff81994f94: tcp_data_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tcp_data_ready(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819cd7ea)
Location: net/ipv4/tcp_input.c:4749
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
Direct callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
**Symbols:**

```
ffffffff819cbab0-ffffffff819cbae4: tcp_data_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_data_ready(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab8df0)
Location: net/ipv4/tcp_input.c:4787
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
```
**Symbols:**

```
ffffffff81ab8df0-ffffffff81ab8e3b: tcp_data_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_data_ready(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ac4160)
Location: net/ipv4/tcp_input.c:4925
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
```
**Symbols:**

```
ffffffff81ac4160-ffffffff81ac4230: tcp_data_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_data_ready(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aaf250)
Location: net/ipv4/tcp_input.c:4935
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
```
**Symbols:**

```
ffffffff81aaf250-ffffffff81aaf324: tcp_data_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_data_ready(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b6bf60)
Location: net/ipv4/tcp_input.c:4969
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
```
**Symbols:**

```
ffffffff81b6bf60-ffffffff81b6c02e: tcp_data_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_data_ready(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cfb130)
Location: net/ipv4/tcp_input.c:4990
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
```
**Symbols:**

```
ffffffff81cfb130-ffffffff81cfb21e: tcp_data_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_data_ready(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ebfc60)
Location: net/ipv4/tcp_input.c:5003
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
```
**Symbols:**

```
ffffffff81ebfc60-ffffffff81ebfd4e: tcp_data_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_data_ready(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f1e190)
Location: net/ipv4/tcp_input.c:5008
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
**Symbols:**

```
ffffffff81f1e190-ffffffff81f1e282: tcp_data_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_data_ready(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fe2870)
Location: net/ipv4/tcp_input.c:5140
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
**Symbols:**

```
ffffffff81fe2870-ffffffff81fe2962: tcp_data_ready (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void tcp_data_ready(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c80394)
Location: net/ipv4/tcp_input.c:4749
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
Direct callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
**Symbols:**

```
ffff800010c7e6d0-ffff800010c7e724: tcp_data_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tcp_data_ready(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d8f498)
Location: net/ipv4/tcp_input.c:4749
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
Direct callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
**Symbols:**

```
c0d8d6dc-c0d8d720: tcp_data_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tcp_data_ready(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d8aef0)
Location: net/ipv4/tcp_input.c:4749
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
Direct callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
**Symbols:**

```
c000000000d889a0-c000000000d88a04: tcp_data_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tcp_data_ready(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007e232c)
Location: net/ipv4/tcp_input.c:4749
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
Direct callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
**Symbols:**

```
ffffffe0007e0a56-ffffffe0007e0a98: tcp_data_ready (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void tcp_data_ready(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8196d65a)
Location: net/ipv4/tcp_input.c:4749
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
Direct callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
**Symbols:**

```
ffffffff8196b920-ffffffff8196b954: tcp_data_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tcp_data_ready(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192714a)
Location: net/ipv4/tcp_input.c:4749
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
Direct callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
**Symbols:**

```
ffffffff81925410-ffffffff81925444: tcp_data_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tcp_data_ready(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d7e2a)
Location: net/ipv4/tcp_input.c:4749
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
Direct callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
**Symbols:**

```
ffffffff819d60f0-ffffffff819d6124: tcp_data_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tcp_data_ready(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819e1a63)
Location: net/ipv4/tcp_input.c:4749
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
Direct callers:
  - net/ipv4/tcp.c:tcp_set_rcvlowat
```
**Symbols:**

```
ffffffff819dfd10-ffffffff819dfd44: tcp_data_ready (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
