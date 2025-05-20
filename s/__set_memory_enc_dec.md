# Function: <code>__set_memory_enc_dec</code>

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
int __set_memory_enc_dec(long unsigned int addr, int numpages, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810774b0)
Location: arch/x86/mm/pageattr.c:1778
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_memory_decrypted
  - arch/x86/mm/pageattr.c:set_memory_encrypted
```
**Symbols:**

```
ffffffff810774b0-ffffffff810775eb: __set_memory_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __set_memory_enc_dec(long unsigned int addr, int numpages, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81079f20)
Location: arch/x86/mm/pageattr.c:1829
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_memory_decrypted
  - arch/x86/mm/pageattr.c:set_memory_encrypted
```
**Symbols:**

```
ffffffff81079f20-ffffffff8107a05c: __set_memory_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __set_memory_enc_dec(long unsigned int addr, int numpages, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81080730)
Location: arch/x86/mm/pageattr.c:2022
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_memory_decrypted
  - arch/x86/mm/pageattr.c:set_memory_encrypted
```
**Symbols:**

```
ffffffff81080730-ffffffff8108083e: __set_memory_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __set_memory_enc_dec(long unsigned int addr, int numpages, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084220)
Location: arch/x86/mm/pageattr.c:2033
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_memory_decrypted
  - arch/x86/mm/pageattr.c:set_memory_encrypted
```
**Symbols:**

```
ffffffff81084220-ffffffff8108433c: __set_memory_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __set_memory_enc_dec(long unsigned int addr, int numpages, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084f60)
Location: arch/x86/mm/pageattr.c:1939
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_memory_decrypted
  - arch/x86/mm/pageattr.c:set_memory_encrypted
```
**Symbols:**

```
ffffffff81084f60-ffffffff8108507c: __set_memory_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __set_memory_enc_dec(long unsigned int addr, int numpages, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ebb0)
Location: arch/x86/mm/pat/set_memory.c:1975
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:set_memory_decrypted
  - arch/x86/mm/pat/set_memory.c:set_memory_encrypted
```
**Symbols:**

```
ffffffff8108ebb0-ffffffff8108ecbd: __set_memory_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __set_memory_enc_dec(long unsigned int addr, int numpages, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e980)
Location: arch/x86/mm/pat/set_memory.c:1975
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:set_memory_decrypted
  - arch/x86/mm/pat/set_memory.c:set_memory_encrypted
```
**Symbols:**

```
ffffffff8108e980-ffffffff8108eaa2: __set_memory_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __set_memory_enc_dec(long unsigned int addr, int numpages, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f540)
Location: arch/x86/mm/pat/set_memory.c:1983
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:set_memory_decrypted
  - arch/x86/mm/pat/set_memory.c:set_memory_encrypted
```
**Symbols:**

```
ffffffff8108f540-ffffffff8108f662: __set_memory_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __set_memory_enc_dec(long unsigned int addr, int numpages, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:1983
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:set_memory_decrypted
  - arch/x86/mm/pat/set_memory.c:set_memory_encrypted
```
**Symbols:**

```
ffffffff8109eff0-ffffffff8109f121: __set_memory_enc_dec (STB_LOCAL)
ffffffff81ca13de-ffffffff81ca13f7: __set_memory_enc_dec.cold (STB_LOCAL)
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
In arch/x86/mm/pat/set_memory.c (ffffffff810b2cf1)
Location: arch/x86/mm/pat/set_memory.c:2072
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_memory_decrypted
  - arch/x86/mm/pat/set_memory.c:set_memory_decrypted
  - arch/x86/mm/pat/set_memory.c:set_memory_encrypted
  - arch/x86/mm/pat/set_memory.c:set_memory_encrypted
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
In arch/x86/mm/pat/set_memory.c (ffffffff810cd6d1)
Location: arch/x86/mm/pat/set_memory.c:2176
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_memory_decrypted
  - arch/x86/mm/pat/set_memory.c:set_memory_decrypted
  - arch/x86/mm/pat/set_memory.c:set_memory_encrypted
  - arch/x86/mm/pat/set_memory.c:set_memory_encrypted
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
In arch/x86/mm/pat/set_memory.c (ffffffff810d0c72)
Location: arch/x86/mm/pat/set_memory.c:2178
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_memory_decrypted
  - arch/x86/mm/pat/set_memory.c:set_memory_encrypted
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
In arch/x86/mm/pat/set_memory.c (ffffffff810d9352)
Location: arch/x86/mm/pat/set_memory.c:2182
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_memory_decrypted
  - arch/x86/mm/pat/set_memory.c:set_memory_encrypted
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
int __set_memory_enc_dec(long unsigned int addr, int numpages, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81083f60)
Location: arch/x86/mm/pageattr.c:1939
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_memory_decrypted
  - arch/x86/mm/pageattr.c:set_memory_encrypted
```
**Symbols:**

```
ffffffff81083f60-ffffffff8108407c: __set_memory_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __set_memory_enc_dec(long unsigned int addr, int numpages, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81072bb0)
Location: arch/x86/mm/pageattr.c:1939
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_memory_decrypted
  - arch/x86/mm/pageattr.c:set_memory_encrypted
```
**Symbols:**

```
ffffffff81072bb0-ffffffff81072ccc: __set_memory_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __set_memory_enc_dec(long unsigned int addr, int numpages, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81083f10)
Location: arch/x86/mm/pageattr.c:1939
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_memory_decrypted
  - arch/x86/mm/pageattr.c:set_memory_encrypted
```
**Symbols:**

```
ffffffff81083f10-ffffffff8108402c: __set_memory_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __set_memory_enc_dec(long unsigned int addr, int numpages, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81086050)
Location: arch/x86/mm/pageattr.c:1939
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:set_memory_decrypted
  - arch/x86/mm/pageattr.c:set_memory_encrypted
```
**Symbols:**

```
ffffffff81086050-ffffffff8108616c: __set_memory_enc_dec (STB_LOCAL)
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
