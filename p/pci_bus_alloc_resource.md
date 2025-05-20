# Function: <code>pci_bus_alloc_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_alloc_resource(struct pci_bus *bus, struct resource *res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8142f4e0)
Location: drivers/pci/bus.c:196
Inline: True
Direct callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/char/agp/intel-gtt.c:intel_alloc_chipset_flush_resource
```
**Symbols:**

```
ffffffff8142f4e0-ffffffff8142f597: pci_bus_alloc_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_alloc_resource(struct pci_bus *bus, struct resource *res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8147ab60)
Location: drivers/pci/bus.c:225
Inline: True
Direct callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/char/agp/intel-gtt.c:intel_alloc_chipset_flush_resource
```
**Symbols:**

```
ffffffff8147ab60-ffffffff8147ac13: pci_bus_alloc_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_alloc_resource(struct pci_bus *bus, struct resource *res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8149bfe0)
Location: drivers/pci/bus.c:225
Inline: True
Direct callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/char/agp/intel-gtt.c:intel_alloc_chipset_flush_resource
```
**Symbols:**

```
ffffffff8149bfe0-ffffffff8149c093: pci_bus_alloc_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_alloc_resource(struct pci_bus *bus, struct resource *res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff814a5da0)
Location: drivers/pci/bus.c:225
Inline: True
Direct callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/char/agp/intel-gtt.c:intel_alloc_chipset_flush_resource
```
**Symbols:**

```
ffffffff814a5da0-ffffffff814a5e39: pci_bus_alloc_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_alloc_resource(struct pci_bus *bus, struct resource *res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff814e4be0)
Location: drivers/pci/bus.c:225
Inline: True
Direct callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/char/agp/intel-gtt.c:intel_alloc_chipset_flush_resource
```
**Symbols:**

```
ffffffff814e4be0-ffffffff814e4c79: pci_bus_alloc_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_alloc_resource(struct pci_bus *bus, struct resource *res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff815140c0)
Location: drivers/pci/bus.c:224
Inline: True
Direct callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/char/agp/intel-gtt.c:intel_alloc_chipset_flush_resource
```
**Symbols:**

```
ffffffff815140c0-ffffffff81514159: pci_bus_alloc_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_alloc_resource(struct pci_bus *bus, struct resource *res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81529820)
Location: drivers/pci/bus.c:224
Inline: True
Direct callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/char/agp/intel-gtt.c:intel_alloc_chipset_flush_resource
```
**Symbols:**

```
ffffffff81529820-ffffffff815298b9: pci_bus_alloc_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_alloc_resource(struct pci_bus *bus, struct resource *res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81558aa0)
Location: drivers/pci/bus.c:224
Inline: True
Direct callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/char/agp/intel-gtt.c:intel_alloc_chipset_flush_resource
```
**Symbols:**

```
ffffffff81558aa0-ffffffff81558b35: pci_bus_alloc_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_alloc_resource(struct pci_bus *bus, struct resource *res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8157a030)
Location: drivers/pci/bus.c:224
Inline: True
Direct callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/char/agp/intel-gtt.c:intel_alloc_chipset_flush_resource
```
**Symbols:**

```
ffffffff8157a030-ffffffff8157a0c5: pci_bus_alloc_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_bus_alloc_resource(struct pci_bus *bus, struct resource *res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8161f0b0)
Location: drivers/pci/bus.c:224
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:__pci_assign_resource
  - drivers/pci/setup-res.c:__pci_assign_resource
  - drivers/pci/setup-res.c:__pci_assign_resource
  - drivers/char/agp/intel-gtt.c:intel_i9xx_setup_flush
  - drivers/char/agp/intel-gtt.c:intel_i965_g33_setup_chipset_flush
```
**Symbols:**

```
ffffffff8161f0b0-ffffffff8161f145: pci_bus_alloc_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_bus_alloc_resource(struct pci_bus *bus, struct resource *res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff816458a0)
Location: drivers/pci/bus.c:224
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:__pci_assign_resource
  - drivers/pci/setup-res.c:__pci_assign_resource
  - drivers/pci/setup-res.c:__pci_assign_resource
  - drivers/char/agp/intel-gtt.c:intel_i9xx_setup_flush
  - drivers/char/agp/intel-gtt.c:intel_i965_g33_setup_chipset_flush
