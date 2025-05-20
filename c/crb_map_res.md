# Function: <code>crb_map_res</code>

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
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff8165fd20)
Location: drivers/char/tpm/tpm_crb.c:444
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff8165fd20-ffffffff8165fdbe: crb_map_res.isra.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff8167e370)
Location: drivers/char/tpm/tpm_crb.c:454
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
**Symbols:**

```
ffffffff8167e370-ffffffff8167e40e: crb_map_res.isra.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff816b5020)
Location: drivers/char/tpm/tpm_crb.c:450
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
**Symbols:**

```
ffffffff816b5020-ffffffff816b50be: crb_map_res.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff816d7d00)
Location: drivers/char/tpm/tpm_crb.c:450
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
**Symbols:**

```
ffffffff816d7d00-ffffffff816d7d9e: crb_map_res.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *crb_map_res(struct device *dev, struct resource *iores, void **iobase_ptr, u64 start, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff8178c090)
Location: drivers/char/tpm/tpm_crb.c:456
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
**Symbols:**

```
ffffffff8178c090-ffffffff8178c139: crb_map_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *crb_map_res(struct device *dev, struct resource *iores, void **iobase_ptr, u64 start, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff817a2620)
Location: drivers/char/tpm/tpm_crb.c:456
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
**Symbols:**

```
ffffffff817a2620-ffffffff817a26c9: crb_map_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *crb_map_res(struct device *dev, struct resource *iores, void **iobase_ptr, u64 start, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff81785320)
Location: drivers/char/tpm/tpm_crb.c:456
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
**Symbols:**

```
ffffffff81785320-ffffffff817853c9: crb_map_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *crb_map_res(struct device *dev, struct resource *iores, void **iobase_ptr, u64 start, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff8180be50)
Location: drivers/char/tpm/tpm_crb.c:456
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
**Symbols:**

```
ffffffff8180be50-ffffffff8180bef9: crb_map_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *crb_map_res(struct device *dev, struct resource *iores, void **iobase_ptr, u64 start, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff8194c410)
Location: drivers/char/tpm/tpm_crb.c:456
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
**Symbols:**

```
ffffffff8194c410-ffffffff8194c4cb: crb_map_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *crb_map_res(struct device *dev, struct resource *iores, void **iobase_ptr, u64 start, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff81ab05b0)
Location: drivers/char/tpm/tpm_crb.c:456
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
**Symbols:**

```
ffffffff81ab05b0-ffffffff81ab066b: crb_map_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *crb_map_res(struct device *dev, struct resource *iores, void **iobase_ptr, u64 start, u32 size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff81afd63d)
Location: drivers/char/tpm/tpm_crb.c:502
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
**Symbols:**

```
ffffffff81afc300-ffffffff81afc3bb: crb_map_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *crb_map_res(struct device *dev, struct resource *iores, void **iobase_ptr, u64 start, u32 size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff81b50c46)
Location: drivers/char/tpm/tpm_crb.c:502
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
**Symbols:**

```
ffffffff81b4f910-ffffffff81b4f9cb: crb_map_res (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffff8000108c3040)
Location: drivers/char/tpm/tpm_crb.c:450
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
**Symbols:**

```
ffff8000108c3040-ffff8000108c3114: crb_map_res.isra.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff8169d750)
Location: drivers/char/tpm/tpm_crb.c:450
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
**Symbols:**

```
ffffffff8169d750-ffffffff8169d7ee: crb_map_res.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff8167b140)
Location: drivers/char/tpm/tpm_crb.c:450
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
**Symbols:**

```
ffffffff8167b140-ffffffff8167b1de: crb_map_res.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff816cb9c0)
Location: drivers/char/tpm/tpm_crb.c:450
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
**Symbols:**

```
ffffffff816cb9c0-ffffffff816cba5e: crb_map_res.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff816e5e90)
Location: drivers/char/tpm/tpm_crb.c:450
Inline: True
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
**Symbols:**

```
ffffffff816e5e90-ffffffff816e5f2e: crb_map_res.isra.0 (STB_LOCAL)
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
