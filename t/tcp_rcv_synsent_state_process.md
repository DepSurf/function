# Function: <code>tcp_rcv_synsent_state_process</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8177365f)
Location: net/ipv4/tcp_input.c:5517
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817e04dd)
Location: net/ipv4/tcp_input.c:5582
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818108c3)
Location: net/ipv4/tcp_input.c:5668
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818308a4)
Location: net/ipv4/tcp_input.c:5656
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818afd30)
Location: net/ipv4/tcp_input.c:5562
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8190548b)
Location: net/ipv4/tcp_input.c:5723
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81933631)
Location: net/ipv4/tcp_input.c:5772
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcp_rcv_synsent_state_process(struct sock *sk, struct sk_buff *skb, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81996fa0)
Location: net/ipv4/tcp_input.c:5818
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffffffff81996fa0-ffffffff819977df: tcp_rcv_synsent_state_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_rcv_synsent_state_process(struct sock *sk, struct sk_buff *skb, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819cdb20)
Location: net/ipv4/tcp_input.c:5869
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffffffff819cdb20-ffffffff819ce367: tcp_rcv_synsent_state_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_rcv_synsent_state_process(struct sock *sk, struct sk_buff *skb, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab9cf0)
Location: net/ipv4/tcp_input.c:5915
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffffffff81ab9cf0-ffffffff81aba42b: tcp_rcv_synsent_state_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_rcv_synsent_state_process(struct sock *sk, struct sk_buff *skb, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ac5130)
Location: net/ipv4/tcp_input.c:6051
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffffffff81ac5130-ffffffff81ac586c: tcp_rcv_synsent_state_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_rcv_synsent_state_process(struct sock *sk, struct sk_buff *skb, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab0360)
Location: net/ipv4/tcp_input.c:6057
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffffffff81ab0360-ffffffff81ab0a78: tcp_rcv_synsent_state_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tcp_rcv_synsent_state_process(struct sock *sk, struct sk_buff *skb, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:6092
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffffffff81b6d190-ffffffff81b6d8b9: tcp_rcv_synsent_state_process (STB_LOCAL)
ffffffff81d3ad6b-ffffffff81d3ad7f: tcp_rcv_synsent_state_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tcp_rcv_synsent_state_process(struct sock *sk, struct sk_buff *skb, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:6158
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffffffff81cfc640-ffffffff81cfcd15: tcp_rcv_synsent_state_process (STB_LOCAL)
ffffffff81f07619-ffffffff81f0762e: tcp_rcv_synsent_state_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tcp_rcv_synsent_state_process(struct sock *sk, struct sk_buff *skb, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:6180
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffffffff81ec11f0-ffffffff81ec18c1: tcp_rcv_synsent_state_process (STB_LOCAL)
ffffffff820af091-ffffffff820af0a6: tcp_rcv_synsent_state_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tcp_rcv_synsent_state_process(struct sock *sk, struct sk_buff *skb, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:6187
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffffffff81f1f750-ffffffff81f1fe22: tcp_rcv_synsent_state_process (STB_LOCAL)
ffffffff82130480-ffffffff82130495: tcp_rcv_synsent_state_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tcp_rcv_synsent_state_process(struct sock *sk, struct sk_buff *skb, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:6334
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffffffff81fe3e10-ffffffff81fe450b: tcp_rcv_synsent_state_process (STB_LOCAL)
ffffffff82211e66-ffffffff82211e7b: tcp_rcv_synsent_state_process.cold (STB_LOCAL)
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
int tcp_rcv_synsent_state_process(struct sock *sk, struct sk_buff *skb, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c806a8)
Location: net/ipv4/tcp_input.c:5869
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffff800010c806a8-ffff800010c80da4: tcp_rcv_synsent_state_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_rcv_synsent_state_process(struct sock *sk, struct sk_buff *skb, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d8f858)
Location: net/ipv4/tcp_input.c:5869
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
c0d8f858-c0d90004: tcp_rcv_synsent_state_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_rcv_synsent_state_process(struct sock *sk, struct sk_buff *skb, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d8b300)
Location: net/ipv4/tcp_input.c:5869
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
c000000000d8b300-c000000000d8bc00: tcp_rcv_synsent_state_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_rcv_synsent_state_process(struct sock *sk, struct sk_buff *skb, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007e2656)
Location: net/ipv4/tcp_input.c:5869
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffffffe0007e2656-ffffffe0007e2d1e: tcp_rcv_synsent_state_process (STB_LOCAL)
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
int tcp_rcv_synsent_state_process(struct sock *sk, struct sk_buff *skb, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8196d990)
Location: net/ipv4/tcp_input.c:5869
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffffffff8196d990-ffffffff8196e1d7: tcp_rcv_synsent_state_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_rcv_synsent_state_process(struct sock *sk, struct sk_buff *skb, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81927480)
Location: net/ipv4/tcp_input.c:5869
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffffffff81927480-ffffffff81927cc7: tcp_rcv_synsent_state_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_rcv_synsent_state_process(struct sock *sk, struct sk_buff *skb, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d8160)
Location: net/ipv4/tcp_input.c:5869
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffffffff819d8160-ffffffff819d89a7: tcp_rcv_synsent_state_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_rcv_synsent_state_process(struct sock *sk, struct sk_buff *skb, const struct tcphdr *th);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819e1da0)
Location: net/ipv4/tcp_input.c:5869
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffffffff819e1da0-ffffffff819e25fe: tcp_rcv_synsent_state_process (STB_LOCAL)
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
