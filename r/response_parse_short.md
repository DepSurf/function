# Function: <code>response_parse_short</code>

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
In block/sed-opal.c (ffffffff8145e9c6)
Location: block/sed-opal.c:713
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
In block/sed-opal.c (ffffffff8148a886)
Location: block/sed-opal.c:725
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
In block/sed-opal.c (ffffffff814bf493)
Location: block/sed-opal.c:722
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
In block/sed-opal.c (ffffffff814d3923)
Location: block/sed-opal.c:722
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
In block/sed-opal.c (ffffffff81500743)
Location: block/sed-opal.c:769
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
In block/sed-opal.c (ffffffff8151e6a3)
Location: block/sed-opal.c:771
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t response_parse_short(struct opal_resp_tok *tok, const u8 *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8157c610)
Location: block/sed-opal.c:773
Inline: False
```
**Symbols:**

```
ffffffff8157c610-ffffffff8157c6b7: response_parse_short (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t response_parse_short(struct opal_resp_tok *tok, const u8 *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81599650)
Location: block/sed-opal.c:773
Inline: False
```
**Symbols:**

```
ffffffff81599650-ffffffff815996f7: response_parse_short (STB_LOCAL)
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
In block/sed-opal.c (ffffffff815a0a64)
Location: block/sed-opal.c:773
Inline: True
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
In block/sed-opal.c (ffffffff81609250)
Location: block/sed-opal.c:773
Inline: True
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
In block/sed-opal.c (ffffffff816bd149)
Location: block/sed-opal.c:773
Inline: True
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
In block/sed-opal.c (ffffffff8177dd84)
Location: block/sed-opal.c:813
Inline: True
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
In block/sed-opal.c (ffffffff817bd8e4)
Location: block/sed-opal.c:821
Inline: True
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
In block/sed-opal.c (ffffffff8180201c)
Location: block/sed-opal.c:934
Inline: True
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
In block/sed-opal.c (ffff800010627214)
Location: block/sed-opal.c:771
Inline: True
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
In block/sed-opal.c (c07cf03c)
Location: block/sed-opal.c:771
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
In block/sed-opal.c (c0000000007c89b0)
Location: block/sed-opal.c:771
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
In block/sed-opal.c (ffffffe000458d26)
Location: block/sed-opal.c:771
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
In block/sed-opal.c (ffffffff81516c83)
Location: block/sed-opal.c:771
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
In block/sed-opal.c (ffffffff81506f93)
Location: block/sed-opal.c:771
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
In block/sed-opal.c (ffffffff81512d13)
Location: block/sed-opal.c:771
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
In block/sed-opal.c (ffffffff8152c4d3)
Location: block/sed-opal.c:771
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
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
