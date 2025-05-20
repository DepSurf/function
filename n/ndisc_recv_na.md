# Function: <code>ndisc_recv_na</code>

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
In net/ipv6/ndisc.c (ffffffff817e124e)
Location: net/ipv6/ndisc.c:876
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ndisc_recv_na(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff8184e440)
Location: net/ipv6/ndisc.c:904
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff8184e440-ffffffff8184e765: ndisc_recv_na (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ndisc_recv_na(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81880390)
Location: net/ipv6/ndisc.c:924
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81880390-ffffffff818806b5: ndisc_recv_na (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ndisc_recv_na(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff818a6430)
Location: net/ipv6/ndisc.c:924
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff818a6430-ffffffff818a6773: ndisc_recv_na (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ndisc_recv_na(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81928e60)
Location: net/ipv6/ndisc.c:937
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81928e60-ffffffff819291c6: ndisc_recv_na (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void ndisc_recv_na(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:937
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff819811d0-ffffffff819814f8: ndisc_recv_na (STB_LOCAL)
ffffffff8198295f-ffffffff8198299d: ndisc_recv_na.cold.39 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void ndisc_recv_na(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:937
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff819b7890-ffffffff819b7bad: ndisc_recv_na (STB_LOCAL)
ffffffff819b8fff-ffffffff819b903d: ndisc_recv_na.cold.39 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ndisc_recv_na(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:950
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81a262e0-ffffffff81a26619: ndisc_recv_na (STB_LOCAL)
ffffffff81a27b09-ffffffff81a27b4a: ndisc_recv_na.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void ndisc_recv_na(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:951
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81a5cd60-ffffffff81a5d099: ndisc_recv_na (STB_LOCAL)
ffffffff81a5e569-ffffffff81a5e5aa: ndisc_recv_na.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ndisc_recv_na(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:952
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81b54930-ffffffff81b54c7c: ndisc_recv_na (STB_LOCAL)
ffffffff81b5733f-ffffffff81b57380: ndisc_recv_na.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ndisc_recv_na(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:954
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81b62f50-ffffffff81b6329c: ndisc_recv_na (STB_LOCAL)
ffffffff81c32e3c-ffffffff81c32e7d: ndisc_recv_na.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ndisc_recv_na(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:954
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81b51260-ffffffff81b515bc: ndisc_recv_na (STB_LOCAL)
ffffffff81c2513d-ffffffff81c2517e: ndisc_recv_na.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ndisc_recv_na(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:954
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81c186c0-ffffffff81c18a1c: ndisc_recv_na (STB_LOCAL)
ffffffff81d4052a-ffffffff81d4056b: ndisc_recv_na.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ndisc_recv_na(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:969
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81db4740-ffffffff81db4bb1: ndisc_recv_na (STB_LOCAL)
ffffffff81f0cef5-ffffffff81f0cf31: ndisc_recv_na.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ndisc_recv_na(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81f842d0)
Location: net/ipv6/ndisc.c:989
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81f842d0-ffffffff81f8479c: ndisc_recv_na (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum skb_drop_reason ndisc_recv_na(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81fe4600)
Location: net/ipv6/ndisc.c:991
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81fe4600-ffffffff81fe4adf: ndisc_recv_na (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum skb_drop_reason ndisc_recv_na(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff820b2500)
Location: net/ipv6/ndisc.c:991
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff820b2500-ffffffff820b29ea: ndisc_recv_na (STB_LOCAL)
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
void ndisc_recv_na(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffff800010d22010)
Location: net/ipv6/ndisc.c:951
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffff800010d22010-ffff800010d2230c: ndisc_recv_na (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (c0e27cfc)
Location: net/ipv6/ndisc.c:951
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ndisc_recv_na(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (c000000000e51960)
Location: net/ipv6/ndisc.c:951
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
c000000000e51960-c000000000e51d94: ndisc_recv_na (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ndisc_recv_na(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffe000863cd0)
Location: net/ipv6/ndisc.c:951
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffe000863cd0-ffffffe000863f1c: ndisc_recv_na (STB_LOCAL)
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
void ndisc_recv_na(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:951
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff819fc3f0-ffffffff819fc729: ndisc_recv_na (STB_LOCAL)
ffffffff819fdbf9-ffffffff819fdc3a: ndisc_recv_na.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void ndisc_recv_na(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:951
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff819b91b0-ffffffff819b94e9: ndisc_recv_na (STB_LOCAL)
ffffffff819ba9b9-ffffffff819ba9fa: ndisc_recv_na.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void ndisc_recv_na(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:951
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81a66e70-ffffffff81a671a9: ndisc_recv_na (STB_LOCAL)
ffffffff81a68679-ffffffff81a686ba: ndisc_recv_na.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void ndisc_recv_na(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:951
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81a73450-ffffffff81a73789: ndisc_recv_na (STB_LOCAL)
ffffffff81a74c74-ffffffff81a74cb5: ndisc_recv_na.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>enum skb_drop_reason</code>
</li>
</ul>
</details>
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
