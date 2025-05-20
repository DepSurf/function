# Function: <code>bpf_struct_ops_get</code>

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
bool bpf_struct_ops_get(const void *kdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff81230130)
Location: kernel/bpf/bpf_struct_ops.c:628
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_ca_dst_init
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
**Symbols:**

```
ffffffff81230130-ffffffff81230182: bpf_struct_ops_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool bpf_struct_ops_get(const void *kdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff812385e0)
Location: kernel/bpf/bpf_struct_ops.c:616
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_ca_dst_init
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
**Symbols:**

```
ffffffff812385e0-ffffffff81238632: bpf_struct_ops_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool bpf_struct_ops_get(const void *kdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff8123cdd0)
Location: kernel/bpf/bpf_struct_ops.c:616
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
**Symbols:**

```
ffffffff8123cdd0-ffffffff8123ce1e: bpf_struct_ops_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool bpf_struct_ops_get(const void *kdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff81277850)
Location: kernel/bpf/bpf_struct_ops.c:620
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
**Symbols:**

```
ffffffff81277850-ffffffff8127789e: bpf_struct_ops_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool bpf_struct_ops_get(const void *kdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff812c74f0)
Location: kernel/bpf/bpf_struct_ops.c:659
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
**Symbols:**

```
ffffffff812c74f0-ffffffff812c7551: bpf_struct_ops_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool bpf_struct_ops_get(const void *kdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff8132cec0)
Location: kernel/bpf/bpf_struct_ops.c:660
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
**Symbols:**

```
ffffffff8132cec0-ffffffff8132cf21: bpf_struct_ops_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool bpf_struct_ops_get(const void *kdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff8135d310)
Location: kernel/bpf/bpf_struct_ops.c:733
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
```
**Symbols:**

```
ffffffff8135d310-ffffffff8135d33a: bpf_struct_ops_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool bpf_struct_ops_get(const void *kdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff81386060)
Location: kernel/bpf/bpf_struct_ops.c:757
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_assign_congestion_control
  - net/mptcp/sched.c:mptcp_init_sched
```
**Symbols:**

```
ffffffff81386060-ffffffff8138608a: bpf_struct_ops_get (STB_GLOBAL)
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
