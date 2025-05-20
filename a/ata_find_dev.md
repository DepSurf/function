# Function: <code>ata_find_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff815d18b0)
Location: drivers/ata/libata-scsi.c:2832
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
Direct callers:
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
```
**Symbols:**

```
ffffffff815d18b0-ffffffff815d1918: ata_find_dev.part.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8162e12a)
Location: drivers/ata/libata-scsi.c:2972
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
```
**Symbols:**

```
ffffffff8162ad60-ffffffff8162adbb: ata_find_dev.part.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8165f27a)
Location: drivers/ata/libata-scsi.c:3053
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
```
**Symbols:**

```
ffffffff8165bfe0-ffffffff8165c045: ata_find_dev.part.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_find_dev(struct ata_port *ap, int devno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81671630)
Location: drivers/ata/libata-scsi.c:3030
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
```
**Symbols:**

```
ffffffff81671630-ffffffff816716b8: ata_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_find_dev(struct ata_port *ap, int devno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff816dac10)
Location: drivers/ata/libata-scsi.c:3031
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
```
**Symbols:**

```
ffffffff816dac10-ffffffff816dac98: ata_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_find_dev(struct ata_port *ap, int devno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81717100)
Location: drivers/ata/libata-scsi.c:3034
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
```
**Symbols:**

```
ffffffff81717100-ffffffff81717188: ata_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_find_dev(struct ata_port *ap, int devno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81739740)
Location: drivers/ata/libata-scsi.c:3029
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
```
**Symbols:**

```
ffffffff81739740-ffffffff817397d2: ata_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_find_dev(struct ata_port *ap, int devno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81775750)
Location: drivers/ata/libata-scsi.c:3033
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
```
**Symbols:**

```
ffffffff81775750-ffffffff817757d5: ata_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_find_dev(struct ata_port *ap, int devno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff817996c0)
Location: drivers/ata/libata-scsi.c:3033
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
```
**Symbols:**

```
ffffffff817996c0-ffffffff81799745: ata_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_find_dev(struct ata_port *ap, int devno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8185b325)
Location: drivers/ata/libata-scsi.c:2745
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
```
**Symbols:**

```
ffffffff8185b110-ffffffff8185b195: ata_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_find_dev(struct ata_port *ap, int devno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8186a425)
Location: drivers/ata/libata-scsi.c:2745
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
```
**Symbols:**

```
ffffffff8186a210-ffffffff8186a295: ata_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_find_dev(struct ata_port *ap, int devno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8184cce1)
Location: drivers/ata/libata-scsi.c:2741
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
```
**Symbols:**

```
ffffffff8184cac0-ffffffff8184cb48: ata_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_find_dev(struct ata_port *ap, int devno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff818da2d6)
Location: drivers/ata/libata-scsi.c:2701
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
```
**Symbols:**

```
ffffffff818da110-ffffffff818da1c5: ata_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_find_dev(struct ata_port *ap, int devno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81a2b6fc)
Location: drivers/ata/libata-scsi.c:2705
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
```
**Symbols:**

```
ffffffff81a2b140-ffffffff81a2b22a: ata_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_find_dev(struct ata_port *ap, int devno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81bae7bc)
Location: drivers/ata/libata-scsi.c:2718
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
```
**Symbols:**

```
ffffffff81badff0-ffffffff81bae0da: ata_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_find_dev(struct ata_port *ap, unsigned int devno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81c05d76)
Location: drivers/ata/libata-scsi.c:2848
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
```
**Symbols:**

```
ffffffff81c04130-ffffffff81c041f2: ata_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_find_dev(struct ata_port *ap, unsigned int devno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81c5b1e6)
Location: drivers/ata/libata-scsi.c:2720
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
```
**Symbols:**

```
ffffffff81c597a0-ffffffff81c59860: ata_find_dev (STB_LOCAL)
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
struct ata_device *ata_find_dev(struct ata_port *ap, int devno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffff8000109a1118)
Location: drivers/ata/libata-scsi.c:3033
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
```
**Symbols:**

```
ffff8000109a1118-ffff8000109a11d4: ata_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_find_dev(struct ata_port *ap, int devno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (c0a73fe0)
Location: drivers/ata/libata-scsi.c:3033
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
```
**Symbols:**

```
c0a73fe0-c0a74094: ata_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_find_dev(struct ata_port *ap, int devno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (c000000000a68c10)
Location: drivers/ata/libata-scsi.c:3033
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
```
**Symbols:**

```
c000000000a68c10-c000000000a68cc8: ata_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_find_dev(struct ata_port *ap, int devno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffe0006023a2)
Location: drivers/ata/libata-scsi.c:3033
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
```
**Symbols:**

```
ffffffe0006023a2-ffffffe000602454: ata_find_dev (STB_LOCAL)
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
struct ata_device *ata_find_dev(struct ata_port *ap, int devno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8175e7b0)
Location: drivers/ata/libata-scsi.c:3033
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
```
**Symbols:**

```
ffffffff8175e7b0-ffffffff8175e835: ata_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_find_dev(struct ata_port *ap, int devno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8173e650)
Location: drivers/ata/libata-scsi.c:3033
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
```
**Symbols:**

```
ffffffff8173e650-ffffffff8173e6d5: ata_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_find_dev(struct ata_port *ap, int devno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8178e540)
Location: drivers/ata/libata-scsi.c:3033
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
```
**Symbols:**

```
ffffffff8178e540-ffffffff8178e5c5: ata_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct ata_device *ata_find_dev(struct ata_port *ap, int devno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff817a8390)
Location: drivers/ata/libata-scsi.c:3033
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_user_scan
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_scsi_find_dev
```
**Symbols:**

```
ffffffff817a8390-ffffffff817a8415: ata_find_dev (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int devno</code> ➡️ <code>unsigned int devno</code>
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
