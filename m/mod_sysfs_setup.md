# Function: <code>mod_sysfs_setup</code>

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
In kernel/module.c (ffffffff8110952b)
Location: kernel/module.c:1761
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
In kernel/module.c (ffffffff8111114d)
Location: kernel/module.c:1765
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
In kernel/module.c (ffffffff81118264)
Location: kernel/module.c:1757
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
In kernel/module.c (ffffffff81119f37)
Location: kernel/module.c:1779
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
In kernel/module.c (ffffffff811254eb)
Location: kernel/module.c:1787
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int mod_sysfs_setup(struct module *mod, const struct load_info *info, struct kernel_param *kparam, unsigned int num_params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1786
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81130600-ffffffff81130c01: mod_sysfs_setup (STB_LOCAL)
ffffffff8113462d-ffffffff8113466b: mod_sysfs_setup.cold.72 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int mod_sysfs_setup(struct module *mod, const struct load_info *info, struct kernel_param *kparam, unsigned int num_params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1787
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8113beb0-ffffffff8113c4bf: mod_sysfs_setup (STB_LOCAL)
ffffffff8113fe0f-ffffffff8113fe4b: mod_sysfs_setup.cold.75 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mod_sysfs_setup(struct module *mod, const struct load_info *info, struct kernel_param *kparam, unsigned int num_params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1794
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff811474f0-ffffffff81147b10: mod_sysfs_setup (STB_LOCAL)
ffffffff8114b176-ffffffff8114b1b2: mod_sysfs_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mod_sysfs_setup(struct module *mod, const struct load_info *info, struct kernel_param *kparam, unsigned int num_params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1851
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81153310-ffffffff8115394c: mod_sysfs_setup (STB_LOCAL)
ffffffff81156eb9-ffffffff81156ef5: mod_sysfs_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mod_sysfs_setup(struct module *mod, const struct load_info *info, struct kernel_param *kparam, unsigned int num_params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81164d50)
Location: kernel/module.c:1873
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81164d50-ffffffff81164f73: mod_sysfs_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mod_sysfs_setup(struct module *mod, const struct load_info *info, struct kernel_param *kparam, unsigned int num_params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81161400)
Location: kernel/module.c:1933
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81161400-ffffffff81161619: mod_sysfs_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mod_sysfs_setup(struct module *mod, const struct load_info *info, struct kernel_param *kparam, unsigned int num_params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1843
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81161870-ffffffff81161c18: mod_sysfs_setup (STB_LOCAL)
ffffffff81bd5ff9-ffffffff81bd6037: mod_sysfs_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mod_sysfs_setup(struct module *mod, const struct load_info *info, struct kernel_param *kparam, unsigned int num_params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1845
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81186a40-ffffffff81186e07: mod_sysfs_setup (STB_LOCAL)
ffffffff81cb2724-ffffffff81cb2762: mod_sysfs_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mod_sysfs_setup(struct module *mod, const struct load_info *info, struct kernel_param *kparam, unsigned int num_params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/sysfs.c (0)
Location: kernel/module/sysfs.c:370
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff81e61c67-ffffffff81e61c99: mod_sysfs_setup.cold (STB_LOCAL)
ffffffff81192810-ffffffff81192ae3: mod_sysfs_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mod_sysfs_setup(struct module *mod, const struct load_info *info, struct kernel_param *kparam, unsigned int num_params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/sysfs.c (ffffffff811cffc0)
Location: kernel/module/sysfs.c:370
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff811cffc0-ffffffff811d0283: mod_sysfs_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mod_sysfs_setup(struct module *mod, const struct load_info *info, struct kernel_param *kparam, unsigned int num_params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/sysfs.c (ffffffff811e41c0)
Location: kernel/module/sysfs.c:370
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff811e41c0-ffffffff811e4484: mod_sysfs_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mod_sysfs_setup(struct module *mod, const struct load_info *info, struct kernel_param *kparam, unsigned int num_params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/sysfs.c (ffffffff811f9f10)
Location: kernel/module/sysfs.c:370
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff811f9f10-ffffffff811fa1d4: mod_sysfs_setup (STB_GLOBAL)
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
int mod_sysfs_setup(struct module *mod, const struct load_info *info, struct kernel_param *kparam, unsigned int num_params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101c1c18)
Location: kernel/module.c:1851
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffff8000101c1c18-ffff8000101c21e4: mod_sysfs_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mod_sysfs_setup(struct module *mod, const struct load_info *info, struct kernel_param *kparam, unsigned int num_params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c040983c)
Location: kernel/module.c:1851
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
c040983c-c0409ee8: mod_sysfs_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mod_sysfs_setup(struct module *mod, const struct load_info *info, struct kernel_param *kparam, unsigned int num_params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c000000000228c40)
Location: kernel/module.c:1851
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
c000000000228c40-c0000000002293e8: mod_sysfs_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mod_sysfs_setup(struct module *mod, const struct load_info *info, struct kernel_param *kparam, unsigned int num_params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe00014396a)
Location: kernel/module.c:1851
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffe00014396a-ffffffe000143e94: mod_sysfs_setup (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int mod_sysfs_setup(struct module *mod, const struct load_info *info, struct kernel_param *kparam, unsigned int num_params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1851
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8114b930-ffffffff8114bf6c: mod_sysfs_setup (STB_LOCAL)
ffffffff8114f4d9-ffffffff8114f515: mod_sysfs_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int mod_sysfs_setup(struct module *mod, const struct load_info *info, struct kernel_param *kparam, unsigned int num_params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1851
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8113ebe0-ffffffff8113f21c: mod_sysfs_setup (STB_LOCAL)
ffffffff81142789-ffffffff811427c5: mod_sysfs_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int mod_sysfs_setup(struct module *mod, const struct load_info *info, struct kernel_param *kparam, unsigned int num_params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1851
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff811497e0-ffffffff81149e1c: mod_sysfs_setup (STB_LOCAL)
ffffffff8114d389-ffffffff8114d3c5: mod_sysfs_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mod_sysfs_setup(struct module *mod, const struct load_info *info, struct kernel_param *kparam, unsigned int num_params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1851
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff811564a0-ffffffff81156adc: mod_sysfs_setup (STB_LOCAL)
ffffffff8115a150-ffffffff8115a18c: mod_sysfs_setup.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
