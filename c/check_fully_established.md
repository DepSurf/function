# Function: <code>check_fully_established</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bb122f)
Location: net/mptcp/options.c:677
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool check_fully_established(struct mptcp_sock *msk, struct sock *ssk, struct mptcp_subflow_context *subflow, struct sk_buff *skb, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/options.c (0)
Location: net/mptcp/options.c:760
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81bc4520-ffffffff81bc471e: check_fully_established (STB_LOCAL)
ffffffff81c33f44-ffffffff81c33f64: check_fully_established.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool check_fully_established(struct mptcp_sock *msk, struct sock *ssk, struct mptcp_subflow_context *subflow, struct sk_buff *skb, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/options.c (0)
Location: net/mptcp/options.c:814
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81bb4c10-ffffffff81bb4dff: check_fully_established (STB_LOCAL)
ffffffff81c2628b-ffffffff81c262ab: check_fully_established.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool check_fully_established(struct mptcp_sock *msk, struct sock *ssk, struct mptcp_subflow_context *subflow, struct sk_buff *skb, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/options.c (0)
Location: net/mptcp/options.c:893
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81c83600-ffffffff81c83839: check_fully_established (STB_LOCAL)
ffffffff81d43c88-ffffffff81d43cf7: check_fully_established.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool check_fully_established(struct mptcp_sock *msk, struct sock *ssk, struct mptcp_subflow_context *subflow, struct sk_buff *skb, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/options.c (0)
Location: net/mptcp/options.c:919
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81e29500-ffffffff81e29780: check_fully_established (STB_LOCAL)
ffffffff81f107bb-ffffffff81f10829: check_fully_established.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool check_fully_established(struct mptcp_sock *msk, struct sock *ssk, struct mptcp_subflow_context *subflow, struct sk_buff *skb, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/options.c (0)
Location: net/mptcp/options.c:924
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff82001560-ffffffff82001838: check_fully_established (STB_LOCAL)
ffffffff820b6b4a-ffffffff820b6b98: check_fully_established.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool check_fully_established(struct mptcp_sock *msk, struct sock *ssk, struct mptcp_subflow_context *subflow, struct sk_buff *skb, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/options.c (0)
Location: net/mptcp/options.c:924
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff8207d730-ffffffff8207d9e1: check_fully_established (STB_LOCAL)
ffffffff82137eec-ffffffff82137f3a: check_fully_established.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool check_fully_established(struct mptcp_sock *msk, struct sock *ssk, struct mptcp_subflow_context *subflow, struct sk_buff *skb, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/options.c (0)
Location: net/mptcp/options.c:925
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff82153050-ffffffff82153306: check_fully_established (STB_LOCAL)
ffffffff82219d86-ffffffff82219dd4: check_fully_established.cold (STB_LOCAL)
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
