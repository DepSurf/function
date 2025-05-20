# Function: <code>ata_port_classify</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int ata_port_classify(struct ata_port *ap, const struct ata_taskfile *tf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-transport.c (0)
Location: drivers/ata/libata-transport.c:335
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_dev_classify
```
**Symbols:**

```
ffffffff81ed8c63-ffffffff81ed8c7b: ata_port_classify.cold (STB_LOCAL)
ffffffff81a36d10-ffffffff81a36dd8: ata_port_classify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int ata_port_classify(struct ata_port *ap, const struct ata_taskfile *tf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-transport.c (ffffffff81bbba80)
Location: drivers/ata/libata-transport.c:337
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_dev_classify
```
**Symbols:**

```
ffffffff81bbba80-ffffffff81bbbb74: ata_port_classify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int ata_port_classify(struct ata_port *ap, const struct ata_taskfile *tf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-transport.c (ffffffff81c132e0)
Location: drivers/ata/libata-transport.c:337
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_dev_classify
```
**Symbols:**

```
ffffffff81c132e0-ffffffff81c133d4: ata_port_classify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int ata_port_classify(struct ata_port *ap, const struct ata_taskfile *tf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-transport.c (ffffffff81c684a0)
Location: drivers/ata/libata-transport.c:344
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_dev_classify
```
**Symbols:**

```
ffffffff81c684a0-ffffffff81c68594: ata_port_classify (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
