# Function: <code>__efi_memmap_init</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data *data, bool late);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff8202242e)
Location: drivers/firmware/efi/memmap.c:68
Inline: True
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_install
  - drivers/firmware/efi/memmap.c:efi_memmap_init_late
  - drivers/firmware/efi/memmap.c:efi_memmap_init_early
```
**Symbols:**

```
ffffffff8202242e-ffffffff820224dc: __efi_memmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data *data, bool late);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff82105157)
Location: drivers/firmware/efi/memmap.c:68
Inline: True
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_install
  - drivers/firmware/efi/memmap.c:efi_memmap_init_late
  - drivers/firmware/efi/memmap.c:efi_memmap_init_early
```
**Symbols:**

```
ffffffff82105157-ffffffff8210520b: __efi_memmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data *data, bool late);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff8270e820)
Location: drivers/firmware/efi/memmap.c:69
Inline: True
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_install
  - drivers/firmware/efi/memmap.c:efi_memmap_init_late
  - drivers/firmware/efi/memmap.c:efi_memmap_init_early
```
**Symbols:**

```
ffffffff8270e820-ffffffff8270e8d4: __efi_memmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data *data, bool late);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff82738adf)
Location: drivers/firmware/efi/memmap.c:69
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_install
  - drivers/firmware/efi/memmap.c:efi_memmap_init_late
  - drivers/firmware/efi/memmap.c:efi_memmap_init_early
```
**Symbols:**

```
ffffffff82738adf-ffffffff82738b93: __efi_memmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data *data, bool late);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff828f2a8b)
Location: drivers/firmware/efi/memmap.c:69
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_install
  - drivers/firmware/efi/memmap.c:efi_memmap_init_late
  - drivers/firmware/efi/memmap.c:efi_memmap_init_early
```
**Symbols:**

```
ffffffff828f2a8b-ffffffff828f2b3f: __efi_memmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data *data, bool late);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff8290e378)
Location: drivers/firmware/efi/memmap.c:69
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_install
  - drivers/firmware/efi/memmap.c:efi_memmap_init_late
  - drivers/firmware/efi/memmap.c:efi_memmap_init_early
```
**Symbols:**

```
ffffffff8290e378-ffffffff8290e430: __efi_memmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data *data, bool late);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff82917d91)
Location: drivers/firmware/efi/memmap.c:69
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_install
  - drivers/firmware/efi/memmap.c:efi_memmap_init_late
  - drivers/firmware/efi/memmap.c:efi_memmap_init_early
```
**Symbols:**

```
ffffffff82917d91-ffffffff82917e49: __efi_memmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff82d2a510)
Location: drivers/firmware/efi/memmap.c:105
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_install
  - drivers/firmware/efi/memmap.c:efi_memmap_init_late
  - drivers/firmware/efi/memmap.c:efi_memmap_init_early
```
**Symbols:**

```
ffffffff82d2a510-ffffffff82d2a5f2: __efi_memmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff83018c2a)
Location: drivers/firmware/efi/memmap.c:105
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_install
  - drivers/firmware/efi/memmap.c:efi_memmap_init_late
  - drivers/firmware/efi/memmap.c:efi_memmap_init_early
```
**Symbols:**

```
ffffffff83018c2a-ffffffff83018d0c: __efi_memmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff83223c22)
Location: drivers/firmware/efi/memmap.c:105
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_install
  - drivers/firmware/efi/memmap.c:efi_memmap_init_late
  - drivers/firmware/efi/memmap.c:efi_memmap_init_early
```
**Symbols:**

```
ffffffff83223c22-ffffffff83223d04: __efi_memmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff8330da28)
Location: drivers/firmware/efi/memmap.c:105
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_install
  - drivers/firmware/efi/memmap.c:efi_memmap_init_late
  - drivers/firmware/efi/memmap.c:efi_memmap_init_early
```
**Symbols:**

```
ffffffff8330da28-ffffffff8330db0a: __efi_memmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff834c77a3)
Location: drivers/firmware/efi/memmap.c:105
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_install
  - drivers/firmware/efi/memmap.c:efi_memmap_init_late
  - drivers/firmware/efi/memmap.c:efi_memmap_init_early
