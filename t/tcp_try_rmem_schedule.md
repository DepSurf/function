# Function: <code>tcp_try_rmem_schedule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tcp_try_rmem_schedule(struct sock *sk, struct sk_buff *skb, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176e830)
Location: net/ipv4/tcp_input.c:4321
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff8176e830-ffffffff8176ec49: tcp_try_rmem_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tcp_try_rmem_schedule(struct sock *sk, struct sk_buff *skb, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817da800)
Location: net/ipv4/tcp_input.c:4385
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff817da800-ffffffff817dac41: tcp_try_rmem_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int tcp_try_rmem_schedule(struct sock *sk, struct sk_buff *skb, unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8180b400)
Location: net/ipv4/tcp_input.c:4412
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff8180b400-ffffffff8180b7d9: tcp_try_rmem_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int tcp_try_rmem_schedule(struct sock *sk, struct sk_buff *skb, unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8182bc70)
Location: net/ipv4/tcp_input.c:4371
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff8182bc70-ffffffff8182c081: tcp_try_rmem_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int tcp_try_rmem_schedule(struct sock *sk, struct sk_buff *skb, unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818ae440)
Location: net/ipv4/tcp_input.c:4348
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff818ae440-ffffffff818ae860: tcp_try_rmem_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tcp_try_rmem_schedule(struct sock *sk, struct sk_buff *skb, unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:4448
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff81903af0-ffffffff81903f1f: tcp_try_rmem_schedule (STB_LOCAL)
ffffffff819061e0-ffffffff819061f7: tcp_try_rmem_schedule.cold.82 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tcp_try_rmem_schedule(struct sock *sk, struct sk_buff *skb, unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:4465
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
```
**Symbols:**

```
ffffffff81931cc0-ffffffff819320e9: tcp_try_rmem_schedule (STB_LOCAL)
ffffffff81934366-ffffffff8193437d: tcp_try_rmem_schedule.cold.87 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int tcp_try_rmem_schedule(struct sock *sk, struct sk_buff *skb, unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819953c0)
Location: net/ipv4/tcp_input.c:4478
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
ffffffff819953c0-ffffffff819957f1: tcp_try_rmem_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int tcp_try_rmem_schedule(struct sock *sk, struct sk_buff *skb, unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819cbf10)
Location: net/ipv4/tcp_input.c:4528
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
ffffffff819cbf10-ffffffff819cc34b: tcp_try_rmem_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int tcp_try_rmem_schedule(struct sock *sk, struct sk_buff *skb, unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab29d0)
Location: net/ipv4/tcp_input.c:4557
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81ab29d0-ffffffff81ab2a82: tcp_try_rmem_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int tcp_try_rmem_schedule(struct sock *sk, struct sk_buff *skb, unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abdd10)
Location: net/ipv4/tcp_input.c:4695
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81abdd10-ffffffff81abddc2: tcp_try_rmem_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int tcp_try_rmem_schedule(struct sock *sk, struct sk_buff *skb, unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa8e70)
Location: net/ipv4/tcp_input.c:4705
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81aa8e70-ffffffff81aa928f: tcp_try_rmem_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int tcp_try_rmem_schedule(struct sock *sk, struct sk_buff *skb, unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b64bc0)
Location: net/ipv4/tcp_input.c:4739
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81b64bc0-ffffffff81b64fdc: tcp_try_rmem_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tcp_try_rmem_schedule(struct sock *sk, struct sk_buff *skb, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:4758
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81cf3a50-ffffffff81cf3f34: tcp_try_rmem_schedule (STB_LOCAL)
ffffffff81f0704d-ffffffff81f0708d: tcp_try_rmem_schedule.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tcp_try_rmem_schedule(struct sock *sk, struct sk_buff *skb, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:4771
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81eb8450-ffffffff81eb88d7: tcp_try_rmem_schedule (STB_LOCAL)
ffffffff820aeaf2-ffffffff820aeb3e: tcp_try_rmem_schedule.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tcp_try_rmem_schedule(struct sock *sk, struct sk_buff *skb, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:4776
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81f168c0-ffffffff81f16d4f: tcp_try_rmem_schedule (STB_LOCAL)
ffffffff8212ff90-ffffffff8212ffdc: tcp_try_rmem_schedule.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcp_try_rmem_schedule(struct sock *sk, struct sk_buff *skb, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fdb730)
Location: net/ipv4/tcp_input.c:4907
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81fdb730-ffffffff81fdbb8e: tcp_try_rmem_schedule (STB_LOCAL)
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
int tcp_try_rmem_schedule(struct sock *sk, struct sk_buff *skb, unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c7eb68)
Location: net/ipv4/tcp_input.c:4528
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
ffff800010c7eb68-ffff800010c7ef98: tcp_try_rmem_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int tcp_try_rmem_schedule(struct sock *sk, struct sk_buff *skb, unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d8dba0)
Location: net/ipv4/tcp_input.c:4528
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
c0d8dba0-c0d8e068: tcp_try_rmem_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int tcp_try_rmem_schedule(struct sock *sk, struct sk_buff *skb, unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d88fe0)
Location: net/ipv4/tcp_input.c:4528
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
c000000000d88fe0-c000000000d895a4: tcp_try_rmem_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int tcp_try_rmem_schedule(struct sock *sk, struct sk_buff *skb, unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007e0dd6)
Location: net/ipv4/tcp_input.c:4528
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
ffffffe0007e0dd6-ffffffe0007e11a4: tcp_try_rmem_schedule (STB_LOCAL)
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
int tcp_try_rmem_schedule(struct sock *sk, struct sk_buff *skb, unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8196bd80)
Location: net/ipv4/tcp_input.c:4528
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
ffffffff8196bd80-ffffffff8196c1bb: tcp_try_rmem_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int tcp_try_rmem_schedule(struct sock *sk, struct sk_buff *skb, unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81925870)
Location: net/ipv4/tcp_input.c:4528
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81925870-ffffffff81925cab: tcp_try_rmem_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int tcp_try_rmem_schedule(struct sock *sk, struct sk_buff *skb, unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d6550)
Location: net/ipv4/tcp_input.c:4528
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
ffffffff819d6550-ffffffff819d698b: tcp_try_rmem_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int tcp_try_rmem_schedule(struct sock *sk, struct sk_buff *skb, unsigned int size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819e0170)
Location: net/ipv4/tcp_input.c:4528
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
**Symbols:**

```
ffffffff819e0170-ffffffff819e05ab: tcp_try_rmem_schedule (STB_LOCAL)
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
