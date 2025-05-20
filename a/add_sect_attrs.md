# Function: <code>add_sect_attrs</code>

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
In kernel/module.c (ffffffff81109e59)
Location: kernel/module.c:1465
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff81111369)
Location: kernel/module.c:1470
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff81118eae)
Location: kernel/module.c:1462
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8111a6fe)
Location: kernel/module.c:1479
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81125b34)
Location: kernel/module.c:1487
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1487
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1488
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1484
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
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
In kernel/module.c (0)
Location: kernel/module.c:1539
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void add_sect_attrs(struct module *mod, const struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81164bb0)
Location: kernel/module.c:1562
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff81164bb0-ffffffff81164d4c: add_sect_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void add_sect_attrs(struct module *mod, const struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81161260)
Location: kernel/module.c:1621
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff81161260-ffffffff811613f7: add_sect_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void add_sect_attrs(struct module *mod, const struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811616d0)
Location: kernel/module.c:1531
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff811616d0-ffffffff81161869: add_sect_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void add_sect_attrs(struct module *mod, const struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811868a0)
Location: kernel/module.c:1533
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff811868a0-ffffffff81186a39: add_sect_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void add_sect_attrs(struct module *mod, const struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/sysfs.c (ffffffff81192650)
Location: kernel/module/sysfs.c:72
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff81192650-ffffffff81192803: add_sect_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void add_sect_attrs(struct module *mod, const struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/sysfs.c (ffffffff811cfc80)
Location: kernel/module/sysfs.c:72
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff811cfc80-ffffffff811cfe33: add_sect_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void add_sect_attrs(struct module *mod, const struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/sysfs.c (ffffffff811e3e20)
Location: kernel/module/sysfs.c:72
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff811e3e20-ffffffff811e3fd3: add_sect_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void add_sect_attrs(struct module *mod, const struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/sysfs.c (ffffffff811f9b70)
Location: kernel/module/sysfs.c:72
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff811f9b70-ffffffff811f9d2a: add_sect_attrs (STB_LOCAL)
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
In kernel/module.c (0)
Location: kernel/module.c:1539
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
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
In kernel/module.c (0)
Location: kernel/module.c:1539
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
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
In kernel/module.c (0)
Location: kernel/module.c:1539
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
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
In kernel/module.c (ffffffe000143b80)
Location: kernel/module.c:1539
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
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
In kernel/module.c (0)
Location: kernel/module.c:1539
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
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
In kernel/module.c (0)
Location: kernel/module.c:1539
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
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
In kernel/module.c (0)
Location: kernel/module.c:1539
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
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
In kernel/module.c (0)
Location: kernel/module.c:1539
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
</details>
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
