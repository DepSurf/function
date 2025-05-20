# Function: <code>bpf_output</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bpf_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff817da0b0)
Location: net/core/lwt_bpf.c:114
Inline: False
```
**Symbols:**

```
ffffffff817da0b0-ffffffff817da14f: bpf_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bpf_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff817f9070)
Location: net/core/lwt_bpf.c:114
Inline: False
```
**Symbols:**

```
ffffffff817f9070-ffffffff817f910f: bpf_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bpf_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81876970)
Location: net/core/lwt_bpf.c:114
Inline: False
```
**Symbols:**

```
ffffffff81876970-ffffffff81876a12: bpf_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int bpf_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (0)
Location: net/core/lwt_bpf.c:114
Inline: False
```
**Symbols:**

```
ffffffff818c8060-ffffffff818c80e7: bpf_output (STB_LOCAL)
ffffffff818c8511-ffffffff818c852d: bpf_output.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int bpf_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (0)
Location: net/core/lwt_bpf.c:113
Inline: False
```
**Symbols:**

```
ffffffff818f11d0-ffffffff818f1257: bpf_output (STB_LOCAL)
ffffffff818f1681-ffffffff818f169d: bpf_output.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int bpf_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (0)
Location: net/core/lwt_bpf.c:133
Inline: False
```
**Symbols:**

```
ffffffff81942c70-ffffffff81942cf7: bpf_output (STB_LOCAL)
ffffffff81943b1e-ffffffff81943b3a: bpf_output.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int bpf_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (0)
Location: net/core/lwt_bpf.c:138
Inline: False
```
**Symbols:**

```
ffffffff81977c20-ffffffff81977ca7: bpf_output (STB_LOCAL)
ffffffff81978b0f-ffffffff81978b2b: bpf_output.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int bpf_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (0)
Location: net/core/lwt_bpf.c:138
Inline: False
```
**Symbols:**

```
ffffffff81a4cac0-ffffffff81a4cb47: bpf_output (STB_LOCAL)
ffffffff81a4d89d-ffffffff81a4d8b9: bpf_output.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int bpf_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (0)
Location: net/core/lwt_bpf.c:138
Inline: False
```
**Symbols:**

```
ffffffff81a52780-ffffffff81a52807: bpf_output (STB_LOCAL)
ffffffff81c31ee3-ffffffff81c31eff: bpf_output.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int bpf_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (0)
Location: net/core/lwt_bpf.c:138
Inline: False
```
**Symbols:**

```
ffffffff81a37f50-ffffffff81a37fd7: bpf_output (STB_LOCAL)
ffffffff81c241c6-ffffffff81c241e2: bpf_output.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int bpf_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (0)
Location: net/core/lwt_bpf.c:138
Inline: False
```
**Symbols:**

```
ffffffff81aedd80-ffffffff81aede13: bpf_output (STB_LOCAL)
ffffffff81d3831c-ffffffff81d3834c: bpf_output.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int bpf_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (0)
Location: net/core/lwt_bpf.c:139
Inline: False
```
**Symbols:**

```
ffffffff81c70ba0-ffffffff81c70c47: bpf_output (STB_LOCAL)
ffffffff81f04ce9-ffffffff81f04d1a: bpf_output.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int bpf_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (0)
Location: net/core/lwt_bpf.c:139
Inline: False
```
**Symbols:**

```
ffffffff81e28c00-ffffffff81e28cbc: bpf_output (STB_LOCAL)
ffffffff820acd5a-ffffffff820acd6f: bpf_output.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bpf_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (0)
Location: net/core/lwt_bpf.c:138
Inline: False
```
**Symbols:**

```
ffffffff81e9e220-ffffffff81e9e2e2: bpf_output (STB_LOCAL)
ffffffff8212e48c-ffffffff8212e4a1: bpf_output.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bpf_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (0)
Location: net/core/lwt_bpf.c:138
Inline: False
```
**Symbols:**

```
ffffffff81f609a0-ffffffff81f60a62: bpf_output (STB_LOCAL)
ffffffff82210238-ffffffff8221024d: bpf_output.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int bpf_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffff800010c1eeb0)
Location: net/core/lwt_bpf.c:138
Inline: False
```
**Symbols:**

```
ffff800010c1eeb0-ffff800010c1ef74: bpf_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (c0d36470)
Location: net/core/lwt_bpf.c:138
Inline: False
```
**Symbols:**

```
c0d36470-c0d3652c: bpf_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (c000000000d0fea0)
Location: net/core/lwt_bpf.c:138
Inline: False
```
**Symbols:**

```
c000000000d0fea0-c000000000d0ffb8: bpf_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffe000797f3c)
Location: net/core/lwt_bpf.c:138
Inline: False
```
**Symbols:**

```
ffffffe000797f3c-ffffffe000797fe6: bpf_output (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int bpf_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (0)
Location: net/core/lwt_bpf.c:138
Inline: False
```
**Symbols:**

```
ffffffff81917a90-ffffffff81917b17: bpf_output (STB_LOCAL)
ffffffff8191897f-ffffffff8191899b: bpf_output.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int bpf_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (0)
Location: net/core/lwt_bpf.c:138
Inline: False
```
**Symbols:**

```
ffffffff818d1840-ffffffff818d18c7: bpf_output (STB_LOCAL)
ffffffff818d272f-ffffffff818d274b: bpf_output.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int bpf_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (0)
Location: net/core/lwt_bpf.c:138
Inline: False
```
**Symbols:**

```
ffffffff81968c20-ffffffff81968ca7: bpf_output (STB_LOCAL)
ffffffff81969b0f-ffffffff81969b2b: bpf_output.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int bpf_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (0)
Location: net/core/lwt_bpf.c:138
Inline: False
```
**Symbols:**

```
ffffffff8198b000-ffffffff8198b087: bpf_output (STB_LOCAL)
ffffffff8198beef-ffffffff8198bf0b: bpf_output.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
