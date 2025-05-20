# Function: <code>dump_vma_snapshot</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dump_vma_snapshot(struct coredump_params *cprm, int *vma_count, struct core_vma_metadata **vma_meta, size_t *vma_data_size_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff813b96a0)
Location: fs/coredump.c:1072
Inline: False
Direct callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
**Symbols:**

```
ffffffff813b96a0-ffffffff813b98bc: dump_vma_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dump_vma_snapshot(struct coredump_params *cprm, int *vma_count, struct core_vma_metadata **vma_meta, size_t *vma_data_size_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff813c0800)
Location: fs/coredump.c:1090
Inline: False
Direct callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
**Symbols:**

```
ffffffff813c0800-ffffffff813c0a1f: dump_vma_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dump_vma_snapshot(struct coredump_params *cprm, int *vma_count, struct core_vma_metadata **vma_meta, size_t *vma_data_size_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81410670)
Location: fs/coredump.c:1097
Inline: False
Direct callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
**Symbols:**

```
ffffffff81410670-ffffffff8141088b: dump_vma_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool dump_vma_snapshot(struct coredump_params *cprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff814848f0)
Location: fs/coredump.c:1120
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff814848f0-ffffffff81484b8b: dump_vma_snapshot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool dump_vma_snapshot(struct coredump_params *cprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81517dc0)
Location: fs/coredump.c:1145
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81517dc0-ffffffff815180a4: dump_vma_snapshot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool dump_vma_snapshot(struct coredump_params *cprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff8154f6d0)
Location: fs/coredump.c:1145
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff8154f6d0-ffffffff8154f9b1: dump_vma_snapshot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool dump_vma_snapshot(struct coredump_params *cprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81585510)
Location: fs/coredump.c:1183
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81585510-ffffffff815857f0: dump_vma_snapshot (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int *vma_count</code>
</li>
<li>
<b>Param removed. </b>
<code>struct core_vma_metadata **vma_meta</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t *vma_data_size_ptr</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
