# Function: <code>edac_pci_add_device</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int edac_pci_add_device(struct edac_pci_ctl_info *pci, int edac_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci.c (ffffffff8175fa70)
Location: drivers/edac/edac_pci.c:204
Inline: True
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
**Symbols:**

```
ffffffff8175fa70-ffffffff8175fca5: edac_pci_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int edac_pci_add_device(struct edac_pci_ctl_info *pci, int edac_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci.c (ffffffff817d1b00)
Location: drivers/edac/edac_pci.c:204
Inline: True
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
**Symbols:**

```
ffffffff817d1b00-ffffffff817d1d28: edac_pci_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int edac_pci_add_device(struct edac_pci_ctl_info *pci, int edac_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (0)
Location: drivers/edac/edac_pci.c:204
Inline: True
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
**Symbols:**

```
ffffffff8181abe6-ffffffff8181ac8d: edac_pci_add_device.cold.11 (STB_LOCAL)
ffffffff8181a890-ffffffff8181aa1b: edac_pci_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int edac_pci_add_device(struct edac_pci_ctl_info *pci, int edac_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (ffffffff81846136)
Location: drivers/edac/edac_pci.c:204
Inline: True
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
**Symbols:**

```
ffffffff818463d6-ffffffff8184647d: edac_pci_add_device.cold.11 (STB_LOCAL)
ffffffff81846080-ffffffff8184620b: edac_pci_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int edac_pci_add_device(struct edac_pci_ctl_info *pci, int edac_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (ffffffff81888f05)
Location: drivers/edac/edac_pci.c:204
Inline: True
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
**Symbols:**

```
ffffffff81889189-ffffffff81889224: edac_pci_add_device.cold (STB_LOCAL)
ffffffff81888e60-ffffffff81888fb5: edac_pci_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int edac_pci_add_device(struct edac_pci_ctl_info *pci, int edac_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (ffffffff818baeb5)
Location: drivers/edac/edac_pci.c:204
Inline: True
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
**Symbols:**

```
ffffffff818bb139-ffffffff818bb1d4: edac_pci_add_device.cold (STB_LOCAL)
ffffffff818bae10-ffffffff818baf65: edac_pci_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int edac_pci_add_device(struct edac_pci_ctl_info *pci, int edac_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (0)
Location: drivers/edac/edac_pci.c:204
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
**Symbols:**

```
ffffffff8198ba25-ffffffff8198ba61: edac_pci_add_device.cold (STB_LOCAL)
ffffffff8198b590-ffffffff8198b6a6: edac_pci_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int edac_pci_add_device(struct edac_pci_ctl_info *pci, int edac_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (0)
Location: drivers/edac/edac_pci.c:204
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
**Symbols:**

```
ffffffff81c28b6f-ffffffff81c28bab: edac_pci_add_device.cold (STB_LOCAL)
ffffffff8198f180-ffffffff8198f296: edac_pci_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int edac_pci_add_device(struct edac_pci_ctl_info *pci, int edac_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (0)
Location: drivers/edac/edac_pci.c:204
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
**Symbols:**

```
ffffffff81c1ad03-ffffffff81c1ad9e: edac_pci_add_device.cold (STB_LOCAL)
ffffffff81973750-ffffffff819738a5: edac_pci_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int edac_pci_add_device(struct edac_pci_ctl_info *pci, int edac_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (0)
Location: drivers/edac/edac_pci.c:204
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
**Symbols:**

```
ffffffff81d2ac33-ffffffff81d2acce: edac_pci_add_device.cold (STB_LOCAL)
ffffffff81a1c450-ffffffff81a1c5a5: edac_pci_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int edac_pci_add_device(struct edac_pci_ctl_info *pci, int edac_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (0)
Location: drivers/edac/edac_pci.c:203
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
**Symbols:**

```
ffffffff81ef6dd7-ffffffff81ef6e72: edac_pci_add_device.cold (STB_LOCAL)
ffffffff81b85510-ffffffff81b85677: edac_pci_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int edac_pci_add_device(struct edac_pci_ctl_info *pci, int edac_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci.c (ffffffff81d24570)
Location: drivers/edac/edac_pci.c:200
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
**Symbols:**

```
ffffffff81d24570-ffffffff81d2478f: edac_pci_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int edac_pci_add_device(struct edac_pci_ctl_info *pci, int edac_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci.c (ffffffff81d8d780)
Location: drivers/edac/edac_pci.c:200
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
**Symbols:**

```
ffffffff81d8d780-ffffffff81d8d99f: edac_pci_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int edac_pci_add_device(struct edac_pci_ctl_info *pci, int edac_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci.c (ffffffff81e45030)
Location: drivers/edac/edac_pci.c:200
Inline: False
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
**Symbols:**

```
ffffffff81e45030-ffffffff81e4524f: edac_pci_add_device (STB_GLOBAL)
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
int edac_pci_add_device(struct edac_pci_ctl_info *pci, int edac_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci.c (ffff800010b13428)
Location: drivers/edac/edac_pci.c:204
Inline: True
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
**Symbols:**

```
ffff800010b13428-ffff800010b13630: edac_pci_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int edac_pci_add_device(struct edac_pci_ctl_info *pci, int edac_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci.c (c0bf13bc)
Location: drivers/edac/edac_pci.c:204
Inline: True
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
**Symbols:**

```
c0bf13bc-c0bf15d0: edac_pci_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int edac_pci_add_device(struct edac_pci_ctl_info *pci, int edac_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci.c (c000000000c07ea0)
Location: drivers/edac/edac_pci.c:204
Inline: True
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
**Symbols:**

```
c000000000c07ea0-c000000000c08158: edac_pci_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int edac_pci_add_device(struct edac_pci_ctl_info *pci, int edac_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci.c (ffffffe0006ffe90)
Location: drivers/edac/edac_pci.c:204
Inline: True
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
**Symbols:**

```
ffffffe0006ffe90-ffffffe00070006c: edac_pci_add_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int edac_pci_add_device(struct edac_pci_ctl_info *pci, int edac_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (ffffffff81860d35)
Location: drivers/edac/edac_pci.c:204
Inline: True
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
**Symbols:**

```
ffffffff81860fb9-ffffffff81861054: edac_pci_add_device.cold (STB_LOCAL)
ffffffff81860c90-ffffffff81860de5: edac_pci_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int edac_pci_add_device(struct edac_pci_ctl_info *pci, int edac_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (ffffffff81828305)
Location: drivers/edac/edac_pci.c:204
Inline: True
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
**Symbols:**

```
ffffffff81828589-ffffffff81828624: edac_pci_add_device.cold (STB_LOCAL)
ffffffff81828260-ffffffff818283b5: edac_pci_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int edac_pci_add_device(struct edac_pci_ctl_info *pci, int edac_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (ffffffff818b0365)
Location: drivers/edac/edac_pci.c:204
Inline: True
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
**Symbols:**

```
ffffffff818b05e9-ffffffff818b0684: edac_pci_add_device.cold (STB_LOCAL)
ffffffff818b02c0-ffffffff818b0415: edac_pci_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int edac_pci_add_device(struct edac_pci_ctl_info *pci, int edac_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_pci.c (ffffffff818cc5f5)
Location: drivers/edac/edac_pci.c:204
Inline: True
Direct callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
**Symbols:**

```
ffffffff818cc879-ffffffff818cc914: edac_pci_add_device.cold (STB_LOCAL)
ffffffff818cc550-ffffffff818cc6a5: edac_pci_add_device (STB_GLOBAL)
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
