# Function: <code>tpm2_init_bank_info</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tpm2_init_bank_info(struct tpm_chip *chip, u32 bank_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816ae280)
Location: drivers/char/tpm/tpm2-cmd.c:813
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
**Symbols:**

```
ffffffff816ae280-ffffffff816ae33f: tpm2_init_bank_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tpm2_init_bank_info(struct tpm_chip *chip, u32 bank_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816d0f60)
Location: drivers/char/tpm/tpm2-cmd.c:813
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
**Symbols:**

```
ffffffff816d0f60-ffffffff816d1028: tpm2_init_bank_info (STB_LOCAL)
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81786731)
Location: drivers/char/tpm/tpm2-cmd.c:507
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff8179d931)
Location: drivers/char/tpm/tpm2-cmd.c:507
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff8178046f)
Location: drivers/char/tpm/tpm2-cmd.c:507
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81806843)
Location: drivers/char/tpm/tpm2-cmd.c:507
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81946352)
Location: drivers/char/tpm/tpm2-cmd.c:516
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81aa93f2)
Location: drivers/char/tpm/tpm2-cmd.c:516
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81af4c22)
Location: drivers/char/tpm/tpm2-cmd.c:516
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81b481e2)
Location: drivers/char/tpm/tpm2-cmd.c:516
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
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
int tpm2_init_bank_info(struct tpm_chip *chip, u32 bank_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffff8000108bb778)
Location: drivers/char/tpm/tpm2-cmd.c:813
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
**Symbols:**

```
ffff8000108bb778-ffff8000108bb880: tpm2_init_bank_info (STB_LOCAL)
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
In drivers/char/tpm/tpm2-cmd.c (c09b6144)
Location: drivers/char/tpm/tpm2-cmd.c:813
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm2_init_bank_info(struct tpm_chip *chip, u32 bank_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (c00000000095cf20)
Location: drivers/char/tpm/tpm2-cmd.c:813
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
**Symbols:**

```
c00000000095cf20-c00000000095d03c: tpm2_init_bank_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm2_init_bank_info(struct tpm_chip *chip, u32 bank_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056c968)
Location: drivers/char/tpm/tpm2-cmd.c:813
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
**Symbols:**

```
ffffffe00056c968-ffffffe00056ca48: tpm2_init_bank_info (STB_LOCAL)
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
int tpm2_init_bank_info(struct tpm_chip *chip, u32 bank_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816969b0)
Location: drivers/char/tpm/tpm2-cmd.c:813
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
**Symbols:**

```
ffffffff816969b0-ffffffff81696a78: tpm2_init_bank_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tpm2_init_bank_info(struct tpm_chip *chip, u32 bank_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816743a0)
Location: drivers/char/tpm/tpm2-cmd.c:813
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
**Symbols:**

```
ffffffff816743a0-ffffffff81674468: tpm2_init_bank_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tpm2_init_bank_info(struct tpm_chip *chip, u32 bank_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816c4c20)
Location: drivers/char/tpm/tpm2-cmd.c:813
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
**Symbols:**

```
ffffffff816c4c20-ffffffff816c4ce8: tpm2_init_bank_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tpm2_init_bank_info(struct tpm_chip *chip, u32 bank_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816df180)
Location: drivers/char/tpm/tpm2-cmd.c:813
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
```
**Symbols:**

```
ffffffff816df180-ffffffff816df248: tpm2_init_bank_info (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
