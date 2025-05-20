# Function: <code>rpm_get_suppliers</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815d6c11)
Location: drivers/base/power/runtime.c:264
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__rpm_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815eb621)
Location: drivers/base/power/runtime.c:264
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__rpm_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81652a07)
Location: drivers/base/power/runtime.c:264
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__rpm_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8168f79e)
Location: drivers/base/power/runtime.c:264
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__rpm_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816afb2e)
Location: drivers/base/power/runtime.c:255
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__rpm_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rpm_get_suppliers(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816e9540)
Location: drivers/base/power/runtime.c:286
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
```
**Symbols:**

```
ffffffff816e9540-ffffffff816e95ce: rpm_get_suppliers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rpm_get_suppliers(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8170d5a0)
Location: drivers/base/power/runtime.c:286
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
```
**Symbols:**

```
ffffffff8170d5a0-ffffffff8170d62e: rpm_get_suppliers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rpm_get_suppliers(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c8b70)
Location: drivers/base/power/runtime.c:286
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
```
**Symbols:**

```
ffffffff817c8b70-ffffffff817c8c2f: rpm_get_suppliers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rpm_get_suppliers(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817dd950)
Location: drivers/base/power/runtime.c:286
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
```
**Symbols:**

```
ffffffff817dd950-ffffffff817dda10: rpm_get_suppliers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rpm_get_suppliers(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c1ce0)
Location: drivers/base/power/runtime.c:286
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
```
**Symbols:**

```
ffffffff817c1ce0-ffffffff817c1da0: rpm_get_suppliers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rpm_get_suppliers(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8184b860)
Location: drivers/base/power/runtime.c:286
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
```
**Symbols:**

```
ffffffff8184b860-ffffffff8184b920: rpm_get_suppliers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rpm_get_suppliers(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff819912a0)
Location: drivers/base/power/runtime.c:286
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
```
**Symbols:**

```
ffffffff819912a0-ffffffff81991374: rpm_get_suppliers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rpm_get_suppliers(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b01620)
Location: drivers/base/power/runtime.c:283
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
```
**Symbols:**

```
ffffffff81b01620-ffffffff81b016f4: rpm_get_suppliers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rpm_get_suppliers(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b4f750)
Location: drivers/base/power/runtime.c:283
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
```
**Symbols:**

```
ffffffff81b4f750-ffffffff81b4f824: rpm_get_suppliers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rpm_get_suppliers(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81ba7cd0)
Location: drivers/base/power/runtime.c:284
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
```
**Symbols:**

```
ffffffff81ba7cd0-ffffffff81ba7da4: rpm_get_suppliers (STB_LOCAL)
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
int rpm_get_suppliers(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffff8000108fca20)
Location: drivers/base/power/runtime.c:286
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
```
**Symbols:**

```
ffff8000108fca20-ffff8000108fcaf0: rpm_get_suppliers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rpm_get_suppliers(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c09e6fa4)
Location: drivers/base/power/runtime.c:286
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
```
**Symbols:**

```
c09e6fa4-c09e7070: rpm_get_suppliers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rpm_get_suppliers(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c000000000999400)
Location: drivers/base/power/runtime.c:286
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
```
**Symbols:**

```
c000000000999400-c00000000099950c: rpm_get_suppliers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rpm_get_suppliers(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffe00058b9a4)
Location: drivers/base/power/runtime.c:286
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
```
**Symbols:**

```
ffffffe00058b9a4-ffffffe00058ba44: rpm_get_suppliers (STB_LOCAL)
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
int rpm_get_suppliers(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816d2cf0)
Location: drivers/base/power/runtime.c:286
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
```
**Symbols:**

```
ffffffff816d2cf0-ffffffff816d2d7e: rpm_get_suppliers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rpm_get_suppliers(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816adfe0)
Location: drivers/base/power/runtime.c:286
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
```
**Symbols:**

```
ffffffff816adfe0-ffffffff816ae06e: rpm_get_suppliers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rpm_get_suppliers(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81701260)
Location: drivers/base/power/runtime.c:286
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
```
**Symbols:**

```
ffffffff81701260-ffffffff817012ee: rpm_get_suppliers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rpm_get_suppliers(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8171b100)
Location: drivers/base/power/runtime.c:286
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
```
**Symbols:**

```
ffffffff8171b100-ffffffff8171b18e: rpm_get_suppliers (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
