# Function: <code>tcp_snd_cwnd_set</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c4aad2)
Location: include/net/tcp.h:1217
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/ipv4/tcp.c (ffffffff81ceea97)
Location: include/net/tcp.h:1217
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81cfc23c)
Location: include/net/tcp.h:1217
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff81d034c8)
Location: include/net/tcp.h:1217
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_cong.c (ffffffff81d0f7d6)
Location: include/net/tcp.h:1217
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_reno_cong_avoid
  - net/ipv4/tcp_cong.c:tcp_cong_avoid_ai
  - net/ipv4/tcp_cong.c:tcp_cong_avoid_ai
  - net/ipv4/tcp_cong.c:tcp_cong_avoid_ai
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
In net/core/filter.c (ffffffff81df5563)
Location: include/net/tcp.h:1230
Inline: True
Inline callers:
  - net/core/filter.c:sol_tcp_sockopt
```
```
In net/ipv4/tcp.c (ffffffff81eb1cff)
Location: include/net/tcp.h:1230
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81ec0dcc)
Location: include/net/tcp.h:1230
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff81ec7b2b)
Location: include/net/tcp.h:1230
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_cong.c (ffffffff81ed52a7)
Location: include/net/tcp.h:1230
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_cong_avoid_ai
  - net/ipv4/tcp_cong.c:tcp_cong_avoid_ai
  - net/ipv4/tcp_cong.c:tcp_cong_avoid_ai
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
In net/core/filter.c (ffffffff81e66f60)
Location: include/net/tcp.h:1228
Inline: True
Inline callers:
  - net/core/filter.c:sol_tcp_sockopt
```
```
In net/ipv4/tcp.c (ffffffff81f103ad)
Location: include/net/tcp.h:1228
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81f1f33c)
Location: include/net/tcp.h:1228
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff81f26380)
Location: include/net/tcp.h:1228
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_cong.c (ffffffff81f33f87)
Location: include/net/tcp.h:1228
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_cong_avoid_ai
  - net/ipv4/tcp_cong.c:tcp_cong_avoid_ai
  - net/ipv4/tcp_cong.c:tcp_cong_avoid_ai
  - net/ipv4/tcp_cong.c:tcp_slow_start
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
In net/core/filter.c (ffffffff81f2611a)
Location: include/net/tcp.h:1265
Inline: True
Inline callers:
  - net/core/filter.c:sol_tcp_sockopt
```
```
In net/ipv4/tcp.c (ffffffff81fd45b3)
Location: include/net/tcp.h:1265
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81fe3a0c)
Location: include/net/tcp.h:1265
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_output.c (ffffffff81fead3d)
Location: include/net/tcp.h:1265
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_cwnd_validate
  - net/ipv4/tcp_output.c:tcp_cwnd_restart
```
```
In net/ipv4/tcp_cong.c (ffffffff81ffa107)
Location: include/net/tcp.h:1265
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_cong_avoid_ai
  - net/ipv4/tcp_cong.c:tcp_cong_avoid_ai
  - net/ipv4/tcp_cong.c:tcp_cong_avoid_ai
  - net/ipv4/tcp_cong.c:tcp_slow_start
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
