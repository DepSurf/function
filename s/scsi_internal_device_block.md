# Function: <code>scsi_internal_device_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_internal_device_block(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff815ae0a0)
Location: drivers/scsi/scsi_lib.c:2949
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_block
```
**Symbols:**

```
ffffffff815ae0a0-ffffffff815ae126: scsi_internal_device_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_internal_device_block(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81605f70)
Location: drivers/scsi/scsi_lib.c:2823
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_block
```
**Symbols:**

```
ffffffff81605f70-ffffffff81605ff6: scsi_internal_device_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_internal_device_block(struct scsi_device *sdev, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81637120)
Location: drivers/scsi/scsi_lib.c:2902
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_block
```
**Symbols:**

```
ffffffff81637120-ffffffff81637277: scsi_internal_device_block (STB_GLOBAL)
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
In drivers/scsi/scsi_lib.c (ffffffff8164b6db)
Location: drivers/scsi/scsi_lib.c:3022
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_block
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
In drivers/scsi/scsi_lib.c (ffffffff816b4a1b)
Location: drivers/scsi/scsi_lib.c:3122
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_block
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
In drivers/scsi/scsi_lib.c (ffffffff816f0c45)
Location: drivers/scsi/scsi_lib.c:3138
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_block
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
In drivers/scsi/scsi_lib.c (ffffffff81713475)
Location: drivers/scsi/scsi_lib.c:2693
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_block
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8174ed55)
Location: drivers/scsi/scsi_lib.c:2642
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_block
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81772f05)
Location: drivers/scsi/scsi_lib.c:2689
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_block
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818368b5)
Location: drivers/scsi/scsi_lib.c:2672
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_block
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81847385)
Location: drivers/scsi/scsi_lib.c:2678
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_block
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8182a455)
Location: drivers/scsi/scsi_lib.c:2695
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_block
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b5f35)
Location: drivers/scsi/scsi_lib.c:2688
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_block
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81a000c5)
Location: drivers/scsi/scsi_lib.c:2780
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_block
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b7e6d5)
Location: drivers/scsi/scsi_lib.c:2785
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_block
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffff8000109764d0)
Location: drivers/scsi/scsi_lib.c:2689
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_block
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c0a4ae64)
Location: drivers/scsi/scsi_lib.c:2689
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_block
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c000000000a30cac)
Location: drivers/scsi/scsi_lib.c:2689
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_block
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffe0005debb8)
Location: drivers/scsi/scsi_lib.c:2689
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_block
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817275f5)
Location: drivers/scsi/scsi_lib.c:2689
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_block
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81700a25)
Location: drivers/scsi/scsi_lib.c:2689
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_block
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817663c5)
Location: drivers/scsi/scsi_lib.c:2689
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_block
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81781a75)
Location: drivers/scsi/scsi_lib.c:2689
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_block
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool wait</code>
</li>
</ul>
</details>
</li>
</ul>
