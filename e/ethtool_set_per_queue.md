# Function: <code>ethtool_set_per_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ethtool_set_per_queue(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff81789450)
Location: net/core/ethtool.c:2408
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff81789450-ffffffff817894f2: ethtool_set_per_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ethtool_set_per_queue(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff817b6d00)
Location: net/core/ethtool.c:2422
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff817b6d00-ffffffff817b6da2: ethtool_set_per_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ethtool_set_per_queue(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff817d5720)
Location: net/core/ethtool.c:2428
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff817d5720-ffffffff817d57c2: ethtool_set_per_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ethtool_set_per_queue(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8184fb80)
Location: net/core/ethtool.c:2431
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff8184fb80-ffffffff8184fc22: ethtool_set_per_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ethtool_set_per_queue(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8189b6a0)
Location: net/core/ethtool.c:2466
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff8189b6a0-ffffffff8189b742: ethtool_set_per_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ethtool_set_per_queue(struct net_device *dev, void *useraddr, u32 sub_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff818bcde0)
Location: net/core/ethtool.c:2408
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff818bcde0-ffffffff818bce95: ethtool_set_per_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ethtool_set_per_queue(struct net_device *dev, void *useraddr, u32 sub_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff81909e80)
Location: net/core/ethtool.c:2426
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff81909e80-ffffffff81909f33: ethtool_set_per_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ethtool_set_per_queue(struct net_device *dev, void *useraddr, u32 sub_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8193c450)
Location: net/core/ethtool.c:2427
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff8193c450-ffffffff8193c503: ethtool_set_per_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ethtool_set_per_queue(struct net_device *dev, void *useraddr, u32 sub_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a82bd0)
Location: net/ethtool/ioctl.c:2416
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81a82bd0-ffffffff81a82c83: ethtool_set_per_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ethtool_set_per_queue(struct net_device *dev, void *useraddr, u32 sub_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a8c6a0)
Location: net/ethtool/ioctl.c:2418
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81a8c6a0-ffffffff81a8c753: ethtool_set_per_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ethtool_set_per_queue(struct net_device *dev, void *useraddr, u32 sub_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a75470)
Location: net/ethtool/ioctl.c:2430
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81a75470-ffffffff81a75523: ethtool_set_per_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ethtool_set_per_queue(struct net_device *dev, void *useraddr, u32 sub_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81b30650)
Location: net/ethtool/ioctl.c:2544
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81b30650-ffffffff81b30703: ethtool_set_per_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ethtool_set_per_queue(struct net_device *dev, void *useraddr, u32 sub_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81cbb4f0)
Location: net/ethtool/ioctl.c:2573
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff81cbb4f0-ffffffff81cbb5bb: ethtool_set_per_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ethtool_set_per_queue(struct net_device *dev, void *useraddr, u32 sub_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81e79a70)
Location: net/ethtool/ioctl.c:2600
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff81e79a70-ffffffff81e79b3b: ethtool_set_per_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ethtool_set_per_queue(struct net_device *dev, void *useraddr, u32 sub_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81ed5d70)
Location: net/ethtool/ioctl.c:2612
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff81ed5d70-ffffffff81ed5e3b: ethtool_set_per_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ethtool_set_per_queue(struct net_device *dev, void *useraddr, u32 sub_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81f99460)
Location: net/ethtool/ioctl.c:2661
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff81f99460-ffffffff81f9952b: ethtool_set_per_queue (STB_LOCAL)
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
int ethtool_set_per_queue(struct net_device *dev, void *useraddr, u32 sub_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffff800010bdaae0)
Location: net/core/ethtool.c:2427
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffff800010bdaae0-ffff800010bdabb0: ethtool_set_per_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ethtool_set_per_queue(struct net_device *dev, void *useraddr, u32 sub_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (c0cf5ff0)
Location: net/core/ethtool.c:2427
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
c0cf5ff0-c0cf60f8: ethtool_set_per_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ethtool_set_per_queue(struct net_device *dev, void *useraddr, u32 sub_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (c000000000cbb8c0)
Location: net/core/ethtool.c:2427
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
c000000000cbb8c0-c000000000cbb9d0: ethtool_set_per_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ethtool_set_per_queue(struct net_device *dev, void *useraddr, u32 sub_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffe00076313a)
Location: net/core/ethtool.c:2427
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffe00076313a-ffffffe0007631ec: ethtool_set_per_queue (STB_LOCAL)
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
int ethtool_set_per_queue(struct net_device *dev, void *useraddr, u32 sub_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff818dc420)
Location: net/core/ethtool.c:2427
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff818dc420-ffffffff818dc4d3: ethtool_set_per_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ethtool_set_per_queue(struct net_device *dev, void *useraddr, u32 sub_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff81896260)
Location: net/core/ethtool.c:2427
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff81896260-ffffffff81896313: ethtool_set_per_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ethtool_set_per_queue(struct net_device *dev, void *useraddr, u32 sub_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8192d450)
Location: net/core/ethtool.c:2427
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff8192d450-ffffffff8192d503: ethtool_set_per_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ethtool_set_per_queue(struct net_device *dev, void *useraddr, u32 sub_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8194eb20)
Location: net/core/ethtool.c:2427
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff8194eb20-ffffffff8194ebd3: ethtool_set_per_queue (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 sub_cmd</code>
</li>
</ul>
</details>
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
