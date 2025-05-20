# Function: <code>klp_write_section_relocs</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int klp_write_section_relocs(struct module *pmod, Elf64_Shdr *sechdrs, const char *shstrtab, const char *strtab, unsigned int symndx, unsigned int secndx, const char *objname, bool apply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811cf5c0)
Location: kernel/livepatch/core.c:294
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_write_object_relocs
  - kernel/livepatch/core.c:klp_apply_section_relocs
```
**Symbols:**

```
ffffffff811cf5c0-ffffffff811cf705: klp_write_section_relocs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int klp_write_section_relocs(struct module *pmod, Elf64_Shdr *sechdrs, const char *shstrtab, const char *strtab, unsigned int symndx, unsigned int secndx, const char *objname, bool apply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811e4210)
Location: kernel/livepatch/core.c:294
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_write_object_relocs
  - kernel/livepatch/core.c:klp_apply_section_relocs
```
**Symbols:**

```
ffffffff811e4210-ffffffff811e4355: klp_write_section_relocs (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
