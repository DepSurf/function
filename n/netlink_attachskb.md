# Function: <code>netlink_attachskb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int netlink_attachskb(struct sock *sk, struct sk_buff *skb, long int *timeo, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8174e2d0)
Location: net/netlink/af_netlink.c:1723
Inline: True
Direct callers:
  - ipc/mqueue.c:SyS_mq_notify
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff8174e2d0-ffffffff8174e4a9: netlink_attachskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int netlink_attachskb(struct sock *sk, struct sk_buff *skb, long int *timeo, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817ba490)
Location: net/netlink/af_netlink.c:1114
Inline: False
Direct callers:
  - ipc/mqueue.c:SyS_mq_notify
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff817ba490-ffffffff817ba64c: netlink_attachskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int netlink_attachskb(struct sock *sk, struct sk_buff *skb, long int *timeo, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817e9e30)
Location: net/netlink/af_netlink.c:1131
Inline: False
Direct callers:
  - ipc/mqueue.c:SyS_mq_notify
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff817e9e30-ffffffff817e9fe9: netlink_attachskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int netlink_attachskb(struct sock *sk, struct sk_buff *skb, long int *timeo, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81809b00)
Location: net/netlink/af_netlink.c:1165
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_notify
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81809b00-ffffffff81809cb9: netlink_attachskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int netlink_attachskb(struct sock *sk, struct sk_buff *skb, long int *timeo, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81888a50)
Location: net/netlink/af_netlink.c:1178
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_notify
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81888a50-ffffffff81888c15: netlink_attachskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int netlink_attachskb(struct sock *sk, struct sk_buff *skb, long int *timeo, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818dc490)
Location: net/netlink/af_netlink.c:1217
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_notify
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff818dc490-ffffffff818dc669: netlink_attachskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int netlink_attachskb(struct sock *sk, struct sk_buff *skb, long int *timeo, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81908e70)
Location: net/netlink/af_netlink.c:1210
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_notify
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81908e70-ffffffff81909049: netlink_attachskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int netlink_attachskb(struct sock *sk, struct sk_buff *skb, long int *timeo, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8196a1c0)
Location: net/netlink/af_netlink.c:1202
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_notify
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff8196a1c0-ffffffff8196a392: netlink_attachskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int netlink_attachskb(struct sock *sk, struct sk_buff *skb, long int *timeo, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819a0c30)
Location: net/netlink/af_netlink.c:1203
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_notify
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff819a0c30-ffffffff819a0e02: netlink_attachskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int netlink_attachskb(struct sock *sk, struct sk_buff *skb, long int *timeo, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a7a3f0)
Location: net/netlink/af_netlink.c:1203
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_notify
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81a7a3f0-ffffffff81a7a616: netlink_attachskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netlink_attachskb(struct sock *sk, struct sk_buff *skb, long int *timeo, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a83250)
Location: net/netlink/af_netlink.c:1204
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_notify
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81a83250-ffffffff81a83481: netlink_attachskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int netlink_attachskb(struct sock *sk, struct sk_buff *skb, long int *timeo, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a6c320)
Location: net/netlink/af_netlink.c:1214
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_notify
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81a6c320-ffffffff81a6c551: netlink_attachskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int netlink_attachskb(struct sock *sk, struct sk_buff *skb, long int *timeo, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81b25980)
Location: net/netlink/af_netlink.c:1219
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_notify
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81b25980-ffffffff81b25baf: netlink_attachskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int netlink_attachskb(struct sock *sk, struct sk_buff *skb, long int *timeo, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81cae520)
Location: net/netlink/af_netlink.c:1219
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_notify
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81cae520-ffffffff81cae75c: netlink_attachskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int netlink_attachskb(struct sock *sk, struct sk_buff *skb, long int *timeo, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81e6bb50)
Location: net/netlink/af_netlink.c:1239
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_notify
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81e6bb50-ffffffff81e6bd88: netlink_attachskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int netlink_attachskb(struct sock *sk, struct sk_buff *skb, long int *timeo, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81ec7bb0)
Location: net/netlink/af_netlink.c:1239
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_notify
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81ec7bb0-ffffffff81ec7de8: netlink_attachskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int netlink_attachskb(struct sock *sk, struct sk_buff *skb, long int *timeo, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81f8afc0)
Location: net/netlink/af_netlink.c:1241
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_notify
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81f8afc0-ffffffff81f8b1fa: netlink_attachskb (STB_GLOBAL)
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
int netlink_attachskb(struct sock *sk, struct sk_buff *skb, long int *timeo, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffff800010c4f360)
Location: net/netlink/af_netlink.c:1203
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_notify
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffff800010c4f360-ffff800010c4f514: netlink_attachskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int netlink_attachskb(struct sock *sk, struct sk_buff *skb, long int *timeo, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c0d5f48c)
Location: net/netlink/af_netlink.c:1203
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_notify
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
c0d5f48c-c0d5f67c: netlink_attachskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int netlink_attachskb(struct sock *sk, struct sk_buff *skb, long int *timeo, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c000000000d4db00)
Location: net/netlink/af_netlink.c:1203
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_notify
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
c000000000d4db00-c000000000d4dd68: netlink_attachskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int netlink_attachskb(struct sock *sk, struct sk_buff *skb, long int *timeo, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffe0007baf9a)
Location: net/netlink/af_netlink.c:1203
Inline: False
Direct callers:
  - ipc/mqueue.c:__se_sys_mq_notify
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffe0007baf9a-ffffffe0007bb124: netlink_attachskb (STB_GLOBAL)
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
int netlink_attachskb(struct sock *sk, struct sk_buff *skb, long int *timeo, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81940aa0)
Location: net/netlink/af_netlink.c:1203
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_notify
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81940aa0-ffffffff81940c72: netlink_attachskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int netlink_attachskb(struct sock *sk, struct sk_buff *skb, long int *timeo, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818fa590)
Location: net/netlink/af_netlink.c:1203
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_notify
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff818fa590-ffffffff818fa762: netlink_attachskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int netlink_attachskb(struct sock *sk, struct sk_buff *skb, long int *timeo, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81991c30)
Location: net/netlink/af_netlink.c:1203
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_notify
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff81991c30-ffffffff81991e02: netlink_attachskb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int netlink_attachskb(struct sock *sk, struct sk_buff *skb, long int *timeo, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819b4720)
Location: net/netlink/af_netlink.c:1203
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_notify
  - net/netlink/af_netlink.c:netlink_unicast
```
**Symbols:**

```
ffffffff819b4720-ffffffff819b48f2: netlink_attachskb (STB_GLOBAL)
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
