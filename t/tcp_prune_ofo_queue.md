# Function: <code>tcp_prune_ofo_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool tcp_prune_ofo_queue(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176c4c0)
Location: net/ipv4/tcp_input.c:4816
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
**Symbols:**

```
ffffffff8176c4c0-ffffffff8176c59e: tcp_prune_ofo_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool tcp_prune_ofo_queue(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817d9a80)
Location: net/ipv4/tcp_input.c:4879
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
**Symbols:**

```
ffffffff817d9a80-ffffffff817d9b5a: tcp_prune_ofo_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool tcp_prune_ofo_queue(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8180a450)
Location: net/ipv4/tcp_input.c:4951
Inline: False
```
**Symbols:**

```
ffffffff8180a450-ffffffff8180a583: tcp_prune_ofo_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8182b310)
Location: net/ipv4/tcp_input.c:4911
Inline: True
```
**Symbols:**

```
ffffffff8182b310-ffffffff8182b42b: tcp_prune_ofo_queue.part.46 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818a99e0)
Location: net/ipv4/tcp_input.c:4863
Inline: True
```
**Symbols:**

```
ffffffff818a99e0-ffffffff818a9afb: tcp_prune_ofo_queue.part.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818ff580)
Location: net/ipv4/tcp_input.c:4984
Inline: True
```
**Symbols:**

```
ffffffff818ff580-ffffffff818ff6ca: tcp_prune_ofo_queue.part.52 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192d030)
Location: net/ipv4/tcp_input.c:5015
Inline: True
```
**Symbols:**

```
ffffffff8192d030-ffffffff8192d17a: tcp_prune_ofo_queue.part.60 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81990430)
Location: net/ipv4/tcp_input.c:5022
Inline: True
```
**Symbols:**

```
ffffffff81990430-ffffffff8199057b: tcp_prune_ofo_queue.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c71b0)
Location: net/ipv4/tcp_input.c:5073
Inline: True
```
**Symbols:**

```
ffffffff819c71b0-ffffffff819c72fd: tcp_prune_ofo_queue.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tcp_prune_ofo_queue(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab2470)
Location: net/ipv4/tcp_input.c:5116
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_prune_queue
```
**Symbols:**

```
ffffffff81ab2470-ffffffff81ab2616: tcp_prune_ofo_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tcp_prune_ofo_queue(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abd430)
Location: net/ipv4/tcp_input.c:5255
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_prune_queue
```
**Symbols:**

```
ffffffff81abd430-ffffffff81abd5cd: tcp_prune_ofo_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tcp_prune_ofo_queue(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa8410)
Location: net/ipv4/tcp_input.c:5263
Inline: False
```
**Symbols:**

```
ffffffff81aa8410-ffffffff81aa85a3: tcp_prune_ofo_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool tcp_prune_ofo_queue(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b64680)
Location: net/ipv4/tcp_input.c:5297
Inline: False
```
**Symbols:**

```
ffffffff81b64680-ffffffff81b6480d: tcp_prune_ofo_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool tcp_prune_ofo_queue(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf3460)
Location: net/ipv4/tcp_input.c:5327
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
**Symbols:**

```
ffffffff81cf3460-ffffffff81cf363f: tcp_prune_ofo_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool tcp_prune_ofo_queue(struct sock *sk, const struct sk_buff *in_skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb7ab0)
Location: net/ipv4/tcp_input.c:5342
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
**Symbols:**

```
ffffffff81eb7ab0-ffffffff81eb7c65: tcp_prune_ofo_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool tcp_prune_ofo_queue(struct sock *sk, const struct sk_buff *in_skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f158e0)
Location: net/ipv4/tcp_input.c:5347
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
**Symbols:**

```
ffffffff81f158e0-ffffffff81f15a95: tcp_prune_ofo_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool tcp_prune_ofo_queue(struct sock *sk, const struct sk_buff *in_skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fda560)
Location: net/ipv4/tcp_input.c:5485
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
**Symbols:**

```
ffffffff81fda560-ffffffff81fda715: tcp_prune_ofo_queue (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c787e0)
Location: net/ipv4/tcp_input.c:5073
Inline: True
```
**Symbols:**

```
ffff800010c787e0-ffff800010c78950: tcp_prune_ofo_queue.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (c0d874e0)
Location: net/ipv4/tcp_input.c:5073
Inline: True
```
**Symbols:**

```
c0d874e0-c0d87684: tcp_prune_ofo_queue.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d831e0)
Location: net/ipv4/tcp_input.c:5073
Inline: True
```
**Symbols:**

```
c000000000d831e0-c000000000d8340c: tcp_prune_ofo_queue.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007dcf7e)
Location: net/ipv4/tcp_input.c:5073
Inline: True
```
**Symbols:**

```
ffffffe0007dcf7e-ffffffe0007dd110: tcp_prune_ofo_queue.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81967020)
Location: net/ipv4/tcp_input.c:5073
Inline: True
```
**Symbols:**

```
ffffffff81967020-ffffffff8196716d: tcp_prune_ofo_queue.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81920b10)
Location: net/ipv4/tcp_input.c:5073
Inline: True
```
**Symbols:**

```
ffffffff81920b10-ffffffff81920c5d: tcp_prune_ofo_queue.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d17f0)
Location: net/ipv4/tcp_input.c:5073
Inline: True
```
**Symbols:**

```
ffffffff819d17f0-ffffffff819d193d: tcp_prune_ofo_queue.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819db380)
Location: net/ipv4/tcp_input.c:5073
Inline: True
```
**Symbols:**

```
ffffffff819db380-ffffffff819db4cd: tcp_prune_ofo_queue.part.0 (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct sk_buff *in_skb</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
