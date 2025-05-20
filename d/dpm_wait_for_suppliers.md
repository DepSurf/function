# Function: <code>dpm_wait_for_suppliers</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dpm_wait_for_suppliers(struct device *dev, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815d93d0)
Location: drivers/base/power/main.c:249
Inline: False
Direct callers:
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff815d93d0-ffffffff815d9441: dpm_wait_for_suppliers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dpm_wait_for_suppliers(struct device *dev, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815ede90)
Location: drivers/base/power/main.c:251
Inline: False
Direct callers:
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff815ede90-ffffffff815edf01: dpm_wait_for_suppliers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dpm_wait_for_suppliers(struct device *dev, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81655240)
Location: drivers/base/power/main.c:251
Inline: False
Direct callers:
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff81655240-ffffffff816552b1: dpm_wait_for_suppliers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dpm_wait_for_suppliers(struct device *dev, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81690d90)
Location: drivers/base/power/main.c:247
Inline: False
Direct callers:
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff81690d90-ffffffff81690e01: dpm_wait_for_suppliers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dpm_wait_for_suppliers(struct device *dev, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b13f0)
Location: drivers/base/power/main.c:248
Inline: False
Direct callers:
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff816b13f0-ffffffff816b1461: dpm_wait_for_suppliers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dpm_wait_for_suppliers(struct device *dev, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816eb150)
Location: drivers/base/power/main.c:255
Inline: False
Direct callers:
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
**Symbols:**

```
ffffffff816eb150-ffffffff816eb1c1: dpm_wait_for_suppliers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8170f4d0)
Location: drivers/base/power/main.c:255
Inline: True
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
In drivers/base/power/main.c (ffffffff817cb0d1)
Location: drivers/base/power/main.c:259
Inline: True
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
In drivers/base/power/main.c (ffffffff817dfb61)
Location: drivers/base/power/main.c:259
Inline: True
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
In drivers/base/power/main.c (ffffffff817c3f41)
Location: drivers/base/power/main.c:260
Inline: True
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
In drivers/base/power/main.c (ffffffff8184e311)
Location: drivers/base/power/main.c:257
Inline: True
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
In drivers/base/power/main.c (ffffffff81993e61)
Location: drivers/base/power/main.c:256
Inline: True
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
In drivers/base/power/main.c (ffffffff81b047c1)
Location: drivers/base/power/main.c:256
Inline: True
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
In drivers/base/power/main.c (ffffffff81b52041)
Location: drivers/base/power/main.c:256
Inline: True
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
In drivers/base/power/main.c (ffffffff81baa631)
Location: drivers/base/power/main.c:256
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffff8000108ffb44)
Location: drivers/base/power/main.c:255
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c09e9e88)
Location: drivers/base/power/main.c:255
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c00000000099cec0)
Location: drivers/base/power/main.c:255
Inline: True
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816d5210)
Location: drivers/base/power/main.c:255
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816afec0)
Location: drivers/base/power/main.c:255
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81703190)
Location: drivers/base/power/main.c:255
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8171da10)
Location: drivers/base/power/main.c:255
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
