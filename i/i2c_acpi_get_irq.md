# Function: <code>i2c_acpi_get_irq</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int i2c_acpi_get_irq(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81840e40)
Location: drivers/i2c/i2c-core-acpi.c:154
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff81840e40-ffffffff81840ee8: i2c_acpi_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int i2c_acpi_get_irq(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff818727a0)
Location: drivers/i2c/i2c-core-acpi.c:155
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff818727a0-ffffffff81872848: i2c_acpi_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int i2c_acpi_get_irq(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81946930)
Location: drivers/i2c/i2c-core-acpi.c:155
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff81946930-ffffffff819469d8: i2c_acpi_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int i2c_acpi_get_irq(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff8194c890)
Location: drivers/i2c/i2c-core-acpi.c:155
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff8194c890-ffffffff8194c93a: i2c_acpi_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int i2c_acpi_get_irq(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81930400)
Location: drivers/i2c/i2c-core-acpi.c:155
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff81930400-ffffffff819304ac: i2c_acpi_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int i2c_acpi_get_irq(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff819d36e0)
Location: drivers/i2c/i2c-core-acpi.c:187
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff819d36e0-ffffffff819d378c: i2c_acpi_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int i2c_acpi_get_irq(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81b35df0)
Location: drivers/i2c/i2c-core-acpi.c:190
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff81b35df0-ffffffff81b35ea1: i2c_acpi_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int i2c_acpi_get_irq(struct i2c_client *client, bool *wake_capable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:202
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff820a76b4-ffffffff820a76cb: i2c_acpi_get_irq.cold (STB_LOCAL)
ffffffff81ccb070-ffffffff81ccb152: i2c_acpi_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int i2c_acpi_get_irq(struct i2c_client *client, bool *wake_capable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:202
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff82128ad7-ffffffff82128aee: i2c_acpi_get_irq.cold (STB_LOCAL)
ffffffff81d32de0-ffffffff81d32ec2: i2c_acpi_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int i2c_acpi_get_irq(struct i2c_client *client, bool *wake_capable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:202
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff8220a469-ffffffff8220a480: i2c_acpi_get_irq.cold (STB_LOCAL)
ffffffff81de8e00-ffffffff81de8ee2: i2c_acpi_get_irq (STB_GLOBAL)
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
int i2c_acpi_get_irq(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffff800010ab6008)
Location: drivers/i2c/i2c-core-acpi.c:155
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffff800010ab6008-ffff800010ab60c8: i2c_acpi_get_irq (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int i2c_acpi_get_irq(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81866930)
Location: drivers/i2c/i2c-core-acpi.c:155
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff81866930-ffffffff818669d8: i2c_acpi_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int i2c_acpi_get_irq(struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81881be0)
Location: drivers/i2c/i2c-core-acpi.c:155
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff81881be0-ffffffff81881c88: i2c_acpi_get_irq (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool *wake_capable</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
