# Function: <code>sata_link_scr_lpm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sata_link_scr_lpm(struct ata_link *link, enum ata_lpm_policy policy, bool spm_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815c8900)
Location: drivers/ata/libata-core.c:3645
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_set_lpm
  - drivers/ata/ata_piix.c:piix_sidpr_set_lpm
```
**Symbols:**

```
ffffffff815c8900-ffffffff815c8a1e: sata_link_scr_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sata_link_scr_lpm(struct ata_link *link, enum ata_lpm_policy policy, bool spm_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81620f00)
Location: drivers/ata/libata-core.c:3821
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_set_lpm
  - drivers/ata/ata_piix.c:piix_sidpr_set_lpm
```
**Symbols:**

```
ffffffff81620f00-ffffffff8162101e: sata_link_scr_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sata_link_scr_lpm(struct ata_link *link, enum ata_lpm_policy policy, bool spm_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81651a80)
Location: drivers/ata/libata-core.c:3863
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_set_lpm
  - drivers/ata/ata_piix.c:piix_sidpr_set_lpm
```
**Symbols:**

```
ffffffff81651a80-ffffffff81651b9e: sata_link_scr_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sata_link_scr_lpm(struct ata_link *link, enum ata_lpm_policy policy, bool spm_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816660f0)
Location: drivers/ata/libata-core.c:3940
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_set_lpm
  - drivers/ata/ata_piix.c:piix_sidpr_set_lpm
```
**Symbols:**

```
ffffffff816660f0-ffffffff816661ff: sata_link_scr_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sata_link_scr_lpm(struct ata_link *link, enum ata_lpm_policy policy, bool spm_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816cf730)
Location: drivers/ata/libata-core.c:3949
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_set_lpm
  - drivers/ata/ata_piix.c:piix_sidpr_set_lpm
```
**Symbols:**

```
ffffffff816cf730-ffffffff816cf844: sata_link_scr_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sata_link_scr_lpm(struct ata_link *link, enum ata_lpm_policy policy, bool spm_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8170c170)
Location: drivers/ata/libata-core.c:3945
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_set_lpm
  - drivers/ata/ata_piix.c:piix_sidpr_set_lpm
```
**Symbols:**

```
ffffffff8170c170-ffffffff8170c280: sata_link_scr_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sata_link_scr_lpm(struct ata_link *link, enum ata_lpm_policy policy, bool spm_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8172e5f0)
Location: drivers/ata/libata-core.c:3945
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_set_lpm
  - drivers/ata/ata_piix.c:piix_sidpr_set_lpm
