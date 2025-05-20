# Function: <code>parse_args</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *parse_args(const char *doing, char *args, const struct kernel_param *params, unsigned int num, s16 min_level, s16 max_level, void *arg, int (*unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff8109fa10)
Location: kernel/params.c:216
Inline: False
Direct callers:
  - init/main.c:parse_early_options
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:kernel_init_freeable
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff8109fa10-ffffffff8109feb1: parse_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *parse_args(const char *doing, char *args, const struct kernel_param *params, unsigned int num, s16 min_level, s16 max_level, void *arg, int (*unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810a30c0)
Location: kernel/params.c:216
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:parse_early_options
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff810a30c0-ffffffff810a35af: parse_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *parse_args(const char *doing, char *args, const struct kernel_param *params, unsigned int num, s16 min_level, s16 max_level, void *arg, int (*unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810a8180)
Location: kernel/params.c:216
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:parse_early_options
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff810a8180-ffffffff810a866f: parse_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *parse_args(const char *doing, char *args, const struct kernel_param *params, unsigned int num, s16 min_level, s16 max_level, void *arg, int (*unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810a5120)
Location: kernel/params.c:164
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:parse_early_options
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff810a5120-ffffffff810a54e0: parse_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *parse_args(const char *doing, char *args, const struct kernel_param *params, unsigned int num, s16 min_level, s16 max_level, void *arg, int (*unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810ab7e0)
Location: kernel/params.c:172
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:parse_early_options
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff810ab7e0-ffffffff810abbaf: parse_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
char *parse_args(const char *doing, char *args, const struct kernel_param *params, unsigned int num, s16 min_level, s16 max_level, void *arg, int (*unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:172
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:parse_early_options
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff810b297f-ffffffff810b2a2c: parse_args.cold.18 (STB_LOCAL)
ffffffff810b2400-ffffffff810b2745: parse_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
char *parse_args(const char *doing, char *args, const struct kernel_param *params, unsigned int num, s16 min_level, s16 max_level, void *arg, int (*unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:172
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:parse_early_options
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff810bbaaf-ffffffff810bbb5c: parse_args.cold.17 (STB_LOCAL)
ffffffff810bb530-ffffffff810bb875: parse_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
char *parse_args(const char *doing, char *args, const struct kernel_param *params, unsigned int num, s16 min_level, s16 max_level, void *arg, int (*unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:160
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:parse_early_options
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff810c196d-ffffffff810c1a14: parse_args.cold (STB_LOCAL)
ffffffff810c1430-ffffffff810c174d: parse_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
char *parse_args(const char *doing, char *args, const struct kernel_param *params, unsigned int num, s16 min_level, s16 max_level, void *arg, int (*unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:161
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:parse_early_options
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff810c7d5d-ffffffff810c7e00: parse_args.cold (STB_LOCAL)
ffffffff810c7820-ffffffff810c7b40: parse_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
char *parse_args(const char *doing, char *args, const struct kernel_param *params, unsigned int num, s16 min_level, s16 max_level, void *arg, int (*unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:161
Inline: False
Direct callers:
  - init/main.c:do_initcalls
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:parse_early_options
  - kernel/module.c:load_module
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff810cfe3d-ffffffff810cfed3: parse_args.cold (STB_LOCAL)
ffffffff810cfa40-ffffffff810cfbce: parse_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
char *parse_args(const char *doing, char *args, const struct kernel_param *params, unsigned int num, s16 min_level, s16 max_level, void *arg, int (*unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:161
Inline: False
Direct callers:
  - init/main.c:do_initcalls
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:parse_early_options
  - kernel/module.c:load_module
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff81bdc20d-ffffffff81bdc2a3: parse_args.cold (STB_LOCAL)
ffffffff810ca590-ffffffff810ca71e: parse_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
char *parse_args(const char *doing, char *args, const struct kernel_param *params, unsigned int num, s16 min_level, s16 max_level, void *arg, int (*unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:161
Inline: False
Direct callers:
  - init/main.c:do_initcalls
  - init/main.c:setup_boot_config
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:parse_early_options
  - kernel/module.c:load_module
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff81bce330-ffffffff81bce3c6: parse_args.cold (STB_LOCAL)
ffffffff810cc050-ffffffff810cc1de: parse_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
char *parse_args(const char *doing, char *args, const struct kernel_param *params, unsigned int num, s16 min_level, s16 max_level, void *arg, int (*unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:161
Inline: False
Direct callers:
  - init/main.c:do_initcalls
  - init/main.c:setup_boot_config
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:parse_early_options
  - kernel/module.c:load_module
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff81ca566e-ffffffff81ca5704: parse_args.cold (STB_LOCAL)
ffffffff810df250-ffffffff810df3db: parse_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
char *parse_args(const char *doing, char *args, const struct kernel_param *params, unsigned int num, s16 min_level, s16 max_level, void *arg, int (*unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:161
Inline: False
Direct callers:
  - init/main.c:do_initcalls
  - init/main.c:setup_boot_config
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:parse_early_options
  - kernel/module/main.c:load_module
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff81e54f11-ffffffff81e54fa7: parse_args.cold (STB_LOCAL)
ffffffff810f90c0-ffffffff810f9267: parse_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *parse_args(const char *doing, char *args, const struct kernel_param *params, unsigned int num, s16 min_level, s16 max_level, void *arg, int (*unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff8111bc80)
Location: kernel/params.c:161
Inline: False
Direct callers:
  - init/main.c:do_initcalls
  - init/main.c:setup_boot_config
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:parse_early_param
  - kernel/module/main.c:load_module
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff8111bc80-ffffffff8111beac: parse_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *parse_args(const char *doing, char *args, const struct kernel_param *params, unsigned int num, s16 min_level, s16 max_level, void *arg, int (*unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff81128ed0)
Location: kernel/params.c:162
Inline: False
Direct callers:
  - init/main.c:do_initcalls
  - init/main.c:setup_boot_config
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:parse_early_param
  - kernel/module/main.c:load_module
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff81128ed0-ffffffff811290fc: parse_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *parse_args(const char *doing, char *args, const struct kernel_param *params, unsigned int num, s16 min_level, s16 max_level, void *arg, parse_unknown_fn unknown);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff81133550)
Location: kernel/params.c:161
Inline: False
Direct callers:
  - init/main.c:do_initcalls
  - init/main.c:setup_boot_config
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:parse_early_param
  - kernel/module/main.c:load_module
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff81133550-ffffffff8113377c: parse_args (STB_GLOBAL)
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
char *parse_args(const char *doing, char *args, const struct kernel_param *params, unsigned int num, s16 min_level, s16 max_level, void *arg, int (*unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffff800010126a80)
Location: kernel/params.c:161
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:parse_early_options
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffff800010126a80-ffff800010126e68: parse_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *parse_args(const char *doing, char *args, const struct kernel_param *params, unsigned int num, s16 min_level, s16 max_level, void *arg, int (*unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (c037942c)
Location: kernel/params.c:161
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:parse_early_options
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
c037942c-c037988c: parse_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *parse_args(const char *doing, char *args, const struct kernel_param *params, unsigned int num, s16 min_level, s16 max_level, void *arg, int (*unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (c000000000170ea0)
Location: kernel/params.c:161
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:parse_early_options
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
c000000000170ea0-c0000000001713e8: parse_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *parse_args(const char *doing, char *args, const struct kernel_param *params, unsigned int num, s16 min_level, s16 max_level, void *arg, int (*unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffe0000de3f4)
Location: kernel/params.c:161
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:parse_early_options
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffe0000de3f4-ffffffe0000de79e: parse_args (STB_GLOBAL)
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
char *parse_args(const char *doing, char *args, const struct kernel_param *params, unsigned int num, s16 min_level, s16 max_level, void *arg, int (*unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:161
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:parse_early_options
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff810c20dd-ffffffff810c2180: parse_args.cold (STB_LOCAL)
ffffffff810c1ba0-ffffffff810c1ec0: parse_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
char *parse_args(const char *doing, char *args, const struct kernel_param *params, unsigned int num, s16 min_level, s16 max_level, void *arg, int (*unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:161
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:parse_early_options
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff810b08fd-ffffffff810b09c8: parse_args.cold (STB_LOCAL)
ffffffff810b0390-ffffffff810b06db: parse_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
char *parse_args(const char *doing, char *args, const struct kernel_param *params, unsigned int num, s16 min_level, s16 max_level, void *arg, int (*unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:161
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:parse_early_options
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff810c162d-ffffffff810c16d0: parse_args.cold (STB_LOCAL)
ffffffff810c10f0-ffffffff810c1410: parse_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
char *parse_args(const char *doing, char *args, const struct kernel_param *params, unsigned int num, s16 min_level, s16 max_level, void *arg, int (*unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:161
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - init/main.c:parse_early_options
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff810c9a5d-ffffffff810c9b00: parse_args.cold (STB_LOCAL)
ffffffff810c9520-ffffffff810c9840: parse_args (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*unknown)(char *, char *, const char *, void *)</code> ➡️ <code>parse_unknown_fn unknown</code>
</li>
</ul>
</details>
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
