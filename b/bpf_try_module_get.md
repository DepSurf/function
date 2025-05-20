# Function: <code>bpf_try_module_get</code>

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
In net/ipv4/tcp_output.c (ffffffff81abc76e)
Location: include/linux/bpf.h:782
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_ca_dst_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac4e00)
Location: include/linux/bpf.h:782
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81aca558)
Location: include/linux/bpf.h:782
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_cong.c (ffffffff81acb4ed)
Location: include/linux/bpf.h:782
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff81ac7ece)
Location: include/linux/bpf.h:937
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_ca_dst_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad0790)
Location: include/linux/bpf.h:937
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad64b8)
Location: include/linux/bpf.h:937
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_cong.c (ffffffff81ad736c)
Location: include/linux/bpf.h:937
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff81ab3760)
Location: include/linux/bpf.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abb880)
Location: include/linux/bpf.h:964
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac1532)
Location: include/linux/bpf.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_cong.c (ffffffff81ac2466)
Location: include/linux/bpf.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff81b7056e)
Location: include/linux/bpf.h:1001
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b78aa3)
Location: include/linux/bpf.h:1001
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e5b2)
Location: include/linux/bpf.h:1001
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_cong.c (ffffffff81b801da)
Location: include/linux/bpf.h:1001
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff81cffafd)
Location: include/linux/bpf.h:1168
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d08dce)
Location: include/linux/bpf.h:1168
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0e553)
Location: include/linux/bpf.h:1168
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_cong.c (ffffffff81d105c1)
Location: include/linux/bpf.h:1168
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff81ec4b9d)
Location: include/linux/bpf.h:1457
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecd9ca)
Location: include/linux/bpf.h:1457
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed4013)
Location: include/linux/bpf.h:1457
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_cong.c (ffffffff81ed62e1)
Location: include/linux/bpf.h:1457
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff81f234f6)
Location: include/linux/bpf.h:1573
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2c682)
Location: include/linux/bpf.h:1573
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f33033)
Location: include/linux/bpf.h:1573
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_cong.c (ffffffff81f35201)
Location: include/linux/bpf.h:1573
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
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
In net/ipv4/tcp_output.c (ffffffff81fe7985)
Location: include/linux/bpf.h:1698
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff15fc)
Location: include/linux/bpf.h:1698
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff9183)
Location: include/linux/bpf.h:1698
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
```
```
In net/ipv4/tcp_cong.c (ffffffff81ffb381)
Location: include/linux/bpf.h:1698
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
```
In net/mptcp/sched.c (ffffffff82161dfe)
Location: include/linux/bpf.h:1698
Inline: True
Inline callers:
  - net/mptcp/sched.c:mptcp_init_sched
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
