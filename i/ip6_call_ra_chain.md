# Function: <code>ip6_call_ra_chain</code>

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
In net/ipv6/ip6_output.c (ffffffff817c6f48)
Location: net/ipv6/ip6_output.c:251
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv6/ip6_output.c (ffffffff81833ffc)
Location: net/ipv6/ip6_output.c:251
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv6/ip6_output.c (ffffffff81865a5c)
Location: net/ipv6/ip6_output.c:277
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv6/ip6_output.c (ffffffff8188a1e5)
Location: net/ipv6/ip6_output.c:278
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv6/ip6_output.c (ffffffff8190b3e7)
Location: net/ipv6/ip6_output.c:294
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv6/ip6_output.c (ffffffff819628ab)
Location: net/ipv6/ip6_output.c:292
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv6/ip6_output.c (ffffffff819978a6)
Location: net/ipv6/ip6_output.c:292
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv6/ip6_output.c (ffffffff81a03903)
Location: net/ipv6/ip6_output.c:296
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv6/ip6_output.c (ffffffff81a3a4d3)
Location: net/ipv6/ip6_output.c:296
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip6_call_ra_chain(struct sk_buff *skb, int sel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b2cf00)
Location: net/ipv6/ip6_output.c:297
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff81b2cf00-ffffffff81b2d02f: ip6_call_ra_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip6_call_ra_chain(struct sk_buff *skb, int sel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b3b910)
Location: net/ipv6/ip6_output.c:336
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff81b3b910-ffffffff81b3ba3f: ip6_call_ra_chain (STB_LOCAL)
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
In net/ipv6/ip6_output.c (ffffffff81b2cf79)
Location: net/ipv6/ip6_output.c:365
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv6/ip6_output.c (ffffffff81bf3115)
Location: net/ipv6/ip6_output.c:341
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv6/ip6_output.c (ffffffff81d8bcd7)
Location: net/ipv6/ip6_output.c:360
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv6/ip6_output.c (ffffffff81f59c69)
Location: net/ipv6/ip6_output.c:360
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv6/ip6_output.c (ffffffff81fb991b)
Location: net/ipv6/ip6_output.c:361
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv6/ip6_output.c (ffffffff82086e5c)
Location: net/ipv6/ip6_output.c:375
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv6/ip6_output.c (ffff800010cfb4ac)
Location: net/ipv6/ip6_output.c:296
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv6/ip6_output.c (c0e020f0)
Location: net/ipv6/ip6_output.c:296
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv6/ip6_output.c (c000000000e22b20)
Location: net/ipv6/ip6_output.c:296
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv6/ip6_output.c (ffffffe000845f6a)
Location: net/ipv6/ip6_output.c:296
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv6/ip6_output.c (ffffffff819d9b63)
Location: net/ipv6/ip6_output.c:296
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv6/ip6_output.c (ffffffff81996923)
Location: net/ipv6/ip6_output.c:296
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv6/ip6_output.c (ffffffff81a445e3)
Location: net/ipv6/ip6_output.c:296
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
In net/ipv6/ip6_output.c (ffffffff81a502a5)
Location: net/ipv6/ip6_output.c:296
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
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
