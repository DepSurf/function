# Function: <code>regulator_force_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regulator_force_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814d9fa0)
Location: drivers/regulator/core.c:2306
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_force_disable
  - drivers/power/charger-manager.c:try_charger_enable
```
**Symbols:**

```
ffffffff814d9fa0-ffffffff814da0b8: regulator_force_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regulator_force_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152c740)
Location: drivers/regulator/core.c:2355
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_force_disable
  - drivers/power/charger-manager.c:try_charger_enable
```
**Symbols:**

```
ffffffff8152c740-ffffffff8152c858: regulator_force_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regulator_force_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81558da0)
Location: drivers/regulator/core.c:2356
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_force_disable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
**Symbols:**

```
ffffffff81558da0-ffffffff81558eb8: regulator_force_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regulator_force_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156d710)
Location: drivers/regulator/core.c:2368
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_force_disable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
**Symbols:**

```
ffffffff8156d710-ffffffff8156d828: regulator_force_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regulator_force_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815d18d0)
Location: drivers/regulator/core.c:2368
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_force_disable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
**Symbols:**

```
ffffffff815d18d0-ffffffff815d19e8: regulator_force_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int regulator_force_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2425
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_force_disable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
**Symbols:**

```
ffffffff8160caf3-ffffffff8160cb44: regulator_force_disable.cold.59 (STB_LOCAL)
ffffffff81609a50-ffffffff81609b1e: regulator_force_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int regulator_force_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2740
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_force_disable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
**Symbols:**

```
ffffffff816298c0-ffffffff81629912: regulator_force_disable.cold.73 (STB_LOCAL)
ffffffff81628420-ffffffff8162851f: regulator_force_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int regulator_force_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2695
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_force_disable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
**Symbols:**

```
ffffffff8165d152-ffffffff8165d17b: regulator_force_disable.cold (STB_LOCAL)
ffffffff8165aeb0-ffffffff8165afde: regulator_force_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int regulator_force_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2703
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_force_disable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
**Symbols:**

```
ffffffff8167f995-ffffffff8167f9be: regulator_force_disable.cold (STB_LOCAL)
ffffffff8167e600-ffffffff8167e72e: regulator_force_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int regulator_force_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2734
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_force_disable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
**Symbols:**

```
ffffffff81730b8b-ffffffff81730bbf: regulator_force_disable.cold (STB_LOCAL)
ffffffff8172f930-ffffffff8172fa2f: regulator_force_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int regulator_force_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2859
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_force_disable
```
**Symbols:**

```
ffffffff81c07130-ffffffff81c07168: regulator_force_disable.cold (STB_LOCAL)
ffffffff8174c600-ffffffff8174c6ff: regulator_force_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int regulator_force_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2857
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_force_disable
```
**Symbols:**

```
ffffffff81bf8ddf-ffffffff81bf8e15: regulator_force_disable.cold (STB_LOCAL)
ffffffff8172fea0-ffffffff8172ff9f: regulator_force_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regulator_force_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2957
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_force_disable
```
**Symbols:**

```
ffffffff81cf8161-ffffffff81cf8197: regulator_force_disable.cold (STB_LOCAL)
ffffffff817afca0-ffffffff817afd9f: regulator_force_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regulator_force_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3004
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_force_disable
```
**Symbols:**

```
ffffffff81ec0244-ffffffff81ec027a: regulator_force_disable.cold (STB_LOCAL)
ffffffff818eb0a0-ffffffff818eb1c4: regulator_force_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regulator_force_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a41d70)
Location: drivers/regulator/core.c:3036
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_force_disable
```
**Symbols:**

```
ffffffff81a41d70-ffffffff81a41eee: regulator_force_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regulator_force_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a8be70)
Location: drivers/regulator/core.c:3102
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_force_disable
```
**Symbols:**

```
ffffffff81a8be70-ffffffff81a8bfee: regulator_force_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regulator_force_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ade670)
Location: drivers/regulator/core.c:3108
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_force_disable
```
**Symbols:**

```
ffffffff81ade670-ffffffff81ade7e5: regulator_force_disable (STB_GLOBAL)
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
int regulator_force_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010848418)
Location: drivers/regulator/core.c:2703
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_force_disable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
**Symbols:**

```
ffff800010848418-ffff800010848570: regulator_force_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regulator_force_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0951c10)
Location: drivers/regulator/core.c:2703
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_force_disable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
**Symbols:**

```
c0951c10-c0951d70: regulator_force_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regulator_force_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e5090)
Location: drivers/regulator/core.c:2703
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_force_disable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
**Symbols:**

```
c0000000008e5090-c0000000008e5248: regulator_force_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regulator_force_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe00052873c)
Location: drivers/regulator/core.c:2703
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_force_disable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
**Symbols:**

```
ffffffe00052873c-ffffffe000528852: regulator_force_disable (STB_GLOBAL)
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
int regulator_force_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2703
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_force_disable
```
**Symbols:**

```
ffffffff81645415-ffffffff8164543e: regulator_force_disable.cold (STB_LOCAL)
ffffffff81644060-ffffffff8164418e: regulator_force_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int regulator_force_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2703
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_force_disable
```
**Symbols:**

```
ffffffff81625875-ffffffff8162589e: regulator_force_disable.cold (STB_LOCAL)
ffffffff816244e0-ffffffff8162460e: regulator_force_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int regulator_force_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2703
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_force_disable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
**Symbols:**

```
ffffffff816737d5-ffffffff816737fe: regulator_force_disable.cold (STB_LOCAL)
ffffffff81672440-ffffffff8167256e: regulator_force_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int regulator_force_disable(struct regulator *regulator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2703
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_force_disable
  - drivers/power/supply/charger-manager.c:try_charger_enable
```
**Symbols:**

```
ffffffff8168de35-ffffffff8168de5e: regulator_force_disable.cold (STB_LOCAL)
ffffffff8168caa0-ffffffff8168cbce: regulator_force_disable (STB_GLOBAL)
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
