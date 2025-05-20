# Function: <code>hmat_free_structures</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffffffff828f435e)
Location: drivers/acpi/hmat/hmat.c:596
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_init
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
In drivers/acpi/hmat/hmat.c (ffffffff828fd36e)
Location: drivers/acpi/hmat/hmat.c:672
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hmat_free_structures();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff82d13a43)
Location: drivers/acpi/numa/hmat.c:774
Inline: False
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff82d13a43-ffffffff82d13bb7: hmat_free_structures (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hmat_free_structures();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff83001632)
Location: drivers/acpi/numa/hmat.c:775
Inline: False
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff83001632-ffffffff830017a6: hmat_free_structures (STB_LOCAL)
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
In drivers/acpi/numa/hmat.c (ffffffff8320cf7e)
Location: drivers/acpi/numa/hmat.c:776
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_init
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
In drivers/acpi/numa/hmat.c (ffffffff832f5767)
Location: drivers/acpi/numa/hmat.c:776
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_init
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
In drivers/acpi/numa/hmat.c (ffffffff834adbd0)
Location: drivers/acpi/numa/hmat.c:776
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_init
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
In drivers/acpi/numa/hmat.c (ffffffff83ee6c80)
Location: drivers/acpi/numa/hmat.c:783
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_init
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
In drivers/acpi/numa/hmat.c (ffffffff8370c640)
Location: drivers/acpi/numa/hmat.c:783
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_init
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
In drivers/acpi/numa/hmat.c (ffffffff8393f6fd)
Location: drivers/acpi/numa/hmat.c:946
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_init
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
In drivers/acpi/hmat/hmat.c (ffff80001148003c)
Location: drivers/acpi/hmat/hmat.c:672
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_init
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffffffff828e57b1)
Location: drivers/acpi/hmat/hmat.c:672
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffffffff828dd9b5)
Location: drivers/acpi/hmat/hmat.c:672
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_init
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffffffff828fe3c2)
Location: drivers/acpi/hmat/hmat.c:672
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
