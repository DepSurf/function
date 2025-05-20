# Function: <code>mod_kobject_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mod_kobject_put(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81105220)
Location: kernel/module.c:1720
Inline: False
Direct callers:
  - kernel/module.c:free_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81105220-ffffffff8110528b: mod_kobject_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mod_kobject_put(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110cb00)
Location: kernel/module.c:1724
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:mod_sysfs_teardown
```
**Symbols:**

```
ffffffff8110cb00-ffffffff8110cb6b: mod_kobject_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mod_kobject_put(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81114540)
Location: kernel/module.c:1716
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:mod_sysfs_teardown
```
**Symbols:**

```
ffffffff81114540-ffffffff811145ab: mod_kobject_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mod_kobject_put(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811156e0)
Location: kernel/module.c:1738
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:mod_sysfs_teardown
```
**Symbols:**

```
ffffffff811156e0-ffffffff8111574b: mod_kobject_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mod_kobject_put(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81120c90)
Location: kernel/module.c:1746
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:mod_sysfs_teardown
```
**Symbols:**

```
ffffffff81120c90-ffffffff81120cfb: mod_kobject_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mod_kobject_put(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8112e5c0)
Location: kernel/module.c:1745
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff8112e5c0-ffffffff8112e62b: mod_kobject_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mod_kobject_put(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81139ec0)
Location: kernel/module.c:1746
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff81139ec0-ffffffff81139f2b: mod_kobject_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mod_kobject_put(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811455f0)
Location: kernel/module.c:1753
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff811455f0-ffffffff8114565d: mod_kobject_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mod_kobject_put(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81151100)
Location: kernel/module.c:1810
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff81151100-ffffffff8115116d: mod_kobject_put (STB_LOCAL)
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
In kernel/module.c (ffffffff8116404b)
Location: kernel/module.c:1832
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_init
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
In kernel/module.c (ffffffff8115f85b)
Location: kernel/module.c:1893
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_init
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
In kernel/module.c (ffffffff81160f34)
Location: kernel/module.c:1803
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
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
In kernel/module.c (ffffffff81186104)
Location: kernel/module.c:1805
Inline: True
Inline callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
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
In kernel/module/sysfs.c (ffffffff81192c44)
Location: kernel/module/sysfs.c:329
Inline: True
Inline callers:
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_setup
  - kernel/module/sysfs.c:mod_sysfs_setup
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
In kernel/module/sysfs.c (ffffffff811d03f4)
Location: kernel/module/sysfs.c:329
Inline: True
Inline callers:
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_setup
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
In kernel/module/sysfs.c (ffffffff811e45f4)
Location: kernel/module/sysfs.c:329
Inline: True
Inline callers:
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_setup
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
In kernel/module/sysfs.c (ffffffff811fa348)
Location: kernel/module/sysfs.c:329
Inline: True
Inline callers:
  - kernel/module/sysfs.c:mod_sysfs_teardown
  - kernel/module/sysfs.c:mod_sysfs_setup
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
void mod_kobject_put(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101bffc0)
Location: kernel/module.c:1810
Inline: False
Direct callers:
  - kernel/module.c:free_module
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffff8000101bffc0-ffff8000101c0038: mod_kobject_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mod_kobject_put(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c04076dc)
Location: kernel/module.c:1810
Inline: False
Direct callers:
  - kernel/module.c:free_module
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
c04076dc-c040775c: mod_kobject_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mod_kobject_put(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c000000000225bf0)
Location: kernel/module.c:1810
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
c000000000225bf0-c000000000225c88: mod_kobject_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mod_kobject_put(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe0001423f6)
Location: kernel/module.c:1810
Inline: False
Direct callers:
  - kernel/module.c:free_module
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffe0001423f6-ffffffe00014244c: mod_kobject_put (STB_LOCAL)
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
void mod_kobject_put(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81149720)
Location: kernel/module.c:1810
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff81149720-ffffffff8114978d: mod_kobject_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mod_kobject_put(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113c9d0)
Location: kernel/module.c:1810
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff8113c9d0-ffffffff8113ca3d: mod_kobject_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mod_kobject_put(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811475d0)
Location: kernel/module.c:1810
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff811475d0-ffffffff8114763d: mod_kobject_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mod_kobject_put(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811541e0)
Location: kernel/module.c:1810
Inline: False
Direct callers:
  - kernel/module.c:mod_sysfs_teardown
  - kernel/module.c:mod_sysfs_setup
  - kernel/module.c:mod_sysfs_setup
```
**Symbols:**

```
ffffffff811541e0-ffffffff8115424d: mod_kobject_put (STB_LOCAL)
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
