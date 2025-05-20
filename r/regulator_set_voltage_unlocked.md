# Function: <code>regulator_set_voltage_unlocked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regulator_set_voltage_unlocked(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814db3f0)
Location: drivers/regulator/core.c:2820
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_set_voltage
```
**Symbols:**

```
ffffffff814db3f0-ffffffff814db625: regulator_set_voltage_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regulator_set_voltage_unlocked(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152bcd0)
Location: drivers/regulator/core.c:2836
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff8152bcd0-ffffffff8152bf0c: regulator_set_voltage_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regulator_set_voltage_unlocked(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81558310)
Location: drivers/regulator/core.c:2872
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff81558310-ffffffff8155854c: regulator_set_voltage_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regulator_set_voltage_unlocked(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156c980)
Location: drivers/regulator/core.c:2892
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff8156c980-ffffffff8156cbfc: regulator_set_voltage_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regulator_set_voltage_unlocked(struct regulator *regulator, int min_uV, int max_uV);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815d0bf0)
Location: drivers/regulator/core.c:2900
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff815d0bf0-ffffffff815d0e6c: regulator_set_voltage_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int regulator_set_voltage_unlocked(struct regulator *regulator, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2983
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
  - drivers/regulator/core.c:regulator_set_voltage_unlocked
```
**Symbols:**

```
ffffffff81607e90-ffffffff8160819d: regulator_set_voltage_unlocked (STB_LOCAL)
ffffffff8160c755-ffffffff8160c77c: regulator_set_voltage_unlocked.cold.50 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int regulator_set_voltage_unlocked(struct regulator *regulator, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3311
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
  - drivers/regulator/core.c:regulator_balance_voltage
```
**Symbols:**

```
ffffffff81626890-ffffffff81626979: regulator_set_voltage_unlocked (STB_LOCAL)
ffffffff8162916f-ffffffff81629184: regulator_set_voltage_unlocked.cold.64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int regulator_set_voltage_unlocked(struct regulator *regulator, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816592c0)
Location: drivers/regulator/core.c:3329
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
ffffffff816592c0-ffffffff816593b4: regulator_set_voltage_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int regulator_set_voltage_unlocked(struct regulator *regulator, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8167e790)
Location: drivers/regulator/core.c:3337
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
ffffffff8167e790-ffffffff8167e884: regulator_set_voltage_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int regulator_set_voltage_unlocked(struct regulator *regulator, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3368
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
ffffffff8172fa90-ffffffff8172fb68: regulator_set_voltage_unlocked (STB_LOCAL)
ffffffff81730bbf-ffffffff81730bdb: regulator_set_voltage_unlocked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int regulator_set_voltage_unlocked(struct regulator *regulator, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3498
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
ffffffff8174c760-ffffffff8174c838: regulator_set_voltage_unlocked (STB_LOCAL)
ffffffff81c07168-ffffffff81c07184: regulator_set_voltage_unlocked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int regulator_set_voltage_unlocked(struct regulator *regulator, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3496
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
ffffffff81730000-ffffffff817300da: regulator_set_voltage_unlocked (STB_LOCAL)
ffffffff81bf8e15-ffffffff81bf8e31: regulator_set_voltage_unlocked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regulator_set_voltage_unlocked(struct regulator *regulator, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3596
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
ffffffff817afe00-ffffffff817afefd: regulator_set_voltage_unlocked (STB_LOCAL)
ffffffff81cf8197-ffffffff81cf81b3: regulator_set_voltage_unlocked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regulator_set_voltage_unlocked(struct regulator *regulator, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:3638
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
ffffffff818eb240-ffffffff818eb36c: regulator_set_voltage_unlocked (STB_LOCAL)
ffffffff81ec027a-ffffffff81ec0296: regulator_set_voltage_unlocked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regulator_set_voltage_unlocked(struct regulator *regulator, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a41f80)
Location: drivers/regulator/core.c:3668
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
ffffffff81a41f80-ffffffff81a420d2: regulator_set_voltage_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regulator_set_voltage_unlocked(struct regulator *regulator, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a8c080)
Location: drivers/regulator/core.c:3734
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
ffffffff81a8c080-ffffffff81a8c1d2: regulator_set_voltage_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regulator_set_voltage_unlocked(struct regulator *regulator, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ade880)
Location: drivers/regulator/core.c:3740
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
ffffffff81ade880-ffffffff81ade9d2: regulator_set_voltage_unlocked (STB_LOCAL)
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
int regulator_set_voltage_unlocked(struct regulator *regulator, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010848600)
Location: drivers/regulator/core.c:3337
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
ffff800010848600-ffff80001084871c: regulator_set_voltage_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regulator_set_voltage_unlocked(struct regulator *regulator, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0951de0)
Location: drivers/regulator/core.c:3337
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
c0951de0-c0951f10: regulator_set_voltage_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regulator_set_voltage_unlocked(struct regulator *regulator, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e5310)
Location: drivers/regulator/core.c:3337
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
c0000000008e5310-c0000000008e54ac: regulator_set_voltage_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regulator_set_voltage_unlocked(struct regulator *regulator, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe0005288ca)
Location: drivers/regulator/core.c:3337
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
ffffffe0005288ca-ffffffe0005289b8: regulator_set_voltage_unlocked (STB_LOCAL)
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
int regulator_set_voltage_unlocked(struct regulator *regulator, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816441f0)
Location: drivers/regulator/core.c:3337
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
ffffffff816441f0-ffffffff816442e4: regulator_set_voltage_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int regulator_set_voltage_unlocked(struct regulator *regulator, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81624670)
Location: drivers/regulator/core.c:3337
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
ffffffff81624670-ffffffff81624764: regulator_set_voltage_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int regulator_set_voltage_unlocked(struct regulator *regulator, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816725d0)
Location: drivers/regulator/core.c:3337
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
ffffffff816725d0-ffffffff816726c4: regulator_set_voltage_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int regulator_set_voltage_unlocked(struct regulator *regulator, int min_uV, int max_uV, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8168cc30)
Location: drivers/regulator/core.c:3337
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_suspend_voltage
  - drivers/regulator/core.c:regulator_set_voltage
  - drivers/regulator/core.c:regulator_set_voltage_rdev
  - drivers/regulator/core.c:regulator_set_voltage_rdev
```
**Symbols:**

```
ffffffff8168cc30-ffffffff8168cd24: regulator_set_voltage_unlocked (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>suspend_state_t state</code>
</li>
</ul>
</details>
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
