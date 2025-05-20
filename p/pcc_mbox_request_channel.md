# Function: <code>pcc_mbox_request_channel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct mbox_chan *pcc_mbox_request_channel(struct mbox_client *cl, int subspace_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff816eba10)
Location: drivers/mailbox/pcc.c:109
Inline: False
```
**Symbols:**

```
ffffffff816eba10-ffffffff816ebae9: pcc_mbox_request_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct mbox_chan *pcc_mbox_request_channel(struct mbox_client *cl, int subspace_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff81750500)
Location: drivers/mailbox/pcc.c:107
Inline: False
```
**Symbols:**

```
ffffffff81750500-ffffffff817505e0: pcc_mbox_request_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct mbox_chan *pcc_mbox_request_channel(struct mbox_client *cl, int subspace_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff8177c440)
Location: drivers/mailbox/pcc.c:240
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff8177c440-ffffffff8177c599: pcc_mbox_request_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct mbox_chan *pcc_mbox_request_channel(struct mbox_client *cl, int subspace_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff8179afa0)
Location: drivers/mailbox/pcc.c:240
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff8179afa0-ffffffff8179b0f1: pcc_mbox_request_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct mbox_chan *pcc_mbox_request_channel(struct mbox_client *cl, int subspace_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff81811380)
Location: drivers/mailbox/pcc.c:239
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff81811380-ffffffff818114d1: pcc_mbox_request_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct mbox_chan *pcc_mbox_request_channel(struct mbox_client *cl, int subspace_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff8185b1e0)
Location: drivers/mailbox/pcc.c:239
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff8185b1e0-ffffffff8185b32a: pcc_mbox_request_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct mbox_chan *pcc_mbox_request_channel(struct mbox_client *cl, int subspace_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff8187a640)
Location: drivers/mailbox/pcc.c:239
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff8187a640-ffffffff8187a78a: pcc_mbox_request_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct mbox_chan *pcc_mbox_request_channel(struct mbox_client *cl, int subspace_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/pcc.c (0)
Location: drivers/mailbox/pcc.c:230
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff818bfdef-ffffffff818bfe3c: pcc_mbox_request_channel.cold (STB_LOCAL)
ffffffff818bfc70-ffffffff818bfd91: pcc_mbox_request_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct mbox_chan *pcc_mbox_request_channel(struct mbox_client *cl, int subspace_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/pcc.c (0)
Location: drivers/mailbox/pcc.c:230
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff818f290f-ffffffff818f295c: pcc_mbox_request_channel.cold (STB_LOCAL)
ffffffff818f2790-ffffffff818f28b1: pcc_mbox_request_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct mbox_chan *pcc_mbox_request_channel(struct mbox_client *cl, int subspace_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/pcc.c (0)
Location: drivers/mailbox/pcc.c:230
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff819c8133-ffffffff819c8180: pcc_mbox_request_channel.cold (STB_LOCAL)
ffffffff819c7d50-ffffffff819c7e71: pcc_mbox_request_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct mbox_chan *pcc_mbox_request_channel(struct mbox_client *cl, int subspace_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/pcc.c (0)
Location: drivers/mailbox/pcc.c:230
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff81c2d9a8-ffffffff81c2d9f5: pcc_mbox_request_channel.cold (STB_LOCAL)
ffffffff819c7c20-ffffffff819c7d41: pcc_mbox_request_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct mbox_chan *pcc_mbox_request_channel(struct mbox_client *cl, int subspace_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/pcc.c (0)
Location: drivers/mailbox/pcc.c:230
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff81c1fc0e-ffffffff81c1fc5b: pcc_mbox_request_channel.cold (STB_LOCAL)
ffffffff819acb60-ffffffff819acc81: pcc_mbox_request_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct mbox_chan *pcc_mbox_request_channel(struct mbox_client *cl, int subspace_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/pcc.c (0)
Location: drivers/mailbox/pcc.c:230
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff81d315ba-ffffffff81d3161b: pcc_mbox_request_channel.cold (STB_LOCAL)
ffffffff81a5b070-ffffffff81a5b19d: pcc_mbox_request_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct pcc_mbox_chan *pcc_mbox_request_channel(struct mbox_client *cl, int subspace_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff81bcad91)
Location: drivers/mailbox/pcc.c:281
Inline: True
Direct callers:
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff81efdaa0-ffffffff81efdaf9: pcc_mbox_request_channel.cold (STB_LOCAL)
ffffffff81bcad60-ffffffff81bcae9b: pcc_mbox_request_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct pcc_mbox_chan *pcc_mbox_request_channel(struct mbox_client *cl, int subspace_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff81d744f9)
Location: drivers/mailbox/pcc.c:281
Inline: True
Direct callers:
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff820aa263-ffffffff820aa278: pcc_mbox_request_channel.cold (STB_LOCAL)
ffffffff81d744d0-ffffffff81d7464a: pcc_mbox_request_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct pcc_mbox_chan *pcc_mbox_request_channel(struct mbox_client *cl, int subspace_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff81de24f0)
Location: drivers/mailbox/pcc.c:281
Inline: True
Direct callers:
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff81de24f0-ffffffff81de258c: pcc_mbox_request_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct pcc_mbox_chan *pcc_mbox_request_channel(struct mbox_client *cl, int subspace_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff81e98550)
Location: drivers/mailbox/pcc.c:335
Inline: True
Direct callers:
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff81e98550-ffffffff81e985e2: pcc_mbox_request_channel (STB_GLOBAL)
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
struct mbox_chan *pcc_mbox_request_channel(struct mbox_client *cl, int subspace_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffff800010b7bc10)
Location: drivers/mailbox/pcc.c:230
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffff800010b7bc10-ffff800010b7bdc0: pcc_mbox_request_channel (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct mbox_chan *pcc_mbox_request_channel(struct mbox_client *cl, int subspace_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/pcc.c (0)
Location: drivers/mailbox/pcc.c:230
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff81893c3f-ffffffff81893c8c: pcc_mbox_request_channel.cold (STB_LOCAL)
ffffffff81893ac0-ffffffff81893be1: pcc_mbox_request_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct mbox_chan *pcc_mbox_request_channel(struct mbox_client *cl, int subspace_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/pcc.c (0)
Location: drivers/mailbox/pcc.c:230
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff8184c13f-ffffffff8184c18c: pcc_mbox_request_channel.cold (STB_LOCAL)
ffffffff8184bfc0-ffffffff8184c0e1: pcc_mbox_request_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct mbox_chan *pcc_mbox_request_channel(struct mbox_client *cl, int subspace_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/pcc.c (0)
Location: drivers/mailbox/pcc.c:230
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff818e773f-ffffffff818e778c: pcc_mbox_request_channel.cold (STB_LOCAL)
ffffffff818e75c0-ffffffff818e76e1: pcc_mbox_request_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct mbox_chan *pcc_mbox_request_channel(struct mbox_client *cl, int subspace_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/pcc.c (0)
Location: drivers/mailbox/pcc.c:230
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff819043bf-ffffffff8190440c: pcc_mbox_request_channel.cold (STB_LOCAL)
ffffffff81904240-ffffffff81904361: pcc_mbox_request_channel (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct mbox_chan *</code> ➡️ <code>struct pcc_mbox_chan *</code>
</li>
</ul>
</details>
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
