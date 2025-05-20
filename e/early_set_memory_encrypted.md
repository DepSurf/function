# Function: <code>early_set_memory_encrypted</code>

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
int early_set_memory_encrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff826c663f)
Location: arch/x86/mm/mem_encrypt.c:387
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvm_memblock_free
```
**Symbols:**

```
ffffffff826c663f-ffffffff826c664f: early_set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int early_set_memory_encrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff826f0008)
Location: arch/x86/mm/mem_encrypt.c:321
Inline: False
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvm_memblock_free
```
**Symbols:**

```
ffffffff826f0008-ffffffff826f0018: early_set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int early_set_memory_encrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828a6cc5)
Location: arch/x86/mm/mem_encrypt.c:321
Inline: False
```
**Symbols:**

```
ffffffff828a6cc5-ffffffff828a6cd5: early_set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int early_set_memory_encrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828bf377)
Location: arch/x86/mm/mem_encrypt.c:326
Inline: False
```
**Symbols:**

```
ffffffff828bf377-ffffffff828bf387: early_set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int early_set_memory_encrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828c57f2)
Location: arch/x86/mm/mem_encrypt.c:326
Inline: False
```
**Symbols:**

```
ffffffff828c57f2-ffffffff828c5802: early_set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int early_set_memory_encrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff82ce89e7)
Location: arch/x86/mm/mem_encrypt.c:326
Inline: False
```
**Symbols:**

```
ffffffff82ce89e7-ffffffff82ce89f7: early_set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int early_set_memory_encrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff82fd643f)
Location: arch/x86/mm/mem_encrypt.c:359
Inline: False
```
**Symbols:**

```
ffffffff82fd643f-ffffffff82fd644f: early_set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int early_set_memory_encrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff831e0e97)
Location: arch/x86/mm/mem_encrypt.c:358
Inline: False
```
**Symbols:**

```
ffffffff831e0e97-ffffffff831e0ea7: early_set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int early_set_memory_encrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff832c45b1)
Location: arch/x86/mm/mem_encrypt.c:359
Inline: False
```
**Symbols:**

```
ffffffff832c45b1-ffffffff832c45c1: early_set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int early_set_memory_encrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff8347702c)
Location: arch/x86/mm/mem_encrypt_amd.c:477
Inline: False
```
**Symbols:**

```
ffffffff8347702c-ffffffff83477046: early_set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int early_set_memory_encrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83ea0450)
Location: arch/x86/mm/mem_encrypt_amd.c:478
Inline: False
```
**Symbols:**

```
ffffffff83ea0450-ffffffff83ea046a: early_set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int early_set_memory_encrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff836c45d0)
Location: arch/x86/mm/mem_encrypt_amd.c:479
Inline: False
```
**Symbols:**

```
ffffffff836c45d0-ffffffff836c45ea: early_set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int early_set_memory_encrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff838f51d0)
Location: arch/x86/mm/mem_encrypt_amd.c:444
Inline: False
```
**Symbols:**

```
ffffffff838f51d0-ffffffff838f51ea: early_set_memory_encrypted (STB_GLOBAL)
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
int early_set_memory_encrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828b078a)
Location: arch/x86/mm/mem_encrypt.c:326
Inline: False
```
**Symbols:**

```
ffffffff828b078a-ffffffff828b079a: early_set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int early_set_memory_encrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828a890f)
Location: arch/x86/mm/mem_encrypt.c:326
Inline: False
```
**Symbols:**

```
ffffffff828a890f-ffffffff828a891f: early_set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int early_set_memory_encrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828c3689)
Location: arch/x86/mm/mem_encrypt.c:326
Inline: False
```
**Symbols:**

```
ffffffff828c3689-ffffffff828c3699: early_set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int early_set_memory_encrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828c682f)
Location: arch/x86/mm/mem_encrypt.c:326
Inline: False
```
**Symbols:**

```
ffffffff828c682f-ffffffff828c683f: early_set_memory_encrypted (STB_GLOBAL)
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
