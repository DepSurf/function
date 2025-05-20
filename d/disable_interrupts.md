# Function: <code>disable_interrupts</code>

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
In drivers/char/tpm/tpm_tis.c (ffffffff81529b3a)
Location: drivers/char/tpm/tpm_tis.c:360
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_send
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff8157c3de)
Location: drivers/char/tpm/tpm_tis_core.c:312
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff815a888e)
Location: drivers/char/tpm/tpm_tis_core.c:334
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff815bdffe)
Location: drivers/char/tpm/tpm_tis_core.c:323
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff816246ac)
Location: drivers/char/tpm/tpm_tis_core.c:326
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff8165e9cc)
Location: drivers/char/tpm/tpm_tis_core.c:434
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167ce7c)
Location: drivers/char/tpm/tpm_tis_core.c:434
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff816b3b64)
Location: drivers/char/tpm/tpm_tis_core.c:430
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff816d6844)
Location: drivers/char/tpm/tpm_tis_core.c:430
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void disable_interrupts(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8178a1e0)
Location: drivers/char/tpm/tpm_tis_core.c:430
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff8178a1e0-ffffffff8178a292: disable_interrupts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void disable_interrupts(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff817a10d0)
Location: drivers/char/tpm/tpm_tis_core.c:397
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff817a10d0-ffffffff817a1182: disable_interrupts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void disable_interrupts(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81783d50)
Location: drivers/char/tpm/tpm_tis_core.c:408
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff81783d50-ffffffff81783e02: disable_interrupts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void disable_interrupts(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8180a780)
Location: drivers/char/tpm/tpm_tis_core.c:409
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff8180a780-ffffffff8180a832: disable_interrupts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void disable_interrupts(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8194af60)
Location: drivers/char/tpm/tpm_tis_core.c:409
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff8194af60-ffffffff8194b056: disable_interrupts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void disable_interrupts(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81aae380)
Location: drivers/char/tpm/tpm_tis_core.c:417
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff81aae380-ffffffff81aae476: disable_interrupts (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/char/tpm/tpm_tis_core.c (ffff8000108c239c)
Location: drivers/char/tpm/tpm_tis_core.c:430
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
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
In drivers/char/tpm/tpm_tis_core.c (c09ba258)
Location: drivers/char/tpm/tpm_tis_core.c:430
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
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
In drivers/char/tpm/tpm_tis_core.c (c000000000963f7c)
Location: drivers/char/tpm/tpm_tis_core.c:430
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
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
In drivers/char/tpm/tpm_tis_core.c (ffffffe000572edc)
Location: drivers/char/tpm/tpm_tis_core.c:430
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff8169c294)
Location: drivers/char/tpm/tpm_tis_core.c:430
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff81679c84)
Location: drivers/char/tpm/tpm_tis_core.c:430
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff816ca504)
Location: drivers/char/tpm/tpm_tis_core.c:430
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
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
In drivers/char/tpm/tpm_tis_core.c (ffffffff816e49d4)
Location: drivers/char/tpm/tpm_tis_core.c:430
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
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
</ul>
