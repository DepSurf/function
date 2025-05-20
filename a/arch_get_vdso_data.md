# Function: <code>arch_get_vdso_data</code>

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
struct vdso_data *arch_get_vdso_data(void *vvar_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81005bd0)
Location: arch/x86/entry/vdso/vma.c:35
Inline: False
```
**Symbols:**

```
ffffffff81005bd0-ffffffff81005be2: arch_get_vdso_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vdso_data *arch_get_vdso_data(void *vvar_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004b80)
Location: arch/x86/entry/vdso/vma.c:35
Inline: False
Direct callers:
  - kernel/time/namespace.c:timens_commit
```
**Symbols:**

```
ffffffff81004b80-ffffffff81004b92: arch_get_vdso_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vdso_data *arch_get_vdso_data(void *vvar_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004b70)
Location: arch/x86/entry/vdso/vma.c:35
Inline: False
Direct callers:
  - kernel/time/namespace.c:timens_commit
```
**Symbols:**

```
ffffffff81004b70-ffffffff81004b82: arch_get_vdso_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vdso_data *arch_get_vdso_data(void *vvar_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810051a0)
Location: arch/x86/entry/vdso/vma.c:35
Inline: False
Direct callers:
  - kernel/time/namespace.c:timens_commit
```
**Symbols:**

```
ffffffff810051a0-ffffffff810051b2: arch_get_vdso_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct vdso_data *arch_get_vdso_data(void *vvar_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004200)
Location: arch/x86/entry/vdso/vma.c:35
Inline: False
Direct callers:
  - kernel/time/namespace.c:timens_commit
```
**Symbols:**

```
ffffffff81004200-ffffffff81004218: arch_get_vdso_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct vdso_data *arch_get_vdso_data(void *vvar_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004aa0)
Location: arch/x86/entry/vdso/vma.c:35
Inline: False
Direct callers:
  - kernel/time/namespace.c:timens_commit
```
**Symbols:**

```
ffffffff81004aa0-ffffffff81004ab8: arch_get_vdso_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct vdso_data *arch_get_vdso_data(void *vvar_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004280)
Location: arch/x86/entry/vdso/vma.c:35
Inline: False
Direct callers:
  - kernel/time/namespace.c:timens_commit
```
**Symbols:**

```
ffffffff81004280-ffffffff81004298: arch_get_vdso_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct vdso_data *arch_get_vdso_data(void *vvar_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81006b90)
Location: arch/x86/entry/vdso/vma.c:35
Inline: False
Direct callers:
  - kernel/time/namespace.c:timens_commit
```
**Symbols:**

```
ffffffff81006b90-ffffffff81006ba8: arch_get_vdso_data (STB_GLOBAL)
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
