# Function: <code>dpm_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dpm_wait(struct device *dev, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81558520)
Location: drivers/base/power/main.c:225
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_wait_fn
  - drivers/base/power/main.c:device_pm_wait_for_dev
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume
```
**Symbols:**

```
ffffffff81558520-ffffffff81558554: dpm_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dpm_wait(struct device *dev, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815aa690)
Location: drivers/base/power/main.c:227
Inline: False
Direct callers:
  - drivers/base/power/main.c:device_pm_wait_for_dev
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:dpm_wait_fn
```
**Symbols:**

```
ffffffff815aa690-ffffffff815aa6c5: dpm_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dpm_wait(struct device *dev, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815d9340)
Location: drivers/base/power/main.c:229
Inline: False
Direct callers:
  - drivers/base/power/main.c:device_pm_wait_for_dev
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_for_suppliers
  - drivers/base/power/main.c:dpm_wait_fn
```
**Symbols:**

```
ffffffff815d9340-ffffffff815d9375: dpm_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dpm_wait(struct device *dev, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815ede00)
Location: drivers/base/power/main.c:231
Inline: False
Direct callers:
  - drivers/base/power/main.c:device_pm_wait_for_dev
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_for_suppliers
  - drivers/base/power/main.c:dpm_wait_fn
```
**Symbols:**

```
ffffffff815ede00-ffffffff815ede36: dpm_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dpm_wait(struct device *dev, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816551b0)
Location: drivers/base/power/main.c:231
Inline: False
Direct callers:
  - drivers/base/power/main.c:device_pm_wait_for_dev
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_for_suppliers
  - drivers/base/power/main.c:dpm_wait_fn
```
**Symbols:**

```
ffffffff816551b0-ffffffff816551e6: dpm_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dpm_wait(struct device *dev, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81690d00)
Location: drivers/base/power/main.c:227
Inline: False
Direct callers:
  - drivers/base/power/main.c:device_pm_wait_for_dev
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_for_suppliers
  - drivers/base/power/main.c:dpm_wait_fn
```
**Symbols:**

```
ffffffff81690d00-ffffffff81690d35: dpm_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dpm_wait(struct device *dev, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b1360)
Location: drivers/base/power/main.c:228
Inline: False
Direct callers:
  - drivers/base/power/main.c:device_pm_wait_for_dev
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_for_suppliers
  - drivers/base/power/main.c:dpm_wait_fn
```
**Symbols:**

```
ffffffff816b1360-ffffffff816b1395: dpm_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dpm_wait(struct device *dev, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816eb0c0)
Location: drivers/base/power/main.c:235
Inline: False
Direct callers:
  - drivers/base/power/main.c:device_pm_wait_for_dev
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_for_suppliers
  - drivers/base/power/main.c:dpm_wait_fn
```
**Symbols:**

```
ffffffff816eb0c0-ffffffff816eb0f5: dpm_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dpm_wait(struct device *dev, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8170f100)
Location: drivers/base/power/main.c:235
Inline: False
Direct callers:
  - drivers/base/power/main.c:device_pm_wait_for_dev
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_fn
```
**Symbols:**

```
ffffffff8170f100-ffffffff8170f135: dpm_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817cb00f)
Location: drivers/base/power/main.c:239
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_wait_for_dev
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817dfa9f)
Location: drivers/base/power/main.c:239
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_wait_for_dev
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_fn
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
In drivers/base/power/main.c (ffffffff817c3e7f)
Location: drivers/base/power/main.c:240
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_wait_for_dev
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8184e1ef)
Location: drivers/base/power/main.c:237
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_wait_for_dev
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81993d2f)
Location: drivers/base/power/main.c:236
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_wait_for_dev
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b0466f)
Location: drivers/base/power/main.c:236
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_wait_for_dev
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_fn
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
In drivers/base/power/main.c (ffffffff81b51eef)
Location: drivers/base/power/main.c:236
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_wait_for_dev
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_fn
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
In drivers/base/power/main.c (ffffffff81baa4df)
Location: drivers/base/power/main.c:236
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_wait_for_dev
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_fn
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
void dpm_wait(struct device *dev, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffff8000108ff660)
Location: drivers/base/power/main.c:235
Inline: False
Direct callers:
  - drivers/base/power/main.c:device_pm_wait_for_dev
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_fn
```
**Symbols:**

```
ffff8000108ff660-ffff8000108ff6ac: dpm_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dpm_wait(struct device *dev, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c09e9b10)
Location: drivers/base/power/main.c:235
Inline: False
Direct callers:
  - drivers/base/power/main.c:device_pm_wait_for_dev
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_fn
```
**Symbols:**

```
c09e9b10-c09e9b60: dpm_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dpm_wait(struct device *dev, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c00000000099c8a0)
Location: drivers/base/power/main.c:235
Inline: False
Direct callers:
  - drivers/base/power/main.c:device_pm_wait_for_dev
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_fn
```
**Symbols:**

```
c00000000099c8a0-c00000000099c908: dpm_wait (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void dpm_wait(struct device *dev, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816d4e40)
Location: drivers/base/power/main.c:235
Inline: False
Direct callers:
  - drivers/base/power/main.c:device_pm_wait_for_dev
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_fn
```
**Symbols:**

```
ffffffff816d4e40-ffffffff816d4e75: dpm_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dpm_wait(struct device *dev, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816afaf0)
Location: drivers/base/power/main.c:235
Inline: False
Direct callers:
  - drivers/base/power/main.c:device_pm_wait_for_dev
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_fn
```
**Symbols:**

```
ffffffff816afaf0-ffffffff816afb25: dpm_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dpm_wait(struct device *dev, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81702dc0)
Location: drivers/base/power/main.c:235
Inline: False
Direct callers:
  - drivers/base/power/main.c:device_pm_wait_for_dev
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_fn
```
**Symbols:**

```
ffffffff81702dc0-ffffffff81702df5: dpm_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dpm_wait(struct device *dev, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8171d640)
Location: drivers/base/power/main.c:235
Inline: False
Direct callers:
  - drivers/base/power/main.c:device_pm_wait_for_dev
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_fn
```
**Symbols:**

```
ffffffff8171d640-ffffffff8171d675: dpm_wait (STB_LOCAL)
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
