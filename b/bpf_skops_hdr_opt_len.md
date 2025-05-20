# Function: <code>bpf_skops_hdr_opt_len</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_skops_hdr_opt_len(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct sk_buff *syn_skb, enum tcp_synack_type synack_type, struct tcp_out_options *opts, unsigned int *remaining);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ac6890)
Location: net/ipv4/tcp_output.c:471
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
**Symbols:**

```
ffffffff81ac6890-ffffffff81ac69af: bpf_skops_hdr_opt_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_skops_hdr_opt_len(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct sk_buff *syn_skb, enum tcp_synack_type synack_type, struct tcp_out_options *opts, unsigned int *remaining);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab1aa0)
Location: net/ipv4/tcp_output.c:471
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
**Symbols:**

```
ffffffff81ab1aa0-ffffffff81ab1bbc: bpf_skops_hdr_opt_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_skops_hdr_opt_len(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct sk_buff *syn_skb, enum tcp_synack_type synack_type, struct tcp_out_options *opts, unsigned int *remaining);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81b6e5f0)
Location: net/ipv4/tcp_output.c:471
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
**Symbols:**

```
ffffffff81b6e5f0-ffffffff81b6e6fa: bpf_skops_hdr_opt_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_skops_hdr_opt_len(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct sk_buff *syn_skb, enum tcp_synack_type synack_type, struct tcp_out_options *opts, unsigned int *remaining);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81cfdba0)
Location: net/ipv4/tcp_output.c:469
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
**Symbols:**

```
ffffffff81cfdba0-ffffffff81cfdcd6: bpf_skops_hdr_opt_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_skops_hdr_opt_len(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct sk_buff *syn_skb, enum tcp_synack_type synack_type, struct tcp_out_options *opts, unsigned int *remaining);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ec2810)
Location: net/ipv4/tcp_output.c:469
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
**Symbols:**

```
ffffffff81ec2810-ffffffff81ec2946: bpf_skops_hdr_opt_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_skops_hdr_opt_len(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct sk_buff *syn_skb, enum tcp_synack_type synack_type, struct tcp_out_options *opts, unsigned int *remaining);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81f20d70)
Location: net/ipv4/tcp_output.c:471
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
**Symbols:**

```
ffffffff81f20d70-ffffffff81f20ea6: bpf_skops_hdr_opt_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_skops_hdr_opt_len(struct sock *sk, struct sk_buff *skb, struct request_sock *req, struct sk_buff *syn_skb, enum tcp_synack_type synack_type, struct tcp_out_options *opts, unsigned int *remaining);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81fe5470)
Location: net/ipv4/tcp_output.c:479
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
**Symbols:**

```
ffffffff81fe5470-ffffffff81fe55a6: bpf_skops_hdr_opt_len (STB_LOCAL)
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
