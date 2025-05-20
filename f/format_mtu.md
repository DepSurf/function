# Function: <code>format_mtu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t format_mtu(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81735660)
Location: net/core/net-sysfs.c:306
Inline: False
```
**Symbols:**

```
ffffffff81735660-ffffffff81735685: format_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t format_mtu(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff817a17b0)
Location: net/core/net-sysfs.c:309
Inline: False
```
**Symbols:**

```
ffffffff817a17b0-ffffffff817a17d5: format_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t format_mtu(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff817d00d0)
Location: net/core/net-sysfs.c:309
Inline: False
```
**Symbols:**

```
ffffffff817d00d0-ffffffff817d00f5: format_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t format_mtu(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff817ef4d0)
Location: net/core/net-sysfs.c:310
Inline: False
```
**Symbols:**

```
ffffffff817ef4d0-ffffffff817ef4f5: format_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t format_mtu(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff8186aa70)
Location: net/core/net-sysfs.c:314
Inline: False
```
**Symbols:**

```
ffffffff8186aa70-ffffffff8186aa95: format_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t format_mtu(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff818bb310)
Location: net/core/net-sysfs.c:335
Inline: False
```
**Symbols:**

```
ffffffff818bb310-ffffffff818bb335: format_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t format_mtu(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff818e2400)
Location: net/core/net-sysfs.c:336
Inline: False
```
**Symbols:**

```
ffffffff818e2400-ffffffff818e2425: format_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t format_mtu(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff819319f0)
Location: net/core/net-sysfs.c:331
Inline: False
```
**Symbols:**

```
ffffffff819319f0-ffffffff81931a16: format_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t format_mtu(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81964530)
Location: net/core/net-sysfs.c:331
Inline: False
```
**Symbols:**

```
ffffffff81964530-ffffffff81964556: format_mtu (STB_LOCAL)
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
In net/core/net-sysfs.c (ffffffff81a38dd4)
Location: net/core/net-sysfs.c:343
Inline: True
Inline callers:
  - net/core/net-sysfs.c:mtu_show
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
In net/core/net-sysfs.c (ffffffff81a3aea4)
Location: net/core/net-sysfs.c:344
Inline: True
Inline callers:
  - net/core/net-sysfs.c:mtu_show
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
In net/core/net-sysfs.c (ffffffff81a22684)
Location: net/core/net-sysfs.c:344
Inline: True
Inline callers:
  - net/core/net-sysfs.c:mtu_show
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
In net/core/net-sysfs.c (ffffffff81ad6564)
Location: net/core/net-sysfs.c:364
Inline: True
Inline callers:
  - net/core/net-sysfs.c:mtu_show
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
In net/core/net-sysfs.c (ffffffff81c568a4)
Location: net/core/net-sysfs.c:366
Inline: True
Inline callers:
  - net/core/net-sysfs.c:mtu_show
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
In net/core/net-sysfs.c (ffffffff81e0c824)
Location: net/core/net-sysfs.c:366
Inline: True
Inline callers:
  - net/core/net-sysfs.c:mtu_show
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
In net/core/net-sysfs.c (ffffffff81e7f874)
Location: net/core/net-sysfs.c:366
Inline: True
Inline callers:
  - net/core/net-sysfs.c:mtu_show
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
In net/core/net-sysfs.c (ffffffff81f407f4)
Location: net/core/net-sysfs.c:378
Inline: True
Inline callers:
  - net/core/net-sysfs.c:mtu_show
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
ssize_t format_mtu(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffff800010c08fa0)
Location: net/core/net-sysfs.c:331
Inline: False
```
**Symbols:**

```
ffff800010c08fa0-ffff800010c08fe0: format_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t format_mtu(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (c0d21ebc)
Location: net/core/net-sysfs.c:331
Inline: False
```
**Symbols:**

```
c0d21ebc-c0d21ee8: format_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t format_mtu(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (c000000000cf3a10)
Location: net/core/net-sysfs.c:331
Inline: False
```
**Symbols:**

```
c000000000cf3a10-c000000000cf3a58: format_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t format_mtu(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffe000786c68)
Location: net/core/net-sysfs.c:331
Inline: False
```
**Symbols:**

```
ffffffe000786c68-ffffffe000786ca4: format_mtu (STB_LOCAL)
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
ssize_t format_mtu(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81904500)
Location: net/core/net-sysfs.c:331
Inline: False
```
**Symbols:**

```
ffffffff81904500-ffffffff81904526: format_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t format_mtu(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff818be330)
Location: net/core/net-sysfs.c:331
Inline: False
```
**Symbols:**

```
ffffffff818be330-ffffffff818be356: format_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t format_mtu(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81955530)
Location: net/core/net-sysfs.c:331
Inline: False
```
**Symbols:**

```
ffffffff81955530-ffffffff81955556: format_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t format_mtu(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff819775b0)
Location: net/core/net-sysfs.c:331
Inline: False
```
**Symbols:**

```
ffffffff819775b0-ffffffff819775d6: format_mtu (STB_LOCAL)
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
