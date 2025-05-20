# Function: <code>pm_stay_awake</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pm_stay_awake(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff8155bbf0)
Location: drivers/base/power/wakeup.c:597
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/power/power_supply_core.c:power_supply_changed
```
**Symbols:**

```
ffffffff8155bbf0-ffffffff8155bc37: pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pm_stay_awake(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815ade00)
Location: drivers/base/power/wakeup.c:595
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/power/power_supply_core.c:power_supply_changed
```
**Symbols:**

```
ffffffff815ade00-ffffffff815ade47: pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pm_stay_awake(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815dcbd0)
Location: drivers/base/power/wakeup.c:595
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
**Symbols:**

```
ffffffff815dcbd0-ffffffff815dcc17: pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pm_stay_awake(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815f1d80)
Location: drivers/base/power/wakeup.c:595
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
**Symbols:**

```
ffffffff815f1d80-ffffffff815f1dcd: pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pm_stay_awake(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81659330)
Location: drivers/base/power/wakeup.c:596
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
**Symbols:**

```
ffffffff81659330-ffffffff8165937d: pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pm_stay_awake(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81695020)
Location: drivers/base/power/wakeup.c:595
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
**Symbols:**

```
ffffffff81695020-ffffffff8169506c: pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pm_stay_awake(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b56c0)
Location: drivers/base/power/wakeup.c:601
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
**Symbols:**

```
ffffffff816b56c0-ffffffff816b570c: pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pm_stay_awake(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816ef260)
Location: drivers/base/power/wakeup.c:585
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_remove
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
**Symbols:**

```
ffffffff816ef260-ffffffff816ef2ac: pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pm_stay_awake(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817133c0)
Location: drivers/base/power/wakeup.c:605
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_remove
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
**Symbols:**

```
ffffffff817133c0-ffffffff8171340c: pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pm_stay_awake(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817cf1c0)
Location: drivers/base/power/wakeup.c:664
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
**Symbols:**

```
ffffffff817cf1c0-ffffffff817cf20c: pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pm_stay_awake(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817e37c0)
Location: drivers/base/power/wakeup.c:664
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
**Symbols:**

```
ffffffff817e37c0-ffffffff817e380c: pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pm_stay_awake(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817c7980)
Location: drivers/base/power/wakeup.c:665
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
**Symbols:**

```
ffffffff817c7980-ffffffff817c79cc: pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pm_stay_awake(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81851d40)
Location: drivers/base/power/wakeup.c:666
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
**Symbols:**

```
ffffffff81851d40-ffffffff81851dc4: pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pm_stay_awake(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81997d20)
Location: drivers/base/power/wakeup.c:666
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
**Symbols:**

```
ffffffff81997d20-ffffffff81997dbc: pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pm_stay_awake(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b08e10)
Location: drivers/base/power/wakeup.c:636
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
**Symbols:**

```
ffffffff81b08e10-ffffffff81b08eac: pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pm_stay_awake(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b56e30)
Location: drivers/base/power/wakeup.c:631
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
**Symbols:**

```
ffffffff81b56e30-ffffffff81b56ecc: pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pm_stay_awake(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81baf420)
Location: drivers/base/power/wakeup.c:631
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
**Symbols:**

```
ffffffff81baf420-ffffffff81baf4bc: pm_stay_awake (STB_GLOBAL)
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
void pm_stay_awake(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffff8000109043d0)
Location: drivers/base/power/wakeup.c:605
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_remove
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
**Symbols:**

```
ffff8000109043d0-ffff800010904484: pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pm_stay_awake(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (c09ee3d8)
Location: drivers/base/power/wakeup.c:605
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
**Symbols:**

```
c09ee3d8-c09ee428: pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pm_stay_awake(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (c0000000009a2ca0)
Location: drivers/base/power/wakeup.c:605
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
**Symbols:**

```
c0000000009a2ca0-c0000000009a2d20: pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (0)
Location: include/linux/pm_wakeup.h:172
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/pm_wakeup.h:172
Inline: True
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
void pm_stay_awake(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816d9730)
Location: drivers/base/power/wakeup.c:605
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_remove
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
**Symbols:**

```
ffffffff816d9730-ffffffff816d977c: pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pm_stay_awake(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b3d80)
Location: drivers/base/power/wakeup.c:605
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_remove
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
**Symbols:**

```
ffffffff816b3d80-ffffffff816b3dcc: pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pm_stay_awake(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81707080)
Location: drivers/base/power/wakeup.c:605
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_remove
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
**Symbols:**

```
ffffffff81707080-ffffffff817070cc: pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pm_stay_awake(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81721ad0)
Location: drivers/base/power/wakeup.c:605
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_remove
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
**Symbols:**

```
ffffffff81721ad0-ffffffff81721b1c: pm_stay_awake (STB_GLOBAL)
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
