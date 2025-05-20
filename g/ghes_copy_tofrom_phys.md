# Function: <code>ghes_copy_tofrom_phys</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ghes_copy_tofrom_phys(void *buffer, u64 paddr, u32 len, int from_phys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff814b5430)
Location: drivers/acpi/apei/ghes.c:296
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
```
**Symbols:**

```
ffffffff814b5430-ffffffff814b56d0: ghes_copy_tofrom_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ghes_copy_tofrom_phys(void *buffer, u64 paddr, u32 len, int from_phys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81504db0)
Location: drivers/acpi/apei/ghes.c:301
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
```
**Symbols:**

```
ffffffff81504db0-ffffffff81505050: ghes_copy_tofrom_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ghes_copy_tofrom_phys(void *buffer, u64 paddr, u32 len, int from_phys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81528fa0)
Location: drivers/acpi/apei/ghes.c:301
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
```
**Symbols:**

```
ffffffff81528fa0-ffffffff81529240: ghes_copy_tofrom_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ghes_copy_tofrom_phys(void *buffer, u64 paddr, u32 len, int from_phys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8153c550)
Location: drivers/acpi/apei/ghes.c:335
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
```
**Symbols:**

```
ffffffff8153c550-ffffffff8153c7e1: ghes_copy_tofrom_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ghes_copy_tofrom_phys(void *buffer, u64 paddr, u32 len, int from_phys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8159f0a0)
Location: drivers/acpi/apei/ghes.c:291
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
```
**Symbols:**

```
ffffffff8159f0a0-ffffffff8159f2f6: ghes_copy_tofrom_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ghes_copy_tofrom_phys(void *buffer, u64 paddr, u32 len, int from_phys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff815d6da0)
Location: drivers/acpi/apei/ghes.c:291
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
  - drivers/acpi/apei/ghes.c:ghes_read_estatus
```
**Symbols:**

```
ffffffff815d6da0-ffffffff815d7002: ghes_copy_tofrom_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ghes_copy_tofrom_phys(void *buffer, u64 paddr, u32 len, int from_phys, enum fixed_addresses fixmap_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff815efec0)
Location: drivers/acpi/apei/ghes.c:282
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
  - drivers/acpi/apei/ghes.c:__ghes_peek_estatus
```
**Symbols:**

```
ffffffff815efec0-ffffffff815effd4: ghes_copy_tofrom_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ghes_copy_tofrom_phys(void *buffer, u64 paddr, u32 len, int from_phys, enum fixed_addresses fixmap_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81621c40)
Location: drivers/acpi/apei/ghes.c:274
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81621c40-ffffffff81621d64: ghes_copy_tofrom_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ghes_copy_tofrom_phys(void *buffer, u64 paddr, u32 len, int from_phys, enum fixed_addresses fixmap_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81643720)
Location: drivers/acpi/apei/ghes.c:287
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81643720-ffffffff81643844: ghes_copy_tofrom_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ghes_copy_tofrom_phys(void *buffer, u64 paddr, u32 len, int from_phys, enum fixed_addresses fixmap_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff816f0b90)
Location: drivers/acpi/apei/ghes.c:282
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff816f0b90-ffffffff816f0ca9: ghes_copy_tofrom_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ghes_copy_tofrom_phys(void *buffer, u64 paddr, u32 len, int from_phys, enum fixed_addresses fixmap_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8170de30)
Location: drivers/acpi/apei/ghes.c:294
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff8170de30-ffffffff8170df49: ghes_copy_tofrom_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ghes_copy_tofrom_phys(void *buffer, u64 paddr, u32 len, int from_phys, enum fixed_addresses fixmap_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff816ef5d0)
Location: drivers/acpi/apei/ghes.c:294
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff816ef5d0-ffffffff816ef6e9: ghes_copy_tofrom_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ghes_copy_tofrom_phys(void *buffer, u64 paddr, u32 len, int from_phys, enum fixed_addresses fixmap_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81769630)
Location: drivers/acpi/apei/ghes.c:294
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81769630-ffffffff81769749: ghes_copy_tofrom_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ghes_copy_tofrom_phys(void *buffer, u64 paddr, u32 len, int from_phys, enum fixed_addresses fixmap_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8189dfa0)
Location: drivers/acpi/apei/ghes.c:294
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff8189dfa0-ffffffff8189e0d1: ghes_copy_tofrom_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ghes_copy_tofrom_phys(void *buffer, u64 paddr, u32 len, int from_phys, enum fixed_addresses fixmap_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff819e6f60)
Location: drivers/acpi/apei/ghes.c:310
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff819e6f60-ffffffff819e7091: ghes_copy_tofrom_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ghes_copy_tofrom_phys(void *buffer, u64 paddr, u32 len, int from_phys, enum fixed_addresses fixmap_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81a2f670)
Location: drivers/acpi/apei/ghes.c:308
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81a2f670-ffffffff81a2f7a1: ghes_copy_tofrom_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ghes_copy_tofrom_phys(void *buffer, u64 paddr, u32 len, int from_phys, enum fixed_addresses fixmap_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81a7a9b0)
Location: drivers/acpi/apei/ghes.c:336
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81a7a9b0-ffffffff81a7aae1: ghes_copy_tofrom_phys (STB_LOCAL)
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
void ghes_copy_tofrom_phys(void *buffer, u64 paddr, u32 len, int from_phys, enum fixed_addresses fixmap_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffff8000107aed50)
Location: drivers/acpi/apei/ghes.c:287
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_in_nmi_queue_one_entry
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffff8000107aed50-ffff8000107aee74: ghes_copy_tofrom_phys (STB_LOCAL)
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
<summary>In <code>gcp</code>: ✅</summary>

```c
void ghes_copy_tofrom_phys(void *buffer, u64 paddr, u32 len, int from_phys, enum fixed_addresses fixmap_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81637560)
Location: drivers/acpi/apei/ghes.c:287
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81637560-ffffffff81637684: ghes_copy_tofrom_phys (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ghes_copy_tofrom_phys(void *buffer, u64 paddr, u32 len, int from_phys, enum fixed_addresses fixmap_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81651870)
Location: drivers/acpi/apei/ghes.c:287
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81651870-ffffffff81651994: ghes_copy_tofrom_phys (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum fixed_addresses fixmap_idx</code>
</li>
</ul>
</details>
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
