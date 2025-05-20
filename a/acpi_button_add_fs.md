# Function: <code>acpi_button_add_fs</code>

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
In drivers/acpi/button.c (ffffffff814ab240)
Location: drivers/acpi/button.c:142
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
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
In drivers/acpi/button.c (ffffffff814fa58f)
Location: drivers/acpi/button.c:183
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
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
In drivers/acpi/button.c (ffffffff8151d333)
Location: drivers/acpi/button.c:260
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
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
In drivers/acpi/button.c (ffffffff8152dece)
Location: drivers/acpi/button.c:260
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
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
In drivers/acpi/button.c (ffffffff8158edd0)
Location: drivers/acpi/button.c:260
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
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
In drivers/acpi/button.c (ffffffff815c60f8)
Location: drivers/acpi/button.c:263
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
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
In drivers/acpi/button.c (ffffffff815df6b8)
Location: drivers/acpi/button.c:265
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
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
In drivers/acpi/button.c (ffffffff8161122f)
Location: drivers/acpi/button.c:252
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
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
In drivers/acpi/button.c (ffffffff816326df)
Location: drivers/acpi/button.c:274
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_button_add_fs(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (0)
Location: drivers/acpi/button.c:278
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
```
**Symbols:**

```
ffffffff816de990-ffffffff816deab1: acpi_button_add_fs (STB_LOCAL)
ffffffff816df597-ffffffff816df5ad: acpi_button_add_fs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_button_add_fs(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/button.c (0)
Location: drivers/acpi/button.c:277
Inline: False
Direct callers:
  - drivers/acpi/button.c:acpi_button_add
```
**Symbols:**

```
ffffffff816fc9d0-ffffffff816fcaf4: acpi_button_add_fs (STB_LOCAL)
ffffffff81c02830-ffffffff81c02846: acpi_button_add_fs.cold (STB_LOCAL)
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
In drivers/acpi/button.c (ffffffff816de91e)
Location: drivers/acpi/button.c:269
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
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
In drivers/acpi/button.c (ffffffff81756abe)
Location: drivers/acpi/button.c:280
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
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
In drivers/acpi/button.c (ffffffff81889bfe)
Location: drivers/acpi/button.c:280
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
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
In drivers/acpi/button.c (ffffffff819d060f)
Location: drivers/acpi/button.c:280
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
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
In drivers/acpi/button.c (ffffffff81a17c07)
Location: drivers/acpi/button.c:287
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
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
In drivers/acpi/button.c (ffffffff81a62e65)
Location: drivers/acpi/button.c:287
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
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
In drivers/acpi/button.c (ffff8000107a0d4c)
Location: drivers/acpi/button.c:274
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
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
In drivers/acpi/button.c (ffffffff81602b4f)
Location: drivers/acpi/button.c:274
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
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
In drivers/acpi/button.c (ffffffff815edfff)
Location: drivers/acpi/button.c:274
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff816269bf)
Location: drivers/acpi/button.c:274
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
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
In drivers/acpi/button.c (ffffffff8164086f)
Location: drivers/acpi/button.c:274
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
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
