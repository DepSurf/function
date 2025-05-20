# Function: <code>parse_build_id_buf</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int parse_build_id_buf(unsigned char *build_id, __u32 *size, const void *note_start, Elf32_Word note_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/buildid.c (ffffffff8165cf90)
Location: lib/buildid.c:16
Inline: False
Direct callers:
  - lib/buildid.c:init_vmlinux_build_id
  - lib/buildid.c:build_id_parse
  - lib/buildid.c:build_id_parse
```
**Symbols:**

```
ffffffff8165cf90-ffffffff8165d11a: parse_build_id_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int parse_build_id_buf(unsigned char *build_id, __u32 *size, const void *note_start, Elf32_Word note_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/buildid.c (ffffffff817763c0)
Location: lib/buildid.c:16
Inline: False
Direct callers:
  - lib/buildid.c:init_vmlinux_build_id
  - lib/buildid.c:build_id_parse
  - lib/buildid.c:build_id_parse
```
**Symbols:**

```
ffffffff817763c0-ffffffff8177656b: parse_build_id_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int parse_build_id_buf(unsigned char *build_id, __u32 *size, const void *note_start, Elf32_Word note_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/buildid.c (ffffffff8201ee00)
Location: lib/buildid.c:16
Inline: False
Direct callers:
  - lib/buildid.c:init_vmlinux_build_id
  - lib/buildid.c:build_id_parse
  - lib/buildid.c:build_id_parse
```
**Symbols:**

```
ffffffff8201ee00-ffffffff8201efab: parse_build_id_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int parse_build_id_buf(unsigned char *build_id, __u32 *size, const void *note_start, Elf32_Word note_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/buildid.c (ffffffff8209ee10)
Location: lib/buildid.c:16
Inline: False
Direct callers:
  - lib/buildid.c:init_vmlinux_build_id
  - lib/buildid.c:build_id_parse
  - lib/buildid.c:build_id_parse
```
**Symbols:**

```
ffffffff8209ee10-ffffffff8209efbb: parse_build_id_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int parse_build_id_buf(unsigned char *build_id, __u32 *size, const void *note_start, Elf32_Word note_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/buildid.c (ffffffff82176e10)
Location: lib/buildid.c:16
Inline: False
Direct callers:
  - lib/buildid.c:init_vmlinux_build_id
  - lib/buildid.c:build_id_parse
  - lib/buildid.c:build_id_parse
```
**Symbols:**

```
ffffffff82176e10-ffffffff82176fbb: parse_build_id_buf (STB_LOCAL)
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