```
**Symbols:**

```
ffffffff834c77a3-ffffffff834c789c: __efi_memmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff83f08800)
Location: drivers/firmware/efi/memmap.c:37
Inline: False
Direct callers:
  - arch/x86/platform/efi/memmap.c:efi_memmap_install
  - drivers/firmware/efi/memmap.c:efi_memmap_init_late
  - drivers/firmware/efi/memmap.c:efi_memmap_init_early
  - drivers/firmware/efi/memmap.c:efi_memmap_init_early
```
**Symbols:**

```
ffffffff83f08800-ffffffff83f088e8: __efi_memmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff8372e940)
Location: drivers/firmware/efi/memmap.c:37
Inline: False
Direct callers:
  - arch/x86/platform/efi/memmap.c:efi_memmap_install
  - drivers/firmware/efi/memmap.c:efi_memmap_init_late
  - drivers/firmware/efi/memmap.c:efi_memmap_init_early
  - drivers/firmware/efi/memmap.c:efi_memmap_init_early
```
**Symbols:**

```
ffffffff8372e940-ffffffff8372ea28: __efi_memmap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff83962d40)
Location: drivers/firmware/efi/memmap.c:37
Inline: False
Direct callers:
  - arch/x86/platform/efi/memmap.c:efi_memmap_install
  - drivers/firmware/efi/memmap.c:efi_memmap_init_late
  - drivers/firmware/efi/memmap.c:efi_memmap_init_early
  - drivers/firmware/efi/memmap.c:efi_memmap_init_early
```
**Symbols:**

```
ffffffff83962d40-ffffffff83962e28: __efi_memmap_init (STB_GLOBAL)
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
int __efi_memmap_init(struct efi_memory_map_data *data, bool late);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffff8000114a6654)
Location: drivers/firmware/efi/memmap.c:69
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_install
  - drivers/firmware/efi/memmap.c:efi_memmap_init_late
  - drivers/firmware/efi/memmap.c:efi_memmap_init_early
```
**Symbols:**

```
ffff8000114a6654-ffff8000114a6740: __efi_memmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data *data, bool late);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (c15a8a04)
Location: drivers/firmware/efi/memmap.c:69
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_install
  - drivers/firmware/efi/memmap.c:efi_memmap_init_late
  - drivers/firmware/efi/memmap.c:efi_memmap_init_early
```
**Symbols:**

```
c15a8a04-c15a8ae0: __efi_memmap_init (STB_LOCAL)
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
int __efi_memmap_init(struct efi_memory_map_data *data, bool late);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff828fd197)
Location: drivers/firmware/efi/memmap.c:69
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_install
  - drivers/firmware/efi/memmap.c:efi_memmap_init_late
  - drivers/firmware/efi/memmap.c:efi_memmap_init_early
```
**Symbols:**

```
ffffffff828fd197-ffffffff828fd24f: __efi_memmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data *data, bool late);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff828f4a33)
Location: drivers/firmware/efi/memmap.c:69
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_install
  - drivers/firmware/efi/memmap.c:efi_memmap_init_late
  - drivers/firmware/efi/memmap.c:efi_memmap_init_early
```
**Symbols:**

```
ffffffff828f4a33-ffffffff828f4aeb: __efi_memmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data *data, bool late);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff829123c6)
Location: drivers/firmware/efi/memmap.c:69
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_install
  - drivers/firmware/efi/memmap.c:efi_memmap_init_late
  - drivers/firmware/efi/memmap.c:efi_memmap_init_early
```
**Symbols:**

```
ffffffff829123c6-ffffffff8291247e: __efi_memmap_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __efi_memmap_init(struct efi_memory_map_data *data, bool late);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff82918df3)
Location: drivers/firmware/efi/memmap.c:69
Inline: False
Direct callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_install
  - drivers/firmware/efi/memmap.c:efi_memmap_init_late
  - drivers/firmware/efi/memmap.c:efi_memmap_init_early
```
**Symbols:**

```
ffffffff82918df3-ffffffff82918eab: __efi_memmap_init (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool late</code>
</li>
</ul>
</details>
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
