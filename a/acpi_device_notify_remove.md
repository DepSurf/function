# Function: <code>acpi_device_notify_remove</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff8158c4ea)
Location: drivers/acpi/glue.c:346
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_platform_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff815bd26a)
Location: drivers/acpi/glue.c:345
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_platform_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff815de52a)
Location: drivers/acpi/glue.c:345
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_platform_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff81688f2e)
Location: drivers/acpi/glue.c:345
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_platform_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff816a6afe)
Location: drivers/acpi/glue.c:345
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_platform_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff81689682)
Location: drivers/acpi/glue.c:345
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_platform_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_device_notify_remove(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff816fec90)
Location: drivers/acpi/glue.c:327
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff816fec90-ffffffff816fed48: acpi_device_notify_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_device_notify_remove(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff8182c620)
Location: drivers/acpi/glue.c:338
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff8182c620-ffffffff8182c694: acpi_device_notify_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_device_notify_remove(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff8195f250)
Location: drivers/acpi/glue.c:401
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff8195f250-ffffffff8195f2c4: acpi_device_notify_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_device_notify_remove(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff819a5650)
Location: drivers/acpi/glue.c:401
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff819a5650-ffffffff819a56c4: acpi_device_notify_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_device_notify_remove(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff819edfd0)
Location: drivers/acpi/glue.c:401
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff819edfd0-ffffffff819ee044: acpi_device_notify_remove (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffff80001076a988)
Location: drivers/acpi/glue.c:345
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_platform_notify
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff815d0a0a)
Location: drivers/acpi/glue.c:345
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_platform_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff815ba5ca)
Location: drivers/acpi/glue.c:345
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_platform_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff815d280a)
Location: drivers/acpi/glue.c:345
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_platform_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff815ec6ca)
Location: drivers/acpi/glue.c:345
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_platform_notify
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
