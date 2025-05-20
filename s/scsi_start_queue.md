# Function: <code>scsi_start_queue</code>

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
void scsi_start_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8164d930)
Location: drivers/scsi/scsi_lib.c:3040
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff8164d930-ffffffff8164d982: scsi_start_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_start_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b6c20)
Location: drivers/scsi/scsi_lib.c:3140
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff816b6c20-ffffffff816b6c72: scsi_start_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_start_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816f2f00)
Location: drivers/scsi/scsi_lib.c:3156
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff816f2f00-ffffffff816f2f52: scsi_start_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void scsi_start_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8171338f)
Location: drivers/scsi/scsi_lib.c:2707
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff81715dd0-ffffffff81715de4: scsi_start_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void scsi_start_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8174ec6f)
Location: drivers/scsi/scsi_lib.c:2656
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff81751580-ffffffff81751594: scsi_start_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void scsi_start_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81772e29)
Location: drivers/scsi/scsi_lib.c:2703
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff81775810-ffffffff81775824: scsi_start_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void scsi_start_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818352f9)
Location: drivers/scsi/scsi_lib.c:2686
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff81838730-ffffffff81838744: scsi_start_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void scsi_start_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81845c29)
Location: drivers/scsi/scsi_lib.c:2692
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff818490b0-ffffffff818490c4: scsi_start_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void scsi_start_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81828eb9)
Location: drivers/scsi/scsi_lib.c:2709
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff8182c4e0-ffffffff8182c4f4: scsi_start_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void scsi_start_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b4899)
Location: drivers/scsi/scsi_lib.c:2702
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff818b8080-ffffffff818b8094: scsi_start_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void scsi_start_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81a013cd)
Location: drivers/scsi/scsi_lib.c:2710
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff81a036e0-ffffffff81a0371c: scsi_start_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void scsi_start_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b7f9cd)
Location: drivers/scsi/scsi_lib.c:2715
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff81b82210-ffffffff81b8224c: scsi_start_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void scsi_start_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd38e9)
Location: drivers/scsi/scsi_lib.c:2731
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff81bd5f20-ffffffff81bd5f5c: scsi_start_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void scsi_start_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c28579)
Location: drivers/scsi/scsi_lib.c:2728
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff81c2ab70-ffffffff81c2abac: scsi_start_queue (STB_GLOBAL)
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
void scsi_start_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffff8000109763a8)
Location: drivers/scsi/scsi_lib.c:2703
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffff800010979ab8-ffff800010979ae4: scsi_start_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void scsi_start_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c0a4ad44)
Location: drivers/scsi/scsi_lib.c:2703
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
c0a4d7b4-c0a4d7d4: scsi_start_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void scsi_start_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c000000000a30abc)
Location: drivers/scsi/scsi_lib.c:2703
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
c000000000a34520-c000000000a34558: scsi_start_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void scsi_start_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffe0005dea9e)
Location: drivers/scsi/scsi_lib.c:2703
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffe0005e1096-ffffffe0005e10c0: scsi_start_queue (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void scsi_start_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81727519)
Location: drivers/scsi/scsi_lib.c:2703
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff81729f00-ffffffff81729f14: scsi_start_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void scsi_start_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81700949)
Location: drivers/scsi/scsi_lib.c:2703
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff81703320-ffffffff81703334: scsi_start_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void scsi_start_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817662e9)
Location: drivers/scsi/scsi_lib.c:2703
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff81768cd0-ffffffff81768ce4: scsi_start_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void scsi_start_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81781999)
Location: drivers/scsi/scsi_lib.c:2703
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock_nowait
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff81784450-ffffffff81784464: scsi_start_queue (STB_GLOBAL)
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
