# Function: <code>module_remove_modinfo_attrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81107630)
Location: kernel/module.c:1704
Inline: True
Inline callers:
  - kernel/module.c:free_module
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110e206)
Location: kernel/module.c:1708
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_teardown
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81115be6)
Location: kernel/module.c:1700
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_teardown
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void module_remove_modinfo_attrs(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811155f0)
Location: kernel/module.c:1722
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:mod_sysfs_teardown
```
**Symbols:**

```
ffffffff811155f0-ffffffff81115678: module_remove_modinfo_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void module_remove_modinfo_attrs(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81120ba0)
Location: kernel/module.c:1730
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:mod_sysfs_teardown
```
**Symbols:**

```
ffffffff81120ba0-ffffffff81120c2b: module_remove_modinfo_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void module_remove_modinfo_attrs(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8112e4d0)
Location: kernel/module.c:1729
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff8112e4d0-ffffffff8112e55b: module_remove_modinfo_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void module_remove_modinfo_attrs(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81139dd0)
Location: kernel/module.c:1730
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff81139dd0-ffffffff81139e5b: module_remove_modinfo_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void module_remove_modinfo_attrs(struct module *mod, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811454e0)
Location: kernel/module.c:1735
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff811454e0-ffffffff81145587: module_remove_modinfo_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void module_remove_modinfo_attrs(struct module *mod, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81150ff0)
Location: kernel/module.c:1792
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff81150ff0-ffffffff81151097: module_remove_modinfo_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void module_remove_modinfo_attrs(struct module *mod, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81161550)
Location: kernel/module.c:1814
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:module_add_modinfo_attrs
```
**Symbols:**

```
ffffffff81161550-ffffffff811615f7: module_remove_modinfo_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void module_remove_modinfo_attrs(struct module *mod, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115d360)
Location: kernel/module.c:1875
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:module_add_modinfo_attrs
```
**Symbols:**

```
ffffffff8115d360-ffffffff8115d407: module_remove_modinfo_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void module_remove_modinfo_attrs(struct module *mod, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115e450)
Location: kernel/module.c:1785
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff8115e450-ffffffff8115e4f7: module_remove_modinfo_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void module_remove_modinfo_attrs(struct module *mod, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81183690)
Location: kernel/module.c:1787
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff81183690-ffffffff81183737: module_remove_modinfo_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void module_remove_modinfo_attrs(struct module *mod, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/sysfs.c (ffffffff81192140)
Location: kernel/module/sysfs.c:275
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_setup
  - kernel/module/sysfs.c:module_add_modinfo_attrs
```
**Symbols:**

```
ffffffff81192140-ffffffff811921f5: module_remove_modinfo_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void module_remove_modinfo_attrs(struct module *mod, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/sysfs.c (ffffffff811cf850)
Location: kernel/module/sysfs.c:275
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_setup
  - kernel/module/sysfs.c:module_add_modinfo_attrs
```
**Symbols:**

```
ffffffff811cf850-ffffffff811cf905: module_remove_modinfo_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void module_remove_modinfo_attrs(struct module *mod, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/sysfs.c (ffffffff811e39f0)
Location: kernel/module/sysfs.c:275
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_setup
  - kernel/module/sysfs.c:module_add_modinfo_attrs
```
**Symbols:**

```
ffffffff811e39f0-ffffffff811e3aa5: module_remove_modinfo_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void module_remove_modinfo_attrs(struct module *mod, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/sysfs.c (ffffffff811f9750)
Location: kernel/module/sysfs.c:275
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_setup
  - kernel/module/sysfs.c:module_add_modinfo_attrs
```
**Symbols:**

```
ffffffff811f9750-ffffffff811f9805: module_remove_modinfo_attrs (STB_LOCAL)
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
void module_remove_modinfo_attrs(struct module *mod, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101bfe98)
Location: kernel/module.c:1792
Inline: False
Direct callers:
  - kernel/module.c:free_module
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffff8000101bfe98-ffff8000101bff48: module_remove_modinfo_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void module_remove_modinfo_attrs(struct module *mod, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c04075d4)
Location: kernel/module.c:1792
Inline: False
Direct callers:
  - kernel/module.c:free_module
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
c04075d4-c0407678: module_remove_modinfo_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void module_remove_modinfo_attrs(struct module *mod, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c000000000225a30)
Location: kernel/module.c:1792
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
c000000000225a30-c000000000225b3c: module_remove_modinfo_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void module_remove_modinfo_attrs(struct module *mod, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe0001422f8)
Location: kernel/module.c:1792
Inline: False
Direct callers:
  - kernel/module.c:free_module
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffe0001422f8-ffffffe000142380: module_remove_modinfo_attrs (STB_LOCAL)
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
void module_remove_modinfo_attrs(struct module *mod, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81149610)
Location: kernel/module.c:1792
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff81149610-ffffffff811496b7: module_remove_modinfo_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void module_remove_modinfo_attrs(struct module *mod, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113c8c0)
Location: kernel/module.c:1792
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff8113c8c0-ffffffff8113c967: module_remove_modinfo_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void module_remove_modinfo_attrs(struct module *mod, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811474c0)
Location: kernel/module.c:1792
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff811474c0-ffffffff81147567: module_remove_modinfo_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void module_remove_modinfo_attrs(struct module *mod, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811540d0)
Location: kernel/module.c:1792
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff811540d0-ffffffff81154177: module_remove_modinfo_attrs (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int end</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
