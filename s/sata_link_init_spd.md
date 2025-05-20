# Function: <code>sata_link_init_spd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int sata_link_init_spd(struct ata_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815cf320)
Location: drivers/ata/libata-core.c:5598
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff815cf320-ffffffff815cf485: sata_link_init_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int sata_link_init_spd(struct ata_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81627ef0)
Location: drivers/ata/libata-core.c:5790
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff81627ef0-ffffffff81628078: sata_link_init_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sata_link_init_spd(struct ata_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81658b60)
Location: drivers/ata/libata-core.c:5832
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff81658b60-ffffffff81658ce8: sata_link_init_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int sata_link_init_spd(struct ata_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8166d330)
Location: drivers/ata/libata-core.c:5918
Inline: True
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff8166d330-ffffffff8166d4e4: sata_link_init_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int sata_link_init_spd(struct ata_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d6980)
Location: drivers/ata/libata-core.c:5949
Inline: True
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff816d6980-ffffffff816d6b34: sata_link_init_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sata_link_init_spd(struct ata_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:5965
Inline: True
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff81713d04-ffffffff81713d7c: sata_link_init_spd.cold.63 (STB_LOCAL)
ffffffff817125c0-ffffffff817126d9: sata_link_init_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sata_link_init_spd(struct ata_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81734aa2)
Location: drivers/ata/libata-core.c:5969
Inline: True
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff817361b3-ffffffff81736235: sata_link_init_spd.cold.64 (STB_LOCAL)
ffffffff81734a70-ffffffff81734b87: sata_link_init_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sata_link_init_spd(struct ata_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81770422)
Location: drivers/ata/libata-core.c:5954
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff81771db1-ffffffff81771e33: sata_link_init_spd.cold (STB_LOCAL)
ffffffff817703f0-ffffffff81770507: sata_link_init_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sata_link_init_spd(struct ata_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81794482)
Location: drivers/ata/libata-core.c:5978
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff81795d30-ffffffff81795db2: sata_link_init_spd.cold (STB_LOCAL)
ffffffff81794450-ffffffff81794567: sata_link_init_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int sata_link_init_spd(struct ata_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81858710)
Location: drivers/ata/libata-core.c:5219
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff81858710-ffffffff81858771: sata_link_init_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int sata_link_init_spd(struct ata_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81868970)
Location: drivers/ata/libata-core.c:5219
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff81868970-ffffffff818689d1: sata_link_init_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sata_link_init_spd(struct ata_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8184b315)
Location: drivers/ata/libata-core.c:5219
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff81c09cb3-ffffffff81c09d3f: sata_link_init_spd.cold (STB_LOCAL)
ffffffff8184b2e0-ffffffff8184b408: sata_link_init_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sata_link_init_spd(struct ata_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff818d8725)
Location: drivers/ata/libata-core.c:5279
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff81d0e440-ffffffff81d0e4f8: sata_link_init_spd.cold (STB_LOCAL)
ffffffff818d86f0-ffffffff818d8818: sata_link_init_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int sata_link_init_spd(struct ata_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81a29910)
Location: drivers/ata/libata-core.c:5262
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff81a29910-ffffffff81a2997d: sata_link_init_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int sata_link_init_spd(struct ata_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81bac440)
Location: drivers/ata/libata-core.c:5268
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff81bac440-ffffffff81bac4ad: sata_link_init_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int sata_link_init_spd(struct ata_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c035d0)
Location: drivers/ata/libata-core.c:5493
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff81c035d0-ffffffff81c0363d: sata_link_init_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int sata_link_init_spd(struct ata_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c58d90)
Location: drivers/ata/libata-core.c:5461
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff81c58d90-ffffffff81c58dfd: sata_link_init_spd (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int sata_link_init_spd(struct ata_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff80001099ea88)
Location: drivers/ata/libata-core.c:5978
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffff80001099ea88-ffff80001099ec34: sata_link_init_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int sata_link_init_spd(struct ata_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a6f140)
Location: drivers/ata/libata-core.c:5978
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
c0a6f140-c0a6f2dc: sata_link_init_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int sata_link_init_spd(struct ata_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a62e60)
Location: drivers/ata/libata-core.c:5978
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
c000000000a62e60-c000000000a6307c: sata_link_init_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int sata_link_init_spd(struct ata_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005fe9e8)
Location: drivers/ata/libata-core.c:5978
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffe0005fe9e8-ffffffe0005feb76: sata_link_init_spd (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sata_link_init_spd(struct ata_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81759592)
Location: drivers/ata/libata-core.c:5978
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff8175ae47-ffffffff8175aec9: sata_link_init_spd.cold (STB_LOCAL)
ffffffff81759560-ffffffff81759677: sata_link_init_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sata_link_init_spd(struct ata_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81739432)
Location: drivers/ata/libata-core.c:5978
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff8173ace7-ffffffff8173ad69: sata_link_init_spd.cold (STB_LOCAL)
ffffffff81739400-ffffffff81739517: sata_link_init_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sata_link_init_spd(struct ata_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81789302)
Location: drivers/ata/libata-core.c:5978
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff8178abb0-ffffffff8178ac32: sata_link_init_spd.cold (STB_LOCAL)
ffffffff817892d0-ffffffff817893e7: sata_link_init_spd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sata_link_init_spd(struct ata_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff817a3152)
Location: drivers/ata/libata-core.c:5978
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-core.c:ata_host_register
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff817a4a00-ffffffff817a4a82: sata_link_init_spd.cold (STB_LOCAL)
ffffffff817a3120-ffffffff817a3237: sata_link_init_spd (STB_GLOBAL)
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
