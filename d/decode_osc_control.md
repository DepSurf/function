# Function: <code>decode_osc_control</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void decode_osc_control(struct acpi_pci_root *root, char *msg, u32 word);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81485947)
Location: drivers/acpi/pci_root.c:179
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81485947-ffffffff8148595e: decode_osc_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void decode_osc_control(struct acpi_pci_root *root, char *msg, u32 word);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff814d44d5)
Location: drivers/acpi/pci_root.c:179
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
```
**Symbols:**

```
ffffffff814d44d5-ffffffff814d44ec: decode_osc_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void decode_osc_control(struct acpi_pci_root *root, char *msg, u32 word);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff814f6b24)
Location: drivers/acpi/pci_root.c:179
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
```
**Symbols:**

```
ffffffff814f6b24-ffffffff814f6b3b: decode_osc_control (STB_LOCAL)
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
In drivers/acpi/pci_root.c (ffffffff81505a79)
Location: drivers/acpi/pci_root.c:179
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff81547bdf)
Location: drivers/acpi/pci_root.c:180
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff8157e062)
Location: drivers/acpi/pci_root.c:181
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff81595d4a)
Location: drivers/acpi/pci_root.c:181
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff815c6d56)
Location: drivers/acpi/pci_root.c:169
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff815e7f73)
Location: drivers/acpi/pci_root.c:168
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff8169390f)
Location: drivers/acpi/pci_root.c:170
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff81c01948)
Location: drivers/acpi/pci_root.c:168
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff81bf3379)
Location: drivers/acpi/pci_root.c:166
Inline: True
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
In drivers/acpi/pci_root.c (ffffffff81ceffc6)
Location: drivers/acpi/pci_root.c:168
Inline: True
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
In drivers/acpi/pci_root.c (ffffffff81eb7ca0)
Location: drivers/acpi/pci_root.c:176
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff8196b23a)
Location: drivers/acpi/pci_root.c:176
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff819b186e)
Location: drivers/acpi/pci_root.c:176
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff819fbd4e)
Location: drivers/acpi/pci_root.c:176
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffff800010775110)
Location: drivers/acpi/pci_root.c:168
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff815d9253)
Location: drivers/acpi/pci_root.c:168
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff815c2e43)
Location: drivers/acpi/pci_root.c:168
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff815dc253)
Location: drivers/acpi/pci_root.c:168
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff815f6113)
Location: drivers/acpi/pci_root.c:168
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
</ul>
