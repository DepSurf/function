# Function: <code>set_consumer_device_supply</code>

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
In drivers/regulator/core.c (ffffffff814dd5bd)
Location: drivers/regulator/core.c:1191
Inline: True
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
In drivers/regulator/core.c (ffffffff8152e90d)
Location: drivers/regulator/core.c:1190
Inline: True
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
In drivers/regulator/core.c (ffffffff8155af76)
Location: drivers/regulator/core.c:1191
Inline: True
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
In drivers/regulator/core.c (ffffffff8156f241)
Location: drivers/regulator/core.c:1191
Inline: True
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
In drivers/regulator/core.c (ffffffff815d34e3)
Location: drivers/regulator/core.c:1191
Inline: True
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
In drivers/regulator/core.c (ffffffff8160b46d)
Location: drivers/regulator/core.c:1256
Inline: True
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
In drivers/regulator/core.c (ffffffff81627eb0)
Location: drivers/regulator/core.c:1465
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8165c19d)
Location: drivers/regulator/core.c:1447
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8167df84)
Location: drivers/regulator/core.c:1455
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_consumer_device_supply(struct regulator_dev *rdev, const char *consumer_dev_name, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172aad0)
Location: drivers/regulator/core.c:1462
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff8172aad0-ffffffff8172ad03: set_consumer_device_supply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_consumer_device_supply(struct regulator_dev *rdev, const char *consumer_dev_name, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81747640)
Location: drivers/regulator/core.c:1488
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff81747640-ffffffff81747873: set_consumer_device_supply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_consumer_device_supply(struct regulator_dev *rdev, const char *consumer_dev_name, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172aec0)
Location: drivers/regulator/core.c:1499
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff8172aec0-ffffffff8172b0f3: set_consumer_device_supply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_consumer_device_supply(struct regulator_dev *rdev, const char *consumer_dev_name, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817ad0c0)
Location: drivers/regulator/core.c:1599
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff817ad0c0-ffffffff817ad2f0: set_consumer_device_supply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int set_consumer_device_supply(struct regulator_dev *rdev, const char *consumer_dev_name, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff818e8360)
Location: drivers/regulator/core.c:1643
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff818e8360-ffffffff818e85b4: set_consumer_device_supply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int set_consumer_device_supply(struct regulator_dev *rdev, const char *consumer_dev_name, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3b880)
Location: drivers/regulator/core.c:1669
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff81a3b880-ffffffff81a3bad4: set_consumer_device_supply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int set_consumer_device_supply(struct regulator_dev *rdev, const char *consumer_dev_name, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a84670)
Location: drivers/regulator/core.c:1734
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff81a84670-ffffffff81a848c4: set_consumer_device_supply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int set_consumer_device_supply(struct regulator_dev *rdev, const char *consumer_dev_name, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ad6e20)
Location: drivers/regulator/core.c:1736
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
ffffffff81ad6e20-ffffffff81ad70a3: set_consumer_device_supply (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010847ca0)
Location: drivers/regulator/core.c:1455
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0951574)
Location: drivers/regulator/core.c:1455
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008e4624)
Location: drivers/regulator/core.c:1455
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe0005281e6)
Location: drivers/regulator/core.c:1455
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff816439e4)
Location: drivers/regulator/core.c:1455
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81623e64)
Location: drivers/regulator/core.c:1455
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81671dc4)
Location: drivers/regulator/core.c:1455
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8168c424)
Location: drivers/regulator/core.c:1455
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
