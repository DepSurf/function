# Function: <code>to_nvdimm_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvdimm_bus *to_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81596ce0)
Location: drivers/nvdimm/core.c:84
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:provider_show
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/core.c:walk_to_nvdimm_bus
Direct callers:
  - drivers/nvdimm/core.c:provider_show
  - drivers/nvdimm/core.c:commands_show
```
**Symbols:**

```
ffffffff81596ce0-ffffffff81596cfc: to_nvdimm_bus.part.3 (STB_LOCAL)
ffffffff81596d00-ffffffff81596d2c: to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvdimm_bus *to_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff815ecc22)
Location: drivers/nvdimm/bus.c:262
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
Direct callers:
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:provider_show
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff815ecbc0-ffffffff815ecbdc: to_nvdimm_bus.part.12 (STB_LOCAL)
ffffffff815ecbe0-ffffffff815ecc0e: to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvdimm_bus *to_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81619a12)
Location: drivers/nvdimm/bus.c:264
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
Direct callers:
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:provider_show
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff816199b0-ffffffff816199cc: to_nvdimm_bus.part.14 (STB_LOCAL)
ffffffff816199d0-ffffffff816199fe: to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvdimm_bus *to_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8162da09)
Location: drivers/nvdimm/bus.c:326
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
Direct callers:
  - drivers/nvdimm/core.c:provider_show
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff8162d9b0-ffffffff8162d9bd: to_nvdimm_bus.part.14 (STB_LOCAL)
ffffffff8162d9c0-ffffffff8162d9ef: to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvdimm_bus *to_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816961c9)
Location: drivers/nvdimm/bus.c:327
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
Direct callers:
  - drivers/nvdimm/core.c:provider_show
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff81696170-ffffffff8169617d: to_nvdimm_bus.part.14 (STB_LOCAL)
ffffffff81696180-ffffffff816961af: to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvdimm_bus *to_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816d22a5)
Location: drivers/nvdimm/bus.c:330
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
Direct callers:
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:provider_show
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/bus.c:nd_bus_remove
```
**Symbols:**

```
ffffffff816d2260-ffffffff816d226d: to_nvdimm_bus.part.16 (STB_LOCAL)
ffffffff816d2270-ffffffff816d229e: to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvdimm_bus *to_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816f3715)
Location: drivers/nvdimm/bus.c:324
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
Direct callers:
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:provider_show
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
```
**Symbols:**

```
ffffffff816f3690-ffffffff816f369d: to_nvdimm_bus.part.13 (STB_LOCAL)
ffffffff816f36a0-ffffffff816f36ce: to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvdimm_bus *to_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8172d088)
Location: drivers/nvdimm/bus.c:323
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
Direct callers:
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:provider_show
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
```
**Symbols:**

```
ffffffff8172e794-ffffffff8172e7ad: to_nvdimm_bus.part.0 (STB_LOCAL)
ffffffff8172e7ad-ffffffff8172e7bf: to_nvdimm_bus.cold (STB_LOCAL)
ffffffff8172d000-ffffffff8172d024: to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvdimm_bus *to_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff817510c8)
Location: drivers/nvdimm/bus.c:321
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
Direct callers:
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:provider_show
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
```
**Symbols:**

```
ffffffff81751020-ffffffff8175102d: to_nvdimm_bus.part.0 (STB_LOCAL)
ffffffff81751030-ffffffff8175105e: to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct nvdimm_bus *to_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8180f998)
Location: drivers/nvdimm/bus.c:326
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
Direct callers:
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:provider_show
  - drivers/nvdimm/core.c:commands_show
```
**Symbols:**

```
ffffffff8180fc20-ffffffff8180fc3d: to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct nvdimm_bus *to_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8181e8d8)
Location: drivers/nvdimm/bus.c:326
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
Direct callers:
  - drivers/nvdimm/core.c:nvdimm_bus_firmware_visible
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_show
  - drivers/nvdimm/core.c:capability_show
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:provider_show
  - drivers/nvdimm/core.c:commands_show
```
**Symbols:**

```
ffffffff8181eb60-ffffffff8181eb7d: to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct nvdimm_bus *to_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81801c48)
Location: drivers/nvdimm/bus.c:325
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
Direct callers:
  - drivers/nvdimm/core.c:nvdimm_bus_firmware_visible
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_show
  - drivers/nvdimm/core.c:capability_show
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:provider_show
  - drivers/nvdimm/core.c:commands_show
```
**Symbols:**

```
ffffffff81801e80-ffffffff81801e9d: to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct nvdimm_bus *to_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8188c148)
Location: drivers/nvdimm/bus.c:324
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
Direct callers:
  - drivers/nvdimm/core.c:nvdimm_bus_firmware_visible
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_show
  - drivers/nvdimm/core.c:capability_show
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:provider_show
  - drivers/nvdimm/core.c:commands_show
