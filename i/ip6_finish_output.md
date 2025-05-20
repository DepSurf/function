# Function: <code>ip6_finish_output</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff817c7b10)
Location: net/ipv6/ip6_output.c:124
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_output
```
**Symbols:**

```
ffffffff817c7b10-ffffffff817c7c10: ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81834c40)
Location: net/ipv6/ip6_output.c:124
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_output
```
**Symbols:**

```
ffffffff81834c40-ffffffff81834d40: ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff818666d0)
Location: net/ipv6/ip6_output.c:133
Inline: True
Direct callers:
  - net/ipv6/ip6_output.c:ip6_output
```
**Symbols:**

```
ffffffff818666d0-ffffffff81866882: ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff8188ae10)
Location: net/ipv6/ip6_output.c:131
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_output
```
**Symbols:**

```
ffffffff8188ae10-ffffffff8188af9f: ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff8190c010)
Location: net/ipv6/ip6_output.c:131
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_output
```
**Symbols:**

```
ffffffff8190c010-ffffffff8190c1b4: ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81963490)
Location: net/ipv6/ip6_output.c:131
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_output
```
**Symbols:**

```
ffffffff81963490-ffffffff8196363d: ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81998450)
Location: net/ipv6/ip6_output.c:131
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_output
```
**Symbols:**

```
ffffffff81998450-ffffffff819985f4: ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a04390)
Location: net/ipv6/ip6_output.c:145
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_output
```
**Symbols:**

```
ffffffff81a04390-ffffffff81a04432: ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a3af80)
Location: net/ipv6/ip6_output.c:145
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_output
```
**Symbols:**

```
ffffffff81a3af80-ffffffff81a3b022: ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b30540)
Location: net/ipv6/ip6_output.c:146
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_output
```
**Symbols:**

```
ffffffff81b30540-ffffffff81b305e2: ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b3f130)
Location: net/ipv6/ip6_output.c:185
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_output
```
**Symbols:**

```
ffffffff81b3f130-ffffffff81b3f20e: ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b2bf50)
Location: net/ipv6/ip6_output.c:213
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_output
```
**Symbols:**

```
ffffffff81b2bf50-ffffffff81b2bfea: ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:194
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_output
```
**Symbols:**

```
ffffffff81bf20c0-ffffffff81bf2174: ip6_finish_output (STB_LOCAL)
ffffffff81d3f4e4-ffffffff81d3f504: ip6_finish_output.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:198
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_output
```
**Symbols:**

```
ffffffff81d8a880-ffffffff81d8abbd: ip6_finish_output (STB_LOCAL)
ffffffff81f0be80-ffffffff81f0bec8: ip6_finish_output.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:198
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_output
```
**Symbols:**

```
ffffffff81f58830-ffffffff81f58b71: ip6_finish_output (STB_LOCAL)
ffffffff820b36b5-ffffffff820b36fd: ip6_finish_output.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:199
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_output
```
**Symbols:**

```
ffffffff81fb84f0-ffffffff81fb8844: ip6_finish_output (STB_LOCAL)
ffffffff821347ff-ffffffff82134839: ip6_finish_output.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:214
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_output
```
**Symbols:**

```
ffffffff82085ae0-ffffffff82085e26: ip6_finish_output (STB_LOCAL)
ffffffff82216385-ffffffff822163bf: ip6_finish_output.cold (STB_LOCAL)
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
int ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffff800010cfc080)
Location: net/ipv6/ip6_output.c:145
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_output
```
**Symbols:**

```
ffff800010cfc080-ffff800010cfc150: ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c0e033e4)
Location: net/ipv6/ip6_output.c:145
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_output
```
**Symbols:**

```
c0e033e4-c0e034a8: ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c000000000e23a60)
Location: net/ipv6/ip6_output.c:145
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_output
```
**Symbols:**

```
c000000000e23a60-c000000000e23b80: ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffe0008469ba)
Location: net/ipv6/ip6_output.c:145
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_output
```
**Symbols:**

```
ffffffe0008469ba-ffffffe000846a70: ip6_finish_output (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff819da610)
Location: net/ipv6/ip6_output.c:145
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_output
```
**Symbols:**

```
ffffffff819da610-ffffffff819da6b2: ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff819973d0)
Location: net/ipv6/ip6_output.c:145
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_output
```
**Symbols:**

```
ffffffff819973d0-ffffffff81997472: ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a45090)
Location: net/ipv6/ip6_output.c:145
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_output
```
**Symbols:**

```
ffffffff81a45090-ffffffff81a45132: ip6_finish_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip6_finish_output(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a50d50)
Location: net/ipv6/ip6_output.c:145
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_output
```
**Symbols:**

```
ffffffff81a50d50-ffffffff81a50df2: ip6_finish_output (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
