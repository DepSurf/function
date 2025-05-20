# Function: <code>twsk_net</code>

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
In net/ipv4/inet_timewait_sock.c (ffffffff81763884)
Location: include/net/inet_timewait_sock.h:132
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/net/inet_timewait_sock.h:132
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff817823b1)
Location: include/net/inet_timewait_sock.h:132
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_tw_remember_stamp
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
In net/ipv4/inet_timewait_sock.c (ffffffff817cfd54)
Location: include/net/inet_timewait_sock.h:132
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/net/inet_timewait_sock.h:132
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ef871)
Location: include/net/inet_timewait_sock.h:132
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_tw_remember_stamp
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
In net/ipv4/inet_timewait_sock.c (ffffffff817ffb44)
Location: include/net/inet_timewait_sock.h:132
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/net/inet_timewait_sock.h:132
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81820281)
Location: include/net/inet_timewait_sock.h:132
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_tw_remember_stamp
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
In net/ipv4/inet_timewait_sock.c (ffffffff8181fd2e)
Location: include/net/inet_timewait_sock.h:121
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/net/inet_timewait_sock.h:121
Inline: True
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
In net/ipv4/inet_timewait_sock.c (ffffffff8189ecd7)
Location: include/net/inet_timewait_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/net/inet_timewait_sock.h:117
Inline: True
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
In net/ipv4/inet_timewait_sock.c (ffffffff818f3749)
Location: include/net/inet_timewait_sock.h:118
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8191370e)
Location: include/net/inet_timewait_sock.h:118
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/inet_timewait_sock.c (ffffffff81921269)
Location: include/net/inet_timewait_sock.h:118
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81941ec5)
Location: include/net/inet_timewait_sock.h:118
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/inet_timewait_sock.c (ffffffff81983c25)
Location: include/net/inet_timewait_sock.h:115
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a64cb)
Location: include/net/inet_timewait_sock.h:115
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/inet_timewait_sock.c (ffffffff819ba405)
Location: include/net/inet_timewait_sock.h:116
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dd49b)
Location: include/net/inet_timewait_sock.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4ee4)
Location: include/net/inet_timewait_sock.h:116
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81aca28d)
Location: include/net/inet_timewait_sock.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf544)
Location: include/net/inet_timewait_sock.h:116
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad61ed)
Location: include/net/inet_timewait_sock.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a854)
Location: include/net/inet_timewait_sock.h:116
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac123a)
Location: include/net/inet_timewait_sock.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/inet_timewait_sock.c (ffffffff81b55cc4)
Location: include/net/inet_timewait_sock.h:116
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7ed9a)
Location: include/net/inet_timewait_sock.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/inet_timewait_sock.c (ffffffff81ce39c7)
Location: include/net/inet_timewait_sock.h:115
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0e838)
Location: include/net/inet_timewait_sock.h:115
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/inet_timewait_sock.c (ffffffff81ea640d)
Location: include/net/inet_timewait_sock.h:120
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed4308)
Location: include/net/inet_timewait_sock.h:120
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/inet_timewait_sock.c (ffffffff81f04bed)
Location: include/net/inet_timewait_sock.h:120
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f33318)
Location: include/net/inet_timewait_sock.h:120
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8ef5)
Location: include/net/inet_timewait_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff947c)
Location: include/net/inet_timewait_sock.h:117
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/inet_timewait_sock.c (ffff800010c6bf80)
Location: include/net/inet_timewait_sock.h:116
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8ffe0)
Location: include/net/inet_timewait_sock.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/inet_timewait_sock.c (c0d7ad70)
Location: include/net/inet_timewait_sock.h:116
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/tcp_minisocks.c (c0d9f2a0)
Location: include/net/inet_timewait_sock.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/inet_timewait_sock.c (c000000000d7155c)
Location: include/net/inet_timewait_sock.h:116
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9f82c)
Location: include/net/inet_timewait_sock.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/inet_timewait_sock.c (ffffffe0007d191a)
Location: include/net/inet_timewait_sock.h:116
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007f0616)
Location: include/net/inet_timewait_sock.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/inet_timewait_sock.c (ffffffff8195a275)
Location: include/net/inet_timewait_sock.h:116
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197d30b)
Location: include/net/inet_timewait_sock.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/inet_timewait_sock.c (ffffffff81913d65)
Location: include/net/inet_timewait_sock.h:116
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81936dcb)
Location: include/net/inet_timewait_sock.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/inet_timewait_sock.c (ffffffff819c4a45)
Location: include/net/inet_timewait_sock.h:116
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e7adb)
Location: include/net/inet_timewait_sock.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
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
In net/ipv4/inet_timewait_sock.c (ffffffff819ce4d2)
Location: include/net/inet_timewait_sock.h:116
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f17ab)
Location: include/net/inet_timewait_sock.h:116
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
```
</details>
</li>
</ul>

## Differences
