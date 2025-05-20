# Function: <code>ndisc_recv_rs</code>

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
In net/ipv6/ndisc.c (ffffffff817e1364)
Location: net/ipv6/ndisc.c:980
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
void ndisc_recv_rs(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff8184e770)
Location: net/ipv6/ndisc.c:1018
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff8184e770-ffffffff8184e923: ndisc_recv_rs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ndisc_recv_rs(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff818806c0)
Location: net/ipv6/ndisc.c:1038
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff818806c0-ffffffff8188087d: ndisc_recv_rs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ndisc_recv_rs(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff818a6780)
Location: net/ipv6/ndisc.c:1038
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff818a6780-ffffffff818a6936: ndisc_recv_rs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ndisc_recv_rs(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff819291d0)
Location: net/ipv6/ndisc.c:1051
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff819291d0-ffffffff81929390: ndisc_recv_rs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void ndisc_recv_rs(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:1051
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81981500-ffffffff819816c4: ndisc_recv_rs (STB_LOCAL)
ffffffff8198299d-ffffffff819829ae: ndisc_recv_rs.cold.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void ndisc_recv_rs(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:1051
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff819b7bb0-ffffffff819b7d62: ndisc_recv_rs (STB_LOCAL)
ffffffff819b903d-ffffffff819b904e: ndisc_recv_rs.cold.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ndisc_recv_rs(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:1064
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81a26620-ffffffff81a267d2: ndisc_recv_rs (STB_LOCAL)
ffffffff81a27b4a-ffffffff81a27b5b: ndisc_recv_rs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void ndisc_recv_rs(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:1065
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81a5d0a0-ffffffff81a5d252: ndisc_recv_rs (STB_LOCAL)
ffffffff81a5e5aa-ffffffff81a5e5bb: ndisc_recv_rs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ndisc_recv_rs(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:1066
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81b54c80-ffffffff81b54e6c: ndisc_recv_rs (STB_LOCAL)
ffffffff81b57380-ffffffff81b57391: ndisc_recv_rs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ndisc_recv_rs(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:1068
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81b632a0-ffffffff81b6348c: ndisc_recv_rs (STB_LOCAL)
ffffffff81c32e7d-ffffffff81c32e8e: ndisc_recv_rs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ndisc_recv_rs(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:1068
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81b515c0-ffffffff81b517aa: ndisc_recv_rs (STB_LOCAL)
ffffffff81c2517e-ffffffff81c2518f: ndisc_recv_rs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ndisc_recv_rs(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:1068
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81c18a20-ffffffff81c18c0a: ndisc_recv_rs (STB_LOCAL)
ffffffff81d4056b-ffffffff81d4057c: ndisc_recv_rs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ndisc_recv_rs(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:1109
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81db4bc0-ffffffff81db4dd2: ndisc_recv_rs (STB_LOCAL)
ffffffff81f0cf31-ffffffff81f0cf42: ndisc_recv_rs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ndisc_recv_rs(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81f847b0)
Location: net/ipv6/ndisc.c:1129
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81f847b0-ffffffff81f849ce: ndisc_recv_rs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum skb_drop_reason ndisc_recv_rs(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81fe4af0)
Location: net/ipv6/ndisc.c:1130
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81fe4af0-ffffffff81fe4d26: ndisc_recv_rs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum skb_drop_reason ndisc_recv_rs(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff820b2a00)
Location: net/ipv6/ndisc.c:1130
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff820b2a00-ffffffff820b2c36: ndisc_recv_rs (STB_LOCAL)
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
void ndisc_recv_rs(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffff800010d22310)
Location: net/ipv6/ndisc.c:1065
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffff800010d22310-ffff800010d224d0: ndisc_recv_rs (STB_LOCAL)
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
In net/ipv6/ndisc.c (c0e27b94)
Location: net/ipv6/ndisc.c:1065
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
void ndisc_recv_rs(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (c000000000e51da0)
Location: net/ipv6/ndisc.c:1065
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
c000000000e51da0-c000000000e52018: ndisc_recv_rs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ndisc_recv_rs(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffe000863f1c)
Location: net/ipv6/ndisc.c:1065
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffe000863f1c-ffffffe00086406c: ndisc_recv_rs (STB_LOCAL)
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
void ndisc_recv_rs(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:1065
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff819fc730-ffffffff819fc8e2: ndisc_recv_rs (STB_LOCAL)
ffffffff819fdc3a-ffffffff819fdc4b: ndisc_recv_rs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void ndisc_recv_rs(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:1065
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff819b94f0-ffffffff819b96a2: ndisc_recv_rs (STB_LOCAL)
ffffffff819ba9fa-ffffffff819baa0b: ndisc_recv_rs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void ndisc_recv_rs(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:1065
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81a671b0-ffffffff81a67362: ndisc_recv_rs (STB_LOCAL)
ffffffff81a686ba-ffffffff81a686cb: ndisc_recv_rs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void ndisc_recv_rs(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ndisc.c (0)
Location: net/ipv6/ndisc.c:1065
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81a73790-ffffffff81a73942: ndisc_recv_rs (STB_LOCAL)
ffffffff81a74cb5-ffffffff81a74cc6: ndisc_recv_rs.cold (STB_LOCAL)
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
