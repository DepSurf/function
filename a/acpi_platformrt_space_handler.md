# Function: <code>acpi_platformrt_space_handler</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_platformrt_space_handler(u32 function, acpi_physical_address addr, u32 bits, acpi_integer *value, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/prmt.c (0)
Location: drivers/acpi/prmt.c:210
Inline: False
```
**Symbols:**

```
ffffffff817135f0-ffffffff817137c3: acpi_platformrt_space_handler (STB_LOCAL)
ffffffff81cf100a-ffffffff81cf1044: acpi_platformrt_space_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_platformrt_space_handler(u32 function, acpi_physical_address addr, u32 bits, acpi_integer *value, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/prmt.c (0)
Location: drivers/acpi/prmt.c:227
Inline: False
```
**Symbols:**

```
ffffffff81842cd0-ffffffff81842efd: acpi_platformrt_space_handler (STB_LOCAL)
ffffffff81eb8ec2-ffffffff81eb8efc: acpi_platformrt_space_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_platformrt_space_handler(u32 function, acpi_physical_address addr, u32 bits, acpi_integer *value, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/prmt.c (0)
Location: drivers/acpi/prmt.c:227
Inline: False
```
**Symbols:**

```
ffffffff81979df0-ffffffff8197a065: acpi_platformrt_space_handler (STB_LOCAL)
ffffffff82091e49-ffffffff82091e83: acpi_platformrt_space_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_platformrt_space_handler(u32 function, acpi_physical_address addr, u32 bits, acpi_integer *value, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/prmt.c (0)
Location: drivers/acpi/prmt.c:227
Inline: False
```
**Symbols:**

```
ffffffff819c0880-ffffffff819c0aff: acpi_platformrt_space_handler (STB_LOCAL)
ffffffff82112733-ffffffff82112781: acpi_platformrt_space_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_platformrt_space_handler(u32 function, acpi_physical_address addr, u32 bits, acpi_integer *value, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/prmt.c (0)
Location: drivers/acpi/prmt.c:227
Inline: False
```
**Symbols:**

```
ffffffff81a0b300-ffffffff81a0b4e2: acpi_platformrt_space_handler (STB_LOCAL)
ffffffff821f049b-ffffffff821f04d5: acpi_platformrt_space_handler.cold (STB_LOCAL)
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
