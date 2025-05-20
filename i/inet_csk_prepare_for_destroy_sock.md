# Function: <code>inet_csk_prepare_for_destroy_sock</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81aa63a1)
Location: include/net/inet_connection_sock.h:290
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/mptcp/subflow.c (ffffffff81baef28)
Location: include/net/inet_connection_sock.h:290
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
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
In net/ipv4/inet_connection_sock.c (ffffffff81ab09f1)
Location: include/net/inet_connection_sock.h:290
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/mptcp/subflow.c (ffffffff81bc1ac1)
Location: include/net/inet_connection_sock.h:290
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
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
In net/ipv4/inet_connection_sock.c (ffffffff81a9c961)
Location: include/net/inet_connection_sock.h:288
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/mptcp/subflow.c (ffffffff81bb240a)
Location: include/net/inet_connection_sock.h:288
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
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
In net/ipv4/inet_connection_sock.c (ffffffff81b576f1)
Location: include/net/inet_connection_sock.h:288
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/mptcp/subflow.c (ffffffff81c8066e)
Location: include/net/inet_connection_sock.h:288
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
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
In net/ipv4/inet_connection_sock.c (ffffffff81ce4e0f)
Location: include/net/inet_connection_sock.h:294
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/mptcp/subflow.c (ffffffff81e26318)
Location: include/net/inet_connection_sock.h:294
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
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
In net/ipv4/inet_connection_sock.c (ffffffff81ea7a3f)
Location: include/net/inet_connection_sock.h:297
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/mptcp/subflow.c (ffffffff81fff51d)
Location: include/net/inet_connection_sock.h:297
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
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
In net/ipv4/inet_connection_sock.c (ffffffff81f0627f)
Location: include/net/inet_connection_sock.h:297
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/mptcp/subflow.c (ffffffff8207b638)
Location: include/net/inet_connection_sock.h:297
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
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
In net/ipv4/inet_connection_sock.c (ffffffff81fca56f)
Location: include/net/inet_connection_sock.h:300
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/mptcp/subflow.c (ffffffff82150c09)
Location: include/net/inet_connection_sock.h:300
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
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
