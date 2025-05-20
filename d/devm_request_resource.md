# Function: <code>devm_request_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int devm_request_resource(struct device *dev, struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810864a0)
Location: kernel/resource.c:1290
Inline: False
```
**Symbols:**

```
ffffffff810864a0-ffffffff8108654e: devm_request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int devm_request_resource(struct device *dev, struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810894f0)
Location: kernel/resource.c:1359
Inline: False
Direct callers:
  - drivers/pci/bus.c:devm_request_pci_bus_resources
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
**Symbols:**

```
ffffffff810894f0-ffffffff8108959e: devm_request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int devm_request_resource(struct device *dev, struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108e440)
Location: kernel/resource.c:1359
Inline: False
Direct callers:
  - drivers/pci/bus.c:devm_request_pci_bus_resources
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
**Symbols:**

```
ffffffff8108e440-ffffffff8108e4ee: devm_request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int devm_request_resource(struct device *dev, struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108b460)
Location: kernel/resource.c:1359
Inline: False
Direct callers:
  - drivers/pci/bus.c:devm_request_pci_bus_resources
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
**Symbols:**

```
ffffffff8108b460-ffffffff8108b507: devm_request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int devm_request_resource(struct device *dev, struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81092140)
Location: kernel/resource.c:1377
Inline: False
Direct callers:
  - drivers/pci/bus.c:devm_request_pci_bus_resources
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
**Symbols:**

```
ffffffff81092140-ffffffff810921e7: devm_request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int devm_request_resource(struct device *dev, struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81096410)
Location: kernel/resource.c:1347
Inline: False
Direct callers:
  - drivers/pci/bus.c:devm_request_pci_bus_resources
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
**Symbols:**

