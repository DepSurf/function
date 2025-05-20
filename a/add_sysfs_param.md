# Function: <code>add_sysfs_param</code>

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
In kernel/params.c (ffffffff8109f760)
Location: kernel/params.c:662
Inline: True
Direct callers:
  - kernel/params.c:module_param_sysfs_setup
```
**Symbols:**

```
ffffffff8109f760-ffffffff8109f93d: add_sysfs_param.isra.7 (STB_LOCAL)
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
In kernel/params.c (ffffffff810a2e10)
Location: kernel/params.c:662
Inline: True
Direct callers:
  - kernel/params.c:module_param_sysfs_setup
```
**Symbols:**

```
ffffffff810a2e10-ffffffff810a2fed: add_sysfs_param.isra.6 (STB_LOCAL)
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
In kernel/params.c (ffffffff810a7cc0)
Location: kernel/params.c:662
Inline: True
Direct callers:
  - kernel/params.c:module_param_sysfs_setup
```
**Symbols:**

```
ffffffff810a7cc0-ffffffff810a7e9d: add_sysfs_param.isra.8 (STB_LOCAL)
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
In kernel/params.c (ffffffff810a4c60)
Location: kernel/params.c:610
Inline: True
Direct callers:
  - kernel/params.c:module_param_sysfs_setup
```
**Symbols:**

```
ffffffff810a4c60-ffffffff810a4e3d: add_sysfs_param.isra.8 (STB_LOCAL)
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
In kernel/params.c (ffffffff810ab3e0)
Location: kernel/params.c:623
Inline: True
Direct callers:
  - kernel/params.c:module_param_sysfs_setup
```
**Symbols:**

```
ffffffff810ab3e0-ffffffff810ab5bd: add_sysfs_param.isra.8 (STB_LOCAL)
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
In kernel/params.c (ffffffff810b1eb0)
Location: kernel/params.c:623
Inline: True
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_setup
```
**Symbols:**

```
ffffffff810b1eb0-ffffffff810b208d: add_sysfs_param.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/params.c (ffffffff810bafd0)
Location: kernel/params.c:623
Inline: True
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_setup
```
**Symbols:**

```
ffffffff810bafd0-ffffffff810bb1ad: add_sysfs_param.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/params.c (ffffffff810c0ef0)
Location: kernel/params.c:611
Inline: True
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_setup
```
**Symbols:**

```
ffffffff810c0ef0-ffffffff810c10c0: add_sysfs_param.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/params.c (ffffffff810c72e0)
Location: kernel/params.c:606
Inline: True
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_setup
```
**Symbols:**

```
ffffffff810c72e0-ffffffff810c74b0: add_sysfs_param.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int add_sysfs_param(struct module_kobject *mk, const struct kernel_param *kp, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810cf2f0)
Location: kernel/params.c:606
Inline: False
Direct callers:
  - kernel/params.c:kernel_add_sysfs_param
  - kernel/params.c:module_param_sysfs_setup
```
**Symbols:**

```
ffffffff810cf2f0-ffffffff810cf4ce: add_sysfs_param (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int add_sysfs_param(struct module_kobject *mk, const struct kernel_param *kp, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810c9e20)
Location: kernel/params.c:607
Inline: False
Direct callers:
  - kernel/params.c:kernel_add_sysfs_param
  - kernel/params.c:module_param_sysfs_setup
```
**Symbols:**

```
ffffffff810c9e20-ffffffff810c9ffe: add_sysfs_param (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int add_sysfs_param(struct module_kobject *mk, const struct kernel_param *kp, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810cb7b0)
Location: kernel/params.c:607
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_builtin
  - kernel/params.c:module_param_sysfs_setup
```
**Symbols:**

```
ffffffff810cb7b0-ffffffff810cb98e: add_sysfs_param (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int add_sysfs_param(struct module_kobject *mk, const struct kernel_param *kp, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810de9b0)
Location: kernel/params.c:625
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_builtin
  - kernel/params.c:module_param_sysfs_setup
```
**Symbols:**

```
ffffffff810de9b0-ffffffff810deb8e: add_sysfs_param (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int add_sysfs_param(struct module_kobject *mk, const struct kernel_param *kp, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810f8a30)
Location: kernel/params.c:625
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_builtin
  - kernel/params.c:module_param_sysfs_setup
```
**Symbols:**

```
ffffffff810f8a30-ffffffff810f8c1d: add_sysfs_param (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int add_sysfs_param(struct module_kobject *mk, const struct kernel_param *kp, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff8111b550)
Location: kernel/params.c:625
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_builtin
  - kernel/params.c:module_param_sysfs_setup
```
**Symbols:**

```
ffffffff8111b550-ffffffff8111b73d: add_sysfs_param (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int add_sysfs_param(struct module_kobject *mk, const struct kernel_param *kp, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff811287a0)
Location: kernel/params.c:626
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_builtin
  - kernel/params.c:module_param_sysfs_setup
```
**Symbols:**

```
ffffffff811287a0-ffffffff8112898c: add_sysfs_param (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int add_sysfs_param(struct module_kobject *mk, const struct kernel_param *kp, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff81132dc0)
Location: kernel/params.c:628
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_builtin
  - kernel/params.c:module_param_sysfs_setup
```
**Symbols:**

```
ffffffff81132dc0-ffffffff8113300a: add_sysfs_param (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/params.c (ffff800010126328)
Location: kernel/params.c:606
Inline: True
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_setup
```
**Symbols:**

```
ffff800010126328-ffff80001012652c: add_sysfs_param.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int add_sysfs_param(struct module_kobject *mk, const struct kernel_param *kp, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (c0378bf4)
Location: kernel/params.c:606
Inline: False
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_setup
```
**Symbols:**

```
c0378bf4-c0378dd8: add_sysfs_param (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/params.c (c000000000170a90)
Location: kernel/params.c:606
Inline: True
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_setup
```
**Symbols:**

```
c000000000170a90-c000000000170d48: add_sysfs_param.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/params.c (ffffffe0000dddfe)
Location: kernel/params.c:606
Inline: True
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_setup
```
**Symbols:**

```
ffffffe0000dddfe-ffffffe0000ddfac: add_sysfs_param.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/params.c (ffffffff810c1660)
Location: kernel/params.c:606
Inline: True
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_setup
```
**Symbols:**

```
ffffffff810c1660-ffffffff810c1830: add_sysfs_param.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/params.c (ffffffff810afe50)
Location: kernel/params.c:606
Inline: True
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_setup
```
**Symbols:**

```
ffffffff810afe50-ffffffff810b0020: add_sysfs_param.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/params.c (ffffffff810c0bb0)
Location: kernel/params.c:606
Inline: True
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_setup
```
**Symbols:**

```
ffffffff810c0bb0-ffffffff810c0d80: add_sysfs_param.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/params.c (ffffffff810c9160)
Location: kernel/params.c:606
Inline: True
Direct callers:
  - kernel/params.c:param_sysfs_init
  - kernel/params.c:module_param_sysfs_setup
```
**Symbols:**

```
ffffffff810c9160-ffffffff810c9330: add_sysfs_param.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
