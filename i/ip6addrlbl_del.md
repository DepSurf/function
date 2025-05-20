# Function: <code>ip6addrlbl_del</code>

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
In net/ipv6/addrlabel.c (ffffffff817d2cc8)
Location: net/ipv6/addrlabel.c:331
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
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
In net/ipv6/addrlabel.c (ffffffff818406bf)
Location: net/ipv6/addrlabel.c:331
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
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
In net/ipv6/addrlabel.c (ffffffff8187233f)
Location: net/ipv6/addrlabel.c:331
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
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
In net/ipv6/addrlabel.c (ffffffff818970a7)
Location: net/ipv6/addrlabel.c:332
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
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
In net/ipv6/addrlabel.c (ffffffff819185e6)
Location: net/ipv6/addrlabel.c:289
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
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
In net/ipv6/addrlabel.c (ffffffff8196fe2c)
Location: net/ipv6/addrlabel.c:289
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
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
In net/ipv6/addrlabel.c (ffffffff819a5a4c)
Location: net/ipv6/addrlabel.c:289
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
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
In net/ipv6/addrlabel.c (ffffffff81a11fc1)
Location: net/ipv6/addrlabel.c:289
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
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
In net/ipv6/addrlabel.c (ffffffff81a48be1)
Location: net/ipv6/addrlabel.c:289
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip6addrlbl_del(struct net *net, const struct in6_addr *prefix, int prefixlen, int ifindex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrlabel.c (ffffffff81b3f5d0)
Location: net/ipv6/addrlabel.c:289
Inline: False
Direct callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
**Symbols:**

```
ffffffff81b3f5d0-ffffffff81b3f78a: ip6addrlbl_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip6addrlbl_del(struct net *net, const struct in6_addr *prefix, int prefixlen, int ifindex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrlabel.c (ffffffff81b4e070)
Location: net/ipv6/addrlabel.c:289
Inline: False
Direct callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
**Symbols:**

```
ffffffff81b4e070-ffffffff81b4e22a: ip6addrlbl_del (STB_LOCAL)
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
In net/ipv6/addrlabel.c (ffffffff81b3c053)
Location: net/ipv6/addrlabel.c:289
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
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
In net/ipv6/addrlabel.c (ffffffff81c02943)
Location: net/ipv6/addrlabel.c:289
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
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
In net/ipv6/addrlabel.c (ffffffff81d9c570)
Location: net/ipv6/addrlabel.c:289
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
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
In net/ipv6/addrlabel.c (ffffffff81f6b260)
Location: net/ipv6/addrlabel.c:289
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
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
In net/ipv6/addrlabel.c (ffffffff81fcb3fd)
Location: net/ipv6/addrlabel.c:289
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
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
In net/ipv6/addrlabel.c (ffffffff82098bdd)
Location: net/ipv6/addrlabel.c:289
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
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
In net/ipv6/addrlabel.c (ffff800010d0c00c)
Location: net/ipv6/addrlabel.c:289
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
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
In net/ipv6/addrlabel.c (c0e11dc0)
Location: net/ipv6/addrlabel.c:289
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
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
In net/ipv6/addrlabel.c (c000000000e36958)
Location: net/ipv6/addrlabel.c:289
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
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
In net/ipv6/addrlabel.c (ffffffe000852f02)
Location: net/ipv6/addrlabel.c:289
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
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
In net/ipv6/addrlabel.c (ffffffff819e8271)
Location: net/ipv6/addrlabel.c:289
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
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
In net/ipv6/addrlabel.c (ffffffff819a5031)
Location: net/ipv6/addrlabel.c:289
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
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
In net/ipv6/addrlabel.c (ffffffff81a52cf1)
Location: net/ipv6/addrlabel.c:289
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
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
In net/ipv6/addrlabel.c (ffffffff81a5ec6d)
Location: net/ipv6/addrlabel.c:289
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
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
