# Function: <code>ata_qc_complete_multiple</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ata_qc_complete_multiple(struct ata_port *ap, u32 qc_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815cb220)
Location: drivers/ata/libata-core.c:5001
Inline: False
```
**Symbols:**

```
ffffffff815cb220-ffffffff815cb2f9: ata_qc_complete_multiple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ata_qc_complete_multiple(struct ata_port *ap, u32 qc_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81623a40)
Location: drivers/ata/libata-core.c:5193
Inline: False
```
**Symbols:**

```
ffffffff81623a40-ffffffff81623b1a: ata_qc_complete_multiple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ata_qc_complete_multiple(struct ata_port *ap, u32 qc_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816545c0)
Location: drivers/ata/libata-core.c:5235
Inline: False
```
**Symbols:**

```
ffffffff816545c0-ffffffff8165469a: ata_qc_complete_multiple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ata_qc_complete_multiple(struct ata_port *ap, u32 qc_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81668c00)
Location: drivers/ata/libata-core.c:5321
Inline: False
```
**Symbols:**

```
ffffffff81668c00-ffffffff81668cde: ata_qc_complete_multiple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ata_qc_complete_multiple(struct ata_port *ap, u32 qc_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d22b0)
Location: drivers/ata/libata-core.c:5353
Inline: False
```
**Symbols:**

```
ffffffff816d22b0-ffffffff816d238e: ata_qc_complete_multiple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ata_qc_complete_multiple(struct ata_port *ap, u64 qc_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:5359
Inline: False
```
**Symbols:**

```
ffffffff817131b4-ffffffff817131d8: ata_qc_complete_multiple.cold.52 (STB_LOCAL)
ffffffff8170e9d0-ffffffff8170eaa8: ata_qc_complete_multiple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ata_qc_complete_multiple(struct ata_port *ap, u64 qc_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:5363
Inline: False
```
**Symbols:**

```
ffffffff81735664-ffffffff81735688: ata_qc_complete_multiple.cold.53 (STB_LOCAL)
ffffffff81730e60-ffffffff81730f38: ata_qc_complete_multiple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ata_qc_complete_multiple(struct ata_port *ap, u64 qc_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:5348
Inline: False
```
**Symbols:**

```
ffffffff817710b6-ffffffff817710da: ata_qc_complete_multiple.cold (STB_LOCAL)
ffffffff8176c610-ffffffff8176c6e1: ata_qc_complete_multiple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ata_qc_complete_multiple(struct ata_port *ap, u64 qc_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:5372
Inline: False
```
**Symbols:**

```
ffffffff817950b4-ffffffff817950d8: ata_qc_complete_multiple.cold (STB_LOCAL)
ffffffff81790680-ffffffff81790751: ata_qc_complete_multiple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ata_qc_complete_multiple(struct ata_port *ap, u64 qc_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81867800)
Location: drivers/ata/libata-sata.c:638
Inline: False
```
**Symbols:**

```
ffffffff81867800-ffffffff818678ef: ata_qc_complete_multiple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ata_qc_complete_multiple(struct ata_port *ap, u64 qc_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81876610)
Location: drivers/ata/libata-sata.c:638
Inline: False
```
**Symbols:**

```
ffffffff81876610-ffffffff818766ff: ata_qc_complete_multiple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ata_qc_complete_multiple(struct ata_port *ap, u64 qc_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81858e40)
Location: drivers/ata/libata-sata.c:638
Inline: False
```
**Symbols:**

```
ffffffff81858e40-ffffffff81858f2f: ata_qc_complete_multiple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ata_qc_complete_multiple(struct ata_port *ap, u64 qc_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-sata.c (0)
Location: drivers/ata/libata-sata.c:638
Inline: False
```
**Symbols:**

```
ffffffff81d0e989-ffffffff81d0e9a2: ata_qc_complete_multiple.cold (STB_LOCAL)
ffffffff818e7870-ffffffff818e7987: ata_qc_complete_multiple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ata_qc_complete_multiple(struct ata_port *ap, u64 qc_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-sata.c (0)
Location: drivers/ata/libata-sata.c:635
Inline: False
```
**Symbols:**

```
ffffffff81ed8c99-ffffffff81ed8cd2: ata_qc_complete_multiple.cold (STB_LOCAL)
ffffffff81a39020-ffffffff81a39135: ata_qc_complete_multiple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ata_qc_complete_multiple(struct ata_port *ap, u64 qc_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-sata.c (0)
Location: drivers/ata/libata-sata.c:635
Inline: False
```
**Symbols:**

```
ffffffff8209c948-ffffffff8209c961: ata_qc_complete_multiple.cold (STB_LOCAL)
ffffffff81bbe0a0-ffffffff81bbe1d3: ata_qc_complete_multiple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ata_qc_complete_multiple(struct ata_port *ap, u64 qc_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-sata.c (0)
Location: drivers/ata/libata-sata.c:637
Inline: False
```
**Symbols:**

```
ffffffff8211d842-ffffffff8211d85b: ata_qc_complete_multiple.cold (STB_LOCAL)
ffffffff81c158f0-ffffffff81c15a40: ata_qc_complete_multiple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ata_qc_complete_multiple(struct ata_port *ap, u64 qc_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-sata.c (0)
Location: drivers/ata/libata-sata.c:649
Inline: False
```
**Symbols:**

```
ffffffff821fb882-ffffffff821fb89a: ata_qc_complete_multiple.cold (STB_LOCAL)
ffffffff81c6aad0-ffffffff81c6ac19: ata_qc_complete_multiple (STB_GLOBAL)
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
int ata_qc_complete_multiple(struct ata_port *ap, u64 qc_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff80001099a2e8)
Location: drivers/ata/libata-core.c:5372
Inline: False
Direct callers:
  - drivers/ata/libahci.c:ahci_handle_port_interrupt
```
**Symbols:**

```
ffff80001099a2e8-ffff80001099a3f8: ata_qc_complete_multiple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ata_qc_complete_multiple(struct ata_port *ap, u64 qc_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a6a42c)
Location: drivers/ata/libata-core.c:5372
Inline: False
Direct callers:
  - drivers/ata/libahci.c:ahci_handle_port_interrupt
```
**Symbols:**

```
c0a6a42c-c0a6a5a8: ata_qc_complete_multiple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ata_qc_complete_multiple(struct ata_port *ap, u64 qc_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a5d750)
Location: drivers/ata/libata-core.c:5372
Inline: False
```
**Symbols:**

```
c000000000a5d750-c000000000a5d8a4: ata_qc_complete_multiple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ata_qc_complete_multiple(struct ata_port *ap, u64 qc_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005fac32)
Location: drivers/ata/libata-core.c:5372
Inline: False
```
**Symbols:**

```
ffffffe0005fac32-ffffffe0005fad80: ata_qc_complete_multiple (STB_GLOBAL)
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
int ata_qc_complete_multiple(struct ata_port *ap, u64 qc_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:5372
Inline: False
```
**Symbols:**

```
ffffffff8175a1c4-ffffffff8175a1e8: ata_qc_complete_multiple.cold (STB_LOCAL)
ffffffff817557c0-ffffffff81755891: ata_qc_complete_multiple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ata_qc_complete_multiple(struct ata_port *ap, u64 qc_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:5372
Inline: False
```
**Symbols:**

```
ffffffff8173a064-ffffffff8173a088: ata_qc_complete_multiple.cold (STB_LOCAL)
ffffffff81735660-ffffffff81735731: ata_qc_complete_multiple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ata_qc_complete_multiple(struct ata_port *ap, u64 qc_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:5372
Inline: False
```
**Symbols:**

```
ffffffff81789f34-ffffffff81789f58: ata_qc_complete_multiple.cold (STB_LOCAL)
ffffffff81785500-ffffffff817855d1: ata_qc_complete_multiple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ata_qc_complete_multiple(struct ata_port *ap, u64 qc_active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:5372
Inline: False
```
**Symbols:**

```
ffffffff817a3d84-ffffffff817a3da8: ata_qc_complete_multiple.cold (STB_LOCAL)
ffffffff8179f330-ffffffff8179f401: ata_qc_complete_multiple (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32 qc_active</code> ➡️ <code>u64 qc_active</code>
</li>
</ul>
</details>
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
