# Function: <code>dev_pm_qos_read_value</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
s32 dev_pm_qos_read_value(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff815558a0)
Location: drivers/base/power/qos.c:119
Inline: False
```
**Symbols:**

```
ffffffff815558a0-ffffffff815558fb: dev_pm_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
s32 dev_pm_qos_read_value(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff815a78f0)
Location: drivers/base/power/qos.c:119
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
```
**Symbols:**

```
ffffffff815a78f0-ffffffff815a794b: dev_pm_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
s32 dev_pm_qos_read_value(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff815d6210)
Location: drivers/base/power/qos.c:119
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
```
**Symbols:**

```
ffffffff815d6210-ffffffff815d626b: dev_pm_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
s32 dev_pm_qos_read_value(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff815eac20)
Location: drivers/base/power/qos.c:113
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
```
**Symbols:**

```
ffffffff815eac20-ffffffff815eac7b: dev_pm_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
s32 dev_pm_qos_read_value(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81651fd0)
Location: drivers/base/power/qos.c:113
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
```
**Symbols:**

```
ffffffff81651fd0-ffffffff8165202e: dev_pm_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
s32 dev_pm_qos_read_value(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff8168d8b0)
Location: drivers/base/power/qos.c:113
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
```
**Symbols:**

```
ffffffff8168d8b0-ffffffff8168d90e: dev_pm_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
s32 dev_pm_qos_read_value(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff816adb00)
Location: drivers/base/power/qos.c:113
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
```
**Symbols:**

```
ffffffff816adb00-ffffffff816adb5e: dev_pm_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
s32 dev_pm_qos_read_value(struct device *dev, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/qos.c (0)
Location: drivers/base/power/qos.c:110
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
**Symbols:**

```
ffffffff816e7d65-ffffffff816e7d7b: dev_pm_qos_read_value.cold (STB_LOCAL)
ffffffff816e7860-ffffffff816e791b: dev_pm_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
s32 dev_pm_qos_read_value(struct device *dev, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff8170ba70)
Location: drivers/base/power/qos.c:110
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
```
**Symbols:**

```
ffffffff8170ba70-ffffffff8170bae8: dev_pm_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
s32 dev_pm_qos_read_value(struct device *dev, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff817c6c20)
Location: drivers/base/power/qos.c:110
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
  - drivers/devfreq/devfreq.c:get_freq_range
  - drivers/devfreq/devfreq.c:get_freq_range
```
**Symbols:**

```
ffffffff817c6c20-ffffffff817c6ce3: dev_pm_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
s32 dev_pm_qos_read_value(struct device *dev, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff817db6a0)
Location: drivers/base/power/qos.c:110
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
  - drivers/devfreq/devfreq.c:get_freq_range
  - drivers/devfreq/devfreq.c:get_freq_range
```
**Symbols:**

```
ffffffff817db6a0-ffffffff817db763: dev_pm_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
s32 dev_pm_qos_read_value(struct device *dev, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff817bfa50)
Location: drivers/base/power/qos.c:110
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
  - drivers/devfreq/devfreq.c:get_freq_range
  - drivers/devfreq/devfreq.c:get_freq_range
```
**Symbols:**

```
ffffffff817bfa50-ffffffff817bfb13: dev_pm_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
s32 dev_pm_qos_read_value(struct device *dev, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81849dc0)
Location: drivers/base/power/qos.c:110
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
  - drivers/devfreq/devfreq.c:get_freq_range
  - drivers/devfreq/devfreq.c:get_freq_range
```
**Symbols:**

```
ffffffff81849dc0-ffffffff81849e83: dev_pm_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
s32 dev_pm_qos_read_value(struct device *dev, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff8198ee10)
Location: drivers/base/power/qos.c:110
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
  - drivers/devfreq/devfreq.c:devfreq_get_freq_range
  - drivers/devfreq/devfreq.c:devfreq_get_freq_range
```
**Symbols:**

```
ffffffff8198ee10-ffffffff8198eee2: dev_pm_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
s32 dev_pm_qos_read_value(struct device *dev, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81afeea0)
Location: drivers/base/power/qos.c:110
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
  - drivers/devfreq/devfreq.c:devfreq_get_freq_range
  - drivers/devfreq/devfreq.c:devfreq_get_freq_range
```
**Symbols:**

```
ffffffff81afeea0-ffffffff81afef72: dev_pm_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
s32 dev_pm_qos_read_value(struct device *dev, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81b4d260)
Location: drivers/base/power/qos.c:110
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
  - drivers/devfreq/devfreq.c:devfreq_get_freq_range
  - drivers/devfreq/devfreq.c:devfreq_get_freq_range
```
**Symbols:**

```
ffffffff81b4d260-ffffffff81b4d32c: dev_pm_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
s32 dev_pm_qos_read_value(struct device *dev, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81ba57e0)
Location: drivers/base/power/qos.c:110
Inline: False
Direct callers:
  - drivers/pmdomain/governor.c:dev_update_qos_constraint
  - drivers/devfreq/devfreq.c:devfreq_get_freq_range
  - drivers/devfreq/devfreq.c:devfreq_get_freq_range
```
**Symbols:**

```
ffffffff81ba57e0-ffffffff81ba58ac: dev_pm_qos_read_value (STB_GLOBAL)
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
s32 dev_pm_qos_read_value(struct device *dev, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffff8000108fa778)
Location: drivers/base/power/qos.c:110
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
```
**Symbols:**

```
ffff8000108fa778-ffff8000108fa85c: dev_pm_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
s32 dev_pm_qos_read_value(struct device *dev, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (c09e5c8c)
Location: drivers/base/power/qos.c:110
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
```
**Symbols:**

```
c09e5c8c-c09e5d18: dev_pm_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
s32 dev_pm_qos_read_value(struct device *dev, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (c000000000996ff0)
Location: drivers/base/power/qos.c:110
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
```
**Symbols:**

```
c000000000996ff0-c0000000009970dc: dev_pm_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
s32 dev_pm_qos_read_value(struct device *dev, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffe000589dba)
Location: drivers/base/power/qos.c:110
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
```
**Symbols:**

```
ffffffe000589dba-ffffffe000589e36: dev_pm_qos_read_value (STB_GLOBAL)
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
s32 dev_pm_qos_read_value(struct device *dev, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff816d11c0)
Location: drivers/base/power/qos.c:110
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
```
**Symbols:**

```
ffffffff816d11c0-ffffffff816d1238: dev_pm_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
s32 dev_pm_qos_read_value(struct device *dev, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff816ac4e0)
Location: drivers/base/power/qos.c:110
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
```
**Symbols:**

```
ffffffff816ac4e0-ffffffff816ac558: dev_pm_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
s32 dev_pm_qos_read_value(struct device *dev, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff816ff730)
Location: drivers/base/power/qos.c:110
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
```
**Symbols:**

```
ffffffff816ff730-ffffffff816ff7a8: dev_pm_qos_read_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
s32 dev_pm_qos_read_value(struct device *dev, enum dev_pm_qos_req_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/qos.c (ffffffff81719fb0)
Location: drivers/base/power/qos.c:110
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:dev_update_qos_constraint
```
**Symbols:**

```
ffffffff81719fb0-ffffffff8171a028: dev_pm_qos_read_value (STB_GLOBAL)
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
