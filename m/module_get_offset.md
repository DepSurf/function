# Function: <code>module_get_offset</code>

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
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int module_get_offset(struct module *mod, unsigned int *size, Elf64_Shdr *sechdr, unsigned int section);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff8118e9ad)
Location: kernel/module/main.c:1392
Inline: True
Inline callers:
  - kernel/module/main.c:layout_sections
  - kernel/module/main.c:layout_sections
Direct callers:
  - kernel/module/kallsyms.c:layout_symtab
  - kernel/module/kallsyms.c:layout_symtab
```
**Symbols:**

```
ffffffff8118e630-ffffffff8118e679: module_get_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int module_get_offset(struct module *mod, unsigned int *size, Elf64_Shdr *sechdr, unsigned int section);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811cb3bd)
Location: kernel/module/main.c:1390
Inline: True
Inline callers:
  - kernel/module/main.c:layout_sections
  - kernel/module/main.c:layout_sections
Direct callers:
  - kernel/module/kallsyms.c:layout_symtab
  - kernel/module/kallsyms.c:layout_symtab
```
**Symbols:**

```
ffffffff811cb000-ffffffff811cb049: module_get_offset (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
