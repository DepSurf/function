# Function: <code>regulator_remove_coupling</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81626f40)
Location: drivers/regulator/core.c:4778
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void regulator_remove_coupling(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4861
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff81656e80-ffffffff8165703a: regulator_remove_coupling (STB_LOCAL)
ffffffff8165cd4a-ffffffff8165cd5e: regulator_remove_coupling.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void regulator_remove_coupling(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4871
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff8167a780-ffffffff8167a93a: regulator_remove_coupling (STB_LOCAL)
ffffffff8167f684-ffffffff8167f698: regulator_remove_coupling.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void regulator_remove_coupling(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4916
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff8172c340-ffffffff8172c4da: regulator_remove_coupling (STB_LOCAL)
ffffffff8173036b-ffffffff8173038a: regulator_remove_coupling.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void regulator_remove_coupling(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:5051
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff817493d0-ffffffff81749569: regulator_remove_coupling (STB_LOCAL)
ffffffff81c06895-ffffffff81c068b4: regulator_remove_coupling.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void regulator_remove_coupling(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:5053
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff8172cc80-ffffffff8172ce19: regulator_remove_coupling (STB_LOCAL)
ffffffff81bf8536-ffffffff81bf8555: regulator_remove_coupling.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void regulator_remove_coupling(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:5190
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff817a91f0-ffffffff817a93d5: regulator_remove_coupling (STB_LOCAL)
ffffffff81cf7610-ffffffff81cf762f: regulator_remove_coupling.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void regulator_remove_coupling(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:5255
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff818e3940-ffffffff818e3b2f: regulator_remove_coupling (STB_LOCAL)
ffffffff81ebf7e9-ffffffff81ebf808: regulator_remove_coupling.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void regulator_remove_coupling(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3a4f0)
Location: drivers/regulator/core.c:5296
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff81a3a4f0-ffffffff81a3a713: regulator_remove_coupling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void regulator_remove_coupling(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a83f00)
Location: drivers/regulator/core.c:5360
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff81a83f00-ffffffff81a84123: regulator_remove_coupling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void regulator_remove_coupling(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ad66b0)
Location: drivers/regulator/core.c:5419
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff81ad66b0-ffffffff81ad68d3: regulator_remove_coupling (STB_LOCAL)
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
void regulator_remove_coupling(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010842b30)
Location: drivers/regulator/core.c:4871
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffff800010842b30-ffff800010842d0c: regulator_remove_coupling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void regulator_remove_coupling(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094d6e0)
Location: drivers/regulator/core.c:4871
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
c094d6e0-c094d8dc: regulator_remove_coupling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void regulator_remove_coupling(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008dec90)
Location: drivers/regulator/core.c:4871
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
c0000000008dec90-c0000000008def3c: regulator_remove_coupling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void regulator_remove_coupling(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe000524cf6)
Location: drivers/regulator/core.c:4871
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffe000524cf6-ffffffe000524e7a: regulator_remove_coupling (STB_LOCAL)
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
void regulator_remove_coupling(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4871
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff81640280-ffffffff8164043a: regulator_remove_coupling (STB_LOCAL)
ffffffff8164509d-ffffffff816450b1: regulator_remove_coupling.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void regulator_remove_coupling(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4871
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff81620660-ffffffff8162081a: regulator_remove_coupling (STB_LOCAL)
ffffffff81625564-ffffffff81625578: regulator_remove_coupling.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void regulator_remove_coupling(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4871
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff8166e5c0-ffffffff8166e77a: regulator_remove_coupling (STB_LOCAL)
ffffffff816734c4-ffffffff816734d8: regulator_remove_coupling.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void regulator_remove_coupling(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:4871
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff81688c20-ffffffff81688dda: regulator_remove_coupling (STB_LOCAL)
ffffffff8168db24-ffffffff8168db38: regulator_remove_coupling.cold (STB_LOCAL)
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
