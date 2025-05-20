# Function: <code>addrconf_set_sit_dstaddr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int addrconf_set_sit_dstaddr(struct net *net, struct net_device *dev, struct in6_ifreq *ireq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b32950)
Location: net/ipv6/addrconf.c:2786
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
```
**Symbols:**

```
ffffffff81b32950-ffffffff81b32a29: addrconf_set_sit_dstaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int addrconf_set_sit_dstaddr(struct net *net, struct net_device *dev, struct in6_ifreq *ireq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b41270)
Location: net/ipv6/addrconf.c:2813
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
```
**Symbols:**

```
ffffffff81b41270-ffffffff81b41349: addrconf_set_sit_dstaddr (STB_LOCAL)
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
In net/ipv6/addrconf.c (ffffffff81b3a13b)
Location: net/ipv6/addrconf.c:2815
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
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
In net/ipv6/addrconf.c (ffffffff81c008db)
Location: net/ipv6/addrconf.c:2835
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
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
In net/ipv6/addrconf.c (ffffffff81d9a4f1)
Location: net/ipv6/addrconf.c:2839
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
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
In net/ipv6/addrconf.c (ffffffff81f692f1)
Location: net/ipv6/addrconf.c:2839
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
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
In net/ipv6/addrconf.c (ffffffff81fc9361)
Location: net/ipv6/addrconf.c:2844
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
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
In net/ipv6/addrconf.c (ffffffff82096b01)
Location: net/ipv6/addrconf.c:2876
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
