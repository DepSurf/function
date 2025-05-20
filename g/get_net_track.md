# Function: <code>get_net_track</code>

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
In fs/proc/proc_net.c (ffffffff814ae713)
Location: include/net/net_namespace.h:331
Inline: True
Inline callers:
  - fs/proc/proc_net.c:bpf_iter_init_seq_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a69f51)
Location: include/net/net_namespace.h:331
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/core/sock.c (ffffffff81bef9ce)
Location: include/net/net_namespace.h:331
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/mptcp/subflow.c (ffffffff81e28144)
Location: include/net/net_namespace.h:331
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In fs/proc/proc_net.c (ffffffff81544d63)
Location: include/net/net_namespace.h:353
Inline: True
Inline callers:
  - fs/proc/proc_net.c:bpf_iter_init_seq_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfcb51)
Location: include/net/net_namespace.h:353
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/core/sock.c (ffffffff81d9c81b)
Location: include/net/net_namespace.h:353
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/mptcp/subflow.c (ffffffff820000a6)
Location: include/net/net_namespace.h:353
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In fs/proc/proc_net.c (ffffffff8157c943)
Location: include/net/net_namespace.h:353
Inline: True
Inline callers:
  - fs/proc/proc_net.c:bpf_iter_init_seq_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c621d1)
Location: include/net/net_namespace.h:353
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/core/sock.c (ffffffff81e0b077)
Location: include/net/net_namespace.h:353
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/mptcp/subflow.c (ffffffff8207c211)
Location: include/net/net_namespace.h:353
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In fs/proc/proc_net.c (ffffffff815b5263)
Location: include/net/net_namespace.h:355
Inline: True
Inline callers:
  - fs/proc/proc_net.c:bpf_iter_init_seq_net
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d18c00)
Location: include/net/net_namespace.h:355
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In net/core/sock.c (ffffffff81ec7a67)
Location: include/net/net_namespace.h:355
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/mptcp/subflow.c (ffffffff821516cb)
Location: include/net/net_namespace.h:355
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
