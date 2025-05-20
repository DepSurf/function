# Function: <code>regulator_mode_constrain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regulator_mode_constrain(struct regulator_dev *rdev, int *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814d7be0)
Location: drivers/regulator/core.c:302
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:drms_uA_update
```
**Symbols:**

```
ffffffff814d7be0-ffffffff814d7cd2: regulator_mode_constrain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regulator_mode_constrain(struct regulator_dev *rdev, int *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152b030)
Location: drivers/regulator/core.c:296
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_mode
```
**Symbols:**

```
ffffffff8152b030-ffffffff8152b13b: regulator_mode_constrain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regulator_mode_constrain(struct regulator_dev *rdev, unsigned int *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81557630)
Location: drivers/regulator/core.c:296
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_mode
```
**Symbols:**

```
ffffffff81557630-ffffffff81557731: regulator_mode_constrain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regulator_mode_constrain(struct regulator_dev *rdev, unsigned int *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156bd00)
Location: drivers/regulator/core.c:296
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_mode
```
**Symbols:**

```
ffffffff8156bd00-ffffffff8156bde8: regulator_mode_constrain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regulator_mode_constrain(struct regulator_dev *rdev, unsigned int *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815cff30)
Location: drivers/regulator/core.c:296
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_mode
```
**Symbols:**

```
ffffffff815cff30-ffffffff815d0018: regulator_mode_constrain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int regulator_mode_constrain(struct regulator_dev *rdev, unsigned int *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:348
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_mode
```
**Symbols:**

```
ffffffff81607a80-ffffffff81607af6: regulator_mode_constrain (STB_LOCAL)
ffffffff8160c625-ffffffff8160c6b2: regulator_mode_constrain.cold.48 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int regulator_mode_constrain(struct regulator_dev *rdev, unsigned int *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:532
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_mode
```
**Symbols:**

```
ffffffff81623270-ffffffff816232e6: regulator_mode_constrain (STB_LOCAL)
ffffffff81628d29-ffffffff81628db6: regulator_mode_constrain.cold.54 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int regulator_mode_constrain(struct regulator_dev *rdev, unsigned int *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:514
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_mode
```
**Symbols:**

```
ffffffff816564c0-ffffffff81656586: regulator_mode_constrain (STB_LOCAL)
ffffffff8165cd1e-ffffffff8165cd36: regulator_mode_constrain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int regulator_mode_constrain(struct regulator_dev *rdev, unsigned int *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:518
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_mode
```
**Symbols:**

```
ffffffff816789f0-ffffffff81678ab6: regulator_mode_constrain (STB_LOCAL)
ffffffff8167f44e-ffffffff8167f466: regulator_mode_constrain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int regulator_mode_constrain(struct regulator_dev *rdev, unsigned int *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:521
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:drms_uA_update
```
**Symbols:**

```
ffffffff8172c510-ffffffff8172c588: regulator_mode_constrain (STB_LOCAL)
ffffffff817303ca-ffffffff81730426: regulator_mode_constrain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int regulator_mode_constrain(struct regulator_dev *rdev, unsigned int *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:520
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:drms_uA_update
```
**Symbols:**

```
ffffffff817495a0-ffffffff81749618: regulator_mode_constrain (STB_LOCAL)
ffffffff81c068f4-ffffffff81c06950: regulator_mode_constrain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int regulator_mode_constrain(struct regulator_dev *rdev, unsigned int *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:520
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:drms_uA_update
```
**Symbols:**

```
ffffffff8172ce50-ffffffff8172cec8: regulator_mode_constrain (STB_LOCAL)
ffffffff81bf8595-ffffffff81bf85ec: regulator_mode_constrain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regulator_mode_constrain(struct regulator_dev *rdev, unsigned int *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:510
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:drms_uA_update
```
**Symbols:**

```
ffffffff817a8a50-ffffffff817a8ac8: regulator_mode_constrain (STB_LOCAL)
ffffffff81cf75b9-ffffffff81cf7610: regulator_mode_constrain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regulator_mode_constrain(struct regulator_dev *rdev, unsigned int *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:511
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:drms_uA_update
```
**Symbols:**

```
ffffffff818e32c0-ffffffff818e334c: regulator_mode_constrain (STB_LOCAL)
ffffffff81ebf797-ffffffff81ebf7e9: regulator_mode_constrain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regulator_mode_constrain(struct regulator_dev *rdev, unsigned int *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3bf20)
Location: drivers/regulator/core.c:511
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:drms_uA_update
```
**Symbols:**

```
ffffffff81a3bf20-ffffffff81a3c036: regulator_mode_constrain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regulator_mode_constrain(struct regulator_dev *rdev, unsigned int *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a85a90)
Location: drivers/regulator/core.c:577
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:drms_uA_update
```
**Symbols:**

```
ffffffff81a85a90-ffffffff81a85b9d: regulator_mode_constrain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regulator_mode_constrain(struct regulator_dev *rdev, unsigned int *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ad8250)
Location: drivers/regulator/core.c:579
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:drms_uA_update
```
**Symbols:**

```
ffffffff81ad8250-ffffffff81ad835d: regulator_mode_constrain (STB_LOCAL)
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
int regulator_mode_constrain(struct regulator_dev *rdev, unsigned int *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff8000108416f0)
Location: drivers/regulator/core.c:518
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_mode
```
**Symbols:**

```
ffff8000108416f0-ffff80001084180c: regulator_mode_constrain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regulator_mode_constrain(struct regulator_dev *rdev, unsigned int *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094ad30)
Location: drivers/regulator/core.c:518
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_mode
```
**Symbols:**

```
c094ad30-c094ae58: regulator_mode_constrain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regulator_mode_constrain(struct regulator_dev *rdev, unsigned int *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008dbda0)
Location: drivers/regulator/core.c:518
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_mode
```
**Symbols:**

```
c0000000008dbda0-c0000000008dbf30: regulator_mode_constrain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regulator_mode_constrain(struct regulator_dev *rdev, unsigned int *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe000523404)
Location: drivers/regulator/core.c:518
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_mode
```
**Symbols:**

```
ffffffe000523404-ffffffe0005234ea: regulator_mode_constrain (STB_LOCAL)
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
int regulator_mode_constrain(struct regulator_dev *rdev, unsigned int *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:518
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_mode
```
**Symbols:**

```
ffffffff8163e4f0-ffffffff8163e5b6: regulator_mode_constrain (STB_LOCAL)
ffffffff81644e67-ffffffff81644e7f: regulator_mode_constrain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int regulator_mode_constrain(struct regulator_dev *rdev, unsigned int *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:518
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_mode
```
**Symbols:**

```
ffffffff8161e8d0-ffffffff8161e996: regulator_mode_constrain (STB_LOCAL)
ffffffff8162532e-ffffffff81625346: regulator_mode_constrain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int regulator_mode_constrain(struct regulator_dev *rdev, unsigned int *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:518
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_mode
```
**Symbols:**

```
ffffffff8166c830-ffffffff8166c8f6: regulator_mode_constrain (STB_LOCAL)
ffffffff8167328e-ffffffff816732a6: regulator_mode_constrain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int regulator_mode_constrain(struct regulator_dev *rdev, unsigned int *mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:518
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_set_mode
```
**Symbols:**

```
ffffffff81686e60-ffffffff81686f26: regulator_mode_constrain (STB_LOCAL)
ffffffff8168d8ee-ffffffff8168d906: regulator_mode_constrain.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int *mode</code> ➡️ <code>unsigned int *mode</code>
</li>
</ul>
</details>
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
