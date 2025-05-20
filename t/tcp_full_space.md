# Function: <code>tcp_full_space</code>

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
In net/ipv4/tcp_input.c (ffffffff8176fc7f)
Location: include/net/tcp.h:1213
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff81775cd5)
Location: include/net/tcp.h:1213
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8177fd25)
Location: include/net/tcp.h:1213
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff817ab7d5)
Location: include/net/tcp.h:1213
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff817ff693)
Location: include/net/tcp.h:1213
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp_input.c (ffffffff817dc91f)
Location: include/net/tcp.h:1223
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff817e4ac6)
Location: include/net/tcp.h:1223
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff817ed245)
Location: include/net/tcp.h:1223
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff818192d2)
Location: include/net/tcp.h:1223
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff8186f016)
Location: include/net/tcp.h:1223
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp_input.c (ffffffff8180ca1f)
Location: include/net/tcp.h:1280
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff81814f16)
Location: include/net/tcp.h:1280
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8181db55)
Location: include/net/tcp.h:1280
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff8184ab50)
Location: include/net/tcp.h:1280
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff818a1f81)
Location: include/net/tcp.h:1280
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp_input.c (ffffffff8182cc9b)
Location: include/net/tcp.h:1319
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff818350c5)
Location: include/net/tcp.h:1319
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183d9af)
Location: include/net/tcp.h:1319
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff8186e55e)
Location: include/net/tcp.h:1319
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff818c85b2)
Location: include/net/tcp.h:1319
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp_input.c (ffffffff818abba2)
Location: include/net/tcp.h:1300
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff818b455d)
Location: include/net/tcp.h:1300
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bda6f)
Location: include/net/tcp.h:1300
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff818eeeed)
Location: include/net/tcp.h:1300
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff8194bb6b)
Location: include/net/tcp.h:1300
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp_input.c (ffffffff81901060)
Location: include/net/tcp.h:1317
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff81909b77)
Location: include/net/tcp.h:1317
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81913902)
Location: include/net/tcp.h:1317
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff8194581e)
Location: include/net/tcp.h:1317
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff819a4e2c)
Location: include/net/tcp.h:1317
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp_input.c (ffffffff8192f1fa)
Location: include/net/tcp.h:1375
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff81937e23)
Location: include/net/tcp.h:1375
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819420b2)
Location: include/net/tcp.h:1375
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff81975bb5)
Location: include/net/tcp.h:1375
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff819db91c)
Location: include/net/tcp.h:1375
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp_input.c (ffffffff8199272a)
Location: include/net/tcp.h:1377
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff8199958d)
Location: include/net/tcp.h:1377
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a66b2)
Location: include/net/tcp.h:1377
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff819df70a)
Location: include/net/tcp.h:1377
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81a4a5b3)
Location: include/net/tcp.h:1377
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp_input.c (ffffffff819c926a)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff819cff80)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dcad2)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff81a1675b)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81a81187)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp_input.c (ffffffff81aaf8fa)
Location: include/net/tcp.h:1413
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff81abcfcf)
Location: include/net/tcp.h:1413
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81aca5ee)
Location: include/net/tcp.h:1413
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff81b07735)
Location: include/net/tcp.h:1413
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81b7be1f)
Location: include/net/tcp.h:1413
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/mptcp/subflow.c (ffffffff81bafa49)
Location: include/net/tcp.h:1413
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_space
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
In net/ipv4/tcp_input.c (ffffffff81abae9d)
Location: include/net/tcp.h:1420
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff81ac8731)
Location: include/net/tcp.h:1420
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad655e)
Location: include/net/tcp.h:1420
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff81b15afc)
Location: include/net/tcp.h:1420
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81b8ae74)
Location: include/net/tcp.h:1420
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/mptcp/subflow.c (ffffffff81bc3321)
Location: include/net/tcp.h:1420
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_space
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
In net/ipv4/tcp_input.c (ffffffff81ab00b0)
Location: include/net/tcp.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffff81ab3465)
Location: include/net/tcp.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac15ce)
Location: include/net/tcp.h:1412
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff81b0390a)
Location: include/net/tcp.h:1412
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81b79cd7)
Location: include/net/tcp.h:1412
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/mptcp/subflow.c (ffffffff81bb3649)
Location: include/net/tcp.h:1412
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_space
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
In net/ipv4/tcp_input.c (ffffffff81b6ce98)
Location: include/net/tcp.h:1405
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffff81b7032d)
Location: include/net/tcp.h:1405
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7f02e)
Location: include/net/tcp.h:1405
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff81bc5ba1)
Location: include/net/tcp.h:1405
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81c44988)
Location: include/net/tcp.h:1405
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/mptcp/subflow.c (ffffffff81c81d61)
Location: include/net/tcp.h:1405
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_space
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
In net/ipv4/tcp_input.c (ffffffff81cfc2fc)
Location: include/net/tcp.h:1437
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffff81cff8bd)
Location: include/net/tcp.h:1437
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0e98e)
Location: include/net/tcp.h:1437
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff81d5ae93)
Location: include/net/tcp.h:1437
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81de398f)
Location: include/net/tcp.h:1437
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/mptcp/subflow.c (ffffffff81e278f1)
Location: include/net/tcp.h:1437
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_space
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
In net/ipv4/tcp_input.c (ffffffff81ec0e8c)
Location: include/net/tcp.h:1453
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffff81ec495d)
Location: include/net/tcp.h:1453
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed446e)
Location: include/net/tcp.h:1453
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff81f25303)
Location: include/net/tcp.h:1453
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81fb600f)
Location: include/net/tcp.h:1453
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/mptcp/subflow.c (ffffffff81fff7c1)
Location: include/net/tcp.h:1453
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_space
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
In net/ipv4/tcp_input.c (ffffffff81f1f3fc)
Location: include/net/tcp.h:1451
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffff81f232c6)
Location: include/net/tcp.h:1451
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f3348e)
Location: include/net/tcp.h:1451
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff81f84e94)
Location: include/net/tcp.h:1451
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff82016728)
Location: include/net/tcp.h:1451
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/mptcp/subflow.c (ffffffff8207b891)
Location: include/net/tcp.h:1451
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_space
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
In net/ipv4/tcp_input.c (ffffffff81fe3acd)
Location: include/net/tcp.h:1516
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
```
```
In net/ipv4/tcp_output.c (ffffffff81fe76b0)
Location: include/net/tcp.h:1516
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff9606)
Location: include/net/tcp.h:1516
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff8204b60a)
Location: include/net/tcp.h:1516
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff820e5754)
Location: include/net/tcp.h:1516
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp_input.c (ffff800010c7c168)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffff800010c8262c)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f6d8)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffff800010cd23d0)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffff800010d4c900)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp_input.c (c0d8afcc)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (c0d91cb0)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (c0d9f45c)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (c0ddc2a4)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (c0e4dc10)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp_input.c (c000000000d85bbc)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (c000000000d8e1b8)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9eb90)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (c000000000df0884)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (c000000000e8309c)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp_input.c (ffffffe0007dea9a)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffe0007e4942)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007efd86)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffe000823768)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffe000885688)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp_input.c (ffffffff819690da)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff8196fdf0)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c942)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff819b5deb)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81a20817)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp_input.c (ffffffff81922bca)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff819298c0)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81936402)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff81972bdb)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff819dd5d7)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp_input.c (ffffffff819d38aa)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff819da5c0)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e7112)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff81a2068b)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81a8b297)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
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
In net/ipv4/tcp_input.c (ffffffff819dd46a)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff819e4242)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0de2)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv4/syncookies.c (ffffffff81a2bb8b)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff81a97eb9)
Location: include/net/tcp.h:1399
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
</details>
</li>
</ul>

## Differences
