# Function: <code>ncsi_register_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct ncsi_dev *ncsi_register_dev(struct net_device *dev, void (*handler)(struct ncsi_dev *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff8188e4a0)
Location: net/ncsi/ncsi-manage.c:1092
Inline: True
```
**Symbols:**

```
ffffffff8188e4a0-ffffffff8188e6b1: ncsi_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct ncsi_dev *ncsi_register_dev(struct net_device *dev, void (*handler)(struct ncsi_dev *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff818c2790)
Location: net/ncsi/ncsi-manage.c:1194
Inline: True
```
**Symbols:**

```
ffffffff818c2790-ffffffff818c29a1: ncsi_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct ncsi_dev *ncsi_register_dev(struct net_device *dev, void (*handler)(struct ncsi_dev *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff818e9120)
Location: net/ncsi/ncsi-manage.c:1194
Inline: True
```
**Symbols:**

```
ffffffff818e9120-ffffffff818e9343: ncsi_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct ncsi_dev *ncsi_register_dev(struct net_device *dev, void (*handler)(struct ncsi_dev *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff8196e690)
Location: net/ncsi/ncsi-manage.c:1545
Inline: True
```
**Symbols:**

```
ffffffff8196e690-ffffffff8196e8c7: ncsi_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct ncsi_dev *ncsi_register_dev(struct net_device *dev, void (*handler)(struct ncsi_dev *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff819c80e0)
Location: net/ncsi/ncsi-manage.c:1435
Inline: True
```
**Symbols:**

```
ffffffff819c80e0-ffffffff819c8323: ncsi_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct ncsi_dev *ncsi_register_dev(struct net_device *dev, void (*handler)(struct ncsi_dev *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff819ffef0)
Location: net/ncsi/ncsi-manage.c:1693
Inline: True
```
**Symbols:**

```
ffffffff819ffef0-ffffffff81a0013f: ncsi_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct ncsi_dev *ncsi_register_dev(struct net_device *dev, void (*handler)(struct ncsi_dev *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a6f200)
Location: net/ncsi/ncsi-manage.c:1689
Inline: True
```
**Symbols:**

```
ffffffff81a6f200-ffffffff81a6f416: ncsi_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct ncsi_dev *ncsi_register_dev(struct net_device *dev, void (*handler)(struct ncsi_dev *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81aa5a90)
Location: net/ncsi/ncsi-manage.c:1622
Inline: True
```
**Symbols:**

```
ffffffff81aa5a90-ffffffff81aa5c77: ncsi_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct ncsi_dev *ncsi_register_dev(struct net_device *dev, void (*handler)(struct ncsi_dev *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81ba1800)
Location: net/ncsi/ncsi-manage.c:1679
Inline: True
```
**Symbols:**

```
ffffffff81ba1800-ffffffff81ba19a1: ncsi_register_dev.part.0 (STB_LOCAL)
ffffffff81ba19b0-ffffffff81ba19fc: ncsi_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct ncsi_dev *ncsi_register_dev(struct net_device *dev, void (*handler)(struct ncsi_dev *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81bb10a0)
Location: net/ncsi/ncsi-manage.c:1679
Inline: True
```
**Symbols:**

```
ffffffff81bb10a0-ffffffff81bb1232: ncsi_register_dev.part.0 (STB_LOCAL)
ffffffff81bb1240-ffffffff81bb128c: ncsi_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct ncsi_dev *ncsi_register_dev(struct net_device *dev, void (*handler)(struct ncsi_dev *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81ba00e0)
Location: net/ncsi/ncsi-manage.c:1685
Inline: True
```
**Symbols:**

```
ffffffff81ba00e0-ffffffff81ba02bf: ncsi_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct ncsi_dev *ncsi_register_dev(struct net_device *dev, void (*handler)(struct ncsi_dev *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81c6da60)
Location: net/ncsi/ncsi-manage.c:1753
Inline: True
```
**Symbols:**

```
ffffffff81c6da60-ffffffff81c6dca6: ncsi_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct ncsi_dev *ncsi_register_dev(struct net_device *dev, void (*handler)(struct ncsi_dev *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81e114d0)
Location: net/ncsi/ncsi-manage.c:1753
Inline: True
```
**Symbols:**

```
ffffffff81e114d0-ffffffff81e11725: ncsi_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct ncsi_dev *ncsi_register_dev(struct net_device *dev, void (*handler)(struct ncsi_dev *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81fe7860)
Location: net/ncsi/ncsi-manage.c:1753
Inline: True
```
**Symbols:**

```
ffffffff81fe7860-ffffffff81fe7ab0: ncsi_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct ncsi_dev *ncsi_register_dev(struct net_device *dev, void (*handler)(struct ncsi_dev *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff82063ac0)
Location: net/ncsi/ncsi-manage.c:1753
Inline: True
```
**Symbols:**

```
ffffffff82063ac0-ffffffff82063d10: ncsi_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct ncsi_dev *ncsi_register_dev(struct net_device *dev, void (*handler)(struct ncsi_dev *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff82136c00)
Location: net/ncsi/ncsi-manage.c:1744
Inline: True
```
**Symbols:**

```
ffffffff82136c00-ffffffff82136e50: ncsi_register_dev (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct ncsi_dev *ncsi_register_dev(struct net_device *dev, void (*handler)(struct ncsi_dev *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffff800010d78240)
Location: net/ncsi/ncsi-manage.c:1622
Inline: True
```
**Symbols:**

```
ffff800010d78240-ffff800010d7848c: ncsi_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct ncsi_dev *ncsi_register_dev(struct net_device *dev, void (*handler)(struct ncsi_dev *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (c0e74258)
Location: net/ncsi/ncsi-manage.c:1622
Inline: True
```
**Symbols:**

```
c0e74258-c0e7443c: ncsi_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct ncsi_dev *ncsi_register_dev(struct net_device *dev, void (*handler)(struct ncsi_dev *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (c000000000eb7c20)
Location: net/ncsi/ncsi-manage.c:1622
Inline: True
```
**Symbols:**

```
c000000000eb7c20-c000000000eb7e70: ncsi_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct ncsi_dev *ncsi_register_dev(struct net_device *dev, void (*handler)(struct ncsi_dev *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffe0008a7844)
Location: net/ncsi/ncsi-manage.c:1622
Inline: True
```
**Symbols:**

```
ffffffe0008a7844-ffffffe0008a79f8: ncsi_register_dev (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct ncsi_dev *ncsi_register_dev(struct net_device *dev, void (*handler)(struct ncsi_dev *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a44e20)
Location: net/ncsi/ncsi-manage.c:1622
Inline: True
```
**Symbols:**

```
ffffffff81a44e20-ffffffff81a45007: ncsi_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct ncsi_dev *ncsi_register_dev(struct net_device *dev, void (*handler)(struct ncsi_dev *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a01a10)
Location: net/ncsi/ncsi-manage.c:1622
Inline: True
```
**Symbols:**

```
ffffffff81a01a10-ffffffff81a01bf7: ncsi_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct ncsi_dev *ncsi_register_dev(struct net_device *dev, void (*handler)(struct ncsi_dev *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81ab0cd0)
Location: net/ncsi/ncsi-manage.c:1622
Inline: True
```
**Symbols:**

```
ffffffff81ab0cd0-ffffffff81ab0eb7: ncsi_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct ncsi_dev *ncsi_register_dev(struct net_device *dev, void (*handler)(struct ncsi_dev *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81abd080)
Location: net/ncsi/ncsi-manage.c:1622
Inline: True
```
**Symbols:**

```
ffffffff81abd080-ffffffff81abd267: ncsi_register_dev (STB_GLOBAL)
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
