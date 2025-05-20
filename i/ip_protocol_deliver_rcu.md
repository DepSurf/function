# Function: <code>ip_protocol_deliver_rcu</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ip_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81915700)
Location: net/ipv4/ip_input.c:191
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
**Symbols:**

```
ffffffff81915700-ffffffff81915890: ip_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ip_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81977c40)
Location: net/ipv4/ip_input.c:187
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
**Symbols:**

```
ffffffff81977c40-ffffffff81977e07: ip_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ip_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff819ae5d0)
Location: net/ipv4/ip_input.c:187
Inline: False
```
**Symbols:**

```
ffffffff819ae5d0-ffffffff819ae777: ip_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ip_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81a98470)
Location: net/ipv4/ip_input.c:187
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
**Symbols:**

```
ffffffff81a98470-ffffffff81a98617: ip_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ip_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81aa23c0)
Location: net/ipv4/ip_input.c:187
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
**Symbols:**

```
ffffffff81aa23c0-ffffffff81aa2567: ip_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ip_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81a8d0c0)
Location: net/ipv4/ip_input.c:187
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
**Symbols:**

```
ffffffff81a8d0c0-ffffffff81a8d26d: ip_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ip_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81b48240)
Location: net/ipv4/ip_input.c:187
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
**Symbols:**

```
ffffffff81b48240-ffffffff81b4843b: ip_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ip_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81cd54e0)
Location: net/ipv4/ip_input.c:187
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
**Symbols:**

```
ffffffff81cd54e0-ffffffff81cd578b: ip_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ip_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81e959d0)
Location: net/ipv4/ip_input.c:187
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
**Symbols:**

```
ffffffff81e959d0-ffffffff81e95bda: ip_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ip_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81ef4210)
Location: net/ipv4/ip_input.c:187
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
**Symbols:**

```
ffffffff81ef4210-ffffffff81ef441a: ip_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ip_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81fb8190)
Location: net/ipv4/ip_input.c:187
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
**Symbols:**

```
ffffffff81fb8190-ffffffff81fb839a: ip_protocol_deliver_rcu (STB_GLOBAL)
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
void ip_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffff800010c5eab0)
Location: net/ipv4/ip_input.c:187
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
**Symbols:**

```
ffff800010c5eab0-ffff800010c5ecac: ip_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (c0d6e110)
Location: net/ipv4/ip_input.c:187
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
**Symbols:**

```
c0d6e110-c0d6e3f4: ip_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ip_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (c000000000d614c0)
Location: net/ipv4/ip_input.c:187
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
**Symbols:**

```
c000000000d614c0-c000000000d6176c: ip_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ip_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffe0007c70d8)
Location: net/ipv4/ip_input.c:187
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
**Symbols:**

```
ffffffe0007c70d8-ffffffe0007c728a: ip_protocol_deliver_rcu (STB_GLOBAL)
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
void ip_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff8194e440)
Location: net/ipv4/ip_input.c:187
Inline: False
```
**Symbols:**

```
ffffffff8194e440-ffffffff8194e5e7: ip_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ip_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81907f30)
Location: net/ipv4/ip_input.c:187
Inline: False
```
**Symbols:**

```
ffffffff81907f30-ffffffff819080d7: ip_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ip_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff819b8c10)
Location: net/ipv4/ip_input.c:187
Inline: False
```
**Symbols:**

```
ffffffff819b8c10-ffffffff819b8db7: ip_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ip_protocol_deliver_rcu(struct net *net, struct sk_buff *skb, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff819c2490)
Location: net/ipv4/ip_input.c:187
Inline: False
```
**Symbols:**

```
ffffffff819c2490-ffffffff819c2637: ip_protocol_deliver_rcu (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
