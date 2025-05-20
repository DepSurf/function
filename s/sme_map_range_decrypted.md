# Function: <code>sme_map_range_decrypted</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sme_map_range_decrypted(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5d95)
Location: arch/x86/mm/mem_encrypt.c:676
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff826c5d95-ffffffff826c5daa: sme_map_range_decrypted (STB_LOCAL)
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f04e6)
Location: arch/x86/mm/mem_encrypt_identity.c:222
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a71ee)
Location: arch/x86/mm/mem_encrypt_identity.c:223
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf8ac)
Location: arch/x86/mm/mem_encrypt_identity.c:233
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c5d4b)
Location: arch/x86/mm/mem_encrypt_identity.c:233
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sme_map_range_decrypted(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8e8b)
Location: arch/x86/mm/mem_encrypt_identity.c:233
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff82ce8e8b-ffffffff82ce8ea0: sme_map_range_decrypted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sme_map_range_decrypted(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd6911)
Location: arch/x86/mm/mem_encrypt_identity.c:233
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff82fd6911-ffffffff82fd6926: sme_map_range_decrypted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sme_map_range_decrypted(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e135b)
Location: arch/x86/mm/mem_encrypt_identity.c:233
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff831e135b-ffffffff831e1370: sme_map_range_decrypted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sme_map_range_decrypted(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c4be5)
Location: arch/x86/mm/mem_encrypt_identity.c:242
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff832c4be5-ffffffff832c4bfa: sme_map_range_decrypted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sme_map_range_decrypted(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83477634)
Location: arch/x86/mm/mem_encrypt_identity.c:245
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff83477634-ffffffff83477653: sme_map_range_decrypted (STB_LOCAL)
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea0e89)
Location: arch/x86/mm/mem_encrypt_identity.c:245
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4f99)
Location: arch/x86/mm/mem_encrypt_identity.c:245
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f5b99)
Location: arch/x86/mm/mem_encrypt_identity.c:245
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b0ce3)
Location: arch/x86/mm/mem_encrypt_identity.c:233
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8e68)
Location: arch/x86/mm/mem_encrypt_identity.c:233
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c3be2)
Location: arch/x86/mm/mem_encrypt_identity.c:233
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c6d88)
Location: arch/x86/mm/mem_encrypt_identity.c:233
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
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
</ul>
