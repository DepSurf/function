# Function: <code>memblock_is_reserved</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int memblock_is_reserved(phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f8b64c)
Location: mm/memblock.c:1512
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_find_free_area
```
**Symbols:**

```
ffffffff81f8b64c-ffffffff81f8b670: memblock_is_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool memblock_is_reserved(phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81fb530c)
Location: mm/memblock.c:1560
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_find_free_area
```
**Symbols:**

```
ffffffff81fb530c-ffffffff81fb532d: memblock_is_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool memblock_is_reserved(phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ff1ced)
Location: mm/memblock.c:1565
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_find_free_area
```
**Symbols:**

```
ffffffff81ff1ced-ffffffff81ff1d0e: memblock_is_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool memblock_is_reserved(phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820d42ad)
Location: mm/memblock.c:1601
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_find_free_area
```
**Symbols:**

```
ffffffff820d42ad-ffffffff820d42d3: memblock_is_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool memblock_is_reserved(phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff826dcd50)
Location: mm/memblock.c:1619
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_find_free_area
```
**Symbols:**

```
ffffffff826dcd50-ffffffff826dcd76: memblock_is_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool memblock_is_reserved(phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82707285)
Location: mm/memblock.c:1629
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_find_free_area
```
**Symbols:**

```
ffffffff82707285-ffffffff827072ab: memblock_is_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool memblock_is_reserved(phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a267dc)
Location: mm/memblock.c:1729
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_find_free_area
```
**Symbols:**

```
ffffffff81a267dc-ffffffff81a267fd: memblock_is_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool memblock_is_reserved(phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a96f8e)
Location: mm/memblock.c:1730
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_find_free_area
```
**Symbols:**

```
ffffffff81a96f8e-ffffffff81a96faf: memblock_is_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool memblock_is_reserved(phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ace7fe)
Location: mm/memblock.c:1730
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_find_free_area
```
**Symbols:**

```
ffffffff81ace7fe-ffffffff81ace81f: memblock_is_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool memblock_is_reserved(phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81bc71e8)
Location: mm/memblock.c:1784
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_find_free_area
```
**Symbols:**

```
ffffffff81bc71e8-ffffffff81bc7202: memblock_is_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool memblock_is_reserved(phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c3ff0a)
Location: mm/memblock.c:1729
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_find_free_area
```
**Symbols:**

```
ffffffff81c3ff0a-ffffffff81c3ff24: memblock_is_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool memblock_is_reserved(phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c31fcb)
Location: mm/memblock.c:1730
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_find_free_area
```
**Symbols:**

```
ffffffff81c31fcb-ffffffff81c31fe5: memblock_is_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool memblock_is_reserved(phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81d509d5)
Location: mm/memblock.c:1758
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_find_free_area
```
**Symbols:**

```
ffffffff81d509d5-ffffffff81d509ef: memblock_is_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool memblock_is_reserved(phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f20ba9)
Location: mm/memblock.c:1765
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_find_free_area
```
**Symbols:**

```
ffffffff81f20ba9-ffffffff81f20bcb: memblock_is_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool memblock_is_reserved(phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820ca540)
Location: mm/memblock.c:1783
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_find_free_area
```
**Symbols:**

```
ffffffff820ca540-ffffffff820ca5ab: memblock_is_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool memblock_is_reserved(phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8214e7d0)
Location: mm/memblock.c:1805
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_find_free_area
```
**Symbols:**

```
ffffffff8214e7d0-ffffffff8214e83b: memblock_is_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool memblock_is_reserved(phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82231640)
Location: mm/memblock.c:1863
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_find_free_area
```
**Symbols:**

```
ffffffff82231640-ffffffff822316ab: memblock_is_reserved (STB_GLOBAL)
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
bool memblock_is_reserved(phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffff80001031d058)
Location: mm/memblock.c:1730
Inline: False
```
**Symbols:**

```
ffff80001031d058-ffff80001031d0f0: memblock_is_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool memblock_is_reserved(phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c0536ccc)
Location: mm/memblock.c:1730
Inline: False
```
**Symbols:**

```
c0536ccc-c0536d50: memblock_is_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool memblock_is_reserved(phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c0000000003f0e80)
Location: mm/memblock.c:1730
Inline: False
```
**Symbols:**

```
c0000000003f0e80-c0000000003f0f18: memblock_is_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool memblock_is_reserved(phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffe0000489bc)
Location: mm/memblock.c:1730
Inline: False
```
**Symbols:**

```
ffffffe0000489bc-ffffffe0000489e8: memblock_is_reserved (STB_GLOBAL)
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
bool memblock_is_reserved(phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a6d66e)
Location: mm/memblock.c:1730
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_find_free_area
```
**Symbols:**

```
ffffffff81a6d66e-ffffffff81a6d68f: memblock_is_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool memblock_is_reserved(phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a29bb5)
Location: mm/memblock.c:1730
Inline: False
```
**Symbols:**

```
ffffffff81a29bb5-ffffffff81a29bd6: memblock_is_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool memblock_is_reserved(phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ad9a7e)
Location: mm/memblock.c:1730
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_find_free_area
```
**Symbols:**

```
ffffffff81ad9a7e-ffffffff81ad9a9f: memblock_is_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool memblock_is_reserved(phys_addr_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ae5f34)
Location: mm/memblock.c:1730
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/xen/setup.c:xen_find_free_area
```
**Symbols:**

```
ffffffff81ae5f34-ffffffff81ae5f55: memblock_is_reserved (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
