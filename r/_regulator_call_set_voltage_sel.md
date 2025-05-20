# Function: <code>_regulator_call_set_voltage_sel</code>

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
In drivers/regulator/core.c (ffffffff814dad10)
Location: drivers/regulator/core.c:2706
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
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
In drivers/regulator/core.c (ffffffff8152ab84)
Location: drivers/regulator/core.c:2722
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
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
In drivers/regulator/core.c (ffffffff8155715f)
Location: drivers/regulator/core.c:2723
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
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
In drivers/regulator/core.c (ffffffff8156b779)
Location: drivers/regulator/core.c:2735
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
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
In drivers/regulator/core.c (ffffffff815cf991)
Location: drivers/regulator/core.c:2743
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
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
In drivers/regulator/core.c (ffffffff816078b7)
Location: drivers/regulator/core.c:2800
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81622ff7)
Location: drivers/regulator/core.c:3128
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int _regulator_call_set_voltage_sel(struct regulator_dev *rdev, int uV, unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81658ae0)
Location: drivers/regulator/core.c:3083
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
```
**Symbols:**

```
ffffffff81658ae0-ffffffff81658b97: _regulator_call_set_voltage_sel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int _regulator_call_set_voltage_sel(struct regulator_dev *rdev, int uV, unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81678d70)
Location: drivers/regulator/core.c:3091
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
```
**Symbols:**

```
ffffffff81678d70-ffffffff81678e27: _regulator_call_set_voltage_sel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int _regulator_call_set_voltage_sel(struct regulator_dev *rdev, int uV, unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172b130)
Location: drivers/regulator/core.c:3122
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_sel_step
```
**Symbols:**

```
ffffffff8172b130-ffffffff8172b1e7: _regulator_call_set_voltage_sel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int _regulator_call_set_voltage_sel(struct regulator_dev *rdev, int uV, unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81747d40)
Location: drivers/regulator/core.c:3252
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_set_voltage_sel_step
```
**Symbols:**

```
ffffffff81747d40-ffffffff81747df7: _regulator_call_set_voltage_sel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int _regulator_call_set_voltage_sel(struct regulator_dev *rdev, int uV, unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172b5d0)
Location: drivers/regulator/core.c:3250
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
```
**Symbols:**

```
ffffffff8172b5d0-ffffffff8172b687: _regulator_call_set_voltage_sel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int _regulator_call_set_voltage_sel(struct regulator_dev *rdev, int uV, unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817a7ae0)
Location: drivers/regulator/core.c:3350
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
```
**Symbols:**

```
ffffffff817a7ae0-ffffffff817a7b97: _regulator_call_set_voltage_sel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int _regulator_call_set_voltage_sel(struct regulator_dev *rdev, int uV, unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff818e2340)
Location: drivers/regulator/core.c:3397
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
```
**Symbols:**

```
ffffffff818e2340-ffffffff818e2411: _regulator_call_set_voltage_sel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int _regulator_call_set_voltage_sel(struct regulator_dev *rdev, int uV, unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3c640)
Location: drivers/regulator/core.c:3429
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
```
**Symbols:**

```
ffffffff81a3c640-ffffffff81a3c711: _regulator_call_set_voltage_sel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int _regulator_call_set_voltage_sel(struct regulator_dev *rdev, int uV, unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a867d0)
Location: drivers/regulator/core.c:3495
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
```
**Symbols:**

```
ffffffff81a867d0-ffffffff81a868a1: _regulator_call_set_voltage_sel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int _regulator_call_set_voltage_sel(struct regulator_dev *rdev, int uV, unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ad8ee0)
Location: drivers/regulator/core.c:3501
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
```
**Symbols:**

```
ffffffff81ad8ee0-ffffffff81ad8fb0: _regulator_call_set_voltage_sel (STB_LOCAL)
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
int _regulator_call_set_voltage_sel(struct regulator_dev *rdev, int uV, unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010841970)
Location: drivers/regulator/core.c:3091
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
```
**Symbols:**

```
ffff800010841970-ffff800010841a40: _regulator_call_set_voltage_sel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _regulator_call_set_voltage_sel(struct regulator_dev *rdev, int uV, unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094afe4)
Location: drivers/regulator/core.c:3091
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
```
**Symbols:**

```
c094afe4-c094b0ac: _regulator_call_set_voltage_sel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _regulator_call_set_voltage_sel(struct regulator_dev *rdev, int uV, unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008dc120)
Location: drivers/regulator/core.c:3091
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
```
**Symbols:**

```
c0000000008dc120-c0000000008dc220: _regulator_call_set_voltage_sel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int _regulator_call_set_voltage_sel(struct regulator_dev *rdev, int uV, unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe0005235ce)
Location: drivers/regulator/core.c:3091
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
```
**Symbols:**

```
ffffffe0005235ce-ffffffe00052365e: _regulator_call_set_voltage_sel (STB_LOCAL)
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
int _regulator_call_set_voltage_sel(struct regulator_dev *rdev, int uV, unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8163e870)
Location: drivers/regulator/core.c:3091
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
```
**Symbols:**

```
ffffffff8163e870-ffffffff8163e927: _regulator_call_set_voltage_sel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int _regulator_call_set_voltage_sel(struct regulator_dev *rdev, int uV, unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8161ec50)
Location: drivers/regulator/core.c:3091
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
```
**Symbols:**

```
ffffffff8161ec50-ffffffff8161ed07: _regulator_call_set_voltage_sel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int _regulator_call_set_voltage_sel(struct regulator_dev *rdev, int uV, unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8166cbb0)
Location: drivers/regulator/core.c:3091
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
```
**Symbols:**

```
ffffffff8166cbb0-ffffffff8166cc67: _regulator_call_set_voltage_sel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int _regulator_call_set_voltage_sel(struct regulator_dev *rdev, int uV, unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816871e0)
Location: drivers/regulator/core.c:3091
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
```
**Symbols:**

```
ffffffff816871e0-ffffffff81687297: _regulator_call_set_voltage_sel (STB_LOCAL)
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
