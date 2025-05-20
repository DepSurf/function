# Function: <code>seq_user_ns</code>

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
In kernel/user_namespace.c (0)
Location: include/linux/seq_file.h:147
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/seq_file.h:147
Inline: True
```
```
In fs/proc/array.c (0)
Location: include/linux/seq_file.h:147
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/seq_file.h:147
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/seq_file.h:147
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/seq_file.h:147
Inline: True
```
```
In security/keys/proc.c (0)
Location: include/linux/seq_file.h:147
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/seq_file.h:147
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/seq_file.h:147
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/seq_file.h:147
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/seq_file.h:147
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/seq_file.h:147
Inline: True
```
```
In net/ipv6/datagram.c (0)
Location: include/linux/seq_file.h:147
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/linux/seq_file.h:147
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/seq_file.h:147
Inline: True
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
In kernel/user_namespace.c (ffffffff811271d3)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
  - kernel/user_namespace.c:projid_m_show
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:uid_m_show
```
```
In kernel/trace/trace.c (ffffffff811599a7)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
```
```
In fs/proc/array.c (ffffffff812adb6c)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/msg.c (ffffffff8135a6ac)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - ipc/msg.c:sysvipc_msg_proc_show
```
```
In ipc/sem.c (ffffffff8135b92c)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
```
```
In ipc/shm.c (ffffffff8135f3c2)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - ipc/shm.c:sysvipc_shm_proc_show
```
```
In security/keys/proc.c (ffffffff8136aac2)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817e8d63)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/raw.c (ffffffff817f1f99)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff817f44ec)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff8180ff5c)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185e140)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
```
In net/ipv6/datagram.c (ffffffff81864bea)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_dgram_sock_seq_show
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff8186537e)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
```
In net/packet/af_packet.c (ffffffff81873f2b)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
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
In kernel/user_namespace.c (ffffffff81130d70)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
  - kernel/user_namespace.c:projid_m_show
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:uid_m_show
```
```
In kernel/trace/trace.c (ffffffff811641c8)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
```
```
In fs/proc/array.c (ffffffff812c3461)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/msg.c (ffffffff81370c8c)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - ipc/msg.c:sysvipc_msg_proc_show
```
```
In ipc/sem.c (ffffffff81371f0c)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
```
```
In ipc/shm.c (ffffffff81375bc2)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - ipc/shm.c:sysvipc_shm_proc_show
```
```
In security/keys/proc.c (ffffffff813812d2)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81818f50)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/raw.c (ffffffff81822d86)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff818255b9)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff818414a9)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8189027d)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
```
In net/ipv6/datagram.c (ffffffff818972ca)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_dgram_sock_seq_show
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81897a4b)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
```
In net/packet/af_packet.c (ffffffff818a84bb)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
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
In kernel/user_namespace.c (ffffffff811323a0)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
  - kernel/user_namespace.c:projid_m_show
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:uid_m_show
```
```
In kernel/trace/trace.c (ffffffff81167501)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
```
```
In fs/proc/array.c (ffffffff812d06dd)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/msg.c (ffffffff8138402c)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - ipc/msg.c:sysvipc_msg_proc_show
```
```
In ipc/sem.c (ffffffff8138596c)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
```
```
In ipc/shm.c (ffffffff8138975f)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - ipc/shm.c:sysvipc_shm_proc_show
```
```
In security/keys/proc.c (ffffffff8139523e)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818396f4)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/raw.c (ffffffff81843966)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff818464e8)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81862d18)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b684a)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
```
In net/ipv6/datagram.c (ffffffff818bd727)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_dgram_sock_seq_show
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff818bde49)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
```
In net/packet/af_packet.c (ffffffff818ced07)
Location: include/linux/seq_file.h:142
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
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
In kernel/user_namespace.c (ffffffff8113f100)
Location: include/linux/seq_file.h:143
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
  - kernel/user_namespace.c:projid_m_show
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:uid_m_show
```
```
In kernel/trace/trace.c (ffffffff81174481)
Location: include/linux/seq_file.h:143
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
```
```
In fs/proc/array.c (ffffffff812f4f0f)
Location: include/linux/seq_file.h:143
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/msg.c (ffffffff813a890c)
Location: include/linux/seq_file.h:143
Inline: True
Inline callers:
  - ipc/msg.c:sysvipc_msg_proc_show
