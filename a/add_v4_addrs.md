# Function: <code>add_v4_addrs</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void add_v4_addrs(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3109
Inline: False
```
**Symbols:**

```
ffffffff81bfb7a0-ffffffff81bfb9bc: add_v4_addrs (STB_LOCAL)
ffffffff81d3f921-ffffffff81d3f936: add_v4_addrs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void add_v4_addrs(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3114
Inline: False
```
**Symbols:**

```
ffffffff81d94fb0-ffffffff81d951ff: add_v4_addrs (STB_LOCAL)
ffffffff81f0c293-ffffffff81f0c2a7: add_v4_addrs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void add_v4_addrs(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3114
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init_auto_addrs
```
**Symbols:**

```
ffffffff81f637e0-ffffffff81f63a53: add_v4_addrs (STB_LOCAL)
ffffffff820b3a52-ffffffff820b3a66: add_v4_addrs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void add_v4_addrs(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3119
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init_auto_addrs
  - net/ipv6/addrconf.c:addrconf_init_auto_addrs
```
**Symbols:**

```
ffffffff81fc37a0-ffffffff81fc3a13: add_v4_addrs (STB_LOCAL)
ffffffff82134b43-ffffffff82134b57: add_v4_addrs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void add_v4_addrs(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3170
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init_auto_addrs
  - net/ipv6/addrconf.c:addrconf_init_auto_addrs
```
**Symbols:**

```
ffffffff82090d60-ffffffff82090fc7: add_v4_addrs (STB_LOCAL)
ffffffff82216607-ffffffff8221661b: add_v4_addrs.cold (STB_LOCAL)
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
