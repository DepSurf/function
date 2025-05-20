# Function: <code>get_next_modinfo</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *get_next_modinfo(const struct load_info *info, const char *tag, char *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811511e0)
Location: kernel/module.c:2541
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffff811511e0-ffffffff81151334: get_next_modinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *get_next_modinfo(const struct load_info *info, const char *tag, char *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81162bf0)
Location: kernel/module.c:2535
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:setup_load_info
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffff81162bf0-ffffffff81162d45: get_next_modinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *get_next_modinfo(const struct load_info *info, const char *tag, char *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115ef40)
Location: kernel/module.c:2622
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:setup_load_info
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffff8115ef40-ffffffff8115f095: get_next_modinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *get_next_modinfo(const struct load_info *info, const char *tag, char *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115ff60)
Location: kernel/module.c:2546
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffff8115ff60-ffffffff8116009a: get_next_modinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *get_next_modinfo(const struct load_info *info, const char *tag, char *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81185110)
Location: kernel/module.c:2548
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffff81185110-ffffffff8118524a: get_next_modinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *get_next_modinfo(const struct load_info *info, const char *tag, char *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff8118bcf0)
Location: kernel/module/main.c:1543
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:resolve_symbol
```
**Symbols:**

```
ffffffff8118bcf0-ffffffff8118be1d: get_next_modinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *get_next_modinfo(const struct load_info *info, const char *tag, char *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811c8410)
Location: kernel/module/main.c:1541
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:resolve_symbol
```
**Symbols:**

```
ffffffff811c8410-ffffffff811c853d: get_next_modinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *get_next_modinfo(const struct load_info *info, const char *tag, char *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811dbd80)
Location: kernel/module/main.c:1031
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:early_mod_check
  - kernel/module/main.c:early_mod_check
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:elf_validity_cache_copy
  - kernel/module/main.c:resolve_symbol
```
**Symbols:**

```
ffffffff811dbd80-ffffffff811dbead: get_next_modinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *get_next_modinfo(const struct load_info *info, const char *tag, char *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811f1bd0)
Location: kernel/module/main.c:1031
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:early_mod_check
  - kernel/module/main.c:early_mod_check
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:elf_validity_cache_copy
  - kernel/module/main.c:resolve_symbol
```
**Symbols:**

```
ffffffff811f1bd0-ffffffff811f1cfd: get_next_modinfo (STB_LOCAL)
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
char *get_next_modinfo(const struct load_info *info, const char *tag, char *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101c0100)
Location: kernel/module.c:2541
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:resolve_symbol
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffff8000101c0100-ffff8000101c0294: get_next_modinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *get_next_modinfo(const struct load_info *info, const char *tag, char *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c04077f4)
Location: kernel/module.c:2541
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:resolve_symbol
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
c04077f4-c040795c: get_next_modinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *get_next_modinfo(const struct load_info *info, const char *tag, char *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c000000000225d90)
Location: kernel/module.c:2541
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:resolve_symbol
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
c000000000225d90-c000000000225ff0: get_next_modinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *get_next_modinfo(const struct load_info *info, const char *tag, char *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe000142506)
Location: kernel/module.c:2541
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:resolve_symbol
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffe000142506-ffffffe00014262a: get_next_modinfo (STB_LOCAL)
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
char *get_next_modinfo(const struct load_info *info, const char *tag, char *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81149800)
Location: kernel/module.c:2541
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffff81149800-ffffffff81149954: get_next_modinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *get_next_modinfo(const struct load_info *info, const char *tag, char *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113cab0)
Location: kernel/module.c:2541
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffff8113cab0-ffffffff8113cc04: get_next_modinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *get_next_modinfo(const struct load_info *info, const char *tag, char *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811476b0)
Location: kernel/module.c:2541
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffff811476b0-ffffffff81147804: get_next_modinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *get_next_modinfo(const struct load_info *info, const char *tag, char *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811542c0)
Location: kernel/module.c:2541
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffff811542c0-ffffffff81154414: get_next_modinfo (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
