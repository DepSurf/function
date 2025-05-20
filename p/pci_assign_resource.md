# Function: <code>pci_assign_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_assign_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8143d700)
Location: drivers/pci/setup-res.c:273
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff8143d700-ffffffff8143d939: pci_assign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_assign_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81489540)
Location: drivers/pci/setup-res.c:273
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff81489540-ffffffff81489749: pci_assign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_assign_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff814aad30)
Location: drivers/pci/setup-res.c:301
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff814aad30-ffffffff814aaf39: pci_assign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_assign_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff814b5020)
Location: drivers/pci/setup-res.c:301
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff814b5020-ffffffff814b5232: pci_assign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_assign_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff814f4a20)
Location: drivers/pci/setup-res.c:315
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff814f4a20-ffffffff814f4c32: pci_assign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_assign_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81524ad0)
Location: drivers/pci/setup-res.c:309
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff81524ad0-ffffffff81524cec: pci_assign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_assign_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8153a950)
Location: drivers/pci/setup-res.c:309
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff8153a950-ffffffff8153ab6c: pci_assign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_assign_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:309
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff8156a60d-ffffffff8156a76a: pci_assign_resource.cold (STB_LOCAL)
ffffffff8156a2c0-ffffffff8156a380: pci_assign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pci_assign_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:309
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff8158b5dd-ffffffff8158b73a: pci_assign_resource.cold (STB_LOCAL)
ffffffff8158b290-ffffffff8158b350: pci_assign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pci_assign_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:309
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
  - drivers/pci/setup-bus.c:reassign_resources_sorted
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff8163270f-ffffffff816327c3: pci_assign_resource.cold (STB_LOCAL)
ffffffff81632220-ffffffff81632328: pci_assign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pci_assign_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:310
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
  - drivers/pci/setup-bus.c:reassign_resources_sorted
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff81bf83eb-ffffffff81bf849f: pci_assign_resource.cold (STB_LOCAL)
ffffffff81657840-ffffffff81657948: pci_assign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pci_assign_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:310
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff81bea196-ffffffff81bea2f0: pci_assign_resource.cold (STB_LOCAL)
ffffffff8163a1b0-ffffffff8163a270: pci_assign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_assign_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:310
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff81ce4fff-ffffffff81ce5159: pci_assign_resource.cold (STB_LOCAL)
ffffffff816aa9c0-ffffffff816aaa80: pci_assign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_assign_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:314
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff81eaba8e-ffffffff81eabbec: pci_assign_resource.cold (STB_LOCAL)
ffffffff817cd930-ffffffff817cd9de: pci_assign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_assign_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff818ecf80)
Location: drivers/pci/setup-res.c:325
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff818ecf80-ffffffff818ed1ef: pci_assign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_assign_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81930460)
Location: drivers/pci/setup-res.c:325
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff81930460-ffffffff819306d4: pci_assign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_assign_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81978e00)
Location: drivers/pci/setup-res.c:327
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
  - drivers/pci/setup-bus.c:reassign_resources_sorted
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff81978e00-ffffffff819790a5: pci_assign_resource (STB_GLOBAL)
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
int pci_assign_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffff8000106f0068)
Location: drivers/pci/setup-res.c:309
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
ffff8000106f0068-ffff8000106f02b4: pci_assign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_assign_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (c088abe4)
Location: drivers/pci/setup-res.c:309
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
c088abe4-c088ae20: pci_assign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_assign_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (c00000000086d550)
Location: drivers/pci/setup-res.c:309
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
c00000000086d550-c00000000086d844: pci_assign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_assign_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffe0004c3d0e)
Location: drivers/pci/setup-res.c:309
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
ffffffe0004c3d0e-ffffffe0004c3ef4: pci_assign_resource (STB_GLOBAL)
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
int pci_assign_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:309
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff8157f45d-ffffffff8157f5ba: pci_assign_resource.cold (STB_LOCAL)
ffffffff8157f110-ffffffff8157f1d0: pci_assign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pci_assign_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:309
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff8156e23d-ffffffff8156e39a: pci_assign_resource.cold (STB_LOCAL)
ffffffff8156def0-ffffffff8156dfb0: pci_assign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pci_assign_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:309
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff8157f32d-ffffffff8157f48a: pci_assign_resource.cold (STB_LOCAL)
ffffffff8157efe0-ffffffff8157f0a0: pci_assign_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pci_assign_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:309
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
**Symbols:**

```
ffffffff815997dd-ffffffff8159993a: pci_assign_resource.cold (STB_LOCAL)
ffffffff81599490-ffffffff81599550: pci_assign_resource (STB_GLOBAL)
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
