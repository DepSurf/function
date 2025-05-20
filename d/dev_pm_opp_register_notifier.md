# Function: <code>dev_pm_opp_register_notifier</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/pm_opp.h:221
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dev_pm_opp_register_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d4f00)
Location: drivers/opp/core.c:1870
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
```
**Symbols:**

```
ffffffff817d4f00-ffffffff817d4f49: dev_pm_opp_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dev_pm_opp_register_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181d260)
Location: drivers/opp/core.c:1761
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
```
**Symbols:**

```
ffffffff8181d260-ffffffff8181d2a9: dev_pm_opp_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dev_pm_opp_register_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81849050)
Location: drivers/opp/core.c:1985
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
```
**Symbols:**

```
ffffffff81849050-ffffffff81849099: dev_pm_opp_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dev_pm_opp_register_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8188bf30)
Location: drivers/opp/core.c:2102
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
```
**Symbols:**

```
ffffffff8188bf30-ffffffff8188bf7c: dev_pm_opp_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dev_pm_opp_register_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818be010)
Location: drivers/opp/core.c:2151
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
```
**Symbols:**

```
ffffffff818be010-ffffffff818be05c: dev_pm_opp_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_register_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2334
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
```
**Symbols:**

```
ffffffff819913ad-ffffffff819913cc: dev_pm_opp_register_notifier.cold (STB_LOCAL)
ffffffff8198e6e0-ffffffff8198e77a: dev_pm_opp_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_register_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2432
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
```
**Symbols:**

```
ffffffff81c2910e-ffffffff81c2912d: dev_pm_opp_register_notifier.cold (STB_LOCAL)
ffffffff81992560-ffffffff819925fa: dev_pm_opp_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_register_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2806
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
```
**Symbols:**

```
ffffffff81c1b203-ffffffff81c1b222: dev_pm_opp_register_notifier.cold (STB_LOCAL)
ffffffff81976b20-ffffffff81976bba: dev_pm_opp_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_register_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2816
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
```
**Symbols:**

```
ffffffff81d2b2a1-ffffffff81d2b2c0: dev_pm_opp_register_notifier.cold (STB_LOCAL)
ffffffff81a1f990-ffffffff81a1fa2a: dev_pm_opp_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_register_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2956
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
```
**Symbols:**

```
ffffffff81ef7469-ffffffff81ef7488: dev_pm_opp_register_notifier.cold (STB_LOCAL)
ffffffff81b88440-ffffffff81b884e5: dev_pm_opp_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_pm_opp_register_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d27f40)
Location: drivers/opp/core.c:2963
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
```
**Symbols:**

```
ffffffff81d27f40-ffffffff81d27ff8: dev_pm_opp_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_pm_opp_register_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d910e0)
Location: drivers/opp/core.c:2977
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
```
**Symbols:**

```
ffffffff81d910e0-ffffffff81d91198: dev_pm_opp_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_pm_opp_register_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81e486e0)
Location: drivers/opp/core.c:3102
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
```
**Symbols:**

```
ffffffff81e486e0-ffffffff81e48798: dev_pm_opp_register_notifier (STB_GLOBAL)
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
int dev_pm_opp_register_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b18e28)
Location: drivers/opp/core.c:2151
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
```
**Symbols:**

```
ffff800010b18e28-ffff800010b18e94: dev_pm_opp_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_pm_opp_register_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf3c90)
Location: drivers/opp/core.c:2151
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
```
**Symbols:**

```
c0bf3c90-c0bf3cdc: dev_pm_opp_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_pm_opp_register_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0a7f0)
Location: drivers/opp/core.c:2151
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
```
**Symbols:**

```
c000000000c0a7f0-c000000000c0a890: dev_pm_opp_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_pm_opp_register_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe00070190a)
Location: drivers/opp/core.c:2151
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
```
**Symbols:**

```
ffffffe00070190a-ffffffe000701970: dev_pm_opp_register_notifier (STB_GLOBAL)
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
int dev_pm_opp_register_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81862730)
Location: drivers/opp/core.c:2151
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
```
**Symbols:**

```
ffffffff81862730-ffffffff8186277c: dev_pm_opp_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dev_pm_opp_register_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8182b3e0)
Location: drivers/opp/core.c:2151
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
```
**Symbols:**

```
ffffffff8182b3e0-ffffffff8182b42c: dev_pm_opp_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dev_pm_opp_register_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818b34c0)
Location: drivers/opp/core.c:2151
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
```
**Symbols:**

```
ffffffff818b34c0-ffffffff818b350c: dev_pm_opp_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dev_pm_opp_register_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818cf770)
Location: drivers/opp/core.c:2151
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_register_opp_notifier
```
**Symbols:**

```
ffffffff818cf770-ffffffff818cf7bc: dev_pm_opp_register_notifier (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
