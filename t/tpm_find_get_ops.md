# Function: <code>tpm_find_get_ops</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
struct tpm_chip *tpm_find_get_ops(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81675a20)
Location: drivers/char/tpm/tpm-chip.c:125
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_unseal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_seal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm-interface.c:tpm_is_tpm2
```
**Symbols:**

```
ffffffff81675a20-ffffffff81675a74: tpm_find_get_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tpm_chip *tpm_find_get_ops(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff816ab6b0)
Location: drivers/char/tpm/tpm-chip.c:235
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_unseal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_seal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm-interface.c:tpm_is_tpm2
```
**Symbols:**

```
ffffffff816ab6b0-ffffffff816ab703: tpm_find_get_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tpm_chip *tpm_find_get_ops(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff816ce3f0)
Location: drivers/char/tpm/tpm-chip.c:235
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_unseal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_seal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm-interface.c:tpm_is_tpm2
```
**Symbols:**

```
ffffffff816ce3f0-ffffffff816ce443: tpm_find_get_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tpm_chip *tpm_find_get_ops(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81783310)
Location: drivers/char/tpm/tpm-chip.c:235
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm-interface.c:tpm_is_tpm2
```
**Symbols:**

```
ffffffff81783310-ffffffff81783363: tpm_find_get_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tpm_chip *tpm_find_get_ops(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff8179a960)
Location: drivers/char/tpm/tpm-chip.c:235
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm-interface.c:tpm_is_tpm2
```
**Symbols:**

```
ffffffff8179a960-ffffffff8179a9b3: tpm_find_get_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tpm_chip *tpm_find_get_ops(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff8177d4b0)
Location: drivers/char/tpm/tpm-chip.c:235
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm-interface.c:tpm_is_tpm2
```
**Symbols:**

```
ffffffff8177d4b0-ffffffff8177d503: tpm_find_get_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct tpm_chip *tpm_find_get_ops(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81803690)
Location: drivers/char/tpm/tpm-chip.c:235
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm-interface.c:tpm_is_tpm2
```
**Symbols:**

```
ffffffff81803690-ffffffff818036e3: tpm_find_get_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct tpm_chip *tpm_find_get_ops(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81942f00)
Location: drivers/char/tpm/tpm-chip.c:235
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm-interface.c:tpm_is_tpm2
```
**Symbols:**

```
ffffffff81942f00-ffffffff81942f60: tpm_find_get_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct tpm_chip *tpm_find_get_ops(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81aa5880)
Location: drivers/char/tpm/tpm-chip.c:235
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm-interface.c:tpm_is_tpm2
```
**Symbols:**

```
ffffffff81aa5880-ffffffff81aa58e0: tpm_find_get_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct tpm_chip *tpm_find_get_ops(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81af1000)
Location: drivers/char/tpm/tpm-chip.c:235
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm-interface.c:tpm_is_tpm2
```
**Symbols:**

```
ffffffff81af1000-ffffffff81af1060: tpm_find_get_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct tpm_chip *tpm_find_get_ops(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81b445e0)
Location: drivers/char/tpm/tpm-chip.c:240
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm-interface.c:tpm_is_tpm2
```
**Symbols:**

```
ffffffff81b445e0-ffffffff81b44640: tpm_find_get_ops (STB_GLOBAL)
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
struct tpm_chip *tpm_find_get_ops(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffff8000108b8658)
Location: drivers/char/tpm/tpm-chip.c:235
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_unseal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_seal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm-interface.c:tpm_is_tpm2
```
**Symbols:**

```
ffff8000108b8658-ffff8000108b86c4: tpm_find_get_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tpm_chip *tpm_find_get_ops(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (c09b1e64)
Location: drivers/char/tpm/tpm-chip.c:235
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_unseal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_seal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm-interface.c:tpm_is_tpm2
```
**Symbols:**

```
c09b1e64-c09b1ec4: tpm_find_get_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tpm_chip *tpm_find_get_ops(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (c000000000959330)
Location: drivers/char/tpm/tpm-chip.c:235
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_unseal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_seal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm-interface.c:tpm_is_tpm2
```
**Symbols:**

```
c000000000959330-c0000000009593cc: tpm_find_get_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tpm_chip *tpm_find_get_ops(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffe000568ec4)
Location: drivers/char/tpm/tpm-chip.c:235
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_unseal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_seal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm-interface.c:tpm_is_tpm2
```
**Symbols:**

```
ffffffe000568ec4-ffffffe000568f2c: tpm_find_get_ops (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct tpm_chip *tpm_find_get_ops(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81693e40)
Location: drivers/char/tpm/tpm-chip.c:235
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_unseal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_seal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm-interface.c:tpm_is_tpm2
```
**Symbols:**

```
ffffffff81693e40-ffffffff81693e93: tpm_find_get_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tpm_chip *tpm_find_get_ops(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81671830)
Location: drivers/char/tpm/tpm-chip.c:235
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_unseal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_seal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm-interface.c:tpm_is_tpm2
```
**Symbols:**

```
ffffffff81671830-ffffffff81671883: tpm_find_get_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tpm_chip *tpm_find_get_ops(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff816c20b0)
Location: drivers/char/tpm/tpm-chip.c:235
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_unseal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_seal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm-interface.c:tpm_is_tpm2
```
**Symbols:**

```
ffffffff816c20b0-ffffffff816c2103: tpm_find_get_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tpm_chip *tpm_find_get_ops(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff816dc680)
Location: drivers/char/tpm/tpm-chip.c:235
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_unseal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_seal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
  - drivers/char/tpm/tpm-interface.c:tpm_is_tpm2
```
**Symbols:**

```
ffffffff816dc680-ffffffff816dc6d3: tpm_find_get_ops (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
