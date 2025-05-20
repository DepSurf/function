# Function: <code>skb_checksum_setup_ipv6</code>

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
In net/core/skbuff.c (ffffffff817095c7)
Location: net/core/skbuff.c:3963
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
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
In net/core/skbuff.c (ffffffff81771567)
Location: net/core/skbuff.c:4004
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
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
In net/core/skbuff.c (ffffffff8179e687)
Location: net/core/skbuff.c:4048
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
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
In net/core/skbuff.c (ffffffff817bc2d7)
Location: net/core/skbuff.c:4142
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
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
In net/core/skbuff.c (ffffffff818369a7)
Location: net/core/skbuff.c:4530
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
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
In net/core/skbuff.c (ffffffff81880ab7)
Location: net/core/skbuff.c:4569
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
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
In net/core/skbuff.c (ffffffff818a1967)
Location: net/core/skbuff.c:4591
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
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
In net/core/skbuff.c (ffffffff818ec357)
Location: net/core/skbuff.c:4776
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
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
In net/core/skbuff.c (ffffffff8191e487)
Location: net/core/skbuff.c:4788
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int skb_checksum_setup_ipv6(struct sk_buff *skb, bool recalculate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f1af0)
Location: net/core/skbuff.c:4890
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup
```
**Symbols:**

```
ffffffff819f1af0-ffffffff819f1dc8: skb_checksum_setup_ipv6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int skb_checksum_setup_ipv6(struct sk_buff *skb, bool recalculate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f1790)
Location: net/core/skbuff.c:4957
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup
```
**Symbols:**

```
ffffffff819f1790-ffffffff819f1a68: skb_checksum_setup_ipv6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int skb_checksum_setup_ipv6(struct sk_buff *skb, bool recalculate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d6a20)
Location: net/core/skbuff.c:5045
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup
```
**Symbols:**

```
ffffffff819d6a20-ffffffff819d6cee: skb_checksum_setup_ipv6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int skb_checksum_setup_ipv6(struct sk_buff *skb, bool recalculate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a87070)
Location: net/core/skbuff.c:5113
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup
```
**Symbols:**

```
ffffffff81a87070-ffffffff81a8733e: skb_checksum_setup_ipv6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int skb_checksum_setup_ipv6(struct sk_buff *skb, bool recalculate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bfc820)
Location: net/core/skbuff.c:5027
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup
```
**Symbols:**

```
ffffffff81bfc820-ffffffff81bfcaf0: skb_checksum_setup_ipv6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int skb_checksum_setup_ipv6(struct sk_buff *skb, bool recalculate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81dab740)
Location: net/core/skbuff.c:5229
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup
```
**Symbols:**

```
ffffffff81dab740-ffffffff81daba10: skb_checksum_setup_ipv6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int skb_checksum_setup_ipv6(struct sk_buff *skb, bool recalculate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e1b240)
Location: net/core/skbuff.c:5427
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup
```
**Symbols:**

```
ffffffff81e1b240-ffffffff81e1b50c: skb_checksum_setup_ipv6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int skb_checksum_setup_ipv6(struct sk_buff *skb, bool recalculate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed8800)
Location: net/core/skbuff.c:5558
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup
```
**Symbols:**

```
ffffffff81ed8800-ffffffff81ed8acc: skb_checksum_setup_ipv6 (STB_LOCAL)
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
In net/core/skbuff.c (ffff800010bb8bf8)
Location: net/core/skbuff.c:4788
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
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
In net/core/skbuff.c (c0cd56b4)
Location: net/core/skbuff.c:4788
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
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
In net/core/skbuff.c (c000000000c90fac)
Location: net/core/skbuff.c:4788
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
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
In net/core/skbuff.c (ffffffe0007482c0)
Location: net/core/skbuff.c:4788
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
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
In net/core/skbuff.c (ffffffff818be487)
Location: net/core/skbuff.c:4788
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
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
In net/core/skbuff.c (ffffffff818783c7)
Location: net/core/skbuff.c:4788
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
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
In net/core/skbuff.c (ffffffff8190f487)
Location: net/core/skbuff.c:4788
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
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
In net/core/skbuff.c (ffffffff819305b7)
Location: net/core/skbuff.c:4788
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
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
