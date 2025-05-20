# Function: <code>pinctrl_dt_to_map</code>

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
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/devicetree.h:26
Inline: True
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
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/devicetree.h:26
Inline: True
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
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/devicetree.h:35
Inline: True
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
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/devicetree.h:42
Inline: True
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
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/devicetree.h:42
Inline: True
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
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/devicetree.h:42
Inline: True
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
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/devicetree.h:42
Inline: True
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
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/devicetree.h:31
Inline: True
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
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/devicetree.h:31
Inline: True
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
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/devicetree.h:24
Inline: True
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
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/devicetree.h:24
Inline: True
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
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/devicetree.h:24
Inline: True
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
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/devicetree.h:24
Inline: True
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
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/devicetree.h:24
Inline: True
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
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/devicetree.h:30
Inline: True
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
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/devicetree.h:30
Inline: True
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
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/devicetree.h:30
Inline: True
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
int pinctrl_dt_to_map(struct pinctrl *p, struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/devicetree.c (ffff800010690e88)
Location: drivers/pinctrl/devicetree.c:199
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
**Symbols:**

```
ffff800010690e88-ffff80001069125c: pinctrl_dt_to_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pinctrl_dt_to_map(struct pinctrl *p, struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/devicetree.c (c0832a44)
Location: drivers/pinctrl/devicetree.c:199
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
**Symbols:**

```
c0832a44-c0832e38: pinctrl_dt_to_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pinctrl_dt_to_map(struct pinctrl *p, struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/devicetree.c (c00000000082ccb0)
Location: drivers/pinctrl/devicetree.c:199
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
**Symbols:**

```
c00000000082ccb0-c00000000082d208: pinctrl_dt_to_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pinctrl_dt_to_map(struct pinctrl *p, struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/devicetree.c (ffffffe00049c782)
Location: drivers/pinctrl/devicetree.c:199
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
**Symbols:**

```
ffffffe00049c782-ffffffe00049cad0: pinctrl_dt_to_map (STB_GLOBAL)
```
</details>
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
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/devicetree.h:31
Inline: True
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
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/devicetree.h:31
Inline: True
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
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/devicetree.h:31
Inline: True
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
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/devicetree.h:31
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
