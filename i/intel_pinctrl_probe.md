# Function: <code>intel_pinctrl_probe</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
int intel_pinctrl_probe(struct platform_device *pdev, const struct intel_pinctrl_soc_data *soc_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff814d5f30)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1269
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cannonlake.c:cnl_pinctrl_probe
```
**Symbols:**

```
ffffffff814d5f30-ffffffff814d670a: intel_pinctrl_probe (STB_GLOBAL)
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
int intel_pinctrl_probe(struct platform_device *pdev, const struct intel_pinctrl_soc_data *soc_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1431
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_uid
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_hid
```
**Symbols:**

```
ffffffff816314b0-ffffffff81631738: intel_pinctrl_probe (STB_LOCAL)
ffffffff81bf58e9-ffffffff81bf5901: intel_pinctrl_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int intel_pinctrl_probe(struct platform_device *pdev, const struct intel_pinctrl_soc_data *soc_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1459
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_uid
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_hid
```
**Symbols:**

```
ffffffff81614c10-ffffffff816151b7: intel_pinctrl_probe (STB_LOCAL)
ffffffff81be7806-ffffffff81be781f: intel_pinctrl_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int intel_pinctrl_probe(struct platform_device *pdev, const struct intel_pinctrl_soc_data *soc_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1487
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_uid
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_hid
```
**Symbols:**

```
ffffffff81683ea0-ffffffff8168444f: intel_pinctrl_probe (STB_LOCAL)
ffffffff81ce11ce-ffffffff81ce11e7: intel_pinctrl_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int intel_pinctrl_probe(struct platform_device *pdev, const struct intel_pinctrl_soc_data *soc_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1502
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_uid
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_hid
```
**Symbols:**

```
ffffffff817a0320-ffffffff817a0a84: intel_pinctrl_probe (STB_LOCAL)
ffffffff81ea7964-ffffffff81ea79a5: intel_pinctrl_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int intel_pinctrl_probe(struct platform_device *pdev, const struct intel_pinctrl_soc_data *soc_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b7480)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1535
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_uid
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_hid
```
**Symbols:**

```
ffffffff818b7480-ffffffff818b7c51: intel_pinctrl_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int intel_pinctrl_probe(struct platform_device *pdev, const struct intel_pinctrl_soc_data *soc_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818fa540)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1539
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_uid
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_hid
```
**Symbols:**

```
ffffffff818fa540-ffffffff818facca: intel_pinctrl_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int intel_pinctrl_probe(struct platform_device *pdev, const struct intel_pinctrl_soc_data *soc_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff819418c0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1507
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_uid
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_hid
```
**Symbols:**

```
ffffffff819418c0-ffffffff8194204a: intel_pinctrl_probe (STB_GLOBAL)
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