```
**Symbols:**

```
ffffffff8172e5f0-ffffffff8172e700: sata_link_scr_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sata_link_scr_lpm(struct ata_link *link, enum ata_lpm_policy policy, bool spm_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3929
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_set_lpm
  - drivers/ata/ata_piix.c:piix_sidpr_set_lpm
```
**Symbols:**

```
ffffffff81770c57-ffffffff81770c6d: sata_link_scr_lpm.cold (STB_LOCAL)
ffffffff81769de0-ffffffff81769ef8: sata_link_scr_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sata_link_scr_lpm(struct ata_link *link, enum ata_lpm_policy policy, bool spm_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8178de40)
Location: drivers/ata/libata-core.c:3929
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_set_lpm
  - drivers/ata/ata_piix.c:piix_sidpr_set_lpm
```
**Symbols:**

```
ffffffff8178de40-ffffffff8178df51: sata_link_scr_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sata_link_scr_lpm(struct ata_link *link, enum ata_lpm_policy policy, bool spm_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff818676e0)
Location: drivers/ata/libata-sata.c:367
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_set_lpm
  - drivers/ata/ata_piix.c:piix_sidpr_set_lpm
```
**Symbols:**

```
ffffffff818676e0-ffffffff818677f1: sata_link_scr_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sata_link_scr_lpm(struct ata_link *link, enum ata_lpm_policy policy, bool spm_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff818764f0)
Location: drivers/ata/libata-sata.c:367
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_set_lpm
  - drivers/ata/ata_piix.c:piix_sidpr_set_lpm
```
**Symbols:**

```
ffffffff818764f0-ffffffff81876601: sata_link_scr_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sata_link_scr_lpm(struct ata_link *link, enum ata_lpm_policy policy, bool spm_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81858d20)
Location: drivers/ata/libata-sata.c:367
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_set_lpm
  - drivers/ata/ata_piix.c:piix_sidpr_set_lpm
```
**Symbols:**

```
ffffffff81858d20-ffffffff81858e31: sata_link_scr_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sata_link_scr_lpm(struct ata_link *link, enum ata_lpm_policy policy, bool spm_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff818e76b0)
Location: drivers/ata/libata-sata.c:367
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_set_lpm
  - drivers/ata/ata_piix.c:piix_sidpr_set_lpm
```
**Symbols:**

```
ffffffff818e76b0-ffffffff818e77c1: sata_link_scr_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sata_link_scr_lpm(struct ata_link *link, enum ata_lpm_policy policy, bool spm_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81a38e40)
Location: drivers/ata/libata-sata.c:367
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_set_lpm
  - drivers/ata/ata_piix.c:piix_sidpr_set_lpm
```
**Symbols:**

```
ffffffff81a38e40-ffffffff81a38f65: sata_link_scr_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sata_link_scr_lpm(struct ata_link *link, enum ata_lpm_policy policy, bool spm_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81bbdea0)
Location: drivers/ata/libata-sata.c:367
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_set_lpm
  - drivers/ata/ata_piix.c:piix_sidpr_set_lpm
```
**Symbols:**

```
ffffffff81bbdea0-ffffffff81bbdfc5: sata_link_scr_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sata_link_scr_lpm(struct ata_link *link, enum ata_lpm_policy policy, bool spm_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81c156f0)
Location: drivers/ata/libata-sata.c:369
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_set_lpm
  - drivers/ata/ata_piix.c:piix_sidpr_set_lpm
```
**Symbols:**

```
ffffffff81c156f0-ffffffff81c15819: sata_link_scr_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sata_link_scr_lpm(struct ata_link *link, enum ata_lpm_policy policy, bool spm_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81c6a890)
Location: drivers/ata/libata-sata.c:369
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_set_lpm
  - drivers/ata/ata_piix.c:piix_sidpr_set_lpm
```
**Symbols:**

```
ffffffff81c6a890-ffffffff81c6a9f5: sata_link_scr_lpm (STB_GLOBAL)
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
int sata_link_scr_lpm(struct ata_link *link, enum ata_lpm_policy policy, bool spm_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff800010996da8)
Location: drivers/ata/libata-core.c:3929
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_set_lpm
  - drivers/ata/libahci.c:ahci_set_lpm
  - drivers/ata/libahci.c:ahci_set_lpm
```
**Symbols:**

```
ffff800010996da8-ffff800010996eec: sata_link_scr_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sata_link_scr_lpm(struct ata_link *link, enum ata_lpm_policy policy, bool spm_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a673ec)
Location: drivers/ata/libata-core.c:3929
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_set_lpm
  - drivers/ata/libahci.c:ahci_set_lpm
  - drivers/ata/libahci.c:ahci_set_lpm
```
**Symbols:**

```
c0a673ec-c0a67540: sata_link_scr_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sata_link_scr_lpm(struct ata_link *link, enum ata_lpm_policy policy, bool spm_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a59b10)
Location: drivers/ata/libata-core.c:3929
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_set_lpm
```
**Symbols:**

```
c000000000a59b10-c000000000a59cac: sata_link_scr_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sata_link_scr_lpm(struct ata_link *link, enum ata_lpm_policy policy, bool spm_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005f825c)
Location: drivers/ata/libata-core.c:3929
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_set_lpm
```
**Symbols:**

```
ffffffe0005f825c-ffffffe0005f8362: sata_link_scr_lpm (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int sata_link_scr_lpm(struct ata_link *link, enum ata_lpm_policy policy, bool spm_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81752fd0)
Location: drivers/ata/libata-core.c:3929
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_set_lpm
  - drivers/ata/ata_piix.c:piix_sidpr_set_lpm
```
**Symbols:**

```
ffffffff81752fd0-ffffffff817530e1: sata_link_scr_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sata_link_scr_lpm(struct ata_link *link, enum ata_lpm_policy policy, bool spm_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81732e70)
Location: drivers/ata/libata-core.c:3929
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_set_lpm
  - drivers/ata/ata_piix.c:piix_sidpr_set_lpm
```
**Symbols:**

```
ffffffff81732e70-ffffffff81732f81: sata_link_scr_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sata_link_scr_lpm(struct ata_link *link, enum ata_lpm_policy policy, bool spm_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81782cc0)
Location: drivers/ata/libata-core.c:3929
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_set_lpm
  - drivers/ata/ata_piix.c:piix_sidpr_set_lpm
```
**Symbols:**

```
ffffffff81782cc0-ffffffff81782dd1: sata_link_scr_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sata_link_scr_lpm(struct ata_link *link, enum ata_lpm_policy policy, bool spm_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8179cb80)
Location: drivers/ata/libata-core.c:3929
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_set_lpm
  - drivers/ata/ata_piix.c:piix_sidpr_set_lpm
```
**Symbols:**

```
ffffffff8179cb80-ffffffff8179cc91: sata_link_scr_lpm (STB_GLOBAL)
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
