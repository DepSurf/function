# Function: <code>acpi_is_ioapic</code>

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
In drivers/acpi/ioapic.c (ffffffff814b142d)
Location: drivers/acpi/ioapic.c:64
Inline: True
Inline callers:
  - drivers/acpi/ioapic.c:handle_ioapic_add
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
In drivers/acpi/ioapic.c (ffffffff81500d53)
Location: drivers/acpi/ioapic.c:64
Inline: True
Inline callers:
  - drivers/acpi/ioapic.c:handle_ioapic_add
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
In drivers/acpi/ioapic.c (ffffffff81523a4f)
Location: drivers/acpi/ioapic.c:64
Inline: True
Inline callers:
  - drivers/acpi/ioapic.c:handle_ioapic_add
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
In drivers/acpi/ioapic.c (ffffffff81535de6)
Location: drivers/acpi/ioapic.c:70
Inline: True
Inline callers:
  - drivers/acpi/ioapic.c:handle_ioapic_add
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
In drivers/acpi/ioapic.c (ffffffff81597696)
Location: drivers/acpi/ioapic.c:70
Inline: True
Inline callers:
  - drivers/acpi/ioapic.c:handle_ioapic_add
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
In drivers/acpi/ioapic.c (ffffffff815ceb65)
Location: drivers/acpi/ioapic.c:70
Inline: True
Inline callers:
  - drivers/acpi/ioapic.c:handle_ioapic_add
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
In drivers/acpi/ioapic.c (ffffffff815e8145)
Location: drivers/acpi/ioapic.c:70
Inline: True
Inline callers:
  - drivers/acpi/ioapic.c:handle_ioapic_add
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
In drivers/acpi/ioapic.c (ffffffff81619e25)
Location: drivers/acpi/ioapic.c:67
Inline: True
Inline callers:
  - drivers/acpi/ioapic.c:handle_ioapic_add
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
In drivers/acpi/ioapic.c (ffffffff8163b855)
Location: drivers/acpi/ioapic.c:67
Inline: True
Inline callers:
  - drivers/acpi/ioapic.c:handle_ioapic_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ioapic.c (ffffffff816e8990)
Location: drivers/acpi/ioapic.c:67
Inline: True
Direct callers:
  - drivers/acpi/ioapic.c:handle_ioapic_add
```
**Symbols:**

```
ffffffff816e8990-ffffffff816e8a6e: acpi_is_ioapic.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ioapic.c (ffffffff817061d0)
Location: drivers/acpi/ioapic.c:67
Inline: True
Direct callers:
  - drivers/acpi/ioapic.c:handle_ioapic_add
```
**Symbols:**

```
ffffffff817061d0-ffffffff817062ae: acpi_is_ioapic.constprop.0 (STB_LOCAL)
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
In drivers/acpi/ioapic.c (ffffffff816e7885)
Location: drivers/acpi/ioapic.c:67
Inline: True
Inline callers:
  - drivers/acpi/ioapic.c:handle_ioapic_add
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
In drivers/acpi/ioapic.c (ffffffff81760ed5)
Location: drivers/acpi/ioapic.c:67
Inline: True
Inline callers:
  - drivers/acpi/ioapic.c:handle_ioapic_add
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
In drivers/acpi/ioapic.c (ffffffff8189496d)
Location: drivers/acpi/ioapic.c:67
Inline: True
Inline callers:
  - drivers/acpi/ioapic.c:handle_ioapic_add
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
In drivers/acpi/ioapic.c (ffffffff819dc55d)
Location: drivers/acpi/ioapic.c:67
Inline: True
Inline callers:
  - drivers/acpi/ioapic.c:handle_ioapic_add
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
In drivers/acpi/ioapic.c (ffffffff81a2421d)
Location: drivers/acpi/ioapic.c:68
Inline: True
Inline callers:
  - drivers/acpi/ioapic.c:handle_ioapic_add
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
In drivers/acpi/ioapic.c (ffffffff81a6f02d)
Location: drivers/acpi/ioapic.c:68
Inline: True
Inline callers:
  - drivers/acpi/ioapic.c:handle_ioapic_add
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ioapic.c (ffffffff81608bb5)
Location: drivers/acpi/ioapic.c:67
Inline: True
Inline callers:
  - drivers/acpi/ioapic.c:handle_ioapic_add
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
In drivers/acpi/ioapic.c (ffffffff815fa745)
Location: drivers/acpi/ioapic.c:67
Inline: True
Inline callers:
  - drivers/acpi/ioapic.c:handle_ioapic_add
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
In drivers/acpi/ioapic.c (ffffffff8162f695)
Location: drivers/acpi/ioapic.c:67
Inline: True
Inline callers:
  - drivers/acpi/ioapic.c:handle_ioapic_add
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
In drivers/acpi/ioapic.c (ffffffff816499d5)
Location: drivers/acpi/ioapic.c:67
Inline: True
Inline callers:
  - drivers/acpi/ioapic.c:handle_ioapic_add
```
</details>
</li>
</ul>

## Differences
