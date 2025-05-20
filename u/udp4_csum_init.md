# Function: <code>udp4_csum_init</code>

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
In net/ipv4/udp.c (ffffffff8178a06c)
Location: net/ipv4/udp.c:1735
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
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
In net/ipv4/udp.c (ffffffff817f73aa)
Location: net/ipv4/udp.c:1703
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
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
In net/ipv4/udp.c (ffffffff818282cc)
Location: net/ipv4/udp.c:1859
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
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
In net/ipv4/udp.c (ffffffff81849629)
Location: net/ipv4/udp.c:2022
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
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
In net/ipv4/udp.c (ffffffff818c909e)
Location: net/ipv4/udp.c:2022
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
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
In net/ipv4/udp.c (ffffffff8191f196)
Location: net/ipv4/udp.c:2105
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
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
In net/ipv4/udp.c (ffffffff8194ddf0)
Location: net/ipv4/udp.c:2191
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819b25d1)
Location: net/ipv4/udp.c:2177
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819e9371)
Location: net/ipv4/udp.c:2213
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int udp4_csum_init(struct sk_buff *skb, struct udphdr *uh, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ad31b0)
Location: net/ipv4/udp.c:2221
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81ad31b0-ffffffff81ad347e: udp4_csum_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int udp4_csum_init(struct sk_buff *skb, struct udphdr *uh, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81adf5b0)
Location: net/ipv4/udp.c:2274
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81adf5b0-ffffffff81adf87b: udp4_csum_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int udp4_csum_init(struct sk_buff *skb, struct udphdr *uh, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81aca4b0)
Location: net/ipv4/udp.c:2325
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81aca4b0-ffffffff81aca780: udp4_csum_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int udp4_csum_init(struct sk_buff *skb, struct udphdr *uh, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81b88d90)
Location: net/ipv4/udp.c:2337
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81b88d90-ffffffff81b8905d: udp4_csum_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int udp4_csum_init(struct sk_buff *skb, struct udphdr *uh, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81d1a800)
Location: net/ipv4/udp.c:2346
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81d1a800-ffffffff81d1aaf9: udp4_csum_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int udp4_csum_init(struct sk_buff *skb, struct udphdr *uh, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ee1530)
Location: net/ipv4/udp.c:2348
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81ee1530-ffffffff81ee1829: udp4_csum_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int udp4_csum_init(struct sk_buff *skb, struct udphdr *uh, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81f40f70)
Location: net/ipv4/udp.c:2320
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff81f40f70-ffffffff81f4125c: udp4_csum_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int udp4_csum_init(struct sk_buff *skb, struct udphdr *uh, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff82006bc0)
Location: net/ipv4/udp.c:2293
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
**Symbols:**

```
ffffffff82006bc0-ffffffff82006eac: udp4_csum_init (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffff800010c9ec5c)
Location: net/ipv4/udp.c:2213
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
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
In net/ipv4/udp.c (c0dabec0)
Location: net/ipv4/udp.c:2213
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c000000000db14b0)
Location: net/ipv4/udp.c:2213
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffe0007fb7b4)
Location: net/ipv4/udp.c:2213
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819891e1)
Location: net/ipv4/udp.c:2213
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81942ca1)
Location: net/ipv4/udp.c:2213
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819f39b1)
Location: net/ipv4/udp.c:2213
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819fdb71)
Location: net/ipv4/udp.c:2213
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
