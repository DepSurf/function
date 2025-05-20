# Function: <code>tcp_initialize_rcv_mss</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void tcp_initialize_rcv_mss(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176a7e0)
Location: net/ipv4/tcp_input.c:469
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
**Symbols:**

```
ffffffff8176a7e0-ffffffff8176a82c: tcp_initialize_rcv_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_initialize_rcv_mss(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817e0837)
Location: net/ipv4/tcp_input.c:471
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
**Symbols:**

```
ffffffff817d7260-ffffffff817d72ac: tcp_initialize_rcv_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void tcp_initialize_rcv_mss(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81810c43)
Location: net/ipv4/tcp_input.c:494
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
**Symbols:**

```
ffffffff81807370-ffffffff818073bc: tcp_initialize_rcv_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tcp_initialize_rcv_mss(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8183099b)
Location: net/ipv4/tcp_input.c:494
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
**Symbols:**

```
ffffffff818279c0-ffffffff81827a0c: tcp_initialize_rcv_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tcp_initialize_rcv_mss(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818afdf9)
Location: net/ipv4/tcp_input.c:482
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
**Symbols:**

```
ffffffff818a7070-ffffffff818a70bc: tcp_initialize_rcv_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tcp_initialize_rcv_mss(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81905882)
Location: net/ipv4/tcp_input.c:514
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
**Symbols:**

```
ffffffff818fc320-ffffffff818fc36c: tcp_initialize_rcv_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tcp_initialize_rcv_mss(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81933a24)
Location: net/ipv4/tcp_input.c:494
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
**Symbols:**

```
ffffffff8192a360-ffffffff8192a3ac: tcp_initialize_rcv_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tcp_initialize_rcv_mss(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81997cbb)
Location: net/ipv4/tcp_input.c:500
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
**Symbols:**

```
ffffffff8198d5a0-ffffffff8198d5ec: tcp_initialize_rcv_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tcp_initialize_rcv_mss(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819ce84b)
Location: net/ipv4/tcp_input.c:502
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
**Symbols:**

```
ffffffff819c3f00-ffffffff819c3f4c: tcp_initialize_rcv_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_initialize_rcv_mss(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aba9d3)
Location: net/ipv4/tcp_input.c:504
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
**Symbols:**

```
ffffffff81aaf5b0-ffffffff81aaf5fc: tcp_initialize_rcv_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tcp_initialize_rcv_mss(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ac5e13)
Location: net/ipv4/tcp_input.c:568
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
**Symbols:**

```
ffffffff81aba600-ffffffff81aba64c: tcp_initialize_rcv_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tcp_initialize_rcv_mss(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab1011)
Location: net/ipv4/tcp_input.c:568
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
**Symbols:**

```
ffffffff81aa58f0-ffffffff81aa5935: tcp_initialize_rcv_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tcp_initialize_rcv_mss(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b6de6a)
Location: net/ipv4/tcp_input.c:591
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
**Symbols:**

```
ffffffff81b61c40-ffffffff81b61c85: tcp_initialize_rcv_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tcp_initialize_rcv_mss(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cfd2e8)
Location: net/ipv4/tcp_input.c:600
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
**Symbols:**

```
ffffffff81cf06c0-ffffffff81cf070f: tcp_initialize_rcv_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tcp_initialize_rcv_mss(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ec1ea8)
Location: net/ipv4/tcp_input.c:600
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
**Symbols:**

```
ffffffff81eb4d00-ffffffff81eb4d4f: tcp_initialize_rcv_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tcp_initialize_rcv_mss(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f203e1)
Location: net/ipv4/tcp_input.c:599
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
**Symbols:**

```
ffffffff81f13130-ffffffff81f1317f: tcp_initialize_rcv_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_initialize_rcv_mss(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fe4a85)
Location: net/ipv4/tcp_input.c:615
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
**Symbols:**

```
ffffffff81fd7570-ffffffff81fd75bf: tcp_initialize_rcv_mss (STB_GLOBAL)
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
void tcp_initialize_rcv_mss(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c812d0)
Location: net/ipv4/tcp_input.c:502
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
**Symbols:**

```
ffff800010c76b58-ffff800010c76bb8: tcp_initialize_rcv_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tcp_initialize_rcv_mss(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d9037c)
Location: net/ipv4/tcp_input.c:502
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
**Symbols:**

```
c0d850ac-c0d85100: tcp_initialize_rcv_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tcp_initialize_rcv_mss(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d8c1e4)
Location: net/ipv4/tcp_input.c:502
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
**Symbols:**

```
c000000000d7e6d0-c000000000d7e720: tcp_initialize_rcv_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tcp_initialize_rcv_mss(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007e3186)
Location: net/ipv4/tcp_input.c:502
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
**Symbols:**

```
ffffffe0007d9a8a-ffffffe0007d9af6: tcp_initialize_rcv_mss (STB_GLOBAL)
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
void tcp_initialize_rcv_mss(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8196e6bb)
Location: net/ipv4/tcp_input.c:502
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
**Symbols:**

```
ffffffff81963d70-ffffffff81963dbc: tcp_initialize_rcv_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tcp_initialize_rcv_mss(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819281ab)
Location: net/ipv4/tcp_input.c:502
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
**Symbols:**

```
ffffffff8191d860-ffffffff8191d8ac: tcp_initialize_rcv_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tcp_initialize_rcv_mss(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d8e8b)
Location: net/ipv4/tcp_input.c:502
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
**Symbols:**

```
ffffffff819ce540-ffffffff819ce58c: tcp_initialize_rcv_mss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tcp_initialize_rcv_mss(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819e2aec)
Location: net/ipv4/tcp_input.c:502
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
**Symbols:**

```
ffffffff819d80d0-ffffffff819d811c: tcp_initialize_rcv_mss (STB_GLOBAL)
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
