# Function: <code>i2c_acpi_match_device</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
int i2c_acpi_match_device(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff81709fd0)
Location: drivers/i2c/i2c-core.c:355
Inline: False
```
**Symbols:**

```
ffffffff81709fd0-ffffffff8170a015: i2c_acpi_match_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const struct acpi_device_id *i2c_acpi_match_device(const struct acpi_device_id *matches, struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81724b80)
Location: drivers/i2c/i2c-core-acpi.c:234
Inline: False
```
**Symbols:**

```
ffffffff81724b80-ffffffff81724ba1: i2c_acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const struct acpi_device_id *i2c_acpi_match_device(const struct acpi_device_id *matches, struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81796050)
Location: drivers/i2c/i2c-core-acpi.c:234
Inline: False
```
**Symbols:**

```
ffffffff81796050-ffffffff81796071: i2c_acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const struct acpi_device_id *i2c_acpi_match_device(const struct acpi_device_id *matches, struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff817d8bb0)
Location: drivers/i2c/i2c-core-acpi.c:234
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff817d8bb0-ffffffff817d8bd1: i2c_acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const struct acpi_device_id *i2c_acpi_match_device(const struct acpi_device_id *matches, struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff817ffd50)
Location: drivers/i2c/i2c-core-acpi.c:257
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff817ffd50-ffffffff817ffd71: i2c_acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const struct acpi_device_id *i2c_acpi_match_device(const struct acpi_device_id *matches, struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81840f50)
Location: drivers/i2c/i2c-core-acpi.c:279
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff81840f50-ffffffff81840f71: i2c_acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const struct acpi_device_id *i2c_acpi_match_device(const struct acpi_device_id *matches, struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff818728b0)
Location: drivers/i2c/i2c-core-acpi.c:280
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff818728b0-ffffffff818728d1: i2c_acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const struct acpi_device_id *i2c_acpi_match_device(const struct acpi_device_id *matches, struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81946a40)
Location: drivers/i2c/i2c-core-acpi.c:280
Inline: False
```
**Symbols:**

```
ffffffff81946a40-ffffffff81946a61: i2c_acpi_match_device (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
const struct acpi_device_id *i2c_acpi_match_device(const struct acpi_device_id *matches, struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffff800010ab6138)
Location: drivers/i2c/i2c-core-acpi.c:280
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffff800010ab6138-ffff800010ab617c: i2c_acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core.h:71
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core.h:71
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core.h:71
Inline: True
```
</details>
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
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const struct acpi_device_id *i2c_acpi_match_device(const struct acpi_device_id *matches, struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81866a40)
Location: drivers/i2c/i2c-core-acpi.c:280
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff81866a40-ffffffff81866a61: i2c_acpi_match_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const struct acpi_device_id *i2c_acpi_match_device(const struct acpi_device_id *matches, struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81881cf0)
Location: drivers/i2c/i2c-core-acpi.c:280
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff81881cf0-ffffffff81881d11: i2c_acpi_match_device (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct acpi_device_id *matches</code>
</li>
<li>
<b>Param added. </b>
<code>struct i2c_client *client</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param removed. </b>
<code>void *data</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>const struct acpi_device_id *</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
