# Function: <code>ata_bmdma_port_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ata_bmdma_port_start(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff815dd4a0)
Location: drivers/ata/libata-sff.c:3111
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
  - drivers/ata/ata_piix.c:piix_port_start
```
**Symbols:**

```
ffffffff815dd4a0-ffffffff815dd4fa: ata_bmdma_port_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ata_bmdma_port_start(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff81637220)
Location: drivers/ata/libata-sff.c:3112
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
  - drivers/ata/ata_piix.c:piix_port_start
```
**Symbols:**

```
ffffffff81637220-ffffffff8163727d: ata_bmdma_port_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ata_bmdma_port_start(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff816682c0)
Location: drivers/ata/libata-sff.c:3112
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
  - drivers/ata/ata_piix.c:piix_port_start
```
**Symbols:**

```
ffffffff816682c0-ffffffff8166831d: ata_bmdma_port_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ata_bmdma_port_start(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff8167cdc5)
Location: drivers/ata/libata-sff.c:3094
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
Direct callers:
  - drivers/ata/ata_piix.c:piix_port_start
```
**Symbols:**

```
ffffffff8167d230-ffffffff8167d28d: ata_bmdma_port_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ata_bmdma_port_start(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff816e64e5)
Location: drivers/ata/libata-sff.c:3094
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
Direct callers:
  - drivers/ata/ata_piix.c:piix_port_start
```
**Symbols:**

```
ffffffff816e69b0-ffffffff816e6a0d: ata_bmdma_port_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ata_bmdma_port_start(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff81722dd2)
Location: drivers/ata/libata-sff.c:3094
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
Direct callers:
  - drivers/ata/ata_piix.c:piix_port_start
```
**Symbols:**

```
ffffffff81723280-ffffffff817232dd: ata_bmdma_port_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ata_bmdma_port_start(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff81745a42)
Location: drivers/ata/libata-sff.c:3064
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
Direct callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
  - drivers/ata/ata_piix.c:piix_port_start
```
**Symbols:**

```
ffffffff817459b0-ffffffff817459f4: ata_bmdma_port_start.part.19 (STB_LOCAL)
ffffffff81745a00-ffffffff81745a27: ata_bmdma_port_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ata_bmdma_port_start(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff81781712)
Location: drivers/ata/libata-sff.c:3054
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
Direct callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
  - drivers/ata/ata_piix.c:piix_port_start
```
**Symbols:**

```
ffffffff81781680-ffffffff817816c4: ata_bmdma_port_start.part.0 (STB_LOCAL)
ffffffff817816d0-ffffffff817816f7: ata_bmdma_port_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ata_bmdma_port_start(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff817a50d2)
Location: drivers/ata/libata-sff.c:3054
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
Direct callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
  - drivers/ata/ata_piix.c:piix_port_start
```
**Symbols:**

```
ffffffff817a5040-ffffffff817a5084: ata_bmdma_port_start.part.0 (STB_LOCAL)
ffffffff817a5090-ffffffff817a50b7: ata_bmdma_port_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ata_bmdma_port_start(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff8186a4aa)
Location: drivers/ata/libata-sff.c:3054
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
Direct callers:
  - drivers/ata/ata_piix.c:piix_port_start
```
**Symbols:**

```
ffffffff8186a050-ffffffff8186a0b0: ata_bmdma_port_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ata_bmdma_port_start(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff818792ba)
Location: drivers/ata/libata-sff.c:3054
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
Direct callers:
  - drivers/ata/ata_piix.c:piix_port_start
```
**Symbols:**

```
ffffffff81878e60-ffffffff81878ec0: ata_bmdma_port_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ata_bmdma_port_start(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff8185ba1a)
Location: drivers/ata/libata-sff.c:3073
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
Direct callers:
  - drivers/ata/ata_piix.c:piix_port_start
```
**Symbols:**

```
ffffffff8185b4d0-ffffffff8185b530: ata_bmdma_port_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ata_bmdma_port_start(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff818ea3aa)
Location: drivers/ata/libata-sff.c:3073
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
Direct callers:
  - drivers/ata/ata_piix.c:piix_port_start
```
**Symbols:**

```
ffffffff818e9f50-ffffffff818e9fb0: ata_bmdma_port_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ata_bmdma_port_start(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff81a3be8a)
Location: drivers/ata/libata-sff.c:3057
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
Direct callers:
  - drivers/ata/ata_piix.c:piix_port_start
