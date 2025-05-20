# Function: <code>regulator_init_coupling</code>

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
In drivers/regulator/core.c (ffffffff81627e62)
Location: drivers/regulator/core.c:4815
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
In drivers/regulator/core.c (ffffffff8165c110)
Location: drivers/regulator/core.c:4910
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
In drivers/regulator/core.c (ffffffff8167def7)
Location: drivers/regulator/core.c:4920
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8172f5d2)
Location: drivers/regulator/core.c:4965
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8174c222)
Location: drivers/regulator/core.c:5100
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
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
In drivers/regulator/core.c (ffffffff8172fa32)
Location: drivers/regulator/core.c:5102
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
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
In drivers/regulator/core.c (ffffffff817af82e)
Location: drivers/regulator/core.c:5239
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
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
In drivers/regulator/core.c (ffffffff818eabe3)
Location: drivers/regulator/core.c:5304
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
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
In drivers/regulator/core.c (ffffffff81a418a0)
Location: drivers/regulator/core.c:5345
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
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
In drivers/regulator/core.c (ffffffff81a8b980)
Location: drivers/regulator/core.c:5409
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
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
In drivers/regulator/core.c (ffffffff81ade152)
Location: drivers/regulator/core.c:5468
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
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
In drivers/regulator/core.c (ffff800010847c20)
Location: drivers/regulator/core.c:4920
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regulator_init_coupling(struct regulator_dev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094c0ac)
Location: drivers/regulator/core.c:4920
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_register
```
**Symbols:**

```
c094c0ac-c094c24c: regulator_init_coupling (STB_LOCAL)
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
In drivers/regulator/core.c (c0000000008e4218)
Location: drivers/regulator/core.c:4920
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
In drivers/regulator/core.c (ffffffe00052806a)
Location: drivers/regulator/core.c:4920
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
In drivers/regulator/core.c (ffffffff81643957)
Location: drivers/regulator/core.c:4920
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
In drivers/regulator/core.c (ffffffff81623dd7)
Location: drivers/regulator/core.c:4920
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
In drivers/regulator/core.c (ffffffff81671d37)
Location: drivers/regulator/core.c:4920
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
In drivers/regulator/core.c (ffffffff8168c397)
Location: drivers/regulator/core.c:4920
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
