# Function: <code>igmp_heard_query</code>

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
In net/ipv4/igmp.c (ffffffff817985ab)
Location: net/ipv4/igmp.c:881
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
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
In net/ipv4/igmp.c (ffffffff818060b3)
Location: net/ipv4/igmp.c:878
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
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
In net/ipv4/igmp.c (ffffffff81837133)
Location: net/ipv4/igmp.c:893
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
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
In net/ipv4/igmp.c (ffffffff818585a2)
Location: net/ipv4/igmp.c:893
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
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
In net/ipv4/igmp.c (ffffffff818d8472)
Location: net/ipv4/igmp.c:921
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
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
In net/ipv4/igmp.c (ffffffff8192ee9c)
Location: net/ipv4/igmp.c:921
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
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
In net/ipv4/igmp.c (ffffffff8195e2fa)
Location: net/ipv4/igmp.c:917
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool igmp_heard_query(struct in_device *in_dev, struct sk_buff *skb, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819c26f0)
Location: net/ipv4/igmp.c:933
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_rcv
```
**Symbols:**

```
ffffffff819c26f0-ffffffff819c2caa: igmp_heard_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool igmp_heard_query(struct in_device *in_dev, struct sk_buff *skb, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819f9290)
Location: net/ipv4/igmp.c:933
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_rcv
```
**Symbols:**

```
ffffffff819f9290-ffffffff819f984a: igmp_heard_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool igmp_heard_query(struct in_device *in_dev, struct sk_buff *skb, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ae8120)
Location: net/ipv4/igmp.c:931
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_rcv
```
**Symbols:**

```
ffffffff81ae8120-ffffffff81ae876f: igmp_heard_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool igmp_heard_query(struct in_device *in_dev, struct sk_buff *skb, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81af5010)
Location: net/ipv4/igmp.c:931
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_rcv
```
**Symbols:**

```
ffffffff81af5010-ffffffff81af5664: igmp_heard_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool igmp_heard_query(struct in_device *in_dev, struct sk_buff *skb, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ae0200)
Location: net/ipv4/igmp.c:938
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_rcv
```
**Symbols:**

```
ffffffff81ae0200-ffffffff81ae0850: igmp_heard_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool igmp_heard_query(struct in_device *in_dev, struct sk_buff *skb, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81b9f840)
Location: net/ipv4/igmp.c:938
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_rcv
```
**Symbols:**

```
ffffffff81b9f840-ffffffff81b9fe90: igmp_heard_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool igmp_heard_query(struct in_device *in_dev, struct sk_buff *skb, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81d31cf0)
Location: net/ipv4/igmp.c:941
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_rcv
```
**Symbols:**

```
ffffffff81d31cf0-ffffffff81d322f0: igmp_heard_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool igmp_heard_query(struct in_device *in_dev, struct sk_buff *skb, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ef8fb0)
Location: net/ipv4/igmp.c:941
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_rcv
```
**Symbols:**

```
ffffffff81ef8fb0-ffffffff81ef95aa: igmp_heard_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool igmp_heard_query(struct in_device *in_dev, struct sk_buff *skb, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81f58b60)
Location: net/ipv4/igmp.c:942
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_rcv
```
**Symbols:**

```
ffffffff81f58b60-ffffffff81f59186: igmp_heard_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool igmp_heard_query(struct in_device *in_dev, struct sk_buff *skb, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8201f030)
Location: net/ipv4/igmp.c:944
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_rcv
```
**Symbols:**

```
ffffffff8201f030-ffffffff8201f649: igmp_heard_query (STB_LOCAL)
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
bool igmp_heard_query(struct in_device *in_dev, struct sk_buff *skb, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffff800010cb0450)
Location: net/ipv4/igmp.c:933
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_rcv
```
**Symbols:**

```
ffff800010cb0450-ffff800010cb0af4: igmp_heard_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool igmp_heard_query(struct in_device *in_dev, struct sk_buff *skb, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c0dbcc64)
Location: net/ipv4/igmp.c:933
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_rcv
```
**Symbols:**

```
c0dbcc64-c0dbd2dc: igmp_heard_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool igmp_heard_query(struct in_device *in_dev, struct sk_buff *skb, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c000000000dc76d0)
Location: net/ipv4/igmp.c:933
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_rcv
```
**Symbols:**

```
c000000000dc76d0-c000000000dc7e9c: igmp_heard_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool igmp_heard_query(struct in_device *in_dev, struct sk_buff *skb, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffe000809c5e)
Location: net/ipv4/igmp.c:933
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_rcv
```
**Symbols:**

```
ffffffe000809c5e-ffffffe00080a158: igmp_heard_query (STB_LOCAL)
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
bool igmp_heard_query(struct in_device *in_dev, struct sk_buff *skb, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81999030)
Location: net/ipv4/igmp.c:933
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_rcv
```
**Symbols:**

```
ffffffff81999030-ffffffff819995ea: igmp_heard_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool igmp_heard_query(struct in_device *in_dev, struct sk_buff *skb, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81952af0)
Location: net/ipv4/igmp.c:933
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_rcv
```
**Symbols:**

```
ffffffff81952af0-ffffffff819530aa: igmp_heard_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool igmp_heard_query(struct in_device *in_dev, struct sk_buff *skb, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a038d0)
Location: net/ipv4/igmp.c:933
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_rcv
```
**Symbols:**

```
ffffffff81a038d0-ffffffff81a03e8a: igmp_heard_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool igmp_heard_query(struct in_device *in_dev, struct sk_buff *skb, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a0de30)
Location: net/ipv4/igmp.c:933
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_rcv
```
**Symbols:**

```
ffffffff81a0de30-ffffffff81a0e3f1: igmp_heard_query (STB_LOCAL)
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
