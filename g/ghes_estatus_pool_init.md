# Function: <code>ghes_estatus_pool_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81fa3775)
Location: drivers/acpi/apei/ghes.c:193
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81fcfcbc)
Location: drivers/acpi/apei/ghes.c:198
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8200d373)
Location: drivers/acpi/apei/ghes.c:198
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff820eed32)
Location: drivers/acpi/apei/ghes.c:210
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff826f8516)
Location: drivers/acpi/apei/ghes.c:166
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff827228f0)
Location: drivers/acpi/apei/ghes.c:166
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ghes_estatus_pool_init(int num_ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff815f1540)
Location: drivers/acpi/apei/ghes.c:161
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:acpi_hest_init
```
**Symbols:**

```
ffffffff815f1540-ffffffff815f15b6: ghes_estatus_pool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ghes_estatus_pool_init(int num_ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81623330)
Location: drivers/acpi/apei/ghes.c:153
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
```
**Symbols:**

```
ffffffff81623330-ffffffff816233b6: ghes_estatus_pool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ghes_estatus_pool_init(int num_ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81644e00)
Location: drivers/acpi/apei/ghes.c:153
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
```
**Symbols:**

```
ffffffff81644e00-ffffffff81644ea5: ghes_estatus_pool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ghes_estatus_pool_init(int num_ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff816f23e0)
Location: drivers/acpi/apei/ghes.c:154
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
```
**Symbols:**

```
ffffffff816f23e0-ffffffff816f2479: ghes_estatus_pool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ghes_estatus_pool_init(int num_ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8170f7a0)
Location: drivers/acpi/apei/ghes.c:166
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
```
**Symbols:**

```
ffffffff8170f7a0-ffffffff8170f839: ghes_estatus_pool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ghes_estatus_pool_init(int num_ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff816f1070)
Location: drivers/acpi/apei/ghes.c:166
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
```
**Symbols:**

```
ffffffff816f1070-ffffffff816f1109: ghes_estatus_pool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ghes_estatus_pool_init(int num_ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8176b180)
Location: drivers/acpi/apei/ghes.c:166
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
```
**Symbols:**

```
ffffffff8176b180-ffffffff8176b219: ghes_estatus_pool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ghes_estatus_pool_init(int num_ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8189fd80)
Location: drivers/acpi/apei/ghes.c:166
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
```
**Symbols:**

```
ffffffff8189fd80-ffffffff8189fe1e: ghes_estatus_pool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ghes_estatus_pool_init(unsigned int num_ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff819e9190)
Location: drivers/acpi/apei/ghes.c:182
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
```
**Symbols:**

```
ffffffff819e9190-ffffffff819e922b: ghes_estatus_pool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ghes_estatus_pool_init(unsigned int num_ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81a318a0)
Location: drivers/acpi/apei/ghes.c:181
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
```
**Symbols:**

```
ffffffff81a318a0-ffffffff81a3193b: ghes_estatus_pool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ghes_estatus_pool_init(unsigned int num_ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81a7cd10)
Location: drivers/acpi/apei/ghes.c:195
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
```
**Symbols:**

```
ffffffff81a7cd10-ffffffff81a7cdab: ghes_estatus_pool_init (STB_GLOBAL)
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
int ghes_estatus_pool_init(int num_ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffff8000107b0a70)
Location: drivers/acpi/apei/ghes.c:153
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:acpi_hest_init
```
**Symbols:**

```
ffff8000107b0a70-ffff8000107b0b1c: ghes_estatus_pool_init (STB_GLOBAL)
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
int ghes_estatus_pool_init(int num_ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81638c40)
Location: drivers/acpi/apei/ghes.c:153
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
```
**Symbols:**

```
ffffffff81638c40-ffffffff81638ce5: ghes_estatus_pool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ghes_estatus_pool_init(int num_ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81652f90)
Location: drivers/acpi/apei/ghes.c:153
Inline: False
Direct callers:
  - drivers/acpi/apei/hest.c:hest_ghes_dev_register
```
**Symbols:**

```
ffffffff81652f90-ffffffff81653035: ghes_estatus_pool_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int num_ghes</code> ➡️ <code>unsigned int num_ghes</code>
</li>
</ul>
</details>
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
