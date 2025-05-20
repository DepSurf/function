# Function: <code>free_notes_attrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_notes_attrs(struct module_notes_attrs *notes_attrs, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811051c0)
Location: kernel/module.c:1552
Inline: False
Direct callers:
  - kernel/module.c:free_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff811051c0-ffffffff81105218: free_notes_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_notes_attrs(struct module_notes_attrs *notes_attrs, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110caa0)
Location: kernel/module.c:1557
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:mod_sysfs_teardown
```
**Symbols:**

```
ffffffff8110caa0-ffffffff8110caf3: free_notes_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_notes_attrs(struct module_notes_attrs *notes_attrs, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811144e0)
Location: kernel/module.c:1549
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:mod_sysfs_teardown
```
**Symbols:**

```
ffffffff811144e0-ffffffff81114533: free_notes_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_notes_attrs(struct module_notes_attrs *notes_attrs, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81115680)
Location: kernel/module.c:1566
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:mod_sysfs_teardown
```
**Symbols:**

```
ffffffff81115680-ffffffff811156de: free_notes_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_notes_attrs(struct module_notes_attrs *notes_attrs, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81120c30)
Location: kernel/module.c:1574
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:mod_sysfs_teardown
```
**Symbols:**

```
ffffffff81120c30-ffffffff81120c8e: free_notes_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_notes_attrs(struct module_notes_attrs *notes_attrs, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8112e560)
Location: kernel/module.c:1574
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff8112e560-ffffffff8112e5be: free_notes_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_notes_attrs(struct module_notes_attrs *notes_attrs, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81139e60)
Location: kernel/module.c:1575
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff81139e60-ffffffff81139ebe: free_notes_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_notes_attrs(struct module_notes_attrs *notes_attrs, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81145590)
Location: kernel/module.c:1570
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff81145590-ffffffff811455ee: free_notes_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_notes_attrs(struct module_notes_attrs *notes_attrs, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811510a0)
Location: kernel/module.c:1625
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff811510a0-ffffffff811510fe: free_notes_attrs (STB_LOCAL)
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
In kernel/module.c (ffffffff81163fa8)
Location: kernel/module.c:1647
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:add_notes_attrs
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
In kernel/module.c (ffffffff8115f7b8)
Location: kernel/module.c:1708
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:add_notes_attrs
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
In kernel/module.c (ffffffff81160e98)
Location: kernel/module.c:1618
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:add_notes_attrs
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
In kernel/module.c (ffffffff81186068)
Location: kernel/module.c:1620
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:add_notes_attrs
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
In kernel/module/sysfs.c (ffffffff81192ba8)
Location: kernel/module/sysfs.c:160
Inline: True
Inline callers:
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:add_notes_attrs
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
In kernel/module/sysfs.c (ffffffff811d0358)
Location: kernel/module/sysfs.c:160
Inline: True
Inline callers:
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:add_notes_attrs
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
In kernel/module/sysfs.c (ffffffff811e4558)
Location: kernel/module/sysfs.c:160
Inline: True
Inline callers:
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:add_notes_attrs
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
In kernel/module/sysfs.c (ffffffff811fa2a8)
Location: kernel/module/sysfs.c:160
Inline: True
Inline callers:
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:add_notes_attrs
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
void free_notes_attrs(struct module_notes_attrs *notes_attrs, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101bff48)
Location: kernel/module.c:1625
Inline: False
Direct callers:
  - kernel/module.c:free_module
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffff8000101bff48-ffff8000101bffbc: free_notes_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_notes_attrs(struct module_notes_attrs *notes_attrs, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c0407678)
Location: kernel/module.c:1625
Inline: False
Direct callers:
  - kernel/module.c:free_module
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
c0407678-c04076dc: free_notes_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_notes_attrs(struct module_notes_attrs *notes_attrs, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c000000000225b40)
Location: kernel/module.c:1625
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
c000000000225b40-c000000000225bec: free_notes_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_notes_attrs(struct module_notes_attrs *notes_attrs, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe000142380)
Location: kernel/module.c:1625
Inline: False
Direct callers:
  - kernel/module.c:free_module
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffe000142380-ffffffe0001423f6: free_notes_attrs (STB_LOCAL)
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
void free_notes_attrs(struct module_notes_attrs *notes_attrs, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811496c0)
Location: kernel/module.c:1625
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff811496c0-ffffffff8114971e: free_notes_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_notes_attrs(struct module_notes_attrs *notes_attrs, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113c970)
Location: kernel/module.c:1625
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff8113c970-ffffffff8113c9ce: free_notes_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_notes_attrs(struct module_notes_attrs *notes_attrs, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81147570)
Location: kernel/module.c:1625
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff81147570-ffffffff811475ce: free_notes_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_notes_attrs(struct module_notes_attrs *notes_attrs, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81154180)
Location: kernel/module.c:1625
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff81154180-ffffffff811541de: free_notes_attrs (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
