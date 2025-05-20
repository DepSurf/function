# Function: <code>add_notes_attrs</code>

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
In kernel/module.c (ffffffff81109dcd)
Location: kernel/module.c:1564
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
In kernel/module.c (ffffffff8111144f)
Location: kernel/module.c:1569
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
In kernel/module.c (ffffffff81118f6a)
Location: kernel/module.c:1561
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
In kernel/module.c (ffffffff8111a7c6)
Location: kernel/module.c:1578
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
In kernel/module.c (ffffffff81125bfa)
Location: kernel/module.c:1586
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
In kernel/module.c (ffffffff81130a18)
Location: kernel/module.c:1586
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
In kernel/module.c (ffffffff8113c2e0)
Location: kernel/module.c:1587
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
In kernel/module.c (ffffffff811478f8)
Location: kernel/module.c:1582
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
In kernel/module.c (ffffffff81153733)
Location: kernel/module.c:1637
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
void add_notes_attrs(struct module *mod, const struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81161f40)
Location: kernel/module.c:1659
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff81161f40-ffffffff81162107: add_notes_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void add_notes_attrs(struct module *mod, const struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115e130)
Location: kernel/module.c:1720
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff8115e130-ffffffff8115e2f7: add_notes_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void add_notes_attrs(struct module *mod, const struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115f160)
Location: kernel/module.c:1630
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff8115f160-ffffffff8115f31b: add_notes_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void add_notes_attrs(struct module *mod, const struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811844c0)
Location: kernel/module.c:1632
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff811844c0-ffffffff8118467b: add_notes_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void add_notes_attrs(struct module *mod, const struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/sysfs.c (ffffffff811922e0)
Location: kernel/module/sysfs.c:172
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff811922e0-ffffffff811924e3: add_notes_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void add_notes_attrs(struct module *mod, const struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/sysfs.c (ffffffff811cfa60)
Location: kernel/module/sysfs.c:172
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff811cfa60-ffffffff811cfc63: add_notes_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void add_notes_attrs(struct module *mod, const struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/sysfs.c (ffffffff811e3c00)
Location: kernel/module/sysfs.c:172
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff811e3c00-ffffffff811e3e03: add_notes_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void add_notes_attrs(struct module *mod, const struct load_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/sysfs.c (ffffffff811f9960)
Location: kernel/module/sysfs.c:172
Inline: False
Direct callers:
  - kernel/module/sysfs.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff811f9960-ffffffff811f9b53: add_notes_attrs (STB_LOCAL)
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
In kernel/module.c (ffff8000101c1fc0)
Location: kernel/module.c:1637
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
In kernel/module.c (c0409e70)
Location: kernel/module.c:1637
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
In kernel/module.c (c000000000229144)
Location: kernel/module.c:1637
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
In kernel/module.c (ffffffe000143cbe)
Location: kernel/module.c:1637
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
In kernel/module.c (ffffffff8114bd53)
Location: kernel/module.c:1637
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
In kernel/module.c (ffffffff8113f003)
Location: kernel/module.c:1637
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
In kernel/module.c (ffffffff81149c03)
Location: kernel/module.c:1637
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
In kernel/module.c (ffffffff811568c3)
Location: kernel/module.c:1637
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
