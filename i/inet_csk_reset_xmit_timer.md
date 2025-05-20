# Function: <code>inet_csk_reset_xmit_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176c1a0)
Location: include/net/inet_connection_sock.h:221
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81775bce)
Location: include/net/inet_connection_sock.h:221
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_schedule_loss_probe
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_ack
  - net/ipv4/tcp_output.c:tcp_xmit_retransmit_queue
  - net/ipv4/tcp_output.c:tcp_send_probe0
```
```
In net/ipv4/tcp_timer.c (ffffffff81779fcb)
Location: include/net/inet_connection_sock.h:221
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177d291)
Location: include/net/inet_connection_sock.h:221
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817829d2)
Location: include/net/inet_connection_sock.h:221
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffffffff8176c1a0-ffffffff8176c28e: inet_csk_reset_xmit_timer.constprop.60 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817e0ac6)
Location: include/net/inet_connection_sock.h:221
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff817e69ec)
Location: include/net/inet_connection_sock.h:221
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_send_ack
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_xmit_retransmit_queue
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_schedule_loss_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff817e71d9)
Location: include/net/inet_connection_sock.h:221
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eb2ee)
Location: include/net/inet_connection_sock.h:221
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817f0082)
Location: include/net/inet_connection_sock.h:221
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffffffff817d8780-ffffffff817d886c: inet_csk_reset_xmit_timer.constprop.63 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81810ebe)
Location: include/net/inet_connection_sock.h:222
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff8181712c)
Location: include/net/inet_connection_sock.h:222
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_send_ack
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_schedule_loss_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff81817919)
Location: include/net/inet_connection_sock.h:222
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181bc3e)
Location: include/net/inet_connection_sock.h:222
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81820aa0)
Location: include/net/inet_connection_sock.h:222
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
**Symbols:**