```
```
In ipc/sem.c (ffffffff813aa3fc)
Location: include/linux/seq_file.h:143
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
```
```
In ipc/shm.c (ffffffff813aeadf)
Location: include/linux/seq_file.h:143
Inline: True
Inline callers:
  - ipc/shm.c:sysvipc_shm_proc_show
```
```
In security/keys/proc.c (ffffffff813ba98e)
Location: include/linux/seq_file.h:143
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b8e84)
Location: include/linux/seq_file.h:143
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/raw.c (ffffffff818c33a6)
Location: include/linux/seq_file.h:143
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff818c5f18)
Location: include/linux/seq_file.h:143
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff818e2e48)
Location: include/linux/seq_file.h:143
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193967a)
Location: include/linux/seq_file.h:143
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
```
In net/ipv6/datagram.c (ffffffff81940847)
Location: include/linux/seq_file.h:143
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_dgram_sock_seq_show
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81940f29)
Location: include/linux/seq_file.h:143
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
```
In net/packet/af_packet.c (ffffffff81953bf7)
Location: include/linux/seq_file.h:143
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
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
In kernel/user_namespace.c (ffffffff8114da20)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
  - kernel/user_namespace.c:projid_m_show
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:uid_m_show
```
```
In kernel/trace/trace.c (ffffffff811834e0)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
```
```
In fs/proc/array.c (ffffffff813222bd)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/msg.c (ffffffff813d7872)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - ipc/msg.c:sysvipc_msg_proc_show
```
```
In ipc/sem.c (ffffffff813d9f45)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
```
```
In ipc/shm.c (ffffffff813ddbd2)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - ipc/shm.c:sysvipc_shm_proc_show
```
```
In security/keys/proc.c (ffffffff813eb7c1)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190e294)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/raw.c (ffffffff81919016)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff8191b22b)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff819397bd)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81991939)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
```
In net/ipv6/datagram.c (ffffffff8199971b)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81999de8)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
```
In net/packet/af_packet.c (ffffffff819ad607)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
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
In kernel/user_namespace.c (ffffffff8115a6f0)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
  - kernel/user_namespace.c:projid_m_show
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:uid_m_show
```
```
In kernel/trace/trace.c (ffffffff81190e40)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
```
```
In fs/proc/array.c (ffffffff813393cd)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In ipc/msg.c (ffffffff813f1e82)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - ipc/msg.c:sysvipc_msg_proc_show
```
```
In ipc/sem.c (ffffffff813f3dd5)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
```
```
In ipc/shm.c (ffffffff813f8252)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - ipc/shm.c:sysvipc_shm_proc_show
```
```
In security/keys/proc.c (ffffffff814063c1)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193c684)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/raw.c (ffffffff819477e6)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff819497ab)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff8196944d)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c8179)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
```
In net/ipv6/datagram.c (ffffffff819d006b)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d09b8)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
```
In net/packet/af_packet.c (ffffffff819e3f77)
Location: include/linux/seq_file.h:162
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
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
In kernel/user_namespace.c (ffffffff81166dd0)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
  - kernel/user_namespace.c:projid_m_show
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:uid_m_show
```
```
In kernel/trace/trace.c (ffffffff8119e7ca)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
```
```
In fs/proc/array.c (ffffffff813603cd)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In ipc/msg.c (ffffffff8141e172)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/msg.c:sysvipc_msg_proc_show
```
```
In ipc/sem.c (ffffffff81420985)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
```
```
In ipc/shm.c (ffffffff81424752)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/shm.c:sysvipc_shm_proc_show
```
```
In security/keys/proc.c (ffffffff814334f7)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a0acd)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/raw.c (ffffffff819abe7c)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff819ade1f)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff819d009e)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a36c13)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
```
In net/ipv6/datagram.c (ffffffff81a3ed80)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a3f428)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
```
In net/packet/af_packet.c (ffffffff81a52e69)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
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
In kernel/user_namespace.c (ffffffff81172c90)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
  - kernel/user_namespace.c:projid_m_show
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:uid_m_show
```
```
In kernel/trace/trace.c (ffffffff811aa199)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
```
```
In fs/proc/array.c (ffffffff8137862d)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In ipc/msg.c (ffffffff81437fc2)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/msg.c:sysvipc_msg_proc_show
```
```
In ipc/sem.c (ffffffff8143a775)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
```
```
In ipc/shm.c (ffffffff8143e4a2)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/shm.c:sysvipc_shm_proc_show
```
```
In security/keys/proc.c (ffffffff8144d267)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d769e)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/raw.c (ffffffff819e2b2c)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff819e4b2f)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81a06bee)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6d7c3)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
```
In net/ipv6/datagram.c (ffffffff81a759f0)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a76098)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
```
In net/packet/af_packet.c (ffffffff81a89a49)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
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
In kernel/user_namespace.c (ffffffff81184af0)
Location: include/linux/seq_file.h:194
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
  - kernel/user_namespace.c:projid_m_show
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:uid_m_show
```
```
In kernel/trace/trace.c (ffffffff811c27a7)
Location: include/linux/seq_file.h:194
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
```
```
In fs/io_uring.c (ffffffff8137af05)
Location: include/linux/seq_file.h:194
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_show_cred
```
```
In fs/proc/array.c (ffffffff813c16f0)
Location: include/linux/seq_file.h:194
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In ipc/msg.c (ffffffff81487f72)
Location: include/linux/seq_file.h:194
Inline: True
Inline callers:
  - ipc/msg.c:sysvipc_msg_proc_show
