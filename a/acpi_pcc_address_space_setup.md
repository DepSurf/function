# Function: <code>acpi_pcc_address_space_setup</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_pcc_address_space_setup(acpi_handle region_handle, u32 function, void *handler_context, void **region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_pcc.c (0)
Location: drivers/acpi/acpi_pcc.c:44
Inline: False
```
**Symbols:**

```
ffffffff81842ff0-ffffffff818430b9: acpi_pcc_address_space_setup (STB_LOCAL)
ffffffff81eb8f2a-ffffffff81eb8f60: acpi_pcc_address_space_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_pcc_address_space_setup(acpi_handle region_handle, u32 function, void *handler_context, void **region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_pcc.c (0)
Location: drivers/acpi/acpi_pcc.c:50
Inline: False
```
**Symbols:**

```
ffffffff8197a1b0-ffffffff8197a325: acpi_pcc_address_space_setup (STB_LOCAL)
ffffffff82091e83-ffffffff82091ea0: acpi_pcc_address_space_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_pcc_address_space_setup(acpi_handle region_handle, u32 function, void *handler_context, void **region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_pcc.c (0)
Location: drivers/acpi/acpi_pcc.c:50
Inline: False
```
**Symbols:**

```
ffffffff819c0c40-ffffffff819c0db5: acpi_pcc_address_space_setup (STB_LOCAL)
ffffffff82112781-ffffffff8211279e: acpi_pcc_address_space_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_pcc_address_space_setup(acpi_handle region_handle, u32 function, void *handler_context, void **region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_pcc.c (0)
Location: drivers/acpi/acpi_pcc.c:50
Inline: False
```
**Symbols:**

```
ffffffff81a0b630-ffffffff81a0b7d9: acpi_pcc_address_space_setup (STB_LOCAL)
ffffffff821f04d5-ffffffff821f04f2: acpi_pcc_address_space_setup.cold (STB_LOCAL)
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
