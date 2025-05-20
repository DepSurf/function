# Function: <code>sata_link_hardreset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sata_link_hardreset(struct ata_link *link, const long unsigned int *timing, long unsigned int deadline, bool *online, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815cee60)
Location: drivers/ata/libata-core.c:3768
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_std_hardreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff815cee60-ffffffff815cf06d: sata_link_hardreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sata_link_hardreset(struct ata_link *link, const long unsigned int *timing, long unsigned int deadline, bool *online, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81627a40)
Location: drivers/ata/libata-core.c:3944
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_std_hardreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81627a40-ffffffff81627c4e: sata_link_hardreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sata_link_hardreset(struct ata_link *link, const long unsigned int *timing, long unsigned int deadline, bool *online, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816586a0)
Location: drivers/ata/libata-core.c:3986
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_std_hardreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff816586a0-ffffffff816588ae: sata_link_hardreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sata_link_hardreset(struct ata_link *link, const long unsigned int *timing, long unsigned int deadline, bool *online, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8166cea0)
Location: drivers/ata/libata-core.c:4063
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_std_hardreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff8166cea0-ffffffff8166d0ae: sata_link_hardreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sata_link_hardreset(struct ata_link *link, const long unsigned int *timing, long unsigned int deadline, bool *online, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d64f0)
Location: drivers/ata/libata-core.c:4073
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_std_hardreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff816d64f0-ffffffff816d66fe: sata_link_hardreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int sata_link_hardreset(struct ata_link *link, const long unsigned int *timing, long unsigned int deadline, bool *online, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4069
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_std_hardreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81713cd9-ffffffff81713d04: sata_link_hardreset.cold.62 (STB_LOCAL)
ffffffff81712140-ffffffff81712340: sata_link_hardreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int sata_link_hardreset(struct ata_link *link, const long unsigned int *timing, long unsigned int deadline, bool *online, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4070
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_std_hardreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81736188-ffffffff817361b3: sata_link_hardreset.cold.63 (STB_LOCAL)
ffffffff817345e0-ffffffff817347e0: sata_link_hardreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sata_link_hardreset(struct ata_link *link, const long unsigned int *timing, long unsigned int deadline, bool *online, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4054
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_std_hardreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81771d5d-ffffffff81771d8b: sata_link_hardreset.cold (STB_LOCAL)
ffffffff8176ff80-ffffffff8177016e: sata_link_hardreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int sata_link_hardreset(struct ata_link *link, const long unsigned int *timing, long unsigned int deadline, bool *online, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4054
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_std_hardreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81795d02-ffffffff81795d30: sata_link_hardreset.cold (STB_LOCAL)
ffffffff81793fe0-ffffffff817941ce: sata_link_hardreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sata_link_hardreset(struct ata_link *link, const long unsigned int *timing, long unsigned int deadline, bool *online, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81868930)
Location: drivers/ata/libata-sata.c:529
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_std_hardreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_handle_disabled_links
```
**Symbols:**

```
ffffffff81868930-ffffffff81868b3e: sata_link_hardreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sata_link_hardreset(struct ata_link *link, const long unsigned int *timing, long unsigned int deadline, bool *online, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81877740)
Location: drivers/ata/libata-sata.c:529
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_std_hardreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_handle_disabled_links
```
**Symbols:**

```
ffffffff81877740-ffffffff8187794e: sata_link_hardreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sata_link_hardreset(struct ata_link *link, const long unsigned int *timing, long unsigned int deadline, bool *online, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81859f20)
Location: drivers/ata/libata-sata.c:529
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_std_hardreset
```
**Symbols:**

```
ffffffff81859f20-ffffffff8185a12e: sata_link_hardreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sata_link_hardreset(struct ata_link *link, const long unsigned int *timing, long unsigned int deadline, bool *online, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff818e8a10)
Location: drivers/ata/libata-sata.c:529
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_std_hardreset
```
**Symbols:**

```
ffffffff818e8a10-ffffffff818e8c1e: sata_link_hardreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sata_link_hardreset(struct ata_link *link, const long unsigned int *timing, long unsigned int deadline, bool *online, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-sata.c (0)
Location: drivers/ata/libata-sata.c:529
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_std_hardreset
  - drivers/ata/libata-sff.c:sata_sff_hardreset
```
**Symbols:**

```
ffffffff81ed8e0f-ffffffff81ed8e65: sata_link_hardreset.cold (STB_LOCAL)
ffffffff81a3a280-ffffffff81a3a488: sata_link_hardreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sata_link_hardreset(struct ata_link *link, const long unsigned int *timing, long unsigned int deadline, bool *online, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81bbf650)
Location: drivers/ata/libata-sata.c:529
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_std_hardreset
  - drivers/ata/libata-sff.c:sata_sff_hardreset
```
**Symbols:**

```
ffffffff81bbf650-ffffffff81bbf8ab: sata_link_hardreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sata_link_hardreset(struct ata_link *link, const long unsigned int *timing, long unsigned int deadline, bool *online, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81c17140)
Location: drivers/ata/libata-sata.c:531
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_std_hardreset
  - drivers/ata/libata-sff.c:sata_sff_hardreset
```
**Symbols:**

```
ffffffff81c17140-ffffffff81c1739b: sata_link_hardreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sata_link_hardreset(struct ata_link *link, const unsigned int *timing, long unsigned int deadline, bool *online, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81c6c240)
Location: drivers/ata/libata-sata.c:544
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_std_hardreset
  - drivers/ata/libata-sff.c:sata_sff_hardreset
```
**Symbols:**

```
ffffffff81c6c240-ffffffff81c6c450: sata_link_hardreset (STB_GLOBAL)
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
int sata_link_hardreset(struct ata_link *link, const long unsigned int *timing, long unsigned int deadline, bool *online, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff80001099e598)
Location: drivers/ata/libata-core.c:4054
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_std_hardreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libahci.c:ahci_do_hardreset
```
**Symbols:**

```
ffff80001099e598-ffff80001099e7b4: sata_link_hardreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sata_link_hardreset(struct ata_link *link, const long unsigned int *timing, long unsigned int deadline, bool *online, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a6eca8)
Location: drivers/ata/libata-core.c:4054
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_std_hardreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libahci.c:ahci_do_hardreset
  - drivers/ata/sata_highbank.c:ahci_highbank_hardreset
```
**Symbols:**

```
c0a6eca8-c0a6eed4: sata_link_hardreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sata_link_hardreset(struct ata_link *link, const long unsigned int *timing, long unsigned int deadline, bool *online, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a628e0)
Location: drivers/ata/libata-core.c:4054
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_std_hardreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
c000000000a628e0-c000000000a62b6c: sata_link_hardreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sata_link_hardreset(struct ata_link *link, const long unsigned int *timing, long unsigned int deadline, bool *online, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005fe61e)
Location: drivers/ata/libata-core.c:4054
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_std_hardreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffe0005fe61e-ffffffe0005fe7c6: sata_link_hardreset (STB_GLOBAL)
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
int sata_link_hardreset(struct ata_link *link, const long unsigned int *timing, long unsigned int deadline, bool *online, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4054
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_std_hardreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff8175ae19-ffffffff8175ae47: sata_link_hardreset.cold (STB_LOCAL)
ffffffff817590f0-ffffffff817592de: sata_link_hardreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int sata_link_hardreset(struct ata_link *link, const long unsigned int *timing, long unsigned int deadline, bool *online, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4054
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_std_hardreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff8173acb9-ffffffff8173ace7: sata_link_hardreset.cold (STB_LOCAL)
ffffffff81738f90-ffffffff8173917e: sata_link_hardreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int sata_link_hardreset(struct ata_link *link, const long unsigned int *timing, long unsigned int deadline, bool *online, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4054
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_std_hardreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff8178ab82-ffffffff8178abb0: sata_link_hardreset.cold (STB_LOCAL)
ffffffff81788e60-ffffffff8178904e: sata_link_hardreset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int sata_link_hardreset(struct ata_link *link, const long unsigned int *timing, long unsigned int deadline, bool *online, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4054
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_std_hardreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff817a49d2-ffffffff817a4a00: sata_link_hardreset.cold (STB_LOCAL)
ffffffff817a2cb0-ffffffff817a2e9e: sata_link_hardreset (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const long unsigned int *timing</code> ➡️ <code>const unsigned int *timing</code>
</li>
</ul>
</details>
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
