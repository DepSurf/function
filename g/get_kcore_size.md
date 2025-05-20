# Function: <code>get_kcore_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
size_t get_kcore_size(int *nphdr, size_t *elf_buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff81286850)
Location: fs/proc/kcore.c:75
Inline: False
Direct callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:read_kcore
```
**Symbols:**

```
ffffffff81286850-ffffffff812868f3: get_kcore_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
size_t get_kcore_size(int *nphdr, size_t *elf_buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff812b39f0)
Location: fs/proc/kcore.c:75
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffff812b39f0-ffffffff812b3a93: get_kcore_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t get_kcore_size(int *nphdr, size_t *elf_buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff812c9280)
Location: fs/proc/kcore.c:75
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffff812c9280-ffffffff812c9323: get_kcore_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t get_kcore_size(int *nphdr, size_t *elf_buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff812d65c0)
Location: fs/proc/kcore.c:76
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffff812d65c0-ffffffff812d6663: get_kcore_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t get_kcore_size(int *nphdr, size_t *elf_buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff812fae10)
Location: fs/proc/kcore.c:77
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffff812fae10-ffffffff812faeb3: get_kcore_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t get_kcore_size(int *nphdr, size_t *elf_buflen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff813283c0)
Location: fs/proc/kcore.c:77
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffff813283c0-ffffffff81328463: get_kcore_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t get_kcore_size(int *nphdr, size_t *phdrs_len, size_t *notes_len, size_t *data_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff8133f5a0)
Location: fs/proc/kcore.c:68
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffff8133f5a0-ffffffff8133f65b: get_kcore_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t get_kcore_size(int *nphdr, size_t *phdrs_len, size_t *notes_len, size_t *data_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff81367890)
Location: fs/proc/kcore.c:90
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffff81367890-ffffffff8136794b: get_kcore_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t get_kcore_size(int *nphdr, size_t *phdrs_len, size_t *notes_len, size_t *data_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff8137fb10)
Location: fs/proc/kcore.c:91
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffff8137fb10-ffffffff8137fbcb: get_kcore_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t get_kcore_size(int *nphdr, size_t *phdrs_len, size_t *notes_len, size_t *data_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff813c9f60)
Location: fs/proc/kcore.c:91
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
```
**Symbols:**

```
ffffffff813c9f60-ffffffff813ca05b: get_kcore_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t get_kcore_size(int *nphdr, size_t *phdrs_len, size_t *notes_len, size_t *data_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff813dbc40)
Location: fs/proc/kcore.c:91
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
```
**Symbols:**

```
ffffffff813dbc40-ffffffff813dbd3b: get_kcore_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t get_kcore_size(int *nphdr, size_t *phdrs_len, size_t *notes_len, size_t *data_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff813e2b60)
Location: fs/proc/kcore.c:91
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
```
**Symbols:**

```
ffffffff813e2b60-ffffffff813e2c5b: get_kcore_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t get_kcore_size(int *nphdr, size_t *phdrs_len, size_t *notes_len, size_t *data_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff81434670)
Location: fs/proc/kcore.c:91
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
```
**Symbols:**

```
ffffffff81434670-ffffffff8143476b: get_kcore_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t get_kcore_size(int *nphdr, size_t *phdrs_len, size_t *notes_len, size_t *data_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff814ae800)
Location: fs/proc/kcore.c:91
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
```
**Symbols:**

```
ffffffff814ae800-ffffffff814ae8ff: get_kcore_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t get_kcore_size(int *nphdr, size_t *phdrs_len, size_t *notes_len, size_t *data_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff81544e70)
Location: fs/proc/kcore.c:90
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
```
**Symbols:**

```
ffffffff81544e70-ffffffff81544f6f: get_kcore_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t get_kcore_size(int *nphdr, size_t *phdrs_len, size_t *notes_len, size_t *data_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff8157ca50)
Location: fs/proc/kcore.c:90
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore_iter
```
**Symbols:**

```
ffffffff8157ca50-ffffffff8157cb4f: get_kcore_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t get_kcore_size(int *nphdr, size_t *phdrs_len, size_t *notes_len, size_t *data_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff815b5370)
Location: fs/proc/kcore.c:90
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore_iter
```
**Symbols:**

```
ffffffff815b5370-ffffffff815b546f: get_kcore_size (STB_LOCAL)
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
size_t get_kcore_size(int *nphdr, size_t *phdrs_len, size_t *notes_len, size_t *data_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffff80001044d458)
Location: fs/proc/kcore.c:91
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffff80001044d458-ffff80001044d538: get_kcore_size (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t get_kcore_size(int *nphdr, size_t *phdrs_len, size_t *notes_len, size_t *data_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (c000000000564d70)
Location: fs/proc/kcore.c:91
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
c000000000564d70-c000000000564e88: get_kcore_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t get_kcore_size(int *nphdr, size_t *phdrs_len, size_t *notes_len, size_t *data_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffe0002e207c)
Location: fs/proc/kcore.c:91
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffe0002e207c-ffffffe0002e212e: get_kcore_size (STB_LOCAL)
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
size_t get_kcore_size(int *nphdr, size_t *phdrs_len, size_t *notes_len, size_t *data_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff813780f0)
Location: fs/proc/kcore.c:91
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffff813780f0-ffffffff813781ab: get_kcore_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t get_kcore_size(int *nphdr, size_t *phdrs_len, size_t *notes_len, size_t *data_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff81368bc0)
Location: fs/proc/kcore.c:91
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffff81368bc0-ffffffff81368c7b: get_kcore_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t get_kcore_size(int *nphdr, size_t *phdrs_len, size_t *notes_len, size_t *data_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff81375bc0)
Location: fs/proc/kcore.c:91
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffff81375bc0-ffffffff81375c7b: get_kcore_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t get_kcore_size(int *nphdr, size_t *phdrs_len, size_t *notes_len, size_t *data_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff81389670)
Location: fs/proc/kcore.c:91
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffff81389670-ffffffff8138972b: get_kcore_size (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t *phdrs_len</code>
</li>
<li>
<b>Param added. </b>
<code>size_t *notes_len</code>
</li>
<li>
<b>Param added. </b>
<code>size_t *data_offset</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t *elf_buflen</code>
</li>
</ul>
</details>
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
