# Function: <code>scsi_add_host_with_dma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_add_host_with_dma(struct Scsi_Host *shost, struct device *dev, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff815a7fd0)
Location: drivers/scsi/hosts.c:201
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff815a7fd0-ffffffff815a82c8: scsi_add_host_with_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_add_host_with_dma(struct Scsi_Host *shost, struct device *dev, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff815ffe50)
Location: drivers/scsi/hosts.c:201
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff815ffe50-ffffffff81600157: scsi_add_host_with_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_add_host_with_dma(struct Scsi_Host *shost, struct device *dev, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8162f4b0)
Location: drivers/scsi/hosts.c:201
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff8162f4b0-ffffffff8162f831: scsi_add_host_with_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int scsi_add_host_with_dma(struct Scsi_Host *shost, struct device *dev, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81644570)
Location: drivers/scsi/hosts.c:201
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff81644570-ffffffff816448d4: scsi_add_host_with_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scsi_add_host_with_dma(struct Scsi_Host *shost, struct device *dev, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff816ad500)
Location: drivers/scsi/hosts.c:201
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff816ad500-ffffffff816ad867: scsi_add_host_with_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int scsi_add_host_with_dma(struct Scsi_Host *shost, struct device *dev, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff816e9df0)
Location: drivers/scsi/hosts.c:206
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff816e9df0-ffffffff816ea12d: scsi_add_host_with_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int scsi_add_host_with_dma(struct Scsi_Host *shost, struct device *dev, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8170d8d0)
Location: drivers/scsi/hosts.c:206
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff8170d8d0-ffffffff8170dbd6: scsi_add_host_with_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int scsi_add_host_with_dma(struct Scsi_Host *shost, struct device *dev, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (0)
Location: drivers/scsi/hosts.c:207
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff8174915c-ffffffff817493df: scsi_add_host_with_dma.cold (STB_LOCAL)
ffffffff81748fc0-ffffffff81749029: scsi_add_host_with_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int scsi_add_host_with_dma(struct Scsi_Host *shost, struct device *dev, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (0)
Location: drivers/scsi/hosts.c:207
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff8176d2ac-ffffffff8176d52f: scsi_add_host_with_dma.cold (STB_LOCAL)
ffffffff8176d110-ffffffff8176d179: scsi_add_host_with_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int scsi_add_host_with_dma(struct Scsi_Host *shost, struct device *dev, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (0)
Location: drivers/scsi/hosts.c:208
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff8182f876-ffffffff8182faf9: scsi_add_host_with_dma.cold (STB_LOCAL)
ffffffff8182f6d0-ffffffff8182f739: scsi_add_host_with_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int scsi_add_host_with_dma(struct Scsi_Host *shost, struct device *dev, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (0)
Location: drivers/scsi/hosts.c:208
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff81c16388-ffffffff81c1660b: scsi_add_host_with_dma.cold (STB_LOCAL)
ffffffff81840700-ffffffff81840769: scsi_add_host_with_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int scsi_add_host_with_dma(struct Scsi_Host *shost, struct device *dev, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (0)
Location: drivers/scsi/hosts.c:208
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff81c0807a-ffffffff81c082e4: scsi_add_host_with_dma.cold (STB_LOCAL)
ffffffff81823940-ffffffff818239aa: scsi_add_host_with_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int scsi_add_host_with_dma(struct Scsi_Host *shost, struct device *dev, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (0)
Location: drivers/scsi/hosts.c:208
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff81d0beff-ffffffff81d0c168: scsi_add_host_with_dma.cold (STB_LOCAL)
ffffffff818ae270-ffffffff818ae2da: scsi_add_host_with_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int scsi_add_host_with_dma(struct Scsi_Host *shost, struct device *dev, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (0)
Location: drivers/scsi/hosts.c:209
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff81ed4e3e-ffffffff81ed5097: scsi_add_host_with_dma.cold (STB_LOCAL)
ffffffff819f9130-ffffffff819f9197: scsi_add_host_with_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scsi_add_host_with_dma(struct Scsi_Host *shost, struct device *dev, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81b76d70)
Location: drivers/scsi/hosts.c:218
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff81b76d70-ffffffff81b770eb: scsi_add_host_with_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scsi_add_host_with_dma(struct Scsi_Host *shost, struct device *dev, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81bcaa00)
Location: drivers/scsi/hosts.c:219
Inline: False
Direct callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff81bcaa00-ffffffff81bcad7b: scsi_add_host_with_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scsi_add_host_with_dma(struct Scsi_Host *shost, struct device *dev, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81c1f630)
Location: drivers/scsi/hosts.c:219
Inline: False
Direct callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff81c1f630-ffffffff81c1f9ab: scsi_add_host_with_dma (STB_GLOBAL)
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
int scsi_add_host_with_dma(struct Scsi_Host *shost, struct device *dev, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffff80001096f8f0)
Location: drivers/scsi/hosts.c:207
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffff80001096f8f0-ffff80001096fbc4: scsi_add_host_with_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_add_host_with_dma(struct Scsi_Host *shost, struct device *dev, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (c0a44b64)
Location: drivers/scsi/hosts.c:207
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
c0a44b64-c0a44e20: scsi_add_host_with_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsi_add_host_with_dma(struct Scsi_Host *shost, struct device *dev, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (c000000000a28f40)
Location: drivers/scsi/hosts.c:207
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
c000000000a28f40-c000000000a292ac: scsi_add_host_with_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsi_add_host_with_dma(struct Scsi_Host *shost, struct device *dev, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffe0005d98ea)
Location: drivers/scsi/hosts.c:207
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffe0005d98ea-ffffffe0005d9b5e: scsi_add_host_with_dma (STB_GLOBAL)
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
int scsi_add_host_with_dma(struct Scsi_Host *shost, struct device *dev, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (0)
Location: drivers/scsi/hosts.c:207
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff8172199c-ffffffff81721c1f: scsi_add_host_with_dma.cold (STB_LOCAL)
ffffffff81721800-ffffffff81721869: scsi_add_host_with_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int scsi_add_host_with_dma(struct Scsi_Host *shost, struct device *dev, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (0)
Location: drivers/scsi/hosts.c:207
Inline: False
Direct callers:
  - drivers/scsi/storvsc_drv.c:storvsc_probe
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff816fadcc-ffffffff816fb04f: scsi_add_host_with_dma.cold (STB_LOCAL)
ffffffff816fac30-ffffffff816fac99: scsi_add_host_with_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int scsi_add_host_with_dma(struct Scsi_Host *shost, struct device *dev, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (0)
Location: drivers/scsi/hosts.c:207
Inline: False
Direct callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff8176076c-ffffffff817609ef: scsi_add_host_with_dma.cold (STB_LOCAL)
ffffffff817605d0-ffffffff81760639: scsi_add_host_with_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int scsi_add_host_with_dma(struct Scsi_Host *shost, struct device *dev, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (0)
Location: drivers/scsi/hosts.c:207
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff8177bdcc-ffffffff8177c04f: scsi_add_host_with_dma.cold (STB_LOCAL)
ffffffff8177bc30-ffffffff8177bc99: scsi_add_host_with_dma (STB_GLOBAL)
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
