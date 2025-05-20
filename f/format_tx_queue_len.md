# Function: <code>format_tx_queue_len</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t format_tx_queue_len(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81735600)
Location: net/core/net-sysfs.c:335
Inline: False
```
**Symbols:**

```
ffffffff81735600-ffffffff81735626: format_tx_queue_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t format_tx_queue_len(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff817a1750)
Location: net/core/net-sysfs.c:351
Inline: False
```
**Symbols:**

```
ffffffff817a1750-ffffffff817a1776: format_tx_queue_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t format_tx_queue_len(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff817d0070)
Location: net/core/net-sysfs.c:351
Inline: False
```
**Symbols:**

```
ffffffff817d0070-ffffffff817d0096: format_tx_queue_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t format_tx_queue_len(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff817ef470)
Location: net/core/net-sysfs.c:356
Inline: False
```
**Symbols:**

```
ffffffff817ef470-ffffffff817ef495: format_tx_queue_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t format_tx_queue_len(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff8186aa10)
Location: net/core/net-sysfs.c:360
Inline: False
```
**Symbols:**

```
ffffffff8186aa10-ffffffff8186aa35: format_tx_queue_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t format_tx_queue_len(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff818bb2b0)
Location: net/core/net-sysfs.c:358
Inline: False
```
**Symbols:**

```
ffffffff818bb2b0-ffffffff818bb2d5: format_tx_queue_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t format_tx_queue_len(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff818e23a0)
Location: net/core/net-sysfs.c:359
Inline: False
```
**Symbols:**

```
ffffffff818e23a0-ffffffff818e23c5: format_tx_queue_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t format_tx_queue_len(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81931990)
Location: net/core/net-sysfs.c:354
Inline: False
```
**Symbols:**

```
ffffffff81931990-ffffffff819319b6: format_tx_queue_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t format_tx_queue_len(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff819644d0)
Location: net/core/net-sysfs.c:354
Inline: False
```
**Symbols:**

```
ffffffff819644d0-ffffffff819644f6: format_tx_queue_len (STB_LOCAL)
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
In net/core/net-sysfs.c (ffffffff81a38e34)
Location: net/core/net-sysfs.c:366
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_queue_len_show
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
In net/core/net-sysfs.c (ffffffff81a3b084)
Location: net/core/net-sysfs.c:367
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_queue_len_show
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
In net/core/net-sysfs.c (ffffffff81a226e4)
Location: net/core/net-sysfs.c:367
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_queue_len_show
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
In net/core/net-sysfs.c (ffffffff81ad6504)
Location: net/core/net-sysfs.c:387
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_queue_len_show
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
In net/core/net-sysfs.c (ffffffff81c56984)
Location: net/core/net-sysfs.c:389
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_queue_len_show
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
In net/core/net-sysfs.c (ffffffff81e0c924)
Location: net/core/net-sysfs.c:389
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_queue_len_show
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
In net/core/net-sysfs.c (ffffffff81e7f5f4)
Location: net/core/net-sysfs.c:389
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_queue_len_show
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
In net/core/net-sysfs.c (ffffffff81f40984)
Location: net/core/net-sysfs.c:401
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_queue_len_show
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
ssize_t format_tx_queue_len(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffff800010c08f18)
Location: net/core/net-sysfs.c:354
Inline: False
```
**Symbols:**

```
ffff800010c08f18-ffff800010c08f58: format_tx_queue_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t format_tx_queue_len(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (c0d21e64)
Location: net/core/net-sysfs.c:354
Inline: False
```
**Symbols:**

```
c0d21e64-c0d21e90: format_tx_queue_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t format_tx_queue_len(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (c000000000cf3970)
Location: net/core/net-sysfs.c:354
Inline: False
```
**Symbols:**

```
c000000000cf3970-c000000000cf39b8: format_tx_queue_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t format_tx_queue_len(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffe000786bf0)
Location: net/core/net-sysfs.c:354
Inline: False
```
**Symbols:**

```
ffffffe000786bf0-ffffffe000786c2c: format_tx_queue_len (STB_LOCAL)
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
ssize_t format_tx_queue_len(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff819044a0)
Location: net/core/net-sysfs.c:354
Inline: False
```
**Symbols:**

```
ffffffff819044a0-ffffffff819044c6: format_tx_queue_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t format_tx_queue_len(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff818be2d0)
Location: net/core/net-sysfs.c:354
Inline: False
```
**Symbols:**

```
ffffffff818be2d0-ffffffff818be2f6: format_tx_queue_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t format_tx_queue_len(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff819554d0)
Location: net/core/net-sysfs.c:354
Inline: False
```
**Symbols:**

```
ffffffff819554d0-ffffffff819554f6: format_tx_queue_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t format_tx_queue_len(const struct net_device *dev, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81977550)
Location: net/core/net-sysfs.c:354
Inline: False
```
**Symbols:**

```
ffffffff81977550-ffffffff81977576: format_tx_queue_len (STB_LOCAL)
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
