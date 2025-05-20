# Function: <code>pinctrl_register_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pinctrl_register_map(const struct pinctrl_map *maps, unsigned int num_maps, bool dup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8141f150)
Location: drivers/pinctrl/core.c:1114
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register_mappings
```
**Symbols:**

```
ffffffff8141f150-ffffffff8141f36f: pinctrl_register_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pinctrl_register_map(const struct pinctrl_map *maps, unsigned int num_maps, bool dup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81467900)
Location: drivers/pinctrl/core.c:1127
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register_mappings
```
**Symbols:**

```
ffffffff81467900-ffffffff81467b01: pinctrl_register_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pinctrl_register_map(const struct pinctrl_map *maps, unsigned int num_maps, bool dup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81486be0)
Location: drivers/pinctrl/core.c:1127
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register_mappings
```
**Symbols:**

```
ffffffff81486be0-ffffffff81486de1: pinctrl_register_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pinctrl_register_map(const struct pinctrl_map *maps, unsigned int num_maps, bool dup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814904b0)
Location: drivers/pinctrl/core.c:1324
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register_mappings
```
**Symbols:**

```
ffffffff814904b0-ffffffff814906a8: pinctrl_register_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pinctrl_register_map(const struct pinctrl_map *maps, unsigned int num_maps, bool dup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814cc690)
Location: drivers/pinctrl/core.c:1334
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register_mappings
```
**Symbols:**

```
ffffffff814cc690-ffffffff814cc87c: pinctrl_register_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int pinctrl_register_map(const struct pinctrl_map *maps, unsigned int num_maps, bool dup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1334
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register_mappings
```
**Symbols:**

```
ffffffff814fd953-ffffffff814fd9be: pinctrl_register_map.cold.23 (STB_LOCAL)
ffffffff814fd640-ffffffff814fd7dc: pinctrl_register_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int pinctrl_register_map(const struct pinctrl_map *maps, unsigned int num_maps, bool dup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1362
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register_mappings
```
**Symbols:**

```
ffffffff815123c3-ffffffff8151242e: pinctrl_register_map.cold.22 (STB_LOCAL)
ffffffff815120b0-ffffffff8151224c: pinctrl_register_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pinctrl_register_map(const struct pinctrl_map *maps, unsigned int num_maps, bool dup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1351
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register_mappings
```
**Symbols:**

```
ffffffff81540aeb-ffffffff81540b4f: pinctrl_register_map.cold (STB_LOCAL)
ffffffff81540620-ffffffff81540798: pinctrl_register_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pinctrl_register_map(const struct pinctrl_map *maps, unsigned int num_maps, bool dup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1379
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register_mappings
```
**Symbols:**

```
ffffffff81561947-ffffffff815619ab: pinctrl_register_map.cold (STB_LOCAL)
ffffffff815614f0-ffffffff81561668: pinctrl_register_map (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int pinctrl_register_map(const struct pinctrl_map *maps, unsigned int num_maps, bool dup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffff80001068e1d8)
Location: drivers/pinctrl/core.c:1379
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register_mappings
  - drivers/pinctrl/devicetree.c:dt_remember_or_free_map
```
**Symbols:**

```
ffff80001068e1d8-ffff80001068e3c0: pinctrl_register_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pinctrl_register_map(const struct pinctrl_map *maps, unsigned int num_maps, bool dup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c08301b8)
Location: drivers/pinctrl/core.c:1379
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register_mappings
  - drivers/pinctrl/devicetree.c:dt_remember_or_free_map
```
**Symbols:**

```
c08301b8-c08303a8: pinctrl_register_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pinctrl_register_map(const struct pinctrl_map *maps, unsigned int num_maps, bool dup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c000000000828a30)
Location: drivers/pinctrl/core.c:1379
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register_mappings
  - drivers/pinctrl/devicetree.c:dt_remember_or_free_map
```
**Symbols:**

```
c000000000828a30-c000000000828cb8: pinctrl_register_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pinctrl_register_map(const struct pinctrl_map *maps, unsigned int num_maps, bool dup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffe00049a234)
Location: drivers/pinctrl/core.c:1379
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register_mappings
  - drivers/pinctrl/devicetree.c:dt_remember_or_free_map
```
**Symbols:**

```
ffffffe00049a234-ffffffe00049a402: pinctrl_register_map (STB_GLOBAL)
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
int pinctrl_register_map(const struct pinctrl_map *maps, unsigned int num_maps, bool dup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1379
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register_mappings
```
**Symbols:**

```
ffffffff81559f37-ffffffff81559f9b: pinctrl_register_map.cold (STB_LOCAL)
ffffffff81559ae0-ffffffff81559c58: pinctrl_register_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pinctrl_register_map(const struct pinctrl_map *maps, unsigned int num_maps, bool dup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1379
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register_mappings
```
**Symbols:**

```
ffffffff8154a3f7-ffffffff8154a45b: pinctrl_register_map.cold (STB_LOCAL)
ffffffff81549fa0-ffffffff8154a118: pinctrl_register_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pinctrl_register_map(const struct pinctrl_map *maps, unsigned int num_maps, bool dup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1379
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register_mappings
```
**Symbols:**

```
ffffffff81555c77-ffffffff81555cdb: pinctrl_register_map.cold (STB_LOCAL)
ffffffff81555820-ffffffff81555998: pinctrl_register_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pinctrl_register_map(const struct pinctrl_map *maps, unsigned int num_maps, bool dup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1379
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register_mappings
```
**Symbols:**

```
ffffffff8156fb07-ffffffff8156fb6b: pinctrl_register_map.cold (STB_LOCAL)
ffffffff8156f6b0-ffffffff8156f828: pinctrl_register_map (STB_GLOBAL)
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
