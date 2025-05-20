# Function: <code>drms_uA_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int drms_uA_update(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814d8b50)
Location: drivers/regulator/core.c:683
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:regulator_enable
```
**Symbols:**

```
ffffffff814d8b50-ffffffff814d8ec9: drms_uA_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int drms_uA_update(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152bf90)
Location: drivers/regulator/core.c:659
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:regulator_enable
```
**Symbols:**

```
ffffffff8152bf90-ffffffff8152c2a3: drms_uA_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int drms_uA_update(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815585d0)
Location: drivers/regulator/core.c:660
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:regulator_enable
```
**Symbols:**

```
ffffffff815585d0-ffffffff81558905: drms_uA_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int drms_uA_update(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156cf20)
Location: drivers/regulator/core.c:660
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:regulator_enable
```
**Symbols:**

```
ffffffff8156cf20-ffffffff8156d25e: drms_uA_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int drms_uA_update(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815d1190)
Location: drivers/regulator/core.c:660
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:regulator_enable
```
**Symbols:**

```
ffffffff815d1190-ffffffff815d14dc: drms_uA_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int drms_uA_update(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:730
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:regulator_enable
```
**Symbols:**

```
ffffffff81609530-ffffffff816096ff: drms_uA_update (STB_LOCAL)
ffffffff8160c8db-ffffffff8160ca21: drms_uA_update.cold.56 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int drms_uA_update(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff816241d6)
Location: drivers/regulator/core.c:921
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81624170-ffffffff8162433f: drms_uA_update (STB_LOCAL)
ffffffff81628e59-ffffffff81628f99: drms_uA_update.cold.56 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int drms_uA_update(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff81659e65)
Location: drivers/regulator/core.c:903
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81659dc0-ffffffff8165a0a6: drms_uA_update (STB_LOCAL)
ffffffff8165ce55-ffffffff8165cec5: drms_uA_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int drms_uA_update(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff8167a4d5)
Location: drivers/regulator/core.c:909
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8167a430-ffffffff8167a716: drms_uA_update (STB_LOCAL)
ffffffff8167f5fe-ffffffff8167f66e: drms_uA_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int drms_uA_update(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:912
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8172cab0-ffffffff8172ccff: drms_uA_update (STB_LOCAL)
ffffffff8173052f-ffffffff817305ef: drms_uA_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int drms_uA_update(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:935
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81749b40-ffffffff81749dca: drms_uA_update (STB_LOCAL)
ffffffff81c06a58-ffffffff81c06b21: drms_uA_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int drms_uA_update(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:937
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8172d3f0-ffffffff8172d63f: drms_uA_update (STB_LOCAL)
ffffffff81bf86f0-ffffffff81bf87bc: drms_uA_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int drms_uA_update(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:917
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff817ac4f0-ffffffff817ac748: drms_uA_update (STB_LOCAL)
ffffffff81cf77f4-ffffffff81cf78c0: drms_uA_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int drms_uA_update(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:942
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff818e72b0-ffffffff818e7520: drms_uA_update (STB_LOCAL)
ffffffff81ebf9c5-ffffffff81ebfa85: drms_uA_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int drms_uA_update(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3df10)
Location: drivers/regulator/core.c:942
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_bulk_get
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81a3df10-ffffffff81a3e331: drms_uA_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int drms_uA_update(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a86100)
Location: drivers/regulator/core.c:1008
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_bulk_get
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81a86100-ffffffff81a8650d: drms_uA_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int drms_uA_update(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ad88c0)
Location: drivers/regulator/core.c:1010
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_bulk_get
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81ad88c0-ffffffff81ad8ccd: drms_uA_update (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int drms_uA_update(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010842758)
Location: drivers/regulator/core.c:909
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffff800010842758-ffff800010842a98: drms_uA_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int drms_uA_update(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094d2d8)
Location: drivers/regulator/core.c:909
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
c094d2d8-c094d64c: drms_uA_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int drms_uA_update(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008de770)
Location: drivers/regulator/core.c:909
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
c0000000008de770-c0000000008debdc: drms_uA_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int drms_uA_update(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe000524a1a)
Location: drivers/regulator/core.c:909
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffe000524a1a-ffffffe000524c84: drms_uA_update (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int drms_uA_update(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff8163ffd5)
Location: drivers/regulator/core.c:909
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8163ff30-ffffffff81640216: drms_uA_update (STB_LOCAL)
ffffffff81645017-ffffffff81645087: drms_uA_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int drms_uA_update(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff816203b5)
Location: drivers/regulator/core.c:909
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81620310-ffffffff816205f6: drms_uA_update (STB_LOCAL)
ffffffff816254de-ffffffff8162554e: drms_uA_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int drms_uA_update(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff8166e315)
Location: drivers/regulator/core.c:909
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8166e270-ffffffff8166e556: drms_uA_update (STB_LOCAL)
ffffffff8167343e-ffffffff816734ae: drms_uA_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int drms_uA_update(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (ffffffff81688975)
Location: drivers/regulator/core.c:909
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_force_disable
  - drivers/regulator/core.c:_regulator_enable
  - drivers/regulator/core.c:_regulator_handle_consumer_disable
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff816888d0-ffffffff81688bb6: drms_uA_update (STB_LOCAL)
ffffffff8168da9e-ffffffff8168db0e: drms_uA_update.cold (STB_LOCAL)
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
