# Function: <code>acpi_sysfs_table_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_sysfs_table_handler(u32 event, void *table, void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff8148a054)
Location: drivers/acpi/sysfs.c:382
Inline: True
```
**Symbols:**

```
ffffffff8148a054-ffffffff8148a0e3: acpi_sysfs_table_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_sysfs_table_handler(u32 event, void *table, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff814d8e42)
Location: drivers/acpi/sysfs.c:381
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_table_handler
```
**Symbols:**

```
ffffffff814d8e42-ffffffff814d8ed1: acpi_sysfs_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_sysfs_table_handler(u32 event, void *table, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff814fb5d2)
Location: drivers/acpi/sysfs.c:387
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_table_handler
```
**Symbols:**

```
ffffffff814fb5d2-ffffffff814fb65c: acpi_sysfs_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_sysfs_table_handler(u32 event, void *table, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff8150acd0)
Location: drivers/acpi/sysfs.c:390
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_table_handler
```
**Symbols:**

```
ffffffff8150acd0-ffffffff8150ad67: acpi_sysfs_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_sysfs_table_handler(u32 event, void *table, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff8154d760)
Location: drivers/acpi/sysfs.c:403
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_table_handler
```
**Symbols:**

```
ffffffff8154d760-ffffffff8154d7f7: acpi_sysfs_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_sysfs_table_handler(u32 event, void *table, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff81583f60)
Location: drivers/acpi/sysfs.c:403
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_table_handler
```
**Symbols:**

```
ffffffff81583f60-ffffffff81583ffd: acpi_sysfs_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_sysfs_table_handler(u32 event, void *table, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff8159c090)
Location: drivers/acpi/sysfs.c:403
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_table_handler
```
**Symbols:**

```
ffffffff8159c090-ffffffff8159c12d: acpi_sysfs_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_sysfs_table_handler(u32 event, void *table, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff815cd720)
Location: drivers/acpi/sysfs.c:403
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_table_handler
```
**Symbols:**

```
ffffffff815cd720-ffffffff815cd7bc: acpi_sysfs_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_sysfs_table_handler(u32 event, void *table, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff815ee9a0)
Location: drivers/acpi/sysfs.c:403
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_table_handler
```
**Symbols:**

```
ffffffff815ee9a0-ffffffff815eea3c: acpi_sysfs_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_sysfs_table_handler(u32 event, void *table, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff8169a950)
Location: drivers/acpi/sysfs.c:403
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_table_handler
```
**Symbols:**

```
ffffffff8169a950-ffffffff8169a9ec: acpi_sysfs_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_sysfs_table_handler(u32 event, void *table, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff816b79d0)
Location: drivers/acpi/sysfs.c:403
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_table_handler
```
**Symbols:**

```
ffffffff816b79d0-ffffffff816b7a6c: acpi_sysfs_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_sysfs_table_handler(u32 event, void *table, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff81699a30)
Location: drivers/acpi/sysfs.c:385
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_table_handler
```
**Symbols:**

```
ffffffff81699a30-ffffffff81699acc: acpi_sysfs_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_sysfs_table_handler(u32 event, void *table, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff8170f8d0)
Location: drivers/acpi/sysfs.c:381
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_table_handler
  - drivers/acpi/bus.c:acpi_bus_table_handler
```
**Symbols:**

```
ffffffff8170f8d0-ffffffff8170f96c: acpi_sysfs_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_sysfs_table_handler(u32 event, void *table, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff8183e420)
Location: drivers/acpi/sysfs.c:381
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_table_handler
  - drivers/acpi/bus.c:acpi_bus_table_handler
```
**Symbols:**

```
ffffffff8183e420-ffffffff8183e4d7: acpi_sysfs_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_sysfs_table_handler(u32 event, void *table, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff81974320)
Location: drivers/acpi/sysfs.c:382
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_table_handler
  - drivers/acpi/bus.c:acpi_bus_table_handler
```
**Symbols:**

```
ffffffff81974320-ffffffff819743d7: acpi_sysfs_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_sysfs_table_handler(u32 event, void *table, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff819bab30)
Location: drivers/acpi/sysfs.c:382
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_table_handler
  - drivers/acpi/bus.c:acpi_bus_table_handler
```
**Symbols:**

```
ffffffff819bab30-ffffffff819babef: acpi_sysfs_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_sysfs_table_handler(u32 event, void *table, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff81a051e0)
Location: drivers/acpi/sysfs.c:382
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_table_handler
  - drivers/acpi/bus.c:acpi_bus_table_handler
```
**Symbols:**

```
ffffffff81a051e0-ffffffff81a052cb: acpi_sysfs_table_handler (STB_GLOBAL)
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
acpi_status acpi_sysfs_table_handler(u32 event, void *table, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffff800010779798)
Location: drivers/acpi/sysfs.c:403
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_table_handler
```
**Symbols:**

```
ffff800010779798-ffff800010779854: acpi_sysfs_table_handler (STB_GLOBAL)
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
acpi_status acpi_sysfs_table_handler(u32 event, void *table, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff815dd660)
Location: drivers/acpi/sysfs.c:403
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_table_handler
```
**Symbols:**

```
ffffffff815dd660-ffffffff815dd6fc: acpi_sysfs_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_sysfs_table_handler(u32 event, void *table, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff815c8ca0)
Location: drivers/acpi/sysfs.c:403
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_table_handler
```
**Symbols:**

```
ffffffff815c8ca0-ffffffff815c8d3c: acpi_sysfs_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_sysfs_table_handler(u32 event, void *table, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff815e2c80)
Location: drivers/acpi/sysfs.c:403
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_table_handler
```
**Symbols:**

```
ffffffff815e2c80-ffffffff815e2d1c: acpi_sysfs_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_sysfs_table_handler(u32 event, void *table, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff815fcb40)
Location: drivers/acpi/sysfs.c:403
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_table_handler
```
**Symbols:**

```
ffffffff815fcb40-ffffffff815fcbdc: acpi_sysfs_table_handler (STB_GLOBAL)
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
