# Function: <code>device_wakeup_attach_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int device_wakeup_attach_irq(struct device *dev, struct wake_irq *wakeirq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff8155c5a0)
Location: drivers/base/power/wakeup.c:290
Inline: False
```
**Symbols:**

```
ffffffff8155c5a0-ffffffff8155c5dc: device_wakeup_attach_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int device_wakeup_attach_irq(struct device *dev, struct wake_irq *wakeirq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815ae74a)
Location: drivers/base/power/wakeup.c:292
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff815ae860-ffffffff815ae89c: device_wakeup_attach_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int device_wakeup_attach_irq(struct device *dev, struct wake_irq *wakeirq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815dd54a)
Location: drivers/base/power/wakeup.c:292
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff815dd660-ffffffff815dd69c: device_wakeup_attach_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int device_wakeup_attach_irq(struct device *dev, struct wake_irq *wakeirq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815f213a)
Location: drivers/base/power/wakeup.c:294
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff815f2250-ffffffff815f228d: device_wakeup_attach_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int device_wakeup_attach_irq(struct device *dev, struct wake_irq *wakeirq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816596ea)
Location: drivers/base/power/wakeup.c:294
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff816597f0-ffffffff8165982d: device_wakeup_attach_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void device_wakeup_attach_irq(struct device *dev, struct wake_irq *wakeirq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff8169532b)
Location: drivers/base/power/wakeup.c:301
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff81695430-ffffffff81695467: device_wakeup_attach_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void device_wakeup_attach_irq(struct device *dev, struct wake_irq *wakeirq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b599b)
Location: drivers/base/power/wakeup.c:307
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff816b5aa0-ffffffff816b5ad7: device_wakeup_attach_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_wakeup_attach_irq(struct device *dev, struct wake_irq *wakeirq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816ef7c0)
Location: drivers/base/power/wakeup.c:291
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff816efc84-ffffffff816efc95: device_wakeup_attach_irq.cold (STB_LOCAL)
ffffffff816ef8c0-ffffffff816ef8f1: device_wakeup_attach_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_wakeup_attach_irq(struct device *dev, struct wake_irq *wakeirq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817137da)
Location: drivers/base/power/wakeup.c:311
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff81713c8e-ffffffff81713c9f: device_wakeup_attach_irq.cold (STB_LOCAL)
ffffffff817138e0-ffffffff81713911: device_wakeup_attach_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_wakeup_attach_irq(struct device *dev, struct wake_irq *wakeirq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817cf02a)
Location: drivers/base/power/wakeup.c:370
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff817cf761-ffffffff817cf772: device_wakeup_attach_irq.cold (STB_LOCAL)
ffffffff817cf3a0-ffffffff817cf3d1: device_wakeup_attach_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_wakeup_attach_irq(struct device *dev, struct wake_irq *wakeirq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817e362a)
Location: drivers/base/power/wakeup.c:370
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff81c0ef9a-ffffffff81c0efab: device_wakeup_attach_irq.cold (STB_LOCAL)
ffffffff817e39a0-ffffffff817e39d1: device_wakeup_attach_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_wakeup_attach_irq(struct device *dev, struct wake_irq *wakeirq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817c7c6a)
Location: drivers/base/power/wakeup.c:370
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff81c01101-ffffffff81c01112: device_wakeup_attach_irq.cold (STB_LOCAL)
ffffffff817c7de0-ffffffff817c7e11: device_wakeup_attach_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_wakeup_attach_irq(struct device *dev, struct wake_irq *wakeirq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff8185208a)
Location: drivers/base/power/wakeup.c:371
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - drivers/base/power/wakeirq.c:dev_pm_attach_wake_irq
```
**Symbols:**

```
ffffffff81d03f0b-ffffffff81d03f1c: device_wakeup_attach_irq.cold (STB_LOCAL)
ffffffff81852200-ffffffff81852231: device_wakeup_attach_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_wakeup_attach_irq(struct device *dev, struct wake_irq *wakeirq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81997bf4)
Location: drivers/base/power/wakeup.c:371
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - drivers/base/power/wakeirq.c:dev_pm_attach_wake_irq
```
**Symbols:**

```
ffffffff81ecc817-ffffffff81ecc828: device_wakeup_attach_irq.cold (STB_LOCAL)
ffffffff819980f0-ffffffff81998129: device_wakeup_attach_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void device_wakeup_attach_irq(struct device *dev, struct wake_irq *wakeirq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b08c03)
Location: drivers/base/power/wakeup.c:371
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - drivers/base/power/wakeirq.c:dev_pm_attach_wake_irq
```
**Symbols:**

```
ffffffff81b090f0-ffffffff81b09131: device_wakeup_attach_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void device_wakeup_attach_irq(struct device *dev, struct wake_irq *wakeirq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b56c23)
Location: drivers/base/power/wakeup.c:366
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - drivers/base/power/wakeirq.c:dev_pm_attach_wake_irq
```
**Symbols:**

```
ffffffff81b57110-ffffffff81b57151: device_wakeup_attach_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void device_wakeup_attach_irq(struct device *dev, struct wake_irq *wakeirq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81baf213)
Location: drivers/base/power/wakeup.c:366
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - drivers/base/power/wakeirq.c:dev_pm_attach_wake_irq
```
**Symbols:**

```
ffffffff81baf700-ffffffff81baf741: device_wakeup_attach_irq (STB_GLOBAL)
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
void device_wakeup_attach_irq(struct device *dev, struct wake_irq *wakeirq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffff800010904bf8)
Location: drivers/base/power/wakeup.c:311
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffff800010904d88-ffff800010904de0: device_wakeup_attach_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void device_wakeup_attach_irq(struct device *dev, struct wake_irq *wakeirq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (c09eea84)
Location: drivers/base/power/wakeup.c:311
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
c09eec2c-c09eec74: device_wakeup_attach_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void device_wakeup_attach_irq(struct device *dev, struct wake_irq *wakeirq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (c0000000009a358c)
Location: drivers/base/power/wakeup.c:311
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
c0000000009a37a0-c0000000009a3810: device_wakeup_attach_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeirq.c (0)
Location: drivers/base/power/power.h:53
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_wakeup_attach_irq(struct device *dev, struct wake_irq *wakeirq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816d9b39)
Location: drivers/base/power/wakeup.c:311
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff816d9fbe-ffffffff816d9fcf: device_wakeup_attach_irq.cold (STB_LOCAL)
ffffffff816d9c10-ffffffff816d9c41: device_wakeup_attach_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_wakeup_attach_irq(struct device *dev, struct wake_irq *wakeirq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b419a)
Location: drivers/base/power/wakeup.c:311
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff816b463e-ffffffff816b464f: device_wakeup_attach_irq.cold (STB_LOCAL)
ffffffff816b4290-ffffffff816b42c1: device_wakeup_attach_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_wakeup_attach_irq(struct device *dev, struct wake_irq *wakeirq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff8170749a)
Location: drivers/base/power/wakeup.c:311
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff8170794e-ffffffff8170795f: device_wakeup_attach_irq.cold (STB_LOCAL)
ffffffff817075a0-ffffffff817075d1: device_wakeup_attach_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_wakeup_attach_irq(struct device *dev, struct wake_irq *wakeirq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81721eaa)
Location: drivers/base/power/wakeup.c:311
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff8172237e-ffffffff8172238f: device_wakeup_attach_irq.cold (STB_LOCAL)
ffffffff81721fd0-ffffffff81722001: device_wakeup_attach_irq (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
