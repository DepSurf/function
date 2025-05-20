# Function: <code>get_modinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff81106410)
Location: kernel/module.c:2318
Inline: True
Direct callers:
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81106410-ffffffff811064b1: get_modinfo.isra.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff8110dd40)
Location: kernel/module.c:2441
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff8110dd40-ffffffff8110dde6: get_modinfo.isra.49 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff81115650)
Location: kernel/module.c:2453
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff81115650-ffffffff811156f6: get_modinfo.isra.49 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff81116570)
Location: kernel/module.c:2480
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff81116570-ffffffff81116622: get_modinfo.isra.46 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff81121b00)
Location: kernel/module.c:2488
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff81121b00-ffffffff81121bb2: get_modinfo.isra.46 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff8112f600)
Location: kernel/module.c:2483
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff8112f600-ffffffff8112f6e0: get_modinfo.isra.51 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *get_modinfo(struct load_info *info, const char *tag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81139fa0)
Location: kernel/module.c:2484
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
```
**Symbols:**

```
ffffffff81139fa0-ffffffff8113a075: get_modinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *get_modinfo(struct load_info *info, const char *tag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811456d0)
Location: kernel/module.c:2484
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
```
**Symbols:**

```
ffffffff811456d0-ffffffff811457b5: get_modinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115571a)
Location: kernel/module.c:2567
Inline: True
Inline callers:
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
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81166c5c)
Location: kernel/module.c:2561
Inline: True
Inline callers:
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
In kernel/module.c (ffffffff81163412)
Location: kernel/module.c:2648
Inline: True
Inline callers:
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
In kernel/module.c (ffffffff81164248)
Location: kernel/module.c:2572
Inline: True
Inline callers:
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
In kernel/module.c (ffffffff81189956)
Location: kernel/module.c:2574
Inline: True
Inline callers:
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
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff8118f26f)
Location: kernel/module/main.c:1569
Inline: True
Inline callers:
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
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811cc125)
Location: kernel/module/main.c:1567
Inline: True
Inline callers:
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
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811df799)
Location: kernel/module/main.c:1057
Inline: True
Inline callers:
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
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811f54c9)
Location: kernel/module/main.c:1057
Inline: True
Inline callers:
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
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101c4b28)
Location: kernel/module.c:2567
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:resolve_symbol
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (c040bc40)
Location: kernel/module.c:2567
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:resolve_symbol
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (c00000000022bce0)
Location: kernel/module.c:2567
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:resolve_symbol
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe000145478)
Location: kernel/module.c:2567
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:resolve_symbol
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114dd3a)
Location: kernel/module.c:2567
Inline: True
Inline callers:
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
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81140fea)
Location: kernel/module.c:2567
Inline: True
Inline callers:
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
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114bbea)
Location: kernel/module.c:2567
Inline: True
Inline callers:
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
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811588d5)
Location: kernel/module.c:2567
Inline: True
Inline callers:
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
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
