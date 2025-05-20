# Function: <code>adjust_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int adjust_resource(struct resource *res, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81086130)
Location: kernel/resource.c:923
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
```
**Symbols:**

```
ffffffff81086130-ffffffff8108616f: adjust_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int adjust_resource(struct resource *res, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810890e0)
Location: kernel/resource.c:987
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
```
**Symbols:**

```
ffffffff810890e0-ffffffff8108911f: adjust_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int adjust_resource(struct resource *res, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108e030)
Location: kernel/resource.c:987
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
```
**Symbols:**

```
ffffffff8108e030-ffffffff8108e06f: adjust_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int adjust_resource(struct resource *res, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108b0a0)
Location: kernel/resource.c:987
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
```
**Symbols:**

```
ffffffff8108b0a0-ffffffff8108b0df: adjust_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int adjust_resource(struct resource *res, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81091d80)
Location: kernel/resource.c:1005
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
```
**Symbols:**

```
ffffffff81091d80-ffffffff81091dbf: adjust_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int adjust_resource(struct resource *res, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81095910)
Location: kernel/resource.c:974
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
```
**Symbols:**

```
ffffffff81095910-ffffffff8109594f: adjust_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int adjust_resource(struct resource *res, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109dc90)
Location: kernel/resource.c:968
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
```
**Symbols:**

```
ffffffff8109dc90-ffffffff8109dccf: adjust_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int adjust_resource(struct resource *res, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a20e0)
Location: kernel/resource.c:982
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
```
**Symbols:**

```
ffffffff810a20e0-ffffffff810a2121: adjust_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int adjust_resource(struct resource *res, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a86a0)
Location: kernel/resource.c:982
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
```
**Symbols:**

```
ffffffff810a86a0-ffffffff810a86e1: adjust_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int adjust_resource(struct resource *res, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810afea0)
Location: kernel/resource.c:982
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_free
```
**Symbols:**

```
ffffffff810afea0-ffffffff810afee1: adjust_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int adjust_resource(struct resource *res, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ab5e0)
Location: kernel/resource.c:989
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/dax/bus.c:adjust_dev_dax_range
```
**Symbols:**

```
ffffffff810ab5e0-ffffffff810ab621: adjust_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int adjust_resource(struct resource *res, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ac7f0)
Location: kernel/resource.c:981
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/dax/bus.c:adjust_dev_dax_range
```
**Symbols:**

```
ffffffff810ac7f0-ffffffff810ac831: adjust_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int adjust_resource(struct resource *res, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810be370)
Location: kernel/resource.c:981
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/dax/bus.c:adjust_dev_dax_range
```
**Symbols:**

```
ffffffff810be370-ffffffff810be3b1: adjust_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int adjust_resource(struct resource *res, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d54c0)
Location: kernel/resource.c:968
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/dax/bus.c:adjust_dev_dax_range
```
**Symbols:**

```
ffffffff810d54c0-ffffffff810d5512: adjust_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int adjust_resource(struct resource *res, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f4490)
Location: kernel/resource.c:976
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/dax/bus.c:adjust_dev_dax_range
```
**Symbols:**

```
ffffffff810f4490-ffffffff810f44e2: adjust_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int adjust_resource(struct resource *res, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff811008c0)
Location: kernel/resource.c:976
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/dax/bus.c:adjust_dev_dax_range
```
**Symbols:**

```
ffffffff811008c0-ffffffff81100912: adjust_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int adjust_resource(struct resource *res, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110a1f0)
Location: kernel/resource.c:1031
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/nvdimm/namespace_devs.c:merge_dpa
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_free
  - drivers/dax/bus.c:adjust_dev_dax_range
```
**Symbols:**

```
ffffffff8110a1f0-ffffffff8110a242: adjust_resource (STB_GLOBAL)
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
int adjust_resource(struct resource *res, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff800010100570)
Location: kernel/resource.c:982
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
```
**Symbols:**

```
ffff800010100570-ffff8000101006bc: adjust_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int adjust_resource(struct resource *res, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035c66c)
Location: kernel/resource.c:982
Inline: False
Direct callers:
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pinctrl_probe
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/memory/omap-gpmc.c:gpmc_cs_request
```
**Symbols:**

```
c035c66c-c035c76c: adjust_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int adjust_resource(struct resource *res, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c000000000147110)
Location: kernel/resource.c:982
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
```
**Symbols:**

```
c000000000147110-c000000000147180: adjust_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int adjust_resource(struct resource *res, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c773c)
Location: kernel/resource.c:982
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
```
**Symbols:**

```
ffffffe0000c773c-ffffffe0000c77e2: adjust_resource (STB_GLOBAL)
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
int adjust_resource(struct resource *res, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a1fc0)
Location: kernel/resource.c:982
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
```
**Symbols:**

```
ffffffff810a1fc0-ffffffff810a2001: adjust_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int adjust_resource(struct resource *res, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810909a0)
Location: kernel/resource.c:982
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
```
**Symbols:**

```
ffffffff810909a0-ffffffff810909e1: adjust_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int adjust_resource(struct resource *res, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a1f70)
Location: kernel/resource.c:982
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
```
**Symbols:**

```
ffffffff810a1f70-ffffffff810a1fb1: adjust_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int adjust_resource(struct resource *res, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a9fd0)
Location: kernel/resource.c:982
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
  - drivers/nvdimm/namespace_devs.c:scan_allocate
```
**Symbols:**

```
ffffffff810a9fd0-ffffffff810aa01c: adjust_resource (STB_GLOBAL)
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
