# Function: <code>__acpi_processor_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __acpi_processor_start(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_driver.c (ffffffff814ac0e1)
Location: drivers/acpi/processor_driver.c:234
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_cpu_soft_notify
  - drivers/acpi/processor_driver.c:acpi_processor_start
```
**Symbols:**

```
ffffffff814ac0e1-ffffffff814ac280: __acpi_processor_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __acpi_processor_start(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_driver.c (ffffffff814fb41b)
Location: drivers/acpi/processor_driver.c:235
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_cpu_soft_notify
```
**Symbols:**

```
ffffffff814fb41b-ffffffff814fb5bc: __acpi_processor_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __acpi_processor_start(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_driver.c (ffffffff8151e0b0)
Location: drivers/acpi/processor_driver.c:226
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff8151e0b0-ffffffff8151e259: __acpi_processor_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __acpi_processor_start(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_driver.c (ffffffff8152f2d0)
Location: drivers/acpi/processor_driver.c:226
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff8152f2d0-ffffffff8152f4ee: __acpi_processor_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __acpi_processor_start(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_driver.c (ffffffff8158ffd0)
Location: drivers/acpi/processor_driver.c:226
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff8158ffd0-ffffffff815901ee: __acpi_processor_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __acpi_processor_start(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_driver.c (ffffffff815c73c0)
Location: drivers/acpi/processor_driver.c:226
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff815c73c0-ffffffff815c75d6: __acpi_processor_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __acpi_processor_start(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_driver.c (ffffffff815e0980)
Location: drivers/acpi/processor_driver.c:226
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff815e0980-ffffffff815e0b96: __acpi_processor_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __acpi_processor_start(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: drivers/acpi/processor_driver.c:213
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff81612500-ffffffff816126d8: __acpi_processor_start (STB_LOCAL)
ffffffff81612884-ffffffff816128ce: __acpi_processor_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __acpi_processor_start(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: drivers/acpi/processor_driver.c:213
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff816339b0-ffffffff81633b88: __acpi_processor_start (STB_LOCAL)
ffffffff81633d84-ffffffff81633dce: __acpi_processor_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __acpi_processor_start(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_driver.c (ffffffff816e0930)
Location: drivers/acpi/processor_driver.c:213
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff816e0930-ffffffff816e0a3a: __acpi_processor_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __acpi_processor_start(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_driver.c (ffffffff816fe750)
Location: drivers/acpi/processor_driver.c:213
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff816fe750-ffffffff816fe85a: __acpi_processor_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __acpi_processor_start(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: drivers/acpi/processor_driver.c:209
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff816e0370-ffffffff816e0548: __acpi_processor_start (STB_LOCAL)
ffffffff81bf43e4-ffffffff81bf442e: __acpi_processor_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __acpi_processor_start(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: drivers/acpi/processor_driver.c:209
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff817585d0-ffffffff817587a8: __acpi_processor_start (STB_LOCAL)
ffffffff81cf135e-ffffffff81cf13a8: __acpi_processor_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __acpi_processor_start(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: drivers/acpi/processor_driver.c:213
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff8188bba0-ffffffff8188bd87: __acpi_processor_start (STB_LOCAL)
ffffffff81eb92d4-ffffffff81eb931c: __acpi_processor_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __acpi_processor_start(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_driver.c (ffffffff819d2810)
Location: drivers/acpi/processor_driver.c:155
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff819d2810-ffffffff819d2911: __acpi_processor_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __acpi_processor_start(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_driver.c (ffffffff81a19e30)
Location: drivers/acpi/processor_driver.c:155
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff81a19e30-ffffffff81a19f31: __acpi_processor_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __acpi_processor_start(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_driver.c (ffffffff81a65130)
Location: drivers/acpi/processor_driver.c:155
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff81a65130-ffffffff81a65231: __acpi_processor_start (STB_LOCAL)
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
int __acpi_processor_start(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_driver.c (ffff8000107a1e68)
Location: drivers/acpi/processor_driver.c:213
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffff8000107a1e68-ffff8000107a1f28: __acpi_processor_start (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __acpi_processor_start(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: drivers/acpi/processor_driver.c:213
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff81603500-ffffffff816036d8: __acpi_processor_start (STB_LOCAL)
ffffffff816038d4-ffffffff8160391e: __acpi_processor_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __acpi_processor_start(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: drivers/acpi/processor_driver.c:213
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff815ee5b0-ffffffff815ee788: __acpi_processor_start (STB_LOCAL)
ffffffff815ee984-ffffffff815ee9ce: __acpi_processor_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __acpi_processor_start(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: drivers/acpi/processor_driver.c:213
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff81627c90-ffffffff81627e68: __acpi_processor_start (STB_LOCAL)
ffffffff81628064-ffffffff816280ae: __acpi_processor_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __acpi_processor_start(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: drivers/acpi/processor_driver.c:213
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff81641b40-ffffffff81641d18: __acpi_processor_start (STB_LOCAL)
ffffffff81641f14-ffffffff81641f5e: __acpi_processor_start.cold (STB_LOCAL)
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