```
**Symbols:**

```
ffffffff816458a0-ffffffff81645935: pci_bus_alloc_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_bus_alloc_resource(struct pci_bus *bus, struct resource *res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff816285e0)
Location: drivers/pci/bus.c:224
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
```
**Symbols:**

```
ffffffff816285e0-ffffffff81628675: pci_bus_alloc_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_bus_alloc_resource(struct pci_bus *bus, struct resource *res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81697f30)
Location: drivers/pci/bus.c:224
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
```
**Symbols:**

```
ffffffff81697f30-ffffffff81697fc5: pci_bus_alloc_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_bus_alloc_resource(struct pci_bus *bus, struct resource *res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff817b91c0)
Location: drivers/pci/bus.c:224
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
```
**Symbols:**

```
ffffffff817b91c0-ffffffff817b927b: pci_bus_alloc_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_bus_alloc_resource(struct pci_bus *bus, struct resource *res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff818d3ce0)
Location: drivers/pci/bus.c:228
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
```
**Symbols:**

```
ffffffff818d3ce0-ffffffff818d3d9b: pci_bus_alloc_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_bus_alloc_resource(struct pci_bus *bus, struct resource *res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81916e10)
Location: drivers/pci/bus.c:250
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
```
**Symbols:**

```
ffffffff81916e10-ffffffff81916ecb: pci_bus_alloc_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_bus_alloc_resource(struct pci_bus *bus, struct resource *res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8195eee0)
Location: drivers/pci/bus.c:250
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/char/agp/intel-gtt.c:i9xx_setup
  - drivers/char/agp/intel-gtt.c:i9xx_setup
```
**Symbols:**

```
ffffffff8195eee0-ffffffff8195ef9b: pci_bus_alloc_resource (STB_GLOBAL)
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
int pci_bus_alloc_resource(struct pci_bus *bus, struct resource *res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffff8000106dc868)
Location: drivers/pci/bus.c:224
Inline: True
Direct callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
```
**Symbols:**

```
ffff8000106dc868-ffff8000106dc9a8: pci_bus_alloc_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_bus_alloc_resource(struct pci_bus *bus, struct resource *res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (c087841c)
Location: drivers/pci/bus.c:224
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
```
**Symbols:**

```
c087841c-c08785cc: pci_bus_alloc_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_alloc_resource(struct pci_bus *bus, struct resource *res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (c0000000008548b0)
Location: drivers/pci/bus.c:224
Inline: True
Direct callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
```
**Symbols:**

```
c0000000008548b0-c0000000008549c0: pci_bus_alloc_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_alloc_resource(struct pci_bus *bus, struct resource *res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffe0004b4dc2)
Location: drivers/pci/bus.c:224
Inline: True
Direct callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
```
**Symbols:**

```
ffffffe0004b4dc2-ffffffe0004b4e66: pci_bus_alloc_resource (STB_GLOBAL)
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
int pci_bus_alloc_resource(struct pci_bus *bus, struct resource *res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8156e550)
Location: drivers/pci/bus.c:224
Inline: True
Direct callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/char/agp/intel-gtt.c:intel_alloc_chipset_flush_resource
```
**Symbols:**

```
ffffffff8156e550-ffffffff8156e5e5: pci_bus_alloc_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_alloc_resource(struct pci_bus *bus, struct resource *res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8155ccb0)
Location: drivers/pci/bus.c:224
Inline: True
Direct callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/char/agp/intel-gtt.c:intel_alloc_chipset_flush_resource
```
**Symbols:**

```
ffffffff8155ccb0-ffffffff8155cd45: pci_bus_alloc_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_alloc_resource(struct pci_bus *bus, struct resource *res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8156dd80)
Location: drivers/pci/bus.c:224
Inline: True
Direct callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/char/agp/intel-gtt.c:intel_alloc_chipset_flush_resource
```
**Symbols:**

```
ffffffff8156dd80-ffffffff8156de15: pci_bus_alloc_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pci_bus_alloc_resource(struct pci_bus *bus, struct resource *res, resource_size_t size, resource_size_t align, resource_size_t min, long unsigned int type_mask, resource_size_t (*alignf)(void *, const struct resource *, resource_size_t, resource_size_t), void *alignf_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81588260)
Location: drivers/pci/bus.c:224
Inline: True
Direct callers:
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/pci/setup-res.c:_pci_assign_resource
  - drivers/char/agp/intel-gtt.c:intel_alloc_chipset_flush_resource
```
**Symbols:**

```
ffffffff81588260-ffffffff815882f5: pci_bus_alloc_resource (STB_GLOBAL)
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
