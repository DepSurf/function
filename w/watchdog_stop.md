# Function: <code>watchdog_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int watchdog_stop(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8168af80)
Location: drivers/watchdog/watchdog_dev.c:128
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
**Symbols:**

```
ffffffff8168af80-ffffffff8168b012: watchdog_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int watchdog_stop(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff816ec330)
Location: drivers/watchdog/watchdog_dev.c:257
Inline: True
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
**Symbols:**

```
ffffffff816ec330-ffffffff816ec429: watchdog_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int watchdog_stop(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8171d320)
Location: drivers/watchdog/watchdog_dev.c:258
Inline: True
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
**Symbols:**

```
ffffffff8171d320-ffffffff8171d41c: watchdog_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int watchdog_stop(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff817354f0)
Location: drivers/watchdog/watchdog_dev.c:266
Inline: True
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
**Symbols:**

```
ffffffff817354f0-ffffffff817355eb: watchdog_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int watchdog_stop(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff817a71e0)
Location: drivers/watchdog/watchdog_dev.c:267
Inline: True
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
**Symbols:**

```
ffffffff817a71e0-ffffffff817a72e1: watchdog_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int watchdog_stop(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:287
Inline: True
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
**Symbols:**

```
ffffffff817eec50-ffffffff817eed34: watchdog_stop (STB_LOCAL)
ffffffff817ef7e2-ffffffff817ef7fa: watchdog_stop.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int watchdog_stop(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8181ab4d)
Location: drivers/watchdog/watchdog_dev.c:287
Inline: True
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
**Symbols:**

```
ffffffff8181ab20-ffffffff8181ac04: watchdog_stop (STB_LOCAL)
ffffffff8181b6b4-ffffffff8181b6cc: watchdog_stop.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8185ced1)
Location: drivers/watchdog/watchdog_dev.c:304
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
**Symbols:**

```
ffffffff8185cd40-ffffffff8185ce24: watchdog_stop.part.0 (STB_LOCAL)
ffffffff8185d943-ffffffff8185d95b: watchdog_stop.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8188edc8)
Location: drivers/watchdog/watchdog_dev.c:303
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
**Symbols:**

```
ffffffff8188eb50-ffffffff8188ec34: watchdog_stop.part.0 (STB_LOCAL)
ffffffff8188f546-ffffffff8188f55e: watchdog_stop.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8195dad8)
Location: drivers/watchdog/watchdog_dev.c:304
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
**Symbols:**

```
ffffffff8195d7f0-ffffffff8195d8d4: watchdog_stop.part.0 (STB_LOCAL)
ffffffff8195e1e8-ffffffff8195e200: watchdog_stop.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff819644d8)
Location: drivers/watchdog/watchdog_dev.c:305
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
**Symbols:**

```
ffffffff819641f0-ffffffff819642d4: watchdog_stop.part.0 (STB_LOCAL)
ffffffff81c25f84-ffffffff81c25f9c: watchdog_stop.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff819488f8)
Location: drivers/watchdog/watchdog_dev.c:305
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
**Symbols:**

```
ffffffff81948610-ffffffff819486f4: watchdog_stop.part.0 (STB_LOCAL)
ffffffff81c18109-ffffffff81c18121: watchdog_stop.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff819ed8f8)
Location: drivers/watchdog/watchdog_dev.c:288
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
**Symbols:**

```
ffffffff819ed610-ffffffff819ed6f4: watchdog_stop.part.0 (STB_LOCAL)
ffffffff81d27505-ffffffff81d2751d: watchdog_stop.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int watchdog_stop(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:284
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
**Symbols:**

```
ffffffff81b53f10-ffffffff81b5400c: watchdog_stop (STB_LOCAL)
ffffffff81ef3398-ffffffff81ef33b0: watchdog_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int watchdog_stop(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81cec4e0)
Location: drivers/watchdog/watchdog_dev.c:290
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
**Symbols:**

```
ffffffff81cec4e0-ffffffff81cec5bd: watchdog_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int watchdog_stop(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81d55200)
Location: drivers/watchdog/watchdog_dev.c:292
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
**Symbols:**

```
ffffffff81d55200-ffffffff81d552dd: watchdog_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int watchdog_stop(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0c0d0)
Location: drivers/watchdog/watchdog_dev.c:292
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
**Symbols:**

```
ffffffff81e0c0d0-ffffffff81e0c1ad: watchdog_stop (STB_LOCAL)
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
int watchdog_stop(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffff800010adf960)
Location: drivers/watchdog/watchdog_dev.c:303
Inline: True
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
**Symbols:**

```
ffff800010adf960-ffff800010adfac0: watchdog_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int watchdog_stop(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (c0bc1340)
Location: drivers/watchdog/watchdog_dev.c:303
Inline: True
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
**Symbols:**

```
c0bc1340-c0bc1484: watchdog_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (c000000000bc7ba0)
Location: drivers/watchdog/watchdog_dev.c:303
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
**Symbols:**

```
c000000000bc7960-c000000000bc7b40: watchdog_stop.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int watchdog_stop(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffe0006d7584)
Location: drivers/watchdog/watchdog_dev.c:303
Inline: True
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
**Symbols:**

```
ffffffe0006d7584-ffffffe0006d765a: watchdog_stop (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81834c48)
Location: drivers/watchdog/watchdog_dev.c:303
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
**Symbols:**

```
ffffffff818349d0-ffffffff81834ab4: watchdog_stop.part.0 (STB_LOCAL)
ffffffff818353c6-ffffffff818353de: watchdog_stop.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff817fc2d8)
Location: drivers/watchdog/watchdog_dev.c:303
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
**Symbols:**

```
ffffffff817fc060-ffffffff817fc144: watchdog_stop.part.0 (STB_LOCAL)
ffffffff817fca56-ffffffff817fca6e: watchdog_stop.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81884278)
Location: drivers/watchdog/watchdog_dev.c:303
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
**Symbols:**

```
ffffffff81884000-ffffffff818840e4: watchdog_stop.part.0 (STB_LOCAL)
ffffffff818849f6-ffffffff81884a0e: watchdog_stop.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8189fd38)
Location: drivers/watchdog/watchdog_dev.c:303
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
**Symbols:**

```
ffffffff8189fac0-ffffffff8189fba4: watchdog_stop.part.0 (STB_LOCAL)
ffffffff818a04b6-ffffffff818a04ce: watchdog_stop.part.0.cold (STB_LOCAL)
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
</ul>
