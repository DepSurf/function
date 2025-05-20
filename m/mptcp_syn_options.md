# Function: <code>mptcp_syn_options</code>

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
bool mptcp_syn_options(struct sock *sk, const struct sk_buff *skb, unsigned int *size, struct mptcp_out_options *opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bb0f40)
Location: net/mptcp/options.c:329
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_syn_options
```
**Symbols:**

```
ffffffff81bb0f40-ffffffff81bb1010: mptcp_syn_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool mptcp_syn_options(struct sock *sk, const struct sk_buff *skb, unsigned int *size, struct mptcp_out_options *opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bc4ca0)
Location: net/mptcp/options.c:344
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_syn_options
```
**Symbols:**

```
ffffffff81bc4ca0-ffffffff81bc4d6d: mptcp_syn_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool mptcp_syn_options(struct sock *sk, const struct sk_buff *skb, unsigned int *size, struct mptcp_out_options *opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bb5320)
Location: net/mptcp/options.c:375
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_syn_options
```
**Symbols:**

```
ffffffff81bb5320-ffffffff81bb53ed: mptcp_syn_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool mptcp_syn_options(struct sock *sk, const struct sk_buff *skb, unsigned int *size, struct mptcp_out_options *opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81c83ef0)
Location: net/mptcp/options.c:396
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_syn_options
```
**Symbols:**

```
ffffffff81c83ef0-ffffffff81c83ffc: mptcp_syn_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool mptcp_syn_options(struct sock *sk, const struct sk_buff *skb, unsigned int *size, struct mptcp_out_options *opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81e2a0a0)
Location: net/mptcp/options.c:398
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_syn_options
```
**Symbols:**

```
ffffffff81e2a0a0-ffffffff81e2a1af: mptcp_syn_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool mptcp_syn_options(struct sock *sk, const struct sk_buff *skb, unsigned int *size, struct mptcp_out_options *opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff820021d0)
Location: net/mptcp/options.c:403
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_syn_options
```
**Symbols:**

```
ffffffff820021d0-ffffffff820022df: mptcp_syn_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool mptcp_syn_options(struct sock *sk, const struct sk_buff *skb, unsigned int *size, struct mptcp_out_options *opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff8207e390)
Location: net/mptcp/options.c:403
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_syn_options
```
**Symbols:**

```
ffffffff8207e390-ffffffff8207e4a0: mptcp_syn_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool mptcp_syn_options(struct sock *sk, const struct sk_buff *skb, unsigned int *size, struct mptcp_out_options *opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff82153880)
Location: net/mptcp/options.c:404
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_syn_options
```
**Symbols:**

```
ffffffff82153880-ffffffff82153990: mptcp_syn_options (STB_GLOBAL)
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
