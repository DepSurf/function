# Function: <code>acpi_table_parse_entries</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_table_parse_entries(char *id, long unsigned int table_size, int entry_id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff81fa0a47)
Location: drivers/acpi/tables.c:352
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_parse_madt
  - drivers/acpi/numa.c:acpi_numa_init
  - drivers/acpi/numa.c:acpi_numa_init
  - drivers/acpi/numa.c:acpi_numa_init
```
**Symbols:**

```
ffffffff81fa0a47-ffffffff81fa0a9d: acpi_table_parse_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_table_parse_entries(char *id, long unsigned int table_size, int entry_id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff81fcc358)
Location: drivers/acpi/tables.c:361
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_parse_madt
  - drivers/acpi/numa.c:acpi_numa_init
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81fcc358-ffffffff81fcc3ae: acpi_table_parse_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_table_parse_entries(char *id, long unsigned int table_size, int entry_id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff82009366)
Location: drivers/acpi/tables.c:362
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_parse_madt
  - drivers/acpi/numa.c:acpi_numa_init
  - drivers/mailbox/pcc.c:acpi_pcc_probe
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff82009366-ffffffff820093bc: acpi_table_parse_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_table_parse_entries(char *id, long unsigned int table_size, int entry_id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff820ea9e3)
Location: drivers/acpi/tables.c:346
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_parse_madt
  - drivers/acpi/numa.c:acpi_numa_init
```
**Symbols:**

```
ffffffff820ea9e3-ffffffff820eaa3e: acpi_table_parse_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_table_parse_entries(char *id, long unsigned int table_size, int entry_id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff826f3943)
Location: drivers/acpi/tables.c:346
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_parse_madt
  - drivers/acpi/numa.c:acpi_numa_init
```
**Symbols:**

```
ffffffff826f3943-ffffffff826f399e: acpi_table_parse_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_table_parse_entries(char *id, long unsigned int table_size, int entry_id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff8271d919)
Location: drivers/acpi/tables.c:351
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_parse_madt
  - drivers/acpi/numa.c:acpi_numa_init
```
**Symbols:**

```
ffffffff8271d919-ffffffff8271d974: acpi_table_parse_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_table_parse_entries(char *id, long unsigned int table_size, int entry_id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff828d5944)
Location: drivers/acpi/tables.c:350
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_parse_madt
  - drivers/acpi/numa.c:acpi_numa_init
```
**Symbols:**

```
ffffffff828d5944-ffffffff828d599f: acpi_table_parse_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int acpi_table_parse_entries(char *id, long unsigned int table_size, int entry_id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff828ef78a)
Location: drivers/acpi/tables.c:389
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_parse_madt
  - drivers/acpi/numa.c:acpi_numa_init
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/hmat/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff828ef78a-ffffffff828ef7e5: acpi_table_parse_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int acpi_table_parse_entries(char *id, long unsigned int table_size, int entry_id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff828f892a)
Location: drivers/acpi/tables.c:390
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_parse_madt
  - drivers/acpi/numa.c:acpi_numa_init
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/hmat/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff828f892a-ffffffff828f8985: acpi_table_parse_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_table_parse_entries(char *id, long unsigned int table_size, int entry_id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff82d0fb15)
Location: drivers/acpi/tables.c:390
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_parse_madt
  - drivers/acpi/numa/srat.c:acpi_numa_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff82d0fb15-ffffffff82d0fb70: acpi_table_parse_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_table_parse_entries(char *id, long unsigned int table_size, int entry_id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff82ffd55c)
Location: drivers/acpi/tables.c:379
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_parse_madt
  - drivers/acpi/numa/srat.c:acpi_numa_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff82ffd55c-ffffffff82ffd5b7: acpi_table_parse_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_table_parse_entries(char *id, long unsigned int table_size, int entry_id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff83208250)
