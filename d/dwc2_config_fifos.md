# Function: <code>dwc2_config_fifos</code>

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
In drivers/usb/dwc2/core.c (ffffffff8162375d)
Location: drivers/usb/dwc2/core.c:951
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_core_host_init
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
In drivers/usb/dwc2/hcd.c (ffffffff816852be)
Location: drivers/usb/dwc2/hcd.c:450
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff816b34e3)
Location: drivers/usb/dwc2/hcd.c:451
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff816c7800)
Location: drivers/usb/dwc2/hcd.c:467
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff81733c7c)
Location: drivers/usb/dwc2/hcd.c:473
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff8177403a)
Location: drivers/usb/dwc2/hcd.c:486
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
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
In drivers/usb/dwc2/hcd.c (ffffffff81798b98)
Location: drivers/usb/dwc2/hcd.c:480
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dwc2_config_fifos(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:290
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff817d7b10-ffffffff817d7dd1: dwc2_config_fifos (STB_LOCAL)
ffffffff817de7e4-ffffffff817de7f8: dwc2_config_fifos.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void dwc2_config_fifos(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:290
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff818089a0-ffffffff81808c61: dwc2_config_fifos (STB_LOCAL)
ffffffff8180f734-ffffffff8180f748: dwc2_config_fifos.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dwc2_config_fifos(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:290
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff818d97c0-ffffffff818d9a81: dwc2_config_fifos (STB_LOCAL)
ffffffff818e045d-ffffffff818e0471: dwc2_config_fifos.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dwc2_config_fifos(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:290
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff818e3710-ffffffff818e39d1: dwc2_config_fifos (STB_LOCAL)
ffffffff81c1f4d4-ffffffff81c1f4e8: dwc2_config_fifos.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dwc2_config_fifos(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:288
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff818c68f0-ffffffff818c6bb8: dwc2_config_fifos (STB_LOCAL)
ffffffff81c11363-ffffffff81c11377: dwc2_config_fifos.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_config_fifos(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:288
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff8195fe30-ffffffff819601dd: dwc2_config_fifos (STB_LOCAL)
ffffffff81d1ac6e-ffffffff81d1ad9b: dwc2_config_fifos.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_config_fifos(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:284
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff81aba2a0-ffffffff81aba65b: dwc2_config_fifos (STB_LOCAL)
ffffffff81ee5e01-ffffffff81ee5f2e: dwc2_config_fifos.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_config_fifos(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:255
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff81c43700-ffffffff81c43acf: dwc2_config_fifos (STB_LOCAL)
ffffffff820a170e-ffffffff820a1827: dwc2_config_fifos.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_config_fifos(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:255
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff81caacc0-ffffffff81cab08f: dwc2_config_fifos (STB_LOCAL)
ffffffff82122ce1-ffffffff82122dfa: dwc2_config_fifos.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_config_fifos(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:255
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff81d5f970-ffffffff81d5fd3f: dwc2_config_fifos (STB_LOCAL)
ffffffff822044b8-ffffffff822045d1: dwc2_config_fifos.cold (STB_LOCAL)
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
void dwc2_config_fifos(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffff800010a40528)
Location: drivers/usb/dwc2/hcd.c:290
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffff800010a40528-ffff800010a40850: dwc2_config_fifos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dwc2_config_fifos(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c0b144d4)
Location: drivers/usb/dwc2/hcd.c:290
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
c0b144d4-c0b1487c: dwc2_config_fifos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dwc2_config_fifos(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c000000000b03060)
Location: drivers/usb/dwc2/hcd.c:290
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
c000000000b03060-c000000000b036e0: dwc2_config_fifos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dwc2_config_fifos(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffe00065db7a)
Location: drivers/usb/dwc2/hcd.c:290
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffe00065db7a-ffffffe00065e0c6: dwc2_config_fifos (STB_LOCAL)
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
void dwc2_config_fifos(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:290
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff817c0d80-ffffffff817c1041: dwc2_config_fifos (STB_LOCAL)
ffffffff817c7b14-ffffffff817c7b28: dwc2_config_fifos.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void dwc2_config_fifos(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:290
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff817fd820-ffffffff817fdae1: dwc2_config_fifos (STB_LOCAL)
ffffffff818045b4-ffffffff818045c8: dwc2_config_fifos.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void dwc2_config_fifos(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:290
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_host_init
```
**Symbols:**

```
ffffffff81817930-ffffffff81817bf1: dwc2_config_fifos (STB_LOCAL)
ffffffff8181e6c4-ffffffff8181e6d8: dwc2_config_fifos.cold (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
