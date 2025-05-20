# Function: <code>ata_scsi_sdev_config</code>

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
In drivers/ata/libata-scsi.c (ffffffff815d1835)
Location: drivers/ata/libata-scsi.c:1092
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_slave_configure
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
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
In drivers/ata/libata-scsi.c (ffffffff8162c6c5)
Location: drivers/ata/libata-scsi.c:1158
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_slave_configure
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
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
In drivers/ata/libata-scsi.c (ffffffff8165d515)
Location: drivers/ata/libata-scsi.c:1237
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_slave_configure
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
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
In drivers/ata/libata-scsi.c (ffffffff81670915)
Location: drivers/ata/libata-scsi.c:1225
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_slave_configure
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
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
In drivers/ata/libata-scsi.c (ffffffff816d9f25)
Location: drivers/ata/libata-scsi.c:1226
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_slave_configure
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
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
In drivers/ata/libata-scsi.c (ffffffff81716415)
Location: drivers/ata/libata-scsi.c:1229
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_slave_configure
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
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
In drivers/ata/libata-scsi.c (ffffffff81738a55)
Location: drivers/ata/libata-scsi.c:1224
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_slave_configure
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
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
In drivers/ata/libata-scsi.c (ffffffff81774a95)
Location: drivers/ata/libata-scsi.c:1209
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_slave_configure
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
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
In drivers/ata/libata-scsi.c (ffffffff81798a05)
Location: drivers/ata/libata-scsi.c:1209
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_slave_configure
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_sdev_config(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8185e87b)
Location: drivers/ata/libata-scsi.c:991
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
Direct callers:
  - drivers/ata/libata-sata.c:ata_sas_slave_configure
```
**Symbols:**

```
ffffffff8185e610-ffffffff8185e62f: ata_scsi_sdev_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_sdev_config(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8186d89b)
Location: drivers/ata/libata-scsi.c:991
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
Direct callers:
  - drivers/ata/libata-sata.c:ata_sas_slave_configure
```
**Symbols:**

```
ffffffff8186d640-ffffffff8186d65f: ata_scsi_sdev_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_sdev_config(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8185077b)
Location: drivers/ata/libata-scsi.c:988
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
Direct callers:
  - drivers/ata/libata-sata.c:ata_sas_slave_configure
```
**Symbols:**

```
ffffffff81850520-ffffffff8185053f: ata_scsi_sdev_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_sdev_config(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff818ddf7b)
Location: drivers/ata/libata-scsi.c:990
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
Direct callers:
  - drivers/ata/libata-sata.c:ata_sas_slave_configure
```
**Symbols:**

```
ffffffff818ddd20-ffffffff818ddd3f: ata_scsi_sdev_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_sdev_config(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81a2ed16)
Location: drivers/ata/libata-scsi.c:1018
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
Direct callers:
  - drivers/ata/libata-sata.c:ata_sas_slave_configure
```
**Symbols:**

```
ffffffff81a2eae0-ffffffff81a2eb05: ata_scsi_sdev_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_sdev_config(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81bb2216)
Location: drivers/ata/libata-scsi.c:1034
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
Direct callers:
  - drivers/ata/libata-sata.c:ata_sas_slave_configure
```
**Symbols:**

```
ffffffff81bb1f70-ffffffff81bb1f95: ata_scsi_sdev_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_sdev_config(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81c09746)
Location: drivers/ata/libata-scsi.c:1037
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
Direct callers:
  - drivers/ata/libata-sata.c:ata_sas_slave_configure
```
**Symbols:**

```
ffffffff81c09490-ffffffff81c094b5: ata_scsi_sdev_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_sdev_config(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81c59aee)
Location: drivers/ata/libata-scsi.c:987
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_slave_alloc
Direct callers:
  - drivers/ata/libata-sata.c:ata_sas_slave_configure
```
**Symbols:**

```
ffffffff81c5e570-ffffffff81c5e594: ata_scsi_sdev_config (STB_GLOBAL)
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
In drivers/ata/libata-scsi.c (ffff8000109a301c)
Location: drivers/ata/libata-scsi.c:1209
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_slave_configure
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (c0a74934)
Location: drivers/ata/libata-scsi.c:1209
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_slave_configure
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (c000000000a6845c)
Location: drivers/ata/libata-scsi.c:1209
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_slave_configure
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffe00060361e)
Location: drivers/ata/libata-scsi.c:1209
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_slave_configure
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
```
</details>
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
In drivers/ata/libata-scsi.c (ffffffff8175daf5)
Location: drivers/ata/libata-scsi.c:1209
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_slave_configure
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
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
In drivers/ata/libata-scsi.c (ffffffff8173d995)
Location: drivers/ata/libata-scsi.c:1209
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_slave_configure
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
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
In drivers/ata/libata-scsi.c (ffffffff8178d885)
Location: drivers/ata/libata-scsi.c:1209
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_slave_configure
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
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
In drivers/ata/libata-scsi.c (ffffffff817a76d5)
Location: drivers/ata/libata-scsi.c:1209
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_slave_configure
  - drivers/ata/libata-scsi.c:ata_scsi_slave_config
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
