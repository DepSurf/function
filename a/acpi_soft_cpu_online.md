# Function: <code>acpi_soft_cpu_online</code>

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
int acpi_soft_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_driver.c (ffffffff8151e2c8)
Location: drivers/acpi/processor_driver.c:113
Inline: False
```
**Symbols:**

```
ffffffff8151e2c8-ffffffff8151e391: acpi_soft_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_soft_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_driver.c (ffffffff8152f550)
Location: drivers/acpi/processor_driver.c:113
Inline: False
```
**Symbols:**

```
ffffffff8152f550-ffffffff8152f611: acpi_soft_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_soft_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_driver.c (ffffffff81590240)
Location: drivers/acpi/processor_driver.c:113
Inline: False
```
**Symbols:**

```
ffffffff81590240-ffffffff81590301: acpi_soft_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_soft_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: drivers/acpi/processor_driver.c:113
Inline: False
```
**Symbols:**

```
ffffffff815c7630-ffffffff815c76c2: acpi_soft_cpu_online (STB_LOCAL)
ffffffff815c7784-ffffffff815c77be: acpi_soft_cpu_online.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_soft_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: drivers/acpi/processor_driver.c:113
Inline: False
```
**Symbols:**

```
ffffffff815e0bf0-ffffffff815e0c82: acpi_soft_cpu_online (STB_LOCAL)
ffffffff815e0d44-ffffffff815e0d7e: acpi_soft_cpu_online.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_soft_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: drivers/acpi/processor_driver.c:100
Inline: False
```
**Symbols:**

```
ffffffff81612730-ffffffff816127c7: acpi_soft_cpu_online (STB_LOCAL)
ffffffff816128ce-ffffffff8161290e: acpi_soft_cpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_soft_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: drivers/acpi/processor_driver.c:100
Inline: False
```
**Symbols:**

```
ffffffff81633be0-ffffffff81633c77: acpi_soft_cpu_online (STB_LOCAL)
ffffffff81633dce-ffffffff81633e0e: acpi_soft_cpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_soft_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: drivers/acpi/processor_driver.c:100
Inline: False
```
**Symbols:**

```
ffffffff816e0a90-ffffffff816e0b23: acpi_soft_cpu_online (STB_LOCAL)
ffffffff816e0c9e-ffffffff816e0cde: acpi_soft_cpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_soft_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: drivers/acpi/processor_driver.c:100
Inline: False
```
**Symbols:**

```
ffffffff816fe8b0-ffffffff816fe943: acpi_soft_cpu_online (STB_LOCAL)
ffffffff81c02a52-ffffffff81c02a92: acpi_soft_cpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_soft_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: drivers/acpi/processor_driver.c:96
Inline: False
```
**Symbols:**

```
ffffffff816e05a0-ffffffff816e0633: acpi_soft_cpu_online (STB_LOCAL)
ffffffff81bf442e-ffffffff81bf446e: acpi_soft_cpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_soft_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: drivers/acpi/processor_driver.c:96
Inline: False
```
**Symbols:**

```
ffffffff81758800-ffffffff817588b2: acpi_soft_cpu_online (STB_LOCAL)
ffffffff81cf13a8-ffffffff81cf13e8: acpi_soft_cpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_soft_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: drivers/acpi/processor_driver.c:96
Inline: False
```
**Symbols:**

```
ffffffff8188bde0-ffffffff8188be6d: acpi_soft_cpu_online (STB_LOCAL)
ffffffff81eb931c-ffffffff81eb9355: acpi_soft_cpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_soft_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_driver.c (ffffffff819d2a10)
Location: drivers/acpi/processor_driver.c:96
Inline: False
```
**Symbols:**

```
ffffffff819d2a10-ffffffff819d2ae1: acpi_soft_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_soft_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_driver.c (ffffffff81a1a030)
Location: drivers/acpi/processor_driver.c:96
Inline: False
```
**Symbols:**

```
ffffffff81a1a030-ffffffff81a1a101: acpi_soft_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_soft_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_driver.c (ffffffff81a65330)
Location: drivers/acpi/processor_driver.c:96
Inline: False
```
**Symbols:**

```
ffffffff81a65330-ffffffff81a65401: acpi_soft_cpu_online (STB_LOCAL)
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
int acpi_soft_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_driver.c (ffff8000107a2068)
Location: drivers/acpi/processor_driver.c:100
Inline: False
```
**Symbols:**

```
ffff8000107a2068-ffff8000107a2140: acpi_soft_cpu_online (STB_LOCAL)
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
int acpi_soft_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: drivers/acpi/processor_driver.c:100
Inline: False
```
**Symbols:**

```
ffffffff81603730-ffffffff816037c7: acpi_soft_cpu_online (STB_LOCAL)
ffffffff8160391e-ffffffff8160395e: acpi_soft_cpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_soft_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: drivers/acpi/processor_driver.c:100
Inline: False
```
**Symbols:**

```
ffffffff815ee7e0-ffffffff815ee877: acpi_soft_cpu_online (STB_LOCAL)
ffffffff815ee9ce-ffffffff815eea0e: acpi_soft_cpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_soft_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: drivers/acpi/processor_driver.c:100
Inline: False
```
**Symbols:**

```
ffffffff81627ec0-ffffffff81627f57: acpi_soft_cpu_online (STB_LOCAL)
ffffffff816280ae-ffffffff816280ee: acpi_soft_cpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_soft_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: drivers/acpi/processor_driver.c:100
Inline: False
```
**Symbols:**

```
ffffffff81641d70-ffffffff81641e07: acpi_soft_cpu_online (STB_LOCAL)
ffffffff81641f5e-ffffffff81641f9e: acpi_soft_cpu_online.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
