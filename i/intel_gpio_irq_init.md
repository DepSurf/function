# Function: <code>intel_gpio_irq_init</code>

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
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff814d68e1)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1433
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume
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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff816328ea)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1643
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq
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
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff816164d6)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1698
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intel_gpio_irq_init(struct intel_pinctrl *pctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff816838f0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1213
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_init_hw
```
**Symbols:**

```
ffffffff816838f0-ffffffff8168396d: intel_gpio_irq_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_gpio_irq_init(struct intel_pinctrl *pctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff8179fef0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1236
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_init_hw
```
**Symbols:**

```
ffffffff8179fef0-ffffffff8179ff87: intel_gpio_irq_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_gpio_irq_init(struct intel_pinctrl *pctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b6d90)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1248
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_init_hw
```
**Symbols:**

```
ffffffff818b6d90-ffffffff818b6e27: intel_gpio_irq_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_gpio_irq_init(struct intel_pinctrl *pctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818f9ea0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1259
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_init_hw
```
**Symbols:**

```
ffffffff818f9ea0-ffffffff818f9f37: intel_gpio_irq_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_gpio_irq_init(struct intel_pinctrl *pctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81941240)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1225
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_init_hw
```
**Symbols:**

```
ffffffff81941240-ffffffff819412fc: intel_gpio_irq_init (STB_LOCAL)
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
