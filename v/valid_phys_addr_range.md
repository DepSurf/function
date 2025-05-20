# Function: <code>valid_phys_addr_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffff815112d5)
Location: drivers/char/mem.c:51
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffff81563882)
Location: drivers/char/mem.c:52
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffff8158ffe2)
Location: drivers/char/mem.c:52
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffff815a409c)
Location: drivers/char/mem.c:51
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int valid_phys_addr_range(phys_addr_t addr, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81078130)
Location: arch/x86/mm/mmap.c:227
Inline: False
Direct callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff81078130-ffffffff8107816f: valid_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int valid_phys_addr_range(phys_addr_t addr, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff8107ac00)
Location: arch/x86/mm/mmap.c:231
Inline: False
Direct callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff8107ac00-ffffffff8107ac3f: valid_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int valid_phys_addr_range(phys_addr_t addr, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81081540)
Location: arch/x86/mm/mmap.c:231
Inline: False
Direct callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff81081540-ffffffff8108157f: valid_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int valid_phys_addr_range(phys_addr_t addr, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff810851b0)
Location: arch/x86/mm/mmap.c:218
Inline: False
Direct callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff810851b0-ffffffff810851f8: valid_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int valid_phys_addr_range(phys_addr_t addr, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81085ea0)
Location: arch/x86/mm/mmap.c:218
Inline: False
Direct callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff81085ea0-ffffffff81085ee8: valid_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int valid_phys_addr_range(phys_addr_t addr, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81089600)
Location: arch/x86/mm/mmap.c:218
Inline: False
Direct callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff81089600-ffffffff81089648: valid_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int valid_phys_addr_range(phys_addr_t addr, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff810897e0)
Location: arch/x86/mm/mmap.c:218
Inline: False
Direct callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff810897e0-ffffffff81089828: valid_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int valid_phys_addr_range(phys_addr_t addr, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff8108a4d0)
Location: arch/x86/mm/mmap.c:218
Inline: False
Direct callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff8108a4d0-ffffffff8108a518: valid_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int valid_phys_addr_range(phys_addr_t addr, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81099a30)
Location: arch/x86/mm/mmap.c:218
Inline: False
Direct callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff81099a30-ffffffff81099a78: valid_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int valid_phys_addr_range(phys_addr_t addr, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff810ac970)
Location: arch/x86/mm/mmap.c:218
Inline: False
Direct callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff810ac970-ffffffff810ac9c4: valid_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int valid_phys_addr_range(phys_addr_t addr, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff810c6a20)
Location: arch/x86/mm/mmap.c:218
Inline: False
Direct callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff810c6a20-ffffffff810c6a74: valid_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int valid_phys_addr_range(phys_addr_t addr, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff810ca1b0)
Location: arch/x86/mm/mmap.c:218
Inline: False
Direct callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff810ca1b0-ffffffff810ca204: valid_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int valid_phys_addr_range(phys_addr_t addr, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff810d2610)
Location: arch/x86/mm/mmap.c:218
Inline: False
Direct callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff810d2610-ffffffff810d2664: valid_phys_addr_range (STB_GLOBAL)
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
int valid_phys_addr_range(phys_addr_t addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/mmap.c (ffff8000100ae060)
Location: arch/arm64/mm/mmap.c:27
Inline: False
Direct callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffff8000100ae060-ffff8000100ae0b8: valid_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int valid_phys_addr_range(phys_addr_t addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mm/mmap.c (c031f708)
Location: arch/arm/mm/mmap.c:151
Inline: False
Direct callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
c031f708-c031f764: valid_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (c000000000942c04)
Location: drivers/char/mem.c:52
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffe000560134)
Location: drivers/char/mem.c:52
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
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
int valid_phys_addr_range(phys_addr_t addr, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81084ea0)
Location: arch/x86/mm/mmap.c:218
Inline: False
Direct callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff81084ea0-ffffffff81084ee8: valid_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int valid_phys_addr_range(phys_addr_t addr, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81073b70)
Location: arch/x86/mm/mmap.c:218
Inline: False
Direct callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff81073b70-ffffffff81073bb8: valid_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int valid_phys_addr_range(phys_addr_t addr, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81084e50)
Location: arch/x86/mm/mmap.c:218
Inline: False
Direct callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff81084e50-ffffffff81084e98: valid_phys_addr_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int valid_phys_addr_range(phys_addr_t addr, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81086fa0)
Location: arch/x86/mm/mmap.c:218
Inline: False
Direct callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff81086fa0-ffffffff81086fe8: valid_phys_addr_range (STB_GLOBAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t size</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t count</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t size</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t count</code>
</li>
</ul>
</details>
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
