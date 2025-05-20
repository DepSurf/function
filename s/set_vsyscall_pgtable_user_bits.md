# Function: <code>set_vsyscall_pgtable_user_bits</code>

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
void set_vsyscall_pgtable_user_bits(pgd_t *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826a63ce)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:347
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff826a63ce-ffffffff826a64d1: set_vsyscall_pgtable_user_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void set_vsyscall_pgtable_user_bits(pgd_t *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826cf56f)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:343
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff826cf56f-ffffffff826cf659: set_vsyscall_pgtable_user_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void set_vsyscall_pgtable_user_bits(pgd_t *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288559c)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:336
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8288559c-ffffffff82885686: set_vsyscall_pgtable_user_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void set_vsyscall_pgtable_user_bits(pgd_t *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289c61a)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:357
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8289c61a-ffffffff8289c704: set_vsyscall_pgtable_user_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void set_vsyscall_pgtable_user_bits(pgd_t *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289f60a)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:357
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8289f60a-ffffffff8289f6f4: set_vsyscall_pgtable_user_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void set_vsyscall_pgtable_user_bits(pgd_t *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82cc5a69)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:357
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
  - arch/x86/mm/pti.c:pti_setup_vsyscall
```
**Symbols:**

```
ffffffff82cc5a69-ffffffff82cc5be2: set_vsyscall_pgtable_user_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void set_vsyscall_pgtable_user_bits(pgd_t *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82fb135d)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:357
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
  - arch/x86/mm/pti.c:pti_setup_vsyscall
```
**Symbols:**

```
ffffffff82fb135d-ffffffff82fb14d6: set_vsyscall_pgtable_user_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void set_vsyscall_pgtable_user_bits(pgd_t *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff831bb4e8)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:357
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff831bb4e8-ffffffff831bb661: set_vsyscall_pgtable_user_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void set_vsyscall_pgtable_user_bits(pgd_t *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8329b9f0)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:358
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8329b9f0-ffffffff8329bb9e: set_vsyscall_pgtable_user_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void set_vsyscall_pgtable_user_bits(pgd_t *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8344a1ec)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:358
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8344a1ec-ffffffff8344a3a7: set_vsyscall_pgtable_user_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void set_vsyscall_pgtable_user_bits(pgd_t *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83e64830)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:358
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff83e64830-ffffffff83e64a1b: set_vsyscall_pgtable_user_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void set_vsyscall_pgtable_user_bits(pgd_t *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83684eb0)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:358
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff83684eb0-ffffffff8368509b: set_vsyscall_pgtable_user_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void set_vsyscall_pgtable_user_bits(pgd_t *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff838b4050)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:358
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff838b4050-ffffffff838b423b: set_vsyscall_pgtable_user_bits (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void set_vsyscall_pgtable_user_bits(pgd_t *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288d60a)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:357
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8288d60a-ffffffff8288d6f4: set_vsyscall_pgtable_user_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void set_vsyscall_pgtable_user_bits(pgd_t *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288b587)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:357
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff8288b587-ffffffff8288b623: set_vsyscall_pgtable_user_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void set_vsyscall_pgtable_user_bits(pgd_t *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a060a)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:357
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff828a060a-ffffffff828a06f4: set_vsyscall_pgtable_user_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void set_vsyscall_pgtable_user_bits(pgd_t *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a060f)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:357
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:map_vsyscall
  - arch/x86/mm/pti.c:pti_init
```
**Symbols:**

```
ffffffff828a060f-ffffffff828a06f9: set_vsyscall_pgtable_user_bits (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
