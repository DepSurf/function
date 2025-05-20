# Function: <code>sme_populate_pgd</code>

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
void sme_populate_pgd(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5b3d)
Location: arch/x86/mm/mem_encrypt.c:596
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_map_range
  - arch/x86/mm/mem_encrypt.c:__sme_map_range
```
**Symbols:**

```
ffffffff826c5b3d-ffffffff826c5bc9: sme_populate_pgd (STB_LOCAL)
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f01f1)
Location: arch/x86/mm/mem_encrypt_identity.c:147
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a6ef9)
Location: arch/x86/mm/mem_encrypt_identity.c:148
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf5af)
Location: arch/x86/mm/mem_encrypt_identity.c:158
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c5a2a)
Location: arch/x86/mm/mem_encrypt_identity.c:158
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sme_populate_pgd(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8cef)
Location: arch/x86/mm/mem_encrypt_identity.c:158
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
**Symbols:**

```
ffffffff82ce8cef-ffffffff82ce8d96: sme_populate_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sme_populate_pgd(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd6775)
Location: arch/x86/mm/mem_encrypt_identity.c:158
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
**Symbols:**

```
ffffffff82fd6775-ffffffff82fd681c: sme_populate_pgd (STB_LOCAL)
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e11e2)
Location: arch/x86/mm/mem_encrypt_identity.c:158
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c4a6c)
Location: arch/x86/mm/mem_encrypt_identity.c:167
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff8347749f)
Location: arch/x86/mm/mem_encrypt_identity.c:170
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sme_populate_pgd(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea0aa0)
Location: arch/x86/mm/mem_encrypt_identity.c:170
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
```
**Symbols:**

```
ffffffff83ea0aa0-ffffffff83ea0bab: sme_populate_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sme_populate_pgd(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4bb0)
Location: arch/x86/mm/mem_encrypt_identity.c:170
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
```
**Symbols:**

```
ffffffff836c4bb0-ffffffff836c4cb6: sme_populate_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sme_populate_pgd(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f57b0)
Location: arch/x86/mm/mem_encrypt_identity.c:170
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
```
**Symbols:**

```
ffffffff838f57b0-ffffffff838f58b6: sme_populate_pgd (STB_LOCAL)
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b09c2)
Location: arch/x86/mm/mem_encrypt_identity.c:158
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8b47)
Location: arch/x86/mm/mem_encrypt_identity.c:158
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c38c1)
Location: arch/x86/mm/mem_encrypt_identity.c:158
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
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
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c6a67)
Location: arch/x86/mm/mem_encrypt_identity.c:158
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
