# Function: <code>intel_gpio_community_irq_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff814d4d37)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1023
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int intel_gpio_community_irq_handler(struct intel_pinctrl *pctrl, const struct intel_community *community);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81630d00)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1156
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq
```
**Symbols:**

```
ffffffff81630d00-ffffffff81630e2f: intel_gpio_community_irq_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int intel_gpio_community_irq_handler(struct intel_pinctrl *pctrl, const struct intel_community *community);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81615580)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1166
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq
```
**Symbols:**

```
ffffffff81615580-ffffffff816156ba: intel_gpio_community_irq_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int intel_gpio_community_irq_handler(struct intel_pinctrl *pctrl, const struct intel_community *community);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81684830)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1160
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq
```
**Symbols:**

```
ffffffff81684830-ffffffff8168497c: intel_gpio_community_irq_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int intel_gpio_community_irq_handler(struct intel_pinctrl *pctrl, const struct intel_community *community);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff817a0f40)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1183
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq
```
**Symbols:**

```
ffffffff817a0f40-ffffffff817a10af: intel_gpio_community_irq_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int intel_gpio_community_irq_handler(struct intel_pinctrl *pctrl, const struct intel_community *community);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b7070)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1195
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq
```
**Symbols:**

```
ffffffff818b7070-ffffffff818b71c0: intel_gpio_community_irq_handler (STB_LOCAL)
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
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818fa1d4)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1211
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq
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
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff8194159c)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1174
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
