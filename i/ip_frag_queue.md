# Function: <code>ip_frag_queue</code>

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
In net/ipv4/ip_fragment.c (ffffffff8175982c)
Location: net/ipv4/ip_fragment.c:334
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
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
In net/ipv4/ip_fragment.c (ffffffff817c5c0c)
Location: net/ipv4/ip_fragment.c:332
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
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
In net/ipv4/ip_fragment.c (ffffffff817f570c)
Location: net/ipv4/ip_fragment.c:332
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
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
In net/ipv4/ip_fragment.c (ffffffff81815baa)
Location: net/ipv4/ip_fragment.c:341
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
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
In net/ipv4/ip_fragment.c (ffffffff81894d81)
Location: net/ipv4/ip_fragment.c:343
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
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
In net/ipv4/ip_fragment.c (ffffffff818e8e76)
Location: net/ipv4/ip_fragment.c:278
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
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
In net/ipv4/ip_fragment.c (ffffffff81916052)
Location: net/ipv4/ip_fragment.c:344
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ip_frag_queue(struct ipq *qp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_fragment.c (0)
Location: net/ipv4/ip_fragment.c:272
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
**Symbols:**

```
ffffffff81978190-ffffffff81978885: ip_frag_queue (STB_LOCAL)
ffffffff8197911e-ffffffff8197914d: ip_frag_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ip_frag_queue(struct ipq *qp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_fragment.c (0)
Location: net/ipv4/ip_fragment.c:272
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
**Symbols:**

```
ffffffff819aeb00-ffffffff819af1f5: ip_frag_queue (STB_LOCAL)
ffffffff819afa8e-ffffffff819afabd: ip_frag_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip_frag_queue(struct ipq *qp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81a98f20)
Location: net/ipv4/ip_fragment.c:272
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
**Symbols:**

```
ffffffff81a98f20-ffffffff81a9938d: ip_frag_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip_frag_queue(struct ipq *qp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81aa2e90)
Location: net/ipv4/ip_fragment.c:272
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
**Symbols:**

```
ffffffff81aa2e90-ffffffff81aa32fd: ip_frag_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip_frag_queue(struct ipq *qp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81a8dea0)
Location: net/ipv4/ip_fragment.c:272
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
**Symbols:**

```
ffffffff81a8dea0-ffffffff81a8e3ba: ip_frag_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip_frag_queue(struct ipq *qp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81b49090)
Location: net/ipv4/ip_fragment.c:273
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
**Symbols:**

```
ffffffff81b49090-ffffffff81b495aa: ip_frag_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip_frag_queue(struct ipq *qp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81cd6710)
Location: net/ipv4/ip_fragment.c:273
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
**Symbols:**

```
ffffffff81cd6710-ffffffff81cd6c4b: ip_frag_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip_frag_queue(struct ipq *qp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81e96cc0)
Location: net/ipv4/ip_fragment.c:275
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
**Symbols:**

```
ffffffff81e96cc0-ffffffff81e97205: ip_frag_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ip_frag_queue(struct ipq *qp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81ef5500)
Location: net/ipv4/ip_fragment.c:275
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
**Symbols:**

```
ffffffff81ef5500-ffffffff81ef5a3c: ip_frag_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ip_frag_queue(struct ipq *qp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81fb94b0)
Location: net/ipv4/ip_fragment.c:275
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
**Symbols:**

```
ffffffff81fb94b0-ffffffff81fb99ec: ip_frag_queue (STB_LOCAL)
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
int ip_frag_queue(struct ipq *qp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffff800010c5f728)
Location: net/ipv4/ip_fragment.c:272
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
**Symbols:**

```
ffff800010c5f728-ffff800010c5fd34: ip_frag_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip_frag_queue(struct ipq *qp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (c0d6e774)
Location: net/ipv4/ip_fragment.c:272
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
**Symbols:**

```
c0d6e774-c0d6ef14: ip_frag_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip_frag_queue(struct ipq *qp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (c000000000d61c20)
Location: net/ipv4/ip_fragment.c:272
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
**Symbols:**

```
c000000000d61c20-c000000000d62370: ip_frag_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip_frag_queue(struct ipq *qp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffe0007c7562)
Location: net/ipv4/ip_fragment.c:272
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
**Symbols:**

```
ffffffe0007c7562-ffffffe0007c7af4: ip_frag_queue (STB_LOCAL)
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
int ip_frag_queue(struct ipq *qp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_fragment.c (0)
Location: net/ipv4/ip_fragment.c:272
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
**Symbols:**

```
ffffffff8194e970-ffffffff8194f065: ip_frag_queue (STB_LOCAL)
ffffffff8194f8fe-ffffffff8194f92d: ip_frag_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ip_frag_queue(struct ipq *qp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_fragment.c (0)
Location: net/ipv4/ip_fragment.c:272
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
**Symbols:**

```
ffffffff81908460-ffffffff81908b55: ip_frag_queue (STB_LOCAL)
ffffffff819093ee-ffffffff8190941d: ip_frag_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ip_frag_queue(struct ipq *qp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_fragment.c (0)
Location: net/ipv4/ip_fragment.c:272
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
**Symbols:**

```
ffffffff819b9140-ffffffff819b9835: ip_frag_queue (STB_LOCAL)
ffffffff819ba0ce-ffffffff819ba0fd: ip_frag_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ip_frag_queue(struct ipq *qp, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_fragment.c (0)
Location: net/ipv4/ip_fragment.c:272
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
**Symbols:**

```
ffffffff819c2a30-ffffffff819c3125: ip_frag_queue (STB_LOCAL)
ffffffff819c39bf-ffffffff819c39ee: ip_frag_queue.cold (STB_LOCAL)
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
