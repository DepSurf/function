# Function: <code>change_mtu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int change_mtu(struct net_device *dev, long unsigned int new_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81735b30)
Location: net/core/net-sysfs.c:296
Inline: False
```
**Symbols:**

```
ffffffff81735b30-ffffffff81735b40: change_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int change_mtu(struct net_device *dev, long unsigned int new_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff817a1ce0)
Location: net/core/net-sysfs.c:299
Inline: False
```
**Symbols:**

```
ffffffff817a1ce0-ffffffff817a1cf0: change_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int change_mtu(struct net_device *dev, long unsigned int new_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff817d0600)
Location: net/core/net-sysfs.c:299
Inline: False
```
**Symbols:**

```
ffffffff817d0600-ffffffff817d0610: change_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int change_mtu(struct net_device *dev, long unsigned int new_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff817ef9f0)
Location: net/core/net-sysfs.c:300
Inline: False
```
**Symbols:**

```
ffffffff817ef9f0-ffffffff817efa00: change_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int change_mtu(struct net_device *dev, long unsigned int new_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff8186af90)
Location: net/core/net-sysfs.c:304
Inline: False
```
**Symbols:**

```
ffffffff8186af90-ffffffff8186afa0: change_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int change_mtu(struct net_device *dev, long unsigned int new_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff818bb840)
Location: net/core/net-sysfs.c:325
Inline: False
```
**Symbols:**

```
ffffffff818bb840-ffffffff818bb850: change_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int change_mtu(struct net_device *dev, long unsigned int new_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff818e2910)
Location: net/core/net-sysfs.c:326
Inline: False
```
**Symbols:**

```
ffffffff818e2910-ffffffff818e2920: change_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int change_mtu(struct net_device *dev, long unsigned int new_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81931ef0)
Location: net/core/net-sysfs.c:321
Inline: False
```
**Symbols:**

```
ffffffff81931ef0-ffffffff81931f00: change_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int change_mtu(struct net_device *dev, long unsigned int new_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81964a30)
Location: net/core/net-sysfs.c:321
Inline: False
```
**Symbols:**

```
ffffffff81964a30-ffffffff81964a40: change_mtu (STB_LOCAL)
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
In net/core/net-sysfs.c (ffffffff81a398c3)
Location: net/core/net-sysfs.c:333
Inline: True
Inline callers:
  - net/core/net-sysfs.c:mtu_store
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
In net/core/net-sysfs.c (ffffffff81a3bb73)
Location: net/core/net-sysfs.c:334
Inline: True
Inline callers:
  - net/core/net-sysfs.c:mtu_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int change_mtu(struct net_device *dev, long unsigned int new_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81a20c70)
Location: net/core/net-sysfs.c:334
Inline: False
```
**Symbols:**

```
ffffffff81a20c70-ffffffff81a20c80: change_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int change_mtu(struct net_device *dev, long unsigned int new_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81ad50f0)
Location: net/core/net-sysfs.c:354
Inline: False
```
**Symbols:**

```
ffffffff81ad50f0-ffffffff81ad5100: change_mtu (STB_LOCAL)
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
In net/core/net-sysfs.c (ffffffff81c57df6)
Location: net/core/net-sysfs.c:356
Inline: True
Inline callers:
  - net/core/net-sysfs.c:mtu_store
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
In net/core/net-sysfs.c (ffffffff81e0dbf6)
Location: net/core/net-sysfs.c:356
Inline: True
Inline callers:
  - net/core/net-sysfs.c:mtu_store
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
In net/core/net-sysfs.c (ffffffff81e80e46)
Location: net/core/net-sysfs.c:356
Inline: True
Inline callers:
  - net/core/net-sysfs.c:mtu_store
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
In net/core/net-sysfs.c (ffffffff81f41e09)
Location: net/core/net-sysfs.c:368
Inline: True
Inline callers:
  - net/core/net-sysfs.c:mtu_store
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
int change_mtu(struct net_device *dev, long unsigned int new_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffff800010c09568)
Location: net/core/net-sysfs.c:321
Inline: False
```
**Symbols:**

```
ffff800010c09568-ffff800010c0959c: change_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int change_mtu(struct net_device *dev, long unsigned int new_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (c0d22354)
Location: net/core/net-sysfs.c:321
Inline: False
```
**Symbols:**

```
c0d22354-c0d22370: change_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int change_mtu(struct net_device *dev, long unsigned int new_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (c000000000cf4230)
Location: net/core/net-sysfs.c:321
Inline: False
```
**Symbols:**

```
c000000000cf4230-c000000000cf4268: change_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int change_mtu(struct net_device *dev, long unsigned int new_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffe0007873f6)
Location: net/core/net-sysfs.c:321
Inline: False
```
**Symbols:**

```
ffffffe0007873f6-ffffffe00078742a: change_mtu (STB_LOCAL)
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
int change_mtu(struct net_device *dev, long unsigned int new_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81904a00)
Location: net/core/net-sysfs.c:321
Inline: False
```
**Symbols:**

```
ffffffff81904a00-ffffffff81904a10: change_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int change_mtu(struct net_device *dev, long unsigned int new_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff818be830)
Location: net/core/net-sysfs.c:321
Inline: False
```
**Symbols:**

```
ffffffff818be830-ffffffff818be840: change_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int change_mtu(struct net_device *dev, long unsigned int new_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81955a30)
Location: net/core/net-sysfs.c:321
Inline: False
```
**Symbols:**

```
ffffffff81955a30-ffffffff81955a40: change_mtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int change_mtu(struct net_device *dev, long unsigned int new_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81977a90)
Location: net/core/net-sysfs.c:321
Inline: False
```
**Symbols:**

```
ffffffff81977a90-ffffffff81977aa0: change_mtu (STB_LOCAL)
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
