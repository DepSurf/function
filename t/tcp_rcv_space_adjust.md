# Function: <code>tcp_rcv_space_adjust</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void tcp_rcv_space_adjust(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176fdd0)
Location: net/ipv4/tcp_input.c:556
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
**Symbols:**

```
ffffffff8176fdd0-ffffffff8176fefa: tcp_rcv_space_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_rcv_space_adjust(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817dca70)
Location: net/ipv4/tcp_input.c:558
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
```
**Symbols:**

```
ffffffff817dca70-ffffffff817dcb94: tcp_rcv_space_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void tcp_rcv_space_adjust(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8180cb70)
Location: net/ipv4/tcp_input.c:581
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
```
**Symbols:**

```
ffffffff8180cb70-ffffffff8180cc94: tcp_rcv_space_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_rcv_space_adjust(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8182cdc0)
Location: net/ipv4/tcp_input.c:588
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_data_queue
```
**Symbols:**

```
ffffffff8182cdc0-ffffffff8182cf07: tcp_rcv_space_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_rcv_space_adjust(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818abce0)
Location: net/ipv4/tcp_input.c:578
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
```
**Symbols:**

```
ffffffff818abce0-ffffffff818abe53: tcp_rcv_space_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_rcv_space_adjust(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81901190)
Location: net/ipv4/tcp_input.c:610
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
```
**Symbols:**

```
ffffffff81901190-ffffffff81901381: tcp_rcv_space_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_rcv_space_adjust(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192f2c0)
Location: net/ipv4/tcp_input.c:595
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
```
**Symbols:**

```
ffffffff8192f2c0-ffffffff8192f480: tcp_rcv_space_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_rcv_space_adjust(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819927f0)
Location: net/ipv4/tcp_input.c:601
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
```
**Symbols:**

```
ffffffff819927f0-ffffffff819929b0: tcp_rcv_space_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_rcv_space_adjust(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c9330)
Location: net/ipv4/tcp_input.c:603
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
```
**Symbols:**

```
ffffffff819c9330-ffffffff819c94f0: tcp_rcv_space_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_rcv_space_adjust(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab5510)
Location: net/ipv4/tcp_input.c:605
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
```
**Symbols:**

```
ffffffff81ab5510-ffffffff81ab56cc: tcp_rcv_space_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_rcv_space_adjust(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ac0620)
Location: net/ipv4/tcp_input.c:669
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
```
**Symbols:**

```
ffffffff81ac0620-ffffffff81ac07ca: tcp_rcv_space_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_rcv_space_adjust(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aab4e0)
Location: net/ipv4/tcp_input.c:669
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
```
**Symbols:**

```
ffffffff81aab4e0-ffffffff81aab689: tcp_rcv_space_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tcp_rcv_space_adjust(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:692
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
```
**Symbols:**

```
ffffffff81d3aade-ffffffff81d3ab88: tcp_rcv_space_adjust.cold (STB_LOCAL)
ffffffff81b67900-ffffffff81b67ac2: tcp_rcv_space_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tcp_rcv_space_adjust(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:701
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
```
**Symbols:**

```
ffffffff81f07386-ffffffff81f07430: tcp_rcv_space_adjust.cold (STB_LOCAL)
ffffffff81cf69b0-ffffffff81cf6ba5: tcp_rcv_space_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void tcp_rcv_space_adjust(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:701
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_skb
  - net/ipv4/tcp.c:tcp_read_skb
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
```
**Symbols:**

```
ffffffff820aee1a-ffffffff820aeec4: tcp_rcv_space_adjust.cold (STB_LOCAL)
ffffffff81ebb3d0-ffffffff81ebb5c5: tcp_rcv_space_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tcp_rcv_space_adjust(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:700
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_eat_skb
```
**Symbols:**

```
ffffffff82130212-ffffffff821302bc: tcp_rcv_space_adjust.cold (STB_LOCAL)
ffffffff81f19850-ffffffff81f19a45: tcp_rcv_space_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_rcv_space_adjust(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fde0b0)
Location: net/ipv4/tcp_input.c:728
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_eat_skb
```
**Symbols:**

```
ffffffff81fde0b0-ffffffff81fde21b: tcp_rcv_space_adjust (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void tcp_rcv_space_adjust(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c7c230)
Location: net/ipv4/tcp_input.c:603
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
```
**Symbols:**

```
ffff800010c7c230-ffff800010c7c3d0: tcp_rcv_space_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_rcv_space_adjust(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d8b08c)
Location: net/ipv4/tcp_input.c:603
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
```
**Symbols:**

```
c0d8b08c-c0d8b350: tcp_rcv_space_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_rcv_space_adjust(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d85cf0)
Location: net/ipv4/tcp_input.c:603
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
```
**Symbols:**

```
c000000000d85cf0-c000000000d85f0c: tcp_rcv_space_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_rcv_space_adjust(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007deb68)
Location: net/ipv4/tcp_input.c:603
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
```
**Symbols:**

```
ffffffe0007deb68-ffffffe0007decf8: tcp_rcv_space_adjust (STB_GLOBAL)
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
void tcp_rcv_space_adjust(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819691a0)
Location: net/ipv4/tcp_input.c:603
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
```
**Symbols:**

```
ffffffff819691a0-ffffffff81969360: tcp_rcv_space_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_rcv_space_adjust(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81922c90)
Location: net/ipv4/tcp_input.c:603
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
```
**Symbols:**

```
ffffffff81922c90-ffffffff81922e50: tcp_rcv_space_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_rcv_space_adjust(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d3970)
Location: net/ipv4/tcp_input.c:603
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
```
**Symbols:**

```
ffffffff819d3970-ffffffff819d3b30: tcp_rcv_space_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_rcv_space_adjust(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819dd530)
Location: net/ipv4/tcp_input.c:603
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
```
**Symbols:**

```
ffffffff819dd530-ffffffff819dd709: tcp_rcv_space_adjust (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
