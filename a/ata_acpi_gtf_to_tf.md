# Function: <code>ata_acpi_gtf_to_tf</code>

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
In drivers/ata/libata-acpi.c (ffffffff815e1456)
Location: drivers/ata/libata-acpi.c:548
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
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
In drivers/ata/libata-acpi.c (ffffffff8163af74)
Location: drivers/ata/libata-acpi.c:548
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
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
In drivers/ata/libata-acpi.c (ffffffff8166bff4)
Location: drivers/ata/libata-acpi.c:548
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ata_acpi_gtf_to_tf(struct ata_device *dev, const struct ata_acpi_gtf *gtf, struct ata_taskfile *tf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff81680560)
Location: drivers/ata/libata-acpi.c:548
Inline: False
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
**Symbols:**

```
ffffffff81680560-ffffffff816805e3: ata_acpi_gtf_to_tf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ata_acpi_gtf_to_tf(struct ata_device *dev, const struct ata_acpi_gtf *gtf, struct ata_taskfile *tf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff816e9dc0)
Location: drivers/ata/libata-acpi.c:548
Inline: False
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
**Symbols:**

```
ffffffff816e9dc0-ffffffff816e9e43: ata_acpi_gtf_to_tf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ata_acpi_gtf_to_tf(struct ata_device *dev, const struct ata_acpi_gtf *gtf, struct ata_taskfile *tf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff817266d0)
Location: drivers/ata/libata-acpi.c:548
Inline: False
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
**Symbols:**

```
ffffffff817266d0-ffffffff81726754: ata_acpi_gtf_to_tf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ata_acpi_gtf_to_tf(struct ata_device *dev, const struct ata_acpi_gtf *gtf, struct ata_taskfile *tf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff81748e90)
Location: drivers/ata/libata-acpi.c:548
Inline: False
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
**Symbols:**

```
ffffffff81748e90-ffffffff81748f14: ata_acpi_gtf_to_tf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ata_acpi_gtf_to_tf(struct ata_device *dev, const struct ata_acpi_gtf *gtf, struct ata_taskfile *tf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff81784d20)
Location: drivers/ata/libata-acpi.c:549
Inline: False
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
**Symbols:**

```
ffffffff81784d20-ffffffff81784da4: ata_acpi_gtf_to_tf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ata_acpi_gtf_to_tf(struct ata_device *dev, const struct ata_acpi_gtf *gtf, struct ata_taskfile *tf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff817a8960)
Location: drivers/ata/libata-acpi.c:549
Inline: False
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
**Symbols:**

```
ffffffff817a8960-ffffffff817a89e4: ata_acpi_gtf_to_tf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ata_acpi_gtf_to_tf(struct ata_device *dev, const struct ata_acpi_gtf *gtf, struct ata_taskfile *tf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff8186e1c0)
Location: drivers/ata/libata-acpi.c:549
Inline: False
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
**Symbols:**

```
ffffffff8186e1c0-ffffffff8186e240: ata_acpi_gtf_to_tf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ata_acpi_gtf_to_tf(struct ata_device *dev, const struct ata_acpi_gtf *gtf, struct ata_taskfile *tf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff8187ce90)
Location: drivers/ata/libata-acpi.c:549
Inline: False
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
**Symbols:**

```
ffffffff8187ce90-ffffffff8187cf10: ata_acpi_gtf_to_tf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ata_acpi_gtf_to_tf(struct ata_device *dev, const struct ata_acpi_gtf *gtf, struct ata_taskfile *tf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff8185f700)
Location: drivers/ata/libata-acpi.c:549
Inline: False
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
**Symbols:**

```
ffffffff8185f700-ffffffff8185f780: ata_acpi_gtf_to_tf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ata_acpi_gtf_to_tf(struct ata_device *dev, const struct ata_acpi_gtf *gtf, struct ata_taskfile *tf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff818ee4c0)
Location: drivers/ata/libata-acpi.c:549
Inline: False
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
**Symbols:**

```
ffffffff818ee4c0-ffffffff818ee540: ata_acpi_gtf_to_tf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ata_acpi_gtf_to_tf(struct ata_device *dev, const struct ata_acpi_gtf *gtf, struct ata_taskfile *tf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff81a40690)
Location: drivers/ata/libata-acpi.c:541
Inline: False
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
**Symbols:**

```
ffffffff81a40690-ffffffff81a4071e: ata_acpi_gtf_to_tf (STB_LOCAL)
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
In drivers/ata/libata-acpi.c (ffffffff81bc6858)
Location: drivers/ata/libata-acpi.c:541
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ata_acpi_gtf_to_tf(struct ata_device *dev, const struct ata_acpi_gtf *gtf, struct ata_taskfile *tf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff81c1e1d0)
Location: drivers/ata/libata-acpi.c:541
Inline: False
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
**Symbols:**

```
ffffffff81c1e1d0-ffffffff81c1e25e: ata_acpi_gtf_to_tf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ata_acpi_gtf_to_tf(struct ata_device *dev, const struct ata_acpi_gtf *gtf, struct ata_taskfile *tf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff81c732d0)
Location: drivers/ata/libata-acpi.c:541
Inline: False
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
**Symbols:**

```
ffffffff81c732d0-ffffffff81c7335e: ata_acpi_gtf_to_tf (STB_LOCAL)
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
void ata_acpi_gtf_to_tf(struct ata_device *dev, const struct ata_acpi_gtf *gtf, struct ata_taskfile *tf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffff8000109b5278)
Location: drivers/ata/libata-acpi.c:549
Inline: False
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
**Symbols:**

```
ffff8000109b5278-ffff8000109b5320: ata_acpi_gtf_to_tf (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void ata_acpi_gtf_to_tf(struct ata_device *dev, const struct ata_acpi_gtf *gtf, struct ata_taskfile *tf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff8176da20)
Location: drivers/ata/libata-acpi.c:549
Inline: False
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
**Symbols:**

```
ffffffff8176da20-ffffffff8176daa4: ata_acpi_gtf_to_tf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ata_acpi_gtf_to_tf(struct ata_device *dev, const struct ata_acpi_gtf *gtf, struct ata_taskfile *tf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff8174d870)
Location: drivers/ata/libata-acpi.c:549
Inline: False
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
**Symbols:**

```
ffffffff8174d870-ffffffff8174d8f4: ata_acpi_gtf_to_tf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ata_acpi_gtf_to_tf(struct ata_device *dev, const struct ata_acpi_gtf *gtf, struct ata_taskfile *tf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff8179d7e0)
Location: drivers/ata/libata-acpi.c:549
Inline: False
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
**Symbols:**

```
ffffffff8179d7e0-ffffffff8179d864: ata_acpi_gtf_to_tf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ata_acpi_gtf_to_tf(struct ata_device *dev, const struct ata_acpi_gtf *gtf, struct ata_taskfile *tf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-acpi.c (ffffffff817b7660)
Location: drivers/ata/libata-acpi.c:549
Inline: False
Direct callers:
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
  - drivers/ata/libata-acpi.c:ata_acpi_run_tf
```
**Symbols:**

```
ffffffff817b7660-ffffffff817b76e4: ata_acpi_gtf_to_tf (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
