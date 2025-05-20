# Function: <code>response_parse</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8145e7b6)
Location: block/sed-opal.c:788
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
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
In block/sed-opal.c (ffffffff8148a676)
Location: block/sed-opal.c:800
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
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
In block/sed-opal.c (ffffffff814bf2b5)
Location: block/sed-opal.c:797
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
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
In block/sed-opal.c (ffffffff814d3745)
Location: block/sed-opal.c:797
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
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
In block/sed-opal.c (ffffffff81500565)
Location: block/sed-opal.c:844
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
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
In block/sed-opal.c (ffffffff8151e4c5)
Location: block/sed-opal.c:846
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff8157cce0)
Location: block/sed-opal.c:848
Inline: True
Direct callers:
  - block/sed-opal.c:end_session_cont
```
**Symbols:**

```
ffffffff8157cce0-ffffffff8157cf4d: response_parse.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff81599d20)
Location: block/sed-opal.c:848
Inline: True
Direct callers:
  - block/sed-opal.c:end_session_cont
```
**Symbols:**

```
ffffffff81599d20-ffffffff81599f8d: response_parse.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff815a0910)
Location: block/sed-opal.c:848
Inline: True
Direct callers:
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffff815a0910-ffffffff815a0bdd: response_parse.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (0)
Location: block/sed-opal.c:848
Inline: True
Direct callers:
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffff81609100-ffffffff81609411: response_parse.constprop.0 (STB_LOCAL)
ffffffff81cda551-ffffffff81cda582: response_parse.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (0)
Location: block/sed-opal.c:848
Inline: True
Direct callers:
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffff816bd000-ffffffff816bd330: response_parse.constprop.0 (STB_LOCAL)
ffffffff81e8e0f9-ffffffff81e8e130: response_parse.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (0)
Location: block/sed-opal.c:888
Inline: True
Direct callers:
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffff8177dc70-ffffffff8177df9d: response_parse.constprop.0 (STB_LOCAL)
ffffffff8207737b-ffffffff820773b2: response_parse.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (0)
Location: block/sed-opal.c:896
Inline: True
Direct callers:
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffff817bd7d0-ffffffff817bdafd: response_parse.constprop.0 (STB_LOCAL)
ffffffff820f73c0-ffffffff820f73f7: response_parse.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (0)
Location: block/sed-opal.c:1009
Inline: True
Direct callers:
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffffffff81801ef0-ffffffff81802255: response_parse.constprop.0 (STB_LOCAL)
ffffffff821d4de8-ffffffff821d4e1f: response_parse.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffff800010627018)
Location: block/sed-opal.c:846
Inline: True
Direct callers:
  - block/sed-opal.c:parse_and_check_status
```
**Symbols:**

```
ffff800010627018-ffff800010627310: response_parse.constprop.0 (STB_LOCAL)
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
In block/sed-opal.c (c07cee90)
Location: block/sed-opal.c:846
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
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
In block/sed-opal.c (c0000000007c8664)
Location: block/sed-opal.c:846
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
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
In block/sed-opal.c (ffffffe000458c36)
Location: block/sed-opal.c:846
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
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
In block/sed-opal.c (ffffffff81516aa5)
Location: block/sed-opal.c:846
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
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
In block/sed-opal.c (ffffffff81506db5)
Location: block/sed-opal.c:846
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
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
In block/sed-opal.c (ffffffff81512b35)
Location: block/sed-opal.c:846
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
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
In block/sed-opal.c (ffffffff8152c2f5)
Location: block/sed-opal.c:846
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
```
</details>
</li>
</ul>

## Differences
