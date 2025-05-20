# Function: <code>pinctrl_unregister_mappings</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pinctrl_unregister_mappings(const struct pinctrl_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff816018f0)
Location: drivers/pinctrl/core.c:1457
Inline: False
```
**Symbols:**

```
ffffffff816018f0-ffffffff81601972: pinctrl_unregister_mappings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pinctrl_unregister_mappings(const struct pinctrl_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81626750)
Location: drivers/pinctrl/core.c:1458
Inline: False
```
**Symbols:**

```
ffffffff81626750-ffffffff816267d2: pinctrl_unregister_mappings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pinctrl_unregister_mappings(const struct pinctrl_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8160a1e0)
Location: drivers/pinctrl/core.c:1481
Inline: False
```
**Symbols:**

```
ffffffff8160a1e0-ffffffff8160a262: pinctrl_unregister_mappings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pinctrl_unregister_mappings(const struct pinctrl_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81678e60)
Location: drivers/pinctrl/core.c:1481
Inline: False
```
**Symbols:**

```
ffffffff81678e60-ffffffff81678ee2: pinctrl_unregister_mappings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pinctrl_unregister_mappings(const struct pinctrl_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81794d10)
Location: drivers/pinctrl/core.c:1481
Inline: True
```
**Symbols:**

```
ffffffff81794d10-ffffffff81794da6: pinctrl_unregister_mappings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pinctrl_unregister_mappings(const struct pinctrl_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff818aa100)
Location: drivers/pinctrl/core.c:1481
Inline: True
```
**Symbols:**

```
ffffffff818aa100-ffffffff818aa196: pinctrl_unregister_mappings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pinctrl_unregister_mappings(const struct pinctrl_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff818ed190)
Location: drivers/pinctrl/core.c:1485
Inline: True
```
**Symbols:**

```
ffffffff818ed190-ffffffff818ed226: pinctrl_unregister_mappings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pinctrl_unregister_mappings(const struct pinctrl_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81934590)
Location: drivers/pinctrl/core.c:1499
Inline: True
```
**Symbols:**

```
ffffffff81934590-ffffffff81934626: pinctrl_unregister_mappings (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
