# Function: <code>regulator_set_current_limit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regulator_set_current_limit(struct regulator *regulator, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814d95d0)
Location: drivers/regulator/core.c:3162
Inline: False
Direct callers:
  - drivers/usb/phy/phy-generic.c:nop_gpio_vbus_thread
```
**Symbols:**

```
ffffffff814d95d0-ffffffff814d96ef: regulator_set_current_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regulator_set_current_limit(struct regulator *regulator, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152b950)
Location: drivers/regulator/core.c:3195
Inline: False
```
**Symbols:**

```
ffffffff8152b950-ffffffff8152ba90: regulator_set_current_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regulator_set_current_limit(struct regulator *regulator, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81557f50)
Location: drivers/regulator/core.c:3228
Inline: False
```
**Symbols:**

```
ffffffff81557f50-ffffffff81558090: regulator_set_current_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regulator_set_current_limit(struct regulator *regulator, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156c180)
Location: drivers/regulator/core.c:3251
Inline: False
```
**Symbols:**

```
ffffffff8156c180-ffffffff8156c2bf: regulator_set_current_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regulator_set_current_limit(struct regulator *regulator, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815d03d0)
Location: drivers/regulator/core.c:3259
Inline: False
```
**Symbols:**

```
ffffffff815d03d0-ffffffff815d0512: regulator_set_current_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int regulator_set_current_limit(struct regulator *regulator, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3433
Inline: False
```
**Symbols:**

```
ffffffff8160c7db-ffffffff8160c892: regulator_set_current_limit.cold.53 (STB_LOCAL)
ffffffff81608eb0-ffffffff81608f71: regulator_set_current_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int regulator_set_current_limit(struct regulator *regulator, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4040
Inline: False
```
**Symbols:**

```
ffffffff81629021-ffffffff816290da: regulator_set_current_limit.cold.59 (STB_LOCAL)
ffffffff81625010-ffffffff8162514a: regulator_set_current_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int regulator_set_current_limit(struct regulator *regulator, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4060
Inline: False
```
**Symbols:**

```
ffffffff8165cd5e-ffffffff8165cd7c: regulator_set_current_limit.cold (STB_LOCAL)
ffffffff81657700-ffffffff816578e2: regulator_set_current_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int regulator_set_current_limit(struct regulator *regulator, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4070
Inline: False
```
**Symbols:**

```
ffffffff8167f698-ffffffff8167f6b6: regulator_set_current_limit.cold (STB_LOCAL)
ffffffff8167b620-ffffffff8167b802: regulator_set_current_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int regulator_set_current_limit(struct regulator *regulator, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4110
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_extcon_work
```
**Symbols:**

```
ffffffff81730426-ffffffff8173048f: regulator_set_current_limit.cold (STB_LOCAL)
ffffffff8172c6c0-ffffffff8172c7fd: regulator_set_current_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int regulator_set_current_limit(struct regulator *regulator, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4248
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_extcon_work
```
**Symbols:**

```
ffffffff81c06950-ffffffff81c069b9: regulator_set_current_limit.cold (STB_LOCAL)
ffffffff81749750-ffffffff8174988d: regulator_set_current_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int regulator_set_current_limit(struct regulator *regulator, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4250
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_extcon_work
```
**Symbols:**

```
ffffffff81bf85ec-ffffffff81bf8651: regulator_set_current_limit.cold (STB_LOCAL)
ffffffff8172d000-ffffffff8172d13d: regulator_set_current_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regulator_set_current_limit(struct regulator *regulator, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4373
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_extcon_work
```
**Symbols:**

```
ffffffff81cf764b-ffffffff81cf76b0: regulator_set_current_limit.cold (STB_LOCAL)
ffffffff817aa9b0-ffffffff817aab44: regulator_set_current_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regulator_set_current_limit(struct regulator *regulator, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4418
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_extcon_work
```
**Symbols:**

```
ffffffff81ebf84e-ffffffff81ebf8ad: regulator_set_current_limit.cold (STB_LOCAL)
ffffffff818e5340-ffffffff818e54cf: regulator_set_current_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regulator_set_current_limit(struct regulator *regulator, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3c1e0)
Location: drivers/regulator/core.c:4448
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_extcon_work
```
**Symbols:**

```
ffffffff81a3c1e0-ffffffff81a3c3ea: regulator_set_current_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regulator_set_current_limit(struct regulator *regulator, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a85d40)
Location: drivers/regulator/core.c:4514
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_extcon_work
```
**Symbols:**

```
ffffffff81a85d40-ffffffff81a85f4a: regulator_set_current_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regulator_set_current_limit(struct regulator *regulator, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ad8500)
Location: drivers/regulator/core.c:4520
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_extcon_work
```
**Symbols:**

```
ffffffff81ad8500-ffffffff81ad870a: regulator_set_current_limit (STB_GLOBAL)
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
int regulator_set_current_limit(struct regulator *regulator, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010843f08)
Location: drivers/regulator/core.c:4070
Inline: False
```
**Symbols:**

```
ffff800010843f08-ffff8000108440f0: regulator_set_current_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regulator_set_current_limit(struct regulator *regulator, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094e648)
Location: drivers/regulator/core.c:4070
Inline: False
Direct callers:
  - drivers/usb/phy/phy-generic.c:nop_gpio_vbus_thread
```
**Symbols:**

```
c094e648-c094e858: regulator_set_current_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regulator_set_current_limit(struct regulator *regulator, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e0430)
Location: drivers/regulator/core.c:4070
Inline: False
```
**Symbols:**

```
c0000000008e0430-c0000000008e0710: regulator_set_current_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regulator_set_current_limit(struct regulator *regulator, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe0005259b0)
Location: drivers/regulator/core.c:4070
Inline: False
```
**Symbols:**

```
ffffffe0005259b0-ffffffe000525b58: regulator_set_current_limit (STB_GLOBAL)
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
int regulator_set_current_limit(struct regulator *regulator, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4070
Inline: False
```
**Symbols:**

```
ffffffff816450b1-ffffffff816450cf: regulator_set_current_limit.cold (STB_LOCAL)
ffffffff81641060-ffffffff81641242: regulator_set_current_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int regulator_set_current_limit(struct regulator *regulator, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4070
Inline: False
```
**Symbols:**

```
ffffffff81625578-ffffffff81625596: regulator_set_current_limit.cold (STB_LOCAL)
ffffffff81621500-ffffffff816216e2: regulator_set_current_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int regulator_set_current_limit(struct regulator *regulator, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4070
Inline: False
```
**Symbols:**

```
ffffffff816734d8-ffffffff816734f6: regulator_set_current_limit.cold (STB_LOCAL)
ffffffff8166f460-ffffffff8166f642: regulator_set_current_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int regulator_set_current_limit(struct regulator *regulator, int min_uA, int max_uA);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4070
Inline: False
```
**Symbols:**

```
ffffffff8168db38-ffffffff8168db56: regulator_set_current_limit.cold (STB_LOCAL)
ffffffff81689ac0-ffffffff81689ca2: regulator_set_current_limit (STB_GLOBAL)
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
