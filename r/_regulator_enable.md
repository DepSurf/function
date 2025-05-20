# Function: <code>_regulator_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814da953)
Location: drivers/regulator/core.c:2090
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152c533)
Location: drivers/regulator/core.c:2142
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_enable
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
In drivers/regulator/core.c (ffffffff81558b93)
Location: drivers/regulator/core.c:2143
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_enable
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
In drivers/regulator/core.c (ffffffff8156d4ab)
Location: drivers/regulator/core.c:2153
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_enable
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
In drivers/regulator/core.c (ffffffff815d172b)
Location: drivers/regulator/core.c:2153
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_enable
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
In drivers/regulator/core.c (ffffffff81609936)
Location: drivers/regulator/core.c:2210
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int _regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2509
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff81627090-ffffffff816271ea: _regulator_enable (STB_LOCAL)
ffffffff81629215-ffffffff81629266: _regulator_enable.cold.68 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int _regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2464
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff8165a710-ffffffff8165a891: _regulator_enable (STB_LOCAL)
ffffffff8165cf46-ffffffff8165cf5a: _regulator_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int _regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2472
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff8167d310-ffffffff8167d491: _regulator_enable (STB_LOCAL)
ffffffff8167f736-ffffffff8167f74a: _regulator_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int _regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2503
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8172e760-ffffffff8172e8b1: _regulator_enable (STB_LOCAL)
ffffffff8173075a-ffffffff81730799: _regulator_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int _regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2628
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8174b330-ffffffff8174b481: _regulator_enable (STB_LOCAL)
ffffffff81c06c5f-ffffffff81c06c9e: _regulator_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int _regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2626
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8172ea40-ffffffff8172eb91: _regulator_enable (STB_LOCAL)
ffffffff81bf88fa-ffffffff81bf8939: _regulator_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int _regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2726
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff817ae680-ffffffff817ae7d4: _regulator_enable (STB_LOCAL)
ffffffff81cf7b04-ffffffff81cf7b43: _regulator_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int _regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2773
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff818e96a0-ffffffff818e9837: _regulator_enable (STB_LOCAL)
ffffffff81ebfcd7-ffffffff81ebfd12: _regulator_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int _regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3fa10)
Location: drivers/regulator/core.c:2805
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81a3fa10-ffffffff81a3fbd0: _regulator_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int _regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a895e0)
Location: drivers/regulator/core.c:2871
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81a895e0-ffffffff81a897a0: _regulator_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int _regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81adbcc0)
Location: drivers/regulator/core.c:2873
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_bulk_disable
  - drivers/regulator/core.c:regulator_bulk_enable_async
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81adbcc0-ffffffff81adbeee: _regulator_enable (STB_LOCAL)
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
int _regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010846f38)
Location: drivers/regulator/core.c:2472
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffff800010846f38-ffff8000108470d0: _regulator_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c09506b4)
Location: drivers/regulator/core.c:2472
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
c09506b4-c0950880: _regulator_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e3130)
Location: drivers/regulator/core.c:2472
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
c0000000008e3130-c0000000008e3340: _regulator_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int _regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe000527382)
Location: drivers/regulator/core.c:2472
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffe000527382-ffffffe0005274d4: _regulator_enable (STB_LOCAL)
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
int _regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2472
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff81642bf0-ffffffff81642d71: _regulator_enable (STB_LOCAL)
ffffffff8164514f-ffffffff81645163: _regulator_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int _regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2472
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff816231f0-ffffffff81623371: _regulator_enable (STB_LOCAL)
ffffffff81625616-ffffffff8162562a: _regulator_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int _regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2472
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff81671150-ffffffff816712d1: _regulator_enable (STB_LOCAL)
ffffffff81673576-ffffffff8167358a: _regulator_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int _regulator_enable(struct regulator *regulator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:2472
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_enable
  - drivers/regulator/core.c:_regulator_enable
```
**Symbols:**

```
ffffffff8168b7b0-ffffffff8168b931: _regulator_enable (STB_LOCAL)
ffffffff8168dbd6-ffffffff8168dbea: _regulator_enable.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
