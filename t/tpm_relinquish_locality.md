# Function: <code>tpm_relinquish_locality</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:390
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
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
In drivers/char/tpm/tpm-interface.c (ffffffff816769f0)
Location: drivers/char/tpm/tpm-interface.c:125
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void tpm_relinquish_locality(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (0)
Location: drivers/char/tpm/tpm-chip.c:50
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_stop
  - drivers/char/tpm/tpm-chip.c:tpm_chip_start
```
**Symbols:**

```
ffffffff816aac60-ffffffff816aac9e: tpm_relinquish_locality (STB_LOCAL)
ffffffff816ab703-ffffffff816ab720: tpm_relinquish_locality.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void tpm_relinquish_locality(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (0)
Location: drivers/char/tpm/tpm-chip.c:50
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_stop
  - drivers/char/tpm/tpm-chip.c:tpm_chip_start
```
**Symbols:**

```
ffffffff816cd9a0-ffffffff816cd9de: tpm_relinquish_locality (STB_LOCAL)
ffffffff816ce443-ffffffff816ce460: tpm_relinquish_locality.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void tpm_relinquish_locality(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (0)
Location: drivers/char/tpm/tpm-chip.c:50
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_stop
  - drivers/char/tpm/tpm-chip.c:tpm_chip_start
```
**Symbols:**

```
ffffffff81782870-ffffffff817828b1: tpm_relinquish_locality (STB_LOCAL)
ffffffff81783363-ffffffff81783380: tpm_relinquish_locality.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void tpm_relinquish_locality(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (0)
Location: drivers/char/tpm/tpm-chip.c:50
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_stop
  - drivers/char/tpm/tpm-chip.c:tpm_chip_start
```
**Symbols:**

```
ffffffff81799ec0-ffffffff81799f01: tpm_relinquish_locality (STB_LOCAL)
ffffffff81c0a274-ffffffff81c0a291: tpm_relinquish_locality.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void tpm_relinquish_locality(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (0)
Location: drivers/char/tpm/tpm-chip.c:50
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_stop
  - drivers/char/tpm/tpm-chip.c:tpm_chip_start
```
**Symbols:**

```
ffffffff8177ca40-ffffffff8177ca81: tpm_relinquish_locality (STB_LOCAL)
ffffffff81bfbcfb-ffffffff81bfbd18: tpm_relinquish_locality.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tpm_relinquish_locality(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (0)
Location: drivers/char/tpm/tpm-chip.c:50
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_stop
  - drivers/char/tpm/tpm-chip.c:tpm_chip_start
```
**Symbols:**

```
ffffffff81802c10-ffffffff81802c51: tpm_relinquish_locality (STB_LOCAL)
ffffffff81cfc985-ffffffff81cfc9a2: tpm_relinquish_locality.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tpm_relinquish_locality(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (0)
Location: drivers/char/tpm/tpm-chip.c:50
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_stop
  - drivers/char/tpm/tpm-chip.c:tpm_chip_start
```
**Symbols:**

```
ffffffff81942450-ffffffff819424ad: tpm_relinquish_locality (STB_LOCAL)
ffffffff81ec51c0-ffffffff81ec51dd: tpm_relinquish_locality.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tpm_relinquish_locality(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81aa4b10)
Location: drivers/char/tpm/tpm-chip.c:50
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_stop
  - drivers/char/tpm/tpm-chip.c:tpm_chip_start
```
**Symbols:**

```
ffffffff81aa4b10-ffffffff81aa4b9f: tpm_relinquish_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tpm_relinquish_locality(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81af0430)
Location: drivers/char/tpm/tpm-chip.c:50
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_stop
  - drivers/char/tpm/tpm-chip.c:tpm_chip_start
```
**Symbols:**

```
ffffffff81af0430-ffffffff81af04bf: tpm_relinquish_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tpm_relinquish_locality(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81b43970)
Location: drivers/char/tpm/tpm-chip.c:55
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_stop
  - drivers/char/tpm/tpm-chip.c:tpm_chip_start
```
**Symbols:**

```
ffffffff81b43970-ffffffff81b439ff: tpm_relinquish_locality (STB_LOCAL)
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
void tpm_relinquish_locality(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffff8000108b7ac8)
Location: drivers/char/tpm/tpm-chip.c:50
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_stop
  - drivers/char/tpm/tpm-chip.c:tpm_chip_start
```
**Symbols:**

```
ffff8000108b7ac8-ffff8000108b7b30: tpm_relinquish_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tpm_relinquish_locality(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (c09b13d4)
Location: drivers/char/tpm/tpm-chip.c:50
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_stop
  - drivers/char/tpm/tpm-chip.c:tpm_chip_start
```
**Symbols:**

```
c09b13d4-c09b1438: tpm_relinquish_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tpm_relinquish_locality(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (c0000000009582c0)
Location: drivers/char/tpm/tpm-chip.c:50
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_stop
  - drivers/char/tpm/tpm-chip.c:tpm_chip_start
```
**Symbols:**

```
c0000000009582c0-c000000000958350: tpm_relinquish_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tpm_relinquish_locality(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffe00056843a)
Location: drivers/char/tpm/tpm-chip.c:50
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_stop
  - drivers/char/tpm/tpm-chip.c:tpm_chip_start
```
**Symbols:**

```
ffffffe00056843a-ffffffe000568498: tpm_relinquish_locality (STB_LOCAL)
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
void tpm_relinquish_locality(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (0)
Location: drivers/char/tpm/tpm-chip.c:50
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_stop
  - drivers/char/tpm/tpm-chip.c:tpm_chip_start
```
**Symbols:**

```
ffffffff816933f0-ffffffff8169342e: tpm_relinquish_locality (STB_LOCAL)
ffffffff81693e93-ffffffff81693eb0: tpm_relinquish_locality.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void tpm_relinquish_locality(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (0)
Location: drivers/char/tpm/tpm-chip.c:50
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_stop
  - drivers/char/tpm/tpm-chip.c:tpm_chip_start
```
**Symbols:**

```
ffffffff81670de0-ffffffff81670e1e: tpm_relinquish_locality (STB_LOCAL)
ffffffff81671883-ffffffff816718a0: tpm_relinquish_locality.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void tpm_relinquish_locality(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (0)
Location: drivers/char/tpm/tpm-chip.c:50
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_stop
  - drivers/char/tpm/tpm-chip.c:tpm_chip_start
```
**Symbols:**

```
ffffffff816c1660-ffffffff816c169e: tpm_relinquish_locality (STB_LOCAL)
ffffffff816c2103-ffffffff816c2120: tpm_relinquish_locality.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void tpm_relinquish_locality(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (0)
Location: drivers/char/tpm/tpm-chip.c:50
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_stop
  - drivers/char/tpm/tpm-chip.c:tpm_chip_start
```
**Symbols:**

```
ffffffff816dbc30-ffffffff816dbc6e: tpm_relinquish_locality (STB_LOCAL)
ffffffff816dc6d3-ffffffff816dc6f0: tpm_relinquish_locality.cold (STB_LOCAL)
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
