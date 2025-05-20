# Function: <code>build_sk_flow_key</code>

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
In net/ipv4/route.c (ffffffff81755373)
Location: net/ipv4/route.c:535
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
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
In net/ipv4/route.c (ffffffff817c1504)
Location: net/ipv4/route.c:541
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
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
In net/ipv4/route.c (ffffffff817f0a91)
Location: net/ipv4/route.c:544
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
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
In net/ipv4/route.c (ffffffff81810ede)
Location: net/ipv4/route.c:565
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
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
In net/ipv4/route.c (ffffffff818904be)
Location: net/ipv4/route.c:568
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
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
In net/ipv4/route.c (ffffffff818e3c4e)
Location: net/ipv4/route.c:551
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
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
In net/ipv4/route.c (ffffffff81910b2e)
Location: net/ipv4/route.c:551
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
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
In net/ipv4/route.c (ffffffff81972d73)
Location: net/ipv4/route.c:559
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
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
In net/ipv4/route.c (ffffffff819a96e3)
Location: net/ipv4/route.c:560
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void build_sk_flow_key(struct flowi4 *fl4, const struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a918c0)
Location: net/ipv4/route.c:559
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffffffff81a918c0-ffffffff81a91980: build_sk_flow_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void build_sk_flow_key(struct flowi4 *fl4, const struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a9b740)
Location: net/ipv4/route.c:559
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffffffff81a9b740-ffffffff81a9b805: build_sk_flow_key (STB_LOCAL)
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
In net/ipv4/route.c (ffffffff81a884e3)
Location: net/ipv4/route.c:542
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
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
In net/ipv4/route.c (ffffffff81b43ce3)
Location: net/ipv4/route.c:543
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
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
In net/ipv4/route.c (ffffffff81cd0803)
Location: net/ipv4/route.c:545
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
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
In net/ipv4/route.c (ffffffff81e909c3)
Location: net/ipv4/route.c:545
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
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
In net/ipv4/route.c (ffffffff81eef153)
Location: net/ipv4/route.c:545
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
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
In net/ipv4/route.c (ffffffff81fb32b2)
Location: net/ipv4/route.c:544
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
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
In net/ipv4/route.c (ffff800010c590f8)
Location: net/ipv4/route.c:560
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
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
In net/ipv4/route.c (c0d68e38)
Location: net/ipv4/route.c:560
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
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
In net/ipv4/route.c (c000000000d5afc0)
Location: net/ipv4/route.c:560
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
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
In net/ipv4/route.c (ffffffe0007c300e)
Location: net/ipv4/route.c:560
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
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
In net/ipv4/route.c (ffffffff81949553)
Location: net/ipv4/route.c:560
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
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
In net/ipv4/route.c (ffffffff81903043)
Location: net/ipv4/route.c:560
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
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
In net/ipv4/route.c (ffffffff819b3d23)
Location: net/ipv4/route.c:560
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
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
In net/ipv4/route.c (ffffffff819bd407)
Location: net/ipv4/route.c:560
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
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
