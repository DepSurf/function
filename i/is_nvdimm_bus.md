# Function: <code>is_nvdimm_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:244
Inline: True
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
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:246
Inline: True
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
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:308
Inline: True
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
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/bus.c:309
Inline: True
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
In drivers/nvdimm/bus.c (ffffffff816d21e5)
Location: drivers/nvdimm/bus.c:312
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_match
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
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
In drivers/nvdimm/bus.c (ffffffff816f3a75)
Location: drivers/nvdimm/bus.c:306
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_match
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8172ce05)
Location: drivers/nvdimm/bus.c:305
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_match
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
```
**Symbols:**

```
ffffffff8172d480-ffffffff8172d499: is_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81751695)
Location: drivers/nvdimm/bus.c:303
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_match
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
```
**Symbols:**

```
ffffffff817516e0-ffffffff817516f9: is_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8180ff65)
Location: drivers/nvdimm/bus.c:308
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_match
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
```
**Symbols:**

```
ffffffff8180ffa0-ffffffff8180ffb6: is_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8181eea5)
Location: drivers/nvdimm/bus.c:308
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_match
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
```
**Symbols:**

```
ffffffff8181eee0-ffffffff8181eef6: is_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff818021c5)
Location: drivers/nvdimm/bus.c:307
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_match
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
```
**Symbols:**

```
ffffffff81802200-ffffffff81802216: is_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8188c685)
Location: drivers/nvdimm/bus.c:306
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_match
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
```
**Symbols:**

```
ffffffff8188c6c0-ffffffff8188c6d6: is_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff819d5b15)
Location: drivers/nvdimm/bus.c:297
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_match
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
```
**Symbols:**

```
ffffffff819d5b60-ffffffff819d5b7c: is_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81b506b5)
Location: drivers/nvdimm/bus.c:297
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_match
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
```
**Symbols:**

```
ffffffff81b50710-ffffffff81b5072c: is_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81ba3b85)
Location: drivers/nvdimm/bus.c:297
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_match
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
```
**Symbols:**

```
ffffffff81ba3be0-ffffffff81ba3bfc: is_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81bf7d75)
Location: drivers/nvdimm/bus.c:297
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_match
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
```
**Symbols:**

```
ffffffff81bf7dd0-ffffffff81bf7dec: is_nvdimm_bus (STB_GLOBAL)
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
bool is_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffff8000109516b4)
Location: drivers/nvdimm/bus.c:303
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_match
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
```
**Symbols:**

```
ffff800010951d50-ffff800010951d88: is_nvdimm_bus (STB_GLOBAL)
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
bool is_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (c0000000009fe058)
Location: drivers/nvdimm/bus.c:303
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_match
  - drivers/nvdimm/bus.c:to_nvdimm_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
```
**Symbols:**

```
c0000000009fe900-c0000000009fe92c: is_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffe0005c1922)
Location: drivers/nvdimm/bus.c:303
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_match
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
```
**Symbols:**

```
ffffffe0005c1976-ffffffe0005c19a8: is_nvdimm_bus (STB_GLOBAL)
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
bool is_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81705d85)
Location: drivers/nvdimm/bus.c:303
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_match
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
```
**Symbols:**

```
ffffffff81705dd0-ffffffff81705de9: is_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816d9805)
Location: drivers/nvdimm/bus.c:303
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_match
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
```
**Symbols:**

```
ffffffff816d9850-ffffffff816d9869: is_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81744b55)
Location: drivers/nvdimm/bus.c:303
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_match
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
```
**Symbols:**

```
ffffffff81744ba0-ffffffff81744bb9: is_nvdimm_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool is_nvdimm_bus(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8175ff95)
Location: drivers/nvdimm/bus.c:303
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_match
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_to_bus
  - drivers/nvdimm/bus.c:walk_to_nvdimm_bus
```
**Symbols:**

```
ffffffff8175ffe0-ffffffff8175fff9: is_nvdimm_bus (STB_GLOBAL)
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
