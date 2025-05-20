# Function: <code>efi_mem_reserve_iomem</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int efi_mem_reserve_iomem(phys_addr_t addr, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff818e7ac0)
Location: drivers/firmware/efi/efi.c:1036
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
**Symbols:**

```
ffffffff818e7ac0-ffffffff818e7b3e: efi_mem_reserve_iomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int efi_mem_reserve_iomem(phys_addr_t addr, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff819bae30)
Location: drivers/firmware/efi/efi.c:950
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
**Symbols:**

```
ffffffff819bae30-ffffffff819baeae: efi_mem_reserve_iomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int efi_mem_reserve_iomem(phys_addr_t addr, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff819bd090)
Location: drivers/firmware/efi/efi.c:958
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
**Symbols:**

```
ffffffff819bd090-ffffffff819bd10e: efi_mem_reserve_iomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int efi_mem_reserve_iomem(phys_addr_t addr, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff819a1820)
Location: drivers/firmware/efi/efi.c:958
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
**Symbols:**

```
ffffffff819a1820-ffffffff819a189e: efi_mem_reserve_iomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int efi_mem_reserve_iomem(phys_addr_t addr, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81a4e7d0)
Location: drivers/firmware/efi/efi.c:965
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
**Symbols:**

```
ffffffff81a4e7d0-ffffffff81a4e84e: efi_mem_reserve_iomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int efi_mem_reserve_iomem(phys_addr_t addr, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81bbd3e0)
Location: drivers/firmware/efi/efi.c:979
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
**Symbols:**

```
ffffffff81bbd3e0-ffffffff81bbd467: efi_mem_reserve_iomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int efi_mem_reserve_iomem(phys_addr_t addr, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81d63040)
Location: drivers/firmware/efi/efi.c:1004
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
**Symbols:**

```
ffffffff81d63040-ffffffff81d630c7: efi_mem_reserve_iomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int efi_mem_reserve_iomem(phys_addr_t addr, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81dce110)
Location: drivers/firmware/efi/efi.c:1071
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
**Symbols:**

```
ffffffff81dce110-ffffffff81dce197: efi_mem_reserve_iomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int efi_mem_reserve_iomem(phys_addr_t addr, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81e86ce0)
Location: drivers/firmware/efi/efi.c:1108
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
**Symbols:**

```
ffffffff81e86ce0-ffffffff81e86d96: efi_mem_reserve_iomem (STB_LOCAL)
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
int efi_mem_reserve_iomem(phys_addr_t addr, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffff800010b5ab20)
Location: drivers/firmware/efi/efi.c:1036
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
**Symbols:**

```
ffff800010b5ab20-ffff800010b5abb8: efi_mem_reserve_iomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int efi_mem_reserve_iomem(phys_addr_t addr, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (c0c3b6cc)
Location: drivers/firmware/efi/efi.c:1036
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
**Symbols:**

```
c0c3b6cc-c0c3b75c: efi_mem_reserve_iomem (STB_LOCAL)
```
</details>
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
int efi_mem_reserve_iomem(phys_addr_t addr, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8188a840)
Location: drivers/firmware/efi/efi.c:1036
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
**Symbols:**

```
ffffffff8188a840-ffffffff8188a8be: efi_mem_reserve_iomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int efi_mem_reserve_iomem(phys_addr_t addr, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff818421c0)
Location: drivers/firmware/efi/efi.c:1036
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
**Symbols:**

```
ffffffff818421c0-ffffffff8184223e: efi_mem_reserve_iomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int efi_mem_reserve_iomem(phys_addr_t addr, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff818dc920)
Location: drivers/firmware/efi/efi.c:1036
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
**Symbols:**

```
ffffffff818dc920-ffffffff818dc99e: efi_mem_reserve_iomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int efi_mem_reserve_iomem(phys_addr_t addr, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff818f9430)
Location: drivers/firmware/efi/efi.c:1036
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
**Symbols:**

```
ffffffff818f9430-ffffffff818f94ae: efi_mem_reserve_iomem (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
