# Function: <code>mptcp_established_options_add_addr</code>

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
bool mptcp_established_options_add_addr(struct sock *sk, struct sk_buff *skb, unsigned int *size, unsigned int remaining, struct mptcp_out_options *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bc42b0)
Location: net/mptcp/options.c:591
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff81bc42b0-ffffffff81bc451e: mptcp_established_options_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool mptcp_established_options_add_addr(struct sock *sk, struct sk_buff *skb, unsigned int *size, unsigned int remaining, struct mptcp_out_options *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bb4a30)
Location: net/mptcp/options.c:617
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff81bb4a30-ffffffff81bb4c0e: mptcp_established_options_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool mptcp_established_options_add_addr(struct sock *sk, struct sk_buff *skb, unsigned int *size, unsigned int remaining, struct mptcp_out_options *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/options.c (0)
Location: net/mptcp/options.c:644
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff81c833b0-ffffffff81c83593: mptcp_established_options_add_addr (STB_LOCAL)
ffffffff81d43ba5-ffffffff81d43c88: mptcp_established_options_add_addr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool mptcp_established_options_add_addr(struct sock *sk, struct sk_buff *skb, unsigned int *size, unsigned int remaining, struct mptcp_out_options *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/options.c (0)
Location: net/mptcp/options.c:646
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff81e29310-ffffffff81e294f4: mptcp_established_options_add_addr (STB_LOCAL)
ffffffff81f10723-ffffffff81f107bb: mptcp_established_options_add_addr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool mptcp_established_options_add_addr(struct sock *sk, struct sk_buff *skb, unsigned int *size, unsigned int remaining, struct mptcp_out_options *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/options.c (0)
Location: net/mptcp/options.c:651
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff82001360-ffffffff82001544: mptcp_established_options_add_addr (STB_LOCAL)
ffffffff820b6ab2-ffffffff820b6b4a: mptcp_established_options_add_addr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool mptcp_established_options_add_addr(struct sock *sk, struct sk_buff *skb, unsigned int *size, unsigned int remaining, struct mptcp_out_options *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/options.c (0)
Location: net/mptcp/options.c:648
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff8207d4f0-ffffffff8207d71e: mptcp_established_options_add_addr (STB_LOCAL)
ffffffff82137e1f-ffffffff82137eec: mptcp_established_options_add_addr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool mptcp_established_options_add_addr(struct sock *sk, struct sk_buff *skb, unsigned int *size, unsigned int remaining, struct mptcp_out_options *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/options.c (0)
Location: net/mptcp/options.c:649
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff821529e0-ffffffff82152c0e: mptcp_established_options_add_addr (STB_LOCAL)
ffffffff82219c94-ffffffff82219d61: mptcp_established_options_add_addr.cold (STB_LOCAL)
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
