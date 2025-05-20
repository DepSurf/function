# Function: <code>pm_runtime_release_supplier</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pm_runtime_release_supplier(struct device_link *link, bool check_idle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8184a9f0)
Location: drivers/base/power/runtime.c:317
Inline: False
Direct callers:
  - drivers/base/core.c:device_link_release_fn
  - drivers/base/power/runtime.c:pm_runtime_drop_link
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
```
**Symbols:**

```
ffffffff8184a9f0-ffffffff8184aa8e: pm_runtime_release_supplier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_release_supplier(struct device_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81990740)
Location: drivers/base/power/runtime.c:314
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__rpm_put_suppliers
Direct callers:
  - drivers/base/core.c:device_link_release_fn
  - drivers/base/power/runtime.c:pm_runtime_drop_link
```
**Symbols:**

```
ffffffff81992220-ffffffff81992274: pm_runtime_release_supplier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_release_supplier(struct device_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b00a60)
Location: drivers/base/power/runtime.c:311
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__rpm_put_suppliers
Direct callers:
  - drivers/base/core.c:device_link_release_fn
  - drivers/base/power/runtime.c:pm_runtime_drop_link
```
**Symbols:**

```
ffffffff81b02650-ffffffff81b026a4: pm_runtime_release_supplier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_release_supplier(struct device_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b4ec00)
Location: drivers/base/power/runtime.c:311
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__rpm_put_suppliers
Direct callers:
  - drivers/base/core.c:device_link_release_fn
  - drivers/base/power/runtime.c:pm_runtime_drop_link
```
**Symbols:**

```
ffffffff81b50700-ffffffff81b5075e: pm_runtime_release_supplier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_release_supplier(struct device_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81ba7180)
Location: drivers/base/power/runtime.c:312
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__rpm_put_suppliers
Direct callers:
  - drivers/base/core.c:device_link_release_fn
  - drivers/base/power/runtime.c:pm_runtime_drop_link
```
**Symbols:**

```
ffffffff81ba8c80-ffffffff81ba8cde: pm_runtime_release_supplier (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool check_idle</code>
</li>
</ul>
</details>
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
