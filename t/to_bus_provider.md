# Function: <code>to_bus_provider</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct module *to_bus_provider(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81597540)
Location: drivers/nvdimm/bus.c:68
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
**Symbols:**

```
ffffffff81597540-ffffffff81597575: to_bus_provider (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct module *to_bus_provider(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff815ed0e0)
Location: drivers/nvdimm/bus.c:64
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
**Symbols:**

```
ffffffff815ed0e0-ffffffff815ed118: to_bus_provider (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct module *to_bus_provider(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81619ed0)
Location: drivers/nvdimm/bus.c:64
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
**Symbols:**

```
ffffffff81619ed0-ffffffff81619f08: to_bus_provider (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct module *to_bus_provider(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8162df80)
Location: drivers/nvdimm/bus.c:66
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
**Symbols:**

```
ffffffff8162df80-ffffffff8162dfc4: to_bus_provider (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct module *to_bus_provider(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81696730)
Location: drivers/nvdimm/bus.c:67
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
**Symbols:**

```
ffffffff81696730-ffffffff81696774: to_bus_provider (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct module *to_bus_provider(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816d2820)
Location: drivers/nvdimm/bus.c:67
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
**Symbols:**

```
ffffffff816d2820-ffffffff816d2864: to_bus_provider (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct module *to_bus_provider(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816f3f70)
Location: drivers/nvdimm/bus.c:61
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
**Symbols:**

```
ffffffff816f3f70-ffffffff816f3fb4: to_bus_provider (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct module *to_bus_provider(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8172d580)
Location: drivers/nvdimm/bus.c:54
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
**Symbols:**

```
ffffffff8172d580-ffffffff8172d5c6: to_bus_provider (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct module *to_bus_provider(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff817517e0)
Location: drivers/nvdimm/bus.c:54
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
**Symbols:**

```
ffffffff817517e0-ffffffff81751826: to_bus_provider (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81810507)
Location: drivers/nvdimm/bus.c:54
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8181f447)
Location: drivers/nvdimm/bus.c:54
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
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
In drivers/nvdimm/bus.c (ffffffff81802767)
Location: drivers/nvdimm/bus.c:54
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
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
In drivers/nvdimm/bus.c (ffffffff8188cc47)
Location: drivers/nvdimm/bus.c:54
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
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
In drivers/nvdimm/bus.c (ffffffff819d6177)
Location: drivers/nvdimm/bus.c:51
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
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
In drivers/nvdimm/bus.c (ffffffff81b50d87)
Location: drivers/nvdimm/bus.c:51
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
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
In drivers/nvdimm/bus.c (ffffffff81ba4227)
Location: drivers/nvdimm/bus.c:51
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
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
In drivers/nvdimm/bus.c (ffffffff81bf8417)
Location: drivers/nvdimm/bus.c:51
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
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
struct module *to_bus_provider(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffff800010951ea8)
Location: drivers/nvdimm/bus.c:54
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
**Symbols:**

```
ffff800010951ea8-ffff800010951f14: to_bus_provider (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct module *to_bus_provider(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (c0000000009feae0)
Location: drivers/nvdimm/bus.c:54
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
**Symbols:**

```
c0000000009feae0-c0000000009feb6c: to_bus_provider (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct module *to_bus_provider(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffe0005c1a98)
Location: drivers/nvdimm/bus.c:54
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
**Symbols:**

```
ffffffe0005c1a98-ffffffe0005c1aec: to_bus_provider (STB_LOCAL)
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
struct module *to_bus_provider(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81705ed0)
Location: drivers/nvdimm/bus.c:54
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
**Symbols:**

```
ffffffff81705ed0-ffffffff81705f16: to_bus_provider (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct module *to_bus_provider(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816d9950)
Location: drivers/nvdimm/bus.c:54
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
**Symbols:**

```
ffffffff816d9950-ffffffff816d9996: to_bus_provider (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct module *to_bus_provider(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81744ca0)
Location: drivers/nvdimm/bus.c:54
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
**Symbols:**

```
ffffffff81744ca0-ffffffff81744ce6: to_bus_provider (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct module *to_bus_provider(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff817600e0)
Location: drivers/nvdimm/bus.c:54
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
```
**Symbols:**

```
ffffffff817600e0-ffffffff81760126: to_bus_provider (STB_LOCAL)
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