```
**Symbols:**

```
ffffffff81a3b6b0-ffffffff81a3b71f: ata_bmdma_port_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ata_bmdma_port_start(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff81bc12ea)
Location: drivers/ata/libata-sff.c:3001
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
Direct callers:
  - drivers/ata/ata_piix.c:piix_port_start
```
**Symbols:**

```
ffffffff81bc0b40-ffffffff81bc0baf: ata_bmdma_port_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ata_bmdma_port_start(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff81c18dca)
Location: drivers/ata/libata-sff.c:2997
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
Direct callers:
  - drivers/ata/ata_piix.c:piix_port_start
```
**Symbols:**

```
ffffffff81c18620-ffffffff81c1868f: ata_bmdma_port_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ata_bmdma_port_start(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff81c6ddda)
Location: drivers/ata/libata-sff.c:2987
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
Direct callers:
  - drivers/ata/ata_piix.c:piix_port_start
```
**Symbols:**

```
ffffffff81c6d370-ffffffff81c6d3df: ata_bmdma_port_start (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ata_bmdma_port_start(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-sff.c (ffff8000109b0298)
Location: drivers/ata/libata-sff.c:3054
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
Direct callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
```
**Symbols:**

```
ffff8000109b01e0-ffff8000109b0230: ata_bmdma_port_start.part.0 (STB_LOCAL)
ffff8000109b0230-ffff8000109b026c: ata_bmdma_port_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ata_bmdma_port_start(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-sff.c (c0a8038c)
Location: drivers/ata/libata-sff.c:3054
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
Direct callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
```
**Symbols:**

```
c0a802d0-c0a80328: ata_bmdma_port_start.part.0 (STB_LOCAL)
c0a80328-c0a80364: ata_bmdma_port_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ata_bmdma_port_start(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-sff.c (c000000000a795c4)
Location: drivers/ata/libata-sff.c:3054
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
Direct callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
```
**Symbols:**

```
c000000000a794f0-c000000000a7955c: ata_bmdma_port_start.part.0 (STB_LOCAL)
c000000000a79560-c000000000a79598: ata_bmdma_port_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ata_bmdma_port_start(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffe00060df58)
Location: drivers/ata/libata-sff.c:3054
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
Direct callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
```
**Symbols:**

```
ffffffe00060deb6-ffffffe00060df04: ata_bmdma_port_start.part.0 (STB_LOCAL)
ffffffe00060df04-ffffffe00060df3c: ata_bmdma_port_start (STB_GLOBAL)
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
int ata_bmdma_port_start(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff8176a192)
Location: drivers/ata/libata-sff.c:3054
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
Direct callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
  - drivers/ata/ata_piix.c:piix_port_start
```
**Symbols:**

```
ffffffff8176a100-ffffffff8176a144: ata_bmdma_port_start.part.0 (STB_LOCAL)
ffffffff8176a150-ffffffff8176a177: ata_bmdma_port_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ata_bmdma_port_start(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff81749ff2)
Location: drivers/ata/libata-sff.c:3054
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
Direct callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
  - drivers/ata/ata_piix.c:piix_port_start
```
**Symbols:**

```
ffffffff81749f60-ffffffff81749fa4: ata_bmdma_port_start.part.0 (STB_LOCAL)
ffffffff81749fb0-ffffffff81749fd7: ata_bmdma_port_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ata_bmdma_port_start(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff81799f52)
Location: drivers/ata/libata-sff.c:3054
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
Direct callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
  - drivers/ata/ata_piix.c:piix_port_start
```
**Symbols:**

```
ffffffff81799ec0-ffffffff81799f04: ata_bmdma_port_start.part.0 (STB_LOCAL)
ffffffff81799f10-ffffffff81799f37: ata_bmdma_port_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ata_bmdma_port_start(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff817b3dd2)
Location: drivers/ata/libata-sff.c:3054
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
Direct callers:
  - drivers/ata/libata-sff.c:ata_bmdma_port_start32
  - drivers/ata/ata_piix.c:piix_port_start
```
**Symbols:**

```
ffffffff817b3d40-ffffffff817b3d84: ata_bmdma_port_start.part.0 (STB_LOCAL)
ffffffff817b3d90-ffffffff817b3db7: ata_bmdma_port_start (STB_GLOBAL)
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
