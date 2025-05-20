# Function: <code>ip_mc_check_iphdr</code>

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
In net/ipv4/igmp.c (ffffffff81797dd3)
Location: net/ipv4/igmp.c:1363
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
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
In net/ipv4/igmp.c (ffffffff8180577a)
Location: net/ipv4/igmp.c:1369
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
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
In net/ipv4/igmp.c (ffffffff81836bca)
Location: net/ipv4/igmp.c:1400
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
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
In net/ipv4/igmp.c (ffffffff81857c2a)
Location: net/ipv4/igmp.c:1409
Inline: True
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
In net/ipv4/igmp.c (ffffffff818d73ea)
Location: net/ipv4/igmp.c:1437
Inline: True
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
In net/ipv4/igmp.c (ffffffff8192dd25)
Location: net/ipv4/igmp.c:1448
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
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
In net/ipv4/igmp.c (ffffffff8195d5f5)
Location: net/ipv4/igmp.c:1457
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
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
In net/ipv4/igmp.c (ffffffff819c2265)
Location: net/ipv4/igmp.c:1482
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
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
In net/ipv4/igmp.c (ffffffff819f8e05)
Location: net/ipv4/igmp.c:1482
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip_mc_check_iphdr(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ae6810)
Location: net/ipv4/igmp.c:1480
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
**Symbols:**

```
ffffffff81ae6810-ffffffff81ae6964: ip_mc_check_iphdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip_mc_check_iphdr(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81af36e0)
Location: net/ipv4/igmp.c:1480
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
**Symbols:**

```
ffffffff81af36e0-ffffffff81af3834: ip_mc_check_iphdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81adf245)
Location: net/ipv4/igmp.c:1487
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81b9e725)
Location: net/ipv4/igmp.c:1487
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81d30a95)
Location: net/ipv4/igmp.c:1494
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ef8ba5)
Location: net/ipv4/igmp.c:1494
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81f58615)
Location: net/ipv4/igmp.c:1495
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8201ead5)
Location: net/ipv4/igmp.c:1497
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
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
In net/ipv4/igmp.c (ffff800010cae5ec)
Location: net/ipv4/igmp.c:1482
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
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
In net/ipv4/igmp.c (c0dbc8e8)
Location: net/ipv4/igmp.c:1482
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
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
In net/ipv4/igmp.c (c000000000dc69bc)
Location: net/ipv4/igmp.c:1482
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
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
In net/ipv4/igmp.c (ffffffe0008099b8)
Location: net/ipv4/igmp.c:1482
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
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
In net/ipv4/igmp.c (ffffffff81998ba5)
Location: net/ipv4/igmp.c:1482
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
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
In net/ipv4/igmp.c (ffffffff81952665)
Location: net/ipv4/igmp.c:1482
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
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
In net/ipv4/igmp.c (ffffffff81a03445)
Location: net/ipv4/igmp.c:1482
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
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
In net/ipv4/igmp.c (ffffffff81a0d995)
Location: net/ipv4/igmp.c:1482
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
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