Location: drivers/acpi/tables.c:379
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_parse_madt
  - drivers/acpi/numa/srat.c:acpi_numa_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff83208250-ffffffff832082ab: acpi_table_parse_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_table_parse_entries(char *id, long unsigned int table_size, int entry_id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff832f0341)
Location: drivers/acpi/tables.c:389
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_parse_madt
  - drivers/acpi/prmt.c:init_prmt
  - drivers/acpi/numa/srat.c:acpi_numa_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff832f0341-ffffffff832f039c: acpi_table_parse_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_table_parse_entries(char *id, long unsigned int table_size, int entry_id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff834a825b)
Location: drivers/acpi/tables.c:440
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_parse_madt
  - drivers/acpi/prmt.c:init_prmt
  - drivers/acpi/numa/srat.c:acpi_numa_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff834a825b-ffffffff834a82cf: acpi_table_parse_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int acpi_table_parse_entries(char *id, long unsigned int table_size, int entry_id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff83edf8d4)
Location: drivers/acpi/tables.c:450
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_parse_madt
Direct callers:
  - drivers/acpi/prmt.c:init_prmt
  - drivers/acpi/numa/srat.c:acpi_numa_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff83edf820-ffffffff83edf89d: acpi_table_parse_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int acpi_table_parse_entries(char *id, long unsigned int table_size, int entry_id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff83705364)
Location: drivers/acpi/tables.c:460
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_parse_madt
Direct callers:
  - drivers/acpi/prmt.c:init_prmt
  - drivers/acpi/numa/srat.c:acpi_numa_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff837052b0-ffffffff8370532d: acpi_table_parse_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_table_parse_entries(char *id, long unsigned int table_size, int entry_id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff83938894)
Location: drivers/acpi/tables.c:288
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_parse_madt
Direct callers:
  - drivers/acpi/prmt.c:init_prmt
  - drivers/acpi/numa/srat.c:acpi_numa_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff839387e0-ffffffff8393885d: acpi_table_parse_entries (STB_GLOBAL)
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
int acpi_table_parse_entries(char *id, long unsigned int table_size, int entry_id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffff80001147b9ac)
Location: drivers/acpi/tables.c:390
Inline: False
Direct callers:
  - arch/arm64/kernel/acpi_numa.c:acpi_map_cpus_to_nodes
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/acpi/tables.c:acpi_table_parse_madt
  - drivers/acpi/numa.c:acpi_numa_init
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/hmat/hmat.c:hmat_init
```
**Symbols:**

```
ffff80001147b9ac-ffff80001147ba38: acpi_table_parse_entries (STB_GLOBAL)
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
int acpi_table_parse_entries(char *id, long unsigned int table_size, int entry_id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff828e1696)
Location: drivers/acpi/tables.c:390
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_parse_madt
  - drivers/acpi/numa.c:acpi_numa_init
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/hmat/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff828e1696-ffffffff828e16f1: acpi_table_parse_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int acpi_table_parse_entries(char *id, long unsigned int table_size, int entry_id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff828d9b21)
Location: drivers/acpi/tables.c:390
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_parse_madt
  - drivers/acpi/numa.c:acpi_numa_init
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/hmat/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff828d9b21-ffffffff828d9b7c: acpi_table_parse_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int acpi_table_parse_entries(char *id, long unsigned int table_size, int entry_id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff828f4526)
Location: drivers/acpi/tables.c:390
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_parse_madt
  - drivers/acpi/numa.c:acpi_numa_init
```
**Symbols:**

```
ffffffff828f4526-ffffffff828f4581: acpi_table_parse_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int acpi_table_parse_entries(char *id, long unsigned int table_size, int entry_id, acpi_tbl_entry_handler handler, unsigned int max_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff828f997e)
Location: drivers/acpi/tables.c:390
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_parse_madt
  - drivers/acpi/numa.c:acpi_numa_init
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/hmat/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff828f997e-ffffffff828f99d9: acpi_table_parse_entries (STB_GLOBAL)
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
