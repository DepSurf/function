# Function: <code>phy_drivers_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void phy_drivers_unregister(struct phy_driver *drv, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff815eb820)
Location: drivers/net/phy/phy_device.c:1431
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_exit
```
**Symbols:**

```
ffffffff815eb820-ffffffff815eb868: phy_drivers_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void phy_drivers_unregister(struct phy_driver *drv, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff820e80ce)
Location: drivers/net/phy/phy_device.c:1675
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_exit
```
**Symbols:**

```
ffffffff8164a550-ffffffff8164a58c: phy_drivers_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void phy_drivers_unregister(struct phy_driver *drv, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff821cde64)
Location: drivers/net/phy/phy_device.c:1851
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_exit
```
**Symbols:**

```
ffffffff8167bc00-ffffffff8167bc40: phy_drivers_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void phy_drivers_unregister(struct phy_driver *drv, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81690ba0)
Location: drivers/net/phy/phy_device.c:1861
Inline: False
```
**Symbols:**

```
ffffffff81690ba0-ffffffff81690be0: phy_drivers_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void phy_drivers_unregister(struct phy_driver *drv, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff816fa9b0)
Location: drivers/net/phy/phy_device.c:1909
Inline: False
```
**Symbols:**

```
ffffffff816fa9b0-ffffffff816fa9f0: phy_drivers_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void phy_drivers_unregister(struct phy_driver *drv, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81737cf0)
Location: drivers/net/phy/phy_device.c:1956
Inline: False
```
**Symbols:**

```
ffffffff81737cf0-ffffffff81737d34: phy_drivers_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void phy_drivers_unregister(struct phy_driver *drv, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8175b040)
Location: drivers/net/phy/phy_device.c:2315
Inline: False
```
**Symbols:**

```
ffffffff8175b040-ffffffff8175b07f: phy_drivers_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void phy_drivers_unregister(struct phy_driver *drv, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81798610)
Location: drivers/net/phy/phy_device.c:2394
Inline: False
```
**Symbols:**

```
ffffffff81798610-ffffffff8179864f: phy_drivers_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void phy_drivers_unregister(struct phy_driver *drv, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817bbfb0)
Location: drivers/net/phy/phy_device.c:2363
Inline: False
```
**Symbols:**

```
ffffffff817bbfb0-ffffffff817bbfef: phy_drivers_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void phy_drivers_unregister(struct phy_driver *drv, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81883a60)
Location: drivers/net/phy/phy_device.c:2863
Inline: False
Direct callers:
  - drivers/net/phy/bcm84881.c:phy_module_exit
```
**Symbols:**

```
ffffffff81883a60-ffffffff81883aa6: phy_drivers_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void phy_drivers_unregister(struct phy_driver *drv, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81892190)
Location: drivers/net/phy/phy_device.c:3020
Inline: False
Direct callers:
  - drivers/net/phy/bcm84881.c:phy_module_exit
```
**Symbols:**

```
ffffffff81892190-ffffffff818921cf: phy_drivers_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void phy_drivers_unregister(struct phy_driver *drv, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff818747d0)
Location: drivers/net/phy/phy_device.c:3066
Inline: False
Direct callers:
  - drivers/net/phy/bcm84881.c:phy_module_exit
```
**Symbols:**

```
ffffffff818747d0-ffffffff8187480f: phy_drivers_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void phy_drivers_unregister(struct phy_driver *drv, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff819051b0)
Location: drivers/net/phy/phy_device.c:3198
Inline: False
Direct callers:
  - drivers/net/phy/bcm84881.c:phy_module_exit
```
**Symbols:**

```
ffffffff819051b0-ffffffff819051ef: phy_drivers_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void phy_drivers_unregister(struct phy_driver *drv, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81a58420)
Location: drivers/net/phy/phy_device.c:3236
Inline: False
Direct callers:
  - drivers/net/phy/bcm84881.c:phy_module_exit
```
**Symbols:**

```
ffffffff81a58420-ffffffff81a5846a: phy_drivers_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void phy_drivers_unregister(struct phy_driver *drv, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81be2290)
Location: drivers/net/phy/phy_device.c:3242
Inline: False
Direct callers:
  - drivers/net/phy/bcm84881.c:phy_module_exit
```
**Symbols:**

```
ffffffff81be2290-ffffffff81be22da: phy_drivers_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void phy_drivers_unregister(struct phy_driver *drv, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81c39b60)
Location: drivers/net/phy/phy_device.c:3411
Inline: False
Direct callers:
  - drivers/net/phy/bcm84881.c:phy_module_exit
```
**Symbols:**

```
ffffffff81c39b60-ffffffff81c39ba8: phy_drivers_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void phy_drivers_unregister(struct phy_driver *drv, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81ceeee0)
Location: drivers/net/phy/phy_device.c:3486
Inline: False
Direct callers:
  - drivers/net/phy/bcm84881.c:phy_module_exit
```
**Symbols:**

```
ffffffff81ceeee0-ffffffff81ceef2a: phy_drivers_unregister (STB_GLOBAL)
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
void phy_drivers_unregister(struct phy_driver *drv, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffff8000109d4f30)
Location: drivers/net/phy/phy_device.c:2363
Inline: False
```
**Symbols:**

```
ffff8000109d4f30-ffff8000109d4f88: phy_drivers_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void phy_drivers_unregister(struct phy_driver *drv, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c0abcab0)
Location: drivers/net/phy/phy_device.c:2363
Inline: False
```
**Symbols:**

```
c0abcab0-c0abcaf0: phy_drivers_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void phy_drivers_unregister(struct phy_driver *drv, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c000000000a95a70)
Location: drivers/net/phy/phy_device.c:2363
Inline: False
```
**Symbols:**

```
c000000000a95a70-c000000000a95af0: phy_drivers_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void phy_drivers_unregister(struct phy_driver *drv, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffe0006211f4)
Location: drivers/net/phy/phy_device.c:2363
Inline: False
```
**Symbols:**

```
ffffffe0006211f4-ffffffe000621246: phy_drivers_unregister (STB_GLOBAL)
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
void phy_drivers_unregister(struct phy_driver *drv, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81780a80)
Location: drivers/net/phy/phy_device.c:2363
Inline: False
```
**Symbols:**

```
ffffffff81780a80-ffffffff81780abf: phy_drivers_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void phy_drivers_unregister(struct phy_driver *drv, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81760810)
Location: drivers/net/phy/phy_device.c:2363
Inline: False
```
**Symbols:**

```
ffffffff81760810-ffffffff8176084f: phy_drivers_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void phy_drivers_unregister(struct phy_driver *drv, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817b0e30)
Location: drivers/net/phy/phy_device.c:2363
Inline: False
```
**Symbols:**

```
ffffffff817b0e30-ffffffff817b0e6f: phy_drivers_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void phy_drivers_unregister(struct phy_driver *drv, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817cadc0)
Location: drivers/net/phy/phy_device.c:2363
Inline: False
```
**Symbols:**

```
ffffffff817cadc0-ffffffff817cadff: phy_drivers_unregister (STB_GLOBAL)
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
