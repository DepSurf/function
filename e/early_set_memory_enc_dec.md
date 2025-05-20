# Function: <code>early_set_memory_enc_dec</code>

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
int early_set_memory_enc_dec(long unsigned int vaddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5fcf)
Location: arch/x86/mm/mem_encrypt.c:318
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_encrypted
  - arch/x86/mm/mem_encrypt.c:early_set_memory_decrypted
```
**Symbols:**

```
ffffffff826c5fcf-ffffffff826c6134: early_set_memory_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int early_set_memory_enc_dec(long unsigned int vaddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff826efda3)
Location: arch/x86/mm/mem_encrypt.c:252
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_encrypted
  - arch/x86/mm/mem_encrypt.c:early_set_memory_decrypted
```
**Symbols:**

```
ffffffff826efda3-ffffffff826eff08: early_set_memory_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int early_set_memory_enc_dec(long unsigned int vaddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828a6a60)
Location: arch/x86/mm/mem_encrypt.c:252
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_encrypted
  - arch/x86/mm/mem_encrypt.c:early_set_memory_decrypted
```
**Symbols:**

```
ffffffff828a6a60-ffffffff828a6bc5: early_set_memory_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int early_set_memory_enc_dec(long unsigned int vaddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828bf10a)
Location: arch/x86/mm/mem_encrypt.c:253
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_encrypted
  - arch/x86/mm/mem_encrypt.c:early_set_memory_decrypted
```
**Symbols:**

```
ffffffff828bf10a-ffffffff828bf277: early_set_memory_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int early_set_memory_enc_dec(long unsigned int vaddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828c5585)
Location: arch/x86/mm/mem_encrypt.c:253
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_encrypted
  - arch/x86/mm/mem_encrypt.c:early_set_memory_decrypted
```
**Symbols:**

```
ffffffff828c5585-ffffffff828c56f2: early_set_memory_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int early_set_memory_enc_dec(long unsigned int vaddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff82ce8795)
Location: arch/x86/mm/mem_encrypt.c:253
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_encrypted
  - arch/x86/mm/mem_encrypt.c:early_set_memory_decrypted
```
**Symbols:**

```
ffffffff82ce8795-ffffffff82ce88ea: early_set_memory_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int early_set_memory_enc_dec(long unsigned int vaddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff82fd61a7)
Location: arch/x86/mm/mem_encrypt.c:286
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_encrypted
  - arch/x86/mm/mem_encrypt.c:early_set_memory_decrypted
```
**Symbols:**

```
ffffffff82fd61a7-ffffffff82fd62fc: early_set_memory_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int early_set_memory_enc_dec(long unsigned int vaddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff831e0c02)
Location: arch/x86/mm/mem_encrypt.c:285
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_encrypted
  - arch/x86/mm/mem_encrypt.c:early_set_memory_decrypted
```
**Symbols:**

```
ffffffff831e0c02-ffffffff831e0d55: early_set_memory_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int early_set_memory_enc_dec(long unsigned int vaddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff832c42da)
Location: arch/x86/mm/mem_encrypt.c:286
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_encrypted
  - arch/x86/mm/mem_encrypt.c:early_set_memory_decrypted
```
**Symbols:**

```
ffffffff832c42da-ffffffff832c4435: early_set_memory_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int early_set_memory_enc_dec(long unsigned int vaddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83476c8a)
Location: arch/x86/mm/mem_encrypt_amd.c:402
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_encrypted
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_decrypted
```
**Symbols:**

```
ffffffff83476c8a-ffffffff83476e30: early_set_memory_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int early_set_memory_enc_dec(long unsigned int vaddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83e9ff10)
Location: arch/x86/mm/mem_encrypt_amd.c:403
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_encrypted
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_decrypted
```
**Symbols:**

```
ffffffff83e9ff10-ffffffff83ea015c: early_set_memory_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int early_set_memory_enc_dec(long unsigned int vaddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff836c4090)
Location: arch/x86/mm/mem_encrypt_amd.c:404
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_encrypted
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_decrypted
```
**Symbols:**

```
ffffffff836c4090-ffffffff836c42c8: early_set_memory_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int early_set_memory_enc_dec(long unsigned int vaddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff838f4d10)
Location: arch/x86/mm/mem_encrypt_amd.c:369
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_encrypted
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_decrypted
```
**Symbols:**

```
ffffffff838f4d10-ffffffff838f4f48: early_set_memory_enc_dec (STB_LOCAL)
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
int early_set_memory_enc_dec(long unsigned int vaddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828b051d)
Location: arch/x86/mm/mem_encrypt.c:253
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_encrypted
  - arch/x86/mm/mem_encrypt.c:early_set_memory_decrypted
```
**Symbols:**

```
ffffffff828b051d-ffffffff828b068a: early_set_memory_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int early_set_memory_enc_dec(long unsigned int vaddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828a86a2)
Location: arch/x86/mm/mem_encrypt.c:253
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_encrypted
  - arch/x86/mm/mem_encrypt.c:early_set_memory_decrypted
```
**Symbols:**

```
ffffffff828a86a2-ffffffff828a880f: early_set_memory_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int early_set_memory_enc_dec(long unsigned int vaddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828c341c)
Location: arch/x86/mm/mem_encrypt.c:253
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_encrypted
  - arch/x86/mm/mem_encrypt.c:early_set_memory_decrypted
```
**Symbols:**

```
ffffffff828c341c-ffffffff828c3589: early_set_memory_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int early_set_memory_enc_dec(long unsigned int vaddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828c65c2)
Location: arch/x86/mm/mem_encrypt.c:253
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_encrypted
  - arch/x86/mm/mem_encrypt.c:early_set_memory_decrypted
```
**Symbols:**

```
ffffffff828c65c2-ffffffff828c672f: early_set_memory_enc_dec (STB_LOCAL)
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
