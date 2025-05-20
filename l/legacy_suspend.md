# Function: <code>legacy_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int legacy_suspend(struct device *dev, pm_message_t state, int (*cb)(struct device *, pm_message_t), char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816f50c1)
Location: drivers/base/power/main.c:1320
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
```
**Symbols:**

```
ffffffff816f50c1-ffffffff816f513d: legacy_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int legacy_suspend(struct device *dev, pm_message_t state, int (*cb)(struct device *, pm_message_t), char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81759cb9)
Location: drivers/base/power/main.c:1326
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
```
**Symbols:**

```
ffffffff81759cb9-ffffffff81759d35: legacy_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int legacy_suspend(struct device *dev, pm_message_t state, int (*cb)(struct device *, pm_message_t), char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817861d8)
Location: drivers/base/power/main.c:1384
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
```
**Symbols:**

```
ffffffff817861d8-ffffffff81786260: legacy_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int legacy_suspend(struct device *dev, pm_message_t state, int (*cb)(struct device *, pm_message_t), const char *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815eedd0)
Location: drivers/base/power/main.c:1387
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
```
**Symbols:**

```
ffffffff815eedd0-ffffffff815eeef4: legacy_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816565ea)
Location: drivers/base/power/main.c:1478
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816921e6)
Location: drivers/base/power/main.c:1657
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b2856)
Location: drivers/base/power/main.c:1659
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816ec667)
Location: drivers/base/power/main.c:1645
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817106d7)
Location: drivers/base/power/main.c:1666
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
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
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1544
Inline: True
Direct callers:
  - drivers/base/power/main.c:__device_suspend
```
**Symbols:**

```
ffffffff817cb660-ffffffff817cb765: legacy_suspend.constprop.0 (STB_LOCAL)
ffffffff817ce1d7-ffffffff817ce205: legacy_suspend.constprop.0.cold (STB_LOCAL)
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
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1543
Inline: True
Direct callers:
  - drivers/base/power/main.c:__device_suspend
```
**Symbols:**

```
ffffffff817e00f0-ffffffff817e01d1: legacy_suspend.constprop.0 (STB_LOCAL)
ffffffff81c0edaa-ffffffff81c0edd8: legacy_suspend.constprop.0.cold (STB_LOCAL)
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
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1544
Inline: True
Direct callers:
  - drivers/base/power/main.c:__device_suspend
```
**Symbols:**

```
ffffffff817c4250-ffffffff817c4331: legacy_suspend.constprop.0 (STB_LOCAL)
ffffffff81c00f23-ffffffff81c00f51: legacy_suspend.constprop.0.cold (STB_LOCAL)
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
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1563
Inline: True
Direct callers:
  - drivers/base/power/main.c:__device_suspend
```
**Symbols:**

```
ffffffff8184e620-ffffffff8184e715: legacy_suspend.constprop.0 (STB_LOCAL)
ffffffff81d03a2a-ffffffff81d03a83: legacy_suspend.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1559
Inline: True
Direct callers:
  - drivers/base/power/main.c:__device_suspend
```
**Symbols:**

```
ffffffff819941b0-ffffffff819942f0: legacy_suspend.constprop.0 (STB_LOCAL)
ffffffff81ecc2df-ffffffff81ecc335: legacy_suspend.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1559
Inline: True
Direct callers:
  - drivers/base/power/main.c:__device_suspend
```
**Symbols:**

```
ffffffff81b04b80-ffffffff81b04d00: legacy_suspend.constprop.0 (STB_LOCAL)
ffffffff82098911-ffffffff82098926: legacy_suspend.constprop.0.cold (STB_LOCAL)
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
In drivers/base/power/main.c (ffffffff81b529eb)
Location: drivers/base/power/main.c:1559
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
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
In drivers/base/power/main.c (ffffffff81bab09b)
Location: drivers/base/power/main.c:1558
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffff800010900e4c)
Location: drivers/base/power/main.c:1666
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c09eb048)
Location: drivers/base/power/main.c:1666
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c00000000099e898)
Location: drivers/base/power/main.c:1666
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816d6a7d)
Location: drivers/base/power/main.c:1666
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b10bb)
Location: drivers/base/power/main.c:1666
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81704397)
Location: drivers/base/power/main.c:1666
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8171e485)
Location: drivers/base/power/main.c:1666
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *info</code> ➡️ <code>const char *info</code>
</li>
</ul>
</details>
</li>
</ul>
