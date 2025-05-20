# Function: <code>format_ifindex</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t format_ifindex(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff817358a0)
Location: net/core/net-sysfs.c:111
Inline: False
```
**Symbols:**

```
ffffffff817358a0-ffffffff817358c5: format_ifindex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t format_ifindex(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff817a19f0)
Location: net/core/net-sysfs.c:111
Inline: False
```
**Symbols:**

```
ffffffff817a19f0-ffffffff817a1a15: format_ifindex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t format_ifindex(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff817d0310)
Location: net/core/net-sysfs.c:111
Inline: False
```
**Symbols:**

```
ffffffff817d0310-ffffffff817d0335: format_ifindex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t format_ifindex(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff817ef5c0)
Location: net/core/net-sysfs.c:112
Inline: False
```
**Symbols:**

```
ffffffff817ef5c0-ffffffff817ef5e5: format_ifindex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t format_ifindex(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff8186ab60)
Location: net/core/net-sysfs.c:113
Inline: False
```
**Symbols:**

```
ffffffff8186ab60-ffffffff8186ab85: format_ifindex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t format_ifindex(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff818bb400)
Location: net/core/net-sysfs.c:113
Inline: False
```
**Symbols:**

```
ffffffff818bb400-ffffffff818bb425: format_ifindex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t format_ifindex(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff818e2630)
Location: net/core/net-sysfs.c:114
Inline: False
```
**Symbols:**

```
ffffffff818e2630-ffffffff818e2655: format_ifindex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t format_ifindex(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81931b10)
Location: net/core/net-sysfs.c:109
Inline: False
```
**Symbols:**

```
ffffffff81931b10-ffffffff81931b36: format_ifindex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t format_ifindex(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81964650)
Location: net/core/net-sysfs.c:109
Inline: False
```
**Symbols:**

```
ffffffff81964650-ffffffff81964676: format_ifindex (STB_LOCAL)
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
In net/core/net-sysfs.c (ffffffff81a39254)
Location: net/core/net-sysfs.c:109
Inline: True
Inline callers:
  - net/core/net-sysfs.c:ifindex_show
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
In net/core/net-sysfs.c (ffffffff81a3ad84)
Location: net/core/net-sysfs.c:110
Inline: True
Inline callers:
  - net/core/net-sysfs.c:ifindex_show
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
In net/core/net-sysfs.c (ffffffff81a22384)
Location: net/core/net-sysfs.c:110
Inline: True
Inline callers:
  - net/core/net-sysfs.c:ifindex_show
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
In net/core/net-sysfs.c (ffffffff81ad6884)
Location: net/core/net-sysfs.c:110
Inline: True
Inline callers:
  - net/core/net-sysfs.c:ifindex_show
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
In net/core/net-sysfs.c (ffffffff81c56bc4)
Location: net/core/net-sysfs.c:112
Inline: True
Inline callers:
  - net/core/net-sysfs.c:ifindex_show
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
In net/core/net-sysfs.c (ffffffff81e0c6a4)
Location: net/core/net-sysfs.c:112
Inline: True
Inline callers:
  - net/core/net-sysfs.c:ifindex_show
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
In net/core/net-sysfs.c (ffffffff81e7faf4)
Location: net/core/net-sysfs.c:112
Inline: True
Inline callers:
  - net/core/net-sysfs.c:ifindex_show
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
In net/core/net-sysfs.c (ffffffff81f40474)
Location: net/core/net-sysfs.c:113
Inline: True
Inline callers:
  - net/core/net-sysfs.c:ifindex_show
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
ssize_t format_ifindex(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffff800010c091e8)
Location: net/core/net-sysfs.c:109
Inline: False
```
**Symbols:**

```
ffff800010c091e8-ffff800010c09228: format_ifindex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t format_ifindex(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (c0d2206c)
Location: net/core/net-sysfs.c:109
Inline: False
```
**Symbols:**

```
c0d2206c-c0d22098: format_ifindex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t format_ifindex(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (c000000000cf3dd0)
Location: net/core/net-sysfs.c:109
Inline: False
```
**Symbols:**

```
c000000000cf3dd0-c000000000cf3e18: format_ifindex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t format_ifindex(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffe000786f12)
Location: net/core/net-sysfs.c:109
Inline: False
```
**Symbols:**

```
ffffffe000786f12-ffffffe000786f4e: format_ifindex (STB_LOCAL)
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
ssize_t format_ifindex(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81904620)
Location: net/core/net-sysfs.c:109
Inline: False
```
**Symbols:**

```
ffffffff81904620-ffffffff81904646: format_ifindex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t format_ifindex(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff818be450)
Location: net/core/net-sysfs.c:109
Inline: False
```
**Symbols:**

```
ffffffff818be450-ffffffff818be476: format_ifindex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t format_ifindex(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81955650)
Location: net/core/net-sysfs.c:109
Inline: False
```
**Symbols:**

```
ffffffff81955650-ffffffff81955676: format_ifindex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t format_ifindex(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff819776d0)
Location: net/core/net-sysfs.c:109
Inline: False
```
**Symbols:**

```
ffffffff819776d0-ffffffff819776f6: format_ifindex (STB_LOCAL)
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
