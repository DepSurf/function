# Function: <code>_default_power_down_ok</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool _default_power_down_ok(struct dev_pm_domain *pd, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain_governor.c (ffffffff817cc420)
Location: drivers/base/power/domain_governor.c:258
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/base/power/domain_governor.c:default_power_down_ok
```
**Symbols:**

```
ffffffff817cc420-ffffffff817cc71c: _default_power_down_ok (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool _default_power_down_ok(struct dev_pm_domain *pd, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain_governor.c (0)
Location: drivers/base/power/domain_governor.c:259
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/base/power/domain_governor.c:default_power_down_ok
```
**Symbols:**

```
ffffffff81856b50-ffffffff81856ea8: _default_power_down_ok (STB_LOCAL)
ffffffff81d040e1-ffffffff81d0411d: _default_power_down_ok.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool _default_power_down_ok(struct dev_pm_domain *pd, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain_governor.c (0)
Location: drivers/base/power/domain_governor.c:265
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/base/power/domain_governor.c:default_power_down_ok
```
**Symbols:**

```
ffffffff8199cf60-ffffffff8199d2da: _default_power_down_ok (STB_LOCAL)
ffffffff81ecc9e6-ffffffff81ecca3d: _default_power_down_ok.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool _default_power_down_ok(struct dev_pm_domain *pd, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain_governor.c (0)
Location: drivers/base/power/domain_governor.c:265
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/base/power/domain_governor.c:default_power_down_ok
```
**Symbols:**

```
ffffffff81b0e5f0-ffffffff81b0e96a: _default_power_down_ok (STB_LOCAL)
ffffffff82098a56-ffffffff82098aad: _default_power_down_ok.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool _default_power_down_ok(struct dev_pm_domain *pd, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/domain_governor.c (0)
Location: drivers/base/power/domain_governor.c:265
Inline: False
Direct callers:
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/base/power/domain_governor.c:default_power_down_ok
```
**Symbols:**

```
ffffffff81b5c6a0-ffffffff81b5ca1a: _default_power_down_ok (STB_LOCAL)
ffffffff82119a0d-ffffffff82119a64: _default_power_down_ok.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool _default_power_down_ok(struct dev_pm_domain *pd, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pmdomain/governor.c (0)
Location: drivers/pmdomain/governor.c:269
Inline: False
Direct callers:
  - drivers/pmdomain/governor.c:cpu_power_down_ok
  - drivers/pmdomain/governor.c:default_power_down_ok
```
**Symbols:**

```
ffffffff81aa41a0-ffffffff81aa451a: _default_power_down_ok (STB_LOCAL)
ffffffff821f211e-ffffffff821f2175: _default_power_down_ok.cold (STB_LOCAL)
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
