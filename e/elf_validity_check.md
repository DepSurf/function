# Function: <code>elf_validity_check</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int elf_validity_check(struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3018
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8115d580-ffffffff8115d70f: elf_validity_check (STB_LOCAL)
ffffffff81be3e97-ffffffff81be3ecf: elf_validity_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int elf_validity_check(struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:2942
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8115e7e0-ffffffff8115e96f: elf_validity_check (STB_LOCAL)
ffffffff81bd5d6f-ffffffff81bd5da7: elf_validity_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int elf_validity_check(struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:2964
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81183870-ffffffff811839ff: elf_validity_check (STB_LOCAL)
ffffffff81cb23e3-ffffffff81cb241b: elf_validity_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int elf_validity_check(struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:1651
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff8118b1f0-ffffffff8118b386: elf_validity_check (STB_LOCAL)
ffffffff81e61477-ffffffff81e61588: elf_validity_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int elf_validity_check(struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811cb950)
Location: kernel/module/main.c:1649
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff811cb950-ffffffff811cbc3f: elf_validity_check (STB_LOCAL)
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
</ul>
