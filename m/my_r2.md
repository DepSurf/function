# Function: <code>my_r2</code>

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
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long unsigned int my_r2(const Elf64_Shdr *sechdrs, struct module *me);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/module_64.c (c00000000004ff38)
Location: arch/powerpc/kernel/module_64.c:393
Inline: True
Inline callers:
  - arch/powerpc/kernel/module_64.c:apply_relocate_add
  - arch/powerpc/kernel/module_64.c:apply_relocate_add
  - arch/powerpc/kernel/module_64.c:apply_relocate_add
  - arch/powerpc/kernel/module_64.c:apply_relocate_add
  - arch/powerpc/kernel/module_64.c:apply_relocate_add
  - arch/powerpc/kernel/module_64.c:apply_relocate_add
  - arch/powerpc/kernel/module_64.c:apply_relocate_add
  - arch/powerpc/kernel/module_64.c:apply_relocate_add
  - arch/powerpc/kernel/module_64.c:apply_relocate_add
```
**Symbols:**

```
c00000000004e4e0-c00000000004e500: my_r2 (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
