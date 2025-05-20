# Function: <code>tpm2_startup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tpm2_startup(struct tpm_chip *chip, u16 startup_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81525bb0)
Location: drivers/char/tpm/tpm2-cmd.c:731
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
```
**Symbols:**

```
ffffffff81525bb0-ffffffff81525c28: tpm2_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81578ff0)
Location: drivers/char/tpm/tpm2-cmd.c:731
Inline: True
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
```
**Symbols:**

```
ffffffff81578ff0-ffffffff81579066: tpm2_startup.constprop.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815a5510)
Location: drivers/char/tpm/tpm2-cmd.c:761
Inline: True
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
```
**Symbols:**

```
ffffffff815a5510-ffffffff815a5588: tpm2_startup.constprop.6 (STB_LOCAL)
```
</details>
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816792d6)
Location: drivers/char/tpm/tpm2-cmd.c:960
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816afa4c)
Location: drivers/char/tpm/tpm2-cmd.c:996
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816d274c)
Location: drivers/char/tpm/tpm2-cmd.c:1002
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff8178699c)
Location: drivers/char/tpm/tpm2-cmd.c:697
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81c0a6a5)
Location: drivers/char/tpm/tpm2-cmd.c:697
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81bfc138)
Location: drivers/char/tpm/tpm2-cmd.c:698
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81cfce61)
Location: drivers/char/tpm/tpm2-cmd.c:698
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81ec56d7)
Location: drivers/char/tpm/tpm2-cmd.c:707
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81aa969c)
Location: drivers/char/tpm/tpm2-cmd.c:707
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81af4ec8)
Location: drivers/char/tpm/tpm2-cmd.c:707
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81b48488)
Location: drivers/char/tpm/tpm2-cmd.c:707
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
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
In drivers/char/tpm/tpm2-cmd.c (ffff8000108bd1a0)
Location: drivers/char/tpm/tpm2-cmd.c:1002
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
In drivers/char/tpm/tpm2-cmd.c (c09b65a4)
Location: drivers/char/tpm/tpm2-cmd.c:1002
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
In drivers/char/tpm/tpm2-cmd.c (c00000000095ec58)
Location: drivers/char/tpm/tpm2-cmd.c:1002
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
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056f040)
Location: drivers/char/tpm/tpm2-cmd.c:1002
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff8169819c)
Location: drivers/char/tpm/tpm2-cmd.c:1002
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81675b8c)
Location: drivers/char/tpm/tpm2-cmd.c:1002
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816c640c)
Location: drivers/char/tpm/tpm2-cmd.c:1002
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816e08fc)
Location: drivers/char/tpm/tpm2-cmd.c:1002
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
</ul>
