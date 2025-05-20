# Function: <code>tpm_chip_find_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct tpm_chip *tpm_chip_find_get(int chip_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81525af0)
Location: drivers/char/tpm/tpm-chip.c:43
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_is_tpm2
  - drivers/char/tpm/tpm-interface.c:tpm_seal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_unseal_trusted
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm-interface.c:tpm_get_random
  - drivers/char/tpm/tpm-interface.c:tpm_pcr_read
```
**Symbols:**

```
ffffffff81525af0-ffffffff81525b68: tpm_chip_find_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct tpm_chip *tpm_chip_find_get(int chip_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81578c60)
Location: drivers/char/tpm/tpm-chip.c:88
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
ffffffff81578c60-ffffffff81578d08: tpm_chip_find_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct tpm_chip *tpm_chip_find_get(int chip_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff815a50c0)
Location: drivers/char/tpm/tpm-chip.c:88
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
ffffffff815a50c0-ffffffff815a518a: tpm_chip_find_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct tpm_chip *tpm_chip_find_get(int chip_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff815b9140)
Location: drivers/char/tpm/tpm-chip.c:89
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
ffffffff815b9140-ffffffff815b91e9: tpm_chip_find_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct tpm_chip *tpm_chip_find_get(int chip_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff8161fc80)
Location: drivers/char/tpm/tpm-chip.c:89
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
ffffffff8161fc80-ffffffff8161fd29: tpm_chip_find_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct tpm_chip *tpm_chip_find_get(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-chip.c (ffffffff81659a70)
Location: drivers/char/tpm/tpm-chip.c:95
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
ffffffff81659a70-ffffffff81659b22: tpm_chip_find_get (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tpm_chip *chip</code>
</li>
<li>
<b>Param removed. </b>
<code>int chip_num</code>
</li>
</ul>
</details>
</li>
</ul>
