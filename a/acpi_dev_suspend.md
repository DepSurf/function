# Function: <code>acpi_dev_suspend</code>

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
int acpi_dev_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8153c2b0)
Location: drivers/acpi/device_pm.c:871
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_dismiss
```
**Symbols:**

```
ffffffff8153c2b0-ffffffff8153c390: acpi_dev_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_dev_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81572160)
Location: drivers/acpi/device_pm.c:871
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_dismiss
```
**Symbols:**

```
ffffffff81572160-ffffffff8157224e: acpi_dev_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_dev_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81589f40)
Location: drivers/acpi/device_pm.c:872
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_dismiss
```
**Symbols:**

```
ffffffff81589f40-ffffffff8158a02e: acpi_dev_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int acpi_dev_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815ba9c0)
Location: drivers/acpi/device_pm.c:916
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_dismiss
```
**Symbols:**

```
ffffffff815ba9c0-ffffffff815baaaf: acpi_dev_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int acpi_dev_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815dbc60)
Location: drivers/acpi/device_pm.c:921
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_dismiss
```
**Symbols:**

```
ffffffff815dbc60-ffffffff815dbd4f: acpi_dev_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_dev_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816861c0)
Location: drivers/acpi/device_pm.c:921
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_dismiss
```
**Symbols:**

```
ffffffff816861c0-ffffffff81686333: acpi_dev_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_dev_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816a3f80)
Location: drivers/acpi/device_pm.c:917
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_dismiss
```
**Symbols:**

```
ffffffff816a3f80-ffffffff816a40ec: acpi_dev_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_dev_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81686d00)
Location: drivers/acpi/device_pm.c:914
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_dismiss
```
**Symbols:**

```
ffffffff81686d00-ffffffff81686e6c: acpi_dev_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_dev_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816fc190)
Location: drivers/acpi/device_pm.c:914
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_dismiss
```
**Symbols:**

```
ffffffff816fc190-ffffffff816fc2fc: acpi_dev_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_dev_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81829980)
Location: drivers/acpi/device_pm.c:940
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_dismiss
```
**Symbols:**

```
ffffffff81829980-ffffffff81829ae3: acpi_dev_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_dev_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8195bd50)
Location: drivers/acpi/device_pm.c:1002
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_dismiss
```
**Symbols:**

```
ffffffff8195bd50-ffffffff8195beb0: acpi_dev_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_dev_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819a2230)
Location: drivers/acpi/device_pm.c:1002
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_dismiss
```
**Symbols:**

```
ffffffff819a2230-ffffffff819a2390: acpi_dev_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_dev_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819ea8e0)
Location: drivers/acpi/device_pm.c:1015
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_dismiss
```
**Symbols:**

```
ffffffff819ea8e0-ffffffff819eaa40: acpi_dev_suspend (STB_GLOBAL)
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
int acpi_dev_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffff8000107682c0)
Location: drivers/acpi/device_pm.c:921
Inline: False
```
**Symbols:**

```
ffff8000107682c0-ffff80001076838c: acpi_dev_suspend (STB_GLOBAL)
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
int acpi_dev_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815ce330)
Location: drivers/acpi/device_pm.c:921
Inline: False
```
**Symbols:**

```
ffffffff815ce330-ffffffff815ce41f: acpi_dev_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int acpi_dev_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815b7ef0)
Location: drivers/acpi/device_pm.c:921
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_dismiss
```
**Symbols:**

```
ffffffff815b7ef0-ffffffff815b7fdf: acpi_dev_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int acpi_dev_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815cff40)
Location: drivers/acpi/device_pm.c:921
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_dismiss
```
**Symbols:**

```
ffffffff815cff40-ffffffff815d002f: acpi_dev_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int acpi_dev_suspend(struct device *dev, bool wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815e9e00)
Location: drivers/acpi/device_pm.c:921
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_dismiss
```
**Symbols:**

```
ffffffff815e9e00-ffffffff815e9eef: acpi_dev_suspend (STB_GLOBAL)
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