```
```
In ipc/sem.c (ffffffff8148abb5)
Location: include/linux/seq_file.h:194
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
```
```
In ipc/shm.c (ffffffff8148f482)
Location: include/linux/seq_file.h:194
Inline: True
Inline callers:
  - ipc/shm.c:sysvipc_shm_proc_show
```
```
In security/keys/proc.c (ffffffff8149f157)
Location: include/linux/seq_file.h:194
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_next
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac4658)
Location: include/linux/seq_file.h:194
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:get_openreq4
```
```
In net/ipv4/raw.c (ffffffff81ad00ed)
Location: include/linux/seq_file.h:194
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sock_seq_show
```
```
In net/ipv4/udp.c (ffffffff81ad2781)
Location: include/linux/seq_file.h:194
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_format_sock
```
```
In net/ipv4/ping.c (ffffffff81af6630)
Location: include/linux/seq_file.h:194
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_format_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66dfb)
Location: include/linux/seq_file.h:194
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:get_openreq6
```
```
In net/ipv6/datagram.c (ffffffff81b6fc30)
Location: include/linux/seq_file.h:194
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b70088)
Location: include/linux/seq_file.h:194
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
```
In net/packet/af_packet.c (ffffffff81b84fc9)
Location: include/linux/seq_file.h:194
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
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
In kernel/user_namespace.c (ffffffff81181b40)
Location: include/linux/seq_file.h:195
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
  - kernel/user_namespace.c:projid_m_show
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:uid_m_show
```
```
In kernel/trace/trace.c (ffffffff811c03b7)
Location: include/linux/seq_file.h:195
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
```
```
In fs/io_uring.c (ffffffff81389282)
Location: include/linux/seq_file.h:195
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_show_cred
```
```
In fs/proc/array.c (ffffffff813d35e0)
Location: include/linux/seq_file.h:195
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In ipc/msg.c (ffffffff814a5592)
Location: include/linux/seq_file.h:195
Inline: True
Inline callers:
  - ipc/msg.c:sysvipc_msg_proc_show
```
```
In ipc/sem.c (ffffffff814a81d5)
Location: include/linux/seq_file.h:195
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
```
```
In ipc/shm.c (ffffffff814acb62)
Location: include/linux/seq_file.h:195
Inline: True
Inline callers:
  - ipc/shm.c:sysvipc_shm_proc_show
```
```
In security/keys/proc.c (ffffffff814bcb87)
Location: include/linux/seq_file.h:195
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_next
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad040e)
Location: include/linux/seq_file.h:195
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:get_openreq4
```
```
In net/ipv4/raw.c (ffffffff81adc06d)
Location: include/linux/seq_file.h:195
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sock_seq_show
```
```
In net/ipv4/udp.c (ffffffff81ade90d)
Location: include/linux/seq_file.h:195
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/ipv4/udp.c:udp4_format_sock
```
```
In net/ipv4/ping.c (ffffffff81b034b0)
Location: include/linux/seq_file.h:195
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_format_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b7535b)
Location: include/linux/seq_file.h:195
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:get_openreq6
```
```
In net/ipv6/datagram.c (ffffffff81b7e760)
Location: include/linux/seq_file.h:195
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7ebb8)
Location: include/linux/seq_file.h:195
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
```
In net/packet/af_packet.c (ffffffff81b94909)
Location: include/linux/seq_file.h:195
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
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
In kernel/user_namespace.c (ffffffff81182c90)
Location: include/linux/seq_file.h:199
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
  - kernel/user_namespace.c:projid_m_show
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:uid_m_show
```
```
In kernel/trace/trace.c (ffffffff811c10b7)
Location: include/linux/seq_file.h:199
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
```
```
In fs/io_uring.c (ffffffff813912f5)
Location: include/linux/seq_file.h:199
Inline: True
```
```
In fs/proc/array.c (ffffffff813da410)
Location: include/linux/seq_file.h:199
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In ipc/msg.c (ffffffff814ab552)
Location: include/linux/seq_file.h:199
Inline: True
Inline callers:
  - ipc/msg.c:sysvipc_msg_proc_show
