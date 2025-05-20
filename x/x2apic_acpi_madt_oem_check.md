# Function: <code>x2apic_acpi_madt_oem_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int x2apic_acpi_madt_oem_check(char *oem_id, char *oem_table_id);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059950)
Location: arch/x86/kernel/apic/x2apic_phys.c:34
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059f40)
Location: arch/x86/kernel/apic/x2apic_cluster.c:16
Inline: True
```
**Symbols:**

```
ffffffff81059950-ffffffff810599e5: x2apic_acpi_madt_oem_check (STB_LOCAL)
ffffffff81059f40-ffffffff81059fa2: x2apic_acpi_madt_oem_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int x2apic_acpi_madt_oem_check(char *oem_id, char *oem_table_id);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059bd0)
Location: arch/x86/kernel/apic/x2apic_phys.c:34
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105a210)
Location: arch/x86/kernel/apic/x2apic_cluster.c:16
Inline: True
```
**Symbols:**

```
ffffffff81059bd0-ffffffff81059c65: x2apic_acpi_madt_oem_check (STB_LOCAL)
ffffffff8105a210-ffffffff8105a272: x2apic_acpi_madt_oem_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
int x2apic_acpi_madt_oem_check(char *oem_id, char *oem_table_id);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c990)
Location: arch/x86/kernel/apic/x2apic_phys.c:34
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105cf60)
Location: arch/x86/kernel/apic/x2apic_cluster.c:16
Inline: True
```
**Symbols:**

```
ffffffff8105c990-ffffffff8105ca25: x2apic_acpi_madt_oem_check (STB_LOCAL)
ffffffff8105cf60-ffffffff8105cfc2: x2apic_acpi_madt_oem_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int x2apic_acpi_madt_oem_check(char *oem_id, char *oem_table_id);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c0a0)
Location: arch/x86/kernel/apic/x2apic_phys.c:34
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c3d0)
Location: arch/x86/kernel/apic/x2apic_cluster.c:17
Inline: True
```
**Symbols:**

```
ffffffff8105c0a0-ffffffff8105c135: x2apic_acpi_madt_oem_check (STB_LOCAL)
ffffffff8105c3d0-ffffffff8105c43e: x2apic_acpi_madt_oem_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int x2apic_acpi_madt_oem_check(char *oem_id, char *oem_table_id);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105ff60)
Location: arch/x86/kernel/apic/x2apic_phys.c:36
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81060540)
Location: arch/x86/kernel/apic/x2apic_cluster.c:25
Inline: True
```
**Symbols:**

```
ffffffff8105ff60-ffffffff8105fff5: x2apic_acpi_madt_oem_check (STB_LOCAL)
ffffffff81060540-ffffffff810605ae: x2apic_acpi_madt_oem_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int x2apic_acpi_madt_oem_check(char *oem_id, char *oem_table_id);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: arch/x86/kernel/apic/x2apic_phys.c:36
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81063620)
Location: arch/x86/kernel/apic/x2apic_cluster.c:25
Inline: True
```
**Symbols:**

```
ffffffff81063130-ffffffff810631bc: x2apic_acpi_madt_oem_check (STB_LOCAL)
ffffffff81063287-ffffffff81063298: x2apic_acpi_madt_oem_check.cold.5 (STB_LOCAL)
ffffffff81063620-ffffffff8106368e: x2apic_acpi_madt_oem_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int x2apic_acpi_madt_oem_check(char *oem_id, char *oem_table_id);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81068da9)
Location: arch/x86/kernel/apic/x2apic_phys.c:36
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81069320)
Location: arch/x86/kernel/apic/x2apic_cluster.c:25
Inline: True
```
**Symbols:**

```
ffffffff81068d30-ffffffff81068dbc: x2apic_acpi_madt_oem_check (STB_LOCAL)
ffffffff81068f87-ffffffff81068f98: x2apic_acpi_madt_oem_check.cold.5 (STB_LOCAL)
ffffffff81069320-ffffffff8106938e: x2apic_acpi_madt_oem_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int x2apic_acpi_madt_oem_check(char *oem_id, char *oem_table_id);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106c5ce)
Location: arch/x86/kernel/apic/x2apic_phys.c:36
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106cb70)
Location: arch/x86/kernel/apic/x2apic_cluster.c:25
Inline: True
```
**Symbols:**

```
ffffffff8106c550-ffffffff8106c5e1: x2apic_acpi_madt_oem_check (STB_LOCAL)
ffffffff8106c7b7-ffffffff8106c7c8: x2apic_acpi_madt_oem_check.cold (STB_LOCAL)
ffffffff8106cb70-ffffffff8106cbde: x2apic_acpi_madt_oem_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int x2apic_acpi_madt_oem_check(char *oem_id, char *oem_table_id);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106dcce)
Location: arch/x86/kernel/apic/x2apic_phys.c:31
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106e2d0)
Location: arch/x86/kernel/apic/x2apic_cluster.c:23
Inline: True
```
**Symbols:**

```
ffffffff8106dc50-ffffffff8106dce1: x2apic_acpi_madt_oem_check (STB_LOCAL)
ffffffff8106df0e-ffffffff8106df1f: x2apic_acpi_madt_oem_check.cold (STB_LOCAL)
ffffffff8106e2d0-ffffffff8106e33e: x2apic_acpi_madt_oem_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int x2apic_acpi_madt_oem_check(char *oem_id, char *oem_table_id);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8107513a)
Location: arch/x86/kernel/apic/x2apic_phys.c:31
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075740)
Location: arch/x86/kernel/apic/x2apic_cluster.c:23
Inline: False
```
**Symbols:**

```
ffffffff810750c0-ffffffff8107514d: x2apic_acpi_madt_oem_check (STB_LOCAL)
ffffffff810753de-ffffffff810753ef: x2apic_acpi_madt_oem_check.cold (STB_LOCAL)
ffffffff81075740-ffffffff810757ab: x2apic_acpi_madt_oem_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int x2apic_acpi_madt_oem_check(char *oem_id, char *oem_table_id);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8107576a)
Location: arch/x86/kernel/apic/x2apic_phys.c:37
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075d80)
Location: arch/x86/kernel/apic/x2apic_cluster.c:23
Inline: False
```
**Symbols:**

```
ffffffff810756f0-ffffffff8107577d: x2apic_acpi_madt_oem_check (STB_LOCAL)
ffffffff81bd799d-ffffffff81bd79ae: x2apic_acpi_madt_oem_check.cold (STB_LOCAL)
ffffffff81075d80-ffffffff81075deb: x2apic_acpi_madt_oem_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int x2apic_acpi_madt_oem_check(char *oem_id, char *oem_table_id);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8107620a)
Location: arch/x86/kernel/apic/x2apic_phys.c:37
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81076800)
Location: arch/x86/kernel/apic/x2apic_cluster.c:23
Inline: False
```
**Symbols:**

```
ffffffff81076190-ffffffff8107621d: x2apic_acpi_madt_oem_check (STB_LOCAL)
ffffffff81bc9953-ffffffff81bc9964: x2apic_acpi_madt_oem_check.cold (STB_LOCAL)
ffffffff81076800-ffffffff8107686b: x2apic_acpi_madt_oem_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int x2apic_acpi_madt_oem_check(char *oem_id, char *oem_table_id);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8108380a)
Location: arch/x86/kernel/apic/x2apic_phys.c:37
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81083f70)
Location: arch/x86/kernel/apic/x2apic_cluster.c:23
Inline: False
```
**Symbols:**

```
ffffffff81083790-ffffffff8108381d: x2apic_acpi_madt_oem_check (STB_LOCAL)
ffffffff81c9e77f-ffffffff81c9e790: x2apic_acpi_madt_oem_check.cold (STB_LOCAL)
ffffffff81083f70-ffffffff81083fdb: x2apic_acpi_madt_oem_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
int x2apic_acpi_madt_oem_check(char *oem_id, char *oem_table_id);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: arch/x86/kernel/apic/x2apic_phys.c:37
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81094060)
Location: arch/x86/kernel/apic/x2apic_cluster.c:29
Inline: False
```
**Symbols:**

```
ffffffff810936b0-ffffffff81093752: x2apic_acpi_madt_oem_check (STB_LOCAL)
ffffffff81e4dbc0-ffffffff81e4dbd1: x2apic_acpi_madt_oem_check.cold (STB_LOCAL)
ffffffff81094060-ffffffff810940de: x2apic_acpi_madt_oem_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
int x2apic_acpi_madt_oem_check(char *oem_id, char *oem_table_id);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810a8cd0)
Location: arch/x86/kernel/apic/x2apic_phys.c:37
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a9680)
Location: arch/x86/kernel/apic/x2apic_cluster.c:29
Inline: False
```
**Symbols:**

```
ffffffff810a8cd0-ffffffff810a8d7b: x2apic_acpi_madt_oem_check (STB_LOCAL)
ffffffff810a9680-ffffffff810a96fe: x2apic_acpi_madt_oem_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
int x2apic_acpi_madt_oem_check(char *oem_id, char *oem_table_id);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810abf00)
Location: arch/x86/kernel/apic/x2apic_phys.c:37
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810ac890)
Location: arch/x86/kernel/apic/x2apic_cluster.c:24
Inline: False
```
**Symbols:**

```
ffffffff810abf00-ffffffff810abfab: x2apic_acpi_madt_oem_check (STB_LOCAL)
ffffffff810ac890-ffffffff810ac90e: x2apic_acpi_madt_oem_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
int x2apic_acpi_madt_oem_check(char *oem_id, char *oem_table_id);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810b2c60)
Location: arch/x86/kernel/apic/x2apic_phys.c:39
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b3510)
Location: arch/x86/kernel/apic/x2apic_cluster.c:24
Inline: False
```
**Symbols:**

```
ffffffff810b2c60-ffffffff810b2d0b: x2apic_acpi_madt_oem_check (STB_LOCAL)
ffffffff810b3510-ffffffff810b358e: x2apic_acpi_madt_oem_check (STB_LOCAL)
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
<summary>In <code>aws</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int x2apic_acpi_madt_oem_check(char *oem_id, char *oem_table_id);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cc6e)
Location: arch/x86/kernel/apic/x2apic_phys.c:31
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d270)
Location: arch/x86/kernel/apic/x2apic_cluster.c:23
Inline: True
```
**Symbols:**

```
ffffffff8106cbf0-ffffffff8106cc81: x2apic_acpi_madt_oem_check (STB_LOCAL)
ffffffff8106ceae-ffffffff8106cebf: x2apic_acpi_madt_oem_check.cold (STB_LOCAL)
ffffffff8106d270-ffffffff8106d2de: x2apic_acpi_madt_oem_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int x2apic_acpi_madt_oem_check(char *oem_id, char *oem_table_id);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105cf74)
Location: arch/x86/kernel/apic/x2apic_phys.c:31
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d760)
Location: arch/x86/kernel/apic/x2apic_cluster.c:23
Inline: False
```
**Symbols:**

```
ffffffff8105cf10-ffffffff8105cf9e: x2apic_acpi_madt_oem_check (STB_LOCAL)
ffffffff8105d2ac-ffffffff8105d2bd: x2apic_acpi_madt_oem_check.cold (STB_LOCAL)
ffffffff8105d760-ffffffff8105d7cb: x2apic_acpi_madt_oem_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int x2apic_acpi_madt_oem_check(char *oem_id, char *oem_table_id);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106d11e)
Location: arch/x86/kernel/apic/x2apic_phys.c:31
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d720)
Location: arch/x86/kernel/apic/x2apic_cluster.c:23
Inline: True
```
**Symbols:**

```
ffffffff8106d0a0-ffffffff8106d131: x2apic_acpi_madt_oem_check (STB_LOCAL)
ffffffff8106d35e-ffffffff8106d36f: x2apic_acpi_madt_oem_check.cold (STB_LOCAL)
ffffffff8106d720-ffffffff8106d78e: x2apic_acpi_madt_oem_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int x2apic_acpi_madt_oem_check(char *oem_id, char *oem_table_id);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106f39e)
Location: arch/x86/kernel/apic/x2apic_phys.c:31
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106f9a0)
Location: arch/x86/kernel/apic/x2apic_cluster.c:23
Inline: True
```
**Symbols:**

```
ffffffff8106f320-ffffffff8106f3b1: x2apic_acpi_madt_oem_check (STB_LOCAL)
ffffffff8106f5de-ffffffff8106f5ef: x2apic_acpi_madt_oem_check.cold (STB_LOCAL)
ffffffff8106f9a0-ffffffff8106fa0e: x2apic_acpi_madt_oem_check (STB_LOCAL)
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
