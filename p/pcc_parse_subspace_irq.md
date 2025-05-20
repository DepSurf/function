# Function: <code>pcc_parse_subspace_irq</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff82023c2e)
Location: drivers/mailbox/pcc.c:416
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
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
In drivers/mailbox/pcc.c (ffffffff82106cc2)
Location: drivers/mailbox/pcc.c:416
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
In drivers/mailbox/pcc.c (ffffffff82710616)
Location: drivers/mailbox/pcc.c:415
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
In drivers/mailbox/pcc.c (ffffffff8273a89c)
Location: drivers/mailbox/pcc.c:406
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
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
In drivers/mailbox/pcc.c (ffffffff828f4897)
Location: drivers/mailbox/pcc.c:406
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
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
In drivers/mailbox/pcc.c (ffffffff829101db)
Location: drivers/mailbox/pcc.c:397
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
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
In drivers/mailbox/pcc.c (ffffffff82919ee8)
Location: drivers/mailbox/pcc.c:397
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pcc_parse_subspace_irq(int id, struct acpi_pcct_hw_reduced *pcct_ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff819c81ef)
Location: drivers/mailbox/pcc.c:397
Inline: False
Direct callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff819c81ef-ffffffff819c82a6: pcc_parse_subspace_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pcc_parse_subspace_irq(int id, struct acpi_pcct_hw_reduced *pcct_ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff81c2da53)
Location: drivers/mailbox/pcc.c:397
Inline: False
Direct callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
```
**Symbols:**

```
ffffffff81c2da53-ffffffff81c2db0a: pcc_parse_subspace_irq (STB_LOCAL)
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
In drivers/mailbox/pcc.c (ffffffff83225e29)
Location: drivers/mailbox/pcc.c:397
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
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
In drivers/mailbox/pcc.c (ffffffff83310068)
Location: drivers/mailbox/pcc.c:397
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
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
In drivers/mailbox/pcc.c (ffffffff81bcaca2)
Location: drivers/mailbox/pcc.c:442
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_probe
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
In drivers/mailbox/pcc.c (ffffffff81d74391)
Location: drivers/mailbox/pcc.c:442
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_probe
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
In drivers/mailbox/pcc.c (ffffffff81de23b5)
Location: drivers/mailbox/pcc.c:448
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_probe
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
In drivers/mailbox/pcc.c (ffffffff81e983a5)
Location: drivers/mailbox/pcc.c:509
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_probe
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
In drivers/mailbox/pcc.c (ffff8000114acedc)
Location: drivers/mailbox/pcc.c:397
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
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
In drivers/mailbox/pcc.c (ffffffff828feff1)
Location: drivers/mailbox/pcc.c:397
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
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
In drivers/mailbox/pcc.c (ffffffff828f6af6)
Location: drivers/mailbox/pcc.c:397
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
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
In drivers/mailbox/pcc.c (ffffffff82914283)
Location: drivers/mailbox/pcc.c:397
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
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
In drivers/mailbox/pcc.c (ffffffff8291af4a)
Location: drivers/mailbox/pcc.c:397
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:acpi_pcc_probe
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
