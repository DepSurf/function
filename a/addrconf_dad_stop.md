# Function: <code>addrconf_dad_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void addrconf_dad_stop(struct inet6_ifaddr *ifp, int dad_failed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817cec40)
Location: net/ipv6/addrconf.c:1773
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff817cec40-ffffffff817ced36: addrconf_dad_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void addrconf_dad_stop(struct inet6_ifaddr *ifp, int dad_failed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8183c300)
Location: net/ipv6/addrconf.c:1835
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff8183c300-ffffffff8183c3fb: addrconf_dad_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void addrconf_dad_stop(struct inet6_ifaddr *ifp, int dad_failed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8186ddc0)
Location: net/ipv6/addrconf.c:1883
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff8186ddc0-ffffffff8186debb: addrconf_dad_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void addrconf_dad_stop(struct inet6_ifaddr *ifp, int dad_failed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81892bc0)
Location: net/ipv6/addrconf.c:1925
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff81892bc0-ffffffff81892cbf: addrconf_dad_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void addrconf_dad_stop(struct inet6_ifaddr *ifp, int dad_failed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81913e10)
Location: net/ipv6/addrconf.c:1949
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff81913e10-ffffffff81913f2a: addrconf_dad_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void addrconf_dad_stop(struct inet6_ifaddr *ifp, int dad_failed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8196b3f0)
Location: net/ipv6/addrconf.c:1970
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff8196b3f0-ffffffff8196b51f: addrconf_dad_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void addrconf_dad_stop(struct inet6_ifaddr *ifp, int dad_failed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819a0e70)
Location: net/ipv6/addrconf.c:1986
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff819a0e70-ffffffff819a0f9f: addrconf_dad_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void addrconf_dad_stop(struct inet6_ifaddr *ifp, int dad_failed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a0d050)
Location: net/ipv6/addrconf.c:2019
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff81a0d050-ffffffff81a0d183: addrconf_dad_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void addrconf_dad_stop(struct inet6_ifaddr *ifp, int dad_failed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a43d30)
Location: net/ipv6/addrconf.c:2021
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff81a43d30-ffffffff81a43e63: addrconf_dad_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void addrconf_dad_stop(struct inet6_ifaddr *ifp, int dad_failed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b3b630)
Location: net/ipv6/addrconf.c:2012
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_begin
```
**Symbols:**

```
ffffffff81b3b630-ffffffff81b3b828: addrconf_dad_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void addrconf_dad_stop(struct inet6_ifaddr *ifp, int dad_failed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b4a340)
Location: net/ipv6/addrconf.c:2038
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_begin
```
**Symbols:**

```
ffffffff81b4a340-ffffffff81b4a538: addrconf_dad_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void addrconf_dad_stop(struct inet6_ifaddr *ifp, int dad_failed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b37ef0)
Location: net/ipv6/addrconf.c:2040
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_begin
```
**Symbols:**

```
ffffffff81b37ef0-ffffffff81b380b5: addrconf_dad_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void addrconf_dad_stop(struct inet6_ifaddr *ifp, int dad_failed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81bfe6f0)
Location: net/ipv6/addrconf.c:2047
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_begin
```
**Symbols:**

```
ffffffff81bfe6f0-ffffffff81bfe8b5: addrconf_dad_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void addrconf_dad_stop(struct inet6_ifaddr *ifp, int dad_failed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d98100)
Location: net/ipv6/addrconf.c:2050
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff81d98100-ffffffff81d982ed: addrconf_dad_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void addrconf_dad_stop(struct inet6_ifaddr *ifp, int dad_failed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f66d90)
Location: net/ipv6/addrconf.c:2050
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff81f66d90-ffffffff81f66f7d: addrconf_dad_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void addrconf_dad_stop(struct inet6_ifaddr *ifp, int dad_failed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fc6ea0)
Location: net/ipv6/addrconf.c:2049
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff81fc6ea0-ffffffff81fc7088: addrconf_dad_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void addrconf_dad_stop(struct inet6_ifaddr *ifp, int dad_failed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff820945c0)
Location: net/ipv6/addrconf.c:2077
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff820945c0-ffffffff820947a8: addrconf_dad_stop (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void addrconf_dad_stop(struct inet6_ifaddr *ifp, int dad_failed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010d05d98)
Location: net/ipv6/addrconf.c:2021
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffff800010d05d98-ffff800010d05fa0: addrconf_dad_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void addrconf_dad_stop(struct inet6_ifaddr *ifp, int dad_failed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e0cc28)
Location: net/ipv6/addrconf.c:2021
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
c0e0cc28-c0e0cd68: addrconf_dad_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void addrconf_dad_stop(struct inet6_ifaddr *ifp, int dad_failed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e2fe50)
Location: net/ipv6/addrconf.c:2021
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
c000000000e2fe50-c000000000e300b8: addrconf_dad_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void addrconf_dad_stop(struct inet6_ifaddr *ifp, int dad_failed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe00084e29c)
Location: net/ipv6/addrconf.c:2021
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffe00084e29c-ffffffe00084e420: addrconf_dad_stop (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void addrconf_dad_stop(struct inet6_ifaddr *ifp, int dad_failed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819e33c0)
Location: net/ipv6/addrconf.c:2021
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff819e33c0-ffffffff819e34f3: addrconf_dad_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void addrconf_dad_stop(struct inet6_ifaddr *ifp, int dad_failed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819a0180)
Location: net/ipv6/addrconf.c:2021
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff819a0180-ffffffff819a02b3: addrconf_dad_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void addrconf_dad_stop(struct inet6_ifaddr *ifp, int dad_failed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a4de40)
Location: net/ipv6/addrconf.c:2021
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff81a4de40-ffffffff81a4df73: addrconf_dad_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void addrconf_dad_stop(struct inet6_ifaddr *ifp, int dad_failed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a59db0)
Location: net/ipv6/addrconf.c:2021
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
**Symbols:**

```
ffffffff81a59db0-ffffffff81a59ee3: addrconf_dad_stop (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
