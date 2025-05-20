# Function: <code>hibernation_set_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void hibernation_set_ops(const struct platform_hibernation_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810cf140)
Location: kernel/power/hibernate.c:77
Inline: True
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff810cf140-ffffffff810cf234: hibernation_set_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void hibernation_set_ops(const struct platform_hibernation_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810d3be0)
Location: kernel/power/hibernate.c:78
Inline: True
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff810d3be0-ffffffff810d3cd4: hibernation_set_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void hibernation_set_ops(const struct platform_hibernation_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810da770)
Location: kernel/power/hibernate.c:78
Inline: True
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff810da770-ffffffff810da864: hibernation_set_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void hibernation_set_ops(const struct platform_hibernation_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810d9520)
Location: kernel/power/hibernate.c:80
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff810d9520-ffffffff810d9605: hibernation_set_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void hibernation_set_ops(const struct platform_hibernation_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810e16b0)
Location: kernel/power/hibernate.c:80
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff810e16b0-ffffffff810e1795: hibernation_set_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void hibernation_set_ops(const struct platform_hibernation_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810e9d10)
Location: kernel/power/hibernate.c:80
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff810e9d10-ffffffff810e9dae: hibernation_set_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void hibernation_set_ops(const struct platform_hibernation_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810f5330)
Location: kernel/power/hibernate.c:80
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff810f5330-ffffffff810f53ce: hibernation_set_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void hibernation_set_ops(const struct platform_hibernation_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:78
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff810fe79b-ffffffff810fe7ae: hibernation_set_ops.cold (STB_LOCAL)
ffffffff810fd820-ffffffff810fd8db: hibernation_set_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void hibernation_set_ops(const struct platform_hibernation_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81109f80)
Location: kernel/power/hibernate.c:79
Inline: True
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff81109f80-ffffffff8110a018: hibernation_set_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hibernation_set_ops(const struct platform_hibernation_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81114800)
Location: kernel/power/hibernate.c:91
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff81114800-ffffffff8111489e: hibernation_set_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hibernation_set_ops(const struct platform_hibernation_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81111030)
Location: kernel/power/hibernate.c:91
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff81111030-ffffffff811110ce: hibernation_set_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hibernation_set_ops(const struct platform_hibernation_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81111a90)
Location: kernel/power/hibernate.c:91
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff81111a90-ffffffff81111b2e: hibernation_set_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hibernation_set_ops(const struct platform_hibernation_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff811319b0)
Location: kernel/power/hibernate.c:94
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff811319b0-ffffffff81131a4e: hibernation_set_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hibernation_set_ops(const struct platform_hibernation_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff811535a0)
Location: kernel/power/hibernate.c:93
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff811535a0-ffffffff8115364a: hibernation_set_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hibernation_set_ops(const struct platform_hibernation_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff811829f0)
Location: kernel/power/hibernate.c:93
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff811829f0-ffffffff81182aa2: hibernation_set_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hibernation_set_ops(const struct platform_hibernation_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff811938a0)
Location: kernel/power/hibernate.c:94
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff811938a0-ffffffff81193952: hibernation_set_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hibernation_set_ops(const struct platform_hibernation_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff811a2290)
Location: kernel/power/hibernate.c:94
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff811a2290-ffffffff811a2342: hibernation_set_ops (STB_GLOBAL)
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
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void hibernation_set_ops(const struct platform_hibernation_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (c03bc360)
Location: kernel/power/hibernate.c:79
Inline: True
```
**Symbols:**

```
c03bc360-c03bc458: hibernation_set_ops (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void hibernation_set_ops(const struct platform_hibernation_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff811021e0)
Location: kernel/power/hibernate.c:79
Inline: True
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff811021e0-ffffffff81102278: hibernation_set_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void hibernation_set_ops(const struct platform_hibernation_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810f3470)
Location: kernel/power/hibernate.c:79
Inline: True
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff810f3470-ffffffff810f3508: hibernation_set_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void hibernation_set_ops(const struct platform_hibernation_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81100450)
Location: kernel/power/hibernate.c:79
Inline: True
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff81100450-ffffffff811004e8: hibernation_set_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void hibernation_set_ops(const struct platform_hibernation_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff8110b7f0)
Location: kernel/power/hibernate.c:79
Inline: True
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff8110b7f0-ffffffff8110b888: hibernation_set_ops (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
