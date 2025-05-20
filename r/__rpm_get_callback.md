# Function: <code>__rpm_get_callback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
pm_callback_t __rpm_get_callback(struct device *dev, size_t cb_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81555d40)
Location: drivers/base/power/runtime.c:19
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
```
**Symbols:**

```
ffffffff81555d40-ffffffff81555dbe: __rpm_get_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
pm_callback_t __rpm_get_callback(struct device *dev, size_t cb_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815a7d90)
Location: drivers/base/power/runtime.c:19
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffffffff815a7d90-ffffffff815a7e0e: __rpm_get_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
pm_callback_t __rpm_get_callback(struct device *dev, size_t cb_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815d6560)
Location: drivers/base/power/runtime.c:21
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffffffff815d6560-ffffffff815d65de: __rpm_get_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
pm_callback_t __rpm_get_callback(struct device *dev, size_t cb_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815eaf70)
Location: drivers/base/power/runtime.c:21
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffffffff815eaf70-ffffffff815eafec: __rpm_get_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
pm_callback_t __rpm_get_callback(struct device *dev, size_t cb_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81652320)
Location: drivers/base/power/runtime.c:21
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffffffff81652320-ffffffff8165239c: __rpm_get_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
pm_callback_t __rpm_get_callback(struct device *dev, size_t cb_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8168dc00)
Location: drivers/base/power/runtime.c:21
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffffffff8168dc00-ffffffff8168dc7c: __rpm_get_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pm_callback_t __rpm_get_callback(struct device *dev, size_t cb_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816ade50)
Location: drivers/base/power/runtime.c:23
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffffffff816ade50-ffffffff816adecc: __rpm_get_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pm_callback_t __rpm_get_callback(struct device *dev, size_t cb_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816e7d80)
Location: drivers/base/power/runtime.c:21
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffffffff816e7d80-ffffffff816e7df6: __rpm_get_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pm_callback_t __rpm_get_callback(struct device *dev, size_t cb_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8170bde0)
Location: drivers/base/power/runtime.c:21
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffffffff8170bde0-ffffffff8170be56: __rpm_get_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pm_callback_t __rpm_get_callback(struct device *dev, size_t cb_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c7130)
Location: drivers/base/power/runtime.c:21
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffffffff817c7130-ffffffff817c71a6: __rpm_get_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pm_callback_t __rpm_get_callback(struct device *dev, size_t cb_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817dbbb0)
Location: drivers/base/power/runtime.c:21
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffffffff817dbbb0-ffffffff817dbc26: __rpm_get_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pm_callback_t __rpm_get_callback(struct device *dev, size_t cb_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817bff70)
Location: drivers/base/power/runtime.c:21
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffffffff817bff70-ffffffff817bffe8: __rpm_get_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
pm_callback_t __rpm_get_callback(struct device *dev, size_t cb_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8184a2e0)
Location: drivers/base/power/runtime.c:21
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffffffff8184a2e0-ffffffff8184a358: __rpm_get_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
pm_callback_t __rpm_get_callback(struct device *dev, size_t cb_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8198f360)
Location: drivers/base/power/runtime.c:21
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffffffff8198f360-ffffffff8198f3f0: __rpm_get_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pm_callback_t __rpm_get_callback(struct device *dev, size_t cb_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81aff420)
Location: drivers/base/power/runtime.c:21
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffffffff81aff420-ffffffff81aff4b0: __rpm_get_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pm_callback_t __rpm_get_callback(struct device *dev, size_t cb_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b4d7d0)
Location: drivers/base/power/runtime.c:21
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffffffff81b4d7d0-ffffffff81b4d860: __rpm_get_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pm_callback_t __rpm_get_callback(struct device *dev, size_t cb_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81ba5d50)
Location: drivers/base/power/runtime.c:22
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffffffff81ba5d50-ffffffff81ba5de0: __rpm_get_callback (STB_LOCAL)
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
pm_callback_t __rpm_get_callback(struct device *dev, size_t cb_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffff8000108fabe8)
Location: drivers/base/power/runtime.c:21
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffff8000108fabe8-ffff8000108fac74: __rpm_get_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
pm_callback_t __rpm_get_callback(struct device *dev, size_t cb_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c09e5fdc)
Location: drivers/base/power/runtime.c:21
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
c09e5fdc-c09e6074: __rpm_get_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
pm_callback_t __rpm_get_callback(struct device *dev, size_t cb_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c000000000997580)
Location: drivers/base/power/runtime.c:21
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
c000000000997580-c00000000099761c: __rpm_get_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
pm_callback_t __rpm_get_callback(struct device *dev, size_t cb_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffe00058a0fe)
Location: drivers/base/power/runtime.c:21
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffffffe00058a0fe-ffffffe00058a164: __rpm_get_callback (STB_LOCAL)
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
pm_callback_t __rpm_get_callback(struct device *dev, size_t cb_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816d1530)
Location: drivers/base/power/runtime.c:21
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffffffff816d1530-ffffffff816d15a6: __rpm_get_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
pm_callback_t __rpm_get_callback(struct device *dev, size_t cb_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816ac850)
Location: drivers/base/power/runtime.c:21
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffffffff816ac850-ffffffff816ac8c6: __rpm_get_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pm_callback_t __rpm_get_callback(struct device *dev, size_t cb_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816ffaa0)
Location: drivers/base/power/runtime.c:21
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffffffff816ffaa0-ffffffff816ffb16: __rpm_get_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pm_callback_t __rpm_get_callback(struct device *dev, size_t cb_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8171a320)
Location: drivers/base/power/runtime.c:21
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffffffff8171a320-ffffffff8171a396: __rpm_get_callback (STB_LOCAL)
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
