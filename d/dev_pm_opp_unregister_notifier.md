# Function: <code>dev_pm_opp_unregister_notifier</code>

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
Location: include/linux/pm_opp.h:226
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dev_pm_opp_unregister_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d4f50)
Location: drivers/opp/core.c:1894
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_opp_release
```
**Symbols:**

```
ffffffff817d4f50-ffffffff817d4f99: dev_pm_opp_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dev_pm_opp_unregister_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181d2b0)
Location: drivers/opp/core.c:1785
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_opp_release
```
**Symbols:**

```
ffffffff8181d2b0-ffffffff8181d2f9: dev_pm_opp_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dev_pm_opp_unregister_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818490a0)
Location: drivers/opp/core.c:2009
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_opp_release
```
**Symbols:**

```
ffffffff818490a0-ffffffff818490e9: dev_pm_opp_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dev_pm_opp_unregister_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8188bf80)
Location: drivers/opp/core.c:2126
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_opp_release
```
**Symbols:**

```
ffffffff8188bf80-ffffffff8188bfcc: dev_pm_opp_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dev_pm_opp_unregister_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818be060)
Location: drivers/opp/core.c:2175
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_opp_release
```
**Symbols:**

```
ffffffff818be060-ffffffff818be0ac: dev_pm_opp_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_unregister_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2358
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_opp_release
```
**Symbols:**

```
ffffffff819913cc-ffffffff819913eb: dev_pm_opp_unregister_notifier.cold (STB_LOCAL)
ffffffff8198e780-ffffffff8198e81a: dev_pm_opp_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_unregister_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2456
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_opp_release
```
**Symbols:**

```
ffffffff81c290ef-ffffffff81c2910e: dev_pm_opp_unregister_notifier.cold (STB_LOCAL)
ffffffff819924c0-ffffffff8199255a: dev_pm_opp_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_unregister_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2830
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_opp_release
```
**Symbols:**

```
ffffffff81c1b222-ffffffff81c1b241: dev_pm_opp_unregister_notifier.cold (STB_LOCAL)
ffffffff81976bc0-ffffffff81976c5a: dev_pm_opp_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_unregister_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2840
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_opp_release
```
**Symbols:**

```
ffffffff81d2b282-ffffffff81d2b2a1: dev_pm_opp_unregister_notifier.cold (STB_LOCAL)
ffffffff81a1f8f0-ffffffff81a1f98a: dev_pm_opp_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_unregister_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2980
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_opp_release
```
**Symbols:**

```
ffffffff81ef7488-ffffffff81ef74a7: dev_pm_opp_unregister_notifier.cold (STB_LOCAL)
ffffffff81b884f0-ffffffff81b88595: dev_pm_opp_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_pm_opp_unregister_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d27e70)
Location: drivers/opp/core.c:2987
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_opp_release
```
**Symbols:**

```
ffffffff81d27e70-ffffffff81d27f28: dev_pm_opp_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_pm_opp_unregister_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d91010)
Location: drivers/opp/core.c:3001
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_opp_release
```
**Symbols:**

```
ffffffff81d91010-ffffffff81d910c8: dev_pm_opp_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_pm_opp_unregister_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81e487b0)
Location: drivers/opp/core.c:3126
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_opp_release
```
**Symbols:**

```
ffffffff81e487b0-ffffffff81e48868: dev_pm_opp_unregister_notifier (STB_GLOBAL)
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
int dev_pm_opp_unregister_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b18e98)
Location: drivers/opp/core.c:2175
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_opp_release
```
**Symbols:**

```
ffff800010b18e98-ffff800010b18f04: dev_pm_opp_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_pm_opp_unregister_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf3cdc)
Location: drivers/opp/core.c:2175
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_opp_release
```
**Symbols:**

```
c0bf3cdc-c0bf3d28: dev_pm_opp_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_pm_opp_unregister_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0a890)
Location: drivers/opp/core.c:2175
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_opp_release
```
**Symbols:**

```
c000000000c0a890-c000000000c0a930: dev_pm_opp_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_pm_opp_unregister_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000701970)
Location: drivers/opp/core.c:2175
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_opp_release
```
**Symbols:**

```
ffffffe000701970-ffffffe0007019d6: dev_pm_opp_unregister_notifier (STB_GLOBAL)
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
int dev_pm_opp_unregister_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81862780)
Location: drivers/opp/core.c:2175
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_opp_release
```
**Symbols:**

```
ffffffff81862780-ffffffff818627cc: dev_pm_opp_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dev_pm_opp_unregister_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8182b430)
Location: drivers/opp/core.c:2175
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_opp_release
```
**Symbols:**

```
ffffffff8182b430-ffffffff8182b47c: dev_pm_opp_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dev_pm_opp_unregister_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818b3510)
Location: drivers/opp/core.c:2175
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_opp_release
```
**Symbols:**

```
ffffffff818b3510-ffffffff818b355c: dev_pm_opp_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dev_pm_opp_unregister_notifier(struct device *dev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818cf7c0)
Location: drivers/opp/core.c:2175
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_opp_release
```
**Symbols:**

```
ffffffff818cf7c0-ffffffff818cf80c: dev_pm_opp_unregister_notifier (STB_GLOBAL)
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
