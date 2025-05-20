# Function: <code>icmp_reply</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (ffffffff8178e920)
Location: net/ipv4/icmp.c:389
Inline: True
```
**Symbols:**

```
ffffffff8178e920-ffffffff8178eb42: icmp_reply.constprop.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (ffffffff817fbf70)
Location: net/ipv4/icmp.c:389
Inline: True
```
**Symbols:**

```
ffffffff817fbf70-ffffffff817fc19e: icmp_reply.constprop.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (ffffffff8182cec0)
Location: net/ipv4/icmp.c:389
Inline: True
```
**Symbols:**

```
ffffffff8182cec0-ffffffff8182d100: icmp_reply.constprop.23 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff8184e350)
Location: net/ipv4/icmp.c:402
Inline: True
```
**Symbols:**

```
ffffffff8184e350-ffffffff8184e5c0: icmp_reply.constprop.26 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff818ce080)
Location: net/ipv4/icmp.c:402
Inline: True
```
**Symbols:**

```
ffffffff818ce080-ffffffff818ce2f2: icmp_reply.constprop.26 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff81924810)
Location: net/ipv4/icmp.c:402
Inline: True
```
**Symbols:**

```
ffffffff81924810-ffffffff81924a96: icmp_reply.constprop.33 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff81953620)
Location: net/ipv4/icmp.c:402
Inline: True
```
**Symbols:**

```
ffffffff81953620-ffffffff819538be: icmp_reply.constprop.34 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff819b7f00)
Location: net/ipv4/icmp.c:397
Inline: True
```
**Symbols:**

```
ffffffff819b7f00-ffffffff819b81a0: icmp_reply.constprop.0 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff819eec00)
Location: net/ipv4/icmp.c:398
Inline: True
```
**Symbols:**

```
ffffffff819eec00-ffffffff819eeea0: icmp_reply.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81adcb00)
Location: net/ipv4/icmp.c:398
Inline: True
```
**Symbols:**

```
ffffffff81adcb00-ffffffff81adcddf: icmp_reply.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81ae9840)
Location: net/ipv4/icmp.c:401
Inline: True
```
**Symbols:**

```
ffffffff81ae9840-ffffffff81ae9b30: icmp_reply.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void icmp_reply(struct icmp_bxm *icmp_param, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81ad43a0)
Location: net/ipv4/icmp.c:401
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_echo
```
**Symbols:**

```
ffffffff81ad43a0-ffffffff81ad4677: icmp_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void icmp_reply(struct icmp_bxm *icmp_param, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81b93db0)
Location: net/ipv4/icmp.c:401
Inline: False
```
**Symbols:**

```
ffffffff81b93db0-ffffffff81b94058: icmp_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void icmp_reply(struct icmp_bxm *icmp_param, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81d251e0)
Location: net/ipv4/icmp.c:394
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_timestamp
  - net/ipv4/icmp.c:icmp_echo
```
**Symbols:**

```
ffffffff81d251e0-ffffffff81d2551a: icmp_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void icmp_reply(struct icmp_bxm *icmp_param, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81eec7d0)
Location: net/ipv4/icmp.c:394
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_timestamp
  - net/ipv4/icmp.c:icmp_echo
```
**Symbols:**

```
ffffffff81eec7d0-ffffffff81eecb0a: icmp_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void icmp_reply(struct icmp_bxm *icmp_param, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81f4b3c0)
Location: net/ipv4/icmp.c:397
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_timestamp
  - net/ipv4/icmp.c:icmp_echo
```
**Symbols:**

```
ffffffff81f4b3c0-ffffffff81f4b709: icmp_reply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void icmp_reply(struct icmp_bxm *icmp_param, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff820114d0)
Location: net/ipv4/icmp.c:397
Inline: False
Direct callers:
  - net/ipv4/icmp.c:icmp_timestamp
  - net/ipv4/icmp.c:icmp_echo
```
**Symbols:**

```
ffffffff820114d0-ffffffff82011819: icmp_reply (STB_LOCAL)
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
In net/ipv4/icmp.c (ffff800010ca4230)
Location: net/ipv4/icmp.c:398
Inline: True
```
**Symbols:**

```
ffff800010ca4230-ffff800010ca44b4: icmp_reply.constprop.0 (STB_LOCAL)
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
In net/ipv4/icmp.c (c0db0ec8)
Location: net/ipv4/icmp.c:398
Inline: True
```
**Symbols:**

```
c0db0ec8-c0db1134: icmp_reply.constprop.0 (STB_LOCAL)
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
In net/ipv4/icmp.c (c000000000db8550)
Location: net/ipv4/icmp.c:398
Inline: True
```
**Symbols:**

```
c000000000db8550-c000000000db887c: icmp_reply.constprop.0 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffe0008000c0)
Location: net/ipv4/icmp.c:398
Inline: True
```
**Symbols:**

```
ffffffe0008000c0-ffffffe000800304: icmp_reply.constprop.0 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff8198e9a0)
Location: net/ipv4/icmp.c:398
Inline: True
```
**Symbols:**

```
ffffffff8198e9a0-ffffffff8198ec40: icmp_reply.constprop.0 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff81948460)
Location: net/ipv4/icmp.c:398
Inline: True
```
**Symbols:**

```
ffffffff81948460-ffffffff81948700: icmp_reply.constprop.0 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff819f9240)
Location: net/ipv4/icmp.c:398
Inline: True
```
**Symbols:**

```
ffffffff819f9240-ffffffff819f94e0: icmp_reply.constprop.0 (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff81a031d0)
Location: net/ipv4/icmp.c:398
Inline: True
```
**Symbols:**

```
ffffffff81a031d0-ffffffff81a0348a: icmp_reply.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
