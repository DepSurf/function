# Function: <code>lpit_read_residency_counter_us</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int lpit_read_residency_counter_us(u64 *counter, bool io_mem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpit.c (ffffffff81550080)
Location: drivers/acpi/acpi_lpit.c:32
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpit.c:low_power_idle_cpu_residency_us_show
  - drivers/acpi/acpi_lpit.c:low_power_idle_system_residency_us_show
```
**Symbols:**

```
ffffffff81550080-ffffffff81550182: lpit_read_residency_counter_us (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int lpit_read_residency_counter_us(u64 *counter, bool io_mem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpit.c (ffffffff81586950)
Location: drivers/acpi/acpi_lpit.c:32
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpit.c:low_power_idle_cpu_residency_us_show
  - drivers/acpi/acpi_lpit.c:low_power_idle_system_residency_us_show
```
**Symbols:**

```
ffffffff81586950-ffffffff81586a52: lpit_read_residency_counter_us (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int lpit_read_residency_counter_us(u64 *counter, bool io_mem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpit.c (ffffffff8159ec70)
Location: drivers/acpi/acpi_lpit.c:32
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpit.c:low_power_idle_cpu_residency_us_show
  - drivers/acpi/acpi_lpit.c:low_power_idle_system_residency_us_show
```
**Symbols:**

```
ffffffff8159ec70-ffffffff8159ed72: lpit_read_residency_counter_us (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int lpit_read_residency_counter_us(u64 *counter, bool io_mem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpit.c (ffffffff815d01b0)
Location: drivers/acpi/acpi_lpit.c:24
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpit.c:low_power_idle_cpu_residency_us_show
  - drivers/acpi/acpi_lpit.c:low_power_idle_system_residency_us_show
```
**Symbols:**

```
ffffffff815d01b0-ffffffff815d02b2: lpit_read_residency_counter_us (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int lpit_read_residency_counter_us(u64 *counter, bool io_mem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpit.c (ffffffff815f1420)
Location: drivers/acpi/acpi_lpit.c:24
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpit.c:low_power_idle_cpu_residency_us_show
  - drivers/acpi/acpi_lpit.c:low_power_idle_system_residency_us_show
```
**Symbols:**

```
ffffffff815f1420-ffffffff815f1522: lpit_read_residency_counter_us (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpit.c (ffffffff8169d515)
Location: drivers/acpi/acpi_lpit.c:24
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpit.c:low_power_idle_cpu_residency_us_show
  - drivers/acpi/acpi_lpit.c:low_power_idle_system_residency_us_show
Direct callers:
  - drivers/acpi/acpi_lpit.c:low_power_idle_cpu_residency_us_show
```
**Symbols:**

```
ffffffff8169d430-ffffffff8169d4e8: lpit_read_residency_counter_us.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpit.c (ffffffff816bae05)
Location: drivers/acpi/acpi_lpit.c:24
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpit.c:low_power_idle_cpu_residency_us_show
  - drivers/acpi/acpi_lpit.c:low_power_idle_system_residency_us_show
Direct callers:
  - drivers/acpi/acpi_lpit.c:low_power_idle_cpu_residency_us_show
```
**Symbols:**

```
ffffffff816bad20-ffffffff816badd8: lpit_read_residency_counter_us.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int lpit_read_residency_counter_us(u64 *counter, bool io_mem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpit.c (ffffffff8169ce30)
Location: drivers/acpi/acpi_lpit.c:24
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpit.c:low_power_idle_cpu_residency_us_show
  - drivers/acpi/acpi_lpit.c:low_power_idle_system_residency_us_show
```
**Symbols:**

```
ffffffff8169ce30-ffffffff8169cf3c: lpit_read_residency_counter_us (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lpit_read_residency_counter_us(u64 *counter, bool io_mem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpit.c (ffffffff81713204)
Location: drivers/acpi/acpi_lpit.c:24
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpit.c:low_power_idle_cpu_residency_us_show
  - drivers/acpi/acpi_lpit.c:low_power_idle_system_residency_us_show
```
**Symbols:**

```
ffffffff81713190-ffffffff817132ca: lpit_read_residency_counter_us (STB_LOCAL)
ffffffff81cf0ec1-ffffffff81cf0f2d: lpit_read_residency_counter_us.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lpit_read_residency_counter_us(u64 *counter, bool io_mem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpit.c (ffffffff8184288c)
Location: drivers/acpi/acpi_lpit.c:24
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpit.c:low_power_idle_cpu_residency_us_show
  - drivers/acpi/acpi_lpit.c:low_power_idle_system_residency_us_show
```
**Symbols:**

```
ffffffff81842800-ffffffff81842958: lpit_read_residency_counter_us (STB_LOCAL)
ffffffff81eb8d6c-ffffffff81eb8dd8: lpit_read_residency_counter_us.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lpit_read_residency_counter_us(u64 *counter, bool io_mem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpit.c (ffffffff8197981c)
Location: drivers/acpi/acpi_lpit.c:24
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpit.c:low_power_idle_cpu_residency_us_show
  - drivers/acpi/acpi_lpit.c:low_power_idle_system_residency_us_show
```
**Symbols:**

```
ffffffff81979790-ffffffff819798e8: lpit_read_residency_counter_us (STB_LOCAL)
ffffffff82091dc8-ffffffff82091e34: lpit_read_residency_counter_us.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lpit_read_residency_counter_us(u64 *counter, bool io_mem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpit.c (ffffffff819c02ac)
Location: drivers/acpi/acpi_lpit.c:25
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpit.c:low_power_idle_cpu_residency_us_show
  - drivers/acpi/acpi_lpit.c:low_power_idle_system_residency_us_show
```
**Symbols:**

```
ffffffff819c0220-ffffffff819c0378: lpit_read_residency_counter_us (STB_LOCAL)
ffffffff821126b2-ffffffff8211271e: lpit_read_residency_counter_us.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lpit_read_residency_counter_us(u64 *counter, bool io_mem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpit.c (ffffffff81a0ad2c)
Location: drivers/acpi/acpi_lpit.c:25
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpit.c:low_power_idle_cpu_residency_us_show
  - drivers/acpi/acpi_lpit.c:low_power_idle_system_residency_us_show
```
**Symbols:**

```
ffffffff81a0aca0-ffffffff81a0adf8: lpit_read_residency_counter_us (STB_LOCAL)
ffffffff821f041a-ffffffff821f0486: lpit_read_residency_counter_us.cold (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int lpit_read_residency_counter_us(u64 *counter, bool io_mem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpit.c (ffffffff815e00b0)
Location: drivers/acpi/acpi_lpit.c:24
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpit.c:low_power_idle_cpu_residency_us_show
  - drivers/acpi/acpi_lpit.c:low_power_idle_system_residency_us_show
```
**Symbols:**

```
ffffffff815e00b0-ffffffff815e01b2: lpit_read_residency_counter_us (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int lpit_read_residency_counter_us(u64 *counter, bool io_mem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpit.c (ffffffff815cb6f0)
Location: drivers/acpi/acpi_lpit.c:24
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpit.c:low_power_idle_cpu_residency_us_show
  - drivers/acpi/acpi_lpit.c:low_power_idle_system_residency_us_show
```
**Symbols:**

```
ffffffff815cb6f0-ffffffff815cb835: lpit_read_residency_counter_us (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int lpit_read_residency_counter_us(u64 *counter, bool io_mem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpit.c (ffffffff815e5700)
Location: drivers/acpi/acpi_lpit.c:24
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpit.c:low_power_idle_cpu_residency_us_show
  - drivers/acpi/acpi_lpit.c:low_power_idle_system_residency_us_show
```
**Symbols:**

```
ffffffff815e5700-ffffffff815e5802: lpit_read_residency_counter_us (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int lpit_read_residency_counter_us(u64 *counter, bool io_mem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpit.c (ffffffff815ff5b0)
Location: drivers/acpi/acpi_lpit.c:24
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpit.c:low_power_idle_cpu_residency_us_show
  - drivers/acpi/acpi_lpit.c:low_power_idle_system_residency_us_show
```
**Symbols:**

```
ffffffff815ff5b0-ffffffff815ff6b2: lpit_read_residency_counter_us (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