```
**Symbols:**

```
ffffffff8188b980-ffffffff8188b99d: to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct nvdimm_bus *to_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff819d54d8)
Location: drivers/nvdimm/bus.c:315
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
Direct callers:
  - drivers/nvdimm/core.c:nvdimm_bus_firmware_visible
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_show
  - drivers/nvdimm/core.c:capability_show
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:provider_show
  - drivers/nvdimm/core.c:commands_show
```
**Symbols:**

```
ffffffff819d4db0-ffffffff819d4dd9: to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct nvdimm_bus *to_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81b4ff78)
Location: drivers/nvdimm/bus.c:315
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
Direct callers:
  - drivers/nvdimm/core.c:nvdimm_bus_firmware_visible
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_show
  - drivers/nvdimm/core.c:capability_show
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:provider_show
  - drivers/nvdimm/core.c:commands_show
```
**Symbols:**

```
ffffffff81b4f710-ffffffff81b4f739: to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct nvdimm_bus *to_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81ba3448)
Location: drivers/nvdimm/bus.c:315
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
Direct callers:
  - drivers/nvdimm/core.c:nvdimm_bus_firmware_visible
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_show
  - drivers/nvdimm/core.c:capability_show
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:provider_show
  - drivers/nvdimm/core.c:commands_show
```
**Symbols:**

```
ffffffff81ba2cd0-ffffffff81ba2cf9: to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct nvdimm_bus *to_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81bf7638)
Location: drivers/nvdimm/bus.c:315
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
Direct callers:
  - drivers/nvdimm/core.c:nvdimm_bus_firmware_visible
  - drivers/nvdimm/core.c:activate_store
  - drivers/nvdimm/core.c:activate_show
  - drivers/nvdimm/core.c:capability_show
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:provider_show
  - drivers/nvdimm/core.c:commands_show
```
**Symbols:**

```
ffffffff81bf6e90-ffffffff81bf6eb9: to_nvdimm_bus (STB_GLOBAL)
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
struct nvdimm_bus *to_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffff800010951a5c)
Location: drivers/nvdimm/bus.c:321
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
Direct callers:
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:provider_show
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
```
**Symbols:**

```
ffff8000109512b0-ffff8000109512cc: to_nvdimm_bus.part.0 (STB_LOCAL)
ffff8000109512d0-ffff800010951324: to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct nvdimm_bus *to_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (c0000000009fd3e0)
Location: drivers/nvdimm/bus.c:321
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:provider_show
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/bus.c:nd_bus_probe
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
```
**Symbols:**

```
c0000000009fd3e0-c0000000009fd414: to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvdimm_bus *to_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffe0005c1366)
Location: drivers/nvdimm/bus.c:321
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
Direct callers:
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:provider_show
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
```
**Symbols:**

```
ffffffe0005c128e-ffffffe0005c12aa: to_nvdimm_bus.part.0 (STB_LOCAL)
ffffffe0005c12aa-ffffffe0005c12f8: to_nvdimm_bus (STB_GLOBAL)
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
struct nvdimm_bus *to_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff817057b8)
Location: drivers/nvdimm/bus.c:321
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
Direct callers:
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:provider_show
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
```
**Symbols:**

```
ffffffff81705710-ffffffff8170571d: to_nvdimm_bus.part.0 (STB_LOCAL)
ffffffff81705720-ffffffff8170574e: to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvdimm_bus *to_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816d9238)
Location: drivers/nvdimm/bus.c:321
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
Direct callers:
  - drivers/acpi/nfit/core.c:nfit_visible
  - drivers/acpi/nfit/core.c:hw_error_scrub_show
  - drivers/acpi/nfit/core.c:revision_show
  - drivers/acpi/nfit/core.c:bus_dsm_mask_show
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:provider_show
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
```
**Symbols:**

```
ffffffff816d9190-ffffffff816d919d: to_nvdimm_bus.part.0 (STB_LOCAL)
ffffffff816d91a0-ffffffff816d91ce: to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvdimm_bus *to_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81744588)
Location: drivers/nvdimm/bus.c:321
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
Direct callers:
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:provider_show
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
```
**Symbols:**

```
ffffffff817444e0-ffffffff817444ed: to_nvdimm_bus.part.0 (STB_LOCAL)
ffffffff817444f0-ffffffff8174451e: to_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvdimm_bus *to_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8175f9d8)
Location: drivers/nvdimm/bus.c:321
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
Direct callers:
  - drivers/nvdimm/core.c:wait_probe_show
  - drivers/nvdimm/core.c:provider_show
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
```
**Symbols:**

```
ffffffff8175f930-ffffffff8175f93d: to_nvdimm_bus.part.0 (STB_LOCAL)
ffffffff8175f940-ffffffff8175f96e: to_nvdimm_bus (STB_GLOBAL)
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
