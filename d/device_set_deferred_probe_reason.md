# Function: <code>device_set_deferred_probe_reason</code>

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
void device_set_deferred_probe_reason(const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817cea10)
Location: drivers/base/dd.c:220
Inline: False
Direct callers:
  - drivers/base/core.c:dev_err_probe
```
**Symbols:**

```
ffffffff817cea10-ffffffff817cea7d: device_set_deferred_probe_reason (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void device_set_deferred_probe_reason(const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817b2420)
Location: drivers/base/dd.c:226
Inline: False
Direct callers:
  - drivers/base/core.c:dev_err_probe
```
**Symbols:**

```
ffffffff817b2420-ffffffff817b2490: device_set_deferred_probe_reason (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void device_set_deferred_probe_reason(const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8183b810)
Location: drivers/base/dd.c:226
Inline: False
Direct callers:
  - drivers/base/core.c:dev_err_probe
```
**Symbols:**

```
ffffffff8183b810-ffffffff8183b880: device_set_deferred_probe_reason (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void device_set_deferred_probe_reason(const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8197dde0)
Location: drivers/base/dd.c:227
Inline: False
Direct callers:
  - drivers/base/core.c:dev_err_probe
```
**Symbols:**

```
ffffffff8197dde0-ffffffff8197de5e: device_set_deferred_probe_reason (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void device_set_deferred_probe_reason(const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81aeb6f0)
Location: drivers/base/dd.c:227
Inline: False
Direct callers:
  - drivers/base/core.c:dev_err_probe
```
**Symbols:**

```
ffffffff81aeb6f0-ffffffff81aeb76e: device_set_deferred_probe_reason (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void device_set_deferred_probe_reason(const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81b399c0)
Location: drivers/base/dd.c:227
Inline: False
Direct callers:
  - drivers/base/core.c:dev_err_probe
```
**Symbols:**

```
ffffffff81b399c0-ffffffff81b39a3e: device_set_deferred_probe_reason (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void device_set_deferred_probe_reason(const struct device *dev, struct va_format *vaf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81b91480)
Location: drivers/base/dd.c:227
Inline: False
Direct callers:
  - drivers/base/core.c:dev_err_probe
```
**Symbols:**

```
ffffffff81b91480-ffffffff81b914fe: device_set_deferred_probe_reason (STB_GLOBAL)
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
