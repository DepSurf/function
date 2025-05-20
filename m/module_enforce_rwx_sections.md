# Function: <code>module_enforce_rwx_sections</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81166828)
Location: kernel/module.c:2064
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81162f60)
Location: kernel/module.c:2123
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81163a48)
Location: kernel/module.c:2033
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81189118)
Location: kernel/module.c:2035
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int module_enforce_rwx_sections(Elf64_Ehdr *hdr, Elf64_Shdr *sechdrs, char *secstrings, struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/strict_rwx.c (0)
Location: kernel/module/strict_rwx.c:125
Inline: False
Direct callers:
  - kernel/module/main.c:layout_and_allocate
```
**Symbols:**

```
ffffffff81e61b65-ffffffff81e61b96: module_enforce_rwx_sections.cold (STB_LOCAL)
ffffffff811907e0-ffffffff81190833: module_enforce_rwx_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int module_enforce_rwx_sections(Elf64_Ehdr *hdr, Elf64_Shdr *sechdrs, char *secstrings, struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/strict_rwx.c (ffffffff811cdcf0)
Location: kernel/module/strict_rwx.c:125
Inline: False
Direct callers:
  - kernel/module/main.c:layout_and_allocate
```
**Symbols:**

```
ffffffff811cdcf0-ffffffff811cdd5e: module_enforce_rwx_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int module_enforce_rwx_sections(Elf64_Ehdr *hdr, Elf64_Shdr *sechdrs, char *secstrings, struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/strict_rwx.c (ffffffff811e1580)
Location: kernel/module/strict_rwx.c:62
Inline: False
```
**Symbols:**

```
ffffffff811e1580-ffffffff811e15ec: module_enforce_rwx_sections (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int module_enforce_rwx_sections(Elf64_Ehdr *hdr, Elf64_Shdr *sechdrs, char *secstrings, struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/strict_rwx.c (ffffffff811f72b0)
Location: kernel/module/strict_rwx.c:62
Inline: False
```
**Symbols:**

```
ffffffff811f72b0-ffffffff811f731c: module_enforce_rwx_sections (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
