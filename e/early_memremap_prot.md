# Function: <code>early_memremap_prot</code>

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
void *early_memremap_prot(resource_size_t phys_addr, long unsigned int size, long unsigned int prot_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff826e047d)
Location: mm/early_ioremap.c:244
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_decrypted
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted
```
**Symbols:**

```
ffffffff826e047d-ffffffff826e048d: early_memremap_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *early_memremap_prot(resource_size_t phys_addr, long unsigned int size, long unsigned int prot_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff8270a993)
Location: mm/early_ioremap.c:244
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_decrypted
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted
```
**Symbols:**

```
ffffffff8270a993-ffffffff8270a9a3: early_memremap_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *early_memremap_prot(resource_size_t phys_addr, long unsigned int size, long unsigned int prot_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828c1b77)
Location: mm/early_ioremap.c:244
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_decrypted
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted
```
**Symbols:**

```
ffffffff828c1b77-ffffffff828c1b87: early_memremap_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *early_memremap_prot(resource_size_t phys_addr, long unsigned int size, long unsigned int prot_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828daf63)
Location: mm/early_ioremap.c:244
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_decrypted
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
```
**Symbols:**

```
ffffffff828daf63-ffffffff828daf73: early_memremap_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *early_memremap_prot(resource_size_t phys_addr, long unsigned int size, long unsigned int prot_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828e3399)
Location: mm/early_ioremap.c:244
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_decrypted
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
```
**Symbols:**

```
ffffffff828e3399-ffffffff828e33a9: early_memremap_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *early_memremap_prot(resource_size_t phys_addr, long unsigned int size, long unsigned int prot_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff82d00685)
Location: mm/early_ioremap.c:244
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_decrypted
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
```
**Symbols:**

```
ffffffff82d00685-ffffffff82d00695: early_memremap_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *early_memremap_prot(resource_size_t phys_addr, long unsigned int size, long unsigned int prot_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff82fed04a)
Location: mm/early_ioremap.c:244
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_decrypted
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
```
**Symbols:**

```
ffffffff82fed04a-ffffffff82fed05a: early_memremap_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *early_memremap_prot(resource_size_t phys_addr, long unsigned int size, long unsigned int prot_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff831f787e)
Location: mm/early_ioremap.c:244
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_decrypted
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
```
**Symbols:**

```
ffffffff831f787e-ffffffff831f788e: early_memremap_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *early_memremap_prot(resource_size_t phys_addr, long unsigned int size, long unsigned int prot_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff832de5e9)
Location: mm/early_ioremap.c:239
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_decrypted
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
```
**Symbols:**

```
ffffffff832de5e9-ffffffff832de5f9: early_memremap_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *early_memremap_prot(resource_size_t phys_addr, long unsigned int size, long unsigned int prot_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff83493e90)
Location: mm/early_ioremap.c:240
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_decrypted
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
```
**Symbols:**

```
ffffffff83493e90-ffffffff83493eaa: early_memremap_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *early_memremap_prot(resource_size_t phys_addr, long unsigned int size, long unsigned int prot_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff83ec8230)
Location: mm/early_ioremap.c:240
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
```
**Symbols:**

```
ffffffff83ec8230-ffffffff83ec824a: early_memremap_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *early_memremap_prot(resource_size_t phys_addr, long unsigned int size, long unsigned int prot_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff836ed2a0)
Location: mm/early_ioremap.c:238
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
```
**Symbols:**

```
ffffffff836ed2a0-ffffffff836ed2ba: early_memremap_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *early_memremap_prot(resource_size_t phys_addr, long unsigned int size, long unsigned int prot_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff839202a0)
Location: mm/early_ioremap.c:238
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
```
**Symbols:**

```
ffffffff839202a0-ffffffff839202ba: early_memremap_prot (STB_GLOBAL)
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
void *early_memremap_prot(resource_size_t phys_addr, long unsigned int size, long unsigned int prot_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffff80001145c854)
Location: mm/early_ioremap.c:244
Inline: False
Direct callers:
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
```
**Symbols:**

```
ffff80001145c854-ffff80001145c898: early_memremap_prot (STB_GLOBAL)
```
</details>
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
void *early_memremap_prot(resource_size_t phys_addr, long unsigned int size, long unsigned int prot_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828cc24d)
Location: mm/early_ioremap.c:244
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_decrypted
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
```
**Symbols:**

```
ffffffff828cc24d-ffffffff828cc25d: early_memremap_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *early_memremap_prot(resource_size_t phys_addr, long unsigned int size, long unsigned int prot_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828c4969)
Location: mm/early_ioremap.c:244
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_decrypted
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
```
**Symbols:**

```
ffffffff828c4969-ffffffff828c4979: early_memremap_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *early_memremap_prot(resource_size_t phys_addr, long unsigned int size, long unsigned int prot_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828defcd)
Location: mm/early_ioremap.c:244
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_decrypted
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
```
**Symbols:**

```
ffffffff828defcd-ffffffff828defdd: early_memremap_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *early_memremap_prot(resource_size_t phys_addr, long unsigned int size, long unsigned int prot_val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/early_ioremap.c (ffffffff828e43e4)
Location: mm/early_ioremap.c:244
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_decrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_decrypted
  - arch/x86/mm/ioremap.c:early_memremap_encrypted_wp
  - arch/x86/mm/ioremap.c:early_memremap_encrypted
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
```
**Symbols:**

```
ffffffff828e43e4-ffffffff828e43f4: early_memremap_prot (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
