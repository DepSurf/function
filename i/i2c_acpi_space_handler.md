# Function: <code>i2c_acpi_space_handler</code>

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
acpi_status i2c_acpi_space_handler(u32 function, acpi_physical_address command, u32 bits, u64 *value64, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170e9a0)
Location: drivers/i2c/i2c-core.c:483
Inline: False
```
**Symbols:**

```
ffffffff8170e9a0-ffffffff8170eded: i2c_acpi_space_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status i2c_acpi_space_handler(u32 function, acpi_physical_address command, u32 bits, u64 *value64, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff817245f0)
Location: drivers/i2c/i2c-core-acpi.c:486
Inline: False
```
**Symbols:**

```
ffffffff817245f0-ffffffff81724b07: i2c_acpi_space_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status i2c_acpi_space_handler(u32 function, acpi_physical_address command, u32 bits, u64 *value64, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81795ac0)
Location: drivers/i2c/i2c-core-acpi.c:486
Inline: False
```
**Symbols:**

```
ffffffff81795ac0-ffffffff81795fdd: i2c_acpi_space_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status i2c_acpi_space_handler(u32 function, acpi_physical_address command, u32 bits, u64 *value64, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff817d8560)
Location: drivers/i2c/i2c-core-acpi.c:502
Inline: False
```
**Symbols:**

```
ffffffff817d8560-ffffffff817d8b36: i2c_acpi_space_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status i2c_acpi_space_handler(u32 function, acpi_physical_address command, u32 bits, u64 *value64, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff817ff710)
Location: drivers/i2c/i2c-core-acpi.c:534
Inline: False
```
**Symbols:**

```
ffffffff817ff710-ffffffff817ffcd6: i2c_acpi_space_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
acpi_status i2c_acpi_space_handler(u32 function, acpi_physical_address command, u32 bits, u64 *value64, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:557
Inline: False
```
**Symbols:**

```
ffffffff81840920-ffffffff81840e34: i2c_acpi_space_handler (STB_LOCAL)
ffffffff81841181-ffffffff8184120e: i2c_acpi_space_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
acpi_status i2c_acpi_space_handler(u32 function, acpi_physical_address command, u32 bits, u64 *value64, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:586
Inline: False
```
**Symbols:**

```
ffffffff81872280-ffffffff81872794: i2c_acpi_space_handler (STB_LOCAL)
ffffffff81872afa-ffffffff81872b87: i2c_acpi_space_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
acpi_status i2c_acpi_space_handler(u32 function, acpi_physical_address command, u32 bits, u64 *value64, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:578
Inline: False
```
**Symbols:**

```
ffffffff819466b0-ffffffff81946922: i2c_acpi_space_handler (STB_LOCAL)
ffffffff81946cb8-ffffffff81946cdb: i2c_acpi_space_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
acpi_status i2c_acpi_space_handler(u32 function, acpi_physical_address command, u32 bits, u64 *value64, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:578
Inline: False
```
**Symbols:**

```
ffffffff8194c610-ffffffff8194c882: i2c_acpi_space_handler (STB_LOCAL)
ffffffff81c24e64-ffffffff81c24e87: i2c_acpi_space_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
acpi_status i2c_acpi_space_handler(u32 function, acpi_physical_address command, u32 bits, u64 *value64, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:574
Inline: False
```
**Symbols:**

```
ffffffff8192fdd0-ffffffff81930193: i2c_acpi_space_handler (STB_LOCAL)
ffffffff81c16e9c-ffffffff81c16ee7: i2c_acpi_space_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
acpi_status i2c_acpi_space_handler(u32 function, acpi_physical_address command, u32 bits, u64 *value64, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:607
Inline: False
```
**Symbols:**

```
ffffffff819d30a0-ffffffff819d3463: i2c_acpi_space_handler (STB_LOCAL)
ffffffff81d25b96-ffffffff81d25be1: i2c_acpi_space_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
acpi_status i2c_acpi_space_handler(u32 function, acpi_physical_address command, u32 bits, u64 *value64, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:623
Inline: False
```
**Symbols:**

```
ffffffff81b35870-ffffffff81b35b05: i2c_acpi_space_handler (STB_LOCAL)
ffffffff81ef190d-ffffffff81ef1930: i2c_acpi_space_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status i2c_acpi_space_handler(u32 function, acpi_physical_address command, u32 bits, u64 *value64, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81ccaad0)
Location: drivers/i2c/i2c-core-acpi.c:643
Inline: False
```
**Symbols:**

```
ffffffff81ccaad0-ffffffff81ccad6f: i2c_acpi_space_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status i2c_acpi_space_handler(u32 function, acpi_physical_address command, u32 bits, u64 *value64, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81d32860)
Location: drivers/i2c/i2c-core-acpi.c:632
Inline: False
```
**Symbols:**

```
ffffffff81d32860-ffffffff81d32b0e: i2c_acpi_space_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status i2c_acpi_space_handler(u32 function, acpi_physical_address command, u32 bits, u64 *value64, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81de8840)
Location: drivers/i2c/i2c-core-acpi.c:632
Inline: False
```
**Symbols:**

```
ffffffff81de8840-ffffffff81de8b23: i2c_acpi_space_handler (STB_LOCAL)
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
acpi_status i2c_acpi_space_handler(u32 function, acpi_physical_address command, u32 bits, u64 *value64, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffff800010ab5be8)
Location: drivers/i2c/i2c-core-acpi.c:586
Inline: False
```
**Symbols:**

```
ffff800010ab5be8-ffff800010ab6004: i2c_acpi_space_handler (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
acpi_status i2c_acpi_space_handler(u32 function, acpi_physical_address command, u32 bits, u64 *value64, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:586
Inline: False
```
**Symbols:**

```
ffffffff81866410-ffffffff81866924: i2c_acpi_space_handler (STB_LOCAL)
ffffffff81866c8a-ffffffff81866d17: i2c_acpi_space_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
acpi_status i2c_acpi_space_handler(u32 function, acpi_physical_address command, u32 bits, u64 *value64, void *handler_context, void *region_context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:586
Inline: False
```
**Symbols:**

```
ffffffff818816c0-ffffffff81881bd4: i2c_acpi_space_handler (STB_LOCAL)
ffffffff81881f3a-ffffffff81881fc7: i2c_acpi_space_handler.cold (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
