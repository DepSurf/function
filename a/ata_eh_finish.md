# Function: <code>ata_eh_finish</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ata_eh_finish(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff815d9b70)
Location: drivers/ata/libata-eh.c:3961
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-pmp.c:sata_pmp_error_handler
```
**Symbols:**

```
ffffffff815d9b70-ffffffff815d9c52: ata_eh_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ata_eh_finish(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81633710)
Location: drivers/ata/libata-eh.c:4052
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_error_handler
```
**Symbols:**

```
ffffffff81633710-ffffffff816337f2: ata_eh_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ata_eh_finish(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81664860)
Location: drivers/ata/libata-eh.c:4052
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_error_handler
```
**Symbols:**

```
ffffffff81664860-ffffffff81664942: ata_eh_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ata_eh_finish(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff816790a0)
Location: drivers/ata/libata-eh.c:4007
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_error_handler
```
**Symbols:**

```
ffffffff816790a0-ffffffff8167917f: ata_eh_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ata_eh_finish(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff816e26f0)
Location: drivers/ata/libata-eh.c:4007
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_error_handler
```
**Symbols:**

```
ffffffff816e26f0-ffffffff816e27cf: ata_eh_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ata_eh_finish(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8171ef60)
Location: drivers/ata/libata-eh.c:3985
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_error_handler
```
**Symbols:**

```
ffffffff8171ef60-ffffffff8171f03f: ata_eh_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ata_eh_finish(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81741850)
Location: drivers/ata/libata-eh.c:3981
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_error_handler
```
**Symbols:**

```
ffffffff81741850-ffffffff8174192f: ata_eh_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ata_eh_finish(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (0)
Location: drivers/ata/libata-eh.c:3966
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_error_handler
```
**Symbols:**

```
ffffffff8177def0-ffffffff8177df03: ata_eh_finish.cold (STB_LOCAL)
ffffffff8177d3d0-ffffffff8177d4af: ata_eh_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ata_eh_finish(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff817a11e0)
Location: drivers/ata/libata-eh.c:3966
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_error_handler
```
**Symbols:**

```
ffffffff817a11e0-ffffffff817a12bf: ata_eh_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ata_eh_finish(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81865280)
Location: drivers/ata/libata-eh.c:3769
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_error_handler
```
**Symbols:**

```
ffffffff81865280-ffffffff8186535f: ata_eh_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ata_eh_finish(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81874080)
Location: drivers/ata/libata-eh.c:3769
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_error_handler
```
**Symbols:**

```
ffffffff81874080-ffffffff8187415f: ata_eh_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ata_eh_finish(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81856770)
Location: drivers/ata/libata-eh.c:3770
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_error_handler
```
**Symbols:**

```
ffffffff81856770-ffffffff8185684f: ata_eh_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ata_eh_finish(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff818e4fb0)
Location: drivers/ata/libata-eh.c:3777
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_error_handler
```
**Symbols:**

```
ffffffff818e4fb0-ffffffff818e50a7: ata_eh_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ata_eh_finish(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81a362b0)
Location: drivers/ata/libata-eh.c:3776
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_error_handler
```
**Symbols:**

```
ffffffff81a362b0-ffffffff81a363b5: ata_eh_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ata_eh_finish(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81bbaf40)
Location: drivers/ata/libata-eh.c:3798
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_error_handler
```
**Symbols:**

```
ffffffff81bbaf40-ffffffff81bbb045: ata_eh_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ata_eh_finish(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c12760)
Location: drivers/ata/libata-eh.c:3908
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_error_handler
```
**Symbols:**

```
ffffffff81c12760-ffffffff81c12865: ata_eh_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ata_eh_finish(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c679d0)
Location: drivers/ata/libata-eh.c:3918
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_error_handler
```
**Symbols:**

```
ffffffff81c679d0-ffffffff81c67ad5: ata_eh_finish (STB_GLOBAL)
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
void ata_eh_finish(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffff8000109ac910)
Location: drivers/ata/libata-eh.c:3966
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_error_handler
```
**Symbols:**

```
ffff8000109ac910-ffff8000109ac9dc: ata_eh_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ata_eh_finish(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (c0a7c58c)
Location: drivers/ata/libata-eh.c:3966
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_error_handler
```
**Symbols:**

```
c0a7c58c-c0a7c678: ata_eh_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ata_eh_finish(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (c000000000a73c90)
Location: drivers/ata/libata-eh.c:3966
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_error_handler
```
**Symbols:**

```
c000000000a73c90-c000000000a73d90: ata_eh_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ata_eh_finish(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffe00060a0cc)
Location: drivers/ata/libata-eh.c:3966
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_error_handler
```
**Symbols:**

```
ffffffe00060a0cc-ffffffe00060a18a: ata_eh_finish (STB_GLOBAL)
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
void ata_eh_finish(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff817662b0)
Location: drivers/ata/libata-eh.c:3966
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_error_handler
```
**Symbols:**

```
ffffffff817662b0-ffffffff8176638f: ata_eh_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ata_eh_finish(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81746110)
Location: drivers/ata/libata-eh.c:3966
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_error_handler
```
**Symbols:**

```
ffffffff81746110-ffffffff817461ef: ata_eh_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ata_eh_finish(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81796060)
Location: drivers/ata/libata-eh.c:3966
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_error_handler
```
**Symbols:**

```
ffffffff81796060-ffffffff8179613f: ata_eh_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ata_eh_finish(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff817afed0)
Location: drivers/ata/libata-eh.c:3966
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_error_handler
```
**Symbols:**

```
ffffffff817afed0-ffffffff817affaf: ata_eh_finish (STB_GLOBAL)
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
