# Function: <code>scsi_internal_device_block_nowait</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int scsi_internal_device_block_nowait(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8164a740)
Location: drivers/scsi/scsi_lib.c:2972
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_block
```
**Symbols:**

```
ffffffff8164a740-ffffffff8164a7c6: scsi_internal_device_block_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scsi_internal_device_block_nowait(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b3ab0)
Location: drivers/scsi/scsi_lib.c:3072
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_block
```
**Symbols:**

```
ffffffff816b3ab0-ffffffff816b3b36: scsi_internal_device_block_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int scsi_internal_device_block_nowait(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816efb80)
Location: drivers/scsi/scsi_lib.c:3088
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_block
```
**Symbols:**

```
ffffffff816efb80-ffffffff816efc06: scsi_internal_device_block_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int scsi_internal_device_block_nowait(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81713320)
Location: drivers/scsi/scsi_lib.c:2651
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_block
```
**Symbols:**

```
ffffffff81713320-ffffffff81713361: scsi_internal_device_block_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int scsi_internal_device_block_nowait(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8174ec00)
Location: drivers/scsi/scsi_lib.c:2604
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_block
```
**Symbols:**

```
ffffffff8174ec00-ffffffff8174ec43: scsi_internal_device_block_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int scsi_internal_device_block_nowait(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81772db0)
Location: drivers/scsi/scsi_lib.c:2651
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_block
```
**Symbols:**

```
ffffffff81772db0-ffffffff81772df3: scsi_internal_device_block_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int scsi_internal_device_block_nowait(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8183629d)
Location: drivers/scsi/scsi_lib.c:2634
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:device_block
```
**Symbols:**

```
ffffffff81835280-ffffffff818352c3: scsi_internal_device_block_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int scsi_internal_device_block_nowait(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81846d7d)
Location: drivers/scsi/scsi_lib.c:2640
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:device_block
```
**Symbols:**

```
ffffffff81845bb0-ffffffff81845bf3: scsi_internal_device_block_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int scsi_internal_device_block_nowait(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81829e5d)
Location: drivers/scsi/scsi_lib.c:2657
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:device_block
```
**Symbols:**

```
ffffffff81828e40-ffffffff81828e83: scsi_internal_device_block_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int scsi_internal_device_block_nowait(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b5d0d)
Location: drivers/scsi/scsi_lib.c:2650
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
  - drivers/scsi/scsi_lib.c:device_block
```
**Symbols:**

```
ffffffff818b4820-ffffffff818b4863: scsi_internal_device_block_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int scsi_internal_device_block_nowait(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81a005f3)
Location: drivers/scsi/scsi_lib.c:2750
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
```
**Symbols:**

```
ffffffff81a006a0-ffffffff81a0070c: scsi_internal_device_block_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int scsi_internal_device_block_nowait(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b7ecaf)
Location: drivers/scsi/scsi_lib.c:2755
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
```
**Symbols:**

```
ffffffff81b7ebe0-ffffffff81b7ec37: scsi_internal_device_block_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int scsi_internal_device_block_nowait(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd2929)
Location: drivers/scsi/scsi_lib.c:2763
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
```
**Symbols:**

```
ffffffff81bd2c50-ffffffff81bd2cbe: scsi_internal_device_block_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int scsi_internal_device_block_nowait(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c27599)
Location: drivers/scsi/scsi_lib.c:2760
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_host_block
```
**Symbols:**

```
ffffffff81c278c0-ffffffff81c2792e: scsi_internal_device_block_nowait (STB_GLOBAL)
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
int scsi_internal_device_block_nowait(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffff800010976300)
Location: drivers/scsi/scsi_lib.c:2651
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_block
```
**Symbols:**

```
ffff800010976300-ffff800010976354: scsi_internal_device_block_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_internal_device_block_nowait(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c0a4ac9c)
Location: drivers/scsi/scsi_lib.c:2651
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_block
```
**Symbols:**

```
c0a4ac9c-c0a4acec: scsi_internal_device_block_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsi_internal_device_block_nowait(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c000000000a309f0)
Location: drivers/scsi/scsi_lib.c:2651
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_block
```
**Symbols:**

```
c000000000a309f0-c000000000a30a68: scsi_internal_device_block_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsi_internal_device_block_nowait(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffe0005dea0e)
Location: drivers/scsi/scsi_lib.c:2651
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_block
```
**Symbols:**

```
ffffffe0005dea0e-ffffffe0005dea5e: scsi_internal_device_block_nowait (STB_GLOBAL)
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
int scsi_internal_device_block_nowait(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817274a0)
Location: drivers/scsi/scsi_lib.c:2651
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_block
```
**Symbols:**

```
ffffffff817274a0-ffffffff817274e3: scsi_internal_device_block_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int scsi_internal_device_block_nowait(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817008d0)
Location: drivers/scsi/scsi_lib.c:2651
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_block
```
**Symbols:**

```
ffffffff817008d0-ffffffff81700913: scsi_internal_device_block_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int scsi_internal_device_block_nowait(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81766270)
Location: drivers/scsi/scsi_lib.c:2651
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_block
```
**Symbols:**

```
ffffffff81766270-ffffffff817662b3: scsi_internal_device_block_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int scsi_internal_device_block_nowait(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81781920)
Location: drivers/scsi/scsi_lib.c:2651
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_block
```
**Symbols:**

```
ffffffff81781920-ffffffff81781963: scsi_internal_device_block_nowait (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
