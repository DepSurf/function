# Function: <code>intel_pinctrl_should_save</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool intel_pinctrl_should_save(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff814d6710)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1371
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend
```
**Symbols:**

```
ffffffff814d6710-ffffffff814d6774: intel_pinctrl_should_save (STB_LOCAL)
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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool intel_pinctrl_should_save(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1578
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
```
**Symbols:**

```
ffffffff81632620-ffffffff81632744: intel_pinctrl_should_save (STB_LOCAL)
ffffffff81bf5985-ffffffff81bf59a2: intel_pinctrl_should_save.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool intel_pinctrl_should_save(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1633
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
```
**Symbols:**

```
ffffffff81616200-ffffffff81616324: intel_pinctrl_should_save (STB_LOCAL)
ffffffff81be78a4-ffffffff81be78c1: intel_pinctrl_should_save.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool intel_pinctrl_should_save(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1661
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
```
**Symbols:**

```
ffffffff81685530-ffffffff81685654: intel_pinctrl_should_save (STB_LOCAL)
ffffffff81ce1357-ffffffff81ce1374: intel_pinctrl_should_save.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool intel_pinctrl_should_save(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1674
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
```
**Symbols:**

```
ffffffff817a1d60-ffffffff817a1e7a: intel_pinctrl_should_save (STB_LOCAL)
ffffffff81ea7b2b-ffffffff81ea7b42: intel_pinctrl_should_save.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool intel_pinctrl_should_save(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b8f20)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1718
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
```
**Symbols:**

```
ffffffff818b8f20-ffffffff818b9088: intel_pinctrl_should_save (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool intel_pinctrl_should_save(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818fbfa0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1722
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
```
**Symbols:**

```
ffffffff818fbfa0-ffffffff818fc100: intel_pinctrl_should_save (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool intel_pinctrl_should_save(struct intel_pinctrl *pctrl, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81943cd0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1689
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq
```
**Symbols:**

```
ffffffff81943cd0-ffffffff81943e30: intel_pinctrl_should_save (STB_LOCAL)
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
