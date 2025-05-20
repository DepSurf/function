# Function: <code>udp4_gro_receive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff **udp4_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff8178b590)
Location: net/ipv4/udp_offload.c:352
Inline: False
```
**Symbols:**

```
ffffffff8178b590-ffffffff8178b86d: udp4_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff **udp4_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff817f8d20)
Location: net/ipv4/udp_offload.c:312
Inline: False
```
**Symbols:**

```
ffffffff817f8d20-ffffffff817f8fec: udp4_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff **udp4_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81829bf0)
Location: net/ipv4/udp_offload.c:308
Inline: False
```
**Symbols:**

```
ffffffff81829bf0-ffffffff81829ebc: udp4_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff **udp4_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff8184ae40)
Location: net/ipv4/udp_offload.c:311
Inline: False
```
**Symbols:**

```
ffffffff8184ae40-ffffffff8184b0f7: udp4_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff **udp4_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff818caaa0)
Location: net/ipv4/udp_offload.c:303
Inline: False
```
**Symbols:**

```
ffffffff818caaa0-ffffffff818cad57: udp4_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff **udp4_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81920a30)
Location: net/ipv4/udp_offload.c:402
Inline: False
```
**Symbols:**

```
ffffffff81920a30-ffffffff81920cdc: udp4_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *udp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff8194fd50)
Location: net/ipv4/udp_offload.c:459
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff8194fd50-ffffffff8194fffa: udp4_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *udp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff819b45e0)
Location: net/ipv4/udp_offload.c:468
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff819b45e0-ffffffff819b48ce: udp4_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *udp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff819eb310)
Location: net/ipv4/udp_offload.c:468
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff819eb310-ffffffff819eb5fe: udp4_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *udp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ad9020)
Location: net/ipv4/udp_offload.c:504
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff81ad9020-ffffffff81ad9318: udp4_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *udp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ae59b0)
Location: net/ipv4/udp_offload.c:576
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff81ae59b0-ffffffff81ae5d53: udp4_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *udp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ad0ca0)
Location: net/ipv4/udp_offload.c:582
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff81ad0ca0-ffffffff81ad1039: udp4_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *udp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81b8f6c0)
Location: net/ipv4/udp_offload.c:582
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff81b8f6c0-ffffffff81b8fa56: udp4_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *udp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81d209d0)
Location: net/ipv4/udp_offload.c:610
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff81d209d0-ffffffff81d20d33: udp4_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *udp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81ee7c40)
Location: net/ipv4/udp_offload.c:612
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff81ee7c40-ffffffff81ee7fb0: udp4_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *udp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81f474b0)
Location: net/ipv4/udp_offload.c:622
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff81f474b0-ffffffff81f4787d: udp4_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *udp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff8200d5f0)
Location: net/ipv4/udp_offload.c:622
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff8200d5f0-ffffffff8200d9bd: udp4_gro_receive (STB_GLOBAL)
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
struct sk_buff *udp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffff800010ca0e60)
Location: net/ipv4/udp_offload.c:468
Inline: False
```
**Symbols:**

```
ffff800010ca0e60-ffff800010ca10fc: udp4_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *udp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (c0dad398)
Location: net/ipv4/udp_offload.c:468
Inline: False
```
**Symbols:**

```
c0dad398-c0dad668: udp4_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *udp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (c000000000db3d30)
Location: net/ipv4/udp_offload.c:468
Inline: False
```
**Symbols:**

```
c000000000db3d30-c000000000db40c8: udp4_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *udp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffe0007fd4be)
Location: net/ipv4/udp_offload.c:468
Inline: False
```
**Symbols:**

```
ffffffe0007fd4be-ffffffe0007fd70a: udp4_gro_receive (STB_LOCAL)
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
struct sk_buff *udp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff8198b180)
Location: net/ipv4/udp_offload.c:468
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff8198b180-ffffffff8198b46e: udp4_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *udp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff81944c40)
Location: net/ipv4/udp_offload.c:468
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff81944c40-ffffffff81944f2e: udp4_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *udp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff819f5950)
Location: net/ipv4/udp_offload.c:468
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff819f5950-ffffffff819f5c3e: udp4_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *udp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_offload.c (ffffffff819ffb50)
Location: net/ipv4/udp_offload.c:468
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff819ffb50-ffffffff819ffe3e: udp4_gro_receive (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct sk_buff **head</code> ➡️ <code>struct list_head *head</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct sk_buff **</code> ➡️ <code>struct sk_buff *</code>
</li>
</ul>
</details>
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
