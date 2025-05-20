# Function: <code>bpf_struct_ops_put</code>

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
void bpf_struct_ops_put(const void *kdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff81230190)
Location: kernel/bpf/bpf_struct_ops.c:637
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_ca_dst_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/ipv4/tcp_cong.c:tcp_reinit_congestion_control
```
**Symbols:**

```
ffffffff81230190-ffffffff812301cf: bpf_struct_ops_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_struct_ops_put(const void *kdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff81238640)
Location: kernel/bpf/bpf_struct_ops.c:625
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_ca_dst_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
```
**Symbols:**

```
ffffffff81238640-ffffffff8123867f: bpf_struct_ops_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_struct_ops_put(const void *kdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff8123ce20)
Location: kernel/bpf/bpf_struct_ops.c:625
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
```
**Symbols:**

```
ffffffff8123ce20-ffffffff8123ce5f: bpf_struct_ops_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_struct_ops_put(const void *kdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff812778a0)
Location: kernel/bpf/bpf_struct_ops.c:637
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
```
**Symbols:**

```
ffffffff812778a0-ffffffff812778e6: bpf_struct_ops_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_struct_ops_put(const void *kdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff812c7560)
Location: kernel/bpf/bpf_struct_ops.c:676
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
```
**Symbols:**

```
ffffffff812c7560-ffffffff812c75ca: bpf_struct_ops_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_struct_ops_put(const void *kdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff8132cf40)
Location: kernel/bpf/bpf_struct_ops.c:677
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
```
**Symbols:**

```
ffffffff8132cf40-ffffffff8132cfaa: bpf_struct_ops_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_struct_ops_put(const void *kdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff8135d350)
Location: kernel/bpf/bpf_struct_ops.c:746
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
```
**Symbols:**

```
ffffffff8135d350-ffffffff8135d36d: bpf_struct_ops_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_struct_ops_put(const void *kdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff813860a0)
Location: kernel/bpf/bpf_struct_ops.c:770
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
  - net/mptcp/sched.c:mptcp_release_sched
```
**Symbols:**

```
ffffffff813860a0-ffffffff813860bd: bpf_struct_ops_put (STB_GLOBAL)
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
