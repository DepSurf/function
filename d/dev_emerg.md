# Function: <code>dev_emerg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dev_emerg(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815477d0)
Location: drivers/base/core.c:2233
Inline: False
Direct callers:
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/power/charger-manager.c:cm_notify_event
```
**Symbols:**

```
ffffffff815477d0-ffffffff81547853: dev_emerg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dev_emerg(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81599530)
Location: drivers/base/core.c:2233
Inline: False
Direct callers:
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/power/charger-manager.c:cm_notify_event
```
**Symbols:**

```
ffffffff81599530-ffffffff815995b3: dev_emerg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dev_emerg(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c6e70)
Location: drivers/base/core.c:2824
Inline: False
Direct callers:
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/power/supply/charger-manager.c:cm_notify_event
```
**Symbols:**

```
ffffffff815c6e70-ffffffff815c6ef3: dev_emerg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dev_emerg(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815dbc00)
Location: drivers/base/core.c:2826
Inline: False
Direct callers:
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/thermal/thermal_core.c:handle_thermal_trip
```
**Symbols:**

```
ffffffff815dbc00-ffffffff815dbc80: dev_emerg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dev_emerg(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81642c30)
Location: drivers/base/core.c:2962
Inline: False
Direct callers:
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/thermal/thermal_core.c:handle_thermal_trip
```
**Symbols:**

```
ffffffff81642c30-ffffffff81642cb0: dev_emerg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dev_emerg(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167dd80)
Location: drivers/base/core.c:3017
Inline: False
Direct callers:
  - drivers/char/agp/intel-agp.c:intel_815_configure
```
**Symbols:**

```
ffffffff8167dd80-ffffffff8167de03: dev_emerg (STB_GLOBAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
