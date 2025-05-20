# Function: <code>acpi_unregister_lps0_dev</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_unregister_lps0_dev(struct acpi_s2idle_dev_ops *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/x86/s2idle.c (ffffffff81841842)
Location: drivers/acpi/x86/s2idle.c:552
Inline: True
```
**Symbols:**

```
ffffffff81eb8b5c-ffffffff81eb8b71: acpi_unregister_lps0_dev.cold (STB_LOCAL)
ffffffff81841800-ffffffff8184188d: acpi_unregister_lps0_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_unregister_lps0_dev(struct acpi_s2idle_dev_ops *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/x86/s2idle.c (ffffffff81978402)
Location: drivers/acpi/x86/s2idle.c:609
Inline: True
```
**Symbols:**

```
ffffffff82091d67-ffffffff82091d7c: acpi_unregister_lps0_dev.cold (STB_LOCAL)
ffffffff819783c0-ffffffff8197844f: acpi_unregister_lps0_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_unregister_lps0_dev(struct acpi_s2idle_dev_ops *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/x86/s2idle.c (ffffffff819beec2)
Location: drivers/acpi/x86/s2idle.c:618
Inline: True
```
**Symbols:**

```
ffffffff82112658-ffffffff8211266d: acpi_unregister_lps0_dev.cold (STB_LOCAL)
ffffffff819bee80-ffffffff819bef0f: acpi_unregister_lps0_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_unregister_lps0_dev(struct acpi_s2idle_dev_ops *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/x86/s2idle.c (ffffffff81a096a2)
Location: drivers/acpi/x86/s2idle.c:655
Inline: True
```
**Symbols:**

```
ffffffff821f03c0-ffffffff821f03d5: acpi_unregister_lps0_dev.cold (STB_LOCAL)
ffffffff81a09660-ffffffff81a096ef: acpi_unregister_lps0_dev (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
