# Function: <code>__acpi_power_on</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff814888ab)
Location: drivers/acpi/power.c:225
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff814d8349)
Location: drivers/acpi/power.c:225
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff814faa31)
Location: drivers/acpi/power.c:225
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
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
In drivers/acpi/power.c (ffffffff81509eee)
Location: drivers/acpi/power.c:226
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (ffffffff8154b330)
Location: drivers/acpi/power.c:226
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
```
**Symbols:**

```
ffffffff8154b330-ffffffff8154b3ad: __acpi_power_on.isra.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (ffffffff81581960)
Location: drivers/acpi/power.c:226
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
```
**Symbols:**

```
ffffffff81581960-ffffffff815819dd: __acpi_power_on.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (ffffffff81599a20)
Location: drivers/acpi/power.c:248
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
```
**Symbols:**

```
ffffffff81599a20-ffffffff81599a9d: __acpi_power_on.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __acpi_power_on(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815cae70)
Location: drivers/acpi/power.c:353
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
```
**Symbols:**

```
ffffffff815cae70-ffffffff815caf7f: __acpi_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __acpi_power_on(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815ec0f0)
Location: drivers/acpi/power.c:353
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
```
**Symbols:**

```
ffffffff815ec0f0-ffffffff815ec1ff: __acpi_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __acpi_power_on(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81697cb0)
Location: drivers/acpi/power.c:351
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
```
**Symbols:**

```
ffffffff81697cb0-ffffffff81697dbf: __acpi_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __acpi_power_on(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff816b4de0)
Location: drivers/acpi/power.c:351
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
```
**Symbols:**

```
ffffffff816b4de0-ffffffff816b4eef: __acpi_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __acpi_power_on(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81696e90)
Location: drivers/acpi/power.c:349
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
```
**Symbols:**

```
ffffffff81696e90-ffffffff81696f6e: __acpi_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __acpi_power_on(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff8170cd30)
Location: drivers/acpi/power.c:361
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
  - drivers/acpi/power.c:acpi_power_on_unlocked
```
**Symbols:**

```
ffffffff8170cd30-ffffffff8170ce24: __acpi_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __acpi_power_on(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff8183b4f0)
Location: drivers/acpi/power.c:361
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_power_on_unlocked
```
**Symbols:**

```
ffffffff8183b4f0-ffffffff8183b5f3: __acpi_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __acpi_power_on(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81970c60)
Location: drivers/acpi/power.c:361
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_power_on_unlocked
```
**Symbols:**

```
ffffffff81970c60-ffffffff81970d66: __acpi_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __acpi_power_on(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff819b72f0)
Location: drivers/acpi/power.c:362
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_power_on_unlocked
```
**Symbols:**

```
ffffffff819b72f0-ffffffff819b73f4: __acpi_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __acpi_power_on(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81a018a0)
Location: drivers/acpi/power.c:362
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_power_on_unlocked
```
**Symbols:**

```
ffffffff81a018a0-ffffffff81a019a4: __acpi_power_on (STB_LOCAL)
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
int __acpi_power_on(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffff800010777800)
Location: drivers/acpi/power.c:353
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on
```
**Symbols:**

```
ffff800010777800-ffff8000107778e0: __acpi_power_on (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int __acpi_power_on(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815db470)
Location: drivers/acpi/power.c:353
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on
```
**Symbols:**

```
ffffffff815db470-ffffffff815db529: __acpi_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __acpi_power_on(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815c6ab0)
Location: drivers/acpi/power.c:353
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on
```
**Symbols:**

```
ffffffff815c6ab0-ffffffff815c6b69: __acpi_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __acpi_power_on(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815e03d0)
Location: drivers/acpi/power.c:353
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
```
**Symbols:**

```
ffffffff815e03d0-ffffffff815e04df: __acpi_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __acpi_power_on(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815fa290)
Location: drivers/acpi/power.c:353
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
```
**Symbols:**

```
ffffffff815fa290-ffffffff815fa39f: __acpi_power_on (STB_LOCAL)
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
