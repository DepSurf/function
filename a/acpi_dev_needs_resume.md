# Function: <code>acpi_dev_needs_resume</code>

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
bool acpi_dev_needs_resume(struct device *dev, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8153b730)
Location: drivers/acpi/device_pm.c:946
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
**Symbols:**

```
ffffffff8153b730-ffffffff8153b7fb: acpi_dev_needs_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool acpi_dev_needs_resume(struct device *dev, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81571570)
Location: drivers/acpi/device_pm.c:946
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
**Symbols:**

```
ffffffff81571570-ffffffff8157163b: acpi_dev_needs_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool acpi_dev_needs_resume(struct device *dev, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81589330)
Location: drivers/acpi/device_pm.c:947
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
**Symbols:**

```
ffffffff81589330-ffffffff81589408: acpi_dev_needs_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool acpi_dev_needs_resume(struct device *dev, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815b9e20)
Location: drivers/acpi/device_pm.c:991
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
**Symbols:**

```
ffffffff815b9e20-ffffffff815b9f06: acpi_dev_needs_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool acpi_dev_needs_resume(struct device *dev, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815db060)
Location: drivers/acpi/device_pm.c:996
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
**Symbols:**

```
ffffffff815db060-ffffffff815db146: acpi_dev_needs_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool acpi_dev_needs_resume(struct device *dev, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81685640)
Location: drivers/acpi/device_pm.c:996
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
**Symbols:**

```
ffffffff81685640-ffffffff81685726: acpi_dev_needs_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool acpi_dev_needs_resume(struct device *dev, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816a33f0)
Location: drivers/acpi/device_pm.c:992
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
**Symbols:**

```
ffffffff816a33f0-ffffffff816a34d6: acpi_dev_needs_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool acpi_dev_needs_resume(struct device *dev, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816861f0)
Location: drivers/acpi/device_pm.c:991
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
**Symbols:**

```
ffffffff816861f0-ffffffff816862d6: acpi_dev_needs_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool acpi_dev_needs_resume(struct device *dev, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816fb500)
Location: drivers/acpi/device_pm.c:991
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
**Symbols:**

```
ffffffff816fb500-ffffffff816fb5e6: acpi_dev_needs_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool acpi_dev_needs_resume(struct device *dev, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff818289c0)
Location: drivers/acpi/device_pm.c:1017
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
**Symbols:**

```
ffffffff818289c0-ffffffff81828abd: acpi_dev_needs_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool acpi_dev_needs_resume(struct device *dev, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8195aaa0)
Location: drivers/acpi/device_pm.c:1079
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
**Symbols:**

```
ffffffff8195aaa0-ffffffff8195ab9d: acpi_dev_needs_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool acpi_dev_needs_resume(struct device *dev, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819a0f70)
Location: drivers/acpi/device_pm.c:1079
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
**Symbols:**

```
ffffffff819a0f70-ffffffff819a106d: acpi_dev_needs_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool acpi_dev_needs_resume(struct device *dev, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819e9620)
Location: drivers/acpi/device_pm.c:1092
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
**Symbols:**

```
ffffffff819e9620-ffffffff819e971d: acpi_dev_needs_resume (STB_LOCAL)
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
bool acpi_dev_needs_resume(struct device *dev, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffff800010767208)
Location: drivers/acpi/device_pm.c:996
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
**Symbols:**

```
ffff800010767208-ffff800010767294: acpi_dev_needs_resume (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool acpi_dev_needs_resume(struct device *dev, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815cd830)
Location: drivers/acpi/device_pm.c:996
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
**Symbols:**

```
ffffffff815cd830-ffffffff815cd916: acpi_dev_needs_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool acpi_dev_needs_resume(struct device *dev, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815b73b0)
Location: drivers/acpi/device_pm.c:996
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
**Symbols:**

```
ffffffff815b73b0-ffffffff815b7496: acpi_dev_needs_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool acpi_dev_needs_resume(struct device *dev, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815cf340)
Location: drivers/acpi/device_pm.c:996
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
**Symbols:**

```
ffffffff815cf340-ffffffff815cf426: acpi_dev_needs_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool acpi_dev_needs_resume(struct device *dev, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815e9200)
Location: drivers/acpi/device_pm.c:996
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
**Symbols:**

```
ffffffff815e9200-ffffffff815e92e6: acpi_dev_needs_resume (STB_LOCAL)
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
