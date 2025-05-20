# Function: <code>ip_ipgre_mc_map</code>

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
In net/ipv4/arp.c (ffffffff8178d3bc)
Location: include/net/ip.h:445
Inline: True
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
In net/ipv4/arp.c (ffffffff817fa98c)
Location: include/net/ip.h:441
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_mc_map
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
In net/ipv4/arp.c (ffffffff8182b83c)
Location: include/net/ip.h:470
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_mc_map
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
In net/ipv4/arp.c (ffffffff8184cc28)
Location: include/net/ip.h:482
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
In net/ipv4/arp.c (ffffffff818cc8e8)
Location: include/net/ip.h:493
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
In net/ipv4/arp.c (ffffffff81922db8)
Location: include/net/ip.h:515
Inline: True
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
In net/ipv4/arp.c (ffffffff81951ba8)
Location: include/net/ip.h:567
Inline: True
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
In net/ipv4/arp.c (ffffffff819b6488)
Location: include/net/ip.h:605
Inline: True
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
In net/ipv4/arp.c (ffffffff819ed1a8)
Location: include/net/ip.h:606
Inline: True
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
In net/ipv4/arp.c (ffffffff81adb148)
Location: include/net/ip.h:606
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_mc_map
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
In net/ipv4/arp.c (ffffffff81ae7c18)
Location: include/net/ip.h:609
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_mc_map
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
In net/ipv4/arp.c (ffffffff81ad2edd)
Location: include/net/ip.h:613
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_mc_map
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
In net/ipv4/arp.c (ffffffff81b91b2d)
Location: include/net/ip.h:626
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_mc_map
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
In net/ipv4/arp.c (ffffffff81d22ff1)
Location: include/net/ip.h:623
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_mc_map
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ip_ipgre_mc_map(__be32 naddr, const unsigned char *broadcast, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81ee8950)
Location: include/net/ip.h:623
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_mc_map
```
**Symbols:**

```
ffffffff81ee8950-ffffffff81ee896f: ip_ipgre_mc_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ip_ipgre_mc_map(__be32 naddr, const unsigned char *broadcast, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81f48240)
Location: include/net/ip.h:643
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_mc_map
```
**Symbols:**

```
ffffffff81f48240-ffffffff81f4825f: ip_ipgre_mc_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ip_ipgre_mc_map(__be32 naddr, const unsigned char *broadcast, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff8200e3a0)
Location: include/net/ip.h:653
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_mc_map
```
**Symbols:**

```
ffffffff8200e3a0-ffffffff8200e3bf: ip_ipgre_mc_map (STB_LOCAL)
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
In net/ipv4/arp.c (ffff800010ca2c18)
Location: include/net/ip.h:606
Inline: True
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
In net/ipv4/arp.c (c0dafa80)
Location: include/net/ip.h:606
Inline: True
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
In net/ipv4/arp.c (c000000000db6404)
Location: include/net/ip.h:606
Inline: True
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
In net/ipv4/arp.c (ffffffe0007fede0)
Location: include/net/ip.h:606
Inline: True
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
In net/ipv4/arp.c (ffffffff8198cf48)
Location: include/net/ip.h:606
Inline: True
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
In net/ipv4/arp.c (ffffffff81946a08)
Location: include/net/ip.h:606
Inline: True
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
In net/ipv4/arp.c (ffffffff819f77e8)
Location: include/net/ip.h:606
Inline: True
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
In net/ipv4/arp.c (ffffffff81a01a18)
Location: include/net/ip.h:606
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
