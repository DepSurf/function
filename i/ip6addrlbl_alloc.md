# Function: <code>ip6addrlbl_alloc</code>

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
In net/ipv6/addrlabel.c (ffffffff817d2872)
Location: net/ipv6/addrlabel.c:198
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In net/ipv6/addrlabel.c (ffffffff81840262)
Location: net/ipv6/addrlabel.c:198
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In net/ipv6/addrlabel.c (ffffffff81871ee2)
Location: net/ipv6/addrlabel.c:198
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In net/ipv6/addrlabel.c (ffffffff81896c42)
Location: net/ipv6/addrlabel.c:199
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In net/ipv6/addrlabel.c (ffffffff81918178)
Location: net/ipv6/addrlabel.c:160
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In net/ipv6/addrlabel.c (ffffffff8196f995)
Location: net/ipv6/addrlabel.c:160
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In net/ipv6/addrlabel.c (ffffffff819a55b5)
Location: net/ipv6/addrlabel.c:160
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In net/ipv6/addrlabel.c (ffffffff81a11b25)
Location: net/ipv6/addrlabel.c:160
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In net/ipv6/addrlabel.c (ffffffff81a48745)
Location: net/ipv6/addrlabel.c:160
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrlabel.c (ffffffff81b3ed75)
Location: net/ipv6/addrlabel.c:160
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrlabel.c (ffffffff81b4d79d)
Location: net/ipv6/addrlabel.c:160
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In net/ipv6/addrlabel.c (ffffffff81b3bb77)
Location: net/ipv6/addrlabel.c:160
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In net/ipv6/addrlabel.c (ffffffff81c023f7)
Location: net/ipv6/addrlabel.c:160
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct ip6addrlbl_entry *ip6addrlbl_alloc(const struct in6_addr *prefix, int prefixlen, int ifindex, u32 label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrlabel.c (0)
Location: net/ipv6/addrlabel.c:160
Inline: False
Direct callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
```
**Symbols:**

```
ffffffff81d9c2e0-ffffffff81d9c433: ip6addrlbl_alloc (STB_LOCAL)
ffffffff81f0c521-ffffffff81f0c52d: ip6addrlbl_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ip6addrlbl_entry *ip6addrlbl_alloc(const struct in6_addr *prefix, int prefixlen, int ifindex, u32 label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrlabel.c (ffffffff81f6afc0)
Location: net/ipv6/addrlabel.c:160
Inline: False
Direct callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
```
**Symbols:**

```
ffffffff81f6afc0-ffffffff81f6b11f: ip6addrlbl_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct ip6addrlbl_entry *ip6addrlbl_alloc(const struct in6_addr *prefix, int prefixlen, int ifindex, u32 label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrlabel.c (0)
Location: net/ipv6/addrlabel.c:160
Inline: False
Direct callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
```
**Symbols:**

```
ffffffff81fcaff0-ffffffff81fcb218: ip6addrlbl_alloc (STB_LOCAL)
ffffffff82134cd2-ffffffff82134cfd: ip6addrlbl_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct ip6addrlbl_entry *ip6addrlbl_alloc(const struct in6_addr *prefix, int prefixlen, int ifindex, u32 label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrlabel.c (0)
Location: net/ipv6/addrlabel.c:160
Inline: False
Direct callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
```
**Symbols:**

```
ffffffff82098790-ffffffff820989f3: ip6addrlbl_alloc (STB_LOCAL)
ffffffff82216796-ffffffff822167c1: ip6addrlbl_alloc.cold (STB_LOCAL)
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
In net/ipv6/addrlabel.c (ffff800010d0bb78)
Location: net/ipv6/addrlabel.c:160
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In net/ipv6/addrlabel.c (c0e11948)
Location: net/ipv6/addrlabel.c:160
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In net/ipv6/addrlabel.c (c000000000e36330)
Location: net/ipv6/addrlabel.c:160
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In net/ipv6/addrlabel.c (ffffffe000852b4a)
Location: net/ipv6/addrlabel.c:160
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In net/ipv6/addrlabel.c (ffffffff819e7dd5)
Location: net/ipv6/addrlabel.c:160
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In net/ipv6/addrlabel.c (ffffffff819a4b95)
Location: net/ipv6/addrlabel.c:160
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In net/ipv6/addrlabel.c (ffffffff81a52855)
Location: net/ipv6/addrlabel.c:160
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
In net/ipv6/addrlabel.c (ffffffff81a5e7e5)
Location: net/ipv6/addrlabel.c:160
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
