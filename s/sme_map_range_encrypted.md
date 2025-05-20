# Function: <code>sme_map_range_encrypted</code>

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
void sme_map_range_encrypted(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5d63)
Location: arch/x86/mm/mem_encrypt.c:671
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff826c5d63-ffffffff826c5d80: sme_map_range_encrypted (STB_LOCAL)
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f055c)
Location: arch/x86/mm/mem_encrypt_identity.c:217
Inline: True
Inline callers:
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a7264)
Location: arch/x86/mm/mem_encrypt_identity.c:218
Inline: True
Inline callers:
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf93a)
Location: arch/x86/mm/mem_encrypt_identity.c:228
Inline: True
Inline callers:
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c5dbe)
Location: arch/x86/mm/mem_encrypt_identity.c:228
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sme_map_range_encrypted(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8e6e)
Location: arch/x86/mm/mem_encrypt_identity.c:228
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff82ce8e6e-ffffffff82ce8e8b: sme_map_range_encrypted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sme_map_range_encrypted(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd68f4)
Location: arch/x86/mm/mem_encrypt_identity.c:228
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff82fd68f4-ffffffff82fd6911: sme_map_range_encrypted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sme_map_range_encrypted(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e133e)
Location: arch/x86/mm/mem_encrypt_identity.c:228
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff831e133e-ffffffff831e135b: sme_map_range_encrypted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sme_map_range_encrypted(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c4bc8)
Location: arch/x86/mm/mem_encrypt_identity.c:237
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff832c4bc8-ffffffff832c4be5: sme_map_range_encrypted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sme_map_range_encrypted(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff8347760d)
Location: arch/x86/mm/mem_encrypt_identity.c:240
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff8347760d-ffffffff83477634: sme_map_range_encrypted (STB_LOCAL)
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea0f33)
Location: arch/x86/mm/mem_encrypt_identity.c:240
Inline: True
Inline callers:
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c5040)
Location: arch/x86/mm/mem_encrypt_identity.c:240
Inline: True
Inline callers:
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f5c40)
Location: arch/x86/mm/mem_encrypt_identity.c:240
Inline: True
Inline callers:
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b0d56)
Location: arch/x86/mm/mem_encrypt_identity.c:228
Inline: True
Inline callers:
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8edb)
Location: arch/x86/mm/mem_encrypt_identity.c:228
Inline: True
Inline callers:
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c3c55)
Location: arch/x86/mm/mem_encrypt_identity.c:228
Inline: True
Inline callers:
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c6dfb)
Location: arch/x86/mm/mem_encrypt_identity.c:228
Inline: True
Inline callers:
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
