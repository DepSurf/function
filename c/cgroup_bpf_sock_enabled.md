# Function: <code>cgroup_bpf_sock_enabled</code>

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
In net/socket.c (ffffffff81be9d2a)
Location: include/linux/bpf-cgroup.h:170
Inline: True
Inline callers:
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
```
```
In net/core/filter.c (ffffffff81c3ca2b)
Location: include/linux/bpf-cgroup.h:170
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81cd8f43)
Location: include/linux/bpf-cgroup.h:170
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv6/ip6_output.c (ffffffff81d8a93a)
Location: include/linux/bpf-cgroup.h:170
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
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
In net/socket.c (ffffffff81d965ea)
Location: include/linux/bpf-cgroup.h:177
Inline: True
Inline callers:
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
```
```
In net/core/filter.c (ffffffff81dfa3c1)
Location: include/linux/bpf-cgroup.h:177
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81e99589)
Location: include/linux/bpf-cgroup.h:177
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv6/ip6_output.c (ffffffff81f588ea)
Location: include/linux/bpf-cgroup.h:177
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
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
In net/socket.c (ffffffff81e04c3a)
Location: include/linux/bpf-cgroup.h:177
Inline: True
Inline callers:
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
```
```
In net/core/filter.c (ffffffff81e6b761)
Location: include/linux/bpf-cgroup.h:177
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81ef7e97)
Location: include/linux/bpf-cgroup.h:177
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv6/ip6_output.c (ffffffff81fb864c)
Location: include/linux/bpf-cgroup.h:177
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
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
In net/socket.c (ffffffff81ebdb6b)
Location: include/linux/bpf-cgroup.h:184
Inline: True
Inline callers:
  - net/socket.c:do_sock_getsockopt
  - net/socket.c:do_sock_setsockopt
```
```
In net/core/filter.c (ffffffff81f2a911)
Location: include/linux/bpf-cgroup.h:184
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81fbbd64)
Location: include/linux/bpf-cgroup.h:184
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv6/ip6_output.c (ffffffff82085c39)
Location: include/linux/bpf-cgroup.h:184
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
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
