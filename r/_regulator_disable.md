# Function: <code>_regulator_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int _regulator_disable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814d9cb0)
Location: drivers/regulator/core.c:2192
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:regulator_disable_work
```
**Symbols:**

```
ffffffff814d9cb0-ffffffff814d9e08: _regulator_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int _regulator_disable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152c300)
Location: drivers/regulator/core.c:2244
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_disable
```
**Symbols:**

```
ffffffff8152c300-ffffffff8152c472: _regulator_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int _regulator_disable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81558960)
Location: drivers/regulator/core.c:2245
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_disable
```
**Symbols:**

```
ffffffff81558960-ffffffff81558ad2: _regulator_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int _regulator_disable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156d2b0)
Location: drivers/regulator/core.c:2257
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_disable
```
**Symbols:**

```
ffffffff8156d2b0-ffffffff8156d410: _regulator_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int _regulator_disable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815d1530)
Location: drivers/regulator/core.c:2257
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_disable
```
**Symbols:**

```
ffffffff815d1530-ffffffff815d1690: _regulator_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int _regulator_disable(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2314
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_disable
```
**Symbols:**

```
ffffffff81609780-ffffffff8160987e: _regulator_disable (STB_LOCAL)
ffffffff8160ca21-ffffffff8160ca81: _regulator_disable.cold.57 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int _regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2627
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff81626ae0-ffffffff81626c13: _regulator_disable (STB_LOCAL)
ffffffff816291ba-ffffffff81629202: _regulator_disable.cold.66 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int _regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2582
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff8165a110-ffffffff8165a275: _regulator_disable (STB_LOCAL)
ffffffff8165cedb-ffffffff8165cefb: _regulator_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int _regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2590
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff8167ce50-ffffffff8167cfb5: _regulator_disable (STB_LOCAL)
ffffffff8167f702-ffffffff8167f722: _regulator_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int _regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2621
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff8172e1c0-ffffffff8172e30a: _regulator_disable (STB_LOCAL)
ffffffff8173071b-ffffffff81730746: _regulator_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int _regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2746
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff8174add0-ffffffff8174af1a: _regulator_disable (STB_LOCAL)
ffffffff81c06c1a-ffffffff81c06c48: _regulator_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int _regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2744
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff8172e4a0-ffffffff8172e5ea: _regulator_disable (STB_LOCAL)
ffffffff81bf88b5-ffffffff81bf88e3: _regulator_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int _regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2844
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff817ae080-ffffffff817ae1ca: _regulator_disable (STB_LOCAL)
ffffffff81cf7abf-ffffffff81cf7aed: _regulator_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int _regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2891
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff818e9030-ffffffff818e9186: _regulator_disable (STB_LOCAL)
ffffffff81ebfc91-ffffffff81ebfcbf: _regulator_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int _regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3f300)
Location: drivers/regulator/core.c:2923
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff81a3f300-ffffffff81a3f4af: _regulator_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int _regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a88e10)
Location: drivers/regulator/core.c:2989
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff81a88e10-ffffffff81a89073: _regulator_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int _regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81adb500)
Location: drivers/regulator/core.c:2992
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff81adb500-ffffffff81adb751: _regulator_disable (STB_LOCAL)
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
int _regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff8000108469e0)
Location: drivers/regulator/core.c:2590
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffff8000108469e0-ffff800010846b6c: _regulator_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0950170)
Location: drivers/regulator/core.c:2590
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
c0950170-c095031c: _regulator_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e29d0)
Location: drivers/regulator/core.c:2590
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
c0000000008e29d0-c0000000008e2c34: _regulator_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int _regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe000526f10)
Location: drivers/regulator/core.c:2590
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffe000526f10-ffffffe000527060: _regulator_disable (STB_LOCAL)
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
int _regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2590
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff81642730-ffffffff81642895: _regulator_disable (STB_LOCAL)
ffffffff8164511b-ffffffff8164513b: _regulator_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int _regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2590
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff81622d30-ffffffff81622e95: _regulator_disable (STB_LOCAL)
ffffffff816255e2-ffffffff81625602: _regulator_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int _regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2590
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff81670c90-ffffffff81670df5: _regulator_disable (STB_LOCAL)
ffffffff81673542-ffffffff81673562: _regulator_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int _regulator_disable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2590
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_disable_work
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:regulator_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff8168b2f0-ffffffff8168b455: _regulator_disable (STB_LOCAL)
ffffffff8168dba2-ffffffff8168dbc2: _regulator_disable.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct regulator *regulator</code>
</li>
<li>
<b>Param removed. </b>
<code>struct regulator_dev *rdev</code>
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
