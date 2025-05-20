# Function: <code>phy_lookup_setting</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const struct phy_setting *phy_lookup_setting(int speed, int duplex, u32 features, bool exact);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8168dbb0)
Location: drivers/net/phy/phy.c:285
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start_aneg_priv
```
**Symbols:**

```
ffffffff8168dbb0-ffffffff8168dc24: phy_lookup_setting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const struct phy_setting *phy_lookup_setting(int speed, int duplex, const long unsigned int *mask, size_t maxbit, bool exact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff816f9580)
Location: drivers/net/phy/phy-core.c:146
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start_aneg_priv
```
**Symbols:**

```
ffffffff816f9580-ffffffff816f9604: phy_lookup_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const struct phy_setting *phy_lookup_setting(int speed, int duplex, const long unsigned int *mask, size_t maxbit, bool exact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81736810)
Location: drivers/net/phy/phy-core.c:146
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start_aneg_priv
```
**Symbols:**

```
ffffffff81736810-ffffffff81736892: phy_lookup_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const struct phy_setting *phy_lookup_setting(int speed, int duplex, const long unsigned int *mask, bool exact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81759980)
Location: drivers/net/phy/phy-core.c:299
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
ffffffff81759980-ffffffff81759a3d: phy_lookup_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const struct phy_setting *phy_lookup_setting(int speed, int duplex, const long unsigned int *mask, bool exact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81796850)
Location: drivers/net/phy/phy-core.c:164
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
ffffffff81796850-ffffffff817968dc: phy_lookup_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const struct phy_setting *phy_lookup_setting(int speed, int duplex, const long unsigned int *mask, bool exact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817ba2d0)
Location: drivers/net/phy/phy-core.c:164
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
ffffffff817ba2d0-ffffffff817ba35c: phy_lookup_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const struct phy_setting *phy_lookup_setting(int speed, int duplex, const long unsigned int *mask, bool exact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81881dd0)
Location: drivers/net/phy/phy-core.c:172
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
ffffffff81881dd0-ffffffff81881e6d: phy_lookup_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const struct phy_setting *phy_lookup_setting(int speed, int duplex, const long unsigned int *mask, bool exact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81890430)
Location: drivers/net/phy/phy-core.c:199
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
ffffffff81890430-ffffffff818904d0: phy_lookup_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct phy_setting *phy_lookup_setting(int speed, int duplex, const long unsigned int *mask, bool exact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81872cf0)
Location: drivers/net/phy/phy-core.c:199
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
ffffffff81872cf0-ffffffff81872d8e: phy_lookup_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const struct phy_setting *phy_lookup_setting(int speed, int duplex, const long unsigned int *mask, bool exact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81903420)
Location: drivers/net/phy/phy-core.c:200
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:_phy_start_aneg
```
**Symbols:**

```
ffffffff81903420-ffffffff819034be: phy_lookup_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct phy_setting *phy_lookup_setting(int speed, int duplex, const long unsigned int *mask, bool exact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81a55810)
Location: drivers/net/phy/phy-core.c:201
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:_phy_start_aneg
```
**Symbols:**

```
ffffffff81a55810-ffffffff81a558d8: phy_lookup_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct phy_setting *phy_lookup_setting(int speed, int duplex, const long unsigned int *mask, bool exact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81bdf220)
Location: drivers/net/phy/phy-core.c:284
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:_phy_start_aneg
```
**Symbols:**

```
ffffffff81bdf220-ffffffff81bdf2e8: phy_lookup_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct phy_setting *phy_lookup_setting(int speed, int duplex, const long unsigned int *mask, bool exact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81c36b10)
Location: drivers/net/phy/phy-core.c:287
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:_phy_start_aneg
  - drivers/net/phy/phy.c:phy_check_valid
```
**Symbols:**

```
ffffffff81c36b10-ffffffff81c36bd1: phy_lookup_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct phy_setting *phy_lookup_setting(int speed, int duplex, const long unsigned int *mask, bool exact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81ceba90)
Location: drivers/net/phy/phy-core.c:289
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:_phy_start_aneg
  - drivers/net/phy/phy.c:phy_check_valid
```
**Symbols:**

```
ffffffff81ceba90-ffffffff81cebb51: phy_lookup_setting (STB_GLOBAL)
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
const struct phy_setting *phy_lookup_setting(int speed, int duplex, const long unsigned int *mask, bool exact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffff8000109d2930)
Location: drivers/net/phy/phy-core.c:164
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
ffff8000109d2930-ffff8000109d2a18: phy_lookup_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const struct phy_setting *phy_lookup_setting(int speed, int duplex, const long unsigned int *mask, bool exact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c0abaa44)
Location: drivers/net/phy/phy-core.c:164
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
c0abaa44-c0abab20: phy_lookup_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const struct phy_setting *phy_lookup_setting(int speed, int duplex, const long unsigned int *mask, bool exact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c000000000a92ae0)
Location: drivers/net/phy/phy-core.c:164
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
c000000000a92ae0-c000000000a92bec: phy_lookup_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const struct phy_setting *phy_lookup_setting(int speed, int duplex, const long unsigned int *mask, bool exact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffe00061f21e)
Location: drivers/net/phy/phy-core.c:164
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
ffffffe00061f21e-ffffffe00061f2e6: phy_lookup_setting (STB_GLOBAL)
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
const struct phy_setting *phy_lookup_setting(int speed, int duplex, const long unsigned int *mask, bool exact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8177eda0)
Location: drivers/net/phy/phy-core.c:164
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
ffffffff8177eda0-ffffffff8177ee2c: phy_lookup_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const struct phy_setting *phy_lookup_setting(int speed, int duplex, const long unsigned int *mask, bool exact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8175eb40)
Location: drivers/net/phy/phy-core.c:164
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
ffffffff8175eb40-ffffffff8175ebcc: phy_lookup_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const struct phy_setting *phy_lookup_setting(int speed, int duplex, const long unsigned int *mask, bool exact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817af150)
Location: drivers/net/phy/phy-core.c:164
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
ffffffff817af150-ffffffff817af1dc: phy_lookup_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const struct phy_setting *phy_lookup_setting(int speed, int duplex, const long unsigned int *mask, bool exact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817c90e0)
Location: drivers/net/phy/phy-core.c:164
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
ffffffff817c90e0-ffffffff817c916c: phy_lookup_setting (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const long unsigned int *mask</code>
</li>
<li>
<b>Param added. </b>
<code>size_t maxbit</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 features</code>
</li>
<li>
<b>Param reordered. </b>
<code>speed, duplex, features, exact</code> ➡️ <code>speed, duplex, mask, maxbit, exact</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>size_t maxbit</code>
</li>
<li>
<b>Param reordered. </b>
<code>speed, duplex, mask, maxbit, exact</code> ➡️ <code>speed, duplex, mask, exact</code>
</li>
</ul>
</details>
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
