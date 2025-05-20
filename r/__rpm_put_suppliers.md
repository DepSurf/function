# Function: <code>__rpm_put_suppliers</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __rpm_put_suppliers(struct device *dev, bool try_to_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817dce40)
Location: drivers/base/power/runtime.c:308
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
```
**Symbols:**

```
ffffffff817dce40-ffffffff817dcf01: __rpm_put_suppliers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __rpm_put_suppliers(struct device *dev, bool try_to_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c1200)
Location: drivers/base/power/runtime.c:308
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
```
**Symbols:**

```
ffffffff817c1200-ffffffff817c12be: __rpm_put_suppliers (STB_LOCAL)
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
In drivers/base/power/runtime.c (ffffffff8184c162)
Location: drivers/base/power/runtime.c:335
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __rpm_put_suppliers(struct device *dev, bool try_to_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81990710)
Location: drivers/base/power/runtime.c:329
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
```
**Symbols:**

```
ffffffff81990710-ffffffff819907de: __rpm_put_suppliers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __rpm_put_suppliers(struct device *dev, bool try_to_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b00a30)
Location: drivers/base/power/runtime.c:326
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
```
**Symbols:**

```
ffffffff81b00a30-ffffffff81b00afe: __rpm_put_suppliers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __rpm_put_suppliers(struct device *dev, bool try_to_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b4ebd0)
Location: drivers/base/power/runtime.c:326
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
```
**Symbols:**

```
ffffffff81b4ebd0-ffffffff81b4eca8: __rpm_put_suppliers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __rpm_put_suppliers(struct device *dev, bool try_to_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81ba7150)
Location: drivers/base/power/runtime.c:327
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
```
**Symbols:**

```
ffffffff81ba7150-ffffffff81ba7228: __rpm_put_suppliers (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
