# Function: <code>mptcp_established_options</code>

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
bool mptcp_established_options(struct sock *sk, struct sk_buff *skb, unsigned int *size, unsigned int remaining, struct mptcp_out_options *opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bb1010)
Location: net/mptcp/options.c:618
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_established_options
```
**Symbols:**

```
ffffffff81bb1010-ffffffff81bb10da: mptcp_established_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool mptcp_established_options(struct sock *sk, struct sk_buff *skb, unsigned int *size, unsigned int remaining, struct mptcp_out_options *opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bc4d70)
Location: net/mptcp/options.c:685
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_established_options
```
**Symbols:**

```
ffffffff81bc4d70-ffffffff81bc4f38: mptcp_established_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool mptcp_established_options(struct sock *sk, struct sk_buff *skb, unsigned int *size, unsigned int remaining, struct mptcp_out_options *opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bb53f0)
Location: net/mptcp/options.c:734
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_established_options
```
**Symbols:**

```
ffffffff81bb53f0-ffffffff81bb5684: mptcp_established_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool mptcp_established_options(struct sock *sk, struct sk_buff *skb, unsigned int *size, unsigned int remaining, struct mptcp_out_options *opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/options.c (0)
Location: net/mptcp/options.c:795
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_established_options
```
**Symbols:**

```
ffffffff81d43dfe-ffffffff81d43e21: mptcp_established_options.cold (STB_LOCAL)
ffffffff81c84000-ffffffff81c84370: mptcp_established_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool mptcp_established_options(struct sock *sk, struct sk_buff *skb, unsigned int *size, unsigned int remaining, struct mptcp_out_options *opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/options.c (0)
Location: net/mptcp/options.c:819
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_established_options
```
**Symbols:**

```
ffffffff81f10930-ffffffff81f10953: mptcp_established_options.cold (STB_LOCAL)
ffffffff81e2a1b0-ffffffff81e2a5c9: mptcp_established_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool mptcp_established_options(struct sock *sk, struct sk_buff *skb, unsigned int *size, unsigned int remaining, struct mptcp_out_options *opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/options.c (0)
Location: net/mptcp/options.c:824
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_established_options
```
**Symbols:**

```
ffffffff820b6c9f-ffffffff820b6cc2: mptcp_established_options.cold (STB_LOCAL)
ffffffff820022f0-ffffffff82002709: mptcp_established_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool mptcp_established_options(struct sock *sk, struct sk_buff *skb, unsigned int *size, unsigned int remaining, struct mptcp_out_options *opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/options.c (0)
Location: net/mptcp/options.c:824
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_established_options
```
**Symbols:**

```
ffffffff82138041-ffffffff82138064: mptcp_established_options.cold (STB_LOCAL)
ffffffff8207e4b0-ffffffff8207e8ef: mptcp_established_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool mptcp_established_options(struct sock *sk, struct sk_buff *skb, unsigned int *size, unsigned int remaining, struct mptcp_out_options *opts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/options.c (0)
Location: net/mptcp/options.c:825
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_established_options
```
**Symbols:**

```
ffffffff82219e57-ffffffff82219e7a: mptcp_established_options.cold (STB_LOCAL)
ffffffff821539a0-ffffffff82153ddf: mptcp_established_options (STB_GLOBAL)
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