```
```
In ipc/sem.c (ffffffff814ae125)
Location: include/linux/seq_file.h:199
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
```
```
In ipc/shm.c (ffffffff814b2ce2)
Location: include/linux/seq_file.h:199
Inline: True
Inline callers:
  - ipc/shm.c:sysvipc_shm_proc_show
```
```
In security/keys/proc.c (ffffffff814c2a27)
Location: include/linux/seq_file.h:199
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abb57e)
Location: include/linux/seq_file.h:199
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv4/raw.c (ffffffff81ac6f2c)
Location: include/linux/seq_file.h:199
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff81ac980d)
Location: include/linux/seq_file.h:199
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81aeed2e)
Location: include/linux/seq_file.h:199
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b63dd0)
Location: include/linux/seq_file.h:199
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
```
In net/ipv6/datagram.c (ffffffff81b6d370)
Location: include/linux/seq_file.h:199
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6d7b8)
Location: include/linux/seq_file.h:199
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
```
In net/packet/af_packet.c (ffffffff81b839e9)
Location: include/linux/seq_file.h:199
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
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
In kernel/user_namespace.c (ffffffff811aad20)
Location: include/linux/seq_file.h:207
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
  - kernel/user_namespace.c:projid_m_show
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:uid_m_show
```
```
In kernel/trace/trace.c (ffffffff811ebbd4)
Location: include/linux/seq_file.h:207
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
```
```
In fs/io_uring.c (ffffffff813df0e5)
Location: include/linux/seq_file.h:207
Inline: True
```
```
In fs/proc/array.c (ffffffff8142bb40)
Location: include/linux/seq_file.h:207
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In ipc/msg.c (ffffffff81503a12)
Location: include/linux/seq_file.h:207
Inline: True
Inline callers:
  - ipc/msg.c:sysvipc_msg_proc_show
```
```
In ipc/sem.c (ffffffff815065b5)
Location: include/linux/seq_file.h:207
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
```
```
In ipc/shm.c (ffffffff8150b322)
Location: include/linux/seq_file.h:207
Inline: True
Inline callers:
  - ipc/shm.c:sysvipc_shm_proc_show
