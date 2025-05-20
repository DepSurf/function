# Function: <code>of_get_regulator</code>

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
In drivers/regulator/core.c (ffffffff814d84ec)
Location: drivers/regulator/core.c:183
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
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
In drivers/regulator/core.c (ffffffff815292a9)
Location: drivers/regulator/core.c:196
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
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
In drivers/regulator/core.c (ffffffff815557b9)
Location: drivers/regulator/core.c:196
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
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
In drivers/regulator/core.c (ffffffff81569dd0)
Location: drivers/regulator/core.c:196
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
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
In drivers/regulator/core.c (ffffffff815cdfb0)
Location: drivers/regulator/core.c:196
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
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
In drivers/regulator/core.c (ffffffff81606430)
Location: drivers/regulator/core.c:239
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
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
In drivers/regulator/core.c (ffffffff81621650)
Location: drivers/regulator/core.c:419
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
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
In drivers/regulator/core.c (ffffffff816548e5)
Location: drivers/regulator/core.c:401
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
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
In drivers/regulator/core.c (ffffffff81676dd5)
Location: drivers/regulator/core.c:405
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct device_node *of_get_regulator(struct device *dev, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817277e0)
Location: drivers/regulator/core.c:408
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_dev_lookup
```
**Symbols:**

```
ffffffff817277e0-ffffffff81727887: of_get_regulator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct device_node *of_get_regulator(struct device *dev, const char *supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81744260)
Location: drivers/regulator/core.c:407
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_dev_lookup
```
**Symbols:**

```
ffffffff81744260-ffffffff81744307: of_get_regulator (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81727cb2)
Location: drivers/regulator/core.c:407
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817a6e02)
Location: drivers/regulator/core.c:397
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff818e1382)
Location: drivers/regulator/core.c:398
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a36512)
Location: drivers/regulator/core.c:398
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a7ffc2)
Location: drivers/regulator/core.c:464
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ad2532)
Location: drivers/regulator/core.c:466
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
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
In drivers/regulator/core.c (ffff80001083fcac)
Location: drivers/regulator/core.c:405
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
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
In drivers/regulator/core.c (c0949508)
Location: drivers/regulator/core.c:405
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
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
In drivers/regulator/core.c (c0000000008d9384)
Location: drivers/regulator/core.c:405
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
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
In drivers/regulator/core.c (ffffffe000521c7c)
Location: drivers/regulator/core.c:405
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
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
In drivers/regulator/core.c (ffffffff8163cac5)
Location: drivers/regulator/core.c:405
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
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
In drivers/regulator/core.c (ffffffff8161ccb5)
Location: drivers/regulator/core.c:405
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
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
In drivers/regulator/core.c (ffffffff8166ac15)
Location: drivers/regulator/core.c:405
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
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
In drivers/regulator/core.c (ffffffff816851d5)
Location: drivers/regulator/core.c:405
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_dev_lookup
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
</ul>
