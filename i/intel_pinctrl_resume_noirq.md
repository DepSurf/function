# Function: <code>intel_pinctrl_resume_noirq</code>

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
In <code>4.15</code>: Absent ⚠️
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
int intel_pinctrl_resume_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff816328d0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1728
Inline: False
```
**Symbols:**

```
ffffffff816328d0-ffffffff81632b1c: intel_pinctrl_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int intel_pinctrl_resume_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff816164b0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1783
Inline: False
```
**Symbols:**

```
ffffffff816164b0-ffffffff8161681a: intel_pinctrl_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int intel_pinctrl_resume_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1791
Inline: False
```
**Symbols:**

```
ffffffff81ce1374-ffffffff81ce138d: intel_pinctrl_resume_noirq.cold (STB_LOCAL)
ffffffff816857e0-ffffffff81685a90: intel_pinctrl_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int intel_pinctrl_resume_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1804
Inline: False
```
**Symbols:**

```
ffffffff81ea7b42-ffffffff81ea7b5b: intel_pinctrl_resume_noirq.cold (STB_LOCAL)
ffffffff817a2010-ffffffff817a2317: intel_pinctrl_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int intel_pinctrl_resume_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1867
Inline: False
```
**Symbols:**

```
ffffffff8208e4be-ffffffff8208e4d7: intel_pinctrl_resume_noirq.cold (STB_LOCAL)
ffffffff818b9240-ffffffff818b9578: intel_pinctrl_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int intel_pinctrl_resume_noirq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1871
Inline: False
```
**Symbols:**

```
ffffffff8210e793-ffffffff8210e7ac: intel_pinctrl_resume_noirq.cold (STB_LOCAL)
ffffffff818fc2b0-ffffffff818fc5e5: intel_pinctrl_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int intel_pinctrl_resume_noirq(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81943fe0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1837
Inline: False
```
**Symbols:**

```
ffffffff81943fe0-ffffffff819441c6: intel_pinctrl_resume_noirq (STB_LOCAL)
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
