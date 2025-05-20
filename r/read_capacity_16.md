# Function: <code>read_capacity_16</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int read_capacity_16(struct scsi_disk *sdkp, struct scsi_device *sdp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff815bd5b0)
Location: drivers/scsi/sd.c:2048
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff815bd5b0-ffffffff815bda59: read_capacity_16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int read_capacity_16(struct scsi_disk *sdkp, struct scsi_device *sdp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81615f60)
Location: drivers/scsi/sd.c:2059
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff81615f60-ffffffff81616412: read_capacity_16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int read_capacity_16(struct scsi_disk *sdkp, struct scsi_device *sdp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81645d50)
Location: drivers/scsi/sd.c:2112
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff81645d50-ffffffff8164622c: read_capacity_16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8165b44c)
Location: drivers/scsi/sd.c:2262
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff8165a950-ffffffff8165adac: read_capacity_16.part.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (ffffffff816c4ac6)
Location: drivers/scsi/sd.c:2300
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff816c3b20-ffffffff816c3f7c: read_capacity_16.part.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81700fbf)
Location: drivers/scsi/sd.c:2271
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff816ffc80-ffffffff81700108: read_capacity_16.part.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81723e3d)
Location: drivers/scsi/sd.c:2258
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff817226f0-ffffffff81722b7c: read_capacity_16.part.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8175dbf1)
Location: drivers/scsi/sd.c:2261
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
Direct callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffff8175d5a0-ffffffff8175da47: read_capacity_16.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81781abf)
Location: drivers/scsi/sd.c:2271
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
Direct callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffff81781470-ffffffff8178191d: read_capacity_16.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (ffffffff818476f0)
Location: drivers/scsi/sd.c:2291
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
Direct callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffff818471b0-ffffffff81847517: read_capacity_16.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81857100)
Location: drivers/scsi/sd.c:2335
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
Direct callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffff81856bc0-ffffffff81856f24: read_capacity_16.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81839e70)
Location: drivers/scsi/sd.c:2350
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
Direct callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffff81839940-ffffffff81839c9c: read_capacity_16.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (ffffffff818c64f0)
Location: drivers/scsi/sd.c:2313
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
Direct callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffff818c5fc0-ffffffff818c6312: read_capacity_16.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int read_capacity_16(struct scsi_disk *sdkp, struct scsi_device *sdp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81a12a20)
Location: drivers/scsi/sd.c:2253
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffff81a12a20-ffffffff81a12e49: read_capacity_16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int read_capacity_16(struct scsi_disk *sdkp, struct scsi_device *sdp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81b92db0)
Location: drivers/scsi/sd.c:2294
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffff81b92db0-ffffffff81b931db: read_capacity_16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int read_capacity_16(struct scsi_disk *sdkp, struct scsi_device *sdp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81be92c0)
Location: drivers/scsi/sd.c:2402
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffff81be92c0-ffffffff81be96f7: read_capacity_16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int read_capacity_16(struct scsi_disk *sdkp, struct scsi_device *sdp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81c3e820)
Location: drivers/scsi/sd.c:2453
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffff81c3e820-ffffffff81c3ec57: read_capacity_16 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (ffff80001098873c)
Location: drivers/scsi/sd.c:2271
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
Direct callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffff800010988248-ffff800010988684: read_capacity_16.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (c0a5a790)
Location: drivers/scsi/sd.c:2271
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
Direct callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
c0a5a27c-c0a5a6c4: read_capacity_16.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (c000000000a484e0)
Location: drivers/scsi/sd.c:2271
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
Direct callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
c000000000a47d70-c000000000a482bc: read_capacity_16.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (ffffffe0005ec8b0)
Location: drivers/scsi/sd.c:2271
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
Direct callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffe0005ec344-ffffffe0005ec726: read_capacity_16.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (ffffffff817361af)
Location: drivers/scsi/sd.c:2271
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
Direct callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffff81735b60-ffffffff8173600d: read_capacity_16.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81717e4f)
Location: drivers/scsi/sd.c:2271
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
Direct callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffff81717800-ffffffff81717cad: read_capacity_16.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8177693f)
Location: drivers/scsi/sd.c:2271
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
Direct callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffff817762f0-ffffffff8177679d: read_capacity_16.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8179071f)
Location: drivers/scsi/sd.c:2271
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
Direct callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffff817900d0-ffffffff8179057d: read_capacity_16.part.0 (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
