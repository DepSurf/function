# Function: <code>icmp_unreach</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool icmp_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff8178eea0)
Location: net/ipv4/icmp.c:773
Inline: False
```
**Symbols:**

```
ffffffff8178eea0-ffffffff8178f04c: icmp_unreach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool icmp_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff817fc470)
Location: net/ipv4/icmp.c:773
Inline: False
```
**Symbols:**

```
ffffffff817fc470-ffffffff817fc6aa: icmp_unreach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool icmp_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff8182d3d0)
Location: net/ipv4/icmp.c:775
Inline: False
```
**Symbols:**

```
ffffffff8182d3d0-ffffffff8182d60a: icmp_unreach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool icmp_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff8184e890)
Location: net/ipv4/icmp.c:789
Inline: False
```
**Symbols:**

```
ffffffff8184e890-ffffffff8184eaa8: icmp_unreach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool icmp_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff818ce5d0)
Location: net/ipv4/icmp.c:789
Inline: False
```
**Symbols:**

```
ffffffff818ce5d0-ffffffff818ce82a: icmp_unreach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
bool icmp_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (0)
Location: net/ipv4/icmp.c:789
Inline: False
```
**Symbols:**

```
ffffffff81924020-ffffffff81924214: icmp_unreach (STB_LOCAL)
ffffffff8192509b-ffffffff819250d5: icmp_unreach.cold.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
bool icmp_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (0)
Location: net/ipv4/icmp.c:785
Inline: False
```
**Symbols:**

```
ffffffff81953430-ffffffff8195361e: icmp_unreach (STB_LOCAL)
ffffffff81953ea7-ffffffff81953ee1: icmp_unreach.cold.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool icmp_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (0)
Location: net/ipv4/icmp.c:786
Inline: False
```
**Symbols:**

```
ffffffff819b7660-ffffffff819b7859: icmp_unreach (STB_LOCAL)
ffffffff819b87c2-ffffffff819b87fd: icmp_unreach.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool icmp_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (0)
Location: net/ipv4/icmp.c:787
Inline: False
```
**Symbols:**

```
ffffffff819ee360-ffffffff819ee559: icmp_unreach (STB_LOCAL)
ffffffff819ef4c2-ffffffff819ef4fd: icmp_unreach.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool icmp_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (0)
Location: net/ipv4/icmp.c:821
Inline: False
```
**Symbols:**

```
ffffffff81adc120-ffffffff81adc319: icmp_unreach (STB_LOCAL)
ffffffff81add412-ffffffff81add44d: icmp_unreach.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool icmp_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (0)
Location: net/ipv4/icmp.c:844
Inline: False
```
**Symbols:**

```
ffffffff81ae8e20-ffffffff81ae9022: icmp_unreach (STB_LOCAL)
ffffffff81c32830-ffffffff81c3286b: icmp_unreach.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool icmp_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (0)
Location: net/ipv4/icmp.c:851
Inline: False
```
**Symbols:**

```
ffffffff81ad3f30-ffffffff81ad4139: icmp_unreach (STB_LOCAL)
ffffffff81c24b02-ffffffff81c24b3f: icmp_unreach.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool icmp_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (0)
Location: net/ipv4/icmp.c:851
Inline: False
```
**Symbols:**

```
ffffffff81b92c20-ffffffff81b92e22: icmp_unreach (STB_LOCAL)
ffffffff81d3c111-ffffffff81d3c14e: icmp_unreach.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum skb_drop_reason icmp_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (0)
Location: net/ipv4/icmp.c:844
Inline: False
```
**Symbols:**

```
ffffffff81d24e00-ffffffff81d2503d: icmp_unreach (STB_LOCAL)
ffffffff81f0897f-ffffffff81f089b4: icmp_unreach.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum skb_drop_reason icmp_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81eecc30)
Location: net/ipv4/icmp.c:844
Inline: False
```
**Symbols:**

```
ffffffff81eecc30-ffffffff81eecea0: icmp_unreach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum skb_drop_reason icmp_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81f4c5c0)
Location: net/ipv4/icmp.c:852
Inline: False
```
**Symbols:**

```
ffffffff81f4c5c0-ffffffff81f4c838: icmp_unreach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum skb_drop_reason icmp_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff820126d0)
Location: net/ipv4/icmp.c:852
Inline: False
```
**Symbols:**

```
ffffffff820126d0-ffffffff8201294f: icmp_unreach (STB_LOCAL)
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
bool icmp_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffff800010ca46b0)
Location: net/ipv4/icmp.c:787
Inline: False
```
**Symbols:**

```
ffff800010ca46b0-ffff800010ca4948: icmp_unreach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool icmp_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (c0db1454)
Location: net/ipv4/icmp.c:787
Inline: False
```
**Symbols:**

```
c0db1454-c0db16f0: icmp_unreach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool icmp_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (c000000000db81d0)
Location: net/ipv4/icmp.c:787
Inline: False
```
**Symbols:**

```
c000000000db81d0-c000000000db8550: icmp_unreach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool icmp_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffe000800546)
Location: net/ipv4/icmp.c:787
Inline: False
```
**Symbols:**

```
ffffffe000800546-ffffffe000800782: icmp_unreach (STB_LOCAL)
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
bool icmp_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (0)
Location: net/ipv4/icmp.c:787
Inline: False
```
**Symbols:**

```
ffffffff8198e100-ffffffff8198e2f9: icmp_unreach (STB_LOCAL)
ffffffff8198f262-ffffffff8198f29d: icmp_unreach.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
bool icmp_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (0)
Location: net/ipv4/icmp.c:787
Inline: False
```
**Symbols:**

```
ffffffff81947bc0-ffffffff81947db9: icmp_unreach (STB_LOCAL)
ffffffff81948d22-ffffffff81948d5d: icmp_unreach.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
bool icmp_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (0)
Location: net/ipv4/icmp.c:787
Inline: False
```
**Symbols:**

```
ffffffff819f89a0-ffffffff819f8b99: icmp_unreach (STB_LOCAL)
ffffffff819f9b02-ffffffff819f9b3d: icmp_unreach.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool icmp_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (0)
Location: net/ipv4/icmp.c:787
Inline: False
```
**Symbols:**

```
ffffffff81a03750-ffffffff81a03957: icmp_unreach (STB_LOCAL)
ffffffff81a03df2-ffffffff81a03e2d: icmp_unreach.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>enum skb_drop_reason</code>
</li>
</ul>
</details>
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
