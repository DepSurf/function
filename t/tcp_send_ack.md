# Function: <code>tcp_send_ack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817781b0)
Location: net/ipv4/tcp_output.c:3342
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
ffffffff817781b0-ffffffff8177830a: tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817e51a0)
Location: net/ipv4/tcp_output.c:3394
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
ffffffff817e51a0-ffffffff817e52ef: tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81815630)
Location: net/ipv4/tcp_output.c:3520
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
ffffffff81815630-ffffffff8181577f: tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818372d1)
Location: net/ipv4/tcp_output.c:3540
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
ffffffff81835a40-ffffffff81835b62: tcp_send_ack.part.35 (STB_LOCAL)
ffffffff81835b70-ffffffff81835b8a: tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818b6984)
Location: net/ipv4/tcp_output.c:3605
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
ffffffff818b5050-ffffffff818b516b: tcp_send_ack.part.39 (STB_LOCAL)
ffffffff818b5170-ffffffff818b518a: tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tcp_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8190c233)
Location: net/ipv4/tcp_output.c:3622
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
ffffffff8190c250-ffffffff8190c26f: tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tcp_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8193a503)
Location: net/ipv4/tcp_output.c:3654
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
ffffffff8193a520-ffffffff8193a53f: tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tcp_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8199e851)
Location: net/ipv4/tcp_output.c:3689
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
ffffffff8199e880-ffffffff8199e89f: tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tcp_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819d5361)
Location: net/ipv4/tcp_output.c:3721
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
ffffffff819d5390-ffffffff819d53af: tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ac1cab)
Location: net/ipv4/tcp_output.c:3794
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81ac1cd0-ffffffff81ac1cef: tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tcp_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81acd710)
Location: net/ipv4/tcp_output.c:3978
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/options.c:check_fully_established
```
**Symbols:**

```
ffffffff81acd740-ffffffff81acd75f: tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tcp_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab88db)
Location: net/ipv4/tcp_output.c:3975
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_send_ack
  - net/mptcp/options.c:check_fully_established
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
```
**Symbols:**

```
ffffffff81ab8900-ffffffff81ab891f: tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tcp_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81b75afb)
Location: net/ipv4/tcp_output.c:3976
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_subflow_send_ack
  - net/mptcp/options.c:check_fully_established
```
**Symbols:**

```
ffffffff81b75b20-ffffffff81b75b3f: tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tcp_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81d053cc)
Location: net/ipv4/tcp_output.c:3985
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_send_challenge_ack
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:__mptcp_subflow_send_ack
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/options.c:check_fully_established
  - net/mptcp/pm.c:mptcp_pm_mp_fail_received
```
**Symbols:**

```
ffffffff81d053f0-ffffffff81d05423: tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tcp_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81eca49c)
Location: net/ipv4/tcp_output.c:3987
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp.c:__tcp_cleanup_rbuf
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_send_challenge_ack
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/options.c:check_fully_established
  - net/mptcp/pm.c:mptcp_pm_mp_fail_received
```
**Symbols:**

```
ffffffff81eca4d0-ffffffff81eca503: tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tcp_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81f28fdc)
Location: net/ipv4/tcp_output.c:4076
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp.c:__tcp_cleanup_rbuf
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_send_challenge_ack
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_send_ack
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/options.c:check_fully_established
  - net/mptcp/pm.c:mptcp_pm_mp_fail_received
```
**Symbols:**

```
ffffffff81f29010-ffffffff81f29043: tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81fedb1f)
Location: net/ipv4/tcp_output.c:4236
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
  - net/ipv4/tcp_output.c:tcp_release_cb
Direct callers:
  - net/ipv4/tcp.c:__tcp_cleanup_rbuf
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_send_challenge_ack
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_send_ack
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/options.c:check_fully_established
  - net/mptcp/pm.c:mptcp_pm_mp_fail_received
```
**Symbols:**

```
ffffffff81fedb50-ffffffff81fedb83: tcp_send_ack (STB_GLOBAL)
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
void tcp_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffff800010c87fa4)
Location: net/ipv4/tcp_output.c:3721
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
ffff800010c87fd0-ffff800010c88010: tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tcp_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c0d972fc)
Location: net/ipv4/tcp_output.c:3721
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
c0d97318-c0d97344: tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tcp_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c000000000d94dc0)
Location: net/ipv4/tcp_output.c:3721
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
c000000000d94e30-c000000000d94e54: tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tcp_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffe0007e9240)
Location: net/ipv4/tcp_output.c:3721
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
ffffffe0007e927a-ffffffe0007e92b6: tcp_send_ack (STB_GLOBAL)
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
void tcp_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819751d1)
Location: net/ipv4/tcp_output.c:3721
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
ffffffff81975200-ffffffff8197521f: tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tcp_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8192ec91)
Location: net/ipv4/tcp_output.c:3721
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
ffffffff8192ecc0-ffffffff8192ecdf: tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tcp_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819df9a1)
Location: net/ipv4/tcp_output.c:3721
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
ffffffff819df9d0-ffffffff819df9ef: tcp_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tcp_send_ack(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819e9657)
Location: net/ipv4/tcp_output.c:3721
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
Direct callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
ffffffff819e9680-ffffffff819e969f: tcp_send_ack (STB_GLOBAL)
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
