# Function: <code>inet_twsk_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void inet_twsk_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff817636c0)
Location: net/ipv4/inet_timewait_sock.c:77
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff817636c0-ffffffff817636da: inet_twsk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void inet_twsk_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff817cfb70)
Location: net/ipv4/inet_timewait_sock.c:77
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff817cfb70-ffffffff817cfb8a: inet_twsk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void inet_twsk_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff817ff960)
Location: net/ipv4/inet_timewait_sock.c:77
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff817ff960-ffffffff817ff97a: inet_twsk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void inet_twsk_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff8181fb80)
Location: net/ipv4/inet_timewait_sock.c:77
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff8181fb80-ffffffff8181fb9b: inet_twsk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void inet_twsk_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff8189eb00)
Location: net/ipv4/inet_timewait_sock.c:76
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff8189eb00-ffffffff8189eb21: inet_twsk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void inet_twsk_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff818f3550)
Location: net/ipv4/inet_timewait_sock.c:76
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff818f3550-ffffffff818f3571: inet_twsk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void inet_twsk_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81921070)
Location: net/ipv4/inet_timewait_sock.c:76
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff81921070-ffffffff81921091: inet_twsk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void inet_twsk_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81983a40)
Location: net/ipv4/inet_timewait_sock.c:77
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff81983a40-ffffffff81983a60: inet_twsk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void inet_twsk_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff819ba230)
Location: net/ipv4/inet_timewait_sock.c:77
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff819ba230-ffffffff819ba250: inet_twsk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void inet_twsk_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4cd0)
Location: net/ipv4/inet_timewait_sock.c:77
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff81aa4cd0-ffffffff81aa4d0e: inet_twsk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void inet_twsk_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf330)
Location: net/ipv4/inet_timewait_sock.c:77
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff81aaf330-ffffffff81aaf36e: inet_twsk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void inet_twsk_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a640)
Location: net/ipv4/inet_timewait_sock.c:77
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff81a9a640-ffffffff81a9a67e: inet_twsk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void inet_twsk_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81b55ab0)
Location: net/ipv4/inet_timewait_sock.c:77
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff81b55ab0-ffffffff81b55aee: inet_twsk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void inet_twsk_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce3a4d)
Location: net/ipv4/inet_timewait_sock.c:79
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff81ce3730-ffffffff81ce3792: inet_twsk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void inet_twsk_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea5fb0)
Location: net/ipv4/inet_timewait_sock.c:87
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff81ea5fb0-ffffffff81ea6012: inet_twsk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void inet_twsk_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04760)
Location: net/ipv4/inet_timewait_sock.c:84
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff81f04760-ffffffff81f047c2: inet_twsk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void inet_twsk_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8a60)
Location: net/ipv4/inet_timewait_sock.c:82
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff81fc8a60-ffffffff81fc8ac2: inet_twsk_put (STB_GLOBAL)
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
void inet_twsk_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffff800010c6bc80)
Location: net/ipv4/inet_timewait_sock.c:77
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffff800010c6bc80-ffff800010c6bcc8: inet_twsk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inet_twsk_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (c0d7ab34)
Location: net/ipv4/inet_timewait_sock.c:77
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
c0d7ab34-c0d7ab68: inet_twsk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inet_twsk_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (c000000000d71230)
Location: net/ipv4/inet_timewait_sock.c:77
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
c000000000d71230-c000000000d7126c: inet_twsk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void inet_twsk_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d190e)
Location: net/ipv4/inet_timewait_sock.c:77
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffe0007d1664-ffffffe0007d16aa: inet_twsk_put (STB_GLOBAL)
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
void inet_twsk_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff8195a0a0)
Location: net/ipv4/inet_timewait_sock.c:77
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff8195a0a0-ffffffff8195a0c0: inet_twsk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void inet_twsk_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81913b90)
Location: net/ipv4/inet_timewait_sock.c:77
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff81913b90-ffffffff81913bb0: inet_twsk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void inet_twsk_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff819c4870)
Location: net/ipv4/inet_timewait_sock.c:77
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff819c4870-ffffffff819c4890: inet_twsk_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void inet_twsk_put(struct inet_timewait_sock *tw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce2f0)
Location: net/ipv4/inet_timewait_sock.c:77
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffffffff819ce2f0-ffffffff819ce310: inet_twsk_put (STB_GLOBAL)
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
