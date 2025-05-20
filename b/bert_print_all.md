# Function: <code>bert_print_all</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/bert.c (ffffffff81fcfb14)
Location: drivers/acpi/apei/bert.c:37
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
In drivers/acpi/apei/bert.c (ffffffff8200d1cb)
Location: drivers/acpi/apei/bert.c:37
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
In drivers/acpi/apei/bert.c (ffffffff820eeb90)
Location: drivers/acpi/apei/bert.c:37
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
In drivers/acpi/apei/bert.c (ffffffff826f83ac)
Location: drivers/acpi/apei/bert.c:37
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
In drivers/acpi/apei/bert.c (ffffffff8272276d)
Location: drivers/acpi/apei/bert.c:37
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
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
In drivers/acpi/apei/bert.c (ffffffff828da8a9)
Location: drivers/acpi/apei/bert.c:37
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
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
In drivers/acpi/apei/bert.c (0)
Location: drivers/acpi/apei/bert.c:35
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
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
In drivers/acpi/apei/bert.c (0)
Location: drivers/acpi/apei/bert.c:35
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bert_print_all(struct acpi_bert_region *region, unsigned int region_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/bert.c (ffffffff82d15039)
Location: drivers/acpi/apei/bert.c:35
Inline: False
Direct callers:
  - drivers/acpi/apei/bert.c:bert_init
```
**Symbols:**

```
ffffffff82d15039-ffffffff82d150e8: bert_print_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bert_print_all(struct acpi_bert_region *region, unsigned int region_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/bert.c (ffffffff83002ccd)
Location: drivers/acpi/apei/bert.c:35
Inline: False
Direct callers:
  - drivers/acpi/apei/bert.c:bert_init
```
**Symbols:**

```
ffffffff83002ccd-ffffffff83002d7c: bert_print_all (STB_LOCAL)
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
In drivers/acpi/apei/bert.c (0)
Location: drivers/acpi/apei/bert.c:35
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
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
In drivers/acpi/apei/bert.c (0)
Location: drivers/acpi/apei/bert.c:35
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
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
In drivers/acpi/apei/bert.c (ffffffff834aebbd)
Location: drivers/acpi/apei/bert.c:45
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
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
In drivers/acpi/apei/bert.c (0)
Location: drivers/acpi/apei/bert.c:45
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
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
In drivers/acpi/apei/bert.c (0)
Location: drivers/acpi/apei/bert.c:46
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
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
In drivers/acpi/apei/bert.c (0)
Location: drivers/acpi/apei/bert.c:46
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
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
In drivers/acpi/apei/bert.c (ffff800011480ff0)
Location: drivers/acpi/apei/bert.c:35
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
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
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/bert.c (0)
Location: drivers/acpi/apei/bert.c:35
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
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
In drivers/acpi/apei/bert.c (0)
Location: drivers/acpi/apei/bert.c:35
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
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
In drivers/acpi/apei/bert.c (0)
Location: drivers/acpi/apei/bert.c:35
Inline: True
Inline callers:
  - drivers/acpi/apei/bert.c:bert_init
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
