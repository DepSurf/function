# Function: <code>__ata_scsi_queuecmd</code>

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
In drivers/ata/libata-scsi.c (ffffffff815d3dfe)
Location: drivers/ata/libata-scsi.c:3453
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
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
In drivers/ata/libata-scsi.c (ffffffff8162d94d)
Location: drivers/ata/libata-scsi.c:3945
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
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
In drivers/ata/libata-scsi.c (ffffffff8165eaad)
Location: drivers/ata/libata-scsi.c:4240
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
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
In drivers/ata/libata-scsi.c (ffffffff8167342e)
Location: drivers/ata/libata-scsi.c:4291
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
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
In drivers/ata/libata-scsi.c (ffffffff816dca1f)
Location: drivers/ata/libata-scsi.c:4298
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
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
In drivers/ata/libata-scsi.c (ffffffff8171915f)
Location: drivers/ata/libata-scsi.c:4307
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
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
In drivers/ata/libata-scsi.c (ffffffff8173b80e)
Location: drivers/ata/libata-scsi.c:4302
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
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
In drivers/ata/libata-scsi.c (ffffffff817773f1)
Location: drivers/ata/libata-scsi.c:4306
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
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
In drivers/ata/libata-scsi.c (ffffffff8179b351)
Location: drivers/ata/libata-scsi.c:4306
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __ata_scsi_queuecmd(struct scsi_cmnd *scmd, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8185f390)
Location: drivers/ata/libata-scsi.c:4020
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
```
**Symbols:**

```
ffffffff8185f390-ffffffff8185f5fd: __ata_scsi_queuecmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __ata_scsi_queuecmd(struct scsi_cmnd *scmd, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8186e370)
Location: drivers/ata/libata-scsi.c:4020
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
```
**Symbols:**

```
ffffffff8186e370-ffffffff8186e5dd: __ata_scsi_queuecmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ata_scsi_queuecmd(struct scsi_cmnd *scmd, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81850b80)
Location: drivers/ata/libata-scsi.c:4016
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
```
**Symbols:**

```
ffffffff81850b80-ffffffff81850dc2: __ata_scsi_queuecmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __ata_scsi_queuecmd(struct scsi_cmnd *scmd, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff818de710)
Location: drivers/ata/libata-scsi.c:3987
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
```
**Symbols:**

```
ffffffff818de710-ffffffff818de952: __ata_scsi_queuecmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __ata_scsi_queuecmd(struct scsi_cmnd *scmd, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (0)
Location: drivers/ata/libata-scsi.c:3966
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-sata.c:ata_sas_queuecmd
```
**Symbols:**

```
ffffffff81ed7864-ffffffff81ed78a1: __ata_scsi_queuecmd.cold (STB_LOCAL)
ffffffff81a2fc20-ffffffff81a2ff44: __ata_scsi_queuecmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __ata_scsi_queuecmd(struct scsi_cmnd *scmd, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81bb3150)
Location: drivers/ata/libata-scsi.c:3981
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-sata.c:ata_sas_queuecmd
```
**Symbols:**

```
ffffffff81bb3150-ffffffff81bb34e0: __ata_scsi_queuecmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __ata_scsi_queuecmd(struct scsi_cmnd *scmd, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81c0a670)
Location: drivers/ata/libata-scsi.c:4239
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-sata.c:ata_sas_queuecmd
```
**Symbols:**

```
ffffffff81c0a670-ffffffff81c0aa08: __ata_scsi_queuecmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __ata_scsi_queuecmd(struct scsi_cmnd *scmd, struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81c5f720)
Location: drivers/ata/libata-scsi.c:4111
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-sata.c:ata_sas_queuecmd
```
**Symbols:**

```
ffffffff81c5f720-ffffffff81c5fab8: __ata_scsi_queuecmd (STB_GLOBAL)
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
In drivers/ata/libata-scsi.c (ffff8000109a5d94)
Location: drivers/ata/libata-scsi.c:4306
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
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
In drivers/ata/libata-scsi.c (c0a75fe4)
Location: drivers/ata/libata-scsi.c:4306
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
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
In drivers/ata/libata-scsi.c (c000000000a6bd84)
Location: drivers/ata/libata-scsi.c:4306
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
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
In drivers/ata/libata-scsi.c (ffffffe000604aa4)
Location: drivers/ata/libata-scsi.c:4306
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
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
In drivers/ata/libata-scsi.c (ffffffff81760441)
Location: drivers/ata/libata-scsi.c:4306
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
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
In drivers/ata/libata-scsi.c (ffffffff817402a1)
Location: drivers/ata/libata-scsi.c:4306
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
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
In drivers/ata/libata-scsi.c (ffffffff817901d1)
Location: drivers/ata/libata-scsi.c:4306
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
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
In drivers/ata/libata-scsi.c (ffffffff817aa011)
Location: drivers/ata/libata-scsi.c:4306
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
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
