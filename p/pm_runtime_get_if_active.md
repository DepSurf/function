# Function: <code>pm_runtime_get_if_active</code>

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
In <code>4.15</code>: Absent ⚠️
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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pm_runtime_get_if_active(struct device *dev, bool ign_usage_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c74b0)
Location: drivers/base/power/runtime.c:1107
Inline: False
```
**Symbols:**

```
ffffffff817c74b0-ffffffff817c75ef: pm_runtime_get_if_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pm_runtime_get_if_active(struct device *dev, bool ign_usage_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817dbf30)
Location: drivers/base/power/runtime.c:1139
Inline: False
```
**Symbols:**

```
ffffffff817dbf30-ffffffff817dc05c: pm_runtime_get_if_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pm_runtime_get_if_active(struct device *dev, bool ign_usage_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c02f0)
Location: drivers/base/power/runtime.c:1139
Inline: False
```
**Symbols:**

```
ffffffff817c02f0-ffffffff817c041c: pm_runtime_get_if_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pm_runtime_get_if_active(struct device *dev, bool ign_usage_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8184a660)
Location: drivers/base/power/runtime.c:1158
Inline: False
```
**Symbols:**

```
ffffffff8184a660-ffffffff8184a789: pm_runtime_get_if_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pm_runtime_get_if_active(struct device *dev, bool ign_usage_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8198f940)
Location: drivers/base/power/runtime.c:1186
Inline: False
```
**Symbols:**

```
ffffffff8198f940-ffffffff8198fa8b: pm_runtime_get_if_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pm_runtime_get_if_active(struct device *dev, bool ign_usage_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81affac0)
Location: drivers/base/power/runtime.c:1199
Inline: False
```
**Symbols:**

```
ffffffff81affac0-ffffffff81affc0b: pm_runtime_get_if_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pm_runtime_get_if_active(struct device *dev, bool ign_usage_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b4de70)
Location: drivers/base/power/runtime.c:1199
Inline: False
```
**Symbols:**

```
ffffffff81b4de70-ffffffff81b4df6c: pm_runtime_get_if_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pm_runtime_get_if_active(struct device *dev, bool ign_usage_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81ba63f0)
Location: drivers/base/power/runtime.c:1200
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pme_list_scan
```
**Symbols:**

```
ffffffff81ba63f0-ffffffff81ba64ec: pm_runtime_get_if_active (STB_GLOBAL)
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
