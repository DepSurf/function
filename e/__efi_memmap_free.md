# Function: <code>__efi_memmap_free</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __efi_memmap_free(u64 phys, long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff82d2a4b0)
Location: drivers/firmware/efi/memmap.c:32
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
```
**Symbols:**

```
ffffffff82d2a4b0-ffffffff82d2a510: __efi_memmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __efi_memmap_free(u64 phys, long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff83018bc7)
Location: drivers/firmware/efi/memmap.c:32
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
```
**Symbols:**

```
ffffffff83018bc7-ffffffff83018c2a: __efi_memmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __efi_memmap_free(u64 phys, long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff83223bbf)
Location: drivers/firmware/efi/memmap.c:32
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
```
**Symbols:**

```
ffffffff83223bbf-ffffffff83223c22: __efi_memmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __efi_memmap_free(u64 phys, long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff8330d9c5)
Location: drivers/firmware/efi/memmap.c:32
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
```
**Symbols:**

```
ffffffff8330d9c5-ffffffff8330da28: __efi_memmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __efi_memmap_free(u64 phys, long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff834c7733)
Location: drivers/firmware/efi/memmap.c:32
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
```
**Symbols:**

```
ffffffff834c7733-ffffffff834c77a3: __efi_memmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __efi_memmap_free(u64 phys, long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/memmap.c (ffffffff83ea1880)
Location: arch/x86/platform/efi/memmap.c:33
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
```
**Symbols:**

```
ffffffff83ea1880-ffffffff83ea1912: __efi_memmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __efi_memmap_free(u64 phys, long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/memmap.c (ffffffff836c5ae0)
Location: arch/x86/platform/efi/memmap.c:33
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
```
**Symbols:**

```
ffffffff836c5ae0-ffffffff836c5b72: __efi_memmap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __efi_memmap_free(u64 phys, long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/memmap.c (ffffffff838f66e0)
Location: arch/x86/platform/efi/memmap.c:33
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
```
**Symbols:**

```
ffffffff838f66e0-ffffffff838f6772: __efi_memmap_free (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
