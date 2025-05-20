# Function: <code>device_prepare</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8155b462)
Location: drivers/base/power/main.c:1551
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815ad47d)
Location: drivers/base/power/main.c:1557
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815dc23d)
Location: drivers/base/power/main.c:1632
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815f0db6)
Location: drivers/base/power/main.c:1635
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
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
In drivers/base/power/main.c (ffffffff81658306)
Location: drivers/base/power/main.c:1722
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
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
In drivers/base/power/main.c (ffffffff81693d18)
Location: drivers/base/power/main.c:1899
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
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
In drivers/base/power/main.c (ffffffff816b4398)
Location: drivers/base/power/main.c:1905
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
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
In drivers/base/power/main.c (ffffffff816ee263)
Location: drivers/base/power/main.c:1892
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
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
In drivers/base/power/main.c (ffffffff81712243)
Location: drivers/base/power/main.c:1913
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int device_prepare(struct device *dev, pm_message_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1795
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_prepare
```
**Symbols:**

```
ffffffff817cb770-ffffffff817cb917: device_prepare (STB_LOCAL)
ffffffff817ce205-ffffffff817ce230: device_prepare.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int device_prepare(struct device *dev, pm_message_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1794
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_prepare
```
**Symbols:**

```
ffffffff817e01e0-ffffffff817e0387: device_prepare (STB_LOCAL)
ffffffff81c0edd8-ffffffff81c0ee03: device_prepare.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int device_prepare(struct device *dev, pm_message_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1795
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_prepare
```
**Symbols:**

```
ffffffff817c4a20-ffffffff817c4bc7: device_prepare (STB_LOCAL)
ffffffff81c00fd6-ffffffff81c01001: device_prepare.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int device_prepare(struct device *dev, pm_message_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1820
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_prepare
```
**Symbols:**

```
ffffffff8184ee30-ffffffff8184efd7: device_prepare (STB_LOCAL)
ffffffff81d03b20-ffffffff81d03b4b: device_prepare.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int device_prepare(struct device *dev, pm_message_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1816
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_prepare
```
**Symbols:**

```
ffffffff81993360-ffffffff819934ef: device_prepare (STB_LOCAL)
ffffffff81ecc1d8-ffffffff81ecc1ff: device_prepare.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int device_prepare(struct device *dev, pm_message_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b03a00)
Location: drivers/base/power/main.c:1816
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_prepare
```
**Symbols:**

```
ffffffff81b03a00-ffffffff81b03bd8: device_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int device_prepare(struct device *dev, pm_message_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b51a60)
Location: drivers/base/power/main.c:1816
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_prepare
```
**Symbols:**

```
ffffffff81b51a60-ffffffff81b51c38: device_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int device_prepare(struct device *dev, pm_message_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81baa050)
Location: drivers/base/power/main.c:1815
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_prepare
```
**Symbols:**

```
ffffffff81baa050-ffffffff81baa228: device_prepare (STB_LOCAL)
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
In drivers/base/power/main.c (ffff800010902c4c)
Location: drivers/base/power/main.c:1913
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
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
In drivers/base/power/main.c (c09ed070)
Location: drivers/base/power/main.c:1913
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
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
In drivers/base/power/main.c (c0000000009a11d4)
Location: drivers/base/power/main.c:1913
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
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
In drivers/base/power/main.c (ffffffff816d85c3)
Location: drivers/base/power/main.c:1913
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
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
In drivers/base/power/main.c (ffffffff816b2c23)
Location: drivers/base/power/main.c:1913
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
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
In drivers/base/power/main.c (ffffffff81705f03)
Location: drivers/base/power/main.c:1913
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
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
In drivers/base/power/main.c (ffffffff817208ce)
Location: drivers/base/power/main.c:1913
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
