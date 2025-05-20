# Function: <code>__ip6_finish_output</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a04280)
Location: net/ipv6/ip6_output.c:127
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff81a04280-ffffffff81a0438f: __ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a3ae70)
Location: net/ipv6/ip6_output.c:127
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff81a3ae70-ffffffff81a3af7f: __ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b30430)
Location: net/ipv6/ip6_output.c:128
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff81b30430-ffffffff81b3053f: __ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b3f14f)
Location: net/ipv6/ip6_output.c:161
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff81b3efa0-ffffffff81b3f0fc: __ip6_finish_output.part.0 (STB_LOCAL)
ffffffff81b3f100-ffffffff81b3f12f: __ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b2bcb0)
Location: net/ipv6/ip6_output.c:189
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff81b2bcb0-ffffffff81b2bf45: __ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81bf1e6c)
Location: net/ipv6/ip6_output.c:170
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff81bf1e10-ffffffff81bf20b1: __ip6_finish_output (STB_LOCAL)
ffffffff81d3f4bb-ffffffff81d3f4e4: __ip6_finish_output.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81d8a8a4)
Location: net/ipv6/ip6_output.c:172
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81f58854)
Location: net/ipv6/ip6_output.c:172
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81fb8517)
Location: net/ipv6/ip6_output.c:173
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff82085b07)
Location: net/ipv6/ip6_output.c:191
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffff800010cfbf08)
Location: net/ipv6/ip6_output.c:127
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffff800010cfbf08-ffff800010cfc07c: __ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c0e0328c)
Location: net/ipv6/ip6_output.c:127
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
c0e0328c-c0e033e4: __ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c000000000e23870)
Location: net/ipv6/ip6_output.c:127
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
c000000000e23870-c000000000e23a5c: __ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffe00084688e)
Location: net/ipv6/ip6_output.c:127
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffe00084688e-ffffffe0008469ba: __ip6_finish_output (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int __ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff819da500)
Location: net/ipv6/ip6_output.c:127
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff819da500-ffffffff819da60f: __ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff819972c0)
Location: net/ipv6/ip6_output.c:127
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff819972c0-ffffffff819973cf: __ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a44f80)
Location: net/ipv6/ip6_output.c:127
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff81a44f80-ffffffff81a4508f: __ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a50c40)
Location: net/ipv6/ip6_output.c:127
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff81a50c40-ffffffff81a50d4f: __ip6_finish_output (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
