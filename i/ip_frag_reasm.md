# Function: <code>ip_frag_reasm</code>

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
In net/ipv4/ip_fragment.c (ffffffff81759f06)
Location: net/ipv4/ip_fragment.c:524
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
In net/ipv4/ip_fragment.c (ffffffff817c62ef)
Location: net/ipv4/ip_fragment.c:522
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
In net/ipv4/ip_fragment.c (ffffffff817f5def)
Location: net/ipv4/ip_fragment.c:522
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
In net/ipv4/ip_fragment.c (ffffffff81816207)
Location: net/ipv4/ip_fragment.c:531
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
In net/ipv4/ip_fragment.c (ffffffff818953c6)
Location: net/ipv4/ip_fragment.c:533
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
In net/ipv4/ip_fragment.c (ffffffff818e9536)
Location: net/ipv4/ip_fragment.c:474
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
In net/ipv4/ip_fragment.c (ffffffff8191663b)
Location: net/ipv4/ip_fragment.c:514
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
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
In net/ipv4/ip_fragment.c (ffffffff819785ee)
Location: net/ipv4/ip_fragment.c:402
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffff819aef5e)
Location: net/ipv4/ip_fragment.c:402
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ip_frag_reasm(struct ipq *qp, struct sk_buff *skb, struct sk_buff *prev_tail, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_fragment.c (0)
Location: net/ipv4/ip_fragment.c:402
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
**Symbols:**

```
ffffffff81a98980-ffffffff81a98b49: ip_frag_reasm (STB_LOCAL)
ffffffff81a9996d-ffffffff81a99988: ip_frag_reasm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ip_frag_reasm(struct ipq *qp, struct sk_buff *skb, struct sk_buff *prev_tail, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_fragment.c (0)
Location: net/ipv4/ip_fragment.c:402
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
**Symbols:**

```
ffffffff81aa28f0-ffffffff81aa2ab9: ip_frag_reasm (STB_LOCAL)
ffffffff81c32550-ffffffff81c3256b: ip_frag_reasm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_fragment.c (0)
Location: net/ipv4/ip_fragment.c:402
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
**Symbols:**

```
ffffffff81a8dc30-ffffffff81a8ddef: ip_frag_reasm.constprop.0 (STB_LOCAL)
ffffffff81c2483b-ffffffff81c24856: ip_frag_reasm.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_fragment.c (0)
Location: net/ipv4/ip_fragment.c:403
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
**Symbols:**

```
ffffffff81b48e00-ffffffff81b48fde: ip_frag_reasm.constprop.0 (STB_LOCAL)
ffffffff81d3a086-ffffffff81d3a0a1: ip_frag_reasm.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_fragment.c (0)
Location: net/ipv4/ip_fragment.c:404
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
**Symbols:**

```
ffffffff81cd6290-ffffffff81cd6476: ip_frag_reasm.constprop.0 (STB_LOCAL)
ffffffff81f0680e-ffffffff81f06823: ip_frag_reasm.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81e967b0)
Location: net/ipv4/ip_fragment.c:411
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
**Symbols:**

```
ffffffff81e967b0-ffffffff81e969a3: ip_frag_reasm.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81ef4fe0)
Location: net/ipv4/ip_fragment.c:411
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
**Symbols:**

```
ffffffff81ef4fe0-ffffffff81ef51d3: ip_frag_reasm.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81fb8f90)
Location: net/ipv4/ip_fragment.c:411
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
**Symbols:**

```
ffffffff81fb8f90-ffffffff81fb9183: ip_frag_reasm.constprop.0 (STB_LOCAL)
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
In net/ipv4/ip_fragment.c (ffff800010c5fb08)
Location: net/ipv4/ip_fragment.c:402
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
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
In net/ipv4/ip_fragment.c (c0d6ec60)
Location: net/ipv4/ip_fragment.c:402
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
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
In net/ipv4/ip_fragment.c (c000000000d6210c)
Location: net/ipv4/ip_fragment.c:402
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffe0007c78de)
Location: net/ipv4/ip_fragment.c:402
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffff8194edce)
Location: net/ipv4/ip_fragment.c:402
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffff819088be)
Location: net/ipv4/ip_fragment.c:402
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffff819b959e)
Location: net/ipv4/ip_fragment.c:402
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffff819c2e8e)
Location: net/ipv4/ip_fragment.c:402
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
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
</ul>