```
ffffffff81096410-ffffffff810964a4: devm_request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int devm_request_resource(struct device *dev, struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109e780)
Location: kernel/resource.c:1356
Inline: False
Direct callers:
  - drivers/pci/bus.c:devm_request_pci_bus_resources
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
**Symbols:**

```
ffffffff8109e780-ffffffff8109e814: devm_request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int devm_request_resource(struct device *dev, struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1379
Inline: False
Direct callers:
  - drivers/pci/bus.c:devm_request_pci_bus_resources
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
**Symbols:**

```
ffffffff810a3992-ffffffff810a39bd: devm_request_resource.cold (STB_LOCAL)
ffffffff810a2df0-ffffffff810a2e62: devm_request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int devm_request_resource(struct device *dev, struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1379
Inline: False
Direct callers:
  - drivers/pci/bus.c:devm_request_pci_bus_resources
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
**Symbols:**

```
ffffffff810a9f86-ffffffff810a9fb1: devm_request_resource.cold (STB_LOCAL)
ffffffff810a9430-ffffffff810a94a2: devm_request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int devm_request_resource(struct device *dev, struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1384
Inline: False
Direct callers:
  - drivers/pci/bus.c:devm_request_pci_bus_resources
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
**Symbols:**

```
ffffffff810b1b31-ffffffff810b1b5c: devm_request_resource.cold (STB_LOCAL)
ffffffff810b0780-ffffffff810b0805: devm_request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int devm_request_resource(struct device *dev, struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1457
Inline: False
Direct callers:
  - drivers/pci/bus.c:devm_request_pci_bus_resources
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
**Symbols:**

```
ffffffff81bdb81a-ffffffff81bdb845: devm_request_resource.cold (STB_LOCAL)
ffffffff810abea0-ffffffff810abf25: devm_request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int devm_request_resource(struct device *dev, struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1510
Inline: False
Direct callers:
  - drivers/pci/bus.c:devm_request_pci_bus_resources
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
**Symbols:**

```
ffffffff81bcd90c-ffffffff81bcd937: devm_request_resource.cold (STB_LOCAL)
ffffffff810acfa0-ffffffff810ad025: devm_request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devm_request_resource(struct device *dev, struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1510
Inline: False
Direct callers:
  - drivers/pci/bus.c:devm_request_pci_bus_resources
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
**Symbols:**

```
ffffffff81ca42f4-ffffffff81ca431f: devm_request_resource.cold (STB_LOCAL)
ffffffff810beb10-ffffffff810beb9c: devm_request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devm_request_resource(struct device *dev, struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1497
Inline: False
Direct callers:
  - drivers/pci/bus.c:devm_request_pci_bus_resources
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
**Symbols:**

```
ffffffff81e53b85-ffffffff81e53bb0: devm_request_resource.cold (STB_LOCAL)
ffffffff810d5c20-ffffffff810d5cc1: devm_request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devm_request_resource(struct device *dev, struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f4dc0)
Location: kernel/resource.c:1489
Inline: False
Direct callers:
  - drivers/pci/bus.c:devm_request_pci_bus_resources
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
**Symbols:**

```
ffffffff810f4dc0-ffffffff810f4e85: devm_request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devm_request_resource(struct device *dev, struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff811011f0)
Location: kernel/resource.c:1489
Inline: False
Direct callers:
  - drivers/pci/bus.c:devm_request_pci_bus_resources
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
**Symbols:**

```
ffffffff811011f0-ffffffff811012b5: devm_request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devm_request_resource(struct device *dev, struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110a8c0)
Location: kernel/resource.c:1544
Inline: False
Direct callers:
  - drivers/pci/bus.c:devm_request_pci_bus_resources
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
**Symbols:**

```
ffffffff8110a8c0-ffffffff8110a985: devm_request_resource (STB_GLOBAL)
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
int devm_request_resource(struct device *dev, struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff800010101180)
Location: kernel/resource.c:1379
Inline: False
Direct callers:
  - drivers/pci/bus.c:devm_request_pci_bus_resources
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
**Symbols:**

```
ffff800010101180-ffff80001010122c: devm_request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devm_request_resource(struct device *dev, struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035d7e4)
Location: kernel/resource.c:1379
Inline: False
Direct callers:
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
**Symbols:**

```
c035d7e4-c035d88c: devm_request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devm_request_resource(struct device *dev, struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c0000000001488b0)
Location: kernel/resource.c:1379
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_vf_resource_shift
  - drivers/pci/bus.c:devm_request_pci_bus_resources
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
**Symbols:**

```
c0000000001488b0-c000000000148990: devm_request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devm_request_resource(struct device *dev, struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c8550)
Location: kernel/resource.c:1379
Inline: False
Direct callers:
  - drivers/pci/bus.c:devm_request_pci_bus_resources
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
**Symbols:**

```
ffffffe0000c8550-ffffffe0000c85e8: devm_request_resource (STB_GLOBAL)
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
int devm_request_resource(struct device *dev, struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1379
Inline: False
Direct callers:
  - drivers/pci/bus.c:devm_request_pci_bus_resources
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
**Symbols:**

```
ffffffff810a38a6-ffffffff810a38d1: devm_request_resource.cold (STB_LOCAL)
ffffffff810a2d50-ffffffff810a2dc2: devm_request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int devm_request_resource(struct device *dev, struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1379
Inline: False
Direct callers:
  - drivers/pci/bus.c:devm_request_pci_bus_resources
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
**Symbols:**

```
ffffffff81092286-ffffffff810922b1: devm_request_resource.cold (STB_LOCAL)
ffffffff81091730-ffffffff810917a2: devm_request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int devm_request_resource(struct device *dev, struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1379
Inline: False
Direct callers:
  - drivers/pci/bus.c:devm_request_pci_bus_resources
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
**Symbols:**

```
ffffffff810a3856-ffffffff810a3881: devm_request_resource.cold (STB_LOCAL)
ffffffff810a2d00-ffffffff810a2d72: devm_request_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int devm_request_resource(struct device *dev, struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1379
Inline: False
Direct callers:
  - drivers/pci/bus.c:devm_request_pci_bus_resources
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
**Symbols:**

```
ffffffff810ab914-ffffffff810ab93f: devm_request_resource.cold (STB_LOCAL)
ffffffff810aada0-ffffffff810aae12: devm_request_resource (STB_GLOBAL)
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
