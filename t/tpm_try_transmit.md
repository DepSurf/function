# Function: <code>tpm_try_transmit</code>

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
In drivers/char/tpm/tpm-interface.c (ffffffff8165726b)
Location: drivers/char/tpm/tpm-interface.c:429
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
In drivers/char/tpm/tpm-interface.c (ffffffff816765bf)
Location: drivers/char/tpm/tpm-interface.c:164
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
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
In drivers/char/tpm/tpm-interface.c (ffffffff816ac37e)
Location: drivers/char/tpm/tpm-interface.c:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
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
In drivers/char/tpm/tpm-interface.c (ffffffff816cf0de)
Location: drivers/char/tpm/tpm-interface.c:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_try_transmit(struct tpm_chip *chip, void *buf, size_t bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:61
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
**Symbols:**

```
ffffffff81783ec0-ffffffff81784084: tpm_try_transmit (STB_LOCAL)
ffffffff8178441f-ffffffff817844b1: tpm_try_transmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_try_transmit(struct tpm_chip *chip, void *buf, size_t bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:61
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
**Symbols:**

```
ffffffff8179b410-ffffffff8179b5d4: tpm_try_transmit (STB_LOCAL)
ffffffff81c0a37c-ffffffff81c0a40e: tpm_try_transmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_try_transmit(struct tpm_chip *chip, void *buf, size_t bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:61
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
**Symbols:**

```
ffffffff8177df50-ffffffff8177e117: tpm_try_transmit (STB_LOCAL)
ffffffff81bfbe0f-ffffffff81bfbea1: tpm_try_transmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_try_transmit(struct tpm_chip *chip, void *buf, size_t bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:61
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
**Symbols:**

```
ffffffff81804140-ffffffff8180430c: tpm_try_transmit (STB_LOCAL)
ffffffff81cfcac9-ffffffff81cfcb5b: tpm_try_transmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t tpm_try_transmit(struct tpm_chip *chip, void *buf, size_t bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (0)
Location: drivers/char/tpm/tpm-interface.c:61
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
**Symbols:**

```
ffffffff81943a70-ffffffff81943c71: tpm_try_transmit (STB_LOCAL)
ffffffff81ec52ac-ffffffff81ec5340: tpm_try_transmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t tpm_try_transmit(struct tpm_chip *chip, void *buf, size_t bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81aa65a0)
Location: drivers/char/tpm/tpm-interface.c:61
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
**Symbols:**

```
ffffffff81aa65a0-ffffffff81aa6888: tpm_try_transmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t tpm_try_transmit(struct tpm_chip *chip, void *buf, size_t bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81af1df0)
Location: drivers/char/tpm/tpm-interface.c:61
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
**Symbols:**

```
ffffffff81af1df0-ffffffff81af20d8: tpm_try_transmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t tpm_try_transmit(struct tpm_chip *chip, void *buf, size_t bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81b45380)
Location: drivers/char/tpm/tpm-interface.c:61
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
**Symbols:**

```
ffffffff81b45380-ffffffff81b45668: tpm_try_transmit (STB_LOCAL)
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
In drivers/char/tpm/tpm-interface.c (ffff8000108b970c)
Location: drivers/char/tpm/tpm-interface.c:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
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
In drivers/char/tpm/tpm-interface.c (c09b2b28)
Location: drivers/char/tpm/tpm-interface.c:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
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
In drivers/char/tpm/tpm-interface.c (c00000000095a674)
Location: drivers/char/tpm/tpm-interface.c:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
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
In drivers/char/tpm/tpm-interface.c (ffffffe000569b02)
Location: drivers/char/tpm/tpm-interface.c:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
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
In drivers/char/tpm/tpm-interface.c (ffffffff81694b2e)
Location: drivers/char/tpm/tpm-interface.c:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
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
In drivers/char/tpm/tpm-interface.c (ffffffff8167251e)
Location: drivers/char/tpm/tpm-interface.c:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
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
In drivers/char/tpm/tpm-interface.c (ffffffff816c2d9e)
Location: drivers/char/tpm/tpm-interface.c:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
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
In drivers/char/tpm/tpm-interface.c (ffffffff816dd36e)
Location: drivers/char/tpm/tpm-interface.c:60
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
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
