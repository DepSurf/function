# Function: <code>ata_host_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ata_host_register(struct ata_host *host, struct scsi_host_template *sht);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815cf490)
Location: drivers/ata/libata-core.c:6116
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
**Symbols:**

```
ffffffff815cf490-ffffffff815cf73a: ata_host_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ata_host_register(struct ata_host *host, struct scsi_host_template *sht);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81628080)
Location: drivers/ata/libata-core.c:6308
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
**Symbols:**

```
ffffffff81628080-ffffffff81628343: ata_host_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ata_host_register(struct ata_host *host, struct scsi_host_template *sht);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81658cf0)
Location: drivers/ata/libata-core.c:6350
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
**Symbols:**

```
ffffffff81658cf0-ffffffff81658fb3: ata_host_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ata_host_register(struct ata_host *host, struct scsi_host_template *sht);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8166d4f0)
Location: drivers/ata/libata-core.c:6436
Inline: True
Direct callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
**Symbols:**

```
ffffffff8166d4f0-ffffffff8166d7c6: ata_host_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ata_host_register(struct ata_host *host, struct scsi_host_template *sht);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d6b40)
Location: drivers/ata/libata-core.c:6466
Inline: True
Direct callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
**Symbols:**

```
ffffffff816d6b40-ffffffff816d6e16: ata_host_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ata_host_register(struct ata_host *host, struct scsi_host_template *sht);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:6513
Inline: True
Direct callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
**Symbols:**

```
ffffffff81713d7c-ffffffff81713e71: ata_host_register.cold.64 (STB_LOCAL)
ffffffff817126e0-ffffffff817128a7: ata_host_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ata_host_register(struct ata_host *host, struct scsi_host_template *sht);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:6517
Inline: True
Direct callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
**Symbols:**

```
ffffffff81736235-ffffffff8173632a: ata_host_register.cold.65 (STB_LOCAL)
ffffffff81734b90-ffffffff81734d57: ata_host_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ata_host_register(struct ata_host *host, struct scsi_host_template *sht);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:6502
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_activate
  - drivers/ata/libata-core.c:ata_host_activate
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
**Symbols:**

```
ffffffff81771e33-ffffffff81771f59: ata_host_register.cold (STB_LOCAL)
ffffffff81770510-ffffffff817706af: ata_host_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ata_host_register(struct ata_host *host, struct scsi_host_template *sht);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:6526
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
**Symbols:**

```
ffffffff81795db2-ffffffff81795ec8: ata_host_register.cold (STB_LOCAL)
ffffffff81794570-ffffffff8179470f: ata_host_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ata_host_register(struct ata_host *host, struct scsi_host_template *sht);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:5710
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
**Symbols:**

```
ffffffff81859f34-ffffffff8185a054: ata_host_register.cold (STB_LOCAL)
ffffffff81858780-ffffffff8185891f: ata_host_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ata_host_register(struct ata_host *host, struct scsi_host_template *sht);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:5710
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
**Symbols:**

```
ffffffff81c17f47-ffffffff81c18067: ata_host_register.cold (STB_LOCAL)
ffffffff818689e0-ffffffff81868b7f: ata_host_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ata_host_register(struct ata_host *host, struct scsi_host_template *sht);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:5710
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
**Symbols:**

```
ffffffff81c09d3f-ffffffff81c09e5f: ata_host_register.cold (STB_LOCAL)
ffffffff8184b410-ffffffff8184b5aa: ata_host_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ata_host_register(struct ata_host *host, struct scsi_host_template *sht);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:5770
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
**Symbols:**

```
ffffffff81d0e4f8-ffffffff81d0e582: ata_host_register.cold (STB_LOCAL)
ffffffff818d8820-ffffffff818d8a69: ata_host_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ata_host_register(struct ata_host *host, struct scsi_host_template *sht);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:5738
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
**Symbols:**

```
ffffffff81ed7343-ffffffff81ed73c8: ata_host_register.cold (STB_LOCAL)
ffffffff81a29980-ffffffff81a29be9: ata_host_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ata_host_register(struct ata_host *host, struct scsi_host_template *sht);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81bac4c0)
Location: drivers/ata/libata-core.c:5744
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
**Symbols:**

```
ffffffff81bac4c0-ffffffff81bac7d6: ata_host_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ata_host_register(struct ata_host *host, const struct scsi_host_template *sht);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c03650)
Location: drivers/ata/libata-core.c:5970
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
**Symbols:**

```
ffffffff81c03650-ffffffff81c03966: ata_host_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ata_host_register(struct ata_host *host, const struct scsi_host_template *sht);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c58e10)
Location: drivers/ata/libata-core.c:5926
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
**Symbols:**

```
ffffffff81c58e10-ffffffff81c59123: ata_host_register (STB_GLOBAL)
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
int ata_host_register(struct ata_host *host, struct scsi_host_template *sht);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff80001099ec38)
Location: drivers/ata/libata-core.c:6526
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
**Symbols:**

```
ffff80001099ec38-ffff80001099ef28: ata_host_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ata_host_register(struct ata_host *host, struct scsi_host_template *sht);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a6f2dc)
Location: drivers/ata/libata-core.c:6526
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
**Symbols:**

```
c0a6f2dc-c0a6f604: ata_host_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ata_host_register(struct ata_host *host, struct scsi_host_template *sht);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a63080)
Location: drivers/ata/libata-core.c:6526
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_host_activate
  - drivers/ata/libata-core.c:ata_host_activate
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
**Symbols:**

```
c000000000a63080-c000000000a63470: ata_host_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ata_host_register(struct ata_host *host, struct scsi_host_template *sht);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005feb76)
Location: drivers/ata/libata-core.c:6526
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
**Symbols:**

```
ffffffe0005feb76-ffffffe0005fedfc: ata_host_register (STB_GLOBAL)
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
int ata_host_register(struct ata_host *host, struct scsi_host_template *sht);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:6526
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
**Symbols:**

```
ffffffff8175aec9-ffffffff8175afdf: ata_host_register.cold (STB_LOCAL)
ffffffff81759680-ffffffff8175981f: ata_host_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ata_host_register(struct ata_host *host, struct scsi_host_template *sht);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:6526
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
**Symbols:**

```
ffffffff8173ad69-ffffffff8173ae7f: ata_host_register.cold (STB_LOCAL)
ffffffff81739520-ffffffff817396bf: ata_host_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ata_host_register(struct ata_host *host, struct scsi_host_template *sht);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:6526
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
**Symbols:**

```
ffffffff8178ac32-ffffffff8178ad48: ata_host_register.cold (STB_LOCAL)
ffffffff817893f0-ffffffff8178958f: ata_host_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ata_host_register(struct ata_host *host, struct scsi_host_template *sht);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:6526
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
**Symbols:**

```
ffffffff817a4a82-ffffffff817a4b98: ata_host_register.cold (STB_LOCAL)
ffffffff817a3240-ffffffff817a33df: ata_host_register (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct scsi_host_template *sht</code> ➡️ <code>const struct scsi_host_template *sht</code>
</li>
</ul>
</details>
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
