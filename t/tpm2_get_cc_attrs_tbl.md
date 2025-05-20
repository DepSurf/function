# Function: <code>tpm2_get_cc_attrs_tbl</code>

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
In drivers/char/tpm/tpm2-cmd.c (ffffffff815bad91)
Location: drivers/char/tpm/tpm2-cmd.c:1008
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816213e7)
Location: drivers/char/tpm/tpm2-cmd.c:983
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff8165b1b5)
Location: drivers/char/tpm/tpm2-cmd.c:965
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff8167916c)
Location: drivers/char/tpm/tpm2-cmd.c:885
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816af78c)
Location: drivers/char/tpm/tpm2-cmd.c:922
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816d247c)
Location: drivers/char/tpm/tpm2-cmd.c:924
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tpm2_get_cc_attrs_tbl(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81785a00)
Location: drivers/char/tpm/tpm2-cmd.c:618
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
```
**Symbols:**

```
ffffffff81785a00-ffffffff81785c44: tpm2_get_cc_attrs_tbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tpm2_get_cc_attrs_tbl(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8179cc00)
Location: drivers/char/tpm/tpm2-cmd.c:618
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
```
**Symbols:**

```
ffffffff8179cc00-ffffffff8179ce44: tpm2_get_cc_attrs_tbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tpm2_get_cc_attrs_tbl(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8177f6d0)
Location: drivers/char/tpm/tpm2-cmd.c:618
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
```
**Symbols:**

```
ffffffff8177f6d0-ffffffff8177f924: tpm2_get_cc_attrs_tbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tpm2_get_cc_attrs_tbl(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81805a60)
Location: drivers/char/tpm/tpm2-cmd.c:618
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
```
**Symbols:**

```
ffffffff81805a60-ffffffff81805cb4: tpm2_get_cc_attrs_tbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tpm2_get_cc_attrs_tbl(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81945500)
Location: drivers/char/tpm/tpm2-cmd.c:627
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
```
**Symbols:**

```
ffffffff81945500-ffffffff8194576a: tpm2_get_cc_attrs_tbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm2_get_cc_attrs_tbl(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81aa8530)
Location: drivers/char/tpm/tpm2-cmd.c:627
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
```
**Symbols:**

```
ffffffff81aa8530-ffffffff81aa879a: tpm2_get_cc_attrs_tbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm2_get_cc_attrs_tbl(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81af3d60)
Location: drivers/char/tpm/tpm2-cmd.c:627
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
```
**Symbols:**

```
ffffffff81af3d60-ffffffff81af3fca: tpm2_get_cc_attrs_tbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm2_get_cc_attrs_tbl(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81b47320)
Location: drivers/char/tpm/tpm2-cmd.c:627
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
```
**Symbols:**

```
ffffffff81b47320-ffffffff81b4758a: tpm2_get_cc_attrs_tbl (STB_GLOBAL)
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
In drivers/char/tpm/tpm2-cmd.c (ffff8000108bcf18)
Location: drivers/char/tpm/tpm2-cmd.c:924
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
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
In drivers/char/tpm/tpm2-cmd.c (c09b631c)
Location: drivers/char/tpm/tpm2-cmd.c:924
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
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
In drivers/char/tpm/tpm2-cmd.c (c00000000095ed70)
Location: drivers/char/tpm/tpm2-cmd.c:924
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
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
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056f188)
Location: drivers/char/tpm/tpm2-cmd.c:924
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81697ecc)
Location: drivers/char/tpm/tpm2-cmd.c:924
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816758bc)
Location: drivers/char/tpm/tpm2-cmd.c:924
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816c613c)
Location: drivers/char/tpm/tpm2-cmd.c:924
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816e063c)
Location: drivers/char/tpm/tpm2-cmd.c:924
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
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
