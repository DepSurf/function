# Function: <code>crb_fixup_cmd_size</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u64 crb_fixup_cmd_size(struct device *dev, struct resource *io_res, u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff8165fc10)
Location: drivers/char/tpm/tpm_crb.c:468
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff8165fc10-ffffffff8165fc65: crb_fixup_cmd_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u64 crb_fixup_cmd_size(struct device *dev, struct resource *io_res, u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff8167e160)
Location: drivers/char/tpm/tpm_crb.c:478
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff8167e160-ffffffff8167e1b5: crb_fixup_cmd_size (STB_LOCAL)
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
In drivers/char/tpm/tpm_crb.c (ffffffff816b5489)
Location: drivers/char/tpm/tpm_crb.c:474
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
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
In drivers/char/tpm/tpm_crb.c (ffffffff816d8169)
Location: drivers/char/tpm/tpm_crb.c:474
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
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
In drivers/char/tpm/tpm_crb.c (ffffffff8178c91c)
Location: drivers/char/tpm/tpm_crb.c:486
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
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
In drivers/char/tpm/tpm_crb.c (ffffffff817a2eb6)
Location: drivers/char/tpm/tpm_crb.c:486
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
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
In drivers/char/tpm/tpm_crb.c (ffffffff81785bbd)
Location: drivers/char/tpm/tpm_crb.c:486
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
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
In drivers/char/tpm/tpm_crb.c (ffffffff8180c7cc)
Location: drivers/char/tpm/tpm_crb.c:486
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
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
In drivers/char/tpm/tpm_crb.c (ffffffff8194ce59)
Location: drivers/char/tpm/tpm_crb.c:486
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
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
In drivers/char/tpm/tpm_crb.c (ffffffff81ab0fdd)
Location: drivers/char/tpm/tpm_crb.c:486
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
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
In drivers/char/tpm/tpm_crb.c (ffffffff81afcec3)
Location: drivers/char/tpm/tpm_crb.c:532
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
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
In drivers/char/tpm/tpm_crb.c (ffffffff81b504d3)
Location: drivers/char/tpm/tpm_crb.c:532
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
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
In drivers/char/tpm/tpm_crb.c (ffff8000108c375c)
Location: drivers/char/tpm/tpm_crb.c:474
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
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
In drivers/char/tpm/tpm_crb.c (ffffffff8169dbb9)
Location: drivers/char/tpm/tpm_crb.c:474
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
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
In drivers/char/tpm/tpm_crb.c (ffffffff8167b5a9)
Location: drivers/char/tpm/tpm_crb.c:474
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
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
In drivers/char/tpm/tpm_crb.c (ffffffff816cbe29)
Location: drivers/char/tpm/tpm_crb.c:474
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
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
In drivers/char/tpm/tpm_crb.c (ffffffff816e62f9)
Location: drivers/char/tpm/tpm_crb.c:474
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
