# Function: <code>bpf_iter_reg_target</code>

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
int bpf_iter_reg_target(const struct bpf_iter_reg *reg_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff81215bd0)
Location: kernel/bpf/bpf_iter.c:255
Inline: False
Direct callers:
  - kernel/bpf/map_iter.c:bpf_map_iter_init
  - kernel/bpf/task_iter.c:task_iter_init
  - kernel/bpf/task_iter.c:task_iter_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv6/route.c:ip6_route_init
```
**Symbols:**

```
ffffffff81215bd0-ffffffff81215c4b: bpf_iter_reg_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_iter_reg_target(const struct bpf_iter_reg *reg_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff81217a60)
Location: kernel/bpf/bpf_iter.c:286
Inline: False
Direct callers:
  - kernel/bpf/map_iter.c:bpf_map_iter_init
  - kernel/bpf/map_iter.c:bpf_map_iter_init
  - kernel/bpf/task_iter.c:task_iter_init
  - kernel/bpf/task_iter.c:task_iter_init
  - kernel/bpf/prog_iter.c:bpf_prog_iter_init
  - net/core/sock_map.c:bpf_sockmap_iter_init
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_iter_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/udp.c:udp_init
  - net/ipv6/route.c:ip6_route_init
```
**Symbols:**

```
ffffffff81217a60-ffffffff81217adb: bpf_iter_reg_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_iter_reg_target(const struct bpf_iter_reg *reg_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff8121aed0)
Location: kernel/bpf/bpf_iter.c:286
Inline: False
Direct callers:
  - kernel/bpf/map_iter.c:bpf_map_iter_init
  - kernel/bpf/map_iter.c:bpf_map_iter_init
  - kernel/bpf/task_iter.c:task_iter_init
  - kernel/bpf/task_iter.c:task_iter_init
  - kernel/bpf/task_iter.c:task_iter_init
  - kernel/bpf/prog_iter.c:bpf_prog_iter_init
  - net/core/sock_map.c:bpf_sockmap_iter_init
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_iter_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/udp.c:udp_init
  - net/ipv6/route.c:ip6_route_init
```
**Symbols:**

```
ffffffff8121aed0-ffffffff8121af4b: bpf_iter_reg_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_iter_reg_target(const struct bpf_iter_reg *reg_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff81251cd0)
Location: kernel/bpf/bpf_iter.c:286
Inline: False
Direct callers:
  - kernel/bpf/map_iter.c:bpf_map_iter_init
  - kernel/bpf/map_iter.c:bpf_map_iter_init
  - kernel/bpf/task_iter.c:task_iter_init
  - kernel/bpf/task_iter.c:task_iter_init
  - kernel/bpf/task_iter.c:task_iter_init
  - kernel/bpf/prog_iter.c:bpf_prog_iter_init
  - net/core/sock_map.c:bpf_sockmap_iter_init
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_iter_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/udp.c:udp_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/route.c:ip6_route_init
```
**Symbols:**

```
ffffffff81251cd0-ffffffff81251d4b: bpf_iter_reg_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_iter_reg_target(const struct bpf_iter_reg *reg_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff81299910)
Location: kernel/bpf/bpf_iter.c:287
Inline: False
Direct callers:
  - kernel/bpf/map_iter.c:bpf_map_iter_init
  - kernel/bpf/map_iter.c:bpf_map_iter_init
  - kernel/bpf/task_iter.c:task_iter_init
  - kernel/bpf/task_iter.c:task_iter_init
  - kernel/bpf/task_iter.c:task_iter_init
  - kernel/bpf/prog_iter.c:bpf_prog_iter_init
  - kernel/bpf/link_iter.c:bpf_link_iter_init
  - net/core/sock_map.c:bpf_sockmap_iter_init
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_iter_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/udp.c:udp_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/route.c:ip6_route_init
```
**Symbols:**

```
ffffffff81299910-ffffffff81299995: bpf_iter_reg_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_iter_reg_target(const struct bpf_iter_reg *reg_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff812f5750)
Location: kernel/bpf/bpf_iter.c:296
Inline: False
Direct callers:
  - kernel/kallsyms.c:bpf_ksym_iter_register
  - kernel/bpf/map_iter.c:bpf_map_iter_init
  - kernel/bpf/map_iter.c:bpf_map_iter_init
  - kernel/bpf/task_iter.c:task_iter_init
  - kernel/bpf/task_iter.c:task_iter_init
  - kernel/bpf/task_iter.c:task_iter_init
  - kernel/bpf/prog_iter.c:bpf_prog_iter_init
  - kernel/bpf/link_iter.c:bpf_link_iter_init
  - kernel/bpf/cgroup_iter.c:bpf_cgroup_iter_init
  - net/core/sock_map.c:bpf_sockmap_iter_init
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_iter_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/udp.c:udp_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/route.c:ip6_route_init
```
**Symbols:**

```
ffffffff812f5750-ffffffff812f57d5: bpf_iter_reg_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_iter_reg_target(const struct bpf_iter_reg *reg_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff813234f0)
Location: kernel/bpf/bpf_iter.c:296
Inline: False
Direct callers:
  - kernel/kallsyms.c:bpf_ksym_iter_register
  - kernel/bpf/map_iter.c:bpf_map_iter_init
  - kernel/bpf/map_iter.c:bpf_map_iter_init
  - kernel/bpf/task_iter.c:task_iter_init
  - kernel/bpf/task_iter.c:task_iter_init
  - kernel/bpf/task_iter.c:task_iter_init
  - kernel/bpf/prog_iter.c:bpf_prog_iter_init
  - kernel/bpf/link_iter.c:bpf_link_iter_init
  - kernel/bpf/cgroup_iter.c:bpf_cgroup_iter_init
  - net/core/sock_map.c:bpf_sockmap_iter_init
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_iter_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/udp.c:udp_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/route.c:ip6_route_init
```
**Symbols:**

```
ffffffff813234f0-ffffffff81323575: bpf_iter_reg_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_iter_reg_target(const struct bpf_iter_reg *reg_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff81347420)
Location: kernel/bpf/bpf_iter.c:296
Inline: False
Direct callers:
  - kernel/kallsyms.c:bpf_ksym_iter_register
  - kernel/bpf/map_iter.c:bpf_map_iter_init
  - kernel/bpf/map_iter.c:bpf_map_iter_init
  - kernel/bpf/task_iter.c:task_iter_init
  - kernel/bpf/task_iter.c:task_iter_init
  - kernel/bpf/task_iter.c:task_iter_init
  - kernel/bpf/prog_iter.c:bpf_prog_iter_init
  - kernel/bpf/link_iter.c:bpf_link_iter_init
  - kernel/bpf/cgroup_iter.c:bpf_cgroup_iter_init
  - net/core/sock_map.c:bpf_sockmap_iter_init
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_iter_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/udp.c:udp_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/route.c:ip6_route_init
```
**Symbols:**

```
ffffffff81347420-ffffffff813474d4: bpf_iter_reg_target (STB_GLOBAL)
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
