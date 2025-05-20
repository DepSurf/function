# Function: <code>amd_chipset_sb_type_init</code>

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
In drivers/usb/host/pci-quirks.c (ffffffff8162fc92)
Location: drivers/usb/host/pci-quirks.c:120
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
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
In drivers/usb/host/pci-quirks.c (ffffffff81690904)
Location: drivers/usb/host/pci-quirks.c:120
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
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
In drivers/usb/host/pci-quirks.c (ffffffff816be9b4)
Location: drivers/usb/host/pci-quirks.c:119
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
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
In drivers/usb/host/pci-quirks.c (ffffffff816d3294)
Location: drivers/usb/host/pci-quirks.c:130
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
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
In drivers/usb/host/pci-quirks.c (ffffffff8173f954)
Location: drivers/usb/host/pci-quirks.c:131
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
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
In drivers/usb/host/pci-quirks.c (ffffffff817802ee)
Location: drivers/usb/host/pci-quirks.c:148
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
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
In drivers/usb/host/pci-quirks.c (ffffffff817a6aee)
Location: drivers/usb/host/pci-quirks.c:148
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
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
In drivers/usb/host/pci-quirks.c (ffffffff817e5d11)
Location: drivers/usb/host/pci-quirks.c:148
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
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
In drivers/usb/host/pci-quirks.c (ffffffff81816bd1)
Location: drivers/usb/host/pci-quirks.c:148
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int amd_chipset_sb_type_init(struct amd_chipset_info *pinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff818e7b40)
Location: drivers/usb/host/pci-quirks.c:151
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
```
**Symbols:**

```
ffffffff818e7b40-ffffffff818e7c3a: amd_chipset_sb_type_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int amd_chipset_sb_type_init(struct amd_chipset_info *pinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff818f0b20)
Location: drivers/usb/host/pci-quirks.c:151
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
```
**Symbols:**

```
ffffffff818f0b20-ffffffff818f0c1a: amd_chipset_sb_type_init (STB_LOCAL)
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
In drivers/usb/host/pci-quirks.c (ffffffff818d4431)
Location: drivers/usb/host/pci-quirks.c:151
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
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
In drivers/usb/host/pci-quirks.c (ffffffff8196f991)
Location: drivers/usb/host/pci-quirks.c:151
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
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
In drivers/usb/host/pci-quirks.c (ffffffff81ac9d85)
Location: drivers/usb/host/pci-quirks.c:151
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
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
In drivers/usb/host/pci-quirks.c (ffffffff81c54245)
Location: drivers/usb/host/pci-quirks.c:151
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81cbb7bf)
Location: drivers/usb/host/pci-quirks.c:151
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81d7052f)
Location: drivers/usb/host/pci-quirks.c:153
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
```
</details>
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
In drivers/usb/host/pci-quirks.c (ffff800010a50490)
Location: drivers/usb/host/pci-quirks.c:148
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
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
In drivers/usb/host/pci-quirks.c (c0b21eb4)
Location: drivers/usb/host/pci-quirks.c:148
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
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
In drivers/usb/host/pci-quirks.c (c000000000b17cb0)
Location: drivers/usb/host/pci-quirks.c:148
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
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
In drivers/usb/host/pci-quirks.c (ffffffe00066c51c)
Location: drivers/usb/host/pci-quirks.c:148
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
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
In drivers/usb/host/pci-quirks.c (ffffffff817cefb1)
Location: drivers/usb/host/pci-quirks.c:148
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
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
In drivers/usb/host/pci-quirks.c (ffffffff817acee1)
Location: drivers/usb/host/pci-quirks.c:148
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
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
In drivers/usb/host/pci-quirks.c (ffffffff8180ba51)
Location: drivers/usb/host/pci-quirks.c:148
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
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
In drivers/usb/host/pci-quirks.c (ffffffff81825b61)
Location: drivers/usb/host/pci-quirks.c:148
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_find_chipset_info
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
