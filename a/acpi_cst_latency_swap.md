# Function: <code>acpi_cst_latency_swap</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_cst_latency_swap(void *a, void *b, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff816e0760)
Location: drivers/acpi/processor_idle.c:400
Inline: False
```
**Symbols:**

```
ffffffff816e0760-ffffffff816e0781: acpi_cst_latency_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_cst_latency_swap(void *a, void *b, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff817589e0)
Location: drivers/acpi/processor_idle.c:400
Inline: False
```
**Symbols:**

```
ffffffff817589e0-ffffffff81758a01: acpi_cst_latency_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void acpi_cst_latency_swap(void *a, void *b, int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff8188c610)
Location: drivers/acpi/processor_idle.c:402
Inline: True
```
**Symbols:**

```
ffffffff8188c610-ffffffff8188c63d: acpi_cst_latency_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void acpi_cst_latency_swap(void *a, void *b, int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff819d3e40)
Location: drivers/acpi/processor_idle.c:401
Inline: True
```
**Symbols:**

```
ffffffff819d3e40-ffffffff819d3e6d: acpi_cst_latency_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void acpi_cst_latency_swap(void *a, void *b, int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81a1b570)
Location: drivers/acpi/processor_idle.c:401
Inline: True
```
**Symbols:**

```
ffffffff81a1b570-ffffffff81a1b59d: acpi_cst_latency_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_cst_latency_swap(void *a, void *b, int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81a66860)
Location: drivers/acpi/processor_idle.c:401
Inline: True
```
**Symbols:**

```
ffffffff81a66860-ffffffff81a6688d: acpi_cst_latency_swap (STB_LOCAL)
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
