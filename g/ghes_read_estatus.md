# Function: <code>ghes_read_estatus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ghes_read_estatus(struct ghes *ghes, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff814b56d0)
Location: drivers/acpi/apei/ghes.c:333
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff814b56d0-ffffffff814b5837: ghes_read_estatus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ghes_read_estatus(struct ghes *ghes, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81505050)
Location: drivers/acpi/apei/ghes.c:338
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81505050-ffffffff815051b7: ghes_read_estatus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ghes_read_estatus(struct ghes *ghes, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81529240)
Location: drivers/acpi/apei/ghes.c:338
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff81529240-ffffffff815293a7: ghes_read_estatus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ghes_read_estatus(struct ghes *ghes, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8153c7f0)
Location: drivers/acpi/apei/ghes.c:372
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff8153c7f0-ffffffff8153c958: ghes_read_estatus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ghes_read_estatus(struct ghes *ghes, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8159f330)
Location: drivers/acpi/apei/ghes.c:328
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff8159f330-ffffffff8159f498: ghes_read_estatus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ghes_read_estatus(struct ghes *ghes, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: drivers/acpi/apei/ghes.c:328
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
  - drivers/acpi/apei/ghes.c:ghes_proc
```
**Symbols:**

```
ffffffff815d7040-ffffffff815d717b: ghes_read_estatus (STB_LOCAL)
ffffffff815d7cdd-ffffffff815d7d0f: ghes_read_estatus.cold.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff815f0ec1)
Location: drivers/acpi/apei/ghes.c:373
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81622c95)
Location: drivers/acpi/apei/ghes.c:365
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81644765)
Location: drivers/acpi/apei/ghes.c:378
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff816f19c7)
Location: drivers/acpi/apei/ghes.c:373
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8170ed87)
Location: drivers/acpi/apei/ghes.c:385
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff816f0667)
Location: drivers/acpi/apei/ghes.c:385
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8176a777)
Location: drivers/acpi/apei/ghes.c:385
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff8189f2fe)
Location: drivers/acpi/apei/ghes.c:385
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff819e856e)
Location: drivers/acpi/apei/ghes.c:401
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81a30dee)
Location: drivers/acpi/apei/ghes.c:399
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81a7c25e)
Location: drivers/acpi/apei/ghes.c:427
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffff8000107b0134)
Location: drivers/acpi/apei/ghes.c:378
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
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
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff816385a5)
Location: drivers/acpi/apei/ghes.c:378
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff816528e5)
Location: drivers/acpi/apei/ghes.c:378
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_proc
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
</ul>
