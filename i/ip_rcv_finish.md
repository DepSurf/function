# Function: <code>ip_rcv_finish</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ip_rcv_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81758720)
Location: net/ipv4/ip_input.c:314
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff81758720-ffffffff81758a3d: ip_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ip_rcv_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff817c4a00)
Location: net/ipv4/ip_input.c:311
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff817c4a00-ffffffff817c4def: ip_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ip_rcv_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff817f4520)
Location: net/ipv4/ip_input.c:311
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff817f4520-ffffffff817f490f: ip_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ip_rcv_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81814950)
Location: net/ipv4/ip_input.c:311
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff81814950-ffffffff81814d53: ip_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ip_rcv_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81893af0)
Location: net/ipv4/ip_input.c:311
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff81893af0-ffffffff81893f13: ip_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ip_rcv_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (0)
Location: net/ipv4/ip_input.c:310
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff818e7da0-ffffffff818e819f: ip_rcv_finish (STB_LOCAL)
ffffffff818e88f3-ffffffff818e890c: ip_rcv_finish.cold.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip_rcv_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81915040)
Location: net/ipv4/ip_input.c:400
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff81915040-ffffffff819150d5: ip_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip_rcv_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81977550)
Location: net/ipv4/ip_input.c:399
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff81977550-ffffffff819775e7: ip_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip_rcv_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff819adee0)
Location: net/ipv4/ip_input.c:399
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff819adee0-ffffffff819adf77: ip_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip_rcv_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81a97d80)
Location: net/ipv4/ip_input.c:414
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff81a97d80-ffffffff81a97e19: ip_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip_rcv_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81aa1ce0)
Location: net/ipv4/ip_input.c:414
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff81aa1ce0-ffffffff81aa1d79: ip_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ip_rcv_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81a8d7c7)
Location: net/ipv4/ip_input.c:415
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff81a8d640-ffffffff81a8d6ff: ip_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ip_rcv_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81b48992)
Location: net/ipv4/ip_input.c:415
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff81b48810-ffffffff81b488cf: ip_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ip_rcv_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81cd5da0)
Location: net/ipv4/ip_input.c:430
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff81cd5bf0-ffffffff81cd5cca: ip_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ip_rcv_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81e96250)
Location: net/ipv4/ip_input.c:435
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff81e96090-ffffffff81e9616a: ip_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ip_rcv_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81ef4a8e)
Location: net/ipv4/ip_input.c:435
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff81ef48d0-ffffffff81ef49aa: ip_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ip_rcv_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81fb8996)
Location: net/ipv4/ip_input.c:435
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff81fb8860-ffffffff81fb8937: ip_rcv_finish (STB_LOCAL)
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
int ip_rcv_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffff800010c5e660)
Location: net/ipv4/ip_input.c:399
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffff800010c5e660-ffff800010c5e70c: ip_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip_rcv_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (c0d6d7b8)
Location: net/ipv4/ip_input.c:399
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
c0d6d7b8-c0d6d86c: ip_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip_rcv_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (c000000000d60ad0)
Location: net/ipv4/ip_input.c:399
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
c000000000d60ad0-c000000000d60bc0: ip_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip_rcv_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffe0007c6ad2)
Location: net/ipv4/ip_input.c:399
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffe0007c6ad2-ffffffe0007c6b56: ip_rcv_finish (STB_LOCAL)
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
int ip_rcv_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff8194dd50)
Location: net/ipv4/ip_input.c:399
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff8194dd50-ffffffff8194dde7: ip_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip_rcv_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81907840)
Location: net/ipv4/ip_input.c:399
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff81907840-ffffffff819078d7: ip_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip_rcv_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff819b8520)
Location: net/ipv4/ip_input.c:399
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff819b8520-ffffffff819b85b7: ip_rcv_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip_rcv_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff819c1d80)
Location: net/ipv4/ip_input.c:399
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_rcv
  - net/ipv4/ip_input.c:ip_rcv
```
**Symbols:**

```
ffffffff819c1d80-ffffffff819c1e17: ip_rcv_finish (STB_LOCAL)
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
