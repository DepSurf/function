# Function: <code>tpm2_get_pcr_allocation</code>

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
In drivers/char/tpm/tpm2-cmd.c (ffffffff815babff)
Location: drivers/char/tpm/tpm2-cmd.c:944
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816212d3)
Location: drivers/char/tpm/tpm2-cmd.c:919
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff8165b08f)
Location: drivers/char/tpm/tpm2-cmd.c:901
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81679043)
Location: drivers/char/tpm/tpm2-cmd.c:821
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t tpm2_get_pcr_allocation(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:843
Inline: False
```
**Symbols:**

```
ffffffff816afa40-ffffffff816afa4c: tpm2_get_pcr_allocation.cold (STB_LOCAL)
ffffffff816af440-ffffffff816af6e9: tpm2_get_pcr_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t tpm2_get_pcr_allocation(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:845
Inline: False
```
**Symbols:**

```
ffffffff816d2740-ffffffff816d274c: tpm2_get_pcr_allocation.cold (STB_LOCAL)
ffffffff816d2130-ffffffff816d23d9: tpm2_get_pcr_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t tpm2_get_pcr_allocation(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:539
Inline: False
```
**Symbols:**

```
ffffffff81786990-ffffffff8178699c: tpm2_get_pcr_allocation.cold (STB_LOCAL)
ffffffff81786510-ffffffff8178686a: tpm2_get_pcr_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t tpm2_get_pcr_allocation(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:539
Inline: False
```
**Symbols:**

```
ffffffff81c0a699-ffffffff81c0a6a5: tpm2_get_pcr_allocation.cold (STB_LOCAL)
ffffffff8179d710-ffffffff8179da6a: tpm2_get_pcr_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t tpm2_get_pcr_allocation(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:539
Inline: False
```
**Symbols:**

```
ffffffff81bfc12c-ffffffff81bfc138: tpm2_get_pcr_allocation.cold (STB_LOCAL)
ffffffff81780200-ffffffff81780587: tpm2_get_pcr_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t tpm2_get_pcr_allocation(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:539
Inline: False
```
**Symbols:**

```
ffffffff81cfce55-ffffffff81cfce61: tpm2_get_pcr_allocation.cold (STB_LOCAL)
ffffffff818065d0-ffffffff81806995: tpm2_get_pcr_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t tpm2_get_pcr_allocation(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:548
Inline: False
```
**Symbols:**

```
ffffffff81ec56a7-ffffffff81ec56b3: tpm2_get_pcr_allocation.cold (STB_LOCAL)
ffffffff81946110-ffffffff819464ea: tpm2_get_pcr_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t tpm2_get_pcr_allocation(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81aa91b0)
Location: drivers/char/tpm/tpm2-cmd.c:548
Inline: False
```
**Symbols:**

```
ffffffff81aa91b0-ffffffff81aa95a4: tpm2_get_pcr_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t tpm2_get_pcr_allocation(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81af49e0)
Location: drivers/char/tpm/tpm2-cmd.c:548
Inline: False
```
**Symbols:**

```
ffffffff81af49e0-ffffffff81af4dd4: tpm2_get_pcr_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t tpm2_get_pcr_allocation(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81b47fa0)
Location: drivers/char/tpm/tpm2-cmd.c:548
Inline: False
```
**Symbols:**

```
ffffffff81b47fa0-ffffffff81b48394: tpm2_get_pcr_allocation (STB_GLOBAL)
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
ssize_t tpm2_get_pcr_allocation(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffff8000108bcb80)
Location: drivers/char/tpm/tpm2-cmd.c:845
Inline: False
```
**Symbols:**

```
ffff8000108bcb80-ffff8000108bce8c: tpm2_get_pcr_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t tpm2_get_pcr_allocation(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (c09b5f1c)
Location: drivers/char/tpm/tpm2-cmd.c:845
Inline: False
```
**Symbols:**

```
c09b5f1c-c09b628c: tpm2_get_pcr_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t tpm2_get_pcr_allocation(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (c00000000095e7f0)
Location: drivers/char/tpm/tpm2-cmd.c:845
Inline: False
```
**Symbols:**

```
c00000000095e7f0-c00000000095eb88: tpm2_get_pcr_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t tpm2_get_pcr_allocation(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056eb40)
Location: drivers/char/tpm/tpm2-cmd.c:845
Inline: False
```
**Symbols:**

```
ffffffe00056eb40-ffffffe00056efb8: tpm2_get_pcr_allocation (STB_GLOBAL)
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
ssize_t tpm2_get_pcr_allocation(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:845
Inline: False
```
**Symbols:**

```
ffffffff81698190-ffffffff8169819c: tpm2_get_pcr_allocation.cold (STB_LOCAL)
ffffffff81697b80-ffffffff81697e29: tpm2_get_pcr_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t tpm2_get_pcr_allocation(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:845
Inline: False
```
**Symbols:**

```
ffffffff81675b80-ffffffff81675b8c: tpm2_get_pcr_allocation.cold (STB_LOCAL)
ffffffff81675570-ffffffff81675819: tpm2_get_pcr_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t tpm2_get_pcr_allocation(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:845
Inline: False
```
**Symbols:**

```
ffffffff816c6400-ffffffff816c640c: tpm2_get_pcr_allocation.cold (STB_LOCAL)
ffffffff816c5df0-ffffffff816c6099: tpm2_get_pcr_allocation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t tpm2_get_pcr_allocation(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:845
Inline: False
```
**Symbols:**

```
ffffffff816e08f0-ffffffff816e08fc: tpm2_get_pcr_allocation.cold (STB_LOCAL)
ffffffff816e02f0-ffffffff816e0591: tpm2_get_pcr_allocation (STB_GLOBAL)
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
