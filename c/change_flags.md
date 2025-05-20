# Function: <code>change_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int change_flags(struct net_device *dev, long unsigned int new_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81735b20)
Location: net/core/net-sysfs.c:308
Inline: False
```
**Symbols:**

```
ffffffff81735b20-ffffffff81735b30: change_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int change_flags(struct net_device *dev, long unsigned int new_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff817a1cd0)
Location: net/core/net-sysfs.c:311
Inline: False
```
**Symbols:**

```
ffffffff817a1cd0-ffffffff817a1ce0: change_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int change_flags(struct net_device *dev, long unsigned int new_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff817d05f0)
Location: net/core/net-sysfs.c:311
Inline: False
```
**Symbols:**

```
ffffffff817d05f0-ffffffff817d0600: change_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int change_flags(struct net_device *dev, long unsigned int new_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff817ef9e0)
Location: net/core/net-sysfs.c:312
Inline: False
```
**Symbols:**

```
ffffffff817ef9e0-ffffffff817ef9f0: change_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int change_flags(struct net_device *dev, long unsigned int new_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff8186af80)
Location: net/core/net-sysfs.c:316
Inline: False
```
**Symbols:**

```
ffffffff8186af80-ffffffff8186af90: change_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int change_flags(struct net_device *dev, long unsigned int new_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff818bb830)
Location: net/core/net-sysfs.c:337
Inline: False
```
**Symbols:**

```
ffffffff818bb830-ffffffff818bb840: change_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int change_flags(struct net_device *dev, long unsigned int new_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff818e28f0)
Location: net/core/net-sysfs.c:338
Inline: False
```
**Symbols:**

```
ffffffff818e28f0-ffffffff818e2902: change_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int change_flags(struct net_device *dev, long unsigned int new_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81931ed0)
Location: net/core/net-sysfs.c:333
Inline: False
```
**Symbols:**

```
ffffffff81931ed0-ffffffff81931ee2: change_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int change_flags(struct net_device *dev, long unsigned int new_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81964a10)
Location: net/core/net-sysfs.c:333
Inline: False
```
**Symbols:**

```
ffffffff81964a10-ffffffff81964a22: change_flags (STB_LOCAL)
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
In net/core/net-sysfs.c (ffffffff81a39993)
Location: net/core/net-sysfs.c:345
Inline: True
Inline callers:
  - net/core/net-sysfs.c:flags_store
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
In net/core/net-sysfs.c (ffffffff81a3bc43)
Location: net/core/net-sysfs.c:346
Inline: True
Inline callers:
  - net/core/net-sysfs.c:flags_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int change_flags(struct net_device *dev, long unsigned int new_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81a20c50)
Location: net/core/net-sysfs.c:346
Inline: False
```
**Symbols:**

```
ffffffff81a20c50-ffffffff81a20c62: change_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int change_flags(struct net_device *dev, long unsigned int new_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81ad50d0)
Location: net/core/net-sysfs.c:366
Inline: False
```
**Symbols:**

```
ffffffff81ad50d0-ffffffff81ad50e2: change_flags (STB_LOCAL)
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
In net/core/net-sysfs.c (ffffffff81c57ed6)
Location: net/core/net-sysfs.c:368
Inline: True
Inline callers:
  - net/core/net-sysfs.c:flags_store
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
In net/core/net-sysfs.c (ffffffff81e0dde6)
Location: net/core/net-sysfs.c:368
Inline: True
Inline callers:
  - net/core/net-sysfs.c:flags_store
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
In net/core/net-sysfs.c (ffffffff81e81036)
Location: net/core/net-sysfs.c:368
Inline: True
Inline callers:
  - net/core/net-sysfs.c:flags_store
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
In net/core/net-sysfs.c (ffffffff81f41ef9)
Location: net/core/net-sysfs.c:380
Inline: True
Inline callers:
  - net/core/net-sysfs.c:flags_store
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
int change_flags(struct net_device *dev, long unsigned int new_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffff800010c09530)
Location: net/core/net-sysfs.c:333
Inline: False
```
**Symbols:**

```
ffff800010c09530-ffff800010c09568: change_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int change_flags(struct net_device *dev, long unsigned int new_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (c0d22334)
Location: net/core/net-sysfs.c:333
Inline: False
```
**Symbols:**

```
c0d22334-c0d22354: change_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int change_flags(struct net_device *dev, long unsigned int new_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (c000000000cf41f0)
Location: net/core/net-sysfs.c:333
Inline: False
```
**Symbols:**

```
c000000000cf41f0-c000000000cf422c: change_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int change_flags(struct net_device *dev, long unsigned int new_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffe0007873c0)
Location: net/core/net-sysfs.c:333
Inline: False
```
**Symbols:**

```
ffffffe0007873c0-ffffffe0007873f6: change_flags (STB_LOCAL)
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
int change_flags(struct net_device *dev, long unsigned int new_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff819049e0)
Location: net/core/net-sysfs.c:333
Inline: False
```
**Symbols:**

```
ffffffff819049e0-ffffffff819049f2: change_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int change_flags(struct net_device *dev, long unsigned int new_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff818be810)
Location: net/core/net-sysfs.c:333
Inline: False
```
**Symbols:**

```
ffffffff818be810-ffffffff818be822: change_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int change_flags(struct net_device *dev, long unsigned int new_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81955a10)
Location: net/core/net-sysfs.c:333
Inline: False
```
**Symbols:**

```
ffffffff81955a10-ffffffff81955a22: change_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int change_flags(struct net_device *dev, long unsigned int new_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81977a70)
Location: net/core/net-sysfs.c:333
Inline: False
```
**Symbols:**

```
ffffffff81977a70-ffffffff81977a82: change_flags (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
