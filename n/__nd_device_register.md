# Function: <code>__nd_device_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __nd_device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81597bb0)
Location: drivers/nvdimm/bus.c:175
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nd_device_register
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_create
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
```
**Symbols:**

```
ffffffff81597bb0-ffffffff81597be6: __nd_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __nd_device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff815ed430)
Location: drivers/nvdimm/bus.c:436
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nd_device_register
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_create
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff815ed430-ffffffff815ed46c: __nd_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __nd_device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8161a240)
Location: drivers/nvdimm/bus.c:438
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nd_device_register
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_create
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff8161a240-ffffffff8161a27c: __nd_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __nd_device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8162dc72)
Location: drivers/nvdimm/bus.c:501
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_register
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_create
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff8162e360-ffffffff8162e39d: __nd_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __nd_device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81696432)
Location: drivers/nvdimm/bus.c:501
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_register
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_create
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff81696b20-ffffffff81696b5d: __nd_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __nd_device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816d2512)
Location: drivers/nvdimm/bus.c:505
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_register
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_create
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff816d2c90-ffffffff816d2ccc: __nd_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __nd_device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816f3e52)
Location: drivers/nvdimm/bus.c:522
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_register
Direct callers:
  - drivers/nvdimm/bus.c:nd_device_register
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_create
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff816f3dc0-ffffffff816f3e3d: __nd_device_register.part.21 (STB_LOCAL)
ffffffff816f43e0-ffffffff816f43f6: __nd_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __nd_device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8172d463)
Location: drivers/nvdimm/bus.c:524
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_register
Direct callers:
  - drivers/nvdimm/bus.c:nd_device_register
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_create
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff8172d3a0-ffffffff8172d449: __nd_device_register.part.0 (STB_LOCAL)
ffffffff8172d9c0-ffffffff8172d9d6: __nd_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __nd_device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81751553)
Location: drivers/nvdimm/bus.c:522
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_register
Direct callers:
  - drivers/nvdimm/bus.c:nd_device_register
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_create
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff81751490-ffffffff81751539: __nd_device_register.part.0 (STB_LOCAL)
ffffffff81751c60-ffffffff81751c76: __nd_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __nd_device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8180fd03)
Location: drivers/nvdimm/bus.c:527
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_register
Direct callers:
  - drivers/nvdimm/bus.c:nd_device_register
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_create
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff8180fc40-ffffffff8180fceb: __nd_device_register.part.0 (STB_LOCAL)
ffffffff818105c0-ffffffff818105d6: __nd_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __nd_device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8181ec43)
Location: drivers/nvdimm/bus.c:527
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_register
Direct callers:
  - drivers/nvdimm/bus.c:nd_device_register
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_create
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff8181eb80-ffffffff8181ec2b: __nd_device_register.part.0 (STB_LOCAL)
ffffffff8181f500-ffffffff8181f516: __nd_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __nd_device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81801f63)
Location: drivers/nvdimm/bus.c:524
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_register
Direct callers:
  - drivers/nvdimm/bus.c:nd_device_register
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_create
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff81801ea0-ffffffff81801f4b: __nd_device_register.part.0 (STB_LOCAL)
ffffffff81802810-ffffffff81802826: __nd_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __nd_device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8188c453)
Location: drivers/nvdimm/bus.c:517
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_register
Direct callers:
  - drivers/nvdimm/bus.c:nd_device_register
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_create
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff8188c380-ffffffff8188c438: __nd_device_register.part.0 (STB_LOCAL)
ffffffff8188ccf0-ffffffff8188cd06: __nd_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81b50e45)
Location: drivers/nvdimm/bus.c:511
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_register_sync
Direct callers:
  - drivers/nvdimm/bus.c:nd_device_register_sync
```
**Symbols:**

```
ffffffff81b502f0-ffffffff81b503c9: __nd_device_register.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81ba42e5)
Location: drivers/nvdimm/bus.c:511
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_register_sync
Direct callers:
  - drivers/nvdimm/bus.c:nd_device_register_sync
```
**Symbols:**

```
ffffffff81ba37c0-ffffffff81ba3899: __nd_device_register.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81bf84d5)
Location: drivers/nvdimm/bus.c:511
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_register_sync
Direct callers:
  - drivers/nvdimm/bus.c:nd_device_register_sync
```
**Symbols:**

```
ffffffff81bf79b0-ffffffff81bf7a89: __nd_device_register.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __nd_device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffff800010951518)
Location: drivers/nvdimm/bus.c:522
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_register
Direct callers:
  - drivers/nvdimm/bus.c:nd_device_register
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_create
```
**Symbols:**

```
ffff800010951438-ffff8000109514f8: __nd_device_register.part.0 (STB_LOCAL)
ffff8000109523a0-ffff8000109523d0: __nd_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __nd_device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (c0000000009fe6ac)
Location: drivers/nvdimm/bus.c:522
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_register
Direct callers:
  - drivers/nvdimm/bus.c:nd_device_register
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_create
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
c0000000009fe540-c0000000009fe67c: __nd_device_register.part.0 (STB_LOCAL)
c0000000009ff240-c0000000009ff25c: __nd_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __nd_device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffe0005c17ba)
Location: drivers/nvdimm/bus.c:522
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_register
Direct callers:
  - drivers/nvdimm/bus.c:nd_device_register
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_create
```
**Symbols:**

```
ffffffe0005c170e-ffffffe0005c179a: __nd_device_register.part.0 (STB_LOCAL)
ffffffe0005c1ecc-ffffffe0005c1ef8: __nd_device_register (STB_GLOBAL)
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
void __nd_device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81705c43)
Location: drivers/nvdimm/bus.c:522
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_register
Direct callers:
  - drivers/nvdimm/bus.c:nd_device_register
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_create
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff81705b80-ffffffff81705c29: __nd_device_register.part.0 (STB_LOCAL)
ffffffff81706350-ffffffff81706366: __nd_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __nd_device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816d96c3)
Location: drivers/nvdimm/bus.c:522
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_register
Direct callers:
  - drivers/nvdimm/bus.c:nd_device_register
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_create
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff816d9600-ffffffff816d96a9: __nd_device_register.part.0 (STB_LOCAL)
ffffffff816d9dd0-ffffffff816d9de6: __nd_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __nd_device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81744a13)
Location: drivers/nvdimm/bus.c:522
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_register
Direct callers:
  - drivers/nvdimm/bus.c:nd_device_register
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_create
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff81744950-ffffffff817449f9: __nd_device_register.part.0 (STB_LOCAL)
ffffffff81745120-ffffffff81745136: __nd_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __nd_device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8175fe53)
Location: drivers/nvdimm/bus.c:522
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_device_register
Direct callers:
  - drivers/nvdimm/bus.c:nd_device_register
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/btt_devs.c:nd_btt_create
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_create
```
**Symbols:**

```
ffffffff8175fd90-ffffffff8175fe39: __nd_device_register.part.0 (STB_LOCAL)
ffffffff81760560-ffffffff81760576: __nd_device_register (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
