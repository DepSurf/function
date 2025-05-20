# Function: <code>bpf_iter_run_prog</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_iter_run_prog(struct bpf_prog *prog, void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff81216050)
Location: kernel/bpf/bpf_iter.c:535
Inline: False
Direct callers:
  - kernel/bpf/map_iter.c:bpf_map_seq_show
  - kernel/bpf/task_iter.c:task_file_seq_show
  - kernel/bpf/task_iter.c:task_seq_show
  - net/netlink/af_netlink.c:netlink_seq_stop
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
```
**Symbols:**

```
ffffffff81216050-ffffffff812160ce: bpf_iter_run_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_iter_run_prog(struct bpf_prog *prog, void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff81217fc0)
Location: kernel/bpf/bpf_iter.c:660
Inline: False
Direct callers:
  - kernel/bpf/map_iter.c:bpf_map_seq_show
  - kernel/bpf/task_iter.c:task_file_seq_show
  - kernel/bpf/task_iter.c:task_seq_show
  - kernel/bpf/prog_iter.c:bpf_prog_seq_show
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - net/core/sock_map.c:sock_hash_seq_show
  - net/core/sock_map.c:sock_map_seq_show
  - net/core/bpf_sk_storage.c:__bpf_sk_storage_map_seq_show
  - net/netlink/af_netlink.c:netlink_seq_stop
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/udp.c:bpf_iter_udp_seq_stop
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
```
**Symbols:**

```
ffffffff81217fc0-ffffffff8121804d: bpf_iter_run_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_iter_run_prog(struct bpf_prog *prog, void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff8121b410)
Location: kernel/bpf/bpf_iter.c:660
Inline: False
Direct callers:
  - kernel/bpf/map_iter.c:bpf_map_seq_show
  - kernel/bpf/task_iter.c:task_vma_seq_stop
  - kernel/bpf/task_iter.c:task_vma_seq_show
  - kernel/bpf/task_iter.c:task_file_seq_show
  - kernel/bpf/task_iter.c:task_seq_show
  - kernel/bpf/prog_iter.c:bpf_prog_seq_show
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - net/core/sock_map.c:sock_hash_seq_show
  - net/core/sock_map.c:sock_map_seq_show
  - net/core/bpf_sk_storage.c:__bpf_sk_storage_map_seq_show
  - net/netlink/af_netlink.c:netlink_seq_stop
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/udp.c:bpf_iter_udp_seq_stop
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
```
**Symbols:**

```
ffffffff8121b410-ffffffff8121b493: bpf_iter_run_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_iter_run_prog(struct bpf_prog *prog, void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff81252320)
Location: kernel/bpf/bpf_iter.c:683
Inline: False
Direct callers:
  - kernel/bpf/map_iter.c:bpf_map_seq_show
  - kernel/bpf/task_iter.c:task_vma_seq_stop
  - kernel/bpf/task_iter.c:task_vma_seq_show
  - kernel/bpf/task_iter.c:task_file_seq_show
  - kernel/bpf/task_iter.c:task_seq_show
  - kernel/bpf/prog_iter.c:bpf_prog_seq_show
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - net/core/sock_map.c:sock_hash_seq_show
  - net/core/sock_map.c:sock_map_seq_show
  - net/core/bpf_sk_storage.c:__bpf_sk_storage_map_seq_show
  - net/netlink/af_netlink.c:netlink_seq_stop
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/udp.c:bpf_iter_udp_seq_stop
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/unix/af_unix.c:bpf_iter_unix_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
```
**Symbols:**

```
ffffffff81252320-ffffffff8125239f: bpf_iter_run_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int bpf_iter_run_prog(struct bpf_prog *prog, void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_iter.c (0)
Location: kernel/bpf/bpf_iter.c:682
Inline: False
Direct callers:
  - kernel/bpf/map_iter.c:bpf_map_seq_show
  - kernel/bpf/task_iter.c:task_vma_seq_show
  - kernel/bpf/task_iter.c:task_file_seq_show
  - kernel/bpf/task_iter.c:task_seq_show
  - kernel/bpf/prog_iter.c:bpf_prog_seq_show
  - kernel/bpf/link_iter.c:bpf_link_seq_show
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - net/core/sock_map.c:sock_hash_seq_show
  - net/core/sock_map.c:sock_map_seq_show
  - net/core/bpf_sk_storage.c:__bpf_sk_storage_map_seq_show
  - net/netlink/af_netlink.c:netlink_seq_stop
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/udp.c:bpf_iter_udp_seq_stop
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/unix/af_unix.c:bpf_iter_unix_seq_stop
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
```
**Symbols:**

```
ffffffff81e6a4a0-ffffffff81e6a4b5: bpf_iter_run_prog.cold (STB_LOCAL)
ffffffff8129a020-ffffffff8129a18e: bpf_iter_run_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int bpf_iter_run_prog(struct bpf_prog *prog, void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_iter.c (0)
Location: kernel/bpf/bpf_iter.c:695
Inline: False
Direct callers:
  - kernel/kallsyms.c:bpf_iter_ksym_seq_show
  - kernel/bpf/map_iter.c:bpf_map_seq_show
  - kernel/bpf/task_iter.c:task_vma_seq_show
  - kernel/bpf/task_iter.c:task_file_seq_show
  - kernel/bpf/task_iter.c:task_seq_show
  - kernel/bpf/prog_iter.c:bpf_prog_seq_show
  - kernel/bpf/link_iter.c:bpf_link_seq_show
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_show
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_stop
  - net/core/sock_map.c:sock_hash_seq_show
  - net/core/sock_map.c:sock_map_seq_show
  - net/core/bpf_sk_storage.c:__bpf_sk_storage_map_seq_show
  - net/netlink/af_netlink.c:netlink_seq_stop
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/udp.c:bpf_iter_udp_seq_stop
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/unix/af_unix.c:bpf_iter_unix_seq_stop
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
```
**Symbols:**

```
ffffffff82061569-ffffffff8206157e: bpf_iter_run_prog.cold (STB_LOCAL)
ffffffff812f5f10-ffffffff812f6100: bpf_iter_run_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bpf_iter_run_prog(struct bpf_prog *prog, void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_iter.c (0)
Location: kernel/bpf/bpf_iter.c:695
Inline: False
Direct callers:
  - kernel/kallsyms.c:bpf_iter_ksym_seq_show
  - kernel/bpf/map_iter.c:bpf_map_seq_show
  - kernel/bpf/task_iter.c:task_vma_seq_show
  - kernel/bpf/task_iter.c:task_file_seq_show
  - kernel/bpf/task_iter.c:task_seq_show
  - kernel/bpf/prog_iter.c:bpf_prog_seq_show
  - kernel/bpf/link_iter.c:bpf_link_seq_show
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_show
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_stop
  - net/core/sock_map.c:sock_hash_seq_show
  - net/core/sock_map.c:sock_map_seq_show
  - net/core/bpf_sk_storage.c:__bpf_sk_storage_map_seq_show
  - net/netlink/af_netlink.c:netlink_seq_stop
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/udp.c:bpf_iter_udp_seq_stop
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/unix/af_unix.c:bpf_iter_unix_seq_stop
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
```
**Symbols:**

```
ffffffff820e0af6-ffffffff820e0b0b: bpf_iter_run_prog.cold (STB_LOCAL)
ffffffff81323cb0-ffffffff81323eb0: bpf_iter_run_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bpf_iter_run_prog(struct bpf_prog *prog, void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_iter.c (0)
Location: kernel/bpf/bpf_iter.c:695
Inline: False
Direct callers:
  - kernel/kallsyms.c:bpf_iter_ksym_seq_show
  - kernel/bpf/map_iter.c:bpf_map_seq_show
  - kernel/bpf/task_iter.c:task_vma_seq_show
  - kernel/bpf/task_iter.c:task_file_seq_show
  - kernel/bpf/task_iter.c:task_seq_show
  - kernel/bpf/prog_iter.c:bpf_prog_seq_show
  - kernel/bpf/link_iter.c:bpf_link_seq_show
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_show
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_stop
  - net/core/sock_map.c:sock_hash_seq_show
  - net/core/sock_map.c:sock_map_seq_show
  - net/core/bpf_sk_storage.c:__bpf_sk_storage_map_seq_show
  - net/netlink/af_netlink.c:netlink_seq_stop
  - net/netlink/af_netlink.c:netlink_seq_show
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/udp.c:bpf_iter_udp_seq_stop
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/unix/af_unix.c:bpf_iter_unix_seq_stop
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
```
**Symbols:**

```
ffffffff821bd2b6-ffffffff821bd2cb: bpf_iter_run_prog.cold (STB_LOCAL)
ffffffff81347c40-ffffffff81347e40: bpf_iter_run_prog (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
