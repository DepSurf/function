# Function: <code>dev_pm_qos_add_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dev_pm_qos_add_notifier(struct device *dev, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff815557a0)
Location: drivers/base/power/qos.c:491
Inline: False
```
**Symbols:**

```
ffffffff815557a0-ffffffff81555816: dev_pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dev_pm_qos_add_notifier(struct device *dev, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff815a77f0)
Location: drivers/base/power/qos.c:491
Inline: False
Direct callers:
  - drivers/base/power/domain.c:__pm_genpd_add_device
```
**Symbols:**

```
ffffffff815a77f0-ffffffff815a7866: dev_pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dev_pm_qos_add_notifier(struct device *dev, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff815d6110)
Location: drivers/base/power/qos.c:491
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:__pm_genpd_add_device
```
**Symbols:**

```
ffffffff815d6110-ffffffff815d6186: dev_pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dev_pm_qos_add_notifier(struct device *dev, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff815eab20)
Location: drivers/base/power/qos.c:478
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:__pm_genpd_add_device
```
**Symbols:**

```
ffffffff815eab20-ffffffff815eab96: dev_pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dev_pm_qos_add_notifier(struct device *dev, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81651ed0)
Location: drivers/base/power/qos.c:481
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:__pm_genpd_add_device
```
**Symbols:**

```
ffffffff81651ed0-ffffffff81651f46: dev_pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dev_pm_qos_add_notifier(struct device *dev, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff8168d7b0)
Location: drivers/base/power/qos.c:481
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
```
**Symbols:**

```
ffffffff8168d7b0-ffffffff8168d827: dev_pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dev_pm_qos_add_notifier(struct device *dev, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff816ada00)
Location: drivers/base/power/qos.c:481
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
```
**Symbols:**

```
ffffffff816ada00-ffffffff816ada77: dev_pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dev_pm_qos_add_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/qos.c (0)
Location: drivers/base/power/qos.c:540
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff816e7d4c-ffffffff816e7d65: dev_pm_qos_add_notifier.cold (STB_LOCAL)
ffffffff816e7580-ffffffff816e7652: dev_pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dev_pm_qos_add_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff8170b960)
Location: drivers/base/power/qos.c:490
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
```
**Symbols:**

```
ffffffff8170b960-ffffffff8170b9f0: dev_pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dev_pm_qos_add_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff817c64f0)
Location: drivers/base/power/qos.c:535
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff817c64f0-ffffffff817c65d8: dev_pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dev_pm_qos_add_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff817daf70)
Location: drivers/base/power/qos.c:535
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff817daf70-ffffffff817db058: dev_pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dev_pm_qos_add_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff817bf8d0)
Location: drivers/base/power/qos.c:535
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff817bf8d0-ffffffff817bf9b8: dev_pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dev_pm_qos_add_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81849c40)
Location: drivers/base/power/qos.c:535
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81849c40-ffffffff81849d28: dev_pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dev_pm_qos_add_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff8198e150)
Location: drivers/base/power/qos.c:535
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff8198e150-ffffffff8198e242: dev_pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_pm_qos_add_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81afe0f0)
Location: drivers/base/power/qos.c:535
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81afe0f0-ffffffff81afe1e2: dev_pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_pm_qos_add_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81b4c4b0)
Location: drivers/base/power/qos.c:535
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81b4c4b0-ffffffff81b4c5a2: dev_pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_pm_qos_add_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81ba4980)
Location: drivers/base/power/qos.c:535
Inline: False
Direct callers:
  - drivers/pmdomain/core.c:genpd_remove_device
  - drivers/pmdomain/core.c:genpd_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81ba4980-ffffffff81ba4a72: dev_pm_qos_add_notifier (STB_GLOBAL)
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
int dev_pm_qos_add_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffff8000108fa508)
Location: drivers/base/power/qos.c:490
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
```
**Symbols:**

```
ffff8000108fa508-ffff8000108fa5d0: dev_pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_pm_qos_add_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (c09e5320)
Location: drivers/base/power/qos.c:490
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
```
**Symbols:**

```
c09e5320-c09e53cc: dev_pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_pm_qos_add_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (c000000000996a00)
Location: drivers/base/power/qos.c:490
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
```
**Symbols:**

```
c000000000996a00-c000000000996b2c: dev_pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_pm_qos_add_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffe000589c8a)
Location: drivers/base/power/qos.c:490
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
```
**Symbols:**

```
ffffffe000589c8a-ffffffe000589d1a: dev_pm_qos_add_notifier (STB_GLOBAL)
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
int dev_pm_qos_add_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff816d10b0)
Location: drivers/base/power/qos.c:490
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
```
**Symbols:**

```
ffffffff816d10b0-ffffffff816d1140: dev_pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dev_pm_qos_add_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff816ac3d0)
Location: drivers/base/power/qos.c:490
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
```
**Symbols:**

```
ffffffff816ac3d0-ffffffff816ac460: dev_pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dev_pm_qos_add_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff816ff620)
Location: drivers/base/power/qos.c:490
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
```
**Symbols:**

```
ffffffff816ff620-ffffffff816ff6b0: dev_pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dev_pm_qos_add_notifier(struct device *dev, struct notifier_block *notifier, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81719670)
Location: drivers/base/power/qos.c:490
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
```
**Symbols:**

```
ffffffff81719670-ffffffff81719700: dev_pm_qos_add_notifier (STB_GLOBAL)
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