```
ffffffff81808ba0-ffffffff81808c8c: inet_csk_reset_xmit_timer.constprop.64 (STB_LOCAL)
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
In net/ipv4/tcp_input.c (ffffffff81830a90)
Location: include/net/inet_connection_sock.h:224
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81837590)
Location: include/net/inet_connection_sock.h:224
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
  - net/ipv4/tcp_output.c:tcp_schedule_loss_probe
```
```
In net/ipv4/tcp_timer.c (ffffffff81837d7e)
Location: include/net/inet_connection_sock.h:224
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183c521)
Location: include/net/inet_connection_sock.h:224
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818410b3)
Location: include/net/inet_connection_sock.h:224
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (ffffffff81841c56)
Location: include/net/inet_connection_sock.h:224
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff818afefc)
Location: include/net/inet_connection_sock.h:224
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff818b6c56)
Location: include/net/inet_connection_sock.h:224
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv4/tcp_timer.c (ffffffff818b74c2)
Location: include/net/inet_connection_sock.h:224
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bbc4c)
Location: include/net/inet_connection_sock.h:224
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c081a)
Location: include/net/inet_connection_sock.h:224
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (ffffffff818c1496)
Location: include/net/inet_connection_sock.h:224
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff819059c0)
Location: include/net/inet_connection_sock.h:219
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff8190c4de)
Location: include/net/inet_connection_sock.h:219
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv4/tcp_timer.c (ffffffff8190ce36)
Location: include/net/inet_connection_sock.h:219
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819116a2)
Location: include/net/inet_connection_sock.h:219
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8191642d)
Location: include/net/inet_connection_sock.h:219
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (ffffffff81917026)
Location: include/net/inet_connection_sock.h:219
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff81933b62)
Location: include/net/inet_connection_sock.h:221
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff8193a835)
Location: include/net/inet_connection_sock.h:221
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv4/tcp_timer.c (ffffffff8193b146)
Location: include/net/inet_connection_sock.h:221
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193fe8e)
Location: include/net/inet_connection_sock.h:221
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81944bcd)
Location: include/net/inet_connection_sock.h:221
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (ffffffff81945836)
Location: include/net/inet_connection_sock.h:221
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff819972f6)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff8199eb26)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv4/tcp_timer.c (ffffffff8199f519)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4396)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a9233)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (ffffffff819a9e37)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff819cde76)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff819d5636)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv4/tcp_timer.c (ffffffff819d60c9)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819dafb6)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819dfdda)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (ffffffff819e0af7)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff81aba012)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81ac1f76)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac2fd6)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac5030)
Location: include/net/inet_connection_sock.h:217
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81acd126)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ace0e7)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff81ac5454)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_ack_probe
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81acd9b4)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv4/tcp_timer.c (ffffffff81acea56)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad09c0)
Location: include/net/inet_connection_sock.h:217
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad9136)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ada0dd)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff81ab0678)
Location: include/net/inet_connection_sock.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81ab8b74)
Location: include/net/inet_connection_sock.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab9bf6)
Location: include/net/inet_connection_sock.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abba9d)
Location: include/net/inet_connection_sock.h:216
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac3f96)
Location: include/net/inet_connection_sock.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ac5135)
Location: include/net/inet_connection_sock.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff81b6d4a8)
Location: include/net/inet_connection_sock.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81b75d94)
Location: include/net/inet_connection_sock.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv4/tcp_timer.c (ffffffff81b77034)
Location: include/net/inet_connection_sock.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b78c73)
Location: include/net/inet_connection_sock.h:216
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b82626)
Location: include/net/inet_connection_sock.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/tcp_recovery.c (ffffffff81b83945)
Location: include/net/inet_connection_sock.h:216
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff81cfca07)
Location: include/net/inet_connection_sock.h:214
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81d056af)
Location: include/net/inet_connection_sock.h:214
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv4/tcp_timer.c (ffffffff81d0695c)
Location: include/net/inet_connection_sock.h:214
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d08a85)
Location: include/net/inet_connection_sock.h:214
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d12b54)
Location: include/net/inet_connection_sock.h:214
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/tcp_recovery.c (ffffffff81d1404b)
Location: include/net/inet_connection_sock.h:214
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff81ec15b7)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81eca7bf)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecbbbe)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecdbc5)
Location: include/net/inet_connection_sock.h:217
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed89d3)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/tcp_recovery.c (ffffffff81eda08b)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff81f1fb16)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81f292ff)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv4/tcp_timer.c (ffffffff81f2a741)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2c895)
Location: include/net/inet_connection_sock.h:217
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f37ae3)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/tcp_recovery.c (ffffffff81f3916b)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff81fe41e5)
Location: include/net/inet_connection_sock.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff81fede3f)
Location: include/net/inet_connection_sock.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv4/tcp_timer.c (ffffffff81fef309)
Location: include/net/inet_connection_sock.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff17a5)
Location: include/net/inet_connection_sock.h:220
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffdbb3)
Location: include/net/inet_connection_sock.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/tcp_recovery.c (ffffffff81fff24f)
Location: include/net/inet_connection_sock.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In net/ipv4/tcp_input.c (ffff800010c8093c)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffff800010c882e4)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv4/tcp_timer.c (ffff800010c890dc)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8e354)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c9397c)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (ffff800010c94900)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In net/ipv4/tcp_input.c (c0d8fb14)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (c0d975d4)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv4/tcp_timer.c (c0d98140)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (c0d9d39c)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_fastopen.c (c0da22f8)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (c0da3198)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In net/ipv4/tcp_input.c (c000000000d8b61c)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (c000000000d9521c)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv4/tcp_timer.c (c000000000d962fc)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9cd90)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_fastopen.c (c000000000da3e10)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (c000000000da5140)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In net/ipv4/tcp_input.c (ffffffe0007e28a4)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffe0007e94d6)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv4/tcp_timer.c (ffffffe0007ea050)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ee754)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f2fac)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (ffffffe0007f3cc2)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff8196dce6)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff819754a6)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv4/tcp_timer.c (ffffffff81975f39)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197ae26)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8197fc4a)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (ffffffff81980967)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff819277d6)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff8192ef66)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv4/tcp_timer.c (ffffffff8192f9f9)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819348e6)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8193970a)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (ffffffff8193a427)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff819d84b6)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff819dfc76)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv4/tcp_timer.c (ffffffff819e0709)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e55f6)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819ea41a)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (ffffffff819eb137)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff819e20fd)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
```
In net/ipv4/tcp_output.c (ffffffff819e9926)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
```
In net/ipv4/tcp_timer.c (ffffffff819ea3c9)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ef2a4)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f4243)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_recovery.c (ffffffff819f4fb7)
Location: include/net/inet_connection_sock.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
</details>
</li>
</ul>

## Differences
