# Function: <code>mptcp_get_options</code>

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
void mptcp_get_options(const struct sk_buff *skb, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bb0ea0)
Location: net/mptcp/options.c:288
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_init_req
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81bb0ea0-ffffffff81bb0f3f: mptcp_get_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mptcp_get_options(const struct sk_buff *skb, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bc4bf0)
Location: net/mptcp/options.c:300
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:mptcp_subflow_init_cookie_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81bc4bf0-ffffffff81bc4c9d: mptcp_get_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mptcp_get_options(const struct sock *sk, const struct sk_buff *skb, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bb5260)
Location: net/mptcp/options.c:326
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:mptcp_subflow_init_cookie_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81bb5260-ffffffff81bb5312: mptcp_get_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mptcp_get_options(const struct sock *sk, const struct sk_buff *skb, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81c83e40)
Location: net/mptcp/options.c:356
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:mptcp_subflow_init_cookie_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81c83e40-ffffffff81c83ee6: mptcp_get_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mptcp_get_options(const struct sk_buff *skb, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81e29fe0)
Location: net/mptcp/options.c:359
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:mptcp_subflow_init_cookie_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81e29fe0-ffffffff81e2a09a: mptcp_get_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mptcp_get_options(const struct sk_buff *skb, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff82002100)
Location: net/mptcp/options.c:364
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:mptcp_subflow_init_cookie_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff82002100-ffffffff820021ba: mptcp_get_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mptcp_get_options(const struct sk_buff *skb, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff8207e2c0)
Location: net/mptcp/options.c:364
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:mptcp_subflow_init_cookie_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff8207e2c0-ffffffff8207e37a: mptcp_get_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_get_options(const struct sk_buff *skb, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff821537b0)
Location: net/mptcp/options.c:365
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:mptcp_subflow_init_cookie_req
  - net/mptcp/subflow.c:subflow_check_req
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff821537b0-ffffffff8215386a: mptcp_get_options (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct sock *sk</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, mp_opt</code> ➡️ <code>sk, skb, mp_opt</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct sock *sk</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, skb, mp_opt</code> ➡️ <code>skb, mp_opt</code>
</li>
</ul>
</details>
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
