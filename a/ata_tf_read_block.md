# Function: <code>ata_tf_read_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 ata_tf_read_block(struct ata_taskfile *tf, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815ca350)
Location: drivers/ata/libata-core.c:697
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
```
**Symbols:**

```
ffffffff815ca350-ffffffff815ca41c: ata_tf_read_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 ata_tf_read_block(const struct ata_taskfile *tf, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81622bc0)
Location: drivers/ata/libata-core.c:700
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_set_sense_information
```
**Symbols:**

```
ffffffff81622bc0-ffffffff81622c6d: ata_tf_read_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 ata_tf_read_block(const struct ata_taskfile *tf, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81653730)
Location: drivers/ata/libata-core.c:700
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_set_sense_information
```
**Symbols:**

```
ffffffff81653730-ffffffff816537dd: ata_tf_read_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 ata_tf_read_block(const struct ata_taskfile *tf, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81667e90)
Location: drivers/ata/libata-core.c:700
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_set_sense_information
```
**Symbols:**

```
ffffffff81667e90-ffffffff81667f3c: ata_tf_read_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 ata_tf_read_block(const struct ata_taskfile *tf, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d1500)
Location: drivers/ata/libata-core.c:700
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_set_sense_information
```
**Symbols:**

```
ffffffff816d1500-ffffffff816d15ac: ata_tf_read_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
u64 ata_tf_read_block(const struct ata_taskfile *tf, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:700
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_set_sense_information
```
**Symbols:**

```
ffffffff8171307f-ffffffff8171309e: ata_tf_read_block.cold.49 (STB_LOCAL)
ffffffff8170dd60-ffffffff8170ddf2: ata_tf_read_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
u64 ata_tf_read_block(const struct ata_taskfile *tf, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:700
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_set_sense_information
```
**Symbols:**

```
ffffffff8173552f-ffffffff8173554e: ata_tf_read_block.cold.50 (STB_LOCAL)
ffffffff817301d0-ffffffff81730262: ata_tf_read_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
u64 ata_tf_read_block(const struct ata_taskfile *tf, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:684
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_set_sense_information
```
**Symbols:**

```
ffffffff81770f7d-ffffffff81770f9c: ata_tf_read_block.cold (STB_LOCAL)
ffffffff8176b930-ffffffff8176b9c4: ata_tf_read_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
u64 ata_tf_read_block(const struct ata_taskfile *tf, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:684
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_set_sense_information
```
**Symbols:**

```
ffffffff81794f7b-ffffffff81794f9a: ata_tf_read_block.cold (STB_LOCAL)
ffffffff8178f9a0-ffffffff8178fa34: ata_tf_read_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
u64 ata_tf_read_block(const struct ata_taskfile *tf, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:619
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_scsi_set_sense_information
```
**Symbols:**

```
ffffffff818593d4-ffffffff818593f3: ata_tf_read_block.cold (STB_LOCAL)
ffffffff818542f0-ffffffff81854384: ata_tf_read_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
u64 ata_tf_read_block(const struct ata_taskfile *tf, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:619
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_scsi_set_sense_information
```
**Symbols:**

```
ffffffff81c173e7-ffffffff81c17406: ata_tf_read_block.cold (STB_LOCAL)
ffffffff818645c0-ffffffff81864654: ata_tf_read_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
u64 ata_tf_read_block(const struct ata_taskfile *tf, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:619
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_scsi_set_sense_information
```
**Symbols:**

```
ffffffff81c09013-ffffffff81c09033: ata_tf_read_block.cold (STB_LOCAL)
ffffffff81847060-ffffffff818470f5: ata_tf_read_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 ata_tf_read_block(const struct ata_taskfile *tf, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:625
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_scsi_set_sense_information
```
**Symbols:**

```
ffffffff81d0d867-ffffffff81d0d887: ata_tf_read_block.cold (STB_LOCAL)
ffffffff818d3d60-ffffffff818d3df5: ata_tf_read_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 ata_tf_read_block(const struct ata_taskfile *tf, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:632
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_scsi_set_sense_information
```
**Symbols:**

```
ffffffff81ed6809-ffffffff81ed683d: ata_tf_read_block.cold (STB_LOCAL)
ffffffff81a24450-ffffffff81a24501: ata_tf_read_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 ata_tf_read_block(const struct ata_taskfile *tf, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81ba6450)
Location: drivers/ata/libata-core.c:632
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_scsi_set_sense_information
```
**Symbols:**

```
ffffffff81ba6450-ffffffff81ba6536: ata_tf_read_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 ata_tf_read_block(const struct ata_taskfile *tf, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81bfcfc0)
Location: drivers/ata/libata-core.c:634
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_scsi_set_sense_information
```
**Symbols:**

```
ffffffff81bfcfc0-ffffffff81bfd0a6: ata_tf_read_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 ata_tf_read_block(const struct ata_taskfile *tf, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c52cc0)
Location: drivers/ata/libata-core.c:634
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_scsi_set_sense_information
```
**Symbols:**

```
ffffffff81c52cc0-ffffffff81c52da6: ata_tf_read_block (STB_GLOBAL)
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
u64 ata_tf_read_block(const struct ata_taskfile *tf, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff800010999468)
Location: drivers/ata/libata-core.c:684
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_set_sense_information
```
**Symbols:**

```
ffff800010999468-ffff800010999534: ata_tf_read_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 ata_tf_read_block(const struct ata_taskfile *tf, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a693d8)
Location: drivers/ata/libata-core.c:684
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_set_sense_information
```
**Symbols:**

```
c0a693d8-c0a694c0: ata_tf_read_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 ata_tf_read_block(const struct ata_taskfile *tf, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a5c490)
Location: drivers/ata/libata-core.c:684
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_set_sense_information
```
**Symbols:**

```
c000000000a5c490-c000000000a5c5ac: ata_tf_read_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 ata_tf_read_block(const struct ata_taskfile *tf, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005f9e4a)
Location: drivers/ata/libata-core.c:684
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_set_sense_information
```
**Symbols:**

```
ffffffe0005f9e4a-ffffffe0005f9f14: ata_tf_read_block (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
u64 ata_tf_read_block(const struct ata_taskfile *tf, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:684
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_set_sense_information
```
**Symbols:**

```
ffffffff8175a08b-ffffffff8175a0aa: ata_tf_read_block.cold (STB_LOCAL)
ffffffff81754b10-ffffffff81754ba4: ata_tf_read_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
u64 ata_tf_read_block(const struct ata_taskfile *tf, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:684
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_set_sense_information
```
**Symbols:**

```
ffffffff81739f2b-ffffffff81739f4a: ata_tf_read_block.cold (STB_LOCAL)
ffffffff817349b0-ffffffff81734a44: ata_tf_read_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
u64 ata_tf_read_block(const struct ata_taskfile *tf, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:684
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_set_sense_information
```
**Symbols:**

```
ffffffff81789dfb-ffffffff81789e1a: ata_tf_read_block.cold (STB_LOCAL)
ffffffff81784820-ffffffff817848b4: ata_tf_read_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
u64 ata_tf_read_block(const struct ata_taskfile *tf, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:684
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_set_sense_information
```
**Symbols:**

```
ffffffff817a3c4b-ffffffff817a3c6a: ata_tf_read_block.cold (STB_LOCAL)
ffffffff8179e610-ffffffff8179e6a4: ata_tf_read_block (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ata_taskfile *tf</code> ➡️ <code>const struct ata_taskfile *tf</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
