# Function: <code>raw_v4_input</code>

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
In net/ipv4/raw.c (ffffffff81785b95)
Location: net/ipv4/raw.c:168
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
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
In net/ipv4/raw.c (ffffffff817f31ae)
Location: net/ipv4/raw.c:170
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
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
In net/ipv4/raw.c (ffffffff81823f8e)
Location: net/ipv4/raw.c:172
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
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
In net/ipv4/raw.c (ffffffff81844c87)
Location: net/ipv4/raw.c:172
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
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
In net/ipv4/raw.c (ffffffff818c46b5)
Location: net/ipv4/raw.c:174
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
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
In net/ipv4/raw.c (ffffffff8191a377)
Location: net/ipv4/raw.c:174
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
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
In net/ipv4/raw.c (ffffffff81948bd7)
Location: net/ipv4/raw.c:173
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
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
In net/ipv4/raw.c (ffffffff819ad28e)
Location: net/ipv4/raw.c:169
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
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
In net/ipv4/raw.c (ffffffff819e3f4e)
Location: net/ipv4/raw.c:169
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int raw_v4_input(struct sk_buff *skb, const struct iphdr *iph, int hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81ad15f0)
Location: net/ipv4/raw.c:169
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_local_deliver
```
**Symbols:**

```
ffffffff81ad15f0-ffffffff81ad181a: raw_v4_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int raw_v4_input(struct sk_buff *skb, const struct iphdr *iph, int hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81add670)
Location: net/ipv4/raw.c:169
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_local_deliver
```
**Symbols:**

```
ffffffff81add670-ffffffff81add89a: raw_v4_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int raw_v4_input(struct sk_buff *skb, const struct iphdr *iph, int hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81ac8740)
Location: net/ipv4/raw.c:169
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_local_deliver
```
**Symbols:**

```
ffffffff81ac8740-ffffffff81ac896b: raw_v4_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int raw_v4_input(struct sk_buff *skb, const struct iphdr *iph, int hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81b86fa0)
Location: net/ipv4/raw.c:169
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_local_deliver
```
**Symbols:**

```
ffffffff81b86fa0-ffffffff81b871e9: raw_v4_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int raw_v4_input(struct sk_buff *skb, const struct iphdr *iph, int hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81d17c40)
Location: net/ipv4/raw.c:163
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_local_deliver
```
**Symbols:**

```
ffffffff81d17c40-ffffffff81d17ea2: raw_v4_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int raw_v4_input(struct sk_buff *skb, const struct iphdr *iph, int hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81ede4c0)
Location: net/ipv4/raw.c:163
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_local_deliver
```
**Symbols:**

```
ffffffff81ede4c0-ffffffff81ede722: raw_v4_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int raw_v4_input(struct net *net, struct sk_buff *skb, const struct iphdr *iph, int hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81f3d820)
Location: net/ipv4/raw.c:163
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_local_deliver
```
**Symbols:**

```
ffffffff81f3d820-ffffffff81f3da5b: raw_v4_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int raw_v4_input(struct net *net, struct sk_buff *skb, const struct iphdr *iph, int hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff82003930)
Location: net/ipv4/raw.c:163
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_local_deliver
```
**Symbols:**

```
ffffffff82003930-ffffffff82003b8e: raw_v4_input (STB_LOCAL)
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
In net/ipv4/raw.c (ffff800010c98924)
Location: net/ipv4/raw.c:169
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
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
In net/ipv4/raw.c (c0da6784)
Location: net/ipv4/raw.c:169
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
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
In net/ipv4/raw.c (c000000000daa0cc)
Location: net/ipv4/raw.c:169
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
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
In net/ipv4/raw.c (ffffffe0007f6a7e)
Location: net/ipv4/raw.c:169
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
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
In net/ipv4/raw.c (ffffffff81983dbe)
Location: net/ipv4/raw.c:169
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
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
In net/ipv4/raw.c (ffffffff8193d87e)
Location: net/ipv4/raw.c:169
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
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
In net/ipv4/raw.c (ffffffff819ee58e)
Location: net/ipv4/raw.c:169
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
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
In net/ipv4/raw.c (ffffffff819f85ee)
Location: net/ipv4/raw.c:169
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net *net</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, iph, hash</code> ➡️ <code>net, skb, iph, hash</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
