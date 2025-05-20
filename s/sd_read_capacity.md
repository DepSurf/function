# Function: <code>sd_read_capacity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff815bdde6)
Location: drivers/scsi/sd.c:2229
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81616d55)
Location: drivers/scsi/sd.c:2240
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8164682b)
Location: drivers/scsi/sd.c:2296
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8165b3ab)
Location: drivers/scsi/sd.c:2446
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff816c4a25)
Location: drivers/scsi/sd.c:2484
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81700f60)
Location: drivers/scsi/sd.c:2455
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81723dde)
Location: drivers/scsi/sd.c:2442
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sd_read_capacity(struct scsi_disk *sdkp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8175da50)
Location: drivers/scsi/sd.c:2429
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff8175da50-ffffffff8175dde7: sd_read_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sd_read_capacity(struct scsi_disk *sdkp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81781920)
Location: drivers/scsi/sd.c:2439
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff81781920-ffffffff81781cab: sd_read_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sd_read_capacity(struct scsi_disk *sdkp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81847520)
Location: drivers/scsi/sd.c:2459
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff81847520-ffffffff818478a2: sd_read_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sd_read_capacity(struct scsi_disk *sdkp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81856f30)
Location: drivers/scsi/sd.c:2503
Inline: False
```
**Symbols:**

```
ffffffff81856f30-ffffffff818572b2: sd_read_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sd_read_capacity(struct scsi_disk *sdkp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81839ca0)
Location: drivers/scsi/sd.c:2518
Inline: False
```
**Symbols:**

```
ffffffff81839ca0-ffffffff8183a022: sd_read_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sd_read_capacity(struct scsi_disk *sdkp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff818c6320)
Location: drivers/scsi/sd.c:2481
Inline: False
```
**Symbols:**

```
ffffffff818c6320-ffffffff818c66a2: sd_read_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sd_read_capacity(struct scsi_disk *sdkp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81a12e50)
Location: drivers/scsi/sd.c:2421
Inline: False
```
**Symbols:**

```
ffffffff81a12e50-ffffffff81a131b2: sd_read_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sd_read_capacity(struct scsi_disk *sdkp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81b931f0)
Location: drivers/scsi/sd.c:2462
Inline: False
```
**Symbols:**

```
ffffffff81b931f0-ffffffff81b93533: sd_read_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sd_read_capacity(struct scsi_disk *sdkp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81be9710)
Location: drivers/scsi/sd.c:2576
Inline: False
```
**Symbols:**

```
ffffffff81be9710-ffffffff81be9a6f: sd_read_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sd_read_capacity(struct scsi_disk *sdkp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81c3ec70)
Location: drivers/scsi/sd.c:2626
Inline: False
```
**Symbols:**

```
ffffffff81c3ec70-ffffffff81c3efcf: sd_read_capacity (STB_LOCAL)
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
void sd_read_capacity(struct scsi_disk *sdkp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffff800010988688)
Location: drivers/scsi/sd.c:2439
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffff800010988688-ffff8000109889a8: sd_read_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sd_read_capacity(struct scsi_disk *sdkp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (c0a5a6c4)
Location: drivers/scsi/sd.c:2439
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
c0a5a6c4-c0a5a9c4: sd_read_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sd_read_capacity(struct scsi_disk *sdkp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (c000000000a482c0)
Location: drivers/scsi/sd.c:2439
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
c000000000a482c0-c000000000a486f8: sd_read_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sd_read_capacity(struct scsi_disk *sdkp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffe0005ec726)
Location: drivers/scsi/sd.c:2439
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffe0005ec726-ffffffe0005eca04: sd_read_capacity (STB_LOCAL)
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
void sd_read_capacity(struct scsi_disk *sdkp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81736010)
Location: drivers/scsi/sd.c:2439
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff81736010-ffffffff8173639b: sd_read_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sd_read_capacity(struct scsi_disk *sdkp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81717cb0)
Location: drivers/scsi/sd.c:2439
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff81717cb0-ffffffff8171803b: sd_read_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sd_read_capacity(struct scsi_disk *sdkp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff817767a0)
Location: drivers/scsi/sd.c:2439
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff817767a0-ffffffff81776b2b: sd_read_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sd_read_capacity(struct scsi_disk *sdkp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81790580)
Location: drivers/scsi/sd.c:2439
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff81790580-ffffffff8179090b: sd_read_capacity (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
