# Function: <code>ip6_forward_proxy_check</code>

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
In net/ipv6/ip6_output.c (ffffffff817c69a4)
Location: net/ipv6/ip6_output.c:280
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
In net/ipv6/ip6_output.c (ffffffff81833aa2)
Location: net/ipv6/ip6_output.c:280
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
In net/ipv6/ip6_output.c (ffffffff8186551c)
Location: net/ipv6/ip6_output.c:306
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
In net/ipv6/ip6_output.c (ffffffff81889cf2)
Location: net/ipv6/ip6_output.c:307
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
In net/ipv6/ip6_output.c (ffffffff8190aee4)
Location: net/ipv6/ip6_output.c:323
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
In net/ipv6/ip6_output.c (ffffffff819623e6)
Location: net/ipv6/ip6_output.c:321
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
In net/ipv6/ip6_output.c (ffffffff819973b3)
Location: net/ipv6/ip6_output.c:321
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
In net/ipv6/ip6_output.c (ffffffff81a03391)
Location: net/ipv6/ip6_output.c:331
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
In net/ipv6/ip6_output.c (ffffffff81a39f61)
Location: net/ipv6/ip6_output.c:331
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
int ip6_forward_proxy_check(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b2c530)
Location: net/ipv6/ip6_output.c:332
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff81b2c530-ffffffff81b2c6b1: ip6_forward_proxy_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip6_forward_proxy_check(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b3af40)
Location: net/ipv6/ip6_output.c:371
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff81b3af40-ffffffff81b3b0c1: ip6_forward_proxy_check (STB_LOCAL)
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
In net/ipv6/ip6_output.c (ffffffff81b2c971)
Location: net/ipv6/ip6_output.c:400
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
In net/ipv6/ip6_output.c (ffffffff81bf2abb)
Location: net/ipv6/ip6_output.c:376
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
In net/ipv6/ip6_output.c (ffffffff81d8b673)
Location: net/ipv6/ip6_output.c:395
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
In net/ipv6/ip6_output.c (ffffffff81f5969f)
Location: net/ipv6/ip6_output.c:395
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
In net/ipv6/ip6_output.c (ffffffff81fb9350)
Location: net/ipv6/ip6_output.c:396
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
In net/ipv6/ip6_output.c (ffffffff820868d0)
Location: net/ipv6/ip6_output.c:409
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
In net/ipv6/ip6_output.c (ffff800010cfaef8)
Location: net/ipv6/ip6_output.c:331
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
In net/ipv6/ip6_output.c (c0e01808)
Location: net/ipv6/ip6_output.c:331
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
In net/ipv6/ip6_output.c (c000000000e223a4)
Location: net/ipv6/ip6_output.c:331
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
In net/ipv6/ip6_output.c (ffffffe000845a84)
Location: net/ipv6/ip6_output.c:331
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
In net/ipv6/ip6_output.c (ffffffff819d95f1)
Location: net/ipv6/ip6_output.c:331
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
In net/ipv6/ip6_output.c (ffffffff819963b1)
Location: net/ipv6/ip6_output.c:331
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
In net/ipv6/ip6_output.c (ffffffff81a44071)
Location: net/ipv6/ip6_output.c:331
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
In net/ipv6/ip6_output.c (ffffffff81a4fd12)
Location: net/ipv6/ip6_output.c:331
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
