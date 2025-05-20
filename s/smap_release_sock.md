# Function: <code>smap_release_sock</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/sockmap.c (ffffffff811b1a2d)
Location: kernel/bpf/sockmap.c:355
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:sock_map_delete_elem
  - kernel/bpf/sockmap.c:sock_map_free
  - kernel/bpf/sockmap.c:smap_state_change
Direct callers:
  - kernel/bpf/sockmap.c:sock_map_delete_elem
  - kernel/bpf/sockmap.c:sock_map_free
  - kernel/bpf/sockmap.c:smap_state_change
```
**Symbols:**

```
ffffffff811b1000-ffffffff811b10a5: smap_release_sock.part.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void smap_release_sock(struct smap_psock *psock, struct sock *sock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/sockmap.c (ffffffff811ccfa0)
Location: kernel/bpf/sockmap.c:1470
Inline: True
Direct callers:
  - kernel/bpf/sockmap.c:sock_hash_delete_elem
  - kernel/bpf/sockmap.c:sock_hash_free
  - kernel/bpf/sockmap.c:sock_map_delete_elem
  - kernel/bpf/sockmap.c:sock_map_free
  - kernel/bpf/sockmap.c:bpf_tcp_sendpage
  - kernel/bpf/sockmap.c:bpf_tcp_sendmsg
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
  - kernel/bpf/sockmap.c:bpf_tcp_close
  - kernel/bpf/sockmap.c:bpf_tcp_close
```
**Symbols:**

```
ffffffff811ccfa0-ffffffff811cd05a: smap_release_sock (STB_LOCAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<b>Regular</b>
<ul>
</ul>
