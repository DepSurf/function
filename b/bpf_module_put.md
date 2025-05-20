# Function: <code>bpf_module_put</code>

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
In net/ipv4/tcp_output.c (ffffffff81abc79e)
Location: include/linux/bpf.h:789
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_ca_dst_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac4a82)
Location: include/linux/bpf.h:789
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/tcp_cong.c (ffffffff81acb521)
Location: include/linux/bpf.h:789
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_reinit_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff81ac7efe)
Location: include/linux/bpf.h:944
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_ca_dst_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad0292)
Location: include/linux/bpf.h:944
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/tcp_cong.c (ffffffff81ad73ba)
Location: include/linux/bpf.h:944
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff81ab3792)
Location: include/linux/bpf.h:971
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abb3fb)
Location: include/linux/bpf.h:971
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/tcp_cong.c (ffffffff81ac24b4)
Location: include/linux/bpf.h:971
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff81b705a0)
Location: include/linux/bpf.h:1008
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7874d)
Location: include/linux/bpf.h:1008
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/tcp_cong.c (ffffffff81b80228)
Location: include/linux/bpf.h:1008
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff81cffb2e)
Location: include/linux/bpf.h:1175
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d09a8b)
Location: include/linux/bpf.h:1175
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/tcp_cong.c (ffffffff81d1060d)
Location: include/linux/bpf.h:1175
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff81ec4bce)
Location: include/linux/bpf.h:1464
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecce50)
Location: include/linux/bpf.h:1464
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/tcp_cong.c (ffffffff81ed632d)
Location: include/linux/bpf.h:1464
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff81f23527)
Location: include/linux/bpf.h:1580
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2bb30)
Location: include/linux/bpf.h:1580
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/tcp_cong.c (ffffffff81f3524d)
Location: include/linux/bpf.h:1580
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff81fe79b2)
Location: include/linux/bpf.h:1705
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff08f0)
Location: include/linux/bpf.h:1705
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
```
```
In net/ipv4/tcp_cong.c (ffffffff81ffb3cd)
Location: include/linux/bpf.h:1705
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
```
```
In net/mptcp/sched.c (ffffffff82161ebd)
Location: include/linux/bpf.h:1705
Inline: True
Inline callers:
  - net/mptcp/sched.c:mptcp_release_sched
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
