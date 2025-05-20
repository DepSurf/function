# Function: <code>tcp_set_ca_state</code>

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
In net/ipv4/tcp.c (ffffffff81768249)
Location: include/net/tcp.h:918
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff8176b440)
Location: include/net/tcp.h:918
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8177fc88)
Location: include/net/tcp.h:918
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
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
In net/ipv4/tcp.c (ffffffff817d4b28)
Location: include/net/tcp.h:935
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff817dd3de)
Location: include/net/tcp.h:935
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_minisocks.c (ffffffff817ed1a8)
Location: include/net/tcp.h:935
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
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
In net/ipv4/tcp.c (ffffffff8180483b)
Location: include/net/tcp.h:982
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff8180d4f6)
Location: include/net/tcp.h:982
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8181dab8)
Location: include/net/tcp.h:982
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
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
In net/ipv4/tcp.c (ffffffff81824ab1)
Location: include/net/tcp.h:1034
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff8182dc35)
Location: include/net/tcp.h:1034
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_enter_cwr
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183d348)
Location: include/net/tcp.h:1034
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
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
In net/ipv4/tcp.c (ffffffff818a688f)
Location: include/net/tcp.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff818acad4)
Location: include/net/tcp.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_enter_cwr
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bd9b8)
Location: include/net/tcp.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
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
In net/ipv4/tcp.c (ffffffff818fb988)
Location: include/net/tcp.h:1053
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff819021c2)
Location: include/net/tcp.h:1053
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81913838)
Location: include/net/tcp.h:1053
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
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
In net/ipv4/tcp.c (ffffffff819298e5)
Location: include/net/tcp.h:1093
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff8193023e)
Location: include/net/tcp.h:1093
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81941fe8)
Location: include/net/tcp.h:1093
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
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
In net/ipv4/tcp.c (ffffffff8198ca17)
Location: include/net/tcp.h:1095
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff8199377d)
Location: include/net/tcp.h:1095
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a65e1)
Location: include/net/tcp.h:1095
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
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
In net/ipv4/tcp.c (ffffffff819c3387)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff819ca309)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dc461)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
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
In net/ipv4/tcp.c (ffffffff81aaea7a)
Location: include/net/tcp.h:1136
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81ab6ff3)
Location: include/net/tcp.h:1136
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81aca4f1)
Location: include/net/tcp.h:1136
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
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
In net/ipv4/tcp.c (ffffffff81ab8ce9)
Location: include/net/tcp.h:1141
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81ac22a4)
Location: include/net/tcp.h:1141
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad6451)
Location: include/net/tcp.h:1141
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
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
In net/ipv4/tcp.c (ffffffff81aa3f9c)
Location: include/net/tcp.h:1133
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81aad9dc)
Location: include/net/tcp.h:1133
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac14d1)
Location: include/net/tcp.h:1133
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
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
In net/ipv4/tcp.c (ffffffff81b601b1)
Location: include/net/tcp.h:1126
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81b6a4cc)
Location: include/net/tcp.h:1126
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e551)
Location: include/net/tcp.h:1126
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_set_ca_state(struct sock *sk, const u8 ca_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81d0fb90)
Location: net/ipv4/tcp_cong.c:37
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
**Symbols:**

```
ffffffff81d0fb90-ffffffff81d0fc3d: tcp_set_ca_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_set_ca_state(struct sock *sk, const u8 ca_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81ed57f0)
Location: net/ipv4/tcp_cong.c:37
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
**Symbols:**

```
ffffffff81ed57f0-ffffffff81ed589d: tcp_set_ca_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_set_ca_state(struct sock *sk, const u8 ca_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81f344d0)
Location: net/ipv4/tcp_cong.c:37
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
**Symbols:**

```
ffffffff81f344d0-ffffffff81f3457d: tcp_set_ca_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_set_ca_state(struct sock *sk, const u8 ca_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81ffa650)
Location: net/ipv4/tcp_cong.c:37
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
**Symbols:**

```
ffffffff81ffa650-ffffffff81ffa6fd: tcp_set_ca_state (STB_GLOBAL)
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
In net/ipv4/tcp.c (ffff800010c76040)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffff800010c7d0d8)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f5c4)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
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
In net/ipv4/tcp.c (c0d84730)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (c0d8c140)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_minisocks.c (c0d9f3a4)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
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
In net/ipv4/tcp.c (c000000000d7dab0)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (c000000000d86f78)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e400)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
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
In net/ipv4/tcp.c (ffffffe0007d9230)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffe0007df8be)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007ef842)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
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
In net/ipv4/tcp.c (ffffffff819631f7)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff8196a179)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c2d1)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
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
In net/ipv4/tcp.c (ffffffff8191cce7)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff81923c69)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81935d91)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
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
In net/ipv4/tcp.c (ffffffff819cd9c7)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff819d4949)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e6aa1)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
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
In net/ipv4/tcp.c (ffffffff819d7557)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_input.c (ffffffff819de529)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_enter_recovery
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0763)
Location: include/net/tcp.h:1116
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
