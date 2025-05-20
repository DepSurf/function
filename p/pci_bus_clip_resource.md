# Function: <code>pci_bus_clip_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool pci_bus_clip_resource(struct pci_dev *dev, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8142f710)
Location: drivers/pci/bus.c:233
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_claim_bridge_resource
```
**Symbols:**

```
ffffffff8142f710-ffffffff8142f8ab: pci_bus_clip_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool pci_bus_clip_resource(struct pci_dev *dev, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8147ad20)
Location: drivers/pci/bus.c:262
Inline: False
```
**Symbols:**

```
ffffffff8147ad20-ffffffff8147ae95: pci_bus_clip_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool pci_bus_clip_resource(struct pci_dev *dev, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8149c1a0)
Location: drivers/pci/bus.c:262
Inline: False
```
**Symbols:**

```
ffffffff8149c1a0-ffffffff8149c31e: pci_bus_clip_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool pci_bus_clip_resource(struct pci_dev *dev, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff814a5f50)
Location: drivers/pci/bus.c:262
Inline: False
```
**Symbols:**

```
ffffffff814a5f50-ffffffff814a60de: pci_bus_clip_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool pci_bus_clip_resource(struct pci_dev *dev, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff814e4d90)
Location: drivers/pci/bus.c:262
Inline: False
```
**Symbols:**

```
ffffffff814e4d90-ffffffff814e4f18: pci_bus_clip_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool pci_bus_clip_resource(struct pci_dev *dev, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81514260)
Location: drivers/pci/bus.c:261
Inline: False
```
**Symbols:**

```
ffffffff81514260-ffffffff815143f4: pci_bus_clip_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool pci_bus_clip_resource(struct pci_dev *dev, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff815299c0)
Location: drivers/pci/bus.c:261
Inline: False
```
**Symbols:**

```
ffffffff815299c0-ffffffff81529b5f: pci_bus_clip_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool pci_bus_clip_resource(struct pci_dev *dev, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:261
Inline: False
```
**Symbols:**

```
ffffffff81558ea9-ffffffff81558ef9: pci_bus_clip_resource.cold (STB_LOCAL)
ffffffff81558c30-ffffffff81558d6e: pci_bus_clip_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool pci_bus_clip_resource(struct pci_dev *dev, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:261
Inline: False
```
**Symbols:**

```
ffffffff8157a49c-ffffffff8157a4e6: pci_bus_clip_resource.cold (STB_LOCAL)
ffffffff8157a1c0-ffffffff8157a304: pci_bus_clip_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool pci_bus_clip_resource(struct pci_dev *dev, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:261
Inline: False
```
**Symbols:**

```
ffffffff8161f5c0-ffffffff8161f611: pci_bus_clip_resource.cold (STB_LOCAL)
ffffffff8161f290-ffffffff8161f428: pci_bus_clip_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool pci_bus_clip_resource(struct pci_dev *dev, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:261
Inline: False
```
**Symbols:**

```
ffffffff81bf6ebd-ffffffff81bf6f0e: pci_bus_clip_resource.cold (STB_LOCAL)
ffffffff81645a80-ffffffff81645c18: pci_bus_clip_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool pci_bus_clip_resource(struct pci_dev *dev, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:261
Inline: False
```
**Symbols:**

```
ffffffff81be8d2c-ffffffff81be8d81: pci_bus_clip_resource.cold (STB_LOCAL)
ffffffff816287c0-ffffffff81628951: pci_bus_clip_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool pci_bus_clip_resource(struct pci_dev *dev, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:261
Inline: False
```
**Symbols:**

```
ffffffff81ce3127-ffffffff81ce317b: pci_bus_clip_resource.cold (STB_LOCAL)
ffffffff81698110-ffffffff816982da: pci_bus_clip_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool pci_bus_clip_resource(struct pci_dev *dev, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:261
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_claim_bridge_resource
```
**Symbols:**

```
ffffffff81ea9c1b-ffffffff81ea9c6f: pci_bus_clip_resource.cold (STB_LOCAL)
ffffffff817b93d0-ffffffff817b95b2: pci_bus_clip_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool pci_bus_clip_resource(struct pci_dev *dev, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff818d3f50)
Location: drivers/pci/bus.c:265
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_claim_bridge_resource
```
**Symbols:**

```
ffffffff818d3f50-ffffffff818d418c: pci_bus_clip_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool pci_bus_clip_resource(struct pci_dev *dev, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81917190)
Location: drivers/pci/bus.c:287
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_claim_bridge_resource
```
**Symbols:**

```
ffffffff81917190-ffffffff819173d6: pci_bus_clip_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool pci_bus_clip_resource(struct pci_dev *dev, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8195f290)
Location: drivers/pci/bus.c:287
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_claim_bridge_resource
```
**Symbols:**

```
ffffffff8195f290-ffffffff8195f4e4: pci_bus_clip_resource (STB_GLOBAL)
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
bool pci_bus_clip_resource(struct pci_dev *dev, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffff8000106dcaa8)
Location: drivers/pci/bus.c:261
Inline: False
```
**Symbols:**

```
ffff8000106dcaa8-ffff8000106dcc00: pci_bus_clip_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool pci_bus_clip_resource(struct pci_dev *dev, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (c08786b0)
Location: drivers/pci/bus.c:261
Inline: False
```
**Symbols:**

```
c08786b0-c0878800: pci_bus_clip_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool pci_bus_clip_resource(struct pci_dev *dev, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (c000000000854b40)
Location: drivers/pci/bus.c:261
Inline: False
```
**Symbols:**

```
c000000000854b40-c000000000854d18: pci_bus_clip_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool pci_bus_clip_resource(struct pci_dev *dev, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffe0004b4f4c)
Location: drivers/pci/bus.c:261
Inline: False
```
**Symbols:**

```
ffffffe0004b4f4c-ffffffe0004b5086: pci_bus_clip_resource (STB_GLOBAL)
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
bool pci_bus_clip_resource(struct pci_dev *dev, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:261
Inline: False
```
**Symbols:**

```
ffffffff8156e9ac-ffffffff8156e9fc: pci_bus_clip_resource.cold (STB_LOCAL)
ffffffff8156e6e0-ffffffff8156e81e: pci_bus_clip_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
bool pci_bus_clip_resource(struct pci_dev *dev, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:261
Inline: False
```
**Symbols:**

```
ffffffff8155d11c-ffffffff8155d166: pci_bus_clip_resource.cold (STB_LOCAL)
ffffffff8155ce40-ffffffff8155cf84: pci_bus_clip_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
bool pci_bus_clip_resource(struct pci_dev *dev, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:261
Inline: False
```
**Symbols:**

```
ffffffff8156e1ec-ffffffff8156e236: pci_bus_clip_resource.cold (STB_LOCAL)
ffffffff8156df10-ffffffff8156e054: pci_bus_clip_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool pci_bus_clip_resource(struct pci_dev *dev, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (0)
Location: drivers/pci/bus.c:261
Inline: False
```
**Symbols:**

```
ffffffff815886cc-ffffffff81588716: pci_bus_clip_resource.cold (STB_LOCAL)
ffffffff815883f0-ffffffff81588534: pci_bus_clip_resource (STB_GLOBAL)
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
