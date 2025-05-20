# Function: <code>module_add_modinfo_attrs</code>

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
In kernel/module.c (ffffffff81109602)
Location: kernel/module.c:1677
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
In kernel/module.c (ffffffff81111232)
Location: kernel/module.c:1682
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
In kernel/module.c (ffffffff81118abc)
Location: kernel/module.c:1674
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
In kernel/module.c (ffffffff8111a001)
Location: kernel/module.c:1696
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
In kernel/module.c (ffffffff811255b5)
Location: kernel/module.c:1704
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
In kernel/module.c (ffffffff8113071e)
Location: kernel/module.c:1703
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
In kernel/module.c (ffffffff8113bfca)
Location: kernel/module.c:1704
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
In kernel/module.c (ffffffff8114760a)
Location: kernel/module.c:1701
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
In kernel/module.c (ffffffff8115342a)
Location: kernel/module.c:1756
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
int module_add_modinfo_attrs(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81164770)
Location: kernel/module.c:1778
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff81164770-ffffffff8116489f: module_add_modinfo_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int module_add_modinfo_attrs(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81160aa0)
Location: kernel/module.c:1839
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff81160aa0-ffffffff81160bcf: module_add_modinfo_attrs (STB_LOCAL)
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
In kernel/module.c (ffffffff81161a0f)
Location: kernel/module.c:1749
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
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
In kernel/module.c (ffffffff81186bdf)
Location: kernel/module.c:1751
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int module_add_modinfo_attrs(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/sysfs.c (ffffffff811924f0)
Location: kernel/module/sysfs.c:293
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff811924f0-ffffffff8119264b: module_add_modinfo_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int module_add_modinfo_attrs(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/sysfs.c (ffffffff811cfe50)
Location: kernel/module/sysfs.c:293
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff811cfe50-ffffffff811cffab: module_add_modinfo_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int module_add_modinfo_attrs(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/sysfs.c (ffffffff811e3ff0)
Location: kernel/module/sysfs.c:293
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff811e3ff0-ffffffff811e41ad: module_add_modinfo_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int module_add_modinfo_attrs(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/sysfs.c (ffffffff811f9d40)
Location: kernel/module/sysfs.c:293
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff811f9d40-ffffffff811f9efd: module_add_modinfo_attrs (STB_LOCAL)
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
In kernel/module.c (ffff8000101c1d14)
Location: kernel/module.c:1756
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
In kernel/module.c (c0409930)
Location: kernel/module.c:1756
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
In kernel/module.c (c000000000228db0)
Location: kernel/module.c:1756
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
In kernel/module.c (ffffffe000143a62)
Location: kernel/module.c:1756
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
In kernel/module.c (ffffffff8114ba4a)
Location: kernel/module.c:1756
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
In kernel/module.c (ffffffff8113ecfa)
Location: kernel/module.c:1756
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
In kernel/module.c (ffffffff811498fa)
Location: kernel/module.c:1756
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
In kernel/module.c (ffffffff811565ba)
Location: kernel/module.c:1756
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