```
```
In security/keys/proc.c (ffffffff8151b417)
Location: include/linux/seq_file.h:207
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7a154)
Location: include/linux/seq_file.h:207
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv4/raw.c (ffffffff81b8574c)
Location: include/linux/seq_file.h:207
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff81b8807d)
Location: include/linux/seq_file.h:207
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81baf0fe)
Location: include/linux/seq_file.h:207
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (ffffffff81be4e77)
Location: include/linux/seq_file.h:207
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2b890)
Location: include/linux/seq_file.h:207
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
```
In net/ipv6/datagram.c (ffffffff81c35290)
Location: include/linux/seq_file.h:207
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81c355f8)
Location: include/linux/seq_file.h:207
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
```
In net/packet/af_packet.c (ffffffff81c4faf9)
Location: include/linux/seq_file.h:207
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
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
In kernel/user_namespace.c (ffffffff811dc3f0)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
  - kernel/user_namespace.c:projid_m_show
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:uid_m_show
```
```
In kernel/trace/trace.c (ffffffff81223cc5)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
```
```
In fs/proc/array.c (ffffffff814a57a0)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In ipc/msg.c (ffffffff81595372)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - ipc/msg.c:sysvipc_msg_proc_show
```
```
In ipc/sem.c (ffffffff815975a5)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
```
```
In ipc/shm.c (ffffffff8159cd02)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - ipc/shm.c:sysvipc_shm_proc_show
```
```
In security/keys/proc.c (ffffffff815ae625)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
```
```
In io_uring/io_uring.c (ffffffff81e8fc6f)
Location: include/linux/seq_file.h:223
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0a2d9)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv4/raw.c (ffffffff81d16318)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff81d192a5)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81d4242d)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (ffffffff81d7c9ce)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dc8e32)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
```
In net/ipv6/datagram.c (ffffffff81dd2c3d)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81dd300d)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
```
In net/packet/af_packet.c (ffffffff81df05b9)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
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
In kernel/user_namespace.c (ffffffff81221cb0)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
  - kernel/user_namespace.c:projid_m_show
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:uid_m_show
```
```
In kernel/trace/trace.c (ffffffff8126edd5)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
```
```
In fs/proc/array.c (ffffffff8153adb0)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In ipc/msg.c (ffffffff8163e0d2)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - ipc/msg.c:sysvipc_msg_proc_show
```
```
In ipc/sem.c (ffffffff816406e5)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
```
```
In ipc/shm.c (ffffffff816461d2)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - ipc/shm.c:sysvipc_shm_proc_show
```
```
In security/keys/proc.c (ffffffff81658d85)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
```
```
In io_uring/fdinfo.c (ffffffff8179afc5)
Location: include/linux/seq_file.h:223
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecfb59)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv4/raw.c (ffffffff81edc4e8)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff81edfa45)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81f0b29d)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (ffffffff81f49a4e)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f99b42)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
```
In net/ipv6/datagram.c (ffffffff81fa40fd)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81fa452d)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
```
In net/packet/af_packet.c (ffffffff81fc4739)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
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
In kernel/user_namespace.c (ffffffff81238160)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
  - kernel/user_namespace.c:projid_m_show
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:uid_m_show
```
```
In kernel/trace/trace.c (ffffffff81286032)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
```
```
In fs/proc/array.c (ffffffff815730c0)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In ipc/msg.c (ffffffff816765c2)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - ipc/msg.c:sysvipc_msg_proc_show
```
```
In ipc/sem.c (ffffffff81678c05)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
```
```
In ipc/shm.c (ffffffff8167e6e2)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - ipc/shm.c:sysvipc_shm_proc_show
```
```
In security/keys/proc.c (ffffffff81691622)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
```
```
In io_uring/fdinfo.c (ffffffff817dc0f5)
Location: include/linux/seq_file.h:223
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2e824)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv4/raw.c (ffffffff81f3b638)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff81f3ec21)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81f6ae7d)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (ffffffff81fa96ae)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffa512)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
```
In net/ipv6/datagram.c (ffffffff820049bd)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff82004ddd)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
```
In net/packet/af_packet.c (ffffffff82027869)
Location: include/linux/seq_file.h:223
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
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
In kernel/user_namespace.c (ffffffff81251e30)
Location: include/linux/seq_file.h:238
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
  - kernel/user_namespace.c:projid_m_show
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:uid_m_show
```
```
In kernel/trace/trace.c (ffffffff812a1142)
Location: include/linux/seq_file.h:238
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
```
```
In fs/proc/array.c (ffffffff815ab880)
Location: include/linux/seq_file.h:238
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In ipc/msg.c (ffffffff816b2982)
Location: include/linux/seq_file.h:238
Inline: True
Inline callers:
  - ipc/msg.c:sysvipc_msg_proc_show
```
```
In ipc/sem.c (ffffffff816b4ff5)
Location: include/linux/seq_file.h:238
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
```
```
In ipc/shm.c (ffffffff816baad2)
Location: include/linux/seq_file.h:238
Inline: True
Inline callers:
  - ipc/shm.c:sysvipc_shm_proc_show
