# Function: <code>inet_ifa_byprefix</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct in_ifaddr *inet_ifa_byprefix(struct in_device *in_dev, __be32 prefix, __be32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff817921e0)
Location: net/ipv4/devinet.c:539
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
```
**Symbols:**

```
ffffffff817921e0-ffffffff81792257: inet_ifa_byprefix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct in_ifaddr *inet_ifa_byprefix(struct in_device *in_dev, __be32 prefix, __be32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff817feff0)
Location: net/ipv4/devinet.c:543
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
ffffffff817feff0-ffffffff817ff067: inet_ifa_byprefix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct in_ifaddr *inet_ifa_byprefix(struct in_device *in_dev, __be32 prefix, __be32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8182ff50)
Location: net/ipv4/devinet.c:543
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
ffffffff8182ff50-ffffffff8182ffc7: inet_ifa_byprefix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct in_ifaddr *inet_ifa_byprefix(struct in_device *in_dev, __be32 prefix, __be32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81851400)
Location: net/ipv4/devinet.c:562
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
ffffffff81851400-ffffffff81851477: inet_ifa_byprefix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct in_ifaddr *inet_ifa_byprefix(struct in_device *in_dev, __be32 prefix, __be32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff818d11d0)
Location: net/ipv4/devinet.c:569
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
ffffffff818d11d0-ffffffff818d1247: inet_ifa_byprefix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct in_ifaddr *inet_ifa_byprefix(struct in_device *in_dev, __be32 prefix, __be32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81927750)
Location: net/ipv4/devinet.c:570
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
ffffffff81927750-ffffffff819277d4: inet_ifa_byprefix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct in_ifaddr *inet_ifa_byprefix(struct in_device *in_dev, __be32 prefix, __be32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81956920)
Location: net/ipv4/devinet.c:580
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
ffffffff81956920-ffffffff819569a4: inet_ifa_byprefix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct in_ifaddr *inet_ifa_byprefix(struct in_device *in_dev, __be32 prefix, __be32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819bb350)
Location: net/ipv4/devinet.c:603
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
ffffffff819bb350-ffffffff819bb3c5: inet_ifa_byprefix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct in_ifaddr *inet_ifa_byprefix(struct in_device *in_dev, __be32 prefix, __be32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819f2040)
Location: net/ipv4/devinet.c:603
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
ffffffff819f2040-ffffffff819f20b5: inet_ifa_byprefix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct in_ifaddr *inet_ifa_byprefix(struct in_device *in_dev, __be32 prefix, __be32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ae0230)
Location: net/ipv4/devinet.c:604
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
ffffffff81ae0230-ffffffff81ae02a5: inet_ifa_byprefix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct in_ifaddr *inet_ifa_byprefix(struct in_device *in_dev, __be32 prefix, __be32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81aed0b0)
Location: net/ipv4/devinet.c:604
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
ffffffff81aed0b0-ffffffff81aed125: inet_ifa_byprefix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct in_ifaddr *inet_ifa_byprefix(struct in_device *in_dev, __be32 prefix, __be32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ad8890)
Location: net/ipv4/devinet.c:604
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
ffffffff81ad8890-ffffffff81ad8905: inet_ifa_byprefix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct in_ifaddr *inet_ifa_byprefix(struct in_device *in_dev, __be32 prefix, __be32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:604
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
ffffffff81d3c2d0-ffffffff81d3c2e5: inet_ifa_byprefix.cold (STB_LOCAL)
ffffffff81b97720-ffffffff81b977a8: inet_ifa_byprefix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct in_ifaddr *inet_ifa_byprefix(struct in_device *in_dev, __be32 prefix, __be32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:605
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
ffffffff81f08b14-ffffffff81f08b29: inet_ifa_byprefix.cold (STB_LOCAL)
ffffffff81d294b0-ffffffff81d29542: inet_ifa_byprefix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct in_ifaddr *inet_ifa_byprefix(struct in_device *in_dev, __be32 prefix, __be32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:606
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
ffffffff820b051a-ffffffff820b052f: inet_ifa_byprefix.cold (STB_LOCAL)
ffffffff81ef0e30-ffffffff81ef0ec2: inet_ifa_byprefix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct in_ifaddr *inet_ifa_byprefix(struct in_device *in_dev, __be32 prefix, __be32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:606
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
ffffffff821317c5-ffffffff821317da: inet_ifa_byprefix.cold (STB_LOCAL)
ffffffff81f508a0-ffffffff81f50932: inet_ifa_byprefix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct in_ifaddr *inet_ifa_byprefix(struct in_device *in_dev, __be32 prefix, __be32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:607
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
ffffffff82213189-ffffffff8221319e: inet_ifa_byprefix.cold (STB_LOCAL)
ffffffff82016b20-ffffffff82016bb2: inet_ifa_byprefix (STB_GLOBAL)
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
struct in_ifaddr *inet_ifa_byprefix(struct in_device *in_dev, __be32 prefix, __be32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffff800010ca82d8)
Location: net/ipv4/devinet.c:603
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
ffff800010ca82d8-ffff800010ca837c: inet_ifa_byprefix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct in_ifaddr *inet_ifa_byprefix(struct in_device *in_dev, __be32 prefix, __be32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c0db4a30)
Location: net/ipv4/devinet.c:603
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
c0db4a30-c0db4ae0: inet_ifa_byprefix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct in_ifaddr *inet_ifa_byprefix(struct in_device *in_dev, __be32 prefix, __be32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c000000000dbcd70)
Location: net/ipv4/devinet.c:603
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
c000000000dbcd70-c000000000dbce58: inet_ifa_byprefix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct in_ifaddr *inet_ifa_byprefix(struct in_device *in_dev, __be32 prefix, __be32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffe00080310c)
Location: net/ipv4/devinet.c:603
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
ffffffe00080310c-ffffffe000803194: inet_ifa_byprefix (STB_GLOBAL)
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
struct in_ifaddr *inet_ifa_byprefix(struct in_device *in_dev, __be32 prefix, __be32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81991de0)
Location: net/ipv4/devinet.c:603
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
ffffffff81991de0-ffffffff81991e55: inet_ifa_byprefix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct in_ifaddr *inet_ifa_byprefix(struct in_device *in_dev, __be32 prefix, __be32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8194b8a0)
Location: net/ipv4/devinet.c:603
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
ffffffff8194b8a0-ffffffff8194b915: inet_ifa_byprefix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct in_ifaddr *inet_ifa_byprefix(struct in_device *in_dev, __be32 prefix, __be32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819fc680)
Location: net/ipv4/devinet.c:603
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
ffffffff819fc680-ffffffff819fc6f5: inet_ifa_byprefix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct in_ifaddr *inet_ifa_byprefix(struct in_device *in_dev, __be32 prefix, __be32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81a06a10)
Location: net/ipv4/devinet.c:603
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
```
**Symbols:**

```
ffffffff81a06a10-ffffffff81a06a85: inet_ifa_byprefix (STB_GLOBAL)
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
