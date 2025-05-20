# Function: <code>mmc_regulator_get_ocrmask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int mmc_regulator_get_ocrmask(struct regulator *supply);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816be940)
Location: drivers/mmc/core/core.c:1322
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff816be940-ffffffff816be9fd: mmc_regulator_get_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int mmc_regulator_get_ocrmask(struct regulator *supply);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817212f0)
Location: drivers/mmc/core/core.c:1338
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff817212f0-ffffffff817213b5: mmc_regulator_get_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int mmc_regulator_get_ocrmask(struct regulator *supply);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81753b70)
Location: drivers/mmc/core/core.c:1410
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff81753b70-ffffffff81753c35: mmc_regulator_get_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int mmc_regulator_get_ocrmask(struct regulator *supply);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81771840)
Location: drivers/mmc/core/core.c:1242
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff81771840-ffffffff817718f3: mmc_regulator_get_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int mmc_regulator_get_ocrmask(struct regulator *supply);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817e7750)
Location: drivers/mmc/core/core.c:1436
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff817e7750-ffffffff817e7803: mmc_regulator_get_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int mmc_regulator_get_ocrmask(struct regulator *supply);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81830970)
Location: drivers/mmc/core/core.c:1235
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff81830970-ffffffff81830a1c: mmc_regulator_get_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int mmc_regulator_get_ocrmask(struct regulator *supply);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185cbf0)
Location: drivers/mmc/core/core.c:1238
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff8185cbf0-ffffffff8185cc9c: mmc_regulator_get_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/regulator.c (ffffffff818b12ac)
Location: drivers/mmc/core/regulator.c:61
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/regulator.c (ffffffff818e374c)
Location: drivers/mmc/core/regulator.c:61
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
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
In drivers/mmc/core/regulator.c (ffffffff819b6853)
Location: drivers/mmc/core/regulator.c:61
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
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
In drivers/mmc/core/regulator.c (ffffffff819b8d93)
Location: drivers/mmc/core/regulator.c:61
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
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
In drivers/mmc/core/regulator.c (ffffffff8199d4c3)
Location: drivers/mmc/core/regulator.c:61
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
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
In drivers/mmc/core/regulator.c (ffffffff81a49e33)
Location: drivers/mmc/core/regulator.c:61
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
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
In drivers/mmc/core/regulator.c (ffffffff81bb8283)
Location: drivers/mmc/core/regulator.c:61
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
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
In drivers/mmc/core/regulator.c (ffffffff81d5cf83)
Location: drivers/mmc/core/regulator.c:61
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
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
In drivers/mmc/core/regulator.c (ffffffff81dc7b43)
Location: drivers/mmc/core/regulator.c:61
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
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
In drivers/mmc/core/regulator.c (ffffffff81e804a3)
Location: drivers/mmc/core/regulator.c:61
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/regulator.c (ffff800010b3e13c)
Location: drivers/mmc/core/regulator.c:61
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/regulator.c (c0c186a4)
Location: drivers/mmc/core/regulator.c:61
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/regulator.c (c000000000c3ba9c)
Location: drivers/mmc/core/regulator.c:61
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/regulator.c (ffffffe0007150ee)
Location: drivers/mmc/core/regulator.c:61
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/regulator.c (ffffffff8188710c)
Location: drivers/mmc/core/regulator.c:61
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/regulator.c (ffffffff818d85ac)
Location: drivers/mmc/core/regulator.c:61
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/regulator.c (ffffffff818f50cc)
Location: drivers/mmc/core/regulator.c:61
Inline: True
Inline callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
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
</ul>