```
```
In security/keys/proc.c (ffffffff816cdbf2)
Location: include/linux/seq_file.h:238
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
```
```
In io_uring/fdinfo.c (ffffffff81820485)
Location: include/linux/seq_file.h:238
Inline: True
```
```
In drivers/gpu/drm/drm_debugfs.c (ffffffff81cbaa40)
Location: include/linux/seq_file.h:238
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_debugfs.c:drm_clients_info
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff3684)
Location: include/linux/seq_file.h:238
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv4/raw.c (ffffffff82001758)
Location: include/linux/seq_file.h:238
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff82004f81)
Location: include/linux/seq_file.h:238
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff8203152d)
Location: include/linux/seq_file.h:238
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/unix/af_unix.c (ffffffff82076b3e)
Location: include/linux/seq_file.h:238
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c8182)
Location: include/linux/seq_file.h:238
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
```
In net/ipv6/datagram.c (ffffffff820d378d)
Location: include/linux/seq_file.h:238
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d3bae)
Location: include/linux/seq_file.h:238
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
```
In net/packet/af_packet.c (ffffffff820f70c9)
Location: include/linux/seq_file.h:238
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
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
In kernel/user_namespace.c (ffff8000101e6c30)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
  - kernel/user_namespace.c:projid_m_show
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:uid_m_show
```
```
In kernel/trace/trace.c (0)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
```
```
In fs/proc/array.c (ffff800010444cd0)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In ipc/msg.c (ffff80001051e990)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/msg.c:sysvipc_msg_proc_show
```
```
In ipc/sem.c (ffff800010522668)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
```
```
In ipc/shm.c (ffff800010527418)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/shm.c:sysvipc_shm_proc_show
```
```
In security/keys/proc.c (ffff8000105372f4)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8a4f4)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/raw.c (ffff800010c96a2c)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffff800010c991dc)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffff800010cbfb9c)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d36060)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
```
In net/ipv6/datagram.c (ffff800010d3e348)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3e8f8)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
```
In net/packet/af_packet.c (ffff800010d56810)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
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
In kernel/user_namespace.c (c042728c)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
  - kernel/user_namespace.c:projid_m_show
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:uid_m_show
```
```
In kernel/trace/trace.c (c0464584)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
```
```
In fs/proc/array.c (c06098b8)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In ipc/msg.c (c06dad80)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/msg.c:sysvipc_msg_proc_show
```
```
In ipc/sem.c (c06dc74c)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
```
```
In ipc/shm.c (c06e04a8)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/shm.c:sysvipc_shm_proc_show
```
```
In security/keys/proc.c (c06ee180)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
```
```
In net/ipv4/tcp_ipv4.c (c0d9a650)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/raw.c (c0da5108)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (c0da80d8)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (c0dcb658)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (c0e38f48)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
```
In net/ipv6/datagram.c (c0e41680)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/ip6_flowlabel.c (c0e41d24)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
```
In net/packet/af_packet.c (c0e56fd8)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
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
In kernel/user_namespace.c (c000000000257438)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
  - kernel/user_namespace.c:projid_m_show
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:uid_m_show
```
```
In kernel/trace/trace.c (c0000000002ad044)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
```
```
In fs/proc/array.c (c00000000055a0b4)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In ipc/msg.c (c000000000668034)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/msg.c:sysvipc_msg_proc_show
```
```
In ipc/sem.c (c00000000066b0a0)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
```
```
In ipc/shm.c (c0000000006708b8)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/shm.c:sysvipc_shm_proc_show
```
```
In security/keys/proc.c (c000000000686024)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
```
```
In net/ipv4/tcp_ipv4.c (c000000000d98c70)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/raw.c (c000000000da8680)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (c000000000dabdd8)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (c000000000ddac4c)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (c000000000e68464)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
```
In net/ipv6/datagram.c (c000000000e72ab8)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/ip6_flowlabel.c (c000000000e73860)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
```
In net/packet/af_packet.c (c000000000e8fbb8)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
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
In kernel/user_namespace.c (ffffffe00015c45a)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
  - kernel/user_namespace.c:projid_m_show
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:uid_m_show
```
```
In kernel/trace/trace.c (ffffffe000181afc)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
```
```
In fs/proc/array.c (ffffffe0002dac6e)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In ipc/msg.c (ffffffe000385b96)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/msg.c:sysvipc_msg_proc_show
```
```
In ipc/sem.c (ffffffe000387b6a)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
```
```
In ipc/shm.c (ffffffe00038ab4a)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/shm.c:sysvipc_shm_proc_show
```
```
In security/keys/proc.c (ffffffe000396636)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eb84e)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/raw.c (ffffffe0007f5c6e)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffe0007f7716)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffe0008158da)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008736ce)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
```
In net/ipv6/datagram.c (ffffffe00087a8fe)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/ip6_flowlabel.c (ffffffe00087affe)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
```
In net/packet/af_packet.c (ffffffe00088e18a)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
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
In kernel/user_namespace.c (ffffffff8116b2b0)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
  - kernel/user_namespace.c:projid_m_show
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:uid_m_show
```
```
In kernel/trace/trace.c (ffffffff811a27b9)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
```
```
In fs/proc/array.c (ffffffff81370c0d)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In ipc/msg.c (ffffffff814305a2)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/msg.c:sysvipc_msg_proc_show
```
```
In ipc/sem.c (ffffffff81432d55)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
```
```
In ipc/shm.c (ffffffff81436a82)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/shm.c:sysvipc_shm_proc_show
```
```
In security/keys/proc.c (ffffffff81445847)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197750e)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/raw.c (ffffffff8198299c)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff8198499f)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff819a698e)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0ce53)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
```
In net/ipv6/datagram.c (ffffffff81a15080)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a15728)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
```
In net/packet/af_packet.c (ffffffff81a290d9)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
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
In kernel/user_namespace.c (ffffffff8115e4b0)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
  - kernel/user_namespace.c:projid_m_show
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:uid_m_show
```
```
In kernel/trace/trace.c (ffffffff81195789)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
```
```
In fs/proc/array.c (ffffffff8136169d)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In ipc/msg.c (ffffffff81421022)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/msg.c:sysvipc_msg_proc_show
```
```
In ipc/sem.c (ffffffff814237d5)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
```
```
In ipc/shm.c (ffffffff814274f2)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/shm.c:sysvipc_shm_proc_show
```
```
In security/keys/proc.c (ffffffff81436297)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81930fce)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/raw.c (ffffffff8193c45c)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff8193e45f)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff8196044e)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c9c13)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
```
In net/ipv6/datagram.c (ffffffff819d1e40)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d24e8)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
```
In net/packet/af_packet.c (ffffffff819e62c9)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
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
In kernel/user_namespace.c (ffffffff81169080)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
  - kernel/user_namespace.c:projid_m_show
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:uid_m_show
```
```
In kernel/trace/trace.c (ffffffff811a0589)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
```
```
In fs/proc/array.c (ffffffff8136e6dd)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In ipc/msg.c (ffffffff8142c742)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/msg.c:sysvipc_msg_proc_show
```
```
In ipc/sem.c (ffffffff8142eef5)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
```
```
In ipc/shm.c (ffffffff81432c22)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/shm.c:sysvipc_shm_proc_show
```
```
In security/keys/proc.c (ffffffff814418e7)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e1cde)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/raw.c (ffffffff819ed16c)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff819ef16f)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81a1122e)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a778d3)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
```
In net/ipv6/datagram.c (ffffffff81a7fb00)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a801a8)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
```
In net/packet/af_packet.c (ffffffff81a94c89)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
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
In kernel/user_namespace.c (ffffffff81176770)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
  - kernel/user_namespace.c:projid_m_show
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:uid_m_show
```
```
In kernel/trace/trace.c (ffffffff811ae319)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
```
```
In fs/proc/array.c (ffffffff81382030)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In ipc/msg.c (ffffffff81443a92)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/msg.c:sysvipc_msg_proc_show
```
```
In ipc/sem.c (ffffffff814455f5)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
```
```
In ipc/shm.c (ffffffff81449e92)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - ipc/shm.c:sysvipc_shm_proc_show
```
```
In security/keys/proc.c (ffffffff81458c17)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - security/keys/proc.c:proc_key_users_show
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_show
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819eba2e)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/raw.c (ffffffff819f704c)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff819f995f)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81a1bb9e)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a84043)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
```
In net/ipv6/datagram.c (ffffffff81a8c3c0)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/datagram.c:__ip6_dgram_sock_seq_show
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a8cb59)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
```
In net/packet/af_packet.c (ffffffff81aa0dd9)
Location: include/linux/seq_file.h:163
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
```
</details>
</li>
</ul>

## Differences
