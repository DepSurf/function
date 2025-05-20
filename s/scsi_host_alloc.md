# Function: <code>scsi_host_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct Scsi_Host *scsi_host_alloc(struct scsi_host_template *sht, int privsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff815a85b0)
Location: drivers/scsi/hosts.c:387
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_register
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff815a85b0-ffffffff815a8a2e: scsi_host_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct Scsi_Host *scsi_host_alloc(struct scsi_host_template *sht, int privsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81600460)
Location: drivers/scsi/hosts.c:396
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_register
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff81600460-ffffffff816008cb: scsi_host_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct Scsi_Host *scsi_host_alloc(struct scsi_host_template *sht, int privsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8162fb40)
Location: drivers/scsi/hosts.c:400
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_register
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff8162fb40-ffffffff8162ffab: scsi_host_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct Scsi_Host *scsi_host_alloc(struct scsi_host_template *sht, int privsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff816448e0)
Location: drivers/scsi/hosts.c:388
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_register
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff816448e0-ffffffff81644d30: scsi_host_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct Scsi_Host *scsi_host_alloc(struct scsi_host_template *sht, int privsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff816ad870)
Location: drivers/scsi/hosts.c:383
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_register
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff816ad870-ffffffff816adcc0: scsi_host_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct Scsi_Host *scsi_host_alloc(struct scsi_host_template *sht, int privsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff816e97c0)
Location: drivers/scsi/hosts.c:382
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff816e97c0-ffffffff816e9bf1: scsi_host_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct Scsi_Host *scsi_host_alloc(struct scsi_host_template *sht, int privsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8170d2c0)
Location: drivers/scsi/hosts.c:367
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff8170d2c0-ffffffff8170d6ce: scsi_host_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct Scsi_Host *scsi_host_alloc(struct scsi_host_template *sht, int privsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (0)
Location: drivers/scsi/hosts.c:368
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff81749073-ffffffff817490f9: scsi_host_alloc.cold (STB_LOCAL)
ffffffff81748770-ffffffff81748b71: scsi_host_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct Scsi_Host *scsi_host_alloc(struct scsi_host_template *sht, int privsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (0)
Location: drivers/scsi/hosts.c:368
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff8176d1c3-ffffffff8176d249: scsi_host_alloc.cold (STB_LOCAL)
ffffffff8176c8c0-ffffffff8176ccc1: scsi_host_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct Scsi_Host *scsi_host_alloc(struct scsi_host_template *sht, int privsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (0)
Location: drivers/scsi/hosts.c:369
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff8182f7e6-ffffffff8182f876: scsi_host_alloc.cold (STB_LOCAL)
ffffffff8182f0e0-ffffffff8182f4bb: scsi_host_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct Scsi_Host *scsi_host_alloc(struct scsi_host_template *sht, int privsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (0)
Location: drivers/scsi/hosts.c:371
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff81c162f8-ffffffff81c16388: scsi_host_alloc.cold (STB_LOCAL)
ffffffff81840100-ffffffff818404e5: scsi_host_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct Scsi_Host *scsi_host_alloc(struct scsi_host_template *sht, int privsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (0)
Location: drivers/scsi/hosts.c:376
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff81c07ffe-ffffffff81c0807a: scsi_host_alloc.cold (STB_LOCAL)
ffffffff81823370-ffffffff81823721: scsi_host_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct Scsi_Host *scsi_host_alloc(struct scsi_host_template *sht, int privsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (0)
Location: drivers/scsi/hosts.c:377
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff81d0be7d-ffffffff81d0beff: scsi_host_alloc.cold (STB_LOCAL)
ffffffff818adc90-ffffffff818ae053: scsi_host_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct Scsi_Host *scsi_host_alloc(struct scsi_host_template *sht, int privsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (0)
Location: drivers/scsi/hosts.c:378
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff81ed4dc1-ffffffff81ed4e3e: scsi_host_alloc.cold (STB_LOCAL)
ffffffff819f8b60-ffffffff819f8f09: scsi_host_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct Scsi_Host *scsi_host_alloc(struct scsi_host_template *sht, int privsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81b76680)
Location: drivers/scsi/hosts.c:393
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff81b76680-ffffffff81b76ad3: scsi_host_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct Scsi_Host *scsi_host_alloc(const struct scsi_host_template *sht, int privsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81bca300)
Location: drivers/scsi/hosts.c:392
Inline: False
Direct callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff81bca300-ffffffff81bca75d: scsi_host_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct Scsi_Host *scsi_host_alloc(const struct scsi_host_template *sht, int privsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81c1ef30)
Location: drivers/scsi/hosts.c:392
Inline: False
Direct callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff81c1ef30-ffffffff81c1f38d: scsi_host_alloc (STB_GLOBAL)
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
struct Scsi_Host *scsi_host_alloc(struct scsi_host_template *sht, int privsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffff80001096f268)
Location: drivers/scsi/hosts.c:368
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffff80001096f268-ffff80001096f5e4: scsi_host_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct Scsi_Host *scsi_host_alloc(struct scsi_host_template *sht, int privsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (c0a445a4)
Location: drivers/scsi/hosts.c:368
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
c0a445a4-c0a44938: scsi_host_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct Scsi_Host *scsi_host_alloc(struct scsi_host_template *sht, int privsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (c000000000a28400)
Location: drivers/scsi/hosts.c:368
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
c000000000a28400-c000000000a28874: scsi_host_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct Scsi_Host *scsi_host_alloc(struct scsi_host_template *sht, int privsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffe0005d9382)
Location: drivers/scsi/hosts.c:368
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffe0005d9382-ffffffe0005d96ec: scsi_host_alloc (STB_GLOBAL)
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
struct Scsi_Host *scsi_host_alloc(struct scsi_host_template *sht, int privsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (0)
Location: drivers/scsi/hosts.c:368
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff817218b3-ffffffff81721939: scsi_host_alloc.cold (STB_LOCAL)
ffffffff81720fb0-ffffffff817213b1: scsi_host_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct Scsi_Host *scsi_host_alloc(struct scsi_host_template *sht, int privsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (0)
Location: drivers/scsi/hosts.c:368
Inline: False
Direct callers:
  - drivers/scsi/storvsc_drv.c:storvsc_probe
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff816face3-ffffffff816fad69: scsi_host_alloc.cold (STB_LOCAL)
ffffffff816fa3e0-ffffffff816fa7e1: scsi_host_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct Scsi_Host *scsi_host_alloc(struct scsi_host_template *sht, int privsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (0)
Location: drivers/scsi/hosts.c:368
Inline: False
Direct callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff81760683-ffffffff81760709: scsi_host_alloc.cold (STB_LOCAL)
ffffffff8175fd80-ffffffff81760181: scsi_host_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct Scsi_Host *scsi_host_alloc(struct scsi_host_template *sht, int privsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (0)
Location: drivers/scsi/hosts.c:368
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff8177bce3-ffffffff8177bd69: scsi_host_alloc.cold (STB_LOCAL)
ffffffff8177b3e0-ffffffff8177b7e1: scsi_host_alloc (STB_GLOBAL)
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
