# Function: <code>dev_pm_qos_remove_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dev_pm_qos_remove_notifier(struct device *dev, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81554de0)
Location: drivers/base/power/qos.c:521
Inline: False
```
**Symbols:**

```
ffffffff81554de0-ffffffff81554e37: dev_pm_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dev_pm_qos_remove_notifier(struct device *dev, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff815a6e40)
Location: drivers/base/power/qos.c:521
Inline: False
```
**Symbols:**

```
ffffffff815a6e40-ffffffff815a6e97: dev_pm_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dev_pm_qos_remove_notifier(struct device *dev, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff815d5600)
Location: drivers/base/power/qos.c:521
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
**Symbols:**

```
ffffffff815d5600-ffffffff815d5657: dev_pm_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dev_pm_qos_remove_notifier(struct device *dev, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff815ea080)
Location: drivers/base/power/qos.c:508
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
**Symbols:**

```
ffffffff815ea080-ffffffff815ea0d7: dev_pm_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dev_pm_qos_remove_notifier(struct device *dev, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81651430)
Location: drivers/base/power/qos.c:511
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
**Symbols:**

```
ffffffff81651430-ffffffff81651487: dev_pm_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dev_pm_qos_remove_notifier(struct device *dev, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff8168cce0)
Location: drivers/base/power/qos.c:511
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
**Symbols:**

```
ffffffff8168cce0-ffffffff8168cd37: dev_pm_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dev_pm_qos_remove_notifier(struct device *dev, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff816acf30)
Location: drivers/base/power/qos.c:511
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
**Symbols:**

```
ffffffff816acf30-ffffffff816acf87: dev_pm_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dev_pm_qos_remove_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/qos.c (0)
Location: drivers/base/power/qos.c:590
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
```
**Symbols:**

```
ffffffff816e7d10-ffffffff816e7d29: dev_pm_qos_remove_notifier.cold (STB_LOCAL)
ffffffff816e6a80-ffffffff816e6b1f: dev_pm_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dev_pm_qos_remove_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff8170adf0)
Location: drivers/base/power/qos.c:532
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
**Symbols:**

```
ffffffff8170adf0-ffffffff8170ae61: dev_pm_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dev_pm_qos_remove_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff817c5c10)
Location: drivers/base/power/qos.c:585
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/devfreq/devfreq.c:devfreq_dev_release
  - drivers/devfreq/devfreq.c:devfreq_dev_release
```
**Symbols:**

```
ffffffff817c5c10-ffffffff817c5cb6: dev_pm_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dev_pm_qos_remove_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff817da720)
Location: drivers/base/power/qos.c:585
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/devfreq/devfreq.c:devfreq_dev_release
  - drivers/devfreq/devfreq.c:devfreq_dev_release
```
**Symbols:**

```
ffffffff817da720-ffffffff817da7c6: dev_pm_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dev_pm_qos_remove_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff817bead0)
Location: drivers/base/power/qos.c:585
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/devfreq/devfreq.c:devfreq_dev_release
  - drivers/devfreq/devfreq.c:devfreq_dev_release
```
**Symbols:**

```
ffffffff817bead0-ffffffff817beb76: dev_pm_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dev_pm_qos_remove_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81848e50)
Location: drivers/base/power/qos.c:585
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/devfreq/devfreq.c:devfreq_dev_release
  - drivers/devfreq/devfreq.c:devfreq_dev_release
```
**Symbols:**

```
ffffffff81848e50-ffffffff81848ef6: dev_pm_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dev_pm_qos_remove_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff8198df30)
Location: drivers/base/power/qos.c:585
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/devfreq/devfreq.c:devfreq_dev_release
  - drivers/devfreq/devfreq.c:devfreq_dev_release
```
**Symbols:**

```
ffffffff8198df30-ffffffff8198dfda: dev_pm_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_pm_qos_remove_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81afdea0)
Location: drivers/base/power/qos.c:585
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/devfreq/devfreq.c:devfreq_dev_release
  - drivers/devfreq/devfreq.c:devfreq_dev_release
```
**Symbols:**

```
ffffffff81afdea0-ffffffff81afdf4a: dev_pm_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_pm_qos_remove_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81b4c260)
Location: drivers/base/power/qos.c:585
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/devfreq/devfreq.c:devfreq_dev_release
  - drivers/devfreq/devfreq.c:devfreq_dev_release
```
**Symbols:**

```
ffffffff81b4c260-ffffffff81b4c30a: dev_pm_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_pm_qos_remove_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81ba46d0)
Location: drivers/base/power/qos.c:585
Inline: False
Direct callers:
  - drivers/pmdomain/core.c:genpd_remove_device
  - drivers/devfreq/devfreq.c:devfreq_dev_release
  - drivers/devfreq/devfreq.c:devfreq_dev_release
```
**Symbols:**

```
ffffffff81ba46d0-ffffffff81ba477a: dev_pm_qos_remove_notifier (STB_GLOBAL)
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
int dev_pm_qos_remove_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffff8000108f9808)
Location: drivers/base/power/qos.c:532
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
```
**Symbols:**

```
ffff8000108f9808-ffff8000108f98ac: dev_pm_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_pm_qos_remove_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (c09e53cc)
Location: drivers/base/power/qos.c:532
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
```
**Symbols:**

```
c09e53cc-c09e5468: dev_pm_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_pm_qos_remove_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (c000000000995bf0)
Location: drivers/base/power/qos.c:532
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
```
**Symbols:**

```
c000000000995bf0-c000000000995cec: dev_pm_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_pm_qos_remove_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffe00058916c)
Location: drivers/base/power/qos.c:532
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
```
**Symbols:**

```
ffffffe00058916c-ffffffe0005891e4: dev_pm_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int dev_pm_qos_remove_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff816d0540)
Location: drivers/base/power/qos.c:532
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
**Symbols:**

```
ffffffff816d0540-ffffffff816d05b1: dev_pm_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dev_pm_qos_remove_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff816ab860)
Location: drivers/base/power/qos.c:532
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
**Symbols:**

```
ffffffff816ab860-ffffffff816ab8d1: dev_pm_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dev_pm_qos_remove_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff816feab0)
Location: drivers/base/power/qos.c:532
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
**Symbols:**

```
ffffffff816feab0-ffffffff816feb21: dev_pm_qos_remove_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dev_pm_qos_remove_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81719700)
Location: drivers/base/power/qos.c:532
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
```
**Symbols:**

```
ffffffff81719700-ffffffff81719771: dev_pm_qos_remove_notifier (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum dev_pm_qos_req_type type</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
